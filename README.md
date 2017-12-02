# ConjurDependencies
sudo yum groupinstall 'Development Tools'
sudo yum install gcc-c++ patch readline readline-devel zlib zlib-devel
sudo yum install libyaml-devel libffi-devel openssl-devel make
sudo yum install bzip2 autoconf automake libtool bison iconv-devel sqlite-devel
curl -sSL https://rvm.io/mpapis.asc | gpg --import -
curl -L get.rvm.io | bash -s stable
source /etc/profile.d/rvm.sh
rvm reload
rvm requirements run
rvm install 2.2.4
rvm use 2.2.4 --default
ruby --version
sudo yum install ruby-rdoc ruby-devel
yum install https://download.postgresql.org/pub/repos/yum/10/redhat/rhel-7-x86_64/pgdg-centos10-10-1.noarch.rpm
yum install postgresql10
yum install postgresql-libs
yum install postgresql-devel
sudo yum install yum-cron
sudo yum install openldap-clients
sudo yum -y install tzdata
