# alexa-device
enabling alexa device commands for mlb led scoreboard


This is based on a hypothetical that I would enjoy in terms of functionality. I currently have Alexa dev accounts and have built skills. It'd be nice to be able to say "Alexa, turn on the scoreboard" and the scoreboard turns on.

I realize there's a number of challenges associated with this issue, but it's a good opportunity for us to implement this feature. This is low on the totem pole for now.

Basically this sounds like you want an Alexa skill that runs a bash command, cause that's all that's needed to turn on the scoreboard.

"Alexa, turn on the scoreboard" => sudo python ~/insert_path/mlb-led-scoreboard/main.py
