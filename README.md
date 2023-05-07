```

.
├── EdgeTemplates
│   └── HammondEnclosures
│       └── 1590B.dxf
├── footprint
│   ├── BATTERY
│   │   ├── GenericCoinCellHolders.pretty
│   │   └── Panasonic_ML_series.pretty
│   ├── BGA
│   │   └── STM32MP151_LFBGA.pretty
│   ├── CONNECTORS
│   │   ├── AUDIO
│   │   │   ├── Jack_TRRS_3.pretty
│   │   │   ├── NeutrikNMJ.pretty
│   │   │   ├── NeutrikNRJ.pretty
│   │   │   └── ThonkiConn_3.pretty
│   │   ├── COAX
│   │   │   └── RSProStraight50OhmPCBMountBulkheadFittingBNC_5260279
│   │   │       └── RSProStraight50OhmPCBMountBulkheadFittingBNC_5260279.pretty
│   │   ├── MIDI
│   │   │   └── RS_5P180_DIN5_SOCKET_WSHIELD.pretty
│   │   ├── POWER
│   │   │   └── MOLEX
│   │   │       └── MINI_FIT_JNR
│   │   │           └── Connector_Molex_MiniFitJnrExtra.pretty
│   │   ├── SIGNAL
│   │   │   ├── IDC_PCB_Edge_Connectors.pretty
│   │   │   ├── Molex_SDIO
│   │   │   │   └── Molex_SDIO.pretty
│   │   │   └── TermiMate One-Circuit Terminal-Style Connector System.pretty
│   │   │       ├── MOLEX_5050710101
│   │   │       └── MOLEX_5050720101
│   │   └── USB
│   │       ├── MolexUSB_TypeC.pretty
│   │       └── USB_Plug_ConnectorLess.pretty
│   ├── DISPLAYS
│   │   ├── 128x64_0_96InchOLED.pretty
│   │   ├── ILI9341_TFTLCD.pretty
│   │   └── SSD1306_0.96_Oled.pretty
│   ├── ENCLOSURES
│   │   └── HAMMOND
│   │       └── Hammond1590.pretty
│   ├── MISC
│   │   ├── Adafruit Trellis 4x4 3mm HT16K33.pretty
│   │   ├── KEYPADS
│   │   │   └── KEYPADS.pretty
│   │   └── TinyNetTies.pretty
│   ├── MODULES
│   │   ├── DISPLAYS
│   │   │   ├── 0.96inch_OLED_SSD1306.pretty
│   │   │   └── 2.42Inch_OLED_SSD1309.pretty
│   │   └── NUCLEO
│   │       └── ST_Nucleo.pretty
│   ├── POTS
│   │   └── SLIDERS
│   │       ├── Alpha_Sliders.pretty
│   │       ├── Bourn_PTA_Slider.pretty
│   │       └── Bourn_PTL_Slider.pretty
│   ├── PWR
│   │   ├── DC-DC
│   │   │   └── ISOLATED
│   │   │       ├── RecomR2D.pretty
│   │   │       ├── RecomRS6.pretty
│   │   │       ├── TRN_SIP6.pretty
│   │   │       ├── XP_ISA.pretty
│   │   │       └── XP_JTF.pretty
│   │   ├── PMIC
│   │   │   └── STPMIC1.pretty
│   │   └── REG
│   │       └── VREF
│   ├── QFN
│   │   ├── QFN-32-1EP_5x5mm_TestPoints.pretty
│   │   └── ThinMiniQFN.pretty
│   ├── RF
│   │   └── PCB_Antenna
│   │       └── PCB_Antenna.pretty
│   └── SWITCHES
│       ├── DailywellSwitches.pretty
│       ├── JS_Series_Sub-Miniature_Slide_Switches
│       │   └── JS_Series_Sub-Miniature_Slide_Switches.pretty
│       ├── PCB_SW_LED.pretty
│       ├── RS_Switches.pretty
│       ├── TACTILE
│       │   └── 12x12x7_3mmTactilePushButtonMomentary.pretty
│       └── custom_sw.pretty
└── symbol
    ├── AUDIOCONVERTERS
    │   └── CirrusAudioConverters.lib
    ├── CONNECTOR
    │   ├── AUDIO
    │   │   ├── MonoJack2Switch.lib
    │   │   └── audiojack2-connector_numbered.lib
    │   └── MIDI
    │       └── MidiDin5.lib
    ├── ENCODER
    │   └── RotaryEncoder
    │       └── RotaryEncoder.lib
    ├── INTERFACE
    │   └── ADP5587.lib
    ├── LOGIC
    │   ├── ADG2188.lib
    │   ├── DG46x.lib
    │   ├── DG470.lib
    │   ├── SN74LVC1G3157.lib
    │   └── TS5A3357.lib
    ├── MCU
    │   ├── STM32G031.lib
    │   ├── STM32G0B1.lib
    │   └── STM32G4.lib
    ├── MPU
    │   └── STM32MP1
    │       └── STM32MP15x.lib
    ├── OTPO
    │   ├── ISOLATORS
    │   │   └── TLP2361.lib
    │   └── LEDDRIVERS
    │       ├── HT16K33.lib
    │       └── TLC5955.lib
    ├── PGA
    │   └── PGA.lib
    ├── PWR
    │   ├── DC-DC
    │   │   ├── CHARGEPUMP
    │   │   │   ├── NCP1729.lib
    │   │   │   └── TPS6040x.lib
    │   │   └── ISOLATED
    │   │       ├── RecomRKZE.lib
    │   │       ├── RecomRS6.lib
    │   │       ├── TracoTRN1.lib
    │   │       ├── XP_ISA.lib
    │   │       └── XP_JTF.lib
    │   ├── LEDDRIVER
    │   │   └── PAM2812.lib
    │   ├── LOADSW
    │   │   └── SiP3250x.lib
    │   ├── PMIC
    │   │   ├── Microchip_PMIC.lib
    │   │   ├── NXP_PMIC.lib
    │   │   ├── ST_PMIC.lib
    │   │   └── TI_PMIC.lib
    │   └── REG
    │       ├── CHARGEPUMP
    │       ├── LDO
    │       │   ├── MIC5233.lib
    │       │   ├── MIC5270YM5.lib
    │       │   └── TC59.lib
    │       └── VREF
    ├── SW
    │   ├── PCB_LED_SW.lib
    │   └── Tactile_SPST-NO.lib
    └── TIMER
        └── MIC155x.lib

112 directories, 39 files

```
