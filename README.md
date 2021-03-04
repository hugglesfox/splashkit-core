# SplashKit

[![Test SplashKit Core Linux Actions Status](https://github.com/splashkit/splashkit-core/workflows/SplashKit%20Core%20Linux/badge.svg)](https://github.com/splashkit/splashkit-core/actions) [![Test SplashKit Core macOS Actions Status](https://github.com/splashkit/splashkit-core/workflows/SplashKit%20Core%20macOS/badge.svg)](https://github.com/splashkit/splashkit-core/actions) [![Test SplashKit Core Windows Actions Status](https://github.com/splashkit/splashkit-core/workflows/SplashKit%20Core%20Windows/badge.svg)](https://github.com/splashkit/splashkit-core/actions) 

Get involved:

```bash
git clone --recursive -j2 https://github.com/splashkit/splashkit.git
```

Refer to documentation guidelines [here](https://github.com/splashkit/splashkit-translator#splashkit-documentation-guidelines).

## Extending SplashKit

### Build dependencies

* c++ compiler
* cmake

#### Development on macOS

1. Install Xcode command line tools
1. Install brew
1. Install cmake
1. Clone repository
1. Build test project cmake
1. Run test project

```sh
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install cmake
git clone --recursive -j2 https://github.com/splashkit/splashkit.git
cd splashkit/projects/cmake
cmake .
make
cd ../../bin
./sktest
```
