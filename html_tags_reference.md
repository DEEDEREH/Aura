# HTML5 Elements Reference Guide
# Structured by functionality with descriptions and examples.

=== DOCUMENT STRUCTURE & METADATA ===

* Tag: <!DOCTYPE>
  Description: Declares the document type.
  Example: <!DOCTYPE html>

* Tag: <html>
  Description: Root element of the page.
  Example: <html lang="en">...</html>

* Tag: <head>
  Description: Contains page metadata.
  Example: <head><title>Home</title></head>

* Tag: <title>
  Description: Sets browser tab title.
  Example: <title>My Website</title>

* Tag: <meta>
  Description: Defines page metadata.
  Example: <meta charset="UTF-8">

* Tag: <link>
  Description: Links external resources.
  Example: <link rel="stylesheet" href="style.css">

* Tag: <style>
  Description: Embeds internal CSS.
  Example: <style>body { color: red; }</style>

* Tag: <script>
  Description: Embeds or links JavaScript.
  Example: <script src="app.js"></script>

* Tag: <noscript>
  Description: Displays content if JavaScript is disabled.
  Example: <noscript>Please enable JavaScript.</noscript>

* Tag: <body>
  Description: Contains visible page content.
  Example: <body><h1>Hello World</h1></body>


=== LAYOUT & SECTIONING ===

* Tag: <header>
  Description: Header for a page or section.
  Example: <header><h1>Site Title</h1></header>

* Tag: <nav>
  Description: Contains navigation links.
  Example: <nav><a href="/home">Home</a></nav>

* Tag: <main>
  Description: Main content of the document.
  Example: <main><p>Core content here.</p></main>

* Tag: <section>
  Description: Defines a generic document section.
  Example: <section><h2>About Us</h2></section>

* Tag: <article>
  Description: Independent, self-contained content block.
  Example: <article><h2>Blog Post</h2></article>

* Tag: <aside>
  Description: Secondary sidebar content.
  Example: <aside><p>Sponsored links</p></aside>

* Tag: <footer>
  Description: Footer for a page or section.
  Example: <footer>&copy; 2026</footer>

* Tag: <div>
  Description: Generic content container.
  Example: <div class="wrapper">Content</div>

* Tag: <span>
  Description: Generic inline container.
  Example: <span class="highlight">Text</span>


=== TEXT & HEADINGS ===

* Tag: <h1> to <h6>
  Description: Text headings (Level 1 to 6).
  Example: <h1>Main Heading</h1>

* Tag: <p>
  Description: Paragraph element.
  Example: <p>This is a paragraph.</p>

* Tag: <br>
  Description: Line break.
  Example: Line one.<br>Line two.

* Tag: <hr>
  Description: Horizontal thematic rule.
  Example: <hr>

* Tag: <strong>
  Description: Bolds text with strong importance.
  Example: <strong>Warning!</strong>

* Tag: <b>
  Description: Bolds text for style without structural importance.
  Example: <b>Bold text</b>

* Tag: <em>
  Description: Emphasized text (typically italicized).
  Example: <em>Please hurry.</em>

* Tag: <i>
  Description: Italicizes text for style without structural importance.
  Example: <i>Italic text</i>

* Tag: <small>
  Description: Smaller side-comment text.
  Example: <small>Terms and conditions apply.</small>

* Tag: <mark>
  Description: Highlighted or marked text.
  Example: <mark>Highlighted text</mark>

* Tag: <del>
  Description: Deleted text with a strikethrough.
  Example: <del>Old price</del>

* Tag: <ins>
  Description: Inserted text with an underline.
  Example: <ins>New text</ins>

* Tag: <s>
  Description: Strikethrough for text no longer accurate.
  Example: <s>Out of stock</s>

* Tag: <u>
  Description: Underlined text.
  Example: <u>Unarticulated text</u>

* Tag: <sub>
  Description: Subscript text.
  Example: H<sub>2</sub>O

