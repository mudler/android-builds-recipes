# android-builds
Android builds for various devices/ROM

## Requirements

- Docker
- [luet](https://github.com/mudler/luet)
- At least 200GB of disk space (same requirement from standard lineageos builds)

## How to build

Clone this repository and run:

```bash
luet build --tree packages lineageos/<device_name>
```

At the moment, only chiron is available.

### Example

Build chiron lineageos 18.1:

```bash
luet build --tree packages lineageos/chiron@18.1
```
