# Tello Gamepad Control

This is a simple Go program that lets you control a DJI Tello drone using a gamepad.

## Requirements

- Computer with Wi-Fi adapter
- DJI Tello drone
- FFmpeg installed and in your PATH (use ffplay for video streaming)
- Gamepad
- Go-lang installed on your computer

## Usage

1. Connect your computer to the Tello's Wi-Fi network
2. Connect your gamepad to your computer
3. Run the program with the following command:
	```bash
	go run .
	```
4. Use the gamepad to control the drone

## Building

You can build the program with the following command:
```bash
go build .
```
This will create an executable file that you can run.

## Thanks

- [Ebitengine™](https://ebitengine.org/ja/) for window management abd gamepad support
- [Gobot](https://gobot.io/documentation/platforms/tello/) for controlling the Tello drone
