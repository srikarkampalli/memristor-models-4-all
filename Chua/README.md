## About 

| Model Class | Model Language | Simulator |
|---|---|---|
|SPICE Subcircuit|SPICE|LTSpice|

This memristor model was built in LTSpice and was based on the theoretical framework proposed by Leon Chua in 1971. In his paper, he proposes a model of the memristor with a M-R mutator and a nonlinear resister. In his figures, he shows a realization of the M-R mutator and nonlinear resistor based on electronic components from the 1970s.

The .lib file contains the SPICE models for the electronic components used in the memristor realization, and are based off of datasheets on the Internet that I found. If you look at Chua_Design_LTSpice, there is a potentiometer with the wiper constantly adjusted to change memristor behavior.

Although this is an impractical memristor emulator (since then, companies like Knowm and HP Lab have made physical memristors), it's still historically important. The voltage source stayed true to the paper, with a 10V amplitude at 63 Hz.

## Sources

1. Original Paper from Leon Chua, 1971: [Paper](https://www.cpmt.org/scv/meetings/chua.pdf)

## How to Run Model

1. Download LTSpice from the official website.
2. Open the memristor model file in LTSpice.
3. Run the simulation. (Alt+R)
