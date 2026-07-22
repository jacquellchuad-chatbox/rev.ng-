# rev.ng-
rev.ng 
$ orc install --test revng
$ git clone https://github.com/revng/orchestra
Cloning into 'orchestra'...
$ cd orchestra
$ python3 -m pip install --user --force-reinstall https://github.com/revng/revng-orchestra/archive/master.zip
$ export PATH="$HOME/.local/bin:$PATH"
$ python -m venv venv
$ source venv/bin/activate
$ pip install --upgrade pip wheel certifi
$ pip install https://github.com/revng/revng-orchestra/archive/master.zip
