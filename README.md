# UNIX-command-line-packer-unpacker
This is a simple ksh script to pack together a bunch of files into one file, for ease of file management. It takes only a little more space than all of the files combined.
# Dependencies
These scripts require KSH to be present and in the system path. If you haven't already done so, you will need to install KSH.
# Installation
No installation needed, just make sure the files are executable (chmod +x) and place them in your PATH.
# Use
To pack files into a big file (called a glob), type:

$ pack \<filename\> [\<another_file\> [...

Then place the glob where you want it. To unpack the glob (or even multiple globs!) type the following:

$ unpack \<glob_name\> [\<another_glob\> [...

# Contact me
If you find an issue with the system or have any questions, feel free to create a pull request or create an issue here on GitHub. If you need tyo contact me directly, my email address is noahkeck72@gmail.com.
