---
MTPE: windsonsea
date: 2024-01-11
hide:
  - toc
---

# Multicloud Management

This page provides offline packages for different versions of the Multicloud Management module.

## Download

| Version     | Architecture | File Size | Package      | Checksum File | Update Date |
|-------------| ----- |-------- |---------------| ---------- |-----------|
| [v0.15.0](../../kairship/intro/release-notes.md) | AMD 64 | 524.68 MB | [:arrow_down: kairship_v0.15.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.15.0_amd64.tar) | [:arrow_down: kairship_v0.15.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.15.0_amd64_checksum.sha512sum) | 2024-01-02 |
| [v0.14.0](../../kairship/intro/release-notes.md) | AMD 64 | 524.58 MB | [:arrow_down: kairship_v0.14.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.14.0_amd64.tar) | [:arrow_down: kairship_v0.14.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.14.0_amd64_checksum.sha512sum) | 2023-12-01 |
| [v0.13.1](../../kairship/intro/release-notes.md) | AMD 64 | 527.09 MB | [:arrow_down: kairship_v0.13.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.13.1_amd64.tar) | [:arrow_down: kairship_v0.13.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.13.1_amd64_checksum.sha512sum) | 2023-11-03 |
| [v0.13.0](../../kairship/intro/release-notes.md) | AMD 64 | 527.09 MB | [:arrow_down: kairship_v0.13.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.13.0_amd64.tar) | [:arrow_down: kairship_v0.13.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.13.0_amd64_checksum.sha512sum) | 2023-10-26 |
| [v0.12.0](../../kairship/intro/release-notes.md) | AMD 64 | 525.11 MB | [:arrow_down: kairship_v0.12.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.12.0_amd64.tar) | [:arrow_down: kairship_v0.12.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.12.0_amd64_checksum.sha512sum) | 2023-09-01 |
| [v0.11.0](../../kairship/intro/release-notes.md) | AMD64 | 486 MB | [:arrow_down: kairship_v0.11.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.11.0_amd64.tar) | [:arrow_down: kairship_v0.11.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/kairship_v0.11.0_amd64_checksum.sha512sum) | 2023-7-31 |

## Validation

To validate the integrity of the downloaded offline package and checksum file,
take v0.11.0 as an example and run the following command in the directory:

```sh
echo "$(cat kairship_v0.11.0_amd64_checksum.sha512sum)" | sha512sum -c
```

Upon successful validation, the result will be similar to:

```none
kairship_v0.11.0_amd64.tar: ok
```

## Installation

If this is your first installation, please [apply for a free trial](../../dce/license0.md) or contact us for authorization: email info@daocloud.io or call 400 002 6898.
For any license key-related inquiries, please contact the DaoCloud delivery team.
