# Frigate with USB Coral TPU in Docker in a Proxmox Virtual Machine.
These are the configs I have to use in order to get Frigate working with a USB Coral TPU running in a Docker container in a PVE (Proxmox) Virtual Machine (VM).

No matter what I did, I kept getting the dreaded `ValueError: Failed to load delegate from libedgetpu.so.1` error when spinning up Frigate (which just means the TPU could not be found). It took a lot of searching and trial & error, but I finally puzzled together the winning combination you can find here. I hope it's useful to someone.

I have only tested this in a VM, but it might work in an LXC as well.
