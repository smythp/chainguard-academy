---
title: "cfssl Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the cfssl Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-27 00:41:27
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/cfssl/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/cfssl/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/cfssl/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/cfssl/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 26th    | `sha256:4f3fe1da9245b802b0780a4fe579306d66d8195f556cd1f4a8596348360a7fbb` |
|  `latest`     | June 20th    | `sha256:2a715172c645f386361750601b1eca36c1fbe8bb96e0b6049b502519157de033` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `1.6.5-dev` `1-dev` `1.6-dev` `latest-dev` | June 26th    | `sha256:b087cab5636fd81bb28d924539ebc238a17c08135a3d4c95be3a6c02f2c5923d` |
|  `1.6.5` `latest` `1.6` `1`                 | June 20th    | `sha256:bac9c672fc38199885f665d37a8d7cf461763517b33869e5d372087c3ac6d919` |

