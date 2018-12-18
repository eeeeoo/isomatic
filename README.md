# isomatic-cs320
a wearable that listens to your body by Jee Lee and Jessenia Aguilar-Hernandez



#


iSomatic is a wearable intended to bring more awareness to our bodily state while using music as a representation as well as a form to manipulate these different states. We gather bodily data through wearable technology in which we aim to make the wearables as fashionable, non-intrusive, and modular as possible. The bodily data is then translated to the music selection to enhance the wearers experience with their body and their biofeedback activity at hand. We designed the wearable to display led lights providing a visual representation of the temperature for social activities as well as for aesthetic. iSomatic not only allows for an exploration of body data leaving the control to the body, but also allows the user to get conscious control again by adjusting whether they’d like to “warm” or “cool” music. iSomatic has versatile use as it can be used for people who want to explore their physiology or try to affect it.

## Implementation

We used Adafruit Flora as our microcontroller, Adafruit Bluefruit, Adafruit Heart Monitor, Sparkfun Temperature Sensor, Adafruit Neopixels, Spotify, and AppleScript.

# 
The Neopixels serve as feedback to represent the body temperature as either hot or cold. According to the temperature, we use the Bluefruit to send data to a computer that runs an Applescript code that would trigger "hot" or "cold" music. The music would begin to play and would only change to reflect a change in temperature once a song has finished.

## Acknowledgments
We'd like to thank Orit Shaer (our Professor and Director of the Wellesley HCI Lab), Clarissa Verish (Research Fellow), and Diana Tosca (Research Fellow).
