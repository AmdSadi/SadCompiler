# SadCompiler
Online Compiler to run your code and save it
# Environment
This application is primarily built for POSIX platforms and compatible with Python 3.8 or higher. However, this application can be easily built for older python versions with minimal changes. Development dependencies are listed in setup.cfg.
```
python3.8 -m venv venv  # if not already created
source venv/bin/activate
pip install --upgrade pip
pip install wheel
pip install -e .[dev,test]