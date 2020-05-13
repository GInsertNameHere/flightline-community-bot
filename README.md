# Flightline Community Bot                     

[![Discord Members Online](https://discordapp.com/api/guilds/593830690777333770/embed.png)](https://discord.gg/XDsWaZq)

This repository hosts the code for the discord bot that is used by the Flightline Community.
This code, as of v3.3.0 includes:

- ATIS System that can be created by an ATC with the appropriate role.
- Holdqueue system that can be used by ATCs.
- ATC Login system which includes ATC Hour Count.
- Other minor commands that display additional information to the population of the server.

# Table of contents

- [Installation and setup](https://github.com/supraaxdd/flightline-community-bot/#installation-and-setup)
- [Support](https://github.com/supraaxdd/flightline-community-bot/#support)
- [Contributing](https://github.com/supraaxdd/flightline-community-bot/#contributing)
- [Acknowledgements](https://github.com/supraaxdd/flightline-community-bot/#acknowledgements)

## Installation and setup

The setup is quite easy to do.
First make sure you have [Node.js](https://nodejs.org/en/) (v12.X.X+) installed, which should come with the package manager "npm" by default.

Alongside that, make sure that you have a PostgreSQL server up and running. This repo will include a database setup file that will enable you to replicate the exact database structure as the main bot is using. 

_Placeholder for command execution_

Simply execute the following command inside of the project folder in your command line:

```bash
npm install
```

This will install all of the dependancies that are needed in order for the bot to work. The full list can be found in the package.json file. **The bot should be running on discord.js v12+ and Node.js v12.X.X+**

If everything was done correctly and you execute:
```bash
node . (OR: node index.js)
```

The following should show up in your Command line:

```

--------------------------------------------------------------------------------------------
Loading x commands:

All commands that were loaded.
--------------------------------------------------------------------------------------------
Connecting to database: [Database Name]
Connecting as: [Username]
Connecting to [Usually localhost:[port]]
Connected to Database...
--------------------------------------------------------------------------------------------
Bot is ready! Logged in as: [Bot Username]
Logged in on: [Bot Token]
Time Logged on: Mon Apr 20 2020 08:36:39 GMT+0100 (Irish Standard Time)
The prefix is: /
Below find the invite link should it be needed for the bot to be invited to another server:
[Link Generated]
--------------------------------------------------------------------------------------------
```

## Support

If you need help with anything, you should preferably contact JusSupra#6561 on discord or join the server by pressing on the small Discord image located just below the title. If that is not possible, feel free to open a new issue. Note that if the issue is invalid, it may be closed.

## Contributing

1. Feel free to Fork & Clone the repository and make sure that it is on the __master branch__ as that branch is the most up to date one and the most stable.
2. Run `npm install` in the project folder.
3. Make the changes that you want to propose and code whatever you want!
4. Make sure that everything is good shape and then feel free to create a [Pull Request](https://github.com/supraaxdd/flightline-community-bot/compare) which will be reviewed.

## Acknowledgements

Main Contributor: supraaxdd

Other Contributors which helped along the way:
- ADragonDood
- AircraftAnorak

