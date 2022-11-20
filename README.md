# Node.js Express, Sequelize & PostgreSQL: CRUD Rest APIs

For instruction, please visit:
> [Node.js CRUD Rest APIs with Express, Sequelize & PostgreSQL example](https://bezkoder.com/node-express-sequelize-postgresql/)

More Practice:
> [Node.js Express Pagination with PostgreSQL example](https://bezkoder.com/node-js-pagination-postgresql/)

> [Node.js Express File Upload Rest API example](https://bezkoder.com/node-js-express-file-upload/)

> [Node.js Express File Upload with Google Cloud Storage example](https://bezkoder.com/google-cloud-storage-nodejs-upload-file/)

Security:
> [Node.js JWT Authentication & Authorization with PostgreSQL example](https://bezkoder.com/node-js-jwt-authentication-postgresql/)

Associations:
> [Sequelize Associations: One-to-Many Relationship example](https://bezkoder.com/sequelize-associate-one-to-many/)

> [Sequelize Associations: Many-to-Many Relationship example](https://bezkoder.com/sequelize-associate-many-to-many/)

Fullstack:
> [Vue + Node.js + Express + PostgreSQL example](https://bezkoder.com/vue-node-express-postgresql/)

> [React + Node.js + Express + PostgreSQL example](https://bezkoder.com/react-node-express-postgresql/)

> [Angular 8 + Node.js + Express + PostgreSQL example](https://bezkoder.com/angular-node-express-postgresql/)

> [Angular 10 + Node.js + Express + PostgreSQL example](https://bezkoder.com/angular-10-node-express-postgresql/)

> [Angular 11 + Node.js + Express + PostgreSQL example](https://bezkoder.com/angular-11-node-js-express-postgresql/)

> [Angular 12 + Node.js + Express + PostgreSQL example](https://bezkoder.com/angular-12-node-js-express-postgresql/)

Integration (run back-end & front-end on same server/port)
> [Integrate React with Node.js Restful Services](https://bezkoder.com/integrate-react-express-same-server-port/)

> [Integrate Angular with Node.js Restful Services](https://bezkoder.com/integrate-angular-10-node-js/)

> [Integrate Vue with Node.js Restful Services](https://bezkoder.com/serve-vue-app-express/)

---

&nbsp;

## Project setup
```
npm install
createdb tutorials-db
```

Also, rename `.env.example` to `.env` and change its environment variable values. If not, it will use hard-coded default values:
```
# Backend port, changed if you need.
PORT=8080

# CORS origin URL, changed if you need.
CORS_ORIGIN=http://localhost:8081

# Database connection configuration
DB_HOST=<your DB_HOST; otherwise, localhost>
DB_USER=<your DB_USER; otherwise, postgres>
DB_USER_PASSWORD=<your DB_USER_PASSWORD; otherwise, empty>
DB_NAME=<your DB_NAME; otherwise, testdb>
```

---
&nbsp;
### Run
```
node server.js
```
---
