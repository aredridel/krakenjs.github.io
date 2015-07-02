---
title: KrakenJS -- Release the Kraken
layout: frontpage
---

A brief introduction to KrakenJS
--------------------------------

KrakenJS was developed by [PayPal] during our migration to [node.js]. It provides structure and some guidance for how to build applications, and comes with a few more [standard bells and whistles] than vanilla Express, which make it a bit more suited to robust development.

We aim to have a small core, and lots of modules that work with Kraken. We believe in small, general interfaces, and that brings a lot of power.

At its heart, Kraken is a configuration layer for Express. We chose JSON (with comments) as the configuration file format, since it's low power enough to keep configuration from being stuck in the turing tarpit of using a full programming language, leaving the door open for predictable tooling that can understand its configuration files.

[node.js]: http://nodejs.org/
[Express]: http://expressjs.com/
[PayPal]: http://paypal.com/
