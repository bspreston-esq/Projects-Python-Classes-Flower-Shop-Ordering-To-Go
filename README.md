# Flower Shop Ordering To Go

**Category:** Classes

## Problem

Create a flower shop application which deals in flower objects and use those flower objects in a bouquet object which can then be sold. Keep track of the number of objects and when you may need to order more.

## Solution

Flowers carry price, stock and a restock threshold; bouquets declare a composition that is priced from the catalogue plus labour. Selling decrements stock atomically (validating every line first), records an order, and the shop reports revenue and which flowers need reordering.

## How to run

Requires Python 3.8+ and no third-party packages.

```bash
python3 main.py --demo
```

## Example

```text
order for Ada: Spring Mix = $33.20
restock needed: ['tulip']
after restock, tulips: 20
revenue: $33.20
```

## Attribution

The problem statement is from [karan/Projects](https://github.com/karan/Projects), a list of practical projects that anyone can solve in any programming language (MIT License, Copyright (c) 2013 Karan Goel). The Python solution in this repository was implemented by [bspreston-esq](https://github.com/bspreston-esq).

This repository is part of the [Projects-Python-All](https://github.com/bspreston-esq/Projects-Python-All) collection.
