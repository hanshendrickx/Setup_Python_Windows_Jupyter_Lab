#Setup Python Windows Jupyter Lab
This repository contains scripts and documentation for setting up a Python development environment on Windows with Jupyter Lab integration.

Repository Structure
Setup_Python_Windows_Jupyter_Lab/
│
├── scripts/
│   ├── folder_tree.py
│   ├── Setup_01_Prerequisites.bat
│   └── Setup_02_Python_Environments.bat
│
├── dashboard/
│
└── README.md


## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/hanshendrickx/Setup_Python_Windows_Jupyter_Lab.git
   cd Setup_Python_Windows_Jupyter_Lab

   scripts\Setup_01_Prerequisites.bat
   scripts\Setup_02_Python_Environments.bat
   scripts\Setup_02_Python_Environments.bat
   python scripts\folder_tree.py
   ## Project Components

### Prerequisites Script

The `Setup_01_Prerequisites.bat` script checks and installs:

- Windows version compatibility
- .NET Framework
- Git
- Visual Studio Code
- Required folder structure
- System environment variables

### Python Environments Script

The `Setup_02_Python_Environments.bat` script sets up:

- Python 3.12 and 3.13 installations
- Virtual environments
- Basic Python packages (Jupyter Lab, NumPy, Pandas, Matplotlib)
- Environment switching utilities

### Dashboard

The dashboard component will provide a web-based interface for data visualization and analysis. (To be implemented)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.


3. Commit these changes:

```bash
git add .
git commit -m "Add script contents and update README"

Create a new repository on GitHub:

- Go to [https://github.com/new](https://github.com/new)
- Name it "Setup_Python_Windows_Jupyter_Lab"
- Do not initialize it with a README, .gitignore, or license

Create a new repository on GitHub:

- Go to [https://github.com/new](https://github.com/new)
- Name it "Setup_Python_Windows_Jupyter_Lab"
- Do not initialize it with a README, .gitignore, or license



Connect your local repository to GitHub:

git remote add origin https://github.com/hanshendrickx/Setup_Python_Windows_Jupyter_Lab.git
git branch -M main
git push -u origin main

To verify, visit [https://github.com/hanshendrickx/Setup_Python_Windows_Jupyter_Lab](https://github.com/hanshendrickx/Setup_Python_Windows_Jupyter_Lab) in your web browser. You should see your repository with all the files we've created.