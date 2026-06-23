# Geode-CLI-4Android-Termux-
Unofficial Geode Command Line Port for Android (Termux)

# Installation
The releases include an archive with a binary based on Android ARM64, which can be used for Termux. After installing the release, unzip the archive and transfer the binary to the Termux home directory using the command:

```bash
# Granting access rights to the storage
termux-setup-storage

# We transfer the binary to the Termux home directory
mv ~/path/to/binary ~
```
We grant permission to execute the binary:

```bash
chmod +x geode
```
And we run the binary:

```bash
./geode
```
You will see the ```geode``` commands 

# Usage
After installing Geode CLI, you can create your own mod, but instead of ```geode``` you will need to use ```./geode```

```bash
# Without ./
geode new❌️
geode build❌️

# With ./
./geode new✅️
./geode build✅️
```
# Problems
I can't compile Geode CLI for ARM32 (ARMv7), so this method is only available for ARM64 (aarch64)😭

(I am not responsible for problems with Android NDK )
