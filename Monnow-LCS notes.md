# Monnow-LCS notes

## Background

These notes describe the computing resources used in the sessions (6 for students, 1 for teacher development) and the ways in which the project creatively evolved as a pragmatic discourse between SL, RT, KMS, staff and particularly the students.

The document is written in [Markdown](https://daringfireball.net/projects/markdown/) — a plain text markup format. You can get the meaning of the file in a plain text editor (eg Notepad-Windows), but to get the full formatting, use a Markdown editor such as [Texts](http://www.texts.io/features/) on Windows, or one of the myriad of equivalents on macOS/iOS eg [Byword](https://bywordapp.com). There is a PDF equivalent provided also.

## Original concepts

The original concept was a strongly mobile-robotics centred one, which in full did not survive the initial planning sessions, but many of the underlying ideas did:

- exploring different kinds of sensors
- programming as a means of thinking about the world
- acting on the world with sounds, light

See my original thoughts document:

[Thoughts](files/Paper-1.pdf)

## Sessions

### Session 1

This session introduced the notions of 'Sense', 'Think', 'Act' to be used in creating creatures which can interact with the world.

 ![](images/Session1-map.png)

There were three activities:

- [Activity 1 (Act-light LEDs)](session%201/Activitity%201-Sense,%20Act.pdf) There'd been a quick intro. to what the Racket programming language looks like; students typed pre-defined commands into a Raspberry Pi to flash leds, use a PIR sensor (like a garage light sensor) to sense movement, and put the two togther to create a 'burglar alarm'.
- [Activity 2 (Sense-measure temperature)](session%201/Activity%202%20(Sense%E2%80%94measure%20temperature).pdf) A temperature probe on a Raspberry Pi was used to create a table of temperatures against time for a mug of warm water. We also tested the radiator temperatures in the room.
- [Activity 3 (Think-human robots)](session%201/Activity%203%20(Think%E2%80%94human%20robots).pdf) In this activity, one student pretends to be a robot, and another is the program which controls the robot. The students learned how surprisingly tricky it is to program a route for a robot. They also observed an autonomous Ras. Pi robot and tried to guess what rules it was obeying as it moved around the room.

### Session 2

We had a brief presentation at the beginning of the session to introduce working with microbits, and as with some other sessions showed a 'computing pioneer', Margaret Hamilton.

Two activities:

- [Activity 4-microbits talking](session%202/Activity%204.pdf) Introduces the idea that microbit can communicate over a built-in (Bluetooth) wireless network. We displayed the network activity of a couple of microbits on a central display. This enabled us to split the classroom into a grid and make a map of temperature and Bluetooth signal across the room.
- [Activity 5-Sonic Pi](session%202/Activity%205.pdf) We explored the possibilities of turning data into sound, for example in [hearing the weather](http://somenotes.stevelloyd.net/notes/2014/06/23/hearing-the-weather-sonification-in-sonic-pi/) resulting in [these sounds](http://somenotes.stevelloyd.net/resources/temperature.mp3) (in the event we used the sound generation of the microbits themselves, but knowledge of Sonic Pi is a great skill to have anyway).

### Session 3

We started off with a reflection on the previous week's activity and then introduced the [pxt](https://pxt.microbit.org) block JavaScript programming language).

