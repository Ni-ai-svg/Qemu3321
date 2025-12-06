    # Installing cinnamon and vnc. Installing xfce4 solves grey screen issue
    apt-get install -y tigervnc-standalone-server dbus-x11 xfce4 xfce4-goodies novnc python3-websockify python3-numpy python3-pip pipx cabextract tightvncserver htop software-properties-common && \
	# Remove dummy Firefox
	# Install Firefox without Snap
	echo 'Package: firefox*\nPin: release o=LP-PPA-mozillateam\nPin-Priority: 1001' | tee /etc/apt/preferences.d/Mozilla && \
	add-apt-repository ppa:mozillateam/ppa && \
	apt-get update && \
    apt-get install -y firefox
    
