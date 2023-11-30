# pytha_leo.aleo


```
program pangkat_hitung.aleo {
    // The main function 'calculate_power'.
    // You can try this function by running:
    // leo run calculate_power 2u32 3u32

    transition calculate_power(base: u32, exponent: u32) -> u32 {
        return base.pow(exponent);
    }
}
```

```
leo run calculate_power 2u32 3u32
```