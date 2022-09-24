# lemonra1n
iOS 15.0 - 15.4.1 (15.5b4) work in progress semi-tethered checkm8 jailbreak

# What does this do?
It boots the device with AMFI patches. There is **no tweak injection yet**.

**NOTE**: Onboard blobs are pretty much needed so you don't get the black screen issue. Dump onboards with [SSHRD_Script](https://github.com/verygenericname/SSHRD_Script), then use that blob with this Jailbreak

**NOTE 2**: This is for macOS only

**Known working devices:**
- iPhone X (GSM)
- iPhone 7
- iPhone 6s

# How to use
1. Install libimobiledevice
    - It's needed for `ideviceenterrecovery` and `ideviceinfo`
2. Install lemonra1n from [here](https://github.com/BenjaminHornbeck6/lemonra1n/releases/download/lemonra1n/lemonra1n.app.zip)
3. Prepare your onboard blob for the **current version** you're on
4. Put your device in DFU mode
6. Open lemonra1n, select your blob then type in your iOS version and tap Jailbreak (should take about 1 minute)
7. Install lemonra1n Loader through TrollStore, then hit Install in the app!
    - You can get the Pogo IPA from [here](https://nightly.link/elihwyma/Pogo/workflows/build/main/Pogo.zip)
    - You should now see Sileo on your homescreen, enjoy!
    - You'll have to open lemonra1n Loader every reboot (opening it will run a uicache for you to use Sileo again)

# Credits
- [Nebula](https://github.com/itsnebulalol) for a lot of the code from palera1n
- [the Procursus Team](https://github.com/ProcursusTeam) for the amazing bootstrap
- [Amy](https://github.com/elihwyma) for Pogo
