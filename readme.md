# Raspi Ethernet bridge

## Overview

This is a project for setting up a subnet with any router and a raspberrypi.

You need:
- A Raspberry Pi (or pi) with an Ethernet port
- A Router
- One Ethernet cable (or additional ones if you desire)

The way this project works is that the pi is connected to the router and whenever the router gets a request for a site, it sends it to the pi. The pi can use it's wifi interface to fetch the data and send it back.

This setup is useful for when you need a wifi bridge or try to build a subnet in a network where you have no cables to connect to.

## Why I did this project

At my home, I've been banished to the guest network.
This is unfortunate, due to the guest network prohibiting other devices from seeing each other.

When i got smart home devices, they worked, but everything worked just a bit wrong.
I mitigated this for a while by creating a subnet with an esp32 (this was the only thing that worked weirdly).

It worked, but it was very unstable and incredibly slow. This setup is so much faster.