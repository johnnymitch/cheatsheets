Password protect a ZIP file
zip -er /users/pw/emails.zip /users/pw/emails

---

Force empty recycle bin
sudo rm -rf ~/.Trash/

---

Add space to doc
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile”;}’ && killall Dock

Clear cache
sudo discoveryutil mdnsflushcache

---

Change screenshot location
defaults write com.apple.screencapture location ~/Pictures/;killall SystemUIServer

---

Add local directory to test a site
sudo vim /etc/hosts

:w

http://osxdaily.com/2012/08/07/edit-hosts-file-mac-os-x/

Launch Terminal, found in /Applications/Utilities/ or launched through Spotlight

Type the following command at the prompt:
sudo nano /private/etc/hosts

Enter the administrator password when requested, you will not see it typed on screen as usual with the command line

Once the hosts file is loaded within nano, use the arrow keys to navigate to the bottom of the hosts file to make your modifications

When finished, hit Control+O followed by ENTER/RETURN to save changes to /private/etc/hosts, then hit Control+X to exit out of nano

Quit out of Terminal when finished
