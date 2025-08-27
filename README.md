CyberData - Global Fake Data Generator
CyberData Logo

A cutting-edge, AI-powered fake data generator with a cyberpunk aesthetic. Generate realistic fake data for testing purposes across multiple countries and data types.

🌟 Features
Multi-Country Support: Generate data from 20+ countries including USA, UK, Canada, Australia, Germany, France, Japan, China, India, Brazil, Russia, and more
Multiple Data Types:
Personal information (name, gender, birthday, SSN)
Address details (street, city, state, zip, coordinates)
Financial data (credit card details with CVV)
Customizable Output: Choose to generate all data or specific categories
Multiple Download Formats: Export data as JSON, PDF, or TXT files
Hacker-Style Watermark: All downloaded files include a custom watermark with usage restrictions
History Tracking: Keep track of your last 10 generated data sets
Responsive Design: Works seamlessly on desktop, tablet, and mobile devices
Cyberpunk UI: Neon-themed interface with animated backgrounds and grid overlays
🚀 Getting Started
Prerequisites
Modern web browser (Chrome, Firefox, Safari, Edge)
Internet connection (for loading external libraries)
Installation
Clone the repository:
bash

Line Wrapping

Collapse
Copy
1
git clone [https://github.com/yourusername/cyberdata.git](https://github.com/lezmehub/cyber-fakedata-generator)
Navigate to the project directory:
bash

Line Wrapping

Collapse
Copy
1
cd cyberdata
Open index.html in your web browser:
bash

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
7
8
# For macOS
open index.html

# For Windows
start index.html

# For Linux
xdg-open index.html
Usage
Select Country: Choose from the dropdown menu of supported countries
Select State/Province: Automatically populated based on your country selection
Select City: Choose from available cities in the selected state/province
Choose Data Type:
All Data (default)
Address Only
Person Only
Credit Card Only
Include SSN: Toggle to include/exclude Social Security Number
Generate Data: Click the "Generate Fake Data" button
View Results: Your generated data will appear with a typing animation effect
Download Data:
Select your preferred format (JSON, PDF, or TXT)
Click "Download All" to save the data with watermark
Copy Individual Fields: Use the copy button next to each data field
📸 Screenshots
Main Interface
Main Interface

Data Generation
Data Generation

Download Options
Download Options

Sample Watermark
Watermark

🛠️ Technologies Used
HTML5: Semantic markup and structure
CSS3: Advanced styling with animations and effects
JavaScript (ES6+): Core functionality and data generation
Bootstrap 5: Responsive grid system and components
Font Awesome: Icon library
jsPDF: PDF generation functionality
Google Fonts: Orbitron and Rajdhani for cyberpunk typography
📄 File Structure

Line Wrapping

Collapse
Copy
1
2
3
4
5
cyberdata/
├── index.html          # Main application file
├── README.md           # This file
├── assets/             # Static assets (if any)
└── docs/               # Documentation (if any)
🔧 Customization
Adding New Countries
To add support for additional countries:

Open index.html
Locate the countryData object in the JavaScript section
Add a new country entry with the following structure:
javascript

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
7
8
9
10
11
⌄
⌄
⌄
countryCode: {
    name: "Country Name",
    states: {
        "State1": ["City1", "City2", ...],
        "State2": ["City1", "City2", ...],
        ...
    },
    streets: ["Street1", "Street2", ...],
    phoneCode: "+XX",
    ssnFormat: "##-##-##-##"
}
Add the country to the countrySelect dropdown in the HTML
Customizing Watermark
To modify the watermark text:

Open index.html
Locate the downloadData() function
Update the watermarkText and ownerText variables:
javascript

Line Wrapping

Collapse
Copy
1
2
const watermarkText = "Your custom disclaimer text";
const ownerText = "Your custom owner name";
Styling Customization
The cyberpunk theme can be customized by modifying the CSS variables in the :root section:

css

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
7
8
9

}
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

⚠️ Disclaimer
Important: This tool generates fake data for testing purposes only. The generated data:

Is not real and should not be used for actual identification
Should not be used for fraudulent purposes
Is intended solely for software testing, development, and educational purposes
By using this tool, you agree to use the generated data responsibly and in compliance with all applicable laws and regulations.

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

📧 Contact
Created by Fetus - @fetus

Project Link: [https://github.com/yourusername/cyberdata](https://github.com/lezmehub/cyber-fakedata-generator)

🙏 Acknowledgments
Bootstrap for the responsive framework
Font Awesome for the icon library
jsPDF for PDF generation
Google Fonts for the cyberpunk typography
