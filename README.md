# Manjaro ARM ClockworkPI A60 DevTerm
[![iso_build](https://github.com/manjaro-arm/clockworkpi-a60-images/workflows/image_build_all/badge.svg)](https://github.com/manjaro-arm/clockworkpi-a60-images/actions)

## description

Development Branch for Manjaro ARM images for the ClockworkPI A60 DevTerm

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm/clockworkpi-a60-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d clockworkpi-a60 -e $EDITION`
