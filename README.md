# klipper_macros

## Install

NOTE: Please backup your current printer_data/config folder prior to installing this

<pre>cd ~
git clone https://github.com/Turge08/klipper_macros
cd klipper_macros
./update.sh</pre>

My Klipper Print Settings are required for the macros to work: https://github.com/Turge08/klipper_print_setting

## Updates:

To be notified of any updates, add the following to moonraker.conf:

<pre>[update_manager klipper_macros]
type: git_repo
path: ~/klipper_macros
origin: https://github.com/Turge08/klipper_macros.git
is_system_service: False</pre>

When an update is available, update the repo folder through Mainsail/Flkuidd then run the following through SSH (Will be automated in the future):

<pre>cd ~/klipper_macros
./update.sh</pre>

Restart the firmware for the changes to take effect.
