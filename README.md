# RedisConf-Golang

### Description
A Golang script designed to populate sample business case A, B, C Configs in Redis. This enchancements save times and improves on quality.

### Basic requirement
```go version >= 1.16.5```

### Recommended IDE

{Visual Studio Code} + {Golang Extension}

### Set Up
A.  Install the following modules:

    go get github.com/go-redis/redis/v8
    go get github.com/joho/godotenv


B. Run using the following steps:

    cd src

C. Run build version after in the src directory
   
    ./main


### Features:
* Able to create and update Business config files A, B, C based on  Redis Key.
* Detect OS and path
* Allows single file per crawling instance in the config directorries
* Prevent empty folder and file content posting to Redis.
* Easy to use.
