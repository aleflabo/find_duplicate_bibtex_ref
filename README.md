## Duplicate BibTeX Finder

### Overview

This repository contains a Jupyter notebook that serves as a tool for identifying duplicate BibTeX items within a reference file. The purpose of this tool is to help prevent the accidental citation of the same reference multiple times in a document or research paper.

### Usage

1. **Upload BibTeX File:** Start by uploading your BibTeX file, which contains the references used in your document.

2. **Run the Notebook:** Execute the cells in the notebook to process the BibTeX file and identify any duplicate entries based on the reference names.

3. **Review Results:** The notebook will display a list of reference names that have multiple entries along with their corresponding IDs. Review this list to identify and resolve any potential duplicates.

### How It Works

The notebook uses Python to parse and analyze the BibTeX file. It checks for duplicates based on the reference names, allowing you to ensure that each reference is cited consistently throughout your document.

### Dependencies

The notebook relies on the following Python libraries:

- `bibtexparser`: For parsing and processing BibTeX files.

Make sure to install these dependencies before running the notebook:

```bash
pip install bibtexparser
```

### Note

Always backup your BibTeX file before making any changes. The tool is designed to assist in identifying potential duplicates, but manual review is recommended for accurate validation.

### License

This tool is provided under the [MIT License](LICENSE), allowing for open collaboration and modification.

Feel free to contribute to the development of this tool by submitting issues or pull requests.

Happy citing!
