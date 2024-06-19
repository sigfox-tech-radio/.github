<p align="center">
  <img src="https://github.com/sigfox-tech-radio/.github/raw/master/images/logo_readme.drawio.png" width="300"/>
</p>

The global 0G Network, powered by Sigfox 0G technology, is a low power wide area network (LPWAN) dedicated to Massive IoT. It is designed to connect devices securely at **low cost** in the most **energy-efficient** way.

In this GitHub organization you will find open-source projects related to the **radio technology** (embedded C for devices). The core repository is the **Sigfox End-Point library** but you will also find **addons** and implementation **examples** on different chipsets.

<p align="center">
  <img src="https://github.com/sigfox-tech-radio/.github/raw/master/images/organization.drawio.png" width="600"/>
</p>

## Core device library

| Repository | Description |
|:---:|:---:|
| [sigfox-ep-lib](https://github.com/sigfox-tech-radio/sigfox-ep-lib) | Core Sigfox device library |

## Addons

| Repository | Description |
|:---:|:---:|
| [sigfox-ep-addon-rfp](https://github.com/sigfox-tech-radio/sigfox-ep-addon-rfp) | RF & Protocol addon to perform Sigfox certification with RSA tool |
| [sigfox-ep-addon-ta](https://github.com/sigfox-tech-radio/sigfox-ep-addon-ta) | Type Approval addon to perform regulatory tests |

## Radio implementation examples

| Repository | Chipset vendor | Chipset reference |
|:---:|:---:|:---:|
| [sigfox-ep-rf-api-st-s2lp](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-st-s2lp) | ST Microelectronics | S2-LPQTR |
| [sigfox-ep-rf-api-semtech-lr11xx](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-semtech-lr11xx) | Semtech | LR11xx |
| [sigfox-ep-rf-api-semtech-sx126x](https://github.com/sigfox-tech-radio/sigfox-ep-rf-api-semtech-sx126x) | Semtech | SX126x |

## Full implementation examples

| Repository | Type| MCU vendor & Reference |  RFs chipsets vendors & reference |
|:---:|:---:|:---:|:---:|
| [sigfox-ep-example-holtek-bc68f2150](https://github.com/sigfox-tech-radio/sigfox-ep-example-holtek-bc68f2150) | SoC | [Holtek-BC68F2150](https://www.bestmodulescorp.com/sgb-1501-rc1.html) | [Holtek-BC68F2150](https://www.bestmodulescorp.com/sgb-1501-rc1.html) |
| [sigfox-ep-example-st-nucleo-xxxxxx](https://github.com/sigfox-tech-radio/sigfox-ep-example-st-nucleo-xxxxxx) | Multi RF | ST-[Nucleo-L053R8](https://www.st.com/en/evaluation-tools/nucleo-l053r8.html) | Semtech-LR11XX, [Semtech-SX126X](https://www.semtech.fr/products/wireless-rf/lora-connect/sx1261dvk1bas), [ST-S2LP](https://www.st.com/en/evaluation-tools/steval-fki868v2.html) |
