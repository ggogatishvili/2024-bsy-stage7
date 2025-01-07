# Stage 7 - Echoes of the Darkness
Congratulations on reaching Stage 7!

The ring is gone, and the mountain trembles in its wake. Flames roar as the earth crumbles beneath you, but hope shines through the smoke. In the distance, the cry of mighty eagles echoes—salvation swoops from the skies. Hold on just a little longer; your journey is almost at its end.

Your final task is to code a Python bot and a controller that uses Bluesky for communication. The bot will run in the infected machine while the controller is used to send commands to the bot(s). Both parts should use Bluesky to communicate. You can register a free account and use it for the task. Do not use your existing personal account (if you have one). You can design your communication protocol within Bluesky, but it MUST BE PUBLIC (do not use DMs/Chats). The communication between the bots and the controller should not be easily detected as 'bots' in the feed. Therefore, all communication should look like regular English markdown or text (text, images, and emojis are accepted). You can also use some steganography techniques to hide your messages in English. Be aware of the Bluesky rate limits for the API.

Requirements:
1. Do not use your existing personal account if you have one.
2. Design and implement your protocol for the C&C communication. You have to use Bluesky as the C&C channel.
3. You MUST NOT use private chats for the C&C communication.
4. Your protocol should be hidden (not easily detected)
5. Minimal required functionality of the bots: a. announcing the presence of the bot to the controller if asked. b. listing users currently logged in the "infected" device (output of w command). c. listing content of a specified directory (output of ls command). The directory is a parameter specified in the controller's command. d. id of the user running the bot (output of id command). e. copying of a file from the infected machine to the controller (file path is a parameter specified by the controller). f. executing a binary inside the infected machine specified by the controller (e.g. /usr/bin/ps).
6. Provide sufficient documentation of your code: a. How to run the controller and the bot (we will test it manually) b. Requirements for your code (e.g., requirements.txt for pip install). c. Description of your custom C&C communication protocol
7. Both the controller and the bot must be able to run inside your Docker container.
8. Upload the code to GitHub and share it with the following teachers' accounts:
  - eldraco
  - HappyStoic
  - LukasForst
  - MariaRigaki
  - ondrej-lukas
  - verovaleros
  - msladic1
9. DO NOT PUBLISH your API keys and passwords!
10. Insert the repository URL as a flag in the CTFd.

Note: This stage can be opened in two ways. If you find the Stage 7 "Echoes of the Darkness (2)", you can solve only that one or this one.
## Solution

