# rrp_distributions

rrp_distributions is a Python library for probability distributions.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install rrp_distributions.

```bash
pip install rrp_distributions
```

## Usage

```python
from rrp_distributions import Gaussian, Binomial

# create new Gaussian distribution with mean 0 and stddev 1
new_gaussian = Gaussian(0, 1)
print(new_gaussian.mean) # print mean
print(new_gaussian.stdev) # print std deviation

# create new binomial distribution
# create distribution with p=0.5 and n=20
new_binomial = Binomial(0.5, 20) 
print(new_binomial.p) # print probability
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
