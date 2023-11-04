# AnchorTask Backend
Anchortask work of a day

npm install
db.config.js -> change -> and make a DB -> 
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


node server.js
