# Rust Brighton week 5

- Plug in the hardware
- Launch `openocd`
- `cargo run`

Lights need 5v
Switch between voltages
Level switch, reference on one side
5.5
Orange 3.3v

https://github.com/smart-leds-rs/smart-leds


openocd, hold down rest as you start it
maybe thing on it previously is putting it to sleep
Error: jtag status contains invalid mode value - communication failure

PA
PB - GPIOB

Alterniative functions count in from the right.
MOSI i s4, nothing on 3m PWM3/2m no 1
into alternative function 5

HAL has spi standrard interface.
Manchester encoding. Half data rate, but simple.

Configure data rate from spec of lights
(don't need a clock - recovers the clock from the data)

Laptop power over USB





