# RPI Touch ShowRoom

## Description
Show room for the RPI Touch Screen abilities of the Raspberry Pi.

## Setup for SSH execution

```sh
export DISPLAY=:0
```

## Run

```sh
python rpi_touch_showroom/__main__.py
```
## Run inside Docker
```sh
xhost +	# Allow the X server to accept connections from the Raspberry Pi
docker compose up --build
```
