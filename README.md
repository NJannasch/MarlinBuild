# MarlinBuild
Automated builds of the Marlin Firmware using GitHub Pipelines.

# Getting started

## Prerequisites
Configuration of firmware variant needs to be stored inside **configurations/< BOARDNAME >**.  
Furthermore the Pipeline needs to be adjusted as it is not fully parameterized yet.

## Firmware configurations
- Creality/Ender-3 V2
    - [Configuration.h](configurations/STM32F103RET6_creality/Configuration.h)
    - [Configuration_adv.h](configurations/STM32F103RET6_creality/Configuration_adv.h)

## Firmware download
To download pipeline artifacts the consumer needs to be authorized / logged in.  
As a workaround [https://nightly.link/](https://nightly.link/) can be used to download pipeline artifacts.

# License
Distributed under the MIT License. See LICENSE for more information.  
Configuration files can have a different license.
