*lightning
`Fn + f10`
*set screen brightness
`xrandr | grep " connected" | cut -f1 -d " "` to find your monutor's name
`...output >>> VGA-1`
`xrandr --output yourmonitoname --brightness brightnesslevel` the brightness level must be between 0 to 1 with 0 being the  dimmest and 1 being the brightest.

