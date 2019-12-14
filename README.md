# nagIOS
nagIOS installation


sudo apt-get remove --purge 'mysql-.*'  <br /> 
sudo apt-get purge --auto-remove mariadb-server  <br /> 

cd /tmp  <br /> 
wget https://assets.nagios.com/downloads/nagiosxi/5/xi-5.5.11.tar.gz  <br /> 
tar xvf xi-5.5.11.tar.gz  <br /> 
cd nagiosxi  <br /> 
sudo ./fullinstall  <br /> 
