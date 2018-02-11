# ArcGIS Rest JS Commands

This demo shows how to create a command-line application that interacts with the ArcGIS Online API.

At this point, the commands are very simple and intended to demonstrate how to build up tooling.

This project uses the `commander` moodule, which streamlines the creation of node cli applications. Check out the [README](https://github.com/tj/commander.js/blob/master/Readme.md) for more details.

### Commands

| command | description | example |
| --- | --- | --- | 
| `ago search <query>` | search for items | `ago search water` |
| `ago export <id> <file>` | export an item to a json file | `ago export a62cb9d894f145cc89531c096d0012b1 pa.json` |
