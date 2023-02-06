# FoodNinja
This repository includes the simulation enviroment used in our "*Towards a Knowledge Engineering Methodology for Flexible Robot Manipulation in Everyday Tasks*" Paper.

### Plugin Dependencies:
 - [UCutting](https://github.com/code-iai/UCutting)
 - [URoboSim](https://github.com/urobosim/URoboSim/tree/1255d628a4a58c84d3903d4b31c9943c38676923)
 - [URoboVision](https://github.com/robcog-iai/URoboVision)
 - [UROSBridge](https://github.com/robcog-iai/UROSBridge)
 - [UROSWorldControl](https://github.com/robcog-iai/UROSWorldControl)
 - [UTFPublisher](https://github.com/robcog-iai/UTFPublisher)
 - [UUtils](https://github.com/robcog-iai/UUtils)


### Pakaged Version
You can find a packaged Version of the Enviroment itself [here](https://seafile.zfn.uni-bremen.de/f/166270fc51fd4fe0acb4/).
**Disclaimer**:
The packaged Version is technically only the enviroment with the robot. As there are many different components used in order to simulate the Robot and not all of them are currently dockerized.
Usage:
To play around in the enviroment simple unzip the file provided and call the *sh* scripte located in the FoodNinja folder. 
```bash=
unzip -xzf FoodNinja.zip
cd FoodNinja
sh FoodNinja.sh
```
