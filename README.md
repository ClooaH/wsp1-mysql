# wsp1-mysql

## Starta server

Kör ubuntu

kör:

  sudo service mysql restart

  sudo service apache2 restart
  
om apache2 är en bicc; tjänster -> apachebranch och stoppa

## viktigt, apache2 är port 88 så localhost:88

## MYSQL

**setup**
kör
	sudo mysql -u root
	
	grant all privileges on *.* to 'adam'@'localhost' identified by 'password';
