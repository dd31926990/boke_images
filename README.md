```
-i https://pypi.tuna.tsinghua.edu.cn/simple

sudo apt-get install virtualenv
sudo apt-get install virtualenvwrapper
mkdir ~/.myvirtualenvs
vim ~/.bashrc
export WORKON_HOME=/home/zhang/.myvirtualenvs
source /usr/share/virtualenvwrapper/virtualenvwrapper.sh
source ~/.bashrc
cd .myvirtualenvs/
mkvirtualenv -p /usr/bin/python3 spiders

pip install ipython
ipython
pip install requests -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip install scrapy -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip install lxml -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip list
pip install selenium -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip install scrapy-redis -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip install pymysql -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip install pymongo -i https://pypi.tuna.tsinghua.edu.cn/simple 
pip install redis -i https://pypi.tuna.tsinghua.edu.cn/simple 
```
。
