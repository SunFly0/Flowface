# FlowFace
Official implementation of the ECCV 2026 paper "FlowFace: Rectifying Identity Conditioning with Riemannian Geometry for Face Generation ".

## Abstract
Diffusion-based face generation commonly combines identity cues and edit conditions through Euclidean mixing at the conditioning interface.
This becomes fragile when facial attributes are coupled: naively adding feature vectors ignores their interactions, can lead to identity drift and artifacts.
We present \textbf{FlowFace}, a geometry-aware identity-conditioning framework that rectifies the Stable Diffusion conditioning geometry during training without modifying the inference sampler.
FlowFace includes (i) a dual-stream manifold encoder inspired by fiber bundles to disentangle geometry-related variation from semantic identity, (ii) a Lie-algebraic composition module based on a truncated BCH expansion to introduce an explicit interaction term between coupled edits, and (iii) a geodesic-consistency regularizer that learns a local SPD metric that encourages Euclidean operations to better correlate with a geodesic-consistent surrogate under the learned geometry.
Experiments show that FlowFace outperforms strong baselines in identity preservation, text alignment, and perceptual quality, while retaining adapter-level inference efficiency.


<!-- ## Citation
If you find our work inspiring or use our codebase in your research, please consider giving a star ⭐ and a citation ❤️. -->
