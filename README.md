<div align="center">

# @M-Scott-Lassiter/semantic-release-github-npm-config

[![NPM Version](https://img.shields.io/npm/v/@M-Scott-Lassiter/semantic-release-github-npm-config)](https://www.npmjs.com/package/@M-Scott-Lassiter/semantic-release-github-npm-config)
[![NPM Package Size](https://img.shields.io/bundlephobia/min/@M-Scott-Lassiter/semantic-release-github-npm-config)](https://www.npmjs.com/package/@M-Scott-Lassiter/semantic-release-github-npm-config)
[![License](https://img.shields.io/github/license/M-Scott-Lassiter/@M-Scott-Lassiter/semantic-release-github-npm-config?color=blue)](https://github.com/M-Scott-Lassiter/@M-Scott-Lassiter/semantic-release-github-npm-config/blob/main/LICENSE)

---

[![Build](https://github.com/M-Scott-Lassiter/semantic-release-github-npm-config/actions/workflows/publish.yml/badge.svg)](https://github.com/M-Scott-Lassiter/semantic-release-github-npm-config/actions/workflows/publish.yml)
[![Dependency status](https://img.shields.io/librariesio/release/npm/@M-Scott-Lassiter/semantic-release-github-npm-config)](https://www.npmjs.com/package/@M-Scott-Lassiter/semantic-release-github-npm-config?activeTab=dependencies)
![Vulnerabilities](https://img.shields.io/snyk/vulnerabilities/npm/@M-Scott-Lassiter/semantic-release-github-npm-config)
[![Open Issues](https://img.shields.io/github/issues/m-scott-lassiter/semantic-release-github-npm-config/bug)](https://github.com/M-Scott-Lassiter/semantic-release-github-npm-config/labels/bug)

[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)](#envelope-contact)

</div>

<details open="open">
    <summary><b>Table of Contents</b></summary>

<!-- Note: The toc tags mark autogenerated content. Do not manually modify the content here -->

<!-- toc -->

-   [Summary](#summary)
    -   [Purpose](#purpose)
    -   [Plugins](#plugins)
    -   [Install](#install)
    -   [Usage](#usage)
    -   [Configuration](#configuration)

<!-- tocstop -->

</details>

# Summary

## Purpose

-   Provide a common repository for release configurations between projects
-   Creates or updates a [CHANGELOG.md](https://github.com/semantic-release/changelog) file that gets included in the release commit.
-   Creates a new GitHub release
-   Publishs on [NPM](https://npmjs.com)

## Plugins

This [shareable configuration](https://github.com/hexonet/semantic-release-github-npm-config/blob/master/.releaserc.json) uses the following plugins:

-   [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
-   [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
-   [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
-   [`@semantic-release/npm`](https://github.com/semantic-release/npm)
-   [`@semantic-release/github`](https://github.com/semantic-release/github)
-   [`@semantic-release/git`](https://github.com/semantic-release/git)

## Install

```bash
$ npm install --save-dev semantic-release @M-Scott-Lassiter/semantic-release-github-npm-config
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
    "extends": "@M-Scott-Lassiter/semantic-release-github-npm-config"
}
```

## Configuration

Ensure that your CI configuration has the following **_secret_** environment variables set:

-   [`GitHub env vars`](https://github.com/semantic-release/github#environment-variables)
-   [`NPM env vars`](https://github.com/semantic-release/npm#environment-variables)

See each [plugin](#plugins) documentation for required installation and configuration steps.
