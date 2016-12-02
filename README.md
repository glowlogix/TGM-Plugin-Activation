# TGM Plugin Activation
[![GitHub license](https://img.shields.io/badge/license-GPLv2-blue.svg)](https://raw.githubusercontent.com/TGMPA/TGM-Plugin-Activation/develop/LICENSE.md)
[![Build Status](https://travis-ci.org/TGMPA/TGM-Plugin-Activation.svg?branch=develop)](https://travis-ci.org/TGMPA/TGM-Plugin-Activation)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/TGMPA/TGM-Plugin-Activation/badges/quality-score.png?b=develop)](https://scrutinizer-ci.com/g/TGMPA/TGM-Plugin-Activation/?branch=develop)


**Lead Developers:**
[Thomas Griffin](https://github.com/thomasgriffin) ([@jthomasgriffin](https://twitter.com/jthomasgriffin)), [Gary Jones](https://github.com/GaryJones) ([@GaryJ](https://twitter.com/GaryJ)), [Juliette Reinders Folmer](https://github.com/jrfnl) ([@jrf_nl](https://twitter.com/jrf_nl))  
**Version:** 2.6.1
**Requires at least:** 3.7.0 
**Tested up to:** 4.5.2 

## Description

TGM Plugin Activation is a PHP library that allows you to easily require or recommend plugins for your WordPress themes (and plugins). It allows your users to install, update and even automatically activate plugins in singular or bulk fashion using native WordPress classes, functions and interfaces. You can reference bundled plugins, plugins from the WordPress Plugin Repository or even plugins hosted elsewhere on the internet.

## Installation

1. Download script from [github](https://github.com/glowlogix/TGM-Plugin-Activation.git).
2. Extract the folder and place in **inc** folder in your theme hierarchy.
3. Add a `require_once` call within `functions.php` referencing the **recommend_plugins.php** file.
4. Prefix the function in **recommend_plugins.php** file.

Detailed documentation on [how to configure TGMPA](http://tgmpluginactivation.com/configuration/) is available on the website.

## Frequently Asked Questions

See [the FAQ page](http://tgmpluginactivation.com/faq/).