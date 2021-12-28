# VTSLivePlugins

Plugin for real-time movement of time, weather, sun and moon using [VTube Studio's API](https://github.com/DenchiSoft/VTubeStudio)!

## About

This plugin allows Vtube Studio to reflect the movement of analog and digital clocks, the movement of the sun and moon, and weather information from around the world.

This plugin is built using the [VTS-Sharp library](https://github.com/FomTarro/VTS-Sharp). Thank you!

If you use the hashtag [#VTSLivePlugin](https://twitter.com/search?q=%23VTSLivePlugin&src=typed_query) on Twitter when you use the plugin, the author may go to see it.

The author assumes no responsibility for any problems caused by this plugin.

If you have any questions, please contact me on [Twitter](https://twitter.com/fastest_yukkuri).

## Usage

### General

1. Download it by selecting "Download ZIP" from the "Code" button on Github.

2. Make sure the API communication of VTube Studio is turned on before launching the plug-in.Also, make sure that the port number is 8001.

3. Launch "VTSLivePlugins.exe" to start communication.When the plugin is launched, it automatically makes API connections and adds 14 custom parameters.

The parameters are updated once every 0.5 seconds.

Saves the configured state when the plugin is closed. When you reopen the plugin, you can start from the fully closed state.

See the "Help" section in the plugin for detailed instructions.

You can switch between Japanese and English.

### Time Clock

Output the parameters for running the digital and analog clocks, and set the smoothing setting in VTube Studio to 0.

You can set the analog and digital clocks. The maximum value of the analog clock parameter can be entered.

### Sun & Moon

Outputs parameters to determine the movement of the sun and moon, the phases of the moon, and day and night.

By entering the latitude and longitude, you can reproduce the movement of the moon and sun at various points.

You can also set the maximum values for the sun and moon parameters.

The sunrise/sunset and moonrise/moonset times are updated once an hour.

### Weathers

Get the weather at the observation point and output it as a parameter to VTube Studio.

There are two modes: one to get the weather from the Japan Meteorological Agency, and the other to get the weather from [OpenWeatherMap](https://openweathermap.org/).

The weather will be updated once an hour.

## Sample Model

There is also a sample Live2D model in the folder that can be used with this plug-in, so please refer to it.

