**Text Comparison Tool (Pure HTML)**
A lightweight, high-performance text comparison tool built entirely in a single HTML file with zero dependencies. It enables real-time side-by-side comparison with clear highlighting and synchronized scrolling for better readability and analysis.

**Overview:**
This tool is designed for simplicity and efficiency. Users can paste two versions of text and instantly view differences without any manual action. It is optimized for handling large content while maintaining smooth performance and a clean user experience.

**Features:**
  Real-time comparison without requiring a button
  Side-by-side layout for clear visual analysis
  Color-coded highlighting for:
  Additions
  Deletions
  Modifications
  Unchanged content
  Synchronized scrolling between both panels
  Central scroll control for unified navigation
  Line-by-line and word-level comparison
  Supports large text inputs efficiently
  Clean, modern, and responsive design
  Sticky headers for better context during scrolling
  Line numbering for improved alignment
  
**Tech Stack:**
HTML
Embedded CSS
Vanilla JavaScript

No external libraries or frameworks are used. The tool runs entirely in the browser.

**How to Use:**
Download or clone the repository
Open the HTML file in any modern browser
Paste text into both panels
Differences will be highlighted automatically in real time
Use Cases
Comparing API responses or JSON data
Reviewing document revisions
Debugging code or logs
Validating configuration changes
Content editing and proofreading
Key Implementation Details

**Comparison Logic:**
The tool performs both line-level and word-level comparison to accurately detect differences while minimizing unnecessary re-rendering.

**Performance Optimization:**
Debouncing is used to ensure smooth performance during continuous input, even with large datasets.

**Scroll Synchronization:**
Both panels remain aligned through bidirectional scroll syncing, along with a central scroll control for improved usability.

**Limitations:**
  Best suited for plain text comparisons
  Performance may vary with extremely large files depending on browser capabilities
  
**Future Enhancements:**
  Dark mode support
  Export comparison results
  Inline diff view
  Syntax highlighting for structured data
  File upload support
  
**License:**
This project is open-source and free to use.
