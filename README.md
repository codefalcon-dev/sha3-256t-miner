# CodeFalcon's SHA3-256T Miner Windows GUI & Linux non-GUI

## How to use

## Windows Miner (NVIDIA, GUI)

1. Double-click `Codefalcon-SHA3-256T-Miner-v6.0-win64.exe`.
2. Fill in:
   - `stratum+tcp:// host/ip`
   - `Port: 3357`
   - `Address/Username: bc1address-sample`
   - `Diff/Password: x` or `d=1`
3. Click `Start`.

## Linux Miner (NVIDIA, non-GUI)

- Added Linux release package for SHA3-256T mining.
- Release asset: CodeFalcon-SHA3-256T-Miner-v6.0-Linux.tar.gz
- Included binary: sha3-256t-miner
- GPU device selection supported with --devices IDX (also accepts -devices IDX).
- Example:
	./sha3-256t-miner -a sha3-256t -o stratum+tcp://stratum.pythonpool.dev:3357 -u YOUR_WALLET.YOUR_WORKER -p x --devices 0

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
- If you have more than one GPU and want to mine on multiple GPUs, open one miner instance per GPU. For example, if you have 2 GPUs, open 2 miner windows. If you have 4 GPUs, open 4 miner windows.

## If mining does not start

- Re-check the pool host/ip and `Port: 3357`.
- Re-check `Address/Username: bc1address-sample` and `Diff/Password: d=1`.
- Try another pool endpoint.
- Restart the app after changing GPU driver settings.

## Recommended pool

- Dashboard: https://pythonpool.dev/dash/?coin=bc3
- Stratum: stratum+tcp://stratum.pythonpool.dev:3357
