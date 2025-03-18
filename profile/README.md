<p align="center">
  <img src="https://github.com/sigfox-tech-radio/.github/raw/master/images/logo_readme.drawio.png" width="300"/>
</p>

The global 0G Network, powered by Sigfox 0G technology, is a low power wide area network (LPWAN) dedicated to Massive IoT. It is designed to connect devices securely at **low cost** in the most **energy-efficient** way.

In this GitHub organization you will find open-source projects related to the **radio technology** (embedded C for devices). The core repository is the **Sigfox End-Point library** but you will also find **addons** and implementation **examples** on different chipsets.

<p align="center">
  <img src="https://github.com/sigfox-tech-radio/.github/raw/master/images/organization.drawio.png" width="600"/>
</p>

## Core device library

| Repository | Description | Latest version | Documentation |
|:---:|:---:|:---:|:---:|
| [sigfox-ep-lib](https://github.com/sigfox-tech-radio/sigfox-ep-lib) | Core Sigfox device library | [v4.1](https://github.com/sigfox-tech-radio/sigfox-ep-lib/releases/tag/v4.1) | [Wiki](https://github.com/sigfox-tech-radio/sigfox-ep-lib/wiki) |

## Addons

| Repository | Description | Latest version |
|:---:|:---:|:---:|
| [sigfox-ep-addon-rfp](https://github.com/sigfox-tech-radio/sigfox-ep-addon-rfp) | RF & Protocol addon to perform Sigfox certification with RSA tool | [v2.1](https://github.com/sigfox-tech-radio/sigfox-ep-addon-rfp/releases/tag/v2.1) |
| [sigfox-ep-addon-ta](https://github.com/sigfox-tech-radio/sigfox-ep-addon-ta) | Type Approval addon to perform regulatory tests | [v2.0](https://github.com/sigfox-tech-radio/sigfox-ep-addon-ta/releases/tag/v2.0) |
| [sigfox-ep-addon-aw](https://github.com/sigfox-tech-radio/sigfox-ep-addon-aw) | Atlas WiFi addon to build WiFi geolocation frames | [v2.0](https://github.com/sigfox-tech-radio/sigfox-ep-addon-aw/releases/tag/v2.0) |

## Radio implementation examples

| Repository | Chipset vendor | Chipset reference | Latest version |
|:---:|:---:|:---:|:---:|
| [sigfox-ep-rf-api-st-s2lp](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-st-s2lp) | ST Microelectronics | S2-LPQTR | [v4.0](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-st-s2lp/releases/tag/v4.0) |
| [sigfox-ep-rf-api-semtech-lr11xx](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-semtech-lr11xx) | Semtech | LR11xx | [v3.0](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-semtech-lr11xx/releases/tag/v3.0) |
| [sigfox-ep-rf-api-semtech-sx126x](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-semtech-sx126x) | Semtech | SX126x | [v2.0](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-semtech-sx126x/releases/tag/v2.0) |
| [sigfox-ep-rf-api-st-stm32wl3x](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-st-stm32wl3x) | ST Microelectronics | STM32WL3x | [v1.0](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-st-stm32wl3x/releases/tag/v1.0) |

## Full implementation examples

| Repository | Type | MCU vendor & Reference |  RFs chipsets vendors & reference | Latest version | Documentation |
|:---:|:---:|:---:|:---:|:---:|:---:|
| [sigfox-ep-example-holtek-bc68f2150](https://github.com/sigfox-tech-radio/sigfox-ep-example-holtek-bc68f2150) | SoC | Holtek [BC68F2150](https://www.bestmodulescorp.com/sgb-1501-rc1.html) | Holtek [BC68F2150](https://www.bestmodulescorp.com/sgb-1501-rc1.html) | [v1.3](https://github.com/sigfox-tech-radio/sigfox-ep-example-holtek-bc68f2150/releases/tag/v1.3) | [Wiki](https://github.com/sigfox-tech-radio/sigfox-ep-example-holtek-bc68f2150/wiki) |
| [sigfox-ep-example-st-nucleo-xxxxxx](https://github.com/sigfox-tech-radio/sigfox-ep-example-st-nucleo-xxxxxx) | Multi RF | ST [Nucleo-L053R8](https://www.st.com/en/evaluation-tools/nucleo-l053r8.html), ST [Nucleo-WL33CC1](https://www.st.com/en/evaluation-tools/nucleo-wl33cc1.html) | ST [S2LP](https://www.st.com/en/evaluation-tools/steval-fki868v2.html), Semtech [LR11XX](https://www.semtech.com/products/wireless-rf/lora-edge/lr1110dvk1tbks), Semtech [SX126X](https://www.semtech.fr/products/wireless-rf/lora-connect/sx1261dvk1bas), ST [STM32WL3X](https://www.st.com/en/evaluation-tools/nucleo-wl33cc1.html) | [v2.1](https://github.com/sigfox-tech-radio/sigfox-ep-example-st-nucleo-xxxxxx/releases/tag/v2.1) | |
