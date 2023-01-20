# main-brain
Server code to be used for training as well as testing ideas before putting into production or another repo.

# The Process

1. Install [Node](https://nodejs.org/en/download/) - my current version is `v19.3.0`.

2. After creating a GitHub repo, I ran `npm init` in my console within the project directory. I then added additional installations as outlined below.

3. To start the server, run:  `node index.js`

## npm Packages To Install

1. nodemon via `npm install nodemon --save-dev` and added `"start": "node server.js",` and `"start:dev": "nodemon server.js",` to `package.json` **scripts**.

2. cors

3. dotenv

4. [express](https://expressjs.com/) via `npm install express`

5. knex

6. pg (since used for initial brain)
