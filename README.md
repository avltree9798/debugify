# Debugify
The open source iOS 13 Internal Settings installer. The AppleInternal is purged on non checkra1n devices and therefore should not be used on such devices. I am not a product of Apple and all legal rights are to be treated to Apple. I am not responsible for files being disrupted or destroyed with the use of these tools while they shouldn't cause harm the way you use them is dependent on yourself.

## How to run.
Download the .sh script and copy it to your iDevice doesn't matter which directory just copy it. Now edit your SystemVersion.plist (File is in /System/Library/CoreServices/SystemVersion.plist) to match the following text Internal descriptor below.

https://pastebin.com/raw/NTpG0vYs

Make sure your file looks like this (Highlighted text should be the changed text)
https://i.imgur.com/BTE7d9X.png

After your finished editing your SystemVersion.plist open NewTerm or a SSH client to login to your phone. Make sure your set as root while SSH users should already be root in the case that you are using NewTerm and aren't root run "su" on NewTerm. Now navigate to the directory of the script and run "chmod +x debugify.sh" after run the final command to start the installation "./debugify.sh"

### Credits
Fire(ShadowFlame#0001, FireInternal on Telegram), Apple Inc.

### DMCA
This is for Apple legal team in the event that you may want me to take this down please send me a email at iifir3z@protonmail.com and ill get right to it.

