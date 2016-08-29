## escapce! spaceship! escape!
**a [collar.js](http://collarjs.com) game example**

You are a spaceship pilot, you accidentally entered an enemy territory. They fired several self guided missiles to shoot you down. Your mission is to do turn maneuver with your mouse to escape from these missiles. You can play with it from the following link. See how long you can last, and good luck! pilot :p

Play it directly:
> [slow motion](http://collarjs.com/examples/spaceship/index.html?rotate=7)
>
> [just for fun](http://collarjs.com/examples/spaceship/index.html?level=4&speed=7&rotate=7)
>
> [challenge yourself](http://collarjs.com/examples/spaceship/index.html?level=10&speed=7&rotate=7)
>
> [fast & furious](http://collarjs.com/examples/spaceship/index.html?level=10&speed=10&rotate=10)
>
> [god like](http://collarjs.com/examples/spaceship/index.html?level=10&invincible=1&speed=10&rotate=10)

## How to play

### browser
click and drag your mouse

### mobile
tap and move your finger

## Installation :

1. clone the repository
2. install http-server: `sudo npm install http-server -g`
3. run the server: `hs`
4. open `http://localhost:8080`

## Understand how it works

With collar.js, it is very easy to understand how your application works:

1. install collar-dev-server `sudo npm install collar-dev-server -g`
2. run collar-dev-server `collar-dev-server`
3. open collar dev tool in browser `http://localhost:7500`
4. open your game in browser and add paramter `dev=1` in the URL.
for example : `http://localhost:8080?dev=1&level=10&speed=7&rotate=7`
5. check collar dev tool at `http://localhost:7500`


## Cheat code:

### pick a level (higher the harder, default : 1)

`http://localhost:8080?level=<number>`

### set spaceship speed (default : 5)

`http://localhost:8080?speed=<number>`

### set spaceship rotation speed (default : 5)

`http://localhost:8080?rotate=<number>`

### set game width, default fit screen (only available on desktop)

`http://localhost:8080?w=800`

### set game height, default fit screen (only available on desktop)

`http://localhost:8080?h=600`

### enable invincible mode

`http://localhost:8080?invincible=1`


## Example:

Play a level 10 game with spaceship speed 7 rotation speed 7

`http://localhost:8080?level=10&speed=7&rotate=7`
