# Installing Webscreenshot
Source:

https://github.com/maaaaz/webscreenshot

pip install webscreenshot

# Installing PhantomJS

Source: 

http://www.vassox.com/linux-general/installing-phantomjs-on-centos-7-rhel/

yum install -y dnf

dnf install -y glibc fontconfig

yum install -y lbzip2

yum install -y fontconfig

yum install -y freetype

yum install -y wget

yum install -y bzip2

cd /opt

wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-linux-x86_64.tar.bz2

tar -xvf phantomjs-2.1.1-linux-x86_64.tar.bz2

ln -s /opt/phantomjs-2.1.1-linux-x86_64/bin/phantomjs /usr/local/bin/phantomjs

phantomjs --version




