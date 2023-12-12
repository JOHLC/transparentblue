# Transparent Blue Theme for Home Assistant

[![HACS Default](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
![GitHub Release Date](https://img.shields.io/github/release-date/johlc/transparentblue)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/johlc/transparentblue?label=Version&style=flat-square&labelColor=2ea9f4&color=1473ae)
![GitHub All Releases](https://img.shields.io/github/downloads/johlc/transparentblue/total?&label=Total%20Downloads&style=flat-square&labelColor=2ea9f4&color=1473ae)

## Overview
Transparent Blue is a theme designed for Home Assistant, offering a sleek and transparent blue aesthetic. It's my first custom theme for Home Assistant and my first ever GitHub/HACS repository.

Please report any issues through the [issues section](https://github.com/JOHLC/transparentblue/issues) and provide feedback or ask questions on the [Home Assistant Community post](https://community.home-assistant.io/t/transparent-blue-custom-theme/).

## Screenshots
**Main**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-1.png" alt="Screenshot 1" width="1000">

**More info**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-4.png" alt="Screenshot 1" width="750">

**Sidebar**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-2.png" alt="v2023.12.1-2.png" width="1000">

**Menu**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-3.png" alt="Screenshot 3" width="750">

<!-- replace screenshot --> 

Here is the [Included background image](https://github.com/JOHLC/transparentblue/blob/main/images/background.jpg)<br />


## HACS installation - recommended<br /> 
Transparent Blue is now a default repo in HACS! 
1. Open HACS
2. Select "Frontend"
3. Click add (+)
4. Search for Transparent Blue and click it
5. Click Download 
You should now be able to select this theme in Home Assistant

### Manual Installation - not recommended<br /> 
1. Download the transparentblue.yaml file from the latest release
2. Upload the downloaded file to your "themes" directory
3. Add the resource reference to your lovelace config

You should now be able to select this theme in Home Assistant


## Changing the background image<br />
This theme uses a base64 encoded image. I use [this](https://www.base64-image.de/) website to encode my images. <br /> 
To change the background of this theme, change the following in the .yaml file:

````
lovelace-background: 'center / cover no-repeat fixed url()'
````

In between the brackets, in the url() section, add your own base64 string:
````
# Example
lovelace-background: 'center / cover no-repeat fixed url('data:image/png;base64,YOURLONGSTRING)'
````
Alternatively, you can use a local image stored in your config/www directory or a publicly accessible image url like so

````
lovelace-background: 'center / cover no-repeat fixed url("/local/background.png")' 
# OR
# lovelace-background: 'center / cover no-repeat fixed url("http://www.reportingday.com/wp-content/uploads/2018/06/Cat-Sleeping-Pics.jpg")' 
````

## Beta versions
Beta versions may be released for personal testing. If you're using HACS, you can enable/disable beta versions by changing the "Show beta versions" setting.
<br /> 
<img src="https://github.com/JOHLC/transparentblue/blob/main/images/hacsbeta.png?raw=true" alt="hacs beta" >
<br />

## Other cool themes
- https://github.com/3ative/3ative-blue-theme
- https://github.com/naofireblade/clear-theme-dark
<br />
