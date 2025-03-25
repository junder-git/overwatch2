# overwatch2 on arch linux hyprland/wayland(xwayland), steam ((flatpak/native version)) with proton ge  
  
Both native/flatpak steam version show error "Restart overwatch to apply settings" eventhough everyone has read and write permissions
  
see the Settings_v0.ini located in :::  
  
/home/j/.var/app/com.valvesoftware.Steam/.steam/steam/steamapps/compatdata/2357570/pfx/drive_c/users/steamuser/Documents/Overwatch/Settings  
  
OR native steam:::  
  
/home/j/.local/share/Steam/steamapps/compatdata/2357570/pfx/drive_c/users/steamuser/Documents/Overwatch/Settings
  
Steam launch options: #game-performance #gamemoderun

  

PROTON_NO_ESYNC=0 PROTON_NO_FSYNC=1 DXVK_ASYNC=1 PULSE_LATENCY_MSEC=30 gamemoderun %command%  
###LD_PRELOAD="" dx11   
  
SEE::: https://flightlessmango.com/games/15751/logs/782  
(((ow2 hits around plus 550 stable fps in practice range)))  
    
Remember to enable/disable steam ovelay
  
Amm currently running some tweaked hyprland conf to help with hardware cursors enabled and faster render see: 
https://wiki.hyprland.org/Configuring/Variables/
  
For latencyflex:::    
PROTON_ENABLE_NVAPI=1 DXVK_NVAPI_DRIVER_VERSION=49729 DXVK_NVAPI_ALLOW_OTHER_DRIVERS=1 LFX=1   
