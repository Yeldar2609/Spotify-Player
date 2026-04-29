# ESP32 Spotify Display

A compact, WiFi-enabled desktop display that shows your currently playing Spotify track in real time. Built around an ESP32 and a small TFT screen, this project combines hardware design, embedded programming, and API integration to create a sleek, functional music companion for your workspace.

## Overview

This project connects to the Spotify Web API to fetch live playback data and renders it on a 1.8" TFT display. It’s designed to sit on your desk and provide at-a-glance information such as track title, artist, album art, and playback status—without needing to open your phone or desktop app.

## Features

* Real-time Spotify playback display
* WiFi connectivity using ESP32
* SPI-driven TFT screen output
* Physical buttons for basic controls (e.g., play/pause, skip)
* Custom 3D-printed enclosure
* Lightweight and always-on desktop companion

## Tech Stack

* **ESP32** (WiFi-enabled microcontroller)
* **SPI communication** for display control
* **Spotify Web API** for music data
* **Arduino / ESP-IDF** firmware
* **Fusion 360** for CAD and enclosure design

## Hardware

* ESP32 development board (tested with LOLIN C3 Mini)
* 1.8" TFT display (ST7735 or ILI9341)
* Tactile switches (or keyboard switches)
* Optional: soldering setup or jumper wires
* 3D-printed case with heat-set inserts

## How It Works

The ESP32 connects to your WiFi network and authenticates with Spotify. It periodically requests the currently playing track and updates the display via SPI. User inputs through buttons can trigger playback actions via API calls.

## Goals

* Build a functional IoT device with real-world API integration
* Practice embedded systems development
* Explore hardware + software co-design
* Create a clean, minimal desktop gadget

## Future Improvements

* Album art rendering
* Touchscreen or rotary encoder input
* Bluetooth audio output
* Custom UI themes and animations
