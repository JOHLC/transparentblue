# Transparent Blue
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
<img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/johlc/transparentblue"> ![GitHub release (latest by date)](https://img.shields.io/github/v/release/johlc/transparentblue?label=Version&style=flat-square&labelColor=2ea9f4&color=1473ae)
![GitHub All Releases](https://img.shields.io/github/downloads/johlc/transparentblue/total?&label=Total%20Downloads&style=flat-square&labelColor=2ea9f4&color=1473ae) ![.github/workflows/validate.yaml](https://github.com/JOHLC/transparentblue/workflows/.github/workflows/validate.yaml/badge.svg)

## A transparent blue theme for Home Assistant 
This is a theme I created for Home Assistant called Transparent Blue. This is/was my first ever custom theme for Home Assistant and my first ever GitHub/HACS repository.<br />
It can be installed via HACS or manually with help from the instructions below.

### Screenshots
**Main**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/sc3.png" alt="Screenshot 1" width="1000">

**Sidebar**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/sc2.png" alt="Screenshot 2" width="1000">

**Misc.**<br />
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/sc4.png" alt="Screenshot 3" width="1000">
<img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/sc5.png" alt="Screenshot 3" width="1000">

<!-- replace screenshot --> 
[Included background image](https://github.com/JOHLC/transparentblue/blob/main/images/background.jpg)<br />


## HACS installation - recommended<br /> 
Transparent Blue is now a default repo in HACS! 
1. Open HACS
2. Select "Frontend"
3. Click add (+)
4. Search for Transparent Blue and click it
5. Click Install 
You should now be able to select this theme in Home Assistant

### Manual Installation - not recommended<br /> 
1. Download the transparentblue.yaml file from the latest release
2. Upload the downloaded file to your "themes" directory
3. Add the resource reference to your lovelace config

You should now be able to select this theme in Home Assistant

<br />

#### Changing the background image<br />
This theme uses a base64 encoded image. I use [this](https://www.base64-image.de/) website to encode my images. <br /> 
To change the background of this theme, change the following in the .yaml file:

````
lovelace-background: 'center / cover no-repeat fixed url()'
````

In between the brackets in the url() section, add your own base64 string. Example: url('data:image/png;base64,YOURLONGSTRING)<br /> 
<br /> 
You can also add a local image stored in your config/www directory or a publicly accessible image url like so

````
lovelace-background: 'center / cover no-repeat fixed url("/local/background.png")' 
# OR
# lovelace-background: 'center / cover no-repeat fixed url("http://www.reportingday.com/wp-content/uploads/2018/06/Cat-Sleeping-Pics.jpg")' 
````

#### Beta versions
From time to time I will be releasing beta versions. This is mainly for personal testing before merging dev branch changes. If you are using HACS you can enable / disable these beta versions by changing the setting "Show beta versions"<br /> 

<img src="https://github.com/JOHLC/transparentblue/blob/main/images/hacsbeta.png?raw=true" alt="hacs beta" >
<br />
