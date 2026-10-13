# Private Credit Risk Measures

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tianci0511/fordham-private-credit-lab/blob/main/private_credit_lab_student.ipynb)

A classroom exercise on cash-flow construction, rate duration, spread duration, and duration-times-spread (DTS), using publicly disclosed Pye-Barker Fire & Safety loan terms.

## Files

- `private_credit_lab_student.ipynb`: student exercise with TODOs.

## Requirements

- Python 3.10 or newer
- Jupyter
- NumPy
- pandas

Install dependencies with:

```bash
python -m pip install jupyter numpy pandas
```

**Easiest:** click the *Open in Colab* button above, then choose **File → Save a copy in Drive** before editing.

Alternatively, open the notebook in JupyterLab, Jupyter Notebook, VS Code, or Google Colab and run the cells from top to bottom.

## Source And Data Notice

The borrower name, SOFR + 450 bps spread, 75 bp floor, and May 26, 2031 maturity are disclosed in a public [SEC Form 10-Q filing](https://www.sec.gov/Archives/edgar/data/1973476/000197347624000074/pif-20240630.htm).

The remaining-period assumption, amortisation schedule, forward curve, discount curve, valuation spread, and scenarios are synthetic teaching inputs. They are not market observations or investment advice.
