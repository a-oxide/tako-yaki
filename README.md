# Archive Notice
After a couple years of usage, my server hosting proivder (Heroku) has decided to remove their free plan. As I don't regularly use this bot, I have decided to take it offline and archive this repository. The code should still be functional, however I cannot provide any guarantees or active support. Thank you to healzer for the idea and the documentation to help me make this project a reality. 

## Takoyaki
Tako-yaki, or Tako for short is an audio playing and voice recognition tool developed using the DiscordSpeechBot and the AI speech data provided by Nigiri-private.  Currently Tako only can be used as a Discord Bot or directly through Dialogflow.

## Annoucements
Version 1.0.4 is live! Tako-yaki (should) now be functional again after the ytdl search algorithm stopped working suddenly. Tako should continue to be supported for a minimum of 6 months, with greater uptime and automatic bug fixing!

## Approved Usage
Currently Tako-yaki is only approved for usage on the official Nigiri Testing Discord. Feel free to make a fork if you'd like to modify it for usage in your own server.

## Usage
Available commands can be listed with the command `$help`  
You can summon Tako to current voice channel with `$join`  
You can remove Tako from your voice channel with `$leave`  

### Voice commands
Tako uses active learning as well as the wit.ai API to interpret speech.  
You can use Tako as you would use any other virtual assistant, by saying his key phrase: `tako`  
Examples:  
```
tako help
tako play [input]
tako pause
```
### Remember:
There should be little sound before and after the command until it is fulfilled.
## Developer to-dos
Create a more complex ytdl search algorithm to sift out music videos and false results.  
Find a way to automatically train wit.ai.  
Import the entirity of data from Nigiri.  
