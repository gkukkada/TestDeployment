# CRUD operations using spring boot with no backend database.

## How to download and execute without IDE help


open cmd / Terminal

```
git clone https://github.com/gkukkada/TestDeployment.git
```

then run following commands

```
cd TestDeployment
mvn install
mvn spring-boot:run
```

## TEST CASES:

### GET:
http://localhost:8082/RestServices/user/

![alt text](https://github.com/gkukkada/TestDeployment/blob/master/demo/GET.png)

### POST:
http://localhost:8082/RestServices/user/

body: 
{
    "name": "IRONMAN",
    "age": 27,
    "salary": 100000
}

![alt text](https://github.com/gkukkada/TestDeployment/blob/master/demo/POST.png)

### PUT:
http://localhost:8082/RestServices/user/5


body: 
{
    "name": "IRONMAN",
    "age": 90,
    "salary": 100000
}

![alt text](https://github.com/gkukkada/TestDeployment/blob/master/demo/PUT.png)

### DELETE:
http://localhost:8082/RestServices/user/5

![alt text](https://github.com/gkukkada/TestDeployment/blob/master/demo/DELETE.png)
