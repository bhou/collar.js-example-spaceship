## escapce! spaceship! escape!
**a [collar.js](http://collarjs.com) game example**

You are a spaceship pilot, you accidentally entered an enemy territory. They fired several self guided missiles to shoot you down. Your mission is to do turn maneuver with your mouse to escape from these missiles. You can play with it from the following link. See how long you can last, and good luck! pilot :p

Play it directly:
> [slow motion](http://collarjs.com/examples/spaceship/index.html)
>
> [just for fun](http://collarjs.com/examples/spaceship/index.html?level=4&rotate=7)
>
> [challenge yourself](http://collarjs.com/examples/spaceship/index.html?level=10)
>
> [god like](http://collarjs.com/examples/spaceship/index.html?level=10&invincible=1&speed=10&rotate=7)

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

## Cheat code:

### pick a level (higher the harder, default : 1)

`http://localhost:8080?level=<number>`

### set spaceship speed (default : 5)

`http://localhost:8080?speed=<number>`

### set spaceship rotation speed (default : 5)

`http://localhost:8080?rotate=<number>`

### enable invincible mode

`http://localhost:8080?invincible=1`

## Example:

Play a level 10 game with spaceship speed 7 rotation speed 7

`http://localhost:8080?level=10&speed=7&rotate=7`
