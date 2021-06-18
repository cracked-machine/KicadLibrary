This repository contains custom Kicad symbols and footprints not found in OOTB Kicad library. 

### Top Level Directory Listing:

<pre>├── <font color="#3465A4"><b>EdgeTemplates</b></font>
│   └── <font color="#3465A4"><b>HammondEnclosures</b></font>
├── <font color="#3465A4"><b>footprint</b></font>
│   ├── <font color="#3465A4"><b>BATTERY</b></font>
│   ├── <font color="#3465A4"><b>BGA</b></font>
│   ├── <font color="#3465A4"><b>CONNECTORS</b></font>
│   ├── <font color="#3465A4"><b>DISPLAYS</b></font>
│   ├── <font color="#3465A4"><b>ENCLOSURES</b></font>
│   ├── <font color="#3465A4"><b>MISC</b></font>
│   ├── <font color="#3465A4"><b>MODULES</b></font>
│   ├── <font color="#3465A4"><b>POTS</b></font>
│   ├── <font color="#3465A4"><b>PWR</b></font>
│   ├── <font color="#3465A4"><b>RF</b></font>
│   └── <font color="#3465A4"><b>SWITCHES</b></font>
└── <font color="#3465A4"><b>symbol</b></font>
    ├── <font color="#3465A4"><b>AUDIOCONVERTERS</b></font>
    ├── <font color="#3465A4"><b>CONNECTOR</b></font>
    ├── <font color="#3465A4"><b>ENCODER</b></font>
    ├── <font color="#3465A4"><b>INTERFACE</b></font>
    ├── <font color="#3465A4"><b>LOGIC</b></font>
    ├── <font color="#3465A4"><b>MCU</b></font>
    ├── <font color="#3465A4"><b>MPU</b></font>
    ├── <font color="#3465A4"><b>OTPO</b></font>
    ├── <font color="#3465A4"><b>PGA</b></font>
    ├── <font color="#3465A4"><b>PWR</b></font>
    ├── <font color="#3465A4"><b>SW</b></font>
    └── <font color="#3465A4"><b>TIMER</b></font>
</pre>

### Full symbol directory listing:

<pre>─── <font color="#3465A4"><b>symbol</b></font>
    ├── <font color="#3465A4"><b>AUDIOCONVERTERS</b></font>
    │   └── CirrusAudioConverters.lib
    ├── <font color="#3465A4"><b>CONNECTOR</b></font>
    │   ├── <font color="#3465A4"><b>AUDIO</b></font>
    │   │   ├── audiojack2-connector_numbered.lib
    │   │   └── MonoJack2Switch.lib
    │   └── <font color="#3465A4"><b>MIDI</b></font>
    │       └── MidiDin5.lib
    ├── <font color="#3465A4"><b>ENCODER</b></font>
    │   └── <font color="#3465A4"><b>RotaryEncoder</b></font>
    │       └── RotaryEncoder.lib
    ├── <font color="#3465A4"><b>INTERFACE</b></font>
    │   └── ADP5587.lib
    ├── <font color="#3465A4"><b>LOGIC</b></font>
    │   ├── ADG2188.lib
    │   ├── DG46x.lib
    │   ├── DG470.lib
    │   ├── SN74LVC1G3157.lib
    │   └── TS5A3357.lib
    ├── <font color="#3465A4"><b>MCU</b></font>
    │   ├── STM32G031.lib
    │   ├── STM32G0B1.lib
    │   └── STM32G4.lib
    ├── <font color="#3465A4"><b>MPU</b></font>
    │   └── <font color="#3465A4"><b>STM32MP1</b></font>
    │       └── STM32MP15x.lib
    ├── <font color="#3465A4"><b>OTPO</b></font>
    │   ├── <font color="#3465A4"><b>ISOLATORS</b></font>
    │   │   └── TLP2361.lib
    │   └── <font color="#3465A4"><b>LEDDRIVERS</b></font>
    │       ├── HT16K33.lib
    │       └── TLC5955.lib
    ├── <font color="#3465A4"><b>PGA</b></font>
    │   └── PGA.lib
    ├── <font color="#3465A4"><b>PWR</b></font>
    │   ├── <font color="#3465A4"><b>DC-DC</b></font>
    │   │   ├── <font color="#3465A4"><b>CHARGEPUMP</b></font>
    │   │   │   ├── NCP1729.lib
    │   │   │   └── TPS6040x.lib
    │   │   └── <font color="#3465A4"><b>ISOLATED</b></font>
    │   │       ├── RecomRKZE.lib
    │   │       ├── RecomRS6.lib
    │   │       ├── TracoTRN1.lib
    │   │       ├── XP_ISA.lib
    │   │       └── XP_JTF.lib
    │   ├── <font color="#3465A4"><b>LEDDRIVER</b></font>
    │   │   └── PAM2812.lib
    │   ├── <font color="#3465A4"><b>LOADSW</b></font>
    │   │   └── SiP3250x.lib
    │   ├── <font color="#3465A4"><b>PMIC</b></font>
    │   │   ├── Microchip_PMIC.lib
    │   │   ├── NXP_PMIC.lib
    │   │   ├── ST_PMIC.lib
    │   │   └── TI_PMIC.lib
    │   └── <font color="#3465A4"><b>REG</b></font>
    │       ├── <font color="#3465A4"><b>LDO</b></font>
    │       │   ├── MIC5233.lib
    │       │   ├── MIC5270YM5.lib
    │       │   └── TC59.lib
    │       └── <font color="#3465A4"><b>VREF</b></font>
    ├── <font color="#3465A4"><b>SW</b></font>
    │   ├── PCB_LED_SW.lib
    │   └── Tactile_SPST-NO.lib
    └── <font color="#3465A4"><b>TIMER</b></font>
        └── MIC155x.lib