* Tag: <sup>
  Description: Superscript text.
  Example: E=mc<sup>2</sup>

* Tag: <abbr>
  Description: Defines an abbreviation with a hover title.
  Example: <abbr title="HyperText Markup Language">HTML</abbr>

* Tag: <q>
  Description: Inline short quotation.
  Example: <q>Be yourself.</q>

* Tag: <blockquote>
  Description: Block-level long quotation.
  Example: <blockquote>To be or not to be...</blockquote>

* Tag: <cite>
  Description: Title of a creative work.
  Example: <cite>The Great Gatsby</cite>

* Tag: <dfn>
  Description: Represents a defined term.
  Example: <dfn>HTML</dfn> is a markup language.

* Tag: <time>
  Description: Machine-readable date/time.
  Example: <time datetime="2026-08-18">Today</time>

* Tag: <address>
  Description: Author contact information.
  Example: <address>Phoenix, AZ</address>

* Tag: <bdo>
  Description: Overrides current text direction.
  Example: <bdo dir="rtl">This text runs right-to-left</bdo>

* Tag: <bdi>
  Description: Isolated text for bi-directional formatting.
  Example: <bdi>User123</bdi>

* Tag: <wbr>
  Description: Word break opportunity.
  Example: super<wbr>cali<wbr>fragilistic


=== LISTS ===

* Tag: <ul>
  Description: Unordered (bulleted) list.
  Example: <ul><li>Item</li></ul>

* Tag: <ol>
  Description: Ordered (numbered) list.
  Example: <ol><li>First</li></ol>

* Tag: <li>
  Description: List item.
  Example: <li>Item</li>

* Tag: <dl>
  Description: Description list.
  Example: <dl><dt>Term</dt><dd>Definition</dd></dl>

* Tag: <dt>
  Description: Term in a description list.
  Example: <dt>Coffee</dt>

* Tag: <dd>
  Description: Description in a description list.
  Example: <dd>Black hot drink</dd>


=== TABLES ===

* Tag: <table>
  Description: Creates a table.
  Example: <table>...</table>

* Tag: <caption>
  Description: Table caption title.
  Example: <caption>Monthly Sales</caption>

* Tag: <thead>
  Description: Groups header content.
  Example: <thead><tr><th>Month</th></tr></thead>

* Tag: <tbody>
  Description: Groups body content.
  Example: <tbody><tr><td>Jan</td></tr></tbody>

* Tag: <tfoot>
  Description: Groups footer content.
  Example: <tfoot><tr><td>Total</td></tr></tfoot>

* Tag: <tr>
  Description: Table row.
  Example: <tr><td>Data</td></tr>

* Tag: <th>
  Description: Table header cell.
  Example: <th>Name</th>

* Tag: <td>
  Description: Table data cell.
  Example: <td>John Doe</td>

* Tag: <colgroup>
  Description: Group of columns for formatting.
  Example: <colgroup><col span="2" style="background:yellow"></colgroup>

* Tag: <col>
  Description: Column properties within a colgroup.
  Example: <col style="background-color:red">


=== FORMS & USER INPUT ===

* Tag: <form>
  Description: Container for interactive input controls.
  Example: <form action="/submit">...</form>

* Tag: <input>
  Description: Interactive input field.
  Example: <input type="text" name="username">

* Tag: <textarea>
  Description: Multi-line text field.
  Example: <textarea rows="4"></textarea>

* Tag: <button>
  Description: Clickable button.
  Example: <button type="submit">Send</button>

* Tag: <select>
  Description: Drop-down selection list.
  Example: <select><option>Option 1</option></select>

* Tag: <optgroup>
  Description: Groups related drop-down options.
  Example: <optgroup label="Fruits"><option>Apple</option></optgroup>

* Tag: <option>
  Description: Option within a drop-down list.
  Example: <option value="1">One</option>

* Tag: <label>
  Description: Label linked to a form control item.
  Example: <label for="user">User:</label>

