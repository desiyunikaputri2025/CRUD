# CRUD
Project CRUD sedehana yang menggambarkan proses berjalannya data
# 1. Masukkan perintah npm init -y untuk membuat file package.json di folder Backend 
PS C:\Users\user\Documents\A Portofolio\CRUD\Backend> npm init -y
# Output
{
  "name": "backend",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}

# 2. Install MySQL client dan sequelize/Object Relational Mapping untuk relational database
PS C:\Users\user\Documents\A Portofolio\CRUD\Backend> npm i express mysql2 sequelize cors

# Output
added 101 packages, and audited 102 packages in 10s

18 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

# 3. Tambahkan type = module di bawah description
{
  "name": "backend",
  "version": "1.0.0",
  "description": "",
  "type": "module",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^5.1.0",
    "mysql2": "^3.15.0",
    "sequelize": "^6.37.7"
  }
}
# 4. Buat file index.js di dalam folder Backend
# 5. Install nodemon
PS C:\Users\user\Documents\A Portofolio\CRUD\Backend> npm install -g nodemon

added 29 packages in 4s

4 packages are looking for funding
  run `npm fund` for details

# 6. Test server running atau tidak
PS C:\Users\user\Documents\A Portofolio\CRUD\Backend> nodemon index
Debugger attached.
[nodemon] 3.1.10
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,cjs,json
[nodemon] starting `node index.js`
Debugger attached.
Server up and running...
Waiting for the debugger to disconnect...
[nodemon] clean exit - waiting for changes before restart


