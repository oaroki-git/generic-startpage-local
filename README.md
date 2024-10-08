# startpage-extension
because chrome doesn't like new tabs redirecting to local pages, I made a manifest.json to turn it into an extension stored it in that instead;
lightweight and eliminates the need for any new tab redirect extension

focus page instead of URL bar functionality is not here though, gotta figure out how to do that eventually (probably never because im lazy as shit)

# credit
thanks to PrettyCoffee for creationg [yet-another-generic-startpage](https://github.com/PrettyCoffee/yet-another-generic-startpage) which is what i use here

## preview
here is what it looks like:
![alt text](https://github.com/oaroki-git/startpage-extension/blob/main/startpage.png)

## install
1. clone the repo with git: ```git clone https://github.com/oaroki-git/generic-startpage-local.git``` or download the .zip from [releases](https://github.com/oaroki-git/generic-startpage-local/releases/) and unzip that
3. open chrome://extensions (in a chromium browser ofc)
4. enable developer mode
5. click "load unpacked" and find and choose the startpage-extension-unpacked folder or drag and drop it in

## for other stuff
the most important part of this is just the manifest.json.

replacing the startpage folder with anything works, whether it be your own yet-another-generic-startpage configuration ([tutorial in their repo](https://github.com/PrettyCoffee/yet-another-generic-startpage)) or literally any other cool startpage project from github or yourself!
