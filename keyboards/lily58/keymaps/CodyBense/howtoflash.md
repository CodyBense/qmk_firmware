# How to flash
1. edit the keymap.c
2. qmk compile -kb lily58 -km CodyBense
3. go to ~/qmk_firmware/.build
4. qmk flash -bl dfu lily58_rev1_CodyBense.hex

