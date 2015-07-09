# lsm9ds0
Simple access to the g-force linear acceleration, gauss magnetic and dps angular rate sensors of the LSM9DS0 through I2C.

I've done some initial work on interfacing with the LSM9DS0 through I2C. Basically, you can set the different sensitivities (or max ranges) and read normalized values from the three sensors.

I intend to add more support for the common options as well as an easy way of setting all options (you can set all options manually with update_reg but I'd like something nicer), as well as SPI and interrupts etc, but this works for now.

SPI access has been implemented according to specification and reference implementation, but may not work.
Either there's a problem with my device, or I've missed something, but I'm not gonna spend any more time on it.
Feel free to test it and send me a pull request when you've found my mistake =)
