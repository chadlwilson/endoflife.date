---
title: nix
category: app
iconSlug: nixos
permalink: /nix
alternate_urls:
-   /nixlang
releasePolicyLink: https://nixos.org/blog/announcements.html
sortReleasesBy: "releaseCycle"
changelogTemplate: https://nixos.org/manual/nix/stable/release-notes/rl-__RELEASE_CYCLE__.html
versionCommand: nix --version
auto:
-   git: https://github.com/NixOS/nix.git
activeSupportColumn: false
releaseColumn: true
releaseDateColumn: true
releases:
-   releaseCycle: "2.9"
    latest: "2.9.1"
    eol: false
    latestReleaseDate: 2022-06-07
    releaseDate: 2022-05-30
-   releaseCycle: "2.8"
    latest: "2.8.1"
    eol: false
    latestReleaseDate: 2022-05-14
    releaseDate: 2022-04-19
-   releaseCycle: "2.7"
    latest: "2.7.0"
    eol: false
    latestReleaseDate: 2022-03-07
    releaseDate: 2022-03-07
-   releaseCycle: "2.6"
    latest: "2.6.1"
    eol: true
    latestReleaseDate: 2022-02-17
    releaseDate: 2022-01-25
-   releaseCycle: "2.5"
    latest: "2.5.1"
    eol: true
    latestReleaseDate: 2021-12-17
    releaseDate: 2021-12-13
-   releaseCycle: "2.4"
    latest: "2.4"
    eol: true
    latestReleaseDate: 2021-11-01
    releaseDate: 2021-11-01
-   releaseCycle: "2.3"
    latest: "2.3.16"
    eol: false
    latestReleaseDate: 2021-10-07
    releaseDate: 2019-09-04
-   releaseCycle: "2.2"
    latest: "2.2.2"
    eol: true
    latestReleaseDate: 2019-04-15
    releaseDate: 2019-01-11
-   releaseCycle: "2.1"
    latest: "2.1.3"
    eol: true
    latestReleaseDate: 2018-10-02
    releaseDate: 2018-09-03
-   releaseCycle: "2.0"
    latest: "2.0.4"
    eol: true
    latestReleaseDate: 2018-05-31
    releaseDate: 2018-02-22
-   releaseCycle: "1"
    latest: "1.11.16"
    eol: true
    latestReleaseDate: 2017-12-20
    releaseDate: 2012-05-11

---

> [nix](https://nixos.org/) is a cross-platform package manager that utilizes a purely functional deployment model where software is installed into unique directories generated through cryptographic hashes. It is also the name of the tool's programming language. A package's hash takes into account the dependencies, which is claimed to eliminate dependency hell. This package management model advertises more reliable, reproducible, and portable packages.

**If you're looking for NixOS, the Linux distribution powered by nix click [here](./nixos)**
