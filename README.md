# Python Notebook Project

## Overview
This project is designed to demonstrate various Python concepts through a series of Jupyter Notebooks and a Python package. It includes examples of data structures, control flow, error handling, and more.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd python-notebook-project
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
- The main application logic can be found in `src/main.py`. You can run this file to execute the primary functions of the project.
- The Jupyter Notebook `notebooks/Session_2_personal.ipynb` contains interactive code examples and visualizations. Open this file in Jupyter Notebook to explore the content.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

cd "c:\Users\An\Downloads\Course\Python Zero\python-notebook-project-1"

# optional: clear heavy outputs to keep commits small
jupyter nbconvert --clear-output --inplace notebooks\*.ipynb

# inspect changes
git status
git diff --name-only

# stage only modified notebooks (either specific files or the whole notebooks folder)
git add notebooks\Assignment1.ipynb notebooks\Session_2_personal.ipynb
# OR stage all notebooks in folder
git add notebooks\*.ipynb
# OR stage tracked modified files only
git add -u notebooks

# commit
git commit -m "Update notebooks: short description of changes"

# update local branch with remote (recommended) and push
git pull --rebase origin main
git push