</pre>

### Full footprint directory listing:

<pre>─── <font color="#3465A4"><b>footprint</b></font>
    ├── <font color="#3465A4"><b>BATTERY</b></font>
    │   └── <font color="#3465A4"><b>Panasonic_ML_series.pretty</b></font>
    ├── <font color="#3465A4"><b>BGA</b></font>
    │   └── <font color="#3465A4"><b>STM32MP151_LFBGA.pretty</b></font>
    ├── <font color="#3465A4"><b>CONNECTORS</b></font>
    │   ├── <font color="#3465A4"><b>AUDIO</b></font>
    │   │   ├── <font color="#3465A4"><b>Jack_TRRS_3.pretty</b></font>
    │   │   ├── <font color="#3465A4"><b>NeutrikNMJ.pretty</b></font>
    │   │   ├── <font color="#3465A4"><b>NeutrikNRJ.pretty</b></font>
    │   │   └── <font color="#3465A4"><b>ThonkiConn_3.pretty</b></font>
    │   ├── <font color="#3465A4"><b>COAX</b></font>
    │   │   └── <font  color="#3465A4"><b>RSProStraight50OhmPCBMountBulkheadFittingBNC_5260279</b></font>
    │   │       └── <font color="#3465A4"><b>RSProStraight50OhmPCBMountBulkheadFittingBNC_5260279.pretty</b></font>
    │   ├── <font color="#3465A4"><b>MIDI</b></font>
    │   │   └── <font color="#3465A4"><b>RS_5P180_DIN5_SOCKET_WSHIELD.pretty</b></font>
    │   ├── <font color="#3465A4"><b>POWER</b></font>
    │   │   └── <font color="#3465A4"><b>MOLEX</b></font>
    │   │       └── <font color="#3465A4"><b>MINI_FIT_JNR</b></font>
    │   │           └── <font color="#3465A4"><b>Connector_Molex_MiniFitJnrExtra.pretty</b></font>
    │   ├── <font color="#3465A4"><b>SIGNAL</b></font>
    │   │   ├── <font color="#3465A4"><b>IDC_PCB_Edge_Connectors.pretty</b></font>
    │   │   ├── <font color="#3465A4"><b>Molex_SDIO</b></font>
    │   │   │   └── <font color="#3465A4"><b>Molex_SDIO.pretty</b></font>
    │   │   └── <font color="#3465A4"><b>TermiMate One-Circuit Terminal-Style Connector System.pretty</b></font>
    │   │       ├── <font color="#3465A4"><b>MOLEX_5050710101</b></font>
    │   │       └── <font color="#3465A4"><b>MOLEX_5050720101</b></font>
    │   └── <font color="#3465A4"><b>USB</b></font>
    │       ├── <font color="#3465A4"><b>MolexUSB_TypeC.pretty</b></font>
    │       └── <font color="#3465A4"><b>USB_Plug_ConnectorLess.pretty</b></font>
    ├── <font color="#3465A4"><b>DISPLAYS</b></font>
    │   └── <font color="#3465A4"><b>ILI9341_TFTLCD.pretty</b></font>
    ├── <font color="#3465A4"><b>ENCLOSURES</b></font>
    │   └── <font color="#3465A4"><b>HAMMOND</b></font>
    │       └── <font color="#3465A4"><b>Hammond1590.pretty</b></font>
    ├── <font color="#3465A4"><b>MISC</b></font>
    │   ├── <font color="#3465A4"><b>Adafruit Trellis 4x4 3mm HT16K33.pretty</b></font>
    │   ├── <font color="#3465A4"><b>KEYPADS</b></font>
    │   │   └── <font color="#3465A4"><b>KEYPADS.pretty</b></font>
    │   └── <font color="#3465A4"><b>TinyNetTies.pretty</b></font>
    ├── <font color="#3465A4"><b>MODULES</b></font>
    │   ├── <font color="#3465A4"><b>DISPLAYS</b></font>
    │   │   └── <font color="#3465A4"><b>2.42Inch_OLED_SSD1309.pretty</b></font>
    │   └── <font color="#3465A4"><b>NUCLEO</b></font>
    │       └── <font color="#3465A4"><b>ST_Nucleo.pretty</b></font>
    ├── <font color="#3465A4"><b>POTS</b></font>
    │   └── <font color="#3465A4"><b>SLIDERS</b></font>
    │       ├── <font color="#3465A4"><b>Alpha_Sliders.pretty</b></font>
    │       ├── <font color="#3465A4"><b>Bourn_PTA_Slider.pretty</b></font>
    │       └── <font color="#3465A4"><b>Bourn_PTL_Slider.pretty</b></font>
    ├── <font color="#3465A4"><b>PWR</b></font>
    │   ├── <font color="#3465A4"><b>DC-DC</b></font>
    │   │   └── <font color="#3465A4"><b>ISOLATED</b></font>
    │   │       ├── <font color="#3465A4"><b>RecomR2D.pretty</b></font>
    │   │       ├── <font color="#3465A4"><b>RecomRS6.pretty</b></font>
    │   │       ├── <font color="#3465A4"><b>TRN_SIP6.pretty</b></font>
    │   │       ├── <font color="#3465A4"><b>XP_ISA.pretty</b></font>
    │   │       └── <font color="#3465A4"><b>XP_JTF.pretty</b></font>
    │   ├── <font color="#3465A4"><b>PMIC</b></font>
    │   │   └── <font color="#3465A4"><b>STPMIC1.pretty</b></font>
    │   ├── <font color="#3465A4"><b>PWR</b></font>
    │   └── <font color="#3465A4"><b>REG</b></font>
    │       └── <font color="#3465A4"><b>VREF</b></font>
    ├── <font color="#3465A4"><b>RF</b></font>
    │   └── <font color="#3465A4"><b>PCB_Antenna</b></font>
    │       └── <font color="#3465A4"><b>PCB_Antenna.pretty</b></font>
    └── <font color="#3465A4"><b>SWITCHES</b></font>
        ├── <font color="#3465A4"><b>custom_sw.pretty</b></font>
        ├── <font color="#3465A4"><b>DailywellSwitches.pretty</b></font>
        ├── <font color="#3465A4"><b>JS_Series_Sub-Miniature_Slide_Switches</b></font>
        │   └── <font color="#3465A4"><b>JS_Series_Sub-Miniature_Slide_Switches.pretty</b></font>
        ├── <font color="#3465A4"><b>PCB_SW_LED.pretty</b></font>
        ├── <font color="#3465A4"><b>RS_Switches.pretty</b></font>
        └── <font color="#3465A4"><b>TACTILE</b></font>
            └── <font color="#3465A4"><b>12x12x7_3mmTactilePushButtonMomentary.pretty</b></font>
</pre>