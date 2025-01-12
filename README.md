# DiffectTool

A powerful Python-based GUI tool for detecting and visualizing differences between directories and files. Built with Tkinter and Python's difflib, this tool provides an intuitive interface for comparing content and structure.


## ✨ Features

- 📁 **Directory Structure Comparison**: View and compare entire directory structures side by side
- 📄 **File Content Comparison**: Compare text files with highlighted differences
- 🎨 **Visual Difference Highlighting**: 
  - Red: Files present only in left directory
  - Green: Files present only in right directory
  - Yellow: Files present in both with changes
  - White: Files present in both with no changes
- 📝 **Multiple File Format Support**: Compare PDFs, TXT files, and DOCX files
- 🖥️ **User-Friendly Interface**: Simple and intuitive file selection interface
- 🚀 **Command Line Support**: Launch with predefined paths using command line arguments

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/Mohammedaoudi/DiffectTool.git

# Navigate to the project directory
cd DiffectTool
```

## 💻 Usage

### GUI Mode
```bash
python diffect.py
```

### Command Line Mode
```bash
python diffect.py -p path1 path2
```

### Arguments
- `-p`, `--paths`: Two paths to compare (optional)

## 🖼️ Screenshots

### Initial View

![Initial Interface](https://github.com/user-attachments/assets/a4f3398e-f04d-4e06-9480-d0fc7726ea95)




### Directory Comparison

![Directory Comparison](https://github.com/user-attachments/assets/e92eb4a2-ac07-4cf6-b741-7264c21d1283)

### Text Comparison

![Text Comparison](https://github.com/user-attachments/assets/362aeda8-27ef-4f31-aff6-7c784d065186)


## 🔧 Technical Details

Built using:
- Python
- Tkinter for GUI
- difflib for comparison logic
- argparse for command line argument parsing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

[MIT License](LICENSE)

