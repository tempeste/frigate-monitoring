# Frigate NVR Setup
Instructions for setting up Frigate NVR can be found [here](https://docs.frigate.video/).

## Why set this up?
I decided to test out this NVR as an alternative to the proprietary application that came with my CCTV system. The original app now requires a paid subscription to access feeds online, which prompted me to explore open-source solutions like Frigate.

## Project Details
1. The Frigate NVR runs on my own Intel NUC (Next Unit of Computing) device.
2. The application is deployed using Docker Compose for easy management

## TODO(s)
### Accessing Frigate Remotely
To access the Frigate NVR remotely, there are a few options I'm currently considering:
1. **VPN (Virtual Private Network)**
2. **Cloudflare Zero Trust**
3. **Reverse Proxy with Nginx**
