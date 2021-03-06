# Innovativeproject -Steal the Treasue Game
## Description

The project consists of two main parts:
 - Steal the Treasure - game using the Unity game engine
 - Map creator -  web application which allows you to create your own or random map for the game

## Installation

Clone repository from github
```
git clone https://github.com/nokia-wroclaw/innovativeproject-treasure-game.git
```

### Web-app

#### Application:
##### Prerequisites:
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Npm](https://www.npmjs.com/)

Start the app:
```
cd map_creator
npm install
npm start
```
#### Server:
##### Prerequisites:
- [Python 3.6.5](https://www.python.org/downloads/)
- [PyMongo](https://api.mongodb.com/python/current/)
- [DNSPython](http://www.dnspython.org/)
- [Flask](http://flask.pocoo.org/)

Start the server:
```
cd db\server
python server.py
```
Start the client:

```
cd db\server
python client.py maps
```

#### Game
Start the game:
```
cd unity
.\StealTheTreasure
```


## Technologies
### Web-app
* [React](https://reactjs.org/)
* [JavaScript](https://www.javascript.com/)
#### Database
* [MongoDB](https://www.mongodb.com/)
#### Server
* [Python 3.6.5](https://www.python.org/)
### Game
* [Unity](https://unity3d.com/)
* [Blender3d](https://www.blender.org/)



## Authors
- Mirka Pawłowicz
- Sebastian Łągiewski
- Jan Pajdak
- Wojciech Słowiński
- Łukasz Zatorki
- Filip Doroszkiewicz
