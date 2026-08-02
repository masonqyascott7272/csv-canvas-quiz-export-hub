# CSV to Canvas v— - Convert Quiz Spreadsheets for Canvas in 2026

> **CSV to Canvas turns quiz-question spreadsheets into Canvas-compatible QTI ZIP packages directly in your web browser. It handles several common question formats and performs conversion locally for offline use.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonqyascott7272/csv-canvas-quiz-export-hub?style=flat-square)](https://github.com/masonqyascott7272/csv-canvas-quiz-export-hub)

---

<p align="center">
  <a href="https://masonqyascott7272.github.io/csv-canvas-quiz-export-hub/">
    <img src="https://img.shields.io/badge/Download-CSV%20to%20Canvas%20Latest-brightgreen?style=for-the-badge" alt="Download CSV to Canvas">
  </a>
</p>

> **[Download CSV to Canvas](https://masonqyascott7272.github.io/csv-canvas-quiz-export-hub/)**

---

[Download Latest Build](https://masonqyascott7272.github.io/csv-canvas-quiz-export-hub/)

---

## What CSV to Canvas Does

CSV to Canvas gives instructors and course administrators a simpler way to move quiz material into Canvas. Enter questions and answers in a CSV file, open that file in the browser, review the resulting questions, and generate a QTI ZIP package for use with a Canvas Item Bank.

The application follows a browser-based workflow and does not require a separate service for conversion. It accepts multiple-choice, true/false, and multiple-response content, while included templates and sample files help you format new quiz data correctly. Files are processed locally on the device.

---

## Capabilities

- Turn CSV quiz records into QTI ZIP files formatted for Canvas
- Generate packages intended for Canvas Item Bank imports
- Handle multiple-choice, true/false, and multiple-response questions
- Inspect imported questions before producing the package
- Start from the supplied CSV templates or example files
- Use the application through a web browser
- Run without a build step or external dependencies
- Keep uploaded data on the device during processing

---

## Getting Started

CSV to Canvas can be used without installing packages or compiling the project.

1. [Download the latest build](https://masonqyascott7272.github.io/csv-canvas-quiz-export-hub/), or clone the repository:

   ```bash
   git clone https://github.com/masonqyascott7272/csv-canvas-quiz-export-hub.git
   cd REPO
   ```

2. Launch the project's HTML entry point in a current browser.
3. Open one of the provided CSV templates or create a file based on the example data.
4. Check the imported questions, then export the QTI ZIP package.

---

## Workflow

1. Start CSV to Canvas in your browser.
2. Select the CSV containing the quiz questions and answers.
3. Review the preview to confirm that the question text and answer formatting were read correctly.
4. Make sure each item uses one of the supported question types as intended.
5. Generate the QTI ZIP file.
6. Upload the resulting package to a Canvas Item Bank.

Using an included template as your starting point is recommended because it provides the expected column arrangement for quiz data.

---

## Input and Configuration

There are no build settings or dependency configuration files required for normal use. The selected CSV is the application's primary input.

Refer to the included templates and examples when organizing question text, answer choices, correct answers, and question types. Rather than using a separate settings file, CSV to Canvas takes its configuration from the imported CSV and the choices made during export.

---

## Requirements

- A current web browser
- A CSV file with quiz questions and answers
- Enough browser memory and storage to process the selected file
- No server runtime, package manager, or build tool
- Internet access only for downloading the application or repository; conversion itself runs in the browser

---

## Frequently Asked Questions

### What file does the tool produce?

CSV to Canvas creates a QTI ZIP package for import into a Canvas Item Bank.

### What question types can it convert?

Supported formats are multiple-choice, true/false, and multiple-response.

### Is there a way to check the questions before export?

Yes. The browser interface displays a preview of the imported quiz content before the QTI package is generated.

### How should my CSV be organized?

The included fillable templates and example CSV files show the expected structure. Use them to arrange your own questions, answers, and question-type fields.

### Do I need to build or install the application?

No. CSV to Canvas is an HTML-based browser utility and does not require dependency installation or a build process.

### Are uploaded files sent anywhere?

No. Conversion takes place in the browser, so uploaded data is not sent away from the device.

### What if the preview or Canvas import is wrong?

Compare the CSV against the supplied templates, check the question-type and answer fields, reload the corrected file, and inspect the preview again before exporting.

### How can I obtain a newer version?

Use the project link to download the latest available build, or visit the repository to look for newer releases and project changes.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
