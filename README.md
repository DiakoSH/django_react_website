# django_react_website

Prequisites for using Django and React to build a website:
    - Install and set up a local programming environment for Python 3
    - Install Node.js and Create a Local Development Environment

to do these:
    - Setting up python3
    - Setting up a virtual environment
    - Test
    - Installing node.js with apt from default repositories
    - Test

Setting up python3:
    - sudo apt update
    - sudo apt -y upgrade
    - python -V
    - sudo apt install -y python3-pip
    - sudo apt install -y build-essential libssl-dev libffi-dev python3-dev
    - pip install <package_name>

Setting up a virtual environment:
    - sudo apt install -y python-venv
    - mkdir environments
    - cd environments
    - python3 -m venv back
    - ls back
    - source back/bin/activate

Test:
    - vim hello.py
        - print ("Hello World :)")
    - python hello.py
    
