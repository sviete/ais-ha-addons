# Home Assistant Add-on Repository from AIS

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

The primary goal of this repository is to provide an add-ons for a
AI-Speaker.com users.

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/sviete/ais-ha-addons
```

## Add-ons provided by this repository

### &#10003; [AIS Cloudflared][addon-cloudflared]

![Latest Version][cloudflared-version-shield]
![Supports armhf Architecture][cloudflared-armhf-shield]
![Supports armv7 Architecture][cloudflared-armv7-shield]
![Supports aarch64 Architecture][cloudflared-aarch64-shield]
![Supports amd64 Architecture][cloudflared-amd64-shield]
![Supports i386 Architecture][cloudflared-i386-shield]

Użyj tunelu AIS Cloudflare, aby zdalnie połączyć się z Home Assistant bez otwierania jakichkolwiek portów

[:books: AIS Cloudflared add-on documentation][addon-doc-cloudflared]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

Open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: AIS Cloudflared][cloudflared-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2023 AIS

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

[addon-cloudflared]: https://github.com/sviete/ais-ha-addon-cloudflared/tree/v0.1.9
[addon-doc-cloudflared]: https://github.com/sviete/ais-ha-addon-cloudflared/blob/v0.1.9/README.md
[cloudflared-issue]: https://github.com/sviete/ais-ha-addon-cloudflared/issues
[cloudflared-version-shield]: https://img.shields.io/badge/version-v0.1.9-blue.svg
[cloudflared-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[cloudflared-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[cloudflared-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[cloudflared-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[cloudflared-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[gitlabci-shield]: https://gitlab.com/sviete/ais-ha-addons/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/sviete/ais-ha-addons/pipelines
[issue]: https://github.com/sviete/ais-ha-addons/issues
[license-shield]: https://img.shields.io/github/license/sviete/ais-ha-addons.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html