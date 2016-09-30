
## [Django 1.9 tutorial](https://docs.djangoproject.com/en/1.9/intro/tutorial01/)

### 0. init git & c9.io

    # make https://github.com/sdoro/tut19
    # start writing into README.md file
    git add README.md
    git commit -m "0. init git & c9.io"
    git push -u origin master
    # make a new workspace tut1 cloned from git@github.com:sdoro/tut19.git

### build a virtual environment with django 1.9

    sudo pip install virtualenv
    virtualenv $HOME/.env
    # make/edit requirements.txt
    git add requirements.txt
    source $HOME/.env/bin/activate
    pip install -r requirements.txt
    git add README.md
    git commit -m "1. build a virtual environment with django 1.9"
    git push

