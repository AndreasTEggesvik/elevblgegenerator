# Få motoren til å flytte seg
## Sett inn blokkene du trenger
Bruk blokken ``||basic:pause||`` og blokken ``||servos:Sett Vinkel På Servo||`` og plasser dem i gjenta for alltid blokken.
```blocks
basic.forever(function () {
servos.P0.setAngle(90)
basic.pause(100)
```
## Se at motoren flytter seg 
For å se dette må du ha minst to ``||servos:Sett Vinkel På Servo||`` blokker med ulik vinkel. Og du bør ha pause mellom hver av dem.