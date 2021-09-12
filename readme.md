# My Marlin Configuration

## Hardware

Ender 3 PRO
- BigTreeTech SKR Mini E3 2.0
- BLTouch
- fang hot end duct V4
    - parts cooling low-pass filter
        - 100Ω + 10µF
        - PWM controlled 25KHz

## Software
- applies to branch https://github.com/MarlinFirmware/Configurations/tree/bugfix-2.0.x

### Initial changes
- Probe enabled
    - offsets calculated
- AUTO_BED_LEVELING_BILINEAR
    - 5 x 5 points
- FAST_PWM_FAN 25KHz