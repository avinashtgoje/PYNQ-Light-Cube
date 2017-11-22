# PYNQ Light Cube

## Framework

![framework](image/framework.png)

## Brief Introduction

This project shows how to write a controller in python to control peripherals connected to FPGA.We could write any peripheral drivers in FPGA to achieve real-time high speed signal processing.Thanks to PYNQ platform, we can easily wrapper the FPGA drivers into simple python code.

## Repository Organisation

```
├── hw
│   ├── ip
│   ├── lightcube.tcl
│   └── srcs
├── image
│   └── framework.png
├── notebook
│   ├── lc_const.py
│   ├── lc_pynq.py
│   ├── LightCube_Playground.ipynb
│   ├── static
│   └── templates
├── overlay
│   ├── __init__.py
│   ├── lightcube.bit
│   ├── lightcube.py
│   └── lightcube.tcl
└── README.md
```

## Get Started

```
git clone https://github.com/sonnyhcl/PYNQ-Light-Cube.git
bash PYNQ-Light-Cube/setup.sh
```

# Based On PYNQ

This project is based on PYNQ, you can find it [here](https://github.com/Xilinx/PYNQ/)
