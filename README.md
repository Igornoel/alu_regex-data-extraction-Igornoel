ALU Regex Data Extraction
A Python tool for extracting various data patterns from text using regular expressions.
Features
Extracts the following patterns:

Email addresses (e.g., user@example.com, firstname.lastname@company.co.uk)
URLs (e.g., https://www.example.com, http://subdomain.example.org/page)
Phone numbers (e.g., (123) 456-7890, 123-456-7890, 123.456.7890)
Credit card numbers (e.g., 1234 5678 9012 3456, 1234-5678-9012-3456)
Time formats (e.g., 14:30, 2:30 PM)
HTML tags (e.g., <div class="example">, <p>)
Hashtags (e.g., #example, #ThisIsAHashtag)
Currency amounts (e.g., $19.99, $1,234.56)

Installation

Clone the repository:

bashCopygit clone https://github.com/yourusername/alu_regex-data-extraction-Igornoel.git
cd alu_regex-data-extraction-Igornoel

Make sure you have Python 3.6+ installed.

Usage
Run the main script:
bashCopypython main.py
The tool provides two options:

Test with sample data
Enter custom text for pattern extraction

Example Usage in Code
pythonCopyfrom main import DataExtractor

extractor = DataExtractor()
text = "Contact us at support@example.com or call (123) 456-7890"
results = extractor.extract_data(text)
print(results)
Testing
The code includes built-in test cases that demonstrate various pattern matches. Run the tests by selecting option 1 in the main menu.
Regex Patterns
Email Addresses

Pattern: \b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b
Matches: Standard email formats including subdomains and various TLDs

URLs

Pattern: https?://(?:www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b(?:[-a-zA-Z0-9()@:%_\+.~#?&//=]*)
Matches: HTTP/HTTPS URLs with optional www, paths, and parameters

[Continue with other patterns...]
Contributing

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.