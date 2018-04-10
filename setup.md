## Python Virtual environment 

1.  Install python virtual enviromment: 
    -  pip3 install virtualenv
2. Create python 2.7 or python 3.6 environment:
    - virtualenv -p <python-version> <desired-path>
    - virtualenv -p /usr/bin/python2.7 python27env
    - virtualenv -p /Library/Frameworks/Python.framework/Versions/3.6/bin/python3.6 python36env
3. Activate/Deactivate python virtual env:
    - source python36env/bin/activate
    - deactivate

## Robotframework installation: (Using Python 3)
* https://github.com/robotframework/SeleniumLibrary#installation
* http://robotframework.org/robotframework/3.0.3/RobotFrameworkUserGuide.html#installation-instructions

* pip install robotframework
* pip uninstall robotframework
* pip install --upgrade robotframework
* pip install --upgrade robotframework-seleniumlibrary
* pip install robotframework-debuglibrary (https://pypi.python.org/pypi/robotframework-debuglibrary/0.8)
* pip install robotframework-lint   #error checking for .robot file (http://boakley.github.io/2014/11/30/robotframework-lint-preview/)

# NOKIA RED plugin for Eclipse
* https://github.com/nokia/RED
* Update Site: Click Help -> Install New Software -> Add and set address in Location to: 
  http://master.dl.sourceforge.net/project/red-robot-editor/repository

