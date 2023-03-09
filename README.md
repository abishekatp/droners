In this repo I am planning to write some rust code on arduino.(Just for learning)

# Project setup:
- Installing needed third party toolchains for mac - 
```
xcode-select --install # for the fist time
brew tap osx-cross/avr
brew install avr-binutils avr-gcc avrdude
```
- Install the ravedude rust crate: 
```
cargo +stable install ravedude
```
- To get this basic template we have used:
```
cargo install cargo-generate
cargo generate --git https://github.com/Rahix/avr-hal-template.git
```
References:
https://medium.com/@ninjapiraatti/programming-arduino-with-rust-on-mac-7c7536f3973d
https://blog.logrocket.com/complete-guide-running-rust-arduino/
