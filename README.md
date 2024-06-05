To run backend dev server:

0. Prerequisite

- Install Node.js v18.x
- Install Yarn
- Install MySQL


1. Install node modules

```bash

cd backend


npm install
# or
yarn install

```

2. Create a database called `fieonix` in MySQL.


3. Migrate and seed database tables before running backend.

3.1. Running migration

```bash

npx sequelize-cli db:migrate
# or
yarn sequelize-cli db:migrate

```

3.2. Running seed

```bash

npx sequelize-cli db:seed:all
# or
yarn sequelize-cli db:seed:all

```


4. Start backend

```bash

npm run dev
# or
yarn dev

```

Then backend server runs on port 4100.