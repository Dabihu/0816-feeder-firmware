# 0816 automatic smt feeder controller firmware

This is the firmware needed to use the 0816 smt feeder. Find details on the feeder design, setup and features in [the wiki documentation](https://docs.mgrl.de/maschine:pickandplace:feeder:0816feeder)

![render of the 3dprintable automatic 0816 smt feeder](https://user-images.githubusercontent.com/3868450/34632854-34719c14-f278-11e7-8e8d-e245edc932fc.jpg)

[Watch a video showing the smt feeder in action](https://www.youtube.com/watch?v=vJzb3llKgjA)

## Modification:

### New commands:

#### M604:
Unload feeder (used on "0816 Feeder Redesigned")

#### M620:
S and R speed parameters -> [Speed control](SpeedControl.md)

#### M621:
Same as [M620](https://docs.mgrl.de/maschine:pickandplace:feeder:0816feeder:mcodes#m620set_feeder_config), without N parameter to modify all feeders in one command.

#### M622:
Change all feeders advance and retract angles to "0816 Feeder Redesigned" default parameters.

#### M630:
Get all feeders configuration (without N parameter) or one feeder configuration (with valid N parameter).
