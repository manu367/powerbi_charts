# Power BI Custom Visual 📊
A custom Power BI visual built from scratch to extend reporting and dashboard capabilities.


<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/06d7bdae-55f7-46a6-947b-2a48fef5bfe7" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/3a223ddb-aa1f-4652-ba9b-8e428e06166d" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/0fbd4d9f-ab26-4be7-81f6-7b34d59b480e" />

## 🚀 Features

* Developed a Power BI Custom Visual using **TypeScript**, **React**, and **D3.js**.
* Implemented a visual schema with properties (`title`, `description`, `imagePath`).
* Added support for dynamic data binding and user interaction.
* Configured `capabilities.json` for fields, formatting options, and interactivity.
* Built and packaged with the Power BI Visuals SDK.
* Optimized for performance and reusability.

## Tech Stack

* Power BI Visuals SDK
* TypeScript
* React
* D3.js
* Node.js / npm

## Project Structure
# Power BI Custom Visual 📊

A custom Power BI visual built from scratch to extend reporting and dashboard capabilities.

## 🚀 Features

* Developed a Power BI Custom Visual using **TypeScript**, **React**, and **D3.js**.
* Implemented a visual schema with properties (`title`, `description`, `imagePath`).
* Added support for dynamic data binding and user interaction.
* Configured `capabilities.json` for fields, formatting options, and interactivity.
* Built and packaged with the Power BI Visuals SDK.
* Optimized for performance and reusability.

## Tech Stack

* Power BI Visuals SDK
* TypeScript
* React
* D3.js
* Node.js / npm

## Project Structure

```plaintext
my-custom-visual/
|- .tmp/             # Temporary build files (ignored in git)
|-- dist/             # Final packaged visual
|-- node_modules/     # Dependencies
├── .vscode/          # Editor settings
├── capabilities.json # Defines visual capabilities
├── visual.ts         # Main logic for rendering
├── visualSettings.ts # Custom settings
├── pbiviz.json       # Config for packaging
├── package.json      # Dependencies & scripts
└── README.md         # Documentation
```

## How I Built This (Step by Step)

1.  Installed Power BI Visuals Tools (`pbiviz`) via npm.
2.  Created a new visual project using the CLI (`pbiviz new <visual-name>`).
3.  Defined schema & configuration in `pbiviz.json` and `capabilities.json`.
4.  Implemented main rendering logic inside `visual.ts`.
5.  Added React components for UI rendering.
6.  Styled visual using CSS for clean presentation.
7.  Tested visual with sample data in Power BI Desktop.
8.  Packaged visual into `.pbiviz` format for deployment.

## Installation

1.  Clone this repository:
    ```bash
    git clone [https://github.com/com/manu367/powerbi_charts.git](https://github.com/com/manu367/powerbi_charts.git)
    cd powerbi_charts
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start development server:
    ```bash
    pbiviz start
    ```
4.  Import `.pbiviz` file into Power BI Desktop.

---

## Author

**👤 Manu Pathak**

* 💼 Java + Power BI Developer
* 🔗 [LinkedIn](https://www.linkedin.com/in/manu-pathak-97b77918a/) | [GitHub](https://github.com/manu367) | [Portfolio](https://manu367.github.io/portfolio/)
