# Windows Setup

## Windows preferences

### Install

1. Install windows updates
2. Drivers
 * [nvidia](http://www.nvidia.fr/Download/index.aspx)
3. Change root password
4. Activate Windows

### Privacy

* General : all off
* Location : all off
* Account info : all off
* Background apps
 * Office : off
 * Photos : off
 * Windows store : off
 * Xbox : off

## Scoop

Update execution policy (this is insecure, don't do that on servers)
`set-executionpolicy unrestricted -s cu`

Install Scoop
`iex (new-object net.webclient).downloadstring('https://get.scoop.sh')`

Install core utils and tools
`scoop install 7zip coreutils curl git grep openssh sed wget vim grep openssh --global`


## Apps & Tools

* [Synergy](http://synergy-project.org/nightly)
* [Skype](https://www.skype.com/en/download-skype/)
* [Slack](https://slack.com/downloads)
* [Todoist](https://todoist.com/windows)
* [Messenger](http://messengerfordesktop.com)
* [WhatsApp](https://github.com/Aluxian/WhatsApp-Desktop)
* [Sublime Text](http://www.sublimetext.com/)
* [VLC](http://www.videolan.org/vlc/download-windows.html)
* [Dropbox](https://www.dropbox.com/downloading)
* [Adobe PDF Reader](http://www.adobe.com/support/downloads/product.jsp?platform=windows&product=10)
* [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
  * [AdblockPlus](https://adblockplus.org/)
  * [Chrome Remote Desktop](https://chrome.google.com/webstore/detail/chrome-remote-desktop/gbchcmhmhahfdphkhkmpfmihenigjmpp?hl=en)
  * [RSS](https://chrome.google.com/webstore/detail/rss-subscription-extensio/nlbjncdgjeocebhnmkbbbdekmmmcbfjd)
* [Firefox](https://www.mozilla.org/fr-FR/firefox/new/)
* [Evernote](https://evernote.com/download/)
* [FileZilla](https://filezilla-project.org/download.php?type=client)

* [Pocket](https://getpocket.com)
* [DoneDone](https://www.getdonedone.com/)
* [Feedly](feedly.com)

## Private network

* Change device name
* Attach to private network


 
