# DataLayer and Schema.org Extractor
A web-based tool to extract and analyze DataLayer implementations and Schema.org structured data from any website.

## Features

- Schema.org Scan: Extracts JSON-LD structured data, Microdata, and RDFa markup from HTML source
- DataLayer Scan: Simulates browser execution to capture dynamic DataLayer implementations
- Real-time Logging: Monitor extraction progress with detailed logs
- Formatted Output: Easy-to-read JSON display with proper formatting

How to Use
Enter a website URL in the input field

Choose your extraction method:

Schema.org Scan: For structured data analysis (SEO, metadata)

DataLayer Scan: For analytics and tracking implementation analysis

View the extracted data in the formatted display panel

Monitor the extraction process in the real-time log

Extraction Methods
Schema.org Scan
Extracts JSON-LD data from <script type="application/ld+json"> tags

Detects Microdata markup (itemtype attributes)

Identifies RDFa markup (typeof attributes)

Perfect for SEO analysis and structured data validation

DataLayer Scan
Simulates headless browser execution

Captures dynamic DataLayer content loaded via JavaScript

Monitors dataLayer.push() events

Ideal for Google Tag Manager and analytics implementation analysis

Technical Details
Built with vanilla HTML, CSS, and JavaScript

Uses CORS proxy for cross-origin requests

Responsive design that works on desktop and mobile

No external dependencies required

Live Demo
Simply open the index.html file in any modern web browser to start using the tool.

License
MIT License - feel free to use and modify as needed.
