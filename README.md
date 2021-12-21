# nttnoperations
This is a special project which I developed to create my own python package.\
The package is just about 4 basic operations in math: addition, subtraction, multiplication, division.\
More infomation at: https://pypi.org/project/nttnoperations/0.0.2/

### How to use?
Step 1: Run "pip install nttnoperations==0.0.2".\
Step 2: Create a python file and try to "import nttnoperations".

### Note: There are 4 operations supported:
+ addition: add_numbers(number1, number2).
+ subtraction: subtract_numbers(number1, number2).
+ multiplication: multiply_numbers(number1, number2).
+ division: devide_numbers(number1, number2).

### How to upload a package to Pypi?
Step 1: Prepare your package as shown in this project.\
Step 2: Register an account on https://pypi.org/ \
Step 3: Install required modules: setuptools, twine.\
Step 4: Open cmd in your package location.\
Step 5: Run "python setup.py sdist". (This command will generate 2 new folders named "dist" and "[your-package-name].egg.info").\
Step 6: Run "twine upload --repository-url https://upload.pypi.org/legacy/ dist/*" (This commnand will upload your package to Pypi).\
Step 7: After finish uploading, try install your package using pip as usual and then... ENJOY!
