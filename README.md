# Ecom ROAS Calculator

A mobile-friendly e-commerce unit economics and paid-ads calculator.

## What it calculates

- Break-even ROAS
- Break-even CPA
- Contribution margin
- Target ROAS for a desired profit margin
- Actual CPA from ROAS and AOV
- Profit per paid order
- First-order net margin
- Monthly attributed revenue, orders, costs, and estimated profit

## Core formulas

**Contribution dollars per order**

```
AOV - COGS - fulfillment - other variable costs - processing fees - refund reserve
```

**Contribution margin**

```
Contribution dollars / AOV
```

**Break-even CPA**

```
Contribution dollars per order
```

**Break-even ROAS**

```
AOV / Break-even CPA
```

Equivalent to:

```
1 / Contribution margin
```

**Target ROAS**

```
1 / (Contribution margin - desired profit margin)
```

## Run it

This project is a static site. Open `index.html` locally, or publish the repository with GitHub Pages.

For GitHub Pages: repository **Settings -> Pages -> Deploy from a branch -> main -> / (root)**.

## Important

The calculator estimates first-order contribution profit. Fixed overhead, payroll, income taxes, and lifetime value are not included unless you model them as variable per-order costs.
