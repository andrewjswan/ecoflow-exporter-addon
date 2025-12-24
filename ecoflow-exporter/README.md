<div align="center">
<h1>EcoFlow Exporter Add-on</h1>
</div>

## General

[![ha addon_badge](https://img.shields.io/badge/HA-Addon-blue.svg)](https://developers.home-assistant.io/docs/add-ons)
[![EcoFlow Exporter](https://img.shields.io/badge/EcoFlow-Exporter-blue.svg)](https://github.com/andrewjswan/ecoflow-exporter-addon/)
[![GitHub](https://img.shields.io/github/license/andrewjswan/ecoflow-exporter-addon?color=blue)](https://github.com/andrewjswan/ecoflow-exporter-addon/blob/main/LICENSE)
[![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/andrewjswan/ecoflow-exporter-addon?include_prereleases)](https://github.com/andrewjswan/ecoflow-exporter-addon/blob/main/ecoflow-exporter/CHANGELOG.md)
[![GitHub release Based_(latest SemVer including pre-releases)](https://img.shields.io/github/v/release/tess1o/go-ecoflow-exporter?include_prereleases&label=Based)](https://github.com/tess1o/go-ecoflow-exporter/releases)
[![StandWithUkraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)

**EcoFlow Exporter** is an implementation of a exporter for [EcoFlow](https://www.ecoflow.com/) products. To receive information from the device, exporter works the same way as the official mobile application.

## Architecture

![Supports amd64 Architecture][amd64-shield] ![Supports aarch64 Architecture][aarch64-shield] ![Supports armv7 Architecture][armv7-shield] ![Supports armhf Architecture][armhf-shield] ![Supports i386 Architecture][i386-shield]

## Installation

Add the repository URL under **Supervisor → Add-on Store** in your Home Assistant front-end:

    https://github.com/andrewjswan/ecoflow-exporter-addon/

## Confururation settings

Configure the add-on via your Home Assistant front-end under **Supervisor → Dashboard → EcoFlow Exporter**.

> [!NOTE]
> Builded from https://github.com/tess1o/go-ecoflow-exporter

> [!TIP]
> - **Documentation**: https://github.com/tess1o/go-ecoflow-exporter
> - **Quick Start**: https://github.com/tess1o/go-ecoflow-exporter/blob/main/docs/quickstart.md
> - **Enviroment variables**: https://github.com/tess1o/go-ecoflow-exporter/blob/main/docker-compose/.env

> [!TIP]
> **Andrew J.Swan - Home Assistant Add-ons**: https://github.com/andrewjswan/home-assistant-addons

[amd64-shield]: https://img.shields.io/badge/amd64-yes-blue.svg
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-blue.svg
[armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg
