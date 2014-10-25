# Introduction

It is a packer template for building a xubuntu desktop from netboot iso.

# Configure

You want to edit `http/preseed.cfg` and `template.json` before building an image.

# Build

`/usr/bin/time -f %E packer build template.json`

# Testing the image after it's built.

`./launch`