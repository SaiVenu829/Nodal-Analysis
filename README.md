# Very Simple Nodal Analysis

A minimal Python script to calculate and plot **IPR & VLP curves** for oil well nodal analysis.

## Steps to Run
```bash
pip install numpy matplotlib
python simple_nodal.py
```
This will produce `simple_nodal_plot.png` and print the operating point.

## Key Parameters (inside script)
- `pr` : reservoir pressure (psia)
- `qmax` : max flow rate (STB/day)
- `psurf` : surface pressure (psia)
- `(a, b, c)` : VLP coefficients
