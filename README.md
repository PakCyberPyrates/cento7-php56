yum install epel*


yum update / yum upgrade


CentOS and Red Hat Enterprise Linux 6.x

wget http://rpms.famillecollet.com/enterprise/remi-release-6.rpm

sudo rpm -Uvh remi-release-6*.rpm


CentOS and Red Hat Enterprise Linux 7.x

wget http://rpms.famillecollet.com/enterprise/remi-release-7.rpm

sudo rpm -Uvh remi-release-7*.rpm

yum update / yum upgrade

yum --enablerepo=remi,remi-php56 update

yum --enablerepo=remi,remi-php56 upgrade

reboot

php -v
