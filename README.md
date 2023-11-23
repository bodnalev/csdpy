This provides a way to call CSDP from python.

CSDP is a software package for solving semidefinite programming problems. CSDP uses BLAS and LAPACK subroutines. The algorithm is a predictor-corrector version of the primal-dual barrier method of Helmberg, Rendl, Vanderbei, and Wolkowicz.

Usage:

solve_sdp(block_sizes, a, mat_inds, mat_vals)

block_sizes - list of blocks sizes

a - right hand side values of the SDP

mat_inds - flattened list of the C and A matrix values with the sparse format (mat number, block number, first coord, second coord)

mat_vals - list of the corresponding values



Original README

Copyright 1997-2018, Brian Borchers.  This copy of CSDP is made
available under the Eclipse Public License.  See LICENCE for the
details of the EPL.

CSDP is a software package for solving semidefinite programming
problems.  This project is a C code for SDP that uses BLAS and LAPACK
subroutines.  The algorithm is a predictor-corrector version of the
primal-dual barrier method of Helmberg, Rendl, Vanderbei, and
Wolkowicz.