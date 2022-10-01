# Awesome Cloudless

Curated list of smart home automation devices that can operate without an internet connection and a private cloud subscription.

Admission requirements:

 - no DIY devices (but hacks and CFW are ok)
 - Bluetooth and IR-controlled devices are ok

## Why?

>>>>>
 - Independence from external services (e.g. service failure).
 - Independence from stable internet connection
 - Independence from discontinuation of products or support of them from providers
 - Sovereignty over own data
 - Usually cheaper than cloud products (no subscriptions, usually lower purchase price)

(copied from [here](https://nocloud.info/en/home/))

## Smart wall plugs

| Manufacturer | Model    | Cloudless     | Reported  |
| ------------ | -------- | ------------- | ----------|
| Wyze         | ??       | NO            | https://www.uncloud.community/t/wyze-smart-plugs/84 |
| TP-Link      | Kasa series | YES (account still req. for some features)        | https://www.tp-link.com/us/support/faq/2707/ |
| BroadLink    | SP3 (others too?) | YES ([python lib here](https://github.com/mjg59/python-broadlink), on Android use [this unoffical app](https://play.google.com/store/apps/details?id=ua.com.lavi.broadlinkclient))
| Athom        | PG01EU16A, PG01V2-EU16A-TAS | YES (Tasmota pre-installed) | https://templates.blakadder.com/preflashed.html |
| CloudFree    | P1EU | YES (Tasmota pre-installed) | https://templates.blakadder.com/preflashed.html |
| DeLOCK    | 11826, 11827 | YES (Tasmota pre-installed) | https://templates.blakadder.com/preflashed.html |
| Nous    | A5T, A1T | YES (Tasmota pre-installed) | https://templates.blakadder.com/preflashed.html |

## USB switchers

| DeLOCK    | WLAN EASY-USB Switch 11828 | YES (Tasmota pre-installed) | [https://templates.blakadder.com/preflashed.html](https://templates.blakadder.com/delock_11828.html) |
	
## Surveillance & security cameras

| Manufacturer | Model    | Cloudless     | Reported |
| ------------ | -------- | ------------- | ---------|
| Amazon       | Blink series | NO        | [official site](https://support.blinkforhome.com/en_US/f-a-q/can-i-use-my-camera-offline-without-an-internet-connection) |
| TP-Link      | Kasa series | YES (account still req. for some features)  | [official site](https://www.tp-link.com/us/support/faq/2707/) |
| EZVIZ        | all models? | YES (only live view? [Possibly more features can be unlocked](https://github.com/BaQs/pyEzviz/issues/61)) | 


## Lights

| Manufacturer | Model    | Cloudless     | Reported |
| ------------ | -------- | ------------- | ---------|
| Osram        | Retrofit RGBW | YES (uses IR) |     |
| Cloudfree    | 1000lm A21 RGBCCT Bulb	CF-LBC | YES (Tasmota pre-installed) | https://templates.blakadder.com/preflashed.html |
| Athom        | LB01 (many models) | YES (Tasmota pre-installed) | https://templates.blakadder.com/preflashed.html |

## WiFi Extenders, Bridges

| Manufacturer | Model    | Cloudless     | Reported |
| ------------ | -------- | ------------- | ---------|
| GL.iNet      | all      | [YES](https://docs.gl-inet.com/en/2/setup/repeater_manager/) (openWRT) |          |

## Vacuum cleaners

WANTED

## CFW projects

 - [Tasmota](https://templates.blakadder.com/)
 - [Gadgetbridge (for smartwatches)](https://github.com/Freeyourgadget/Gadgetbridge)
 - [Valetudo (for Vacuum cleaners)](https://github.com/Hypfer/Valetudo)
 - [Xiaomi-Dafang-Hacks (for security cameras)](https://github.com/EliasKotlyar/Xiaomi-Dafang-Hacks)


## Similar lists

 - https://www.uncloud.community/
 - https://www.reddit.com/r/homeassistant/comments/dgdldn/cloudless_wifi_devices/
 - https://www.reddit.com/r/homeautomation/comments/u1eamn/smart_devices_that_can_work_without_an_internet/
