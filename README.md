# Lesson Plan Generator (RPH)

A simple, powerful, single-page web application to quickly generate and customize daily lesson plans (Rancangan Pengajaran Harian - RPH) from a CSV file. This tool is designed to streamline the lesson planning process for teachers, allowing for bulk creation and easy printing.

![App Screenshot](https://i.imgur.com/wJyMQdD.png)

## Key Features

- **Bulk Import:** Populate lesson plans instantly by importing a `.csv` file.
- **Live Preview & Edit:** Navigate through all imported records and edit any field directly in the app. Changes are saved automatically.
- **Custom Color Schemes:** Change the color of headers and bubbles to personalize your lesson plans.
- **Print to PDF:** Generates a clean, paginated HTML page, ready to be printed or saved as a high-quality, text-selectable PDF using your browser's print function.
- **Fully Contained:** The entire application is a single `index.html` file with no server-side dependencies.

## How to Use

1.  **Prepare your data:** Create a spreadsheet with your lesson plan information. The column headers must match the format specified below. Export this file in `.csv` format.
2.  **Open the App:** Open the `index.html` file in any modern web browser.
3.  **Import:** Click **"Import CSV File"** and select the `.csv` file you created.
4.  **Customize:**
    -   Use the **"Prev"** and **"Next"** buttons to review each lesson plan.
    -   Click on any field to make edits.
    -   Use the color picker to change the theme.
5.  **Generate & Print:**
    -   Click the **"Generate Page"** button. A new tab will open with all your lesson plans.
    -   On the new tab, press `Ctrl+P` (or `Cmd+P`) and select **"Save as PDF"** as the destination.

## Required CSV Format

Your `.csv` file must contain the following headers. The order does not matter, but the names must match exactly.

No,Date,Day,Subject,Week,Class,Total student,Time,Period,"Content standard","Learning standard","Learning objectives","Success criteria","Pre-lesson","Lesson Development","Post Lesson",Reflection,"Strategi PDPC",EMK,BBM,KBATS,Pentaksiran,ABAD21,PETA
---

*Engineered with Gemini*
