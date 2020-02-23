#!/usr/bin/env bash
for a in *.ipynb; do mv $a `printf %04d.%s ${a%.*} ${a##*.}`;done