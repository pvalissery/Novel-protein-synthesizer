# Random protein synthesizer

[Click here](https://pvalissery.github.io/Novel-protein-synthesizer/)

This simulator demonstrates how emergent complexity arises from bare-bones biological rules. By stripping the standard four-letter genetic alphabet down to just two nucleotides, this mini-simulation acts as a sandbox for prebiotic RNA-world scenarios.
It calculates the 8 possible 3-letter codons that can exist in a 2-base environment and maps them to a drastically reduced amino acid pool. While you won't be building highly specific catalytic enzymes with this limited toolkit, the tool shows exactly what kind of primitive, repetitive peptides can be generated from a minimalist genetic code.

## Core Features:

- **Restricted Translation:** Select your 2-base alphabet to see exactly which amino acids survive the bottleneck based on standard translation rules.
- **Dynamic Rendering:** Adjust sliders for sequence length and protein count to instantly brute-force rudimentary proteins on the screen using your restricted amino acid pool.
- **FASTA Export:** Batches up to 100 mathematically unique sequences into a downloadable FASTA file. You can drop this directly into BLASTp to check if these primitive simulated motifs match any highly conserved structural domains in modern proteins.

## Inference: 

I threw one of the first generated sequence batches into BLASTp just to see what would happen. Surprisingly, a completely random sequence from the restricted 2-nucleotide pool found a 71% identity match to a naturally occurring protein. 

Now, quick reality check: because this tool generates short peptides (up to 20 amino acids), a 71% match isn't exactly a statistical miracle. We aren't spontaneously generating complex, folded enzymes in a browser tab. We're creating common, primitive structural motifs. But that is exactly what makes this a compelling proof-of-concept for synthetic biology. 

By artificially bottlenecking the genetic alphabet, this simulator acts as a brute-force sandbox for *de novo* peptide design. It pumps out low-complexity sequences that evolution either abandoned billions of years ago or just never bothered to try. Instead of reverse-engineering modern, highly complex proteins, you can use this as a testbed to prospect for minimalist, primitive peptides with entirely unique properties that don't exist in the current protein data bank.

![picture](example.png)