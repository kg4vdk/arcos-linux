# Welcome to the arcOS Linux Github repository!
### arcOS Linux can be obtained by visiting https://arcos-linux.com
arcOS Linux source files can be obtained [here](https://s3.amazonaws.com/arcos-linux.com/arcOS-iso-setup-21.3_QRV.tar.gz)

### Issues for arcOS Linux and QRV Modules may be reported here.

[Donations](https://www.paypal.com/donate/?hosted_button_id=4SAKRN2MH7NEW) of any amount are greatly appreciated and help keep the project going!

## QRV Modules for arcOS Linux

To install the QRV modules, clone the repository into <code>/media/user/ARCOS-DATA/QRV/CALLSIGN/arcos-linux-modules</code>:

<code>user@arcOS:~$ git clone https://github.com/kg4vdk/arcos-linux-modules /media/user/ARCOS-DATA/QRV/CALLSIGN/arcos-linux-modules <--Replace "CALLSIGN" with your callsign</code>

Example directory structure for QRV modules:

<pre>
├── /media/user/ARCOS-DATA/QRV
    └── KG4VDK
        ├── arcos-linux-modules
        │   ├── APRS
        |   |   ├── tiledir               <-- Offline maps
        |   |   ├── aprs-profile          <-- Extracted contents of desired saved profile *.tgz
        │   │   ├── KG4VDK-9_Mobile.tgz   <-- Saved profile
        │   │   ├── KG4VDK_Home.tgz       <-- Saved profile
        |   |   └── save-aprs.sh          <-- Script to save the current APRS configuration
        │   ├── APRS.sh                   <-- Module script ("hide" inside the APRS directory to DISABLE)
        │   ├── FL-SUITE
        |   |   ├── fl-suite.tgz          <-- Copy of saved config, named fl-suite.tgz to be active
        │   │   ├── fl-suite_Tuesday-Diginet.tgz  <-- Saved config
        |   |   └── save-fl-suite.sh      <-- Script to save the current FL-SUITE configuration
        │   ├── FL-SUITE.sh               <-- Module script ("hide" inside the FL-SUITE directory to DISABLE)
        │   ├── WIFI
        │   │   ├── Home.nmconnection     <-- Saved connection
        │   │   ├── EMA.nmconnection      <-- Saved connection
        │   │   └── save-wifi.sh          <-- Script to save the current WIFI connections
        │   ├── WIFI.sh                   <-- Module script ("hide" inside the WIFI directory to DISABLE)
        │   ├── WINLINK
        │   │   ├── config.json           <-- Copy of saved config, named config.json to be active
        |   |   ├── config_with-aliases.json  <-- Saved config
        |   |   └── save-winlink.sh       <-- Script to save the current WINLINK configuration
        │   └── WINLINK.sh                <-- Module script ("hide" inside the WINLINK directory to DISABLE)
        └── wallpaper.jpg                 <-- Personal wallpaper (overrides default)
</pre>
