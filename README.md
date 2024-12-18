# compile-python
This is a repo for compiling and installing python from scratch

# Compile Python and Create VirtualEnv with It

'sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev'

'wget https://www.python.org/ftp/python/3.10.10/Python-3.10.10.tgz'

'tar zxvf Python-3.10.10.tgz'

'rm Python-3.10.10.tgz'

'cd Python-3.10.10/'

'./configure --enable-optimizations'

'make -j 4'

'make altinstall'
'sudo make altinstall'

# Create virtualenv and source

'cd ..'

'/usr/local/bin/python3.10'

'vim ~/.bashrc'
'alias python="/usr/local/bin/python3.10"'

'source ~/.bashrc'

'python -m venv ~/.venv'

'vim ~/.bashrc'

'source ~/.venv/bin/activate'