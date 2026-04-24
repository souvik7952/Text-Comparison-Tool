<h1>Text Comparison Tool (Pure HTML)</h1>

<p>
A lightweight, high-performance text comparison tool built entirely in a single HTML file with zero dependencies. 
It enables real-time side-by-side comparison with clear highlighting and synchronized scrolling for better readability and analysis.
</p>

<h2>Overview</h2>
<p>
This tool is designed for simplicity and efficiency. Users can paste two versions of text and instantly view differences 
without any manual action. It is optimized for handling large content while maintaining smooth performance and a clean user experience.
</p>

<h2>Features</h2>
<ul>
  <li>Real-time comparison without requiring a button</li>
  <li>Side-by-side layout for clear visual analysis</li>
  <li>Color-coded highlighting for:
    <ul>
      <li>Additions</li>
      <li>Deletions</li>
      <li>Modifications</li>
      <li>Unchanged content</li>
    </ul>
  </li>
  <li>Synchronized scrolling between both panels</li>
  <li>Central scroll control for unified navigation</li>
  <li>Line-by-line and word-level comparison</li>
  <li>Supports large text inputs efficiently</li>
  <li>Clean, modern, and responsive design</li>
  <li>Sticky headers for better context during scrolling</li>
  <li>Line numbering for improved alignment</li>
</ul>

<h2>Tech Stack</h2>
<ul>
  <li>HTML</li>
  <li>Embedded CSS</li>
  <li>Vanilla JavaScript</li>
</ul>

<p>No external libraries or frameworks are used. The tool runs entirely in the browser.</p>

<h2>How to Use</h2>
<ol>
  <li>Download or clone the repository</li>
  <li>Open the HTML file in any modern browser</li>
  <li>Paste text into both panels</li>
  <li>Differences will be highlighted automatically in real time</li>
</ol>

<h2>Use Cases</h2>
<ul>
  <li>Comparing API responses or JSON data</li>
  <li>Reviewing document revisions</li>
  <li>Debugging code or logs</li>
  <li>Validating configuration changes</li>
  <li>Content editing and proofreading</li>
</ul>

<h2>Key Implementation Details</h2>

<h3>Comparison Logic</h3>
<p>
The tool performs both line-level and word-level comparison to accurately detect differences while minimizing unnecessary re-rendering.
</p>

<h3>Performance Optimization</h3>
<p>
Debouncing is used to ensure smooth performance during continuous input, even with large datasets.
</p>

<h3>Scroll Synchronization</h3>
<p>
Both panels remain aligned through bidirectional scroll syncing, along with a central scroll control for improved usability.
</p>

<h2>Limitations</h2>
<ul>
  <li>Best suited for plain text comparisons</li>
  <li>Performance may vary with extremely large files depending on browser capabilities</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
  <li>Dark mode support</li>
  <li>Export comparison results</li>
  <li>Inline diff view</li>
  <li>Syntax highlighting for structured data</li>
  <li>File upload support</li>
</ul>

<h2>License</h2>
<p>This project is open-source and free to use.</p>
