# stressbeat

Stress Beat is an interface that plays upon the
user perception of micro-timing and groove in
tandem with their physiological state. Tempo is
set by the user tapping their finger to the beat
of the desired tempo. A musical groove begins
playing to the set tempo, and the user’s real-time
changes in the heart rate adjusts micro-timing
of an individual component of a drum groove.
If the heartbeat is actively increasing, the given
component occurs behind the beat in relation to
the rest of the groove/tempo grid, and vice versa.


## Flow Chart
![alt text](https://github.com/nol-alb/stressbeat/blob/main/images/updateddiagram.png)

## User Interface
The user is provided with live audio feedback of
the beat with micro-timing variability applied.
In Max/MSP, the user interface also provides
several modes of visual feedback of their biosignals
and manual control. The tempo is displayed
numerically, as well as with a visual pulse. The
signal meter of the EMG input is displayed to
provide the user with feedback that their tapping
is being read by the system, and the cleanliness
of their input signal. The playing beat is also displayed
as a series of five blinking lights for the onset of musical events. The live heart rate is
displayed in real-time, along with another pulse
signifying the changes in heart rate that reflect
the microtiming within the groove.

![alt text](https://github.com/nol-alb/stressbeat/blob/main/images/Stress-Beat-UI.png)


