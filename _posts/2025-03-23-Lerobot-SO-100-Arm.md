# Building and Customizing the LeRobot SO-100 Robotic Arm

Hello everyone! Today I'm excited to share my experience with building the [LeRobot SO-100](https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md) robotic arm. This project utilizes 3D printing, robotics, and mechanical design in an fun and engaging way.

![assembling arm](/assets/images/AssemblingSO100.jpeg)

## Demo video
Here is a demo of the arm picking up a bottle of acrylic color and moving it!

[DEMO VIDEO](https://youtu.be/WWh0zzEwcjU)

![](/assets/images/So100DemoVideoScreenshot.png)

## Initial Build Process

I started by 3D printing the follower arm using translucent orange PETG filament. I chose PETG over PLA for several reasons, but it came down to the superior heat resistance and strength. It took roughly a day to print all parts.

## Assembly Experience
In order to assemble the arm and wireup the electronics, I used both the [instructions on GitHub](https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md) and the [video instructions](https://www.youtube.com/watch?v=FioA2oeFZ5I), but I preferred the video instructions due to the smooth animations.

The assembly process was pretty smooth. There were a few bugs on windows that I ran into, but nothing too serious. It took me about about 2 hours to assemble the arm fully.

## Features and Capabilities

The LeRobot SO-100 offers several impressive features, primarily the multiple degrees of freedom, as well as the open source design which allows for easy modifications.

I used [Phosphobot](https://github.com/phospho-app/phosphobot/) to control the arm. It is possible to record and replay sequences with it, and control the arm with computer keyboard.

## Future Enhancements

I have several exciting plans to enhance this robotic arm. I will add more body segments to give the arm better reach. I will also model new claw designs for specialized applications, like picking up thin objects, which the current design has trouble doing. I will also add a camera to allow AI vision control over the arm.

Stay tuned for updates on these modifications and their performance!