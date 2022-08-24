# Better-MPV-Config
A copy of my mpv.conf file. Complete with required shaders necessary for 4K upscaling.
Please note that this is mainly for upscaling resolutions like 1920x1080 to resolutions like 3840x2160 and beyond, and you will need a very powerful GPU to run this config. My RX 6600 XT goes up to 90-95% utilization on average.

## Introduction:

This an improved MPV config file (And shaders) that do the following:

- sets Color Space, Dithering, Debanding, Subtitles
- sets Motion Interpolation, Anti-Ringing and Upscaling & Processing
- uses shaders for improved visuals

## Credit:
* [hl2guide for inspiring me to make my own config file](https://github.com/hl2guide)
* [FSRCNNX](https://github.com/xzpyth/mpv-config/blob/main/shaders/FSRCNNX_x2_8-0-4-1.glsl)
* [KrigBilateral by Shiandow](https://gist.github.com/igv/a015fc885d5c22e6891820ad89555637)

## Prerequsites:
* official MPV Player: https://mpv.io/
* a PC with at least 4GB of RAM
* a PC with discrete Graphics Card (Must be equivalent in performance to RTX 3060 or faster)

## Configuration

### Windows Users

* Extract the .tar file in the releases section to the location: `%APPDATA%/mpv/`
* Everything should be set up out of the box.

### Linux Users

* You can put all of the options in configuration files which will be read every time mpv is run.
* The system-wide configuration file 'mpv.conf' is in your configuration directory (e.g. `/etc/mpv` or `/usr/local/etc/mpv`).
* The user-specific one is `~/.config/mpv/mpv.conf`.
* Shaders go into `~/.config/mpv/shaders`

### Mac Users

This config will need your own additional work if you happen to use a Mac (since Macs only support OpenGL).

I don't own any Macs to test it so even if I wanted to I couldn't.
