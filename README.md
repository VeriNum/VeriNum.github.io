# VeriNum: Formally Verified Numerical Methods

[Andrew W. Appel](https://www.cs.princeton.edu/~appel/), Princeton University

[David Bindel](https://www.cs.cornell.edu/~bindel/), Cornell University

[Ariel Kellison](https://ak-2485.github.io/), Cornell University

In this collection of research projects, we take a layered approach to foundational verification
of correctness and accuracy of numerical software---that is,
formal machine-checked proofs about programs (not just algorithms),
with no assumptions except specifications of instruction-set
architectures.  We build, improve, and use appropriate tools at
each layer: proving in the real numbers about discrete
algorithms; proving how floating-point algorithms approximate
real-number algorithms; reasoning about C program implementation
of floating-point algorithms; and connecting all proofs end-to-end
in Coq.

Our initial research projects (and results) are,
- [VerifiedLeapfrog](https://github.com/VeriNum/VerifiedLeapfrog): A verified numerical method for an Ordinary Differential Equation, by Kellison and Appel.
- [VCFloat2](https://github.com/VeriNum/vcfloat): Floating-point error analysis in Coq, improvements on an earlier open-source project by Ramananandro et al.
