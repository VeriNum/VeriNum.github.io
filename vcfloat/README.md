# VCFloat: Floating Point Round-off Error Analysis in Coq

VCFloat is a tool for Coq proofs about floating-point round-off error,
as well as a Coq library useful for other reasoning about floating-point computations.

When calculating `x*5.7+y`
in floating-point with a fixed number of mantissa bits,
the result of `x*5.7` cannot always be represented exactly
in the same number of bits, ditto the result of the addition `+y`,
so some low-order bits must be thrown away---there is _round-off error_.
VCFloat can calculate and prove an error theorem, bounding the difference
between the floating-point calculation and the exact value one would have
gotten in the infinite-precision reals.

VCFloat 2 is rebuilt and maintained by Andrew W. Appel and Ariel E. Kellison.  VCFloat 1.0 was built by Tahina Ramananandro, Paul Mountcastle, Benoit Meister, and Richard Lethin.


## Installation and repository

Install via opam.  The package name is `coq-vcfloat` (opam publication is in progress).

VCFloat is an open-source project; the repository and license is at
[https://github.com/VeriNum/vcfloat].

## Documentation

[VCFloat Reference Manual](https://github.com/VeriNum/vcfloat/blob/master/doc/VCFloat-Manual.pdf), by Andrew W. Appel and Ariel E. Kellison

[VCFloat2: Floating-point error analysis in Coq](https://github.com/VeriNum/vcfloat/blob/master/doc/vcfloat2.pdf), preliminary draft 2022, by Appel and Kellison.

[A unified Coq framework for verifying C programs with floating-point computations](https://doi.org/10.1145/2854065.2854066), by Tahina Ramananandro, Paul Mountcastle, Benoit Meister, and Richard Lethin, in Proceedings
of the 5th ACM SIGPLAN Conference on Certified Programs and Proofs (CPP’16), pages 15–26,
2016.
