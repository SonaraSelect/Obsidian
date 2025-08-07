# 3 digit binary counter with select inversion

- Learned quirks of modelsim
- **CLOCK DOMAIN CROSSING** Ran into multi assignment for flashing bits with the way the first design handled flashing
- I used a clock divider, vivado didnt know it was a clock for STA so I had to go into xdc file