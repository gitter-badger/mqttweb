# mqttweb

Examples of how you have use IBM's Node-Red and IoT Foundation in your web apps.  Most examples are written using React.

Login - Just select a username and a device is created for you.  With this you are able to send mqtt messages to the server.

Highscore board - Just add a player and their score.  Will auto update for all users.

Chat - Send text and watch it update for all users.  By creating a Node-Red http endpoint that uses Watson Text to Speech, each chat message is automatically turned into audio.  Auto updates for all users
https://github.com/watson-developer-cloud/node-red-labs/blob/master/basic_examples/text_to_speech/tts_lab_basic.json

Image Analysis - analize an image - duh
https://github.com/watson-developer-cloud/node-red-labs/blob/master/advanced_examples/alchemy_image_analysis_thumbs/alchvis_lab_webfaces_thumbs.json
