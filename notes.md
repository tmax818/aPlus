### A+ Notes

## Chapter 3 CPUs

- central processing unit (CPU) aka microprocessor.
  - it makes a computer a computer
  - have a make and model

### CPU Core Components

- use [Intel 8088](https://en.wikipedia.org/wiki/Intel_8088) as basic example

### The Man in the Box

- The man in the box is the [ALU](https://en.wikipedia.org/wiki/Arithmetic_logic_unit)

### Registers
### Clock

# 1001

## Modern CPUs



## Technology

- eight features:
  - Clock multipliers
  - 64-bit processing
    - width of the EDB
    - allows for more than 4GB of RAM
  - Virtualization suppport
  - Parallel execution
    - four stages
      - Fetch - get data from EDB
      - Decode - determine what needs to be executed
      - Execute - perform the calculation
      - Write - send it back on the EDB
    - Different circuits handle each stage
  - Mulitcore processing
  - Integrated memory controller (IMC)
  - Integrated graphics processing unit (GPU)
  - Security

- frontside bus - address bus and EDB connecting CPU to MCC and RAM.
- backside bus - connection between CPU and L2

## RAM

|RAM  |ClockSpeed | DDR I/O Speed |DDRx Speed Rating| PC Speed Rating(bits)| pins |
|-----|:--------:|:----------:|:----------:|:-----------------:|:----:|
|SDRAM |200 MHz  |200 MHz     |    N/A     |    idk   |168 (2 notches)|
|DDR   |200 MHz  |  ??        |DDR-400     |PC-3200   |184 (single notch)|
|DDR2  |200 MHz  |400 MHz     |DDR2-800    |PC2-6400  |240 (single notch)|
|DDR3  |200 MHz  |800 MHz     |DDR3-1600   |PC3-12800 |240 (single notch)|
|DDR4  |200 MHz  |1600 MT/s   |DDR4-1600   |PC4-12800 |288 (single notch)|