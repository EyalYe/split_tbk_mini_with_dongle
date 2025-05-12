- [ ] set keymap to control macro pad.



old yaml
 board: [ "nice_nano_v2" ]
 shield: [ "tbk_mini" ]
 include:
   - board: nice_nano_v2
     shield: tbk_mini_right
   - board: nice_nano_v2
     shield: tbk_mini_left
   - board: nice_nano_v2
     shield: tbk_mini_dongle
     snippet: studio-rpc-usb-uart
     cmake-args: -DCONFIG_ZMK_STUDIO=y
     artifact-name: tbk_mini_dongle_with_studio

