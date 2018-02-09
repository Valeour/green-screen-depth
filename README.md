# Green Screen Depth Shader
Green screen depth shader to be used with Reshade 3.1.1 by [Chance 'Valeour' Millar](https://twitter.com/ValeourM)

## [Download](https://github.com/Valeour/green-screen-depth/archive/master.zip)

![FFXIV Example](https://pbs.twimg.com/media/DUaJdo-WAAAkfyD.jpg)

Primarily made for FFXIV, should be able to be used with other games.

Contains two adjustable values;
- Green screen colour - Doesn't have to be green
- Depth cut off - This is how far away from the camera until the green screen kicks in.

Please ensure that ```RESHADE_DEPTH_INPUT_IS_REVERESED``` is not enabled in settings, or it will cause the shader to work incorrectly.

To install, simply place the GreenScreenDepth.fx in your shader folder of the game you installed Reshade on.

(Haven't tested with DX9. Maybe DX11 only.)
