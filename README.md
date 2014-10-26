# Introduction

It is an example packer template based on netboot iso that adds sample grains to a built image.

# Configure

You want to edit `http/preseed.cfg` and `template.json` before building an image.

# Build

`/usr/bin/time -f %E packer build template.json`

# Testing the image after it's built.

`./launch`