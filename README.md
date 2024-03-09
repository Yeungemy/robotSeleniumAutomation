# ROBOT SELENIUM AUTOMATION
## Setup Robot Selenium Framework
### Uninstall old version: https://stackoverflow.com/questions/72005302/completely-uninstall-python-3-on-mac 
https://stackoverflow.com/questions/64362772/switching-python-version-installed-by-homebrew 
### Install python3: https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#python-installation 
### Download Python: https://www.python.org/downloads/ 
### Check version: python3 —version
### Install pip: https://stackoverflow.com/questions/17271319/how-do-i-install-pip-on-macos-or-os-x 
curl https://bootstrap.pypa.io/get-pip.py | python
sudo easy_install pip

### https://formulae.brew.sh/formula/pypy 
brew update && brew upgrade 
brew install python3
brew install pypy
Check python: pip3

brew unlink python@3.9
brew link --force python@3.9


Install pypy: https://formulae.brew.sh/formula/pypy or  https://www.pypy.org/download.html 
Run the the following commands to install Robot and Selenium Framework
python3 -m pip install --upgrade pip
pip3 install --upgrade robotframework
pip3 install --upgrade robotframework-databaselibrary
pip3 install --upgrade robotframework-pdf2textlibrary
pip3 install --upgrade robotframework-requests
pip3 install --upgrade robotframework-seleniumlibrary
pip3 install --upgrade robotframework-browser
pip3 install --upgrade pyodbc
rfbrowser init
pip3 list

Check:  robot --version