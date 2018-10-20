# NeuralBeats
We built this Neural Net to learn From MIDI files and generate its own songs live on Twitch!

## Instafluff ##
> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

> https://twitter.com/instafluffTV

## Credits ##
Thank you to all the participants of this project!

**Sorry to the folks that joined during the first part of this stream. We might have missed you because of a stream-restart!**
**MacabreMan2, Chlapicek99, Theoneandonlybigbadmo, Liayda, Kara_Kim, Instafriend, sparky_pugwash, Inventus1, OhMyGoogles, mrbillyk, losthewar, 0BuRner, ravavyr, Neo_TA, Polarami, thwoomp, nallaj, That_MS_Gamer, 6toez, TSM_Late, Instafluff, Replemish, wjplaud83, mrkinix, sethorizer, dyng89, realREAZN, Mromutt, Amarogine, TheSkiDragon, kingswerv, CrimsonKnightZero, DEAD_P1XL, Morwic, NyNzA**

## Instructions ##

1. Install NodeJS - [https://nodejs.org/en/](https://nodejs.org/en/)
2. Open the directory in a Command Prompt/Terminal
3. Install Dependencies: `npm install`
4. Get a Twitch Chat OAuth Password Token - [http://twitchapps.com/tmi/](http://twitchapps.com/tmi/)
4. Create a file named `.env` that looks like this:
```javascript
PORT=8000
TWITCHUSER=[YOUR-USERNAME-HERE]
OAUTH=[YOUR-OAUTH-PASS HERE] # e.g. OAUTH=oauth:kjh12bn1hsj78445234
```
5. Run Server: `npm start`
6. View the webpage from your web browser! [http://localhost:8000](http://localhost:8000)
