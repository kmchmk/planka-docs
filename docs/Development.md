---
sidebar_position: 5
---

Clone the repository and install dependencies:

```
git clone https://github.com/plankanban/planka.git

cd planka
npm install
```

Either use a local database or start the provided development database:

```
docker-compose -f docker-compose-dev.yml up
```

Create `server/.env` based on `server/.env.sample` and edit `DATABASE_URL` if needed, then initialize the database:

```
npm run server:db:init
```

Start the development server:

```
npm start
```

Demo user: demo@demo.demo demo
