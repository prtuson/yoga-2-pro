# yoga-2-pro
Integration of the Orientation application from https://github.com/pfps/yoga-laptop 

Includes systemd services to ensure orientation starts to works on first boot and continues through suspend.

Some modifications to orientation.c to ensure it stays running through faults in the sensors.
