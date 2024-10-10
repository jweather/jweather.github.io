---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: MacroPad resource page
---
This page has links to all the tools and files I talk about in this [YouTube series on building your own custom Macro Pad](https://youtube.com).

Download links
 - [KiCad](https://kicad.org)
 - [Sea Picro footprint library](https://github.com/joshajohnson/sea-picro-footprints)
 - [QMK WSL](https://wsl.qmk.fm)
 - [VIAL app](https://get.vial.today/download)
 
 Web Tools
 - [Keyboard Layout Editor](https://keyboard-layout-editor.com)
 - [keyboard-tools.xyz: KLE to KiCad layout](https://keyboard-tools.xyz)
 - [OnShape](https://onshape.com)
 - [VIAL web app](https://vial.rocks)

Shopping Links
 - [JLCPCB](https://jlcpcb.com)
 - [SOD123 diodes at LCSC](https://www.lcsc.com/product-detail/Switching-Diodes_ST-Semtech-1N4148W_C81598.html)
 - [Reset switch at LCSC](https://www.lcsc.com/product-detail/Switching-Diode_ST-Semtech-1N4148W_C81598.html)
 - [SendCutSend](https://sendcutsend.com)
 - [Sea Picro at beekeeb](https://shop.beekeeb.com/product/sea-picro)
 - [MX hotswap sockets at beekeeb](https://shop.beekeeb.com/product/gateron-mx-hotswap-socket/)
 - [M2 screws and standoffs at keeb.io](https://keeb.io/products/m2-screws-and-standoffs)
 - [M2 screw assortment at Amazon](https://www.amazon.com/dp/B08FMNNFLN)
 - [2mm spacers at Amazon](https://www.amazon.com/gp/product/B07L7JVVFJ)
 - [Rubber feet at Amazon](https://www.amazon.com/dp/B07G8926LH)
 - [Allium58 at beekeeb](https://shop.beekeeb.com/product/allium58-glp-wired-kit/)
 
 Reference Information
 - [Sea Picro pinout](https://joshajohnson.com/sea-picro/#pinout)
 - [Gateron product datasheets](https://www.gateron.co/pages/product-datasheet)
 - [Adafruit's Guide to Excellent Soldering](https://learn.adafruit.com/adafruit-guide-excellent-soldering/tools)
 - [Soldering SMD diodes](https://www.youtube.com/watch?app=desktop&v=Jpj3tilIaik)

 Provided Files
 - [vial.json template](vial.json)
 - [rules.mk file](rules.mk)
 - [pre-built firmware](macro0_vial.uf2)

 Commands to copy and paste in Part 4

    wsl --install

    git clone https://github.com/vial-kb/vial-qmk
    cd vial-qmk
    make git-submodule

    qmk new-keyboard

    qmk compile -kb macro0 -km default

    python3 util/vial_generate_keyboard_uid.py

    qmk compile -kb macro0 -km vial

 
Sources I used to write this series
 - [TKL Keyboard Design - Noah Kiser](https://www.youtube.com/watch?v=6Z49bynRqj8)
 - [How a keyboard matrix works](https://docs.qmk.fm/how_a_matrix_works)
 - [Adding your keyboard to QMK](https://docs.qmk.fm/porting_your_keyboard_to_qmk)
 - [Porting your keyboard to VIAL](https://get.vial.today/docs/porting-to-via.html)
