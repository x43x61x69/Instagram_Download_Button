# Instagram Download Button
[Github](https://github.com/y252328/Instagram_Download_Button), [Greasy Fork](https://greasyfork.org/en/scripts/406535-instagram-download-button) ~~, [OpenUserJS](https://openuserjs.org/scripts/y252328/Instagram_Download_Button)~~

This repository is a JavaScript for Greasemonkey/Tampermonkey. This script will add a download button and open button to your Instagram and you can download or open profile pictures, media in the posts, stories, and highlights by one click.

The newer versions code only do some simple tests on Chrome. So if you have any problem, please feel free to contact me in English or Chinese and attach your runtime environment.

> Note: This script only tests on Chrome ~~, Edge, and Firefox~~ with Tampermonkey on Windows 10 1903 64-bit.

## Options
This script can be configured by modifying the following constant variables in the head of this script.
* `attachLink` : boolean, attach the link into the button elements if true
* `postFilenameTemplate` : string, naming rule for media downloading in the post
* `storyFilenameTemplate` : string, naming rule for media downloading in the story

## Naming Template
* `%id%` : the poster id
* `%datetime%` : the media upload time
* `%medianame%` : the original media file name
* `%postId%` : the post id
* `%mediaIndex%` : the media index in multiple-media posts
* ~~`%ext%` : the file extension of media~~

## Shortcut Keys (May not work in newer versions)
* `Alt` + `i` : Open the media in the new tab
* `Alt` + `k` : Download the media
* `Alt` + `j` : Next media in the multiple media post
* `Alt` + `l` : Previous media in the multiple media post

> The shortcut keys do not work on the Instagram main page currently

## Contributors
* [孙年忠](https://greasyfork.org/users/829246-%E5%AD%99%E5%B9%B4%E5%BF%A0)
* [FlowerForWar](https://github.com/FlowerForWar)
* [xxalexx](https://greasyfork.org/en/users/170052-xxalexx)

## Preview
<img src="img/profile.png" alt="drawing" width="436" height="134"/>
<br/>
<img src="img/post.png" alt="drawing" width="467" height="294"/>
<br/>
<img src="img/story&highlight.png" alt="drawing" width="216" height="376"/>

## License
[MIT](https://github.com/y252328/Instagram_Download_Button/blob/master/LICENSE)
