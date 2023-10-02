Multilanguage Data Generation

# 📗 Table of Contents
1. [📖 About the Project](#-about-the-project)
2. [Tech Stack](#tech-stack)
3. [💻 Getting Started](#-getting-started)
   - [Installation](#installation)
   - [Usage](#usage)
     - [Generating Language-Specific JSONL Files](#generating-language-specific-jsonl-files)
     - [Consolidating Translations to JSON](#consolidating-translations-to-json)
4. [👥 Authors](#-authors)
5. [🤝 Contributing](#-contributing)
6. [⭐️ Show your support](#-show-your-support)
7. [🙏 Acknowledgements](#-acknowledgements)
8. [📝 License](#-license)
 

# 📖 About the Project

The "Multilanguage Data Generation" project entails creating distinct JSONL files for English, Swahili, and German in test, train, and dev sets, and consolidating English-to-other-language translations in a formatted JSON file.

## Tech Stack

- Python
- Visual Studio Code IDE

# 💻 Getting Started

To get a local copy up and running, follow these steps.

## Installation

1. Clone this repository to your desired folder using the following command:

   ```shell
   cd Group_CAT 
   git clone https://github.com/George-Stephen/Group_CAT

2. Set up your Python3 development environment using the following command:
   ```shell
   python -m venv env

3. Activate your Python3 development environment using the following command:
   ```shell
   env\Scripts\activate

4. Install all relevant dependencies using the following commands:
   ```shell
   pip install -r requirements.txt

## Usage

This project provides a set of tools and scripts to generate language-specific JSONL files and consolidate translations from English to other languages in a formatted JSON file.

### Generating Language-Specific JSONL Files

To generate language specific JSONL files for English (en), Swahili (sw), and German (de) in test, train, and dev sets, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone this repository to your desired folder:
   ```shell
   git clone https://github.com/George-Stephen/Group_CAT
   cd Group_CAT

3. Navigate to the data folder and place your input data files in the corresponding language directories (e.g., en, sw, de) inside the data folder.
4. Open a terminal or command prompt and navigate to the project's root directory.
5. Run the following command to generate the JSONL files for each language:
   ```shell
   python generate_jsonl.py

### Consolidating Translations to JSON
To consolidate translations from English to other languages into a formatted JSON file, follow these steps:

1. After generating the language-specific JSONL files, ensure they are available in the output directories.
2. Run the following command to consolidate translations:
   ```shell
   python consolidate_translations.py

3. The consolidated JSON file, named translations.json, will be created in the project's root directory.
   ```shell
   python consolidate_translations.py

# 👥 Authors

👤 Jackson Lowasa
      GitHub: @githubhandle

👤 George Steven
      GitHub: @githubhandle
      
👤 Charity Claire
      GitHub: @githubhandle

👤 Shaleen Ndirangu
      GitHub: @githubhandle

👤 Mwangi Patience
      GitHub: @githubhandle


# 🤝 Contributing

Contributions, issues, and feature requests are welcome!

# 🙏 Acknowledgements

Acknowledgements.

# 📝 License




















