# install-vnc

This script installs VNC for a linux server.

For more information, see [this guide](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-vnc-on-ubuntu-20-04).

## How to use

```bash
chmod +x vnc.sh
./vnc.sh
```

During installation, you may be prompted to choose a default display manager for Xfce. Select either one and press `ENTER`.

Then you’ll be prompted to enter and verify a password to access your machine remotely:

```bash
You will require a password to access your desktops.

Password:
Verify:

# The password must be between six and eight characters long. Passwords more than 8 characters will be truncated automatically.

Would you like to enter a view-only password (y/n)?

# n
```
