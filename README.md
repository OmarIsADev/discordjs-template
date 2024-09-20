# Welcome to my `Discord.js` template

### Setup

run `npm install`
create `.env` and add the following:
- `BOT_TOKEN`
- `CLIENT_ID`
- `MONGO_URI` *optional remove the connect function at `./server.js`*


to run server `npm run dev` *uses nodemon*
to publish commands run `npm run commands`

### This template is route based
- `./src/commands` to add commands
- `./src/events` to add events create new file with the name of the event such as: `guildMemberJoin` and etc.
