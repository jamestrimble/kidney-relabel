# Relabel a kidney-exchange instance

This program reads a kidney-exchange instance in `.input` format from standard
input, relabels the vertices in non-increasing order of total degree, and
writes the resulting instance to standard output.

## Usage

Default (no arguments): non-increasing order.
```
python relabel.py < a.input > b.input
```

Use `-a` flag for non-decreasing order...
```
python relabel.py -a < a.input > b.input
```

... and -r flag for random order.
```
python relabel.py -r < a.input > b.input
```
