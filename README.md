# SpieMachine

SpieMachine is a drum machine and sampler developed using Pure Data. Physical implementation made with a Bela micro-computer.

## Features

For now, SpieMachine gives the user the ability to play, modify, and save 8 patterns. The user has the option to cycle through 8 different kits, or patches, 4 or which are pre-set, and the other 4 are made up of user-uploaded samples.

### Patterns

Patterns are created in real-time using `Record Mode`. To start `Record Mode`, press and hold the `Shift` button, then press the `Start/Stop` button.  The user will know they're in `Record Mode` when they hear the metronome begin. At this point, the user can tap-in the drum sounds for their sequence. To quict `Record Mode`, pres the `Start/Stop` button. 

To select a different pattern, hold `Shift` and `Menu` at the same time, then press one of the 8 `Sample` buttons.

### Kits

SpieMachine comes with 4 defauls kits; a Roland 707, 505, 808, and 909, loaded into slots 1 through 4 respectively. Users can add their own samples by adding a set of samples to samples directory in the build-in storage/ micro SD card in the unit. Samples must follow a specific naming convention in order to be read by the device: `[kit number][instrument name].wav`. Examples for kit 4 would be: `4Kick.wav`, `4Snare.wav`, `4CHat.wav`, etc. The instrument names are the same for each kit: Kick, Snare, CHat, OHat, Tom1, Tom2, Perc1, Perc2.