#linux Command

pkg upgrade
pkg uninstall package-name



Command 	                Description
...
pkg autoclean 	          :Remove outdated .deb files from the cache.
pkg clean 	              :Remove all .deb files from the cache.
pkg files <package> 	    :List files installed by specified package.
pkg list-all 	            :List all available packages.
pkg list-installed 	      :List currently installed packages.
pkg reinstall <package> 	:Re-install specified package.
pkg search <query> 	      :Search package by query.
pkg show <package> 	      :Show information about specific package. 
...


Repository 	                              Command to subscribe to repository
...
game-packages 	                          pkg install game-repo
science-packages 	                        pkg install science-repo
termux-root-packages 	                    pkg install root-repo
x11-packages (Android 7+ only) 	          pkg install x11-repo
...


Python-----------------------------------------------------------------------
pkg install python
pkg install python2



for using python get python-modules------------------------------------------
pip install {module name}
pip uninstall {module name}

'pip list'         for listing installed modules




##A few python packages are available from termux's package manager (for python3 only), and should be installed from there to avoid compilation errors. This is the case for:
...
    numpy                            pkg install python-numpy
    electrum                         pkg install electrum
    opencv                           pkg install opencv-python
    asciinem                         pkg install asciinema
    matplotlib                       pkg install matplotlib
    cryptography                     pkg install python-cryptography
...





##Advance installing instruction------------------------------------------------
'pkg install python-tkinter'



![Termux-commands-list](https://github.com/ashokabairwaideology/Hacking-tools-for-linux/assets/98442276/5fe6bd91-aa2e-42b5-84a6-4209f0741bb5)




Termux Commands List and What They Do:
...

cp -v used to print informative massage

cp -r used to copy any directory

mv -u update-move when the source is newer than the destination

mv -v to move any directory

ls -n to display UID and GID directory

ls –version to check the version of ls command

cd — show last working directory from where we moved

ls -l show file action like – modified, date and time, owner of file, permissions Etc.

ls help show display how to use “ls” command

cp -n no file overwrite

cd ~ move to users home directory from anywhere

cd – move one directory back from the current location

mv [file name] move any file and folder

ls list directory

ls -a list all files including hidden files

pwd - it shows your current working directory


mv -i interactive prompt before overwrite

wget [url] - install tool , apt install wget

git clone [url]- install any tools with git clone, apt install git

ls -al formatted listing with hidden files

mv -f force move by overwriting destination files without prompt

ls -i Display the number of file or directory

cp copy any file

cd / change to the root directory

cd -change directory

cd .. change the current directory to parent directory
...



