# clip.cpp
CLIP inference in plain C/C++ with no extra dependencies

## WARNING
This is not ready for use yet, and it needs some more work to implement tokenization, causal attention and varification of numerical equivalence.

## Roadmap
- [x] Implement Quick GELU.
- [x] Implement causal attention in text model and varify its correctness.
- [ ] Implement tokenization.
- [ ] Implement proper bicubic interpolation.
- [ ] Seperate memory buffers for text and image models, as their memory requirements are different.
- [ ] Do benchmarks and announce the results.