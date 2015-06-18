# count
Plays PWM files on Arduino through piezo speaker.

Most of the results came from the following page:

  http://highlowtech.org/?p=1963

I'm using the library mentioned there. count.ino is my sample sketch. As the web site mentions the audio comes out on Digital I/O pin 11. I've tested with both a piezo buzzer and a 4 ohm speaker. I'm really impressed. It does mess with some of the PWM timers so this may not be suitable for all applications.

I used Audacity to convert the sample wave files I was provided into PWM.
