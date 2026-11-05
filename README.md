# Pharma-Explorer-MK1
An interactive educational reference for exploring active pharmaceutical ingredients (APIs), pharmaceutical excipients, and chemical/pharmaceutical grades.

Pharma-Explorer is a browser-based prototype designed to make pharmaceutical ingredient information easier to navigate. It brings related concepts together in one interface, allowing users to explore APIs, review commonly associated excipients, examine selected formulation incompatibilities, and learn about different material grades.
Why This Project Started
The idea for Pharma-Explorer emerged during my internship at Negin Salamat Saba. While becoming familiar with pharmaceutical materials and the information used in the industry, I became interested in how that information could be organized and presented in a more accessible, connected way.

I saw an opportunity to build something that could help people explore pharmaceutical ingredients rather than treating each piece of information as an isolated entry. I wanted to connect active ingredients with the excipients used in formulations, highlight selected incompatibilities, and provide a place to learn about the grades and specifications associated with pharmaceutical and laboratory materials.

A university assignment gave me the opportunity to begin developing the concept. However, the motivation behind Pharma-Explorer was broader than completing an academic task: I wanted to turn a practical observation from my internship into a useful software project with educational potential.
Current Features
The original HTML version includes:
- API Explorer — Browse active pharmaceutical ingredients with their codes, categories, dosage forms, BCS classifications, explanations, common versions, fields of use, and typical excipient associations.
- Excipient Explorer — Explore excipients by code, name, category, and common pharmaceutical uses.
- API–Excipient Navigation — Follow links between an API and its associated excipients, or explore which APIs are associated with an excipient.
- Selected Incompatibility Notes — View formulation incompatibility examples and their explanations where they are included in the project data.
- Pharmaceutical & Chemical Grades — Review grade descriptions, stated purity ranges, intended applications, example compounds, and Persian-language explanations.
- Modified Excipients — Explore selected modified, co-processed, branded, or alternative versions listed for excipients.
- Search and Category Filtering — Find APIs and excipients by name, code, or category, and filter the displayed entries by category.
- Light and Dark Themes — Switch between light and dark display modes. The selected theme is saved in the browser's local storage.
- Shareable Item Navigation — The selected view and item are represented in the page URL hash, allowing supported selections to be linked or revisited.
- Responsive Layout — The interface adapts to narrower screens as well as desktop displays.
- English and Persian Content — The pharmaceutical-grade section includes Persian-language descriptions alongside its English content.
Data Included in This Version
The original HTML file currently contains:
Data group	Entries
Active pharmaceutical ingredients (APIs)	58
Excipients	60
Pharmaceutical and chemical grades	40
Modified excipient variants	176
Formulation incompatibility examples	5


These figures describe the data currently embedded in this HTML version. They are not a claim that the database is comprehensive.
Technology
This version is implemented as a self-contained web page using:
- HTML5 for page structure
- CSS3 for styling, themes, layout, and responsive behavior
- Vanilla JavaScript for data handling, search, filtering, navigation, and interactive components
- Browser Local Storage for remembering the selected display theme
There is no framework, package installation, build process, or backend server required to run this original version.
Getting Started
1. Download or clone this repository.
2. Keep the original Pharma-Explorer HTML file in the repository's root directory. For the simplest setup, name it index.html.
3. Open index.html in a modern web browser.
The project runs locally in the browser. No installation or additional dependencies are required.
Project Structure
The repository can be organized as follows:
Pharma-Explorer/
├── README.md
└── index.html
The original implementation contains the page markup, styling, JavaScript logic, and project data in a single HTML file.
Intended Use
Pharma-Explorer is intended as an educational and exploratory reference for:
- Pharmaceutical and related-field students
- People learning about APIs and excipients
- Researchers and professionals who want a convenient starting point for exploring ingredient relationships
- Anyone interested in pharmaceutical materials and formulation concepts
The project is a prototype and learning resource. It is not a validated pharmaceutical database, a regulatory reference, or a substitute for professional formulation review.
Important Disclaimer
Pharmaceutical information in this project is provided for educational and informational purposes only. The listed examples, grade descriptions, purity ranges, ingredient associations, and incompatibility notes may be simplified or incomplete and should be independently checked against current authoritative references, applicable pharmacopeial standards, manufacturer documentation, and qualified professional advice.

Do not use this prototype as the sole basis for formulation design, manufacturing, quality control, regulatory decisions, or patient-care decisions.
Current Status
This repository documents the original standalone HTML implementation of Pharma-Explorer. It represents an early working version of the concept and provides a foundation for future review, data validation, feature development, and possible expansion.

The current version should be understood on its own terms; planned features or future integrations are not represented as completed functionality here.
Pharma-Explorer — making pharmaceutical information easier to explore and understand.
