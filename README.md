ALU RegEX Data Extraction Tool  
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
Setup Instructions
Clone the Repository:

git clone https://github.com/YourUsername/alu_regex-data-extraction-YourUsername.git cd alu_regex-data-extraction-YourUsername

Usage
Run the main script:
bashCopypython main.py
The tool provides two options:

Test with sample data
Enter custom text for pattern extraction

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

Credits:
Developer: Igornoel Email: n.ishimwe4@alustudent.com Role: Junior Full Stack Developer 
