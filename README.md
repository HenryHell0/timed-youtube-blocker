# Timed Youtube Blocker
A simple script that keeps youtube blocked most of the time, but lets you "allow" it for a certain ammount of time, with a cooldown

## Setup: 
- download and move both files into `/usr/local/bin/`
- run `block-youtube` once

## Usage:
use `allow-youtube <minutes>` to allow youtube for a number of minutes - there is a 10 minute cooldown between uses


works by modifying the DNS lookup table in /etc/hosts
