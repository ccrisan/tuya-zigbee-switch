# Supported devices

Support new devices: [contribute/porting.md](/docs/contribute/porting.md)  

### Quick-picks
- **modules:** AVATTO, Aubess, iHseno
- **switches:** Moes 1-3gang (any design, except Star Feather)

### Careful with
- generic 1-gang modules - might not support OTA conversion
- BSEED switches - too many variants (can't know which you'll receive)

### Legend

| Symbol | Meaning  |                    |                     |                |                |           |          |
| :----: | -------- | ------------------ | ------------------- | -------------- | -------------- | --------- | -------- |
|   🚧️   | Status   | 🟩️ Fully supported | 🟨️ Mostly supported | 🟧️ In progress | 🟥️ Unsupported |           |          |
|   📦️   | Build    | ✔️ Available       | ❌️ Unavailable      |                |                |           |          |
|   💡️   | Category | 🇲️ Module          | 🇸️ Switch           | 🇴️ Outlet      | 🇵 Plug        | 🇷️ Remote | 🇧️ Board | 
|   ⚡️   | Power    | 🔌️ Mains           | 🔋️ Battery          | 🔱️ USB         |                |           |          |
|   📲️   | Install  | 🛜️ Wireless        | ➿️ By wire          | ❓️ Unknown     |                |           |          |
|   🏭️   | MCU      | `TL` Telink        | `SL` Silicon Labs   | `NXP` NXP      |                |           |          |
|   🅰   | Variant  | 🅰                  | 🅱                  | 🅲             | 🅳              | 🅴        | 🅵        |

<!-------------------------------------------------------------------
  `supported.md` is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make tools/update_supported_devices`
-------------------------------------------------------------------->

> [!IMPORTANT]  
> Identify your device by **Zigbee Manufacturer** and linked threads/stores!  
> *Z2M pages are sometimes generic.*

### Device list

| 🚧 | 📦 | 💡 | ⚡️ | 📲 |  🏭  | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | :--: | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_zmy4lslw` <br> `TS0002` | [Girier 2-gang](https://www.zigbee2mqtt.io/devices/TS0002_basic.html) | [`AlEx`](https://www.aliexpress.com/item/1005006084763437.html) | [`#029`](https://github.com/romasku/tuya-zigbee-switch/issues/29) | Supported | 
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_tqlv4ug4` <br> `TS0001` | [Tuya/OXT 1-gang](https://www.zigbee2mqtt.io/devices/TS0001_switch_module.html) |   | [`#006`](https://github.com/romasku/tuya-zigbee-switch/issues/6) | Reset button on pin D2 (old) or A0 (new) | 
| 🟧 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_j1xl73iw` <br> `TS130F` | [Girier 2-gang curtains](https://www.zigbee2mqtt.io/devices/TS130F_GIRIER_DUAL.html) | [`AlEx`](https://www.aliexpress.com/item/1005003864471089.html) | [`#270`](https://github.com/romasku/tuya-zigbee-switch/issues/270) | Curtains in progress! Reset button on B4 pin, same as switch | 

Data from [`device_db.yaml`](/device_db.yaml)
