# Carl's Hass.io Add-ons for Home Assistant

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]
[![Bountysource][bountysource-shield]][bountysource]
![Awesome][awesome-shield]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Hass.io allows anyone to create add-on repositories to share their add-ons for
Hass.io easily. This repository is one of those repositories, providing extra
Home Assistant add-ons for your Hass.io installation.

The primary goal of this project is to provide you (as a Hass.io /
Home Assistant user) with additional, high quality, add-ons that allow you to
take your automated home to the next level.

## Installation

Adding this add-ons repository to your Hass.io Home Assistant instance is
pretty easy. Follow [the official instructions][third-party-addons] on the
website of Home Assistant, and use the following URL:

```txt
https://github.com/hassio-addons/repository
```

## Add-ons provided by this repository


### &#10003; [UniFi Controller][addon-unifi]

![Latest Version][unifi-version-shield]
![Supports armhf Architecture][unifi-armhf-shield]
![Supports armv7 Architecture][unifi-armv7-shield]
![Supports aarch64 Architecture][unifi-aarch64-shield]
![Supports amd64 Architecture][unifi-amd64-shield]
![Supports i386 Architecture][unifi-i386-shield]
![Docker Pulls][unifi-pulls-shield]

Manage your UniFi network using a web browser

[:books: UniFi Controller add-on documentation][addon-doc-unifi]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all our other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

You have several options to get them answered:

- The Community Hass.io Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: UniFi Controller][unifi-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Adding a new add-on

Have you created an add-on that you want to list in the Repository?
Contact [Carl Halvorson][chalvorson]:


He will set up a GitHub repository and all the other plumbing,
and of course, give you developer access to your contribution.

## License

MIT License

Copyright (c) 2019 Carl Halvorson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-unifi]: https://github.com/hassio-addons/addon-unifi/tree/v0.7.1
[addon-doc-unifi]: https://github.com/hassio-addons/addon-unifi/blob/v0.7.1/README.md
[unifi-issue]: https://github.com/hassio-addons/addon-unifi/issues
[unifi-version-shield]: https://img.shields.io/badge/version-v0.7.1-blue.svg
[unifi-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/unifi.svg
[unifi-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[unifi-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[unifi-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[unifi-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[unifi-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
