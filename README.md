# Home Server Setup

## notes

### list all images sorted by creation date

```bash
docker images --format "table {{.Repository}}\t{{.Tag}}\t{{.ID}}\t{{.CreatedAt}}\t{{.Size}}" | sort -k 4
```

### fritz.box

* blocks all domains mapped to local ip addresses by default

  to use domains in the local network add them to:

  `Home Network` > `Home Network Overview` > `Network Settings` > `DNS Rebind Protection`

## hardware

[PCPartPicker Part List](https://de.pcpartpicker.com/list/LMGFK4)

Type|Item|Price
:----|:----|:----
**CPU** | [AMD Ryzen 5 3400G 3.7 GHz Quad-Core Processor](https://de.pcpartpicker.com/product/XP6qqs/amd-ryzen-5-3400g-37-ghz-quad-core-processor-yd3400c5fhbox) | Purchased For €149.89
**CPU Cooler** | [Noctua NH-L9a-AM4 33.84 CFM CPU Cooler](https://de.pcpartpicker.com/product/DZfhP6/noctua-nh-l9a-am4-338-cfm-cpu-cooler-nh-l9a-am4) | Purchased For €41.10
**Memory** | [Crucial 8 GB (1 x 8 GB) DDR4-2666 Memory](https://de.pcpartpicker.com/product/2YdxFT/crucial-8gb-1-x-8gb-ddr4-2666-memory-ct8g4sfs8266) | Purchased For €31.54
**Memory** | [Crucial 8 GB (1 x 8 GB) DDR4-2666 Memory](https://de.pcpartpicker.com/product/2YdxFT/crucial-8gb-1-x-8gb-ddr4-2666-memory-ct8g4sfs8266) | Purchased For €31.54
**Storage** | [ADATA XPG SX6000 Pro 512 GB M.2-2280 NVME Solid State Drive](https://de.pcpartpicker.com/product/VwbwrH/adata-xpg-sx6000-pro-512-gb-m2-2280-solid-state-drive-asx6000pnp-512gt-c) | Purchased For €78.90
**Custom**| [ASRock Deskmini A300 AMD - Case, Motherboard, Power Supply](https://www.asrock.com/nettop/AMD/DeskMini%20A300%20Series/index.asp) | Purchased For €142.00
**Total** | | **€474.97**
