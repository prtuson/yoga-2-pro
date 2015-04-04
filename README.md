# yoga-2-pro
Integration of the Orientation application from https://github.com/pfps/yoga-laptop 

Includes systemd services to ensure orientation starts to works on first boot and continues through suspend.

Some modifications to orientation.c to ensure it stays running through faults in the sensors.

There are two main branches:

  Sensors contains the changed orientation.c file

  Services contains the new systemd service definitions and assocated scripts.

This has beeen tested using Debian Jessie on a Lenovo Yoga 2 Pro.

It currently run orientation as root.
