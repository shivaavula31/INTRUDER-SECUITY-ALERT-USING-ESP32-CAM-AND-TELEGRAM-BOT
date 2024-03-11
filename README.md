# INTRUDER-SECUITY-ALERT-USING-ESP32-CAM-AND-TELEGRAM-BOT
- make sure that you had gone through the changes to be made in the code like wifi name and password,chat bot id,token number.
- make sure that the name of the folder and name of the ".ino" file should be same.
  
## tools and board setup 
- same as the tools and board setup that is used in the project "Camera_Web_Server" in my repository.

## Telegram bot id and token number generation
- open telegram application
- search and open "Get ID Bot" channel and type "/start" then you will get chat id 
- search and open the "BotFather" channel
- type "/start"
- type "/newbot"
- name your bot
- then go back and search for the bot you have created
- open the bot that you have created and type"/start"
- now when you boot the ESP32 cam the images are captured due to the motion detection near the PIR sensor
- these photos captured are sent to the telegram bot channel you had created in telegram.