* Tag: <fieldset>
  Description: Groups related elements in a form.
  Example: <fieldset><legend>Login</legend></fieldset>

* Tag: <legend>
  Description: Caption for a fieldset.
  Example: <legend>Personal Info</legend>

* Tag: <datalist>
  Description: Pre-defined autocomplete options for inputs.
  Example: <datalist id="browsers"><option value="Chrome"></datalist>

* Tag: <output>
  Description: Displays calculation or script results.
  Example: <output id="result">100</output>

* Tag: <meter>
  Description: Scalar measurement within a known range.
  Example: <meter value="2" min="0" max="10">2 out of 10</meter>

* Tag: <progress>
  Description: Progress bar indicator.
  Example: <progress value="70" max="100">70%</progress>


=== EMBEDDED MEDIA & LINKS ===

* Tag: <a>
  Description: Hyperlink.
  Example: <a href="https://example.com">Visit Site</a>

* Tag: <img>
  Description: Embeds an image.
  Example: <img src="logo.png" alt="Logo">

* Tag: <audio>
  Description: Embeds audio content.
  Example: <audio src="song.mp3" controls></audio>

* Tag: <video>
  Description: Embeds video content.
  Example: <video src="clip.mp4" controls></video>

* Tag: <source>
  Description: Media source fallback option for audio/video.
  Example: <source src="audio.ogg" type="audio/ogg">

* Tag: <track>
  Description: Text tracks (captions) for video/audio.
  Example: <track src="subtitles.vtt" kind="subtitles">

* Tag: <embed>
  Description: Container for external apps or plug-ins.
  Example: <embed src="plugin.swf">

* Tag: <object>
  Description: External resource container.
  Example: <object data="file.pdf" type="application/pdf"></object>

* Tag: <picture>
  Description: Responsive image fallback wrapper container.
  Example: <picture><source srcset="large.jpg" media="(min-width: 800px)"><img src="small.jpg"></picture>

* Tag: <area>
  Description: Clickable hot-spot area inside an image map.
  Example: <area shape="rect" coords="0,0,82,126" href="sun.htm">

* Tag: <map>
  Description: Client-side image map container.
  Example: <map name="workmap"><area shape="rect" href="desk.html"></map>

* Tag: <iframe>
  Description: Nested inline window iframe browsing context.
  Example: <iframe src="https://example.com"></iframe>

* Tag: <param>
  Description: Parameters for an <object> tag.
  Example: <param name="autoplay" value="true">


=== CODE & TECHNICAL ELEMENTS ===

* Tag: <code>
  Description: Computer code text block.
  Example: <code>console.log()</code>

* Tag: <pre>
  Description: Pre-formatted text preservation block.
  Example: <pre>Line 1\n  Line 2</pre>

* Tag: <kbd>
  Description: Represents user keyboard input shortcuts.
  Example: <kbd>Ctrl + C</kbd>

* Tag: <samp>
  Description: Sample output from a computer program.
  Example: <samp>File not found.</samp>

* Tag: <var>
  Description: Represents a variable in math or programming code.
  Example: <var>x</var> = <var>y</var> + 2

* Tag: <data>
  Description: Links a machine-readable data translation to visible values.
  Example: <data value="2105">Product Name</data>


=== INTERACTIVE & DYNAMIC ELEMENTS ===

* Tag: <details>
  Description: Disclosure widget toggle tool.
  Example: <details><summary>Read More</summary>Hidden text</details>

* Tag: <summary>
  Description: Heading caption for a <details> element.
  Example: <summary>Click to Expand</summary>

* Tag: <dialog>
  Description: Dialog popup box window.
  Example: <dialog open>Hello!</dialog>


=== WEB COMPONENTS & TECHNICAL FRAMEWORK TEMPLATES ===

* Tag: <template>
  Description: Hidden markup container cloned via Javascript later.
  Example: <template><p>Dynamic Row</p></template>

* Tag: <slot>
  Description: Placeholder inside a shadow DOM element component.
  Example: <slot name="element-text">Default text</slot>