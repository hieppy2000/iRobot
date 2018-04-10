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

## Robotframework installation:
* pip install robotframework
* pip install robotframework-selenium2library (for python2.7)
* install Selenium2Library for python3: 
  * https://github.com/robotframework/Selenium2Library
  * pip install --upgrade --pre robotframework-selenium2library
* pip install robotframework-debuglibrary (https://pypi.python.org/pypi/robotframework-debuglibrary/0.8)
* pip install robotframework-lint   #error checking for .robot file (http://boakley.github.io/2014/11/30/robotframework-lint-preview/)


