# WebRTC welcomes patches/pulls for features and bug fixes!

For contributors external to Google, follow the instructions given in the
[Google Individual Contributor License Agreement](https://cla.developers.google.com/about/google-individual).
In all cases, contributors must sign a contributor license agreement before a contribution can be accepted.
Please complete the agreement for an [individual](https://developers.google.com/open-source/cla/individual) or
a [corporation](https://developers.google.com/open-source/cla/corporate) as appropriate.

If you plan to add a new sample or make significant changes to an existing sample, we recommend that you start by creating
a [new issue](https://github.com/webrtc/samples/issues/new) where we can discuss the details.

# How to start developing a patch, new feature or bug fix
## Clone the repo in desired folder
```bash
git clone https://github.com/webrtc/samples.git
```

## Install npm dependencies
```bash
npm install
```

## Start web server for development
```bash
npm start
```

# Testing

Some of the samples have an associated test. These are currently using [Nightwatch.JS](https://nightwatchjs.org) and
are only testing the UI of the samples. The purpose of these is to provide examples of how you can write UI tests for
your WebRTC web application.

When creating a new sample or updating an existing one, please make sure you also create, or update any existing, tests.
All tests in this repository are implemented as Nightwatch.JS UI tests, so please follow the same design in your own.

