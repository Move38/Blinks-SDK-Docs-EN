# Glossary
[Blinks API Reference](api.md) - full API reference

## Display
- setColor(color)
- setFaceColor(face, color)

## Colors
- makeColorRGB(red,green,blue)
- makeColorHSB(hue,sat,bri)
- dim(color, value)

## Defined Colors
RED, ORANGE, YELLOW, GREEN, CYAN, BLUE, MAGENTA, WHITE, OFF

## Button
- buttonPressed()
- buttonReleased()
- buttonSingleClicked()
- buttonDoubleClicked()
- buttonMultiClicked()
- buttonClickCount()
- buttonLongPressed()
- buttonDown()

## Communication
- setValueSentOnAllFaces(value)
- setValueSentOnFace(value, face)
- getLastValueReceivedOnFace(face)
- isValueReceivedOnFaceExpired(face)
- didValueOnFaceChange(face);
- isAlone();

## Time
- millis()
- Timer.set(duration)
- Timer.isExpired()
- Timer.getRemaining()

## Types
- byte
- word
- int
- long
- float
- double
- bool
- Color
- Timer

## Convenience
- FOREACH_FACE(f) { }
- COUNT_OF(array)
- FACE_COUNT
- MAX_BRIGHTNESS