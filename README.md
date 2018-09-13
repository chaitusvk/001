# 001
Useful linux commands

# youtude-dl
1. Download playlist with number 
   * youtube-dl -o "%(playlist_index)s-%(title)s.%(ext)s" <playlist_link>
   
# ZSH default 
1.chsh -s $(which zsh)


# Install Git
*sudo apt-get purge runit
*sudo apt-get purge git-all
*sudo apt-get purge git
*sudo apt-get autoremove
*sudo apt update
*sudo apt install git

# Google SEEDBANK
[GOOGLE SEEDBANK](http://tools.google.com/seedbank/)

# Ngrok
[Ngrok](https://6ftdan.com/allyourdev/2015/02/12/setting-up-remote-ssh-access-to-your-ubuntu-box/)          
1.ngrok -proto=tcp 22      
2.You will see a ngrok url like tcp://ngrok.com:12345      
3.ssh -p 12345 ngrok.com       

# REDSHIFT
1.redshift -O 4500 -b 0.9

# Wget
1.wget --mirror --convert-links --adjust-extension --page-requisites --no-parent http://example.org        
--mirror – Makes (among other things) the download recursive.           
--convert-links – convert all the links (also to stuff like CSS stylesheets) to relative, so it will be suitable for offline viewing.            
--adjust-extension – Adds suitable extensions to filenames (html or css) depending on their content-type.        
--page-requisites – Download things like CSS style-sheets and images required to properly display the page offline.         
--no-parent – When recursing do not ascend to the parent directory. It useful for restricting the download to only a portion of the site.




