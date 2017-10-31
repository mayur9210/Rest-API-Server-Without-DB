Rest API Server Without Database
=========

https://rest.now.sh/

Rest API Server Without Database, Data stored to files. No database requried


## Get Started

You must have nodejs install to run this 
```
  git clone https://github.com/mayur9210/Rest-API-Server-Without-DB.git
  
  cd Rest-API-Server-Without-DB

  npm install

  npm start  
```

## How it Works

1. **Creating new Item**
POST request : Post data should not have Id
  ```
  POST /users 
  ```

2. **Retrive all items**
  ```
  GET /users 
  ```

3. **Retrive item with id 1**
  ```
  GET /users/1 
  ```

4. **Modify Item  - Post/Put data must have matching ID**
  ```
  PUT or POST  /users/1
  ```

5. **Delete item**
  ```
  DELETE   /users/1
  ```



## Technologies


| **Tech** | **Description** |
|------------- | -------------|
|  [Node](https://nodejs.org/en/)  |   Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.   |
|  [Express](https://expressjs.com/)  |   Express is Fast, unopinionated, minimalist web framework for Node.js   |
