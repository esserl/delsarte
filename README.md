# Computing the Picard number of weighted Delsarte surfaces

The MAGMA code in this repository provides tools for calculating the Lefschetz number of Delsarte surfaces in weighted projective 3-space.  More details are available in the companion paper "<a href = "https://arxiv.org/abs/2506.14037">Weighted surfaces with maximal Picard number</a>".  All the code in this project is by Louis Esser and Jennifer Li.

The function "DelsartePicard" computes the Lefschetz number of a well-formed, klt, Delsarte surface inside of weighted projective 3-space.  This implements an extension of an algorithm of Shioda, by expressing a given Delsarte surface as a quotient of a Fermat surface.  The program assumes the input is well-formed and klt.

The companion function "matrix_potentials" can be used to generate quasismooth Delsarte equations matching a given degree and weights.
