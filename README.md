CurveDist is a planned open-source Sage/Python research toolkit for auditing distributional assumptions in algebraic map-to-curve and hash-to-curve constructions over finite fields.

The project focuses on elliptic-curve cryptography, finite-field computation and reproducible analysis of output distributions. The toolkit is intended to help researchers and implementers study:

image sizes;
fibre distributions;
collision probabilities;
total variation distance;
character-sum diagnostics;
inverse polynomials;
monodromy-based fixed-point predictions.

CurveDist is not intended to replace RFC 9380 or existing production hash-to-curve libraries. Instead, it aims to provide reproducible research and audit tooling for elliptic-curve encodings that may be relevant to cryptographic research, zero-knowledge protocols, pairing-based systems and security review of cryptographic primitives.

This repository is currently an early project placeholder prepared for Ethereum ESP Office Hours feedback. The project scope may be adapted based on feedback from the Ethereum ecosystem.

Planned components
Sage/Python notebooks for baseline examples;
finite-field and elliptic-curve helper routines;
fibre counting and image-size computation;
collision and distribution diagnostics;
fixed-point and monodromy prediction tools;
experiments with higher-degree map-to-curve correspondences.
Status

Early planning stage.
