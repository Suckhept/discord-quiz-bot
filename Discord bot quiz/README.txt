There are five errors at startup, but i'm fixing them right after message is sent. They're about creating polls subcommands.
You need to change token and bot owners in config.json file.
To change bot owners you need to enable developer mode in discord, right click on user and copy their id. Just write them like in example file: [1, 2, 3, 4, 5]
Owner roles are broken due to outdated api
You can view all subcommands using -help.
To see command usage just write them without args.
To change prefix edit config.json file in the application root.
Quiz and polls data stored in ./modules/quiz/data/[timestamp].json.
You can access last quiz or poll data with -quiz/-poll getresult command.
CreateEntry can't use emotes (Custom server emojis).
Entry answer should look like this: "Answer text;:wave:".
Manual editing is also available for quizes and polls in ./modules/quiz folder.