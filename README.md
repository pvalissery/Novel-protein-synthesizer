# Random protein synthesizer

This simulator demonstrates how emergent complexity arises from bare-bones biological rules. By stripping the standard four-letter genetic alphabet down to just two nucleotides, this mini-simulation acts as a sandbox for prebiotic RNA-world scenarios.
It calculates the 8 possible 3-letter codons that can exist in a 2-base environment and maps them to a drastically reduced amino acid pool. While you won't be building highly specific catalytic enzymes with this limited toolkit, the tool shows exactly what kind of primitive, repetitive peptides can be generated from a minimalist genetic code.

## Core Features:

- **Restricted Translation:** Select your 2-base alphabet to see exactly which amino acids survive the bottleneck based on standard translation rules.
- **Dynamic Rendering:** Adjust sliders for sequence length and protein count to instantly brute-force rudimentary proteins on the screen using your restricted amino acid pool.
- **FASTA Export:** Batches up to 100 mathematically unique sequences into a downloadable FASTA file. You can drop this directly into BLASTp to check if these primitive simulated motifs match any highly conserved structural domains in modern proteins.

