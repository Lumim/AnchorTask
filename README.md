# AnchorTask Backend
Anchortask work of a day

npm install

#####################################
connect DB from config using mySql

#####################################
module.exports = {
  HOST: "localhost",
  USER: "root",
  PASSWORD: "",
  DB: "anchortask",   
  dialect: "mysql",
  pool: {
    max: 5,
    min: 0,
    acquire: 30000,
    idle: 10000
  }
};

########################
node server.js
