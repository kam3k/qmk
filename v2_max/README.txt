1. Clone the keychron version of qmk_firmware
2. Checkout wireless_playground
3. $ qmk config user.keyboard=keychron/v2_max/ansi_encoder
4. $ qmk new-keymap (give name marc)
5. Copy keymap.c into keyboards/keychron/v2_max/ansi_encoder/keymaps/marc 
6. $ qmk compile -kb keychron/v2_max/ansi_encoder -km marc
7. Lift off spacebar, unplug keyboard, hold down button, plug in keyboard while holding button
8. Confirm keyboard is in correct mode with $ qmk console
9. qmk flash -kb keychron/v2_max/ansi_encoder -km marc
