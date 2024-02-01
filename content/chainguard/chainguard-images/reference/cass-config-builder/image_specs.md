---
title: "cass-config-builder Image Variants"
type: "article"
unlisted: true
description: "Detailed information about the public cass-config-builder Chainguard Image variants"
date: 2023-03-07T11:07:52+02:00
lastmod: 2024-02-01 00:31:15
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 550
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/cass-config-builder/" >}}
{{< tab title="Variants" active=true url="/chainguard/chainguard-images/reference/cass-config-builder/image_specs/" >}}
{{< tab title="Tags History" active=false url="/chainguard/chainguard-images/reference/cass-config-builder/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/cass-config-builder/provenance_info/" >}}
{{</ tabs >}}

This page shows detailed information about all public variants of the Chainguard **cass-config-builder** Image.

## Variants Compared
The **cass-config-builder** Chainguard Image currently has 2 public variants: 

- `latest-dev`
- `latest`

The table has detailed information about each of these variants.

|              | latest-dev                  | latest                      |
|--------------|-----------------------------|-----------------------------|
| Default User | `nonroot`                   | `nonroot`                   |
| Entrypoint   | `/usr/local/bin/entrypoint` | `/usr/local/bin/entrypoint` |
| CMD          | not specified               | not specified               |
| Workdir      | not specified               | not specified               |
| Has apk?     | yes                         | no                          |
| Has a shell? | yes                         | yes                         |

Check the [tags history page](/chainguard/chainguard-images/reference/cass-config-builder/tags_history/) for the full list of available tags.

## Packages Included
The table shows package distribution across variants.

|                          | latest-dev | latest |
|--------------------------|------------|--------|
| `apk-tools`              | X          |        |
| `bash`                   | X          | X      |
| `busybox`                | X          | X      |
| `ca-certificates-bundle` | X          | X      |
| `cass-config-builder`    | X          | X      |
| `git`                    | X          |        |
| `glibc`                  | X          | X      |
| `glibc-locale-posix`     | X          | X      |
| `ld-linux`               | X          | X      |
| `libbrotlicommon1`       | X          |        |
| `libbrotlidec1`          | X          |        |
| `libcrypt1`              | X          | X      |
| `libcrypto3`             | X          |        |
| `libcurl-openssl4`       | X          |        |
| `libexpat1`              | X          |        |
| `libidn2`                | X          |        |
| `libnghttp2-14`          | X          |        |
| `libpcre2-8-0`           | X          |        |
| `libpsl`                 | X          |        |
| `libssl3`                | X          |        |
| `libunistring`           | X          |        |
| `ncurses`                | X          | X      |
| `ncurses-terminfo-base`  | X          | X      |
| `openssl-config`         | X          |        |
| `wolfi-baselayout`       | X          | X      |
| `zlib`                   | X          |        |
