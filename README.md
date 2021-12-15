# infocon-watcher
_Infocon Watcher shows the SANS ISC Infocon in the system tray._

Infocon Watcher
===============

_Data security news straight to your desktop!_

This application displays the current Infocon on-line threat level, as determined by the [SANS Internet Storm Center (ISC)](https://isc.sans.edu/), using a little globe in your system tray. The Infocon is a colour-coded assessment of the current condition of data security and connectivity of the Internet infrastructure. Also available are the latest data security headlines from ISC (tips, tricks and current state of affairs, mostly intended for data security professionals).
The levels that can be displayed are: Green, Yellow, Orange, Red, Test (blue) or Unknown (error, grey). For a more detailed description of the Infocon levels and how it is determined, see the [Infocon page](https://isc.sans.edu/infocon.html) at ISC.

Instructions
------------
Infocon Watcher is easy to use. Here's what the various buttons and commands do:

| _Main window_ |
| :---: |
| ![Main window](https://i.postimg.cc/LszB0WK6/Infocon-Watcher-window.png) |

| Command | Description |
|---|---|
| System tray icon | The icon colour indicates the current Infocon level. Click the icon to open the main window. Right-click the icon to open the context menu. The application always minimises to the system tray. |
| Current Infocon | Shows the current state of the Infocon. The Infocon is shown both in the main window and the system tray icon. |
| Open | Shows the main window |
| Show Headlines | Show a webpage with the latest ISC data security diary headlines, and the latest installments of the Stormcast, the ISC podcast. (The page is opened in the system default browser.) |
| Go To ISC | Open the Internet Storm Center's main page. |
| Refresh Infocon | The Infocon is retrieved automatically every 15 minutes, but can also be refreshed manually using this command. |
| Show window on change | Opens the main window if the Infocon changes. (It will not be opened for changes in Infocon retrieval success/failure.) |
| Minimise/Close Window | The application always minimises to the system tray. Click the tray icon or choose the Open context menu command to reopen the window. |
| Quit | Terminates the application and removes it from the system tray. |

Infocon Watcher is available as a binary build for Windows and Raspbian Linux. The Raspbian version of Infocon Watcher depends on the command line tool [cURL](https://curl.haxx.se/) (install package ["curl"](http://mirrordirector.raspbian.org/raspbian/pool/main/c/curl/) using your package manager). Tested on Raspberry Pi 3B.

(C) 2021 VDT Software

VDT Software is not affiliated with SANS ISC.

Developer contact:

![E-mail](https://i.postimg.cc/B6BptVMw/iw-email2.png)
