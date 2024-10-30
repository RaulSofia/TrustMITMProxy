# TrustMITMProxy
Magisk Module that injects the MITMProxy CA Certificate as a System Certificate on Android (14 included), using the method described in [this HTTPToolKit's blog post](https://httptoolkit.com/blog/android-14-install-system-ca-certificate/#option-1-bind-mounting-through-ns-enter).

## Installation and Usage
### Prerequisites
- A rooted Android device with Magisk installed

### Installation
1. Download the latest release from the [Releases]()
2. Install the module using the Magisk Manager app (Modules -> Install from storage -> Select the downloaded zip file)
3. Reboot your device
4. Done! You can check if the certificate was installed by going to Settings -> Security -> Encryption & credentials -> Trusted credentials -> System and looking for the `mitmproxy` certificate