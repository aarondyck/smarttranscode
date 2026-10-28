# Smart Transcode

Smart Transcode converts a video and audio library to efficient codecs from a web page, using your GPU (NVIDIA, Intel,
AMD) or CPU. It runs as a Linux service or in Docker / Podman, and every result is verified before it replaces the
original.

**This repository is for support only. It contains no source code.** Smart Transcode is not open source.

- Website, downloads and documentation: **https://transcode.aarondyck.ca**
- Install: https://transcode.aarondyck.ca/install
- Docker image: `aarondyck/smart-transcode`

## Report a problem or ask for something

[Open an issue](../../issues/new/choose) and pick the form that fits.

1. Check the [troubleshooting pages](https://transcode.aarondyck.ca/docs/troubleshooting/) first; they are specific to
   how you run it (Linux service, Docker or Podman).
2. In Smart Transcode open **Settings → Debug → Report a problem** and press **Copy support report**. Paste it into the
   issue. It holds the version, platform, ffmpeg and encoders and the latest warnings, with folder and file paths and
   IP addresses removed. Read it before you post it; this repository is public.
3. Say what you expected, what happened, and the steps that led to it.

Please do not post passwords, API keys or private addresses in an issue.

Security problems: do not open a public issue. Use **Security → Report a vulnerability** on this repository.

## Copyright

© Aaron Dyck. All rights reserved. See [LICENSE.md](LICENSE.md) and the
[legal page](https://transcode.aarondyck.ca/legal).
