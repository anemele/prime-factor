# prime factor/filter

This crate is a utility to factorize natual number, by the SPF (smallest prime factor) sieve algorithm.

First run requires pre-build the `spf.bin` file, that's quick, finishing in seconds.

high bound is `100_000_000` and cost 400 MB disk space.

Usage

```bash
# factorize
seq 10 | pf

# filter prime
seq 10 | pf -o filter

# read from file
pf my_int_file
```
