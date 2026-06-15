1. Clone the keychron version of qmk_firmware
2. Checkout wireless_playground
3. $ git submodule update --init --recursive --progress
4. $ qmk config user.keyboard=keychron/v2_max/ansi_encoder
5. $ qmk new-keymap (give name marc)
6. Copy keymap.c into keyboards/keychron/v2_max/ansi_encoder/keymaps/marc 
7. $ qmk compile -kb keychron/v2_max/ansi_encoder -km marc
8. Lift off spacebar, unplug usb-c from keyboard, hold down button, plug in keyboard while holding button
9. Confirm keyboard is in correct mode with $ qmk console
10. qmk flash -kb keychron/v2_max/ansi_encoder -km marc
