# Console Commands

## Start the android emulator from the command line

[Android Docs](https://developer.android.com/studio/run/emulator-commandline)

[Youtube video](https://www.youtube.com/watch?v=XmhUU4Ix1Zs)

```sh

cd /home/vi-th-u/Android/Sdk
# cd /home/<USERNAME>/Android/Sdk

cd emulator  


#./emulator @<VIRTUAL DEVICE NAME>
./emulator @Pixel_5_API_30

#or
./emulator -avd Pixel_5_API_30

# Get a list of the emulators installed

./emulator -list-avds

```

### Setup zsh for starting the emulator from command line