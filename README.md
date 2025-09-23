📊 Power BI Custom Visual
A custom Power BI visual built from scratch to extend reporting and dashboard capabilities.

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/06d7bdae-55f7-46a6-947b-2a48fef5bfe7" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/3a223ddb-aa1f-4652-ba9b-8e428e06166d" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/0fbd4d9f-ab26-4be7-81f6-7b34d59b480e" />

🚀 Features
Developed a Power BI Custom Visual using TypeScript, React, and D3.js.
Implemented a visual schema with properties (title, description, imagePath).
Added support for dynamic data binding and user interaction.
Configured Visual capabilities.json for fields, formatting options, and interactivity.
Built and packaged with the Power BI Visuals SDK.
Optimized for performance and reusability.

Tech Stack
Power BI Visuals SDK
TypeScript
React
D3.js
Node.js / npm

Project Structure
my-custom-visual/
│── .tmp/              # Temporary build files (ignored in git)
│── dist/              # Final packaged visual
│── node_modules/      # Dependencies
│── .vscode/           # Editor settings
│── capabilities.json  # Defines visual capabilities
│── visual.ts          # Main logic for rendering
│── visualSettings.ts  # Custom settings
│── pbiviz.json        # Config for packaging
│── package.json       # Dependencies & scripts
│── README.md          # Documentation

How I Built This (Step by Step)
Installed Power BI Visuals Tools (pbiviz) via npm.
Created a new visual project using the CLI (pbiviz new <visual-name>).
Defined schema & configuration in pbiviz.json and capabilities.json.
Implemented main rendering logic inside visual.ts.
Added React components for UI rendering.
Styled visual using CSS for clean presentation.
Tested visual with sample data in Power BI Desktop.
Packaged visual into .pbiviz format for deployment.

Installation
Clone this repository:
git clone https://github.com/com/manu367/powerbi_charts.git
cd powerbi_charts
Install dependencies:
npm install
Start development server:
pbiviz start
Import .pbiviz file into Power BI Desktop.

Author

👤 Manu Pathak
💼 Java + Power BI Developer
🔗 LinkedIn | GitHub | Portfolio
