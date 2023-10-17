# Alarm-Clock

This is a simple alarm clock application written in Python using the Tkinter library. It allows you to set a specific time for an alarm, and when that time is reached, it plays the specified alarm sound.

![image](https://github.com/pranavvangavety/Alarm-Clock/assets/115496999/377855b9-52a0-41df-b96a-e6551743c63b)


## Features

- Set a custom alarm time in hours, minutes, and seconds.
- Plays a sound when the alarm time is reached.
- User-friendly graphical interface provided by Tkinter.
- Uses multithreading to avoid freezing the application while waiting for the alarm.

## Dependencies

- [Tkinter](https://docs.python.org/3/library/tkinter.html): The Python standard library for creating graphical user interfaces.
- [pydub](https://github.com/jiaaro/pydub): A Python library for audio file manipulation. Please note that `pydub` relies on external tools like `ffmpeg` for audio format conversion.
