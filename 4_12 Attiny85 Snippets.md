### PLL

```
  PLLCSR |= (1 << PLLE);               // Enable PLL (64 MHz)
  _delay_us(100);                      // Wait for a steady state
  while (!(PLLCSR & (1 << PLOCK)));    // Ensure PLL lock: do nothing while the bit PLOCK in register PLLCSR is false
  PLLCSR |= (1 << PCKE);               // Enable PLL as clock source for timer 1

```

### Disable USI

```
  PRR = (1 << PRUSI);                  //disable USI to save power as we are not using it
```


### Disable Digital Input

```
  DIDR0 = (1 << ADC1D) | (1 << ADC3D); //PB2,PB3  //disable digital input in pins that do analog conversion

```