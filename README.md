# RedisConf-Golang

### Description
A Golang script designed to populate sample business case A, B, C Configs in Redis. This enchancements save times and improves on quality.

### Basic requirement
```go version >= 1.16.5```

### Recommended IDE

{Visual Studio Code} + {Golang Extension}

### Set up
A.  Install the following modules:

    go get github.com/go-redis/redis/v8
    go get github.com/joho/godotenv


B. Run using the following steps:

    cd src

C. Run build version in the src directory
   
    ./main

### Output
**Config files successfully upload to redis.**

_Rating: 1.00_
```
OS Detected:  MAC OS

Updating file A in ./business_case/A/ on Redis
Task1 completed successfully

Updating file B in ./business_case/B/ on Redis
Task2 completed successfully

Updating file C in ./business_case/C/ on Redis
Task3 completed successfully
```


**Partial config files upload to redis.**

_Rating: 0.75_
```
OS Detect:  MAC OS

Updating file A in ./business_case/A/ on Redis

Updating file B in ./business_case/B/ on Redis
Task2 completed successfully

Updating file C in ./business_case/C/ on Redis
Task3 Failed 
Reason: File content is empty for ./business_case/C/. Ensure to have valid content to update redis

```

**Failed config files upload to redis.**

_Rating: 0.00_

```
OS Detected:  MAC OS

Task1 Failed 
2021/10/14 12:26:22 Fatal error! unable to process empty folder: ./business_case/A/
Add a config file and try again.
```
### Features:
* Able to create and update sample config files A, B, C based on  Redis Key.
* Detect OS and path
* Allows single file per crawling instance in the config directorries
* Prevent empty folder and file content posting to Redis.
* Easy to use.

### Customize use
Feel free to reach me.

Or 

### Community contribution
If you are interested in contributing to improve this project; please, do either of the following:

* Open an [issue](https://github.com/taiwotman/flasklogin_neo4j/issues?q=is%3Aissue+is%3Aclosed)

* Fork repository

* Connect and chat me on [LinkedIn](https://www.linkedin.com/in/taiwo-o-adetiloye-ph-d-505a8023/)

