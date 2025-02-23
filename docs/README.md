<p align="center">
<img width=300px src="https://github.com/MrHerbalizer/logo-for-sema/blob/master/sema%20(off-white)%20shadow.png?raw=true" alt="">  
</p>

# About
Developer Rubric Discord Bot allows you to assess your skills with our [developer rubric](https://github.com/Semalab/developer-rubric) directly on Discord.  

A rubric is simply a scoring tool that identifies the various criteria relevant to an assignment or learning outcome, and then explicitly states the possible levels of achievement along a continuum (poor to excellent or novice to expert). Rubrics can be used to assess almost any type of student work, be it essays, final projects, oral presentations, or theatrical performances. There are four types of rubrics viz. Analytics, Developemental, Holistic and Checklists. 

Sema's [Developer Rubric](https://github.com/Semalab/developer-rubric) is a Developemental type rubrics tool that you can use to measure your current place in your development journey.  
This tool is designed to answer the question as to what extent are students who engage in the programs/services are able to develop a certain skill/ability/value/etc.

# Installation
Following is a step by step guide to set up Sema's Developer Ruberic Discord Bot with any discord server.

## Setting up discord bot:-

- Login to the Discord Developer portal and create a new Application.
- Add a bot to the Application after selecting "Bot" from the left-side panel.
- Copy the bot's token.
- Go to the `Oauth2` tab > `URL Generator` and select both `bot` and `applications.commandss` scopes, along with the `Administrator` permission. Copy the URL generated and invite the bot in your server.
- Copy the guild id of the server you invited the bot into.

## Setting up environment:

- Copy sample.env into .env  
``` 
cp sample.env .env  
```
- Paste the copied token from the discord developers portal as the value for the `BOT_TOKEN` variable.
- Paste the copied token from discord as the value for the `GUILD_ID` variable.

## Installing dependencies: 

```
npm install
```

## Building the Project:
```
npm run build
```

## Running the bot:
```
npm run start
```

## Running the bot in development mode, with file-reloading:
```
npm run start:dev
```
