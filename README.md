# PayloadLoaderInstaller Environment

This is a environment to be loaded with the [EnvironmentLoader](https://github.com/wiiu-env/EnvironmentLoader).

The only purpose of this environment is to run the [PayloadLoaderInstaller](https://github.com/wiiu-env/PayloadLoaderInstaller).

## Content

- [Mocha](https://github.com/wiiu-env/MochaPayload)
- [LaunchInstaller](https://github.com/wiiu-env/LaunchInstaller)
- [PayloadLoaderInstaller](https://github.com/wiiu-env/PayloadLoaderInstaller)

## Usage
- Place the `00_mocha.rpx` from [Mocha](https://github.com/wiiu-env/MochaPayload) in the `sd:/wiiu/environments/installer/modules/setup` folder.
- Place the `90_launch_installer.rpx` from the [LaunchInstaller](https://github.com/wiiu-env/LaunchInstaller) in the `sd:/wiiu/environments/installer/modules/setup` folder.
- Place the `PayloadLoaderInstaller.wuhb` from the [PayloadLoaderInstaller](https://github.com/wiiu-env/PayloadLoaderInstaller)) in the `sd:/wiiu/apps/` folder.
 
Copy all files on the sd card and launch then Environment via the [EnvironmentLoader](https://github.com/wiiu-env/EnvironmentLoader). Press X while launching to force open the environment selection menu.  
After launching the environment, the PayloadLoaderInstaller should load automatically. Follow the instructions on the screen. See the [PayloadLoaderInstaller](https://github.com/wiiu-env/PayloadLoaderInstaller) repository for more information.
 
## Download

A bundle with the latest nightlies can be downloaded [here](https://tiramisu.foryour.cafe/package/payloadloaderinstaller) by clicking on "Download all".
 
## Credits

- Maschell (EnvironmentLoader, MochaPayload, PayloadLoader, FailST, PayloadLoaderInstaller)
- rw-r-r-0644, GaryOderNichts (PayloadLoaderInstaller)
- dimok (mocha))