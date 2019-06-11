Install Arch Linux. Any desktop flavor should work.

Run the following in a terminal.

    sudo pacman -S git alsa-firmware alsa-lib alsa-plugins alsa-utils lib32-alsa-lib lib32-alsa-plugins pulseaudio-alsa lib32-libpulse libcanberra-pulse libpulse pulseaudio lib32-openal
    mkdir -p ~/eq
    git clone .... ~/eq
    ~/eq/bin/install

You'll be prompted with some GUIs. Follow the defaults, with one exception: On the DirectX install, accept the license, click next, and then on the next part of the install window click close without DirectX actually being installed.

Wait for EverQuest to fully download, then exit the patcher.

    ~/eq/bin/post-install

Run EverQuest.

    ~/eq/bin/launch
