# sequelize-aws-x-ray

The `sequelize-aws-x-ray` module is a [`Sequelize`](http://sequelizejs.com/) extension for [AWS X-Ray](https://aws.amazon.com/xray/).

Subprojects:
- [sequelize-aws-x-ray-mysql](https://github.com/shun-tak/sequelize-aws-x-ray-mysql)
- [sequelize-aws-x-ray-mysql2](https://github.com/shun-tak/sequelize-aws-x-ray-mysql2)
- [sequelize-aws-x-ray-pg](https://github.com/shun-tak/sequelize-aws-x-ray-pg)

## Installation

MySQL (with mysql module)
```
npm install --save sequelize-aws-x-ray-mysql
```

MySQL (with mysql2 module)
```
npm install --save sequelize-aws-x-ray-mysql2
```

PostgreSQL (with pg module)
```
npm install --save sequelize-aws-x-ray-pg
```

## Usage

MySQL (with mysql module)
```
var Sequelize = require('sequelize');

var db = new Sequelize({
    dialect: 'mysql',
    dialectModulePath: 'sequelize-aws-x-ray-mysql',
});
```

MySQL (with mysql2 module)
```
var Sequelize = require('sequelize');

var db = new Sequelize({
    dialect: 'mysql',
    dialectModulePath: 'sequelize-aws-x-ray-mysql2',
});
```

PostgreSQL (with pg module)
```
var Sequelize = require('sequelize');

var db = new Sequelize({
    dialect: 'postgres',
    dialectModulePath: 'sequelize-aws-x-ray-pg',
});
```
