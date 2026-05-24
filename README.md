# CodeFalcon's SHA3-256T Miner GUI

## How to use

1. Double-click `codefalcon-sha3-256t-v4.0-win64.exe`.
2. Fill in `stratum+tcp://: host/ip` and `Port: 3357`. `Address/Username: bc1address-sample` and `Diff/Password: x or d=1`.
4. Click `Start`.

## Quick checklist

- Pool address and port are correct.
- Username/wallet worker name is correct.
- NVIDIA driver is installed and up to date.
- Internet connection allows outbound pool traffic.

## Notes

- Algorithm is locked to `sha3-256t`.
- No extra backend executable is required.
- NVIDIA GPU and NVIDIA driver are required.
- The app saves settings automatically.

## If mining does not start

- Re-check `stratum+tcp://: host/ip` and `Port: 3357`.
- Re-check `Address/Username: bc1addresssamble` and `Diff/Password: d=1`.
- Try another pool endpoint.
- Restart the app after changing GPU driver settings.

## Recommended pool

- Dashboard: https://pythonpool.dev/dash/?coin=bc3
- Stratum: stratum+tcp://stratum.pythonpool.dev:3357
