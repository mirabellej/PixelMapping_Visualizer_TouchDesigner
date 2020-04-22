# PixelMapping_Visualizer_TouchDesigner
Included is a homebrew pixelmapping visualizer created using TouchDesigner. This visualizer automatically updates pixel layout based on input of matrix or strip dimensions. Animation UI elements include a moving gradient with slider for speed selection and a color picker for single color output. Animations are determined using a single color Constant TOP, animated gradient Ramp TOP, or Movie File Out TOP. Color values are interpreted for realtime previzualization or implementation. A DMX Out Chop is used to translate color values into DMX data and send this to the controller. This vizualizer can be used with single strand LEDs (WS2812, WS2813, APA102, etc.) or smaller matrixes.   

The visualizer is designed for use with the Advatek Pixlite 4 MK II controller, but any DMX controller can be used.
To output to your controller, make certain that the IP address of your controller and the IP address of your computer match what is listed in the DMX Out Chop. 
You can check for correct configuation using the Advatek Assistant Software which will warn you if your computer and controller are not on the same IP and prompt you to change them. You can confirm that your configuration is correct if the first three sets of numbers for the controller and computer are the same, and the last set of digits is unique. For example:
Computer IP: 10.02.02.82
Controller IP: 10.02.02.55

You will need to update the video files in each Movie File In TOP as these are not included in this repository due to file size constraints. I recommend using moving wallpaper videos, but any video with lots of colors and shifting patterns will do. 

Related tutorials:
https://www.youtube.com/watch?v=ShYYcr30vJw&t=3823s
https://www.youtube.com/watch?v=4-oPy4RFZK0
https://www.youtube.com/watch?v=CSKcfG4Q0o4
https://www.youtube.com/watch?v=KQ9x4VC1CQw
https://www.youtube.com/watch?v=qBKeXgYMDcY
https://www.youtube.com/watch?v=vIZq7tlfLgQ

