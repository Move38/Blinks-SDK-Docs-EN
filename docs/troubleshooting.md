# Blinks Troubleshooting

## Error Codes

Your Blinks have the capability to tell you when something has gone wrong.  Below are a few blink patterns that your Blink may display when it has enoucntered an issue.

|			Flash Pattern 		| 		Description                 |
| 			------------- 		| 		-----------                 |
| 2 Red Flashes Every Second 	| [Low Battery](#low-battery)      |
| 3 Red Flashes Every Second 	| [Programming Error](#prog-error) |
| 4 Red Flashes Every Second 	| [Stack Overflow](#stack-overflow)|


## <a id="low-battery"></a>Low Battery

If your battery is running low, your blink will let you know with 2 red flashes after it wakes from sleep.  It is strongly advised you change the **CR2032** battery when this warning appears.  Instructions for battery changes may be found [here](http://forum.move38.com/t/how-to-replace-the-batteries/100/2).

## <a id="prog-error"></a>Programming Error

If an error occured while programming your Blink or while a Blink was attempting to recieve shared code from one it's neighbors, it will display a pattern of 3 red flashes repeatedly.  To resolve this, attempt the programming process again with the methods found in the [Quick Start Guide](https://move38.github.io/Blinks-SDK-Docs-EN/quickstart.html).  If the problem perists, visit the [forums](http://forum.move38.com) for more help. 

## <a id="stack-overflow"></a>Stack Overflow

A stack overflow in your program is indicated by 4 red flashes.  This error can occur for a variety of reasons, most commonly when your program uses up the Blink's very limited dynamic memory.  To fix this issue, review areas in your code where you oculd potentially save memory, such as [writing debug messages to flash](http://forum.move38.com/t/programming-tip-use-flash-memory/85).