# dell-bios-fan-control snap packaging

[![dell-bios-fan-control](https://snapcraft.io//dell-bios-fan-control/badge.svg)](https://snapcraft.io/dell-bios-fan-control)

## Troubleshooting

```
ioperm:: Operation not permitted
```

Plug `io-ports-control` is not connected

```bash
sudo snap connect dell-bios-fan-control:io-ports-control
```
