# swaylock-effects-gif

Swaylock-effects-gif is a fork of [swaylock-effects](https://github.com/mortie/swaylock-effects)
which adds a --gif option. The chosen gif advances by one frame per keystroke, reverts by one frame on backspace and resets to the first frame of the gif on resetting (Ctrl+C), entering the wrong password or idling.

## Example Command

	swaylock --gif ~/Pictures/lockgif.gif \
		 --inside-color 00000000 \
		 --ring-color 00000000 \
		 --line-color 00000000 \
		 --indicator-thickness 0 \
		 -e --font-size 26 \
		 --text-color AAAAAAAA \
		 --inside-ver-color 00000000 \
		 --inside-clear-color 00000000 \
		 --inside-wrong-color 44FF0000

which works well with [this](https://media.giphy.com/media/UqwLwFj26GSyR968z6/giphy.gif) GIF.

## Additional dependencies

	*gtk
