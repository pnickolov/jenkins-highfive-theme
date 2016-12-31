![image](https://parlaylabs.github.io/jenkins-highfive-theme/images/logo.svg)
# jenkins-material-theme [![Build Status](https://travis-ci.org/parlaylabs/jenkins-highfive-theme.svg?branch=master)](https://travis-ci.org/parlaylabs/jenkins-highfive-theme)
Beautify your Jenkins with the Highfive theme!

Website: https://parlaylabs.github.io/jenkins-highfive-theme

This is a Highfive-themed fork of [Jenkins Material Theme](https://jenkins-contrib-themes.github.io/jenkins-material-theme/).

## Features
* Just one small css file (35K)
* Embed minified SVG images
* Multiple ways to install
* Customize the color and logo using the [generator][generator]

## Screenshots

**TODO: Update these screenshots**

[![Screenshot jenkins-material-theme main](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-main.png)](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-main-large.png)      [![Screenshot jenkins-material-theme legend](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-legend.png)](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-legend-large.png) [![Screenshot jenkins-material-theme console](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-console.png)](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-console-large.png)
[![Screenshot jenkins-material-theme history](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-history.png)](https://parlaylabs.github.io/jenkins-highfive-theme/images/screenshot-jenkins-theme-material-history-large.png)



## Installation 

### Using this GitHub page (recommended) (auto-updated)

1. Choose your color:
![image](https://parlaylabs.github.io/jenkins-highfive-theme/images/pallete.png)

2. Replace `{{your-color-name}}` in the URL by the chosen color: `https://parlaylabs.github.io/jenkins-highfive-theme/dist/material-{{your-color-name}}.css`

3. Install [Jenkins Simple Theme Plugin][simple]

4. Click `Manage Jenkins`

5. Click `Configure System` and scroll down to `Theme`

6. Set the CSS field to the generated URL.

7. Click `Save`


### Using your Jenkins Hosting

1. Follow the step 1 and 2 of the previous method

2. Download the generated URL

3. Upload the downloaded file to your web server

4. Follow the steps 3 to 7 of the previous method using your uploaded file as URL in step 6


### Using Stylish (only you will be able to see the awesome theme)

1. Follow the step 1 and 2 of the previous method

2. Copy the content of the downloaded file

3. Install the [Stylish Chrome extension][stylish]

4. Go to Stylish options and click in `Write new style`

5. Paste the theme css in the code box

6. Click in `Specify` and set your jenkins domain

7. Click in `Save`

8. Go to your Jenkins website and enable the theme in the Stylish Chrome toolbar icon


## Development

CSS file are minified and compressed with Grunt. To prepare the environment:

```
npm install
grunt
```

This will generate the following file:
- dist/material-light.css

You can test the changes before committing using Stylish

## Deployment

After committing and pushing the changes, run `publish.sh`

## Compatibility
- Simple Theme plugin 0.3
- Jenkins 1.636
- Firefox 3.5+
- Chrome 4+
- Safari 4+
- Opera 15+
- Microsoft IE11 and Edge


If you are experiencing issues please let me know! Also, feel free to contribute!

## License
http://afonsof.mit-license.org/

##Thanks to
- [Simple Theme Plugin][simple] for the Simple Theme plugin
- [Google][google] for the the material design inspiration and the icons
- [Material Design Icons][material-design-icons] for some extra icons
- [Stylish][stylish] for making the test of new versions easy
- [canon-jenkins][canon-jenkins] for the base theme
- [@Heldroe][heldroe] for Firefox and Microsoft support
- [@bootstraponline][bootstraponline] for Jenkins native plugin

[simple]: https://wiki.jenkins-ci.org/display/JENKINS/Simple+Theme+Plugin
[google]: https://www.google.com/design/spec/material-design/introduction.html
[material-design-icons]: https://materialdesignicons.com/
[stylish]: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe
[canon-jenkins]: https://github.com/rackerlabs/canon-jenkins
[heldroe]: https://github.com/Heldroe
[generator]: https://parlaylabs.github.io/jenkins-highfive-theme
[bootstraponline]: https://github.com/bootstraponline
