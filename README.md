# invidious-stack

## Description
Invidious Stack - run multiple backend processes with proton-privoxy vpn (or not)

Placeholder repository. Please be patient :) It will be ready eventually :)

invidious.catspeed.cc uses 4 backend processes. Each process has it's own VPN connection.

This repo will help you set up an invidious server stack. It can work for 1 or any even number of invidious services (1,2,4,6,8,etc). 

proton-privoxy can work for 1 or any even number of VPN connections/IP's (1,2,4,6,8,etc).

- You could have for example, 4 process(es) on 1 single VPN IP
- You could have for example, 4 processes on 4 VPN IP's
- You could have for example, 4 processes with no VPN.
- Nginx will rotate the backends for you

## Features
- Invidious (compiled and manual install as service, patched to work via http proxy)
- inv_sig_helper (in docker)
- script to generate/replace the po-token & visitor_data
- script to check if playback is blocked
- nginx config management
- invidious config management
- service file management

## What is the point of this?
I would like to contribute in any way I can to the invidious community. I would like to arm you with the tools to get your instance(s) up and running as easily and smoothly as possible.

Why? The more people that can install their own instance (public or private) the more working instances we have. It broke my hopes when I saw there were no working public instances listed on the documentation. I figured I would add mine to the pile, and get me my own instance to use personally. Together we make invidious stronger, and resilient.

## Additional Notes
Working on setup. Will commit later. Currently the setup works great :3c
