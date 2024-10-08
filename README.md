# 🎧 Morse Transmitter

Many headphones can send ⏮️ ⏸️ ⏯️ commands, such as Airpods, with a single press to pause or resume, double press to play the next track, and triple press to play the previous track.

Using this feature, we can use headphones as morse transmitters.

## Demo

[https://etherdream.github.io/headphone-morse-transmitter/](https://etherdream.github.io/headphone-morse-transmitter/)

https://github.com/user-attachments/assets/37cf43c2-ec2f-429a-b2b2-47a96a5ad242

## Usage

⏸️ = dit (.)

⏯️ = dah (-)

⏮️ = flush or backspace

When ⏮️ is pressed or `delay` time is reached from the last press, the `.` and `-` codes in the input buffer will be flushed.

If the input buffer is empty, pressing ⏮️ deletes the last char.

This program supports `Letter`, `Digit`, `Punctuation Mark` and `New Line` of 
[International Morse Code](https://morsecode.world/international/morse.html).

> Press the `dit` 8 times to delete the last line

## Keyboard

If you don't want to use a headphone, you can also use ⏮️ ⏸️ ⏯️ keys on your keyboard, which can even set a shorter delay, such as 500ms:

https://github.com/user-attachments/assets/6b51ff7e-8c3b-4607-8da6-8e6534e57c74

Alternatively, you can click ⏮️ ⏸️ ⏯️ buttons in the media control popup.

## Tips

This program can run in the background, even if the browser is minimized or the screen is locked. So you can use this program on your phone to practice Morse code, using only your fingers and ears, without eyes!

## Known Issues

Firefox is unstable on MacOS and Windows.

On MacOS, sometimes only one headphone can send commands (e.g. my AirPods right headphone works fine, but left headphone won't pause multiple times).

On Windows, sometimes the first ~0.5s of sound will be lost (even when saved to disk and played with player software, probably a buffer issue with the Bluetooth headphone), but Chrome works fine.
