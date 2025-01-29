# overwatch2 on arch linux hyprland/wayland(xwayland), steam flatpak version with proton ge

see the Settings_v0.ini located in ::: /home/j/.var/app/com.valvesoftware.Steam/.steam/steam/steamapps/compatdata/2357570/pfx/drive_c/users/steamuser/Documents/Overwatch/Settings

Steam launch options: #game-performance #gamemoderun

PROTON_NO_ESYNC=1 PROTON_NO_FSYNC=1 DXVK_ASYNC=0 PULSE_LATENCY_MSEC=30 LD_PRELOAD="" gamemoderun %command%

Remember to enable/disable steam ovelay

Amm currently running some tweaked hyprland conf to help with hardware cursors enabled and faster render see: 
https://wiki.hyprland.org/Configuring/Variables/
