linuxSetUp
==========

Setup



+ Git
  * apt-get install git
+ Node
  1. curl -sL https://deb.nodesource.com/setup | sudo bash -
  2. sudo apt-get install -y nodejs
  3. Optional (apt-get install -y build-essential)
+ Atom
  1. git clone https://github.com/atom/atom
  2. cd atom
  3. git fetch
  4. git checkout $(git describe --tags `git rev-list --tags --max-count=1`)
  5. script/build
  6. sudo script/grunt install
+ Spotify
  1. Search for and open the “Software & Updates” utility from Unity Dash. 
  2.  Under “Other Software” tab, click the Add button and paste the below line into the pop-up box: `deb http://repository.spotify.com stable non-free`
  3.  sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 94558F59
  4.  sudo apt-get update
  5.  sudo apt-get install spotify-client


+ [Atom](https://github.com/atom/atom/blob/master/docs/build-instructions/linux.md)


guvcview
simplescreenrecorder- http://www.maartenbaert.be/simplescreenrecorder/
http://www.x.org/wiki/radeonBuildHowTo/


sudo apt-get update
sudo apt-get upgrade
sudo do-release-upgrade
sudo apt-get install ubuntu-release-upgrader-core



+http://repogen.simplylinux.ch/ - source list
sudo gedit /etc/apt/sources.list 
+ http://www.x.org/wiki/radeonBuildHowTo/

+http://askubuntu.com/questions/450349/permissions-denied-in-qgis-perhaps-all-kde-programs - user issue
