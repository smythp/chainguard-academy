---
title: "vela-cli Image Variants"
type: "article"
description: "Detailed specs for vela-cli Chainguard Image Variants"
date: 2023-03-07T11:07:52+02:00
lastmod: 2023-03-07T11:07:52+02:00
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
menu:
  docs:
    parent: "vela-cli"
weight: 550
toc: true
---

This page shows detailed information about all available variants of the Chainguard **vela-cli** Image.

## Variants Compared
The **vela-cli** Chainguard Image currently has one public variant: 

- `latest`

The table has detailed information about each of these variants.

|              | latest          |
|--------------|-----------------|
| Default User | `nonroot`       |
| Entrypoint   | `/usr/bin/vela` |
| CMD          | not specified   |
| Workdir      | not specified   |
| Has apk?     | no              |
| Has a shell? | yes             |

## Image Dependencies
The table shows package distribution across all variants.

|                          | latest |
|--------------------------|--------|
| `ca-certificates-bundle` | X      |
| `wolfi-baselayout`       | X      |
| `kubevela`               | X      |
| `bash`                   | X      |
| `expat`                  | X      |
