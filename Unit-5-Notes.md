# Unit 5: On The Fly: Part 1

## Step 0

- It might be worth clarifying that `npm init -y` should be run in the `server/` directory in the case that the student creates `server.js` inside `server/` using right click instead of via the terminal. Otherwise, `package.json` is created outside of the directory and using `npm start` will result in an error. (Minor)

## Step 1

- Format in this instruction is probably missing a backtick: In the database.jsfile, import thepgpackage and thedotenv.js` file. (Minor)

## Step 2

- It's worth reminding students to have a `.gitignore` and add `node_modules` and `.env` to it.

## Step 7

- Copy excerpt for `updateTrip()` is written with `getTrip` (Minor)
- Copy excerpt for the SQL query in `results` is missing backticks and the number 7 for the seventh parameter. (Minor)
  - Either backticks should replace single quotation, or backslashes added like they are in Checkpoint 6. Backticks would be consistent with the rest of the lab. (Minor)

## Step 8

- Copy excerpt for SQL query in `activity_deletion` is missing backticks. (Minor)

## Step 9

- Instructions indicate that the endpoint should include '/api/' in front of the trips endpoint, but Checkpoint 8 does not include it. (Minor+)

## Step 11

- Students should be notified to download and configure Postman _before_ starting the lab.
