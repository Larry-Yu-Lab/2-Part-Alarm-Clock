# 2-Part-Alarm-Clock
For those that what to get out of Bed :D

# ESP-NOW Dual-Node Perimeter Alarm

A simple, two-node wireless security alarm built on a pair of ESP32 boards. Instead of routing through a local home Wi-Fi network or spinning up MQTT brokers, the nodes talk directly to each other using Espressif's ESP-NOW protocol (2.4 GHz). 

The goal was to build a reliable door/drawer trip alarm for under $30 that doesn't drop offline when home Wi-Fi blips.

---

## How It Works

The system is split into two physical units: a battery-powered sensor node mounted at the trigger point, and a wall-powered base siren.
