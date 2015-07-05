# usbctrl
Easy extendable usb-device-control util.


## Actions
Actions can easily be added by placing a bash-script in the actions-directory.

## Example

    ./usbctrl   
    1: Bus 001 Device 002: ID 0424:9514 Standard Microsystems Corp.
    2: Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
    3: Bus 001 Device 003: ID 0424:ec00 Standard Microsystems Corp.
    4: Bus 001 Device 004: ID 152d:0569 JMicron Technology Corp. / JMicron USA Technology Corp.
    5: Bus 001 Device 005: ID 041e:3040 Creative Technology, Ltd SoundBlaster Live! 24-bit External SB0490
    Please select a device to operate on: 5
    1: bind
    2: info
    3: poweroff
    4: poweron
    5: remove
    6: unbind
    7: exit
    Please select an action to execute: 7
    
    Bye.

