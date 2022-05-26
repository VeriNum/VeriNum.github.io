<img src=VeriNum.png alt="VeriNum" width=384px height=288px/>
<img src=FoVeNuMe.png alt="Formally Verified Numerical Methods" width=672px height=288px/>

[Andrew W. Appel](https://www.cs.princeton.edu/~appel/), Princeton University

[David Bindel](https://www.cs.cornell.edu/~bindel/), Cornell University

[Ariel Kellison](https://ak-2485.github.io/), Cornell University

In this collection of research projects, we take a layered approach to foundational verification
of correctness and accuracy of numerical software--that is,
formal machine-checked proofs about programs (not just algorithms),
with no assumptions except specifications of instruction-set
architectures.  We build, improve, and use appropriate tools at
each layer: proving in the real numbers about discrete
algorithms; proving how floating-point algorithms approximate
real-number algorithms; reasoning about C program implementation
of floating-point algorithms; and connecting all proofs end-to-end
in Coq.

Our initial research projects (and results) are,
- [cbench_vst](https://github.com/cverified/cbench-vst)/sqrt: Squart root by Newton's Method, by Appel and Bertot.
- [VerifiedLeapfrog](https://github.com/VeriNum/VerifiedLeapfrog): A verified numerical method for an Ordinary Differential Equation, by Kellison and Appel.
- [VCFloat2](https://github.com/VeriNum/vcfloat): Floating-point error analysis in Coq, by Appel & Kellison, improvements on an earlier open-source project by Ramananandro et al.

## Bibliography

- C-language floating-point proofs layered with VST and Flocq, by Andrew W. Appel and Yves Bertot, _Journal of Formalized Reasoning_ volume 13, number 1, pages 1-16.
- Verified Numerical Methods for Ordinary Differential Equations, by Ariel E. Kellison and Andrew W. Appel, May 2022.
- VCFloat2: Floating-point Error Analysis in Coq, by Andrew W. Appel and Ariel E. Kellison, draft, April 2022.
- A Unified Coq Framework for Verifying C Programs with Floating-Point Computations, by Tahina Ramananandro,  Paul Mountcastle, Benoit Meister, and Richard Lethin, _CPP'16: 5th ACM SIGPLAN Conference on Certified Programs and Proofs,_ pages 15-26, 2016.
