# Palindrome Package
**This is a sample Python package by Elian Braja.**

**To upload this package:**
pip install build=0.8.0
pip install twine=4.0.1

python3 -m build (this creates the build filesin the dist directory)
twine upload --repository-url https://upload.pypi.org/legacy/ dist/*

The version of the package is taken from the pyproject.toml file. Make sure to change that 
before the build if you want to create a new version for the package.

Latest uploaded version: https://pypi.org/project/palindrome-elianbraja/0.0.2/

**To install the package:** 
pip install palindrome-elianbraja==0.0.2 OR
pip install palindrome-elianbraja --index-url https://test.pypi.org/simple/

**To use it:**
1. Enter the REPL
2. from palindrome-elianbraja.phrase import Phrase
3. Phrase("apple").ispalindrome()