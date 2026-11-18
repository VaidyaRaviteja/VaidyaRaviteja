![Raviteja Vaidya — Embedded Systems Engineer](https://raw.githubusercontent.com/VaidyaRaviteja/VaidyaRaviteja/59a9b1ff9e53ab086a1378c523c4ecb60d1167a1/assets/profile-aurora.svg)

I’m an **Embedded Systems Engineer at Inductron Energy** in **Masjid Banda, Hyderabad**, where I’ve worked since July 2026. This is my personal firmware workbench. I use small STM32 projects and C programs to explore how a microcontroller reads a pin, measures a signal, and communicates with another device.

## STM32 peripheral projects

| Peripheral | What to explore |
| --- | --- |
| GPIO · Digital input and output | Start with [blinking an LED](https://github.com/VaidyaRaviteja/STM32-Learning/tree/main/MyFirstBlink), then explore the [GPIO project](https://github.com/VaidyaRaviteja/STM32-Learning/tree/main/GPIO). |
| ADC · Analog-to-digital converter | Explore how the [ADC project](https://github.com/VaidyaRaviteja/STM32-Learning/tree/main/ADC) configures the peripheral that turns an analog voltage into a digital reading. |
| UART · Serial communication | Open the [UART project](https://github.com/VaidyaRaviteja/STM32-Learning/tree/main/UART) to explore the setup for serial communication. |

[![Button debounce — Embedded C and GPIO](https://raw.githubusercontent.com/VaidyaRaviteja/VaidyaRaviteja/59a9b1ff9e53ab086a1378c523c4ecb60d1167a1/assets/debounce-cover.svg)](https://github.com/VaidyaRaviteja/embedded-c-learning/blob/main/embedded-c/gpio_button_debounce.c)

**When does a button press count?** In my C simulation, the orange trace follows six readings: `0 1 0 1 1 1`. The first high disappears on the next sample. The last three highs agree, so the accepted state, shown in green, changes on the sixth sample.

[Read the debounce code](https://github.com/VaidyaRaviteja/embedded-c-learning/blob/main/embedded-c/gpio_button_debounce.c) · [Explore timer prescalers](https://github.com/VaidyaRaviteja/embedded-c-learning/blob/main/embedded-c/timer_prescaler.c) · [See how interrupt flags are handled](https://github.com/VaidyaRaviteja/embedded-c-learning/blob/main/embedded-c/interrupt_flag_handling.c)

I enjoy comparing notes on STM32 peripherals and embedded C. [Connect with me on LinkedIn](https://www.linkedin.com/in/raviteja-vaidya/).
