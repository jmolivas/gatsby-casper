---
date: '2015-02-02'
tags:
  - Getting Started
draft:
title: Using Gatsby
author: gatsby
excerpt:
image: img/writing.jpg
updated_at: '2019-08-30T23:40:34.754Z'
---

## Quick Start

This quick start is intended for intermediate to advanced developers. For a gentler intro to Gatsby, head to our tutorial!

## Install the Gatsby CLI.

```
npm install -g gatsby-cli
```

## Create a new site.

```
gatsby new gatsby-site
```

## Change directories into site folder.

```
cd gatsby-site
```

### Start development server.

```
gatsby develop
```

> Gatsby will start a hot-reloading development environment accessible by default at localhost:8000.

Try editing the JavaScript pages in src/pages. Saved changes will live reload in the browser.

## Create a production build.

```
gatsby build
```

> Gatsby will perform an optimized production build for your site, generating static HTML and per-route JavaScript code bundles.

## Serve the production build locally.

```
gatsby serve
```

> Gatsby starts a local HTML server for testing your built site. Remember to build your site using gatsby build before using this command.
