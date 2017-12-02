# ConjurDependencies
```ruby
sudo yum groupinstall -y 'Development Tools'
sudo yum install -y gcc-c++ patch readline readline-devel zlib zlib-devel
sudo yum install -y libyaml-devel libffi-devel openssl-devel make
sudo yum install -y bzip2 autoconf automake libtool bison iconv-devel sqlite-devel
curl -sSL https://rvm.io/mpapis.asc | gpg --import -
curl -L get.rvm.io | bash -s stable
source /etc/profile.d/rvm.sh
rvm reload
rvm requirements run
rvm install 2.3.1
rvm use 2.3.1 --default
ruby --version
sudo yum install -y ruby-rdoc ruby-devel
sudo yum install -y https://download.postgresql.org/pub/repos/yum/10/redhat/rhel-7-x86_64/pgdg-centos10-10-1.noarch.rpm
sudo yum install -y postgresql10
sudo yum install -y postgresql-libs
sudo yum install -y postgresql-devel
sudo yum install -y postgresql-server
sudo yum install -y yum-cron
sudo yum install -y openldap-clients
sudo yum install -y tzdata
sudo yum install -y rails
```
# Then, clone conjur, add config/database.yml, install postgres database gem install pg, gem pristine --all

# Also, gem install bundler, bundle --without test development website and rails server
