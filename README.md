## Rainmeter - Transparent Simplicity

A simple package with the following features:

* A weather skin which shows the current weather and the forecast (high/low/conditions) for the next three days
* A Spotify media player with play/pause/previous/next capabilities. Displays song title and artist
* Roundlines displaying total disk usage, current CPU usage, current GPU usage, and current RAM usage
* A network display which shows the current network input/output speed
* A detailed CPU and GPU view, showing temperatures, speeds, and usage graphs. Requires CoreTemp and MSIAfterburner
* A button that switches between headphones and speakers as audio output device
* A button that opens a browser window to youtube

## How to make this skin work for _you_

* For proper functionality of the GPU detail skin:
  * Install MSIAfterburner [from here](https://www.msi.com/page/afterburner)
  * Install the appropriate MSIAfterburner.dll for your application [from here](https://forums.guru3d.com/threads/rainmeter-plugin-for-msi-afterburner.319558/)
* For proper functionality of the CPU detail skin:
  * Install CoreTemp [from here](https://www.alcpu.com/CoreTemp/)
* For accurate weather information in your area:
  * Find your [weather code](https://weather.codes/) and replace the "WeatherCode" variable in Transparent-Weather.ini
  * Choose either metric or imperial for your weather units
* To use the audio device switcher:
  * Determine the index of the desired audio devices by navigating to Sound Settings > Choose your output device
  * Modify the SetOutPutIndex number in Change.ini to match the index of the corresponding output devices
* To use the Disk skins:
  * Add or delete the skins based on your drive setup
  * Edit each Transparent-Disk.ini and set the Drive variable to an appropriate drive letter
  
  ## TODO
  
  - [x] Allow scrolling to resize the various controls
  - [ ] Make the color of the text/bars/images customizable via a global variable
  - [ ] Create .rmskin installer(s)
