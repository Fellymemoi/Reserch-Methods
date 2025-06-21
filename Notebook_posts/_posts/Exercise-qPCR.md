## Analyzing qPCR DATA

### Ct (Cycle Threshold) values

Ct is the number of cycles needed for the fluorescent signal to exceed the background level. Lower Ct values indicates higher target nucleic acid amounts.

| Condition            | Tubulin | ascs  | Delta | ets   | foxA  | gcm   | NGN   | opt   | pak3  | pak4  | pitx  | SM30  | sm50  | soxC  | synB  |
|----------------------|---------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| DMSO Control         | 23.30   | 29.09 | 25.96 | 24.72 | 24.37 | 28.35 | 28.35 | 31.02 | 25.41 | 25.57 | 29.68 | 20.97 | 23.70 | 25.07 | 24.13 |
| Inhibitor treatment  | 22.72   | 28.51 | 25.54 | 24.44 | 23.72 | 28.18 | 27.35 | 31.71 | 25.29 | 25.25 | 31.72 | 21.77 | 24.81 | 24.33 | 24.06 |


### ΔCt (Delta Ct) Values

Delta Ct is the difference between the Ct of the target gene and the reference gene, normalizing for variations in starting materials.


| Condition           | Tubulin| ascs | Delta | ets  | foxA | gcm  | NGN  | opt  | pak3 | pak4 | pitx | SM30 | sm50 | soxC | synB |
|---------------------|--------|------|-------|------|------|------|------|------|------|------|------|------|------|------|------|
| DMSO Control        |        | 5.80 | 2.67  | 1.42 | 1.07 | 5.06 | 5.06 | 7.72 | 2.11 | 2.28 | 6.38 | -2.33| 0.40 | 1.78 | 0.83 |
| Inhibitor treatment |        | 5.79 | 2.82  | 1.72 | 1.00 | 5.46 | 4.63 | 8.99 | 2.58 | 2.53 | 9.01 | -0.95| 2.09 | 1.61 | 1.34 |


### ΔΔCt (Delta Delta) Values

ΔΔCt is the difference between the ΔCt of the experinmental sample and the ΔCt of the control, allowing relative gene expression calculation.

|        | Tubulin| ascs | Delta | ets  | foxA | gcm  | NGN   | opt   | pak3  | pak4  | pitx  | SM30  | sm50  | soxC  | synB  |
|--------|--------|------|-------|----- |------|------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| ΔΔCt   |        | 1.006| 0.901 | 0.814| 1.047| 0.757| 1.339 | 0.416 | 0.724 | 0.836 | 0.162 | 0.386 | 0.310 | 1.123 | 0.702 |


### Fold Change (Fold change = 2^(−ΔΔCt))

Measures changes in gene expression relative to a control using the 2^(−ΔΔCt) method.

|            | Tubulin | ascs  | Delta | ets   | foxA  | gcm   | NGN   | opt   | pak3   | pak4 | pitx  | SM30  | sm50  | soxC | synB  |
|----------- |---------|-------|-------|-------|-------|-------|-------|-------|--------|------|-------|-------|-------|------|-------|
| Fold change|         | 0.498 | 0.536 | 0.569 | 0.484 | 0.592 | 0.395 | 0.749 | 0.605  | 0.560| 0.894 | 0.765 | 0.806 | 0.459| 0.615 |


Below is a graph showing various gene expressions

![alt text](<WhatsApp Image 2025-06-22 at 00.27.19.jpeg>)