---
title: "datadog-agent Image Variants"
type: "article"
unlisted: true
description: "Detailed information about the public datadog-agent Chainguard Image variants"
date: 2024-01-22 00:18:06
lastmod: 2024-01-22 00:18:06
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 550
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/datadog-agent/" >}}
{{< tab title="Variants" active=true url="/chainguard/chainguard-images/reference/datadog-agent/image_specs/" >}}
{{< tab title="Tags History" active=false url="/chainguard/chainguard-images/reference/datadog-agent/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/datadog-agent/provenance_info/" >}}
{{</ tabs >}}

This page shows detailed information about all public variants of the Chainguard **datadog-agent** Image.

## Variants Compared
The **datadog-agent** Chainguard Image currently has 2 public variants: 

- `latest-dev`
- `latest`

The table has detailed information about each of these variants.

|              | latest-dev                           | latest                               |
|--------------|--------------------------------------|--------------------------------------|
| Default User | `nonroot`                            | `nonroot`                            |
| Entrypoint   | `/opt/datadog-agent/bin/agent/agent` | `/opt/datadog-agent/bin/agent/agent` |
| CMD          | not specified                        | not specified                        |
| Workdir      | not specified                        | not specified                        |
| Has apk?     | yes                                  | no                                   |
| Has a shell? | yes                                  | no                                   |

Check the [tags history page](/chainguard/chainguard-images/reference/datadog-agent/tags_history/) for the full list of available tags.

## Packages Included
The table shows package distribution across variants.

|                          | latest-dev | latest |
|--------------------------|------------|--------|
| `apk-tools`              | X          |        |
| `bash`                   | X          |        |
| `busybox`                | X          |        |
| `ca-certificates-bundle` | X          | X      |
| `datadog-agent`          | X          | X      |
| `gdbm`                   | X          | X      |
| `git`                    | X          |        |
| `glibc`                  | X          | X      |
| `glibc-locale-posix`     | X          | X      |
| `ld-linux`               | X          | X      |
| `libbrotlicommon1`       | X          |        |
| `libbrotlidec1`          | X          |        |
| `libbz2-1`               | X          | X      |
| `libcrypt1`              | X          | X      |
| `libcrypto3`             | X          | X      |
| `libcurl-openssl4`       | X          |        |
| `libexpat1`              | X          | X      |
| `libffi`                 | X          | X      |
| `libgcc`                 | X          | X      |
| `libidn2`                | X          |        |
| `libnghttp2-14`          | X          |        |
| `libpcre2-8-0`           | X          |        |
| `libpsl`                 | X          |        |
| `libssl3`                | X          | X      |
| `libstdc++`              | X          | X      |
| `libunistring`           | X          |        |
| `mpdecimal`              | X          | X      |
| `ncurses`                | X          | X      |
| `ncurses-terminfo-base`  | X          | X      |
| `openssl-config`         | X          | X      |
| `python-3.12`            | X          | X      |
| `readline`               | X          | X      |
| `sqlite-libs`            | X          | X      |
| `wolfi-baselayout`       | X          | X      |
| `xz`                     | X          | X      |
| `zlib`                   | X          | X      |
