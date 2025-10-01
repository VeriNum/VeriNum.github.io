![VeriNum](logo_full.png)

[Andrew W. Appel](https://www.cs.princeton.edu/~appel/), Princeton University

[David Bindel](https://www.cs.cornell.edu/~bindel/), Cornell University

[Jean-Baptiste Jeannin](http://www-personal.umich.edu/~jeannin/), University of Michigan

[Karthik Duraisamy](https://aero.engin.umich.edu/people/duraisamy-karthik/), University of Michigan

--------------------------------------------------------

[Ariel Kellison](https://ak-2485.github.io/), _Consultant_

[Yichen Tao](https://www.linkedin.com/in/yichen-tao-196478286), [Sahil Bola](https://www.linkedin.com/in/bholasahil), University of Michigan, _PhD Students_

Dennis Corraliza, Cornell University, _PhD Student_

Philip Johnson-Freyd, [Samuel Pollard](https://sampollard.github.io/), [Heidi Thornquist](https://en.wikipedia.org/wiki/Heidi_Thornquist),  Sandia National Labs,  _External Collaborators_

Alumni:   [Mohit Tekriwal](https://mohittkr.github.io/), Michigan, _PhD Student_; [Josh Cohen](https://joscoh.github.io/),  _PhD Student_

----------------------------------------------------------------

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
- [cbench_vst](https://github.com/cverified/cbench-vst)/sqrt: Square root by Newton's Method, by [Appel and Bertot](https://doi.org/10.6092/issn.1972-5787/11442).
- [VerifiedLeapfrog](https://github.com/VeriNum/VerifiedLeapfrog): A verified numerical method for an Ordinary Differential Equation, by [Kellison and Appel](https://github.com/VeriNum/VerifiedLeapfrog/raw/main/Paper.pdf).
- [VCFloat2](vcfloat): Floating-point error analysis in Coq, by Appel & Kellison, improvements on an earlier open-source project by Ramananandro et al.
- [Parallel Dot Product](https://github.com/VeriNum/pardotprod), demonstrating how to use VST to verify correctness of simple shared-memory task parallelism
- [Stationary Iterative Methods](https://github.com/VeriNum/iterative_methods) with formally verified error bounds
- [Finite Element Method](https://bindel-group.github.io/simple_cfem/) verification (in progress)

## Bibliography

- [Formal Verification of COO to CSR Sparse Matrix Conversion](https://www.cs.princeton.edu/~appel/papers/coo-csr.pdf), by Andrew W. Appel, in _VSS 2025: International Workshop on Verification of Scientific Software_, 2025.
- [Deterministic and Probabilistic Rounding Error Analysis for Mixed-Precision Arithmetic on Modern Computing Units](https://doi.org/10.48550/arXiv.2411.18747), by Sahil Bhola and Karthik Duraisamy, arXiv preprint, November 2024.
- [Variance-informed Rounding Uncertainty Analysis for Floating-point Statistical Models](https://doi.org/10.48550/arXiv.2404.12556),  by Sahil Bhola and Karthik Duraisamy, arXiv preprint, April 2024.
- [VCFloat2: Floating-point Error Analysis in Coq](https://doi.org/10.1145/3636501.3636953), by Andrew W. Appel and Ariel E. Kellison, in _CPP 2024: Proceedings of the 13th ACM SIGPLAN International Conference on Certified Programs and Proofs_, pages 14–29, January 2024.
- [Verified correctness, accuracy, and convergence of a stationary iterative linear solver: Jacobi method](https://www.cs.princeton.edu/~appel/papers/jacobi.pdf), by Mohit Tekriwal, Andrew W. Appel, Ariel E. Kellison, David Bindel, and Jean-Baptiste Jeannin. _16th Conference on Intelligent Computer Mathematics_, September 2023.
- [LAProof: a library of formal accuracy and correctness proofs for sparse linear algebra programs](https://www.cs.princeton.edu/~appel/papers/LAProof.pdf), by Ariel E. Kellison, Andrew W. Appel, Mohit Tekriwal, and David Bindel, _30th IEEE International Symposium on Computer Arithmetic_, September 2023.
- [Towards verified rounding error analysis for stationary iterative methods](https://www.osti.gov/servlets/purl/2004333), by Ariel Kellison, Mohit Tekriwal, Jean-Baptiste Jeannin, and Geoffrey Hulette, in _Correctness 2022: Sixth International Workshop on Software Correctness for HPC Applications_, November 2022.
- [Verified Numerical Methods for Ordinary Differential Equations](https://github.com/VeriNum/VerifiedLeapfrog/raw/main/Paper.pdf), by Ariel E. Kellison and Andrew W. Appel, in _NSV'22: 15th International Workshop on Numerical Software Verification_, August 2022.
- [A Formal Proof of the Lax Equivalence Theorem for Finite Difference Schemes](https://doi.org/10.1007/978-3-030-76384-8_20), by Mohit Tekriwal, Karthik Duraisamy, and Jean-Baptiste Jeannin, in _Nasa Formal Methods Symposium_, pages 332-339, May 2021.
- [C-language floating-point proofs layered with VST and Flocq](https://doi.org/10.6092/issn.1972-5787/11442), by Andrew W. Appel and Yves Bertot, _Journal of Formalized Reasoning_ volume 13, number 1, pages 1-16, December 2020.

## Funding

VeriNum's various projects are supported in part by
- Department of Energy grant DE-NA0004264 "Center for AI-enabled Exascale Prediction of Long-time Events in the Multimaterial Shock-assisted Chemical Reactions" to the University of Michigan (Duraisamy and Appel).
- National Science Foundation grant 2219757 "Formally Verified Numerical Methods", to Princeton University (Appel, Principal Investigator) and grant 2219758 to Cornell University (Bindel)
- National Science Foundation grant 2219997 "Foundational Approaches for End-to-end Formal Verification of Computational Physics" to the University of Michigan (Jeannin and Duraisamy)
- U.S. Department of Energy Computational Science Graduate Fellowship (Ariel Kellison)
- Sandia National Laboratories, funding the collaboration of Sandia participants with these projects
