[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/xDom7pvU)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17146216&assignment_repo_type=AssignmentRepo)
# lab6-converter (Now lab9)
# Vivethen Balachandiran
# 300245080

#### example 1 (curl on git bash)

$ curl -i -u user2:pass2 http://localhost:8080/temperature-converter/fahrenheit-celsius/150
% Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
Dload  Upload   Total   Spent    Left  Speed
100    17    0    17    0     0    142      0 --:--:-- --:--:-- --:--:--   142HTTP/1.1 200
Vary: Origin
Vary: Access-Control-Request-Method
Vary: Access-Control-Request-Headers
X-Content-Type-Options: nosniff
X-XSS-Protection: 0
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json
Transfer-Encoding: chunked
Date: Fri, 15 Nov 2024 00:55:46 GMT

65.55555555555556

##### example 2 (curl on git bash)

$ curl -i -u user1:pass1 http://localhost:8080/temperature-converter/celsius-fahrenheit/100
% Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
Dload  Upload   Total   Spent    Left  Speed
100     5    0     5    0     0     37      0 --:--:-- --:--:-- --:--:--    37HTTP/1.1 200
Vary: Origin
Vary: Access-Control-Request-Method
Vary: Access-Control-Request-Headers
X-Content-Type-Options: nosniff
X-XSS-Protection: 0
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Pragma: no-cache
Expires: 0
X-Frame-Options: DENY
Content-Type: application/json
Transfer-Encoding: chunked
Date: Fri, 15 Nov 2024 00:55:55 GMT

212.0
