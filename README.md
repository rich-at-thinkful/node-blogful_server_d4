# Setup

* `npm i`
* create `.env`
  - `PORT`
  - `NODE_ENV=developmen`t
  - `DB_URL`
  - `TEST_DB_URL`
  - `API_TOKEN`
* `postgrator-config.js`
  - set either `connectionString` or all db props
* Run migrations for dev and test db:
  - `npm run migrate`
  - `NODE_ENV=test npm run migrate`
