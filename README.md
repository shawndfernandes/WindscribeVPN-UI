# WindscribeVPN-UI
Windscribe VPN UI interface for Windscribe VPN

    A convienient UI tool to trigger Windscribe VPN cli commands via UI.

    Tested on Ubuntu 20, built with gtkmm3.0.

Instructions:

    Run "./main" from terminal, or rename and copy "main" to "/usr/local/bin" folder (can execute from any path).
    
    Command to run program with its own terminal (can even be configured to run from startup)

    gnome-terminal -x bash -c "main; exec bash"

    gnome-terminal -x bash -c "<name of executable file>; exec bash"

Pre requisites : Windscribe VPN CLI on Unix

    https://windscribe.com/guides/linux
