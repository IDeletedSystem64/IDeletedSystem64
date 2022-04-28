# notes.md
This is just a bunch of notes I'm putting here simply for the sake of accessing anywhere since I'm almost always able to access GitHub anyway.

# Passing things in Discord.JS
Example Code:

``client.commands.get(command).execute(message, args);``
<br>
You want to pass something to the command so you can more easily access it, <br> For example: ``client`` <br> You can achieve this by doing
``client.commands.get(command).execute(``**``client``**``, message, args, footer);``

# Naming links
Example Code: 

<br>

``[example](example.com)``