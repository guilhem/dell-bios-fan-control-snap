# dell-bios-fan-control snap packaging

## Troubleshooting

```
ioperm:: Operation not permitted
```

Plug `io-ports-control` is not connected

```bash
sudo snap connect dell-bios-fan-control:io-ports-control
```
