# Gen-Tool

A tool for generating README files from case data.

## 📋 Description

Gen-Tool is a Node.js utility that generates README files from case data stored in YAML files. It assembles content from template files in English.

## 🔧 Installation

```bash
# Clone the repository (if you haven't already)
# cd into the gen-tool directory
cd gen-tool

# Install dependencies
npm install
```

## 🚀 Usage

### Generate README

```bash
npm run generate
```

## 📁 Project Structure

- `src/` - Source code
  - `index.js` - Main script
  - `i18n/` - Internationalization files
- `templates/` - Templates for README generation
  - `README.md.md` - Main template
  - `en/` - English templates

## 🧩 How It Works

1. The tool reads numeric directories from the `cases` folder
2. It loads each case's YAML data
3. It processes the data and applies it to templates 
4. It generates the README.md file

## 📝 Note

This tool only processes directories with numeric names in the `cases` folder. Each of these directories should contain a `case.yml` file with case information and a image file.
