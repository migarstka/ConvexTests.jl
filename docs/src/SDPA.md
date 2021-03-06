Table of contents:

```@contents
Pages = ["SDPA.md"]
Depth = 4
```


Compilation warmup gives an estimate of 26 seconds of compilation time.

## SDPA `PARAMETER_DEFAULT`
These tests were run on March 3, 2020 at 17:18 (UTC).

Tests with SDPA via SDPA.jl.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 1 minute, 31 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">373</td>
<td style="text-align:center;color:red;">17</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">390</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">139</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">97</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">59</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">50</td>
<td style="text-align:center;color:red;">14</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr></table>
```

### Errors

```julia
Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:209
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 18.152102027357614 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:222
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 18.96542138093355 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_neg_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:143
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 0.9847759806458971 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:190
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: 2.9936547752587583 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:191
  Expression: ≈(evaluate(x), ones(3, 3), atol=atol, rtol=rtol)
   Evaluated: [1.0035306380823386 1.001956861967301 1.0019568621555663; 1.0019568621928556 1.00353063627972 1.0019568611278373; 1.0019568633251765 1.0019568634616007 1.0035306353820488] ≈ [1.0 1.0 1.0; 1.0 1.0 1.0; 1.0 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:200
  Expression: ≈(p.optval, 8.4853, atol=atol, rtol=rtol)
   Evaluated: 8.45125099774496 ≈ 8.4853 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:214
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 3.994593686072978 ≈ 3.9979070973684436 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:228
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 8.436082957101833 ≈ 8.234379113931876 (atol=0.001, rtol=0.0)

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:351
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:352
  Expression: ≈(evaluate(ρ), [1.0 0.0; 0.0 1.0], atol=atol, rtol=rtol)
   Evaluated: Complex{Float64}[0.9659901969134808 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.9659901969134808 + 0.0im] ≈ [1.0 0.0; 0.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:353
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -1080.5553501764657 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:124
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 3.994593686072978 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:133
  Expression: ≈(p.optval, 1.5, atol=atol, rtol=rtol)
   Evaluated: 1.493549820758451 ≈ 1.5 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:134
  Expression: ≈((p.constraints[1]).dual, im, atol=atol, rtol=rtol)
   Evaluated: 0.0 + 1.0031736424933193im ≈ im (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:135
  Expression: ≈((p.constraints[2]).dual, 0.75, atol=atol, rtol=rtol)
   Evaluated: 0.7451880887254957 + 0.0im ≈ 0.75 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:163
  Expression: ≈(p.optval, 7, atol=atol, rtol=rtol)
   Evaluated: 6.881464557240665 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:164
  Expression: ≈((evaluate(matrixfrac(x, P)))[1], 7, atol=atol, rtol=rtol)
   Evaluated: 7.0995827842471595 ≈ 7 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            92.0s / 98.2%           8.50GiB / 98.8%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 affine                     1    28.3s  31.4%   28.3s   2.79GiB  33.2%  2.79GiB
   affine_Partial_t...      1    2.97s  3.28%   2.97s    300MiB  3.49%   300MiB
   affine_permutedd...      1    2.72s  3.01%   2.72s    324MiB  3.77%   324MiB
   affine_dot_multi...      1    2.42s  2.68%   2.42s    176MiB  2.05%   176MiB
   affine_multiply_...      1    2.09s  2.31%   2.09s    212MiB  2.47%   212MiB
   affine_hcat_atom         1    1.97s  2.18%   1.97s    185MiB  2.15%   185MiB
   affine_transpose...      1    1.97s  2.18%   1.97s    173MiB  2.01%   173MiB
   affine_vcat_atom         1    1.28s  1.42%   1.28s    100MiB  1.17%   100MiB
   affine_Diagonal_...      1    1.14s  1.26%   1.14s    108MiB  1.26%   108MiB
   affine_add_atom          1    1.08s  1.19%   1.08s   67.6MiB  0.79%  67.6MiB
   affine_satisfy_p...      1    1.06s  1.17%   1.06s   57.7MiB  0.67%  57.7MiB
   affine_conv_atom         1    850ms  0.94%   850ms   54.3MiB  0.63%  54.3MiB
   affine_index_atom        1    626ms  0.69%   626ms   40.8MiB  0.47%  40.8MiB
   affine_dot_atom          1    598ms  0.66%   598ms   25.7MiB  0.30%  25.7MiB
   affine_reshape_atom      1    554ms  0.61%   554ms   28.2MiB  0.33%  28.2MiB
   affine_dualvalue         1    429ms  0.47%   429ms   33.7MiB  0.39%  33.7MiB
   affine_sum_atom          1    384ms  0.43%   384ms   31.4MiB  0.37%  31.4MiB
   affine_kron_atom         1    280ms  0.31%   280ms   20.0MiB  0.23%  20.0MiB
   affine_diag_atom         1    151ms  0.17%   151ms   14.5MiB  0.17%  14.5MiB
   affine_dot_atom_...      1    108ms  0.12%   108ms   5.04MiB  0.06%  5.04MiB
   affine_negate_atom       1    103ms  0.11%   103ms   3.85MiB  0.04%  3.85MiB
   affine_trace_atom        1   70.0ms  0.08%  70.0ms   2.68MiB  0.03%  2.68MiB
 socp                       1    24.0s  26.5%   24.0s   2.21GiB  26.4%  2.21GiB
   socp_dual_minima...      1    6.27s  6.94%   6.27s    489MiB  5.69%   489MiB
   socp_quad_form_atom      1    2.75s  3.05%   2.75s   33.4MiB  0.39%  33.4MiB
   socp_rational_no...      1    1.67s  1.85%   1.67s    136MiB  1.58%   136MiB
   socp_sum_squares...      1    1.22s  1.35%   1.22s    106MiB  1.23%   106MiB
   socp_inv_pos_atom        1    934ms  1.03%   934ms   70.3MiB  0.82%  70.3MiB
   socp_dual_norm_2...      1    759ms  0.84%   759ms   65.9MiB  0.77%  65.9MiB
   socp_rational_no...      1    717ms  0.79%   717ms   58.6MiB  0.68%  58.6MiB
   socp_quad_over_l...      1    646ms  0.72%   646ms   30.6MiB  0.36%  30.6MiB
   socp_huber_atom          1    493ms  0.55%   493ms   51.4MiB  0.60%  51.4MiB
   socp_fix_multipl...      1    485ms  0.54%   485ms   33.6MiB  0.39%  33.6MiB
   socp_norm_consis...      1    484ms  0.54%   484ms   28.4MiB  0.33%  28.4MiB
   socp_dual_froben...      1    397ms  0.44%   397ms   26.7MiB  0.31%  26.7MiB
   socp_geo_mean_atom       1    367ms  0.41%   367ms   25.6MiB  0.30%  25.6MiB
   socp_fix_and_fre...      1    349ms  0.39%   349ms   30.5MiB  0.35%  30.5MiB
   socp_square_atom         1    344ms  0.38%   344ms   14.9MiB  0.17%  14.9MiB
   socp_rational_no...      1    163ms  0.18%   163ms   10.3MiB  0.12%  10.3MiB
   socp_sqrt_atom           1   55.1ms  0.06%  55.1ms   1.10MiB  0.01%  1.10MiB
 sdp                        1    17.9s  19.8%   17.9s   1.53GiB  18.3%  1.53GiB
   sdp_operator_nor...      1    3.22s  3.56%   3.22s    258MiB  3.01%   258MiB
   sdp_Partial_trace        1    2.34s  2.59%   2.34s    226MiB  2.63%   226MiB
   sdp_matrix_frac_...      1    1.32s  1.46%   1.32s    100MiB  1.16%   100MiB
   sdp_matrix_frac_...      1    1.15s  1.27%   1.15s   82.8MiB  0.96%  82.8MiB
   sdp_sum_largest_...      1    989ms  1.09%   989ms   53.2MiB  0.62%  53.2MiB
   sdp_dual_lambda_...      1    924ms  1.02%   924ms   81.9MiB  0.95%  81.9MiB
   sdp_Complex_Vari...      1    761ms  0.84%   761ms   36.4MiB  0.42%  36.4MiB
   sdp_Issue_198            1    658ms  0.73%   658ms   52.1MiB  0.61%  52.1MiB
   sdp_socp_sumsqua...      1    647ms  0.72%   647ms   54.7MiB  0.64%  54.7MiB
   sdp_lambda_min_atom      1    629ms  0.70%   629ms   44.4MiB  0.52%  44.4MiB
   sdp_nuclear_norm...      1    457ms  0.51%   457ms   37.1MiB  0.43%  37.1MiB
   sdp_socp_norm2_atom      1    394ms  0.44%   394ms   23.7MiB  0.28%  23.7MiB
   sdp_sdp_variables        1    279ms  0.31%   279ms   24.1MiB  0.28%  24.1MiB
   sdp_socp_abs_atom        1    265ms  0.29%   265ms   16.8MiB  0.20%  16.8MiB
   sdp_kron_atom            1    207ms  0.23%   207ms   21.4MiB  0.25%  21.4MiB
   sdp_sigma_max_atom       1    156ms  0.17%   156ms   13.8MiB  0.16%  13.8MiB
   sdp_Real_Variabl...      1    145ms  0.16%   145ms   5.72MiB  0.07%  5.72MiB
   sdp_sdp_constraints      1    145ms  0.16%   145ms   11.1MiB  0.13%  11.1MiB
 constant                   1    10.1s  11.2%   10.1s   0.97GiB  11.6%  0.97GiB
   constant_fix!_wi...      1    3.43s  3.79%   3.43s    287MiB  3.34%   287MiB
   constant_Issue_166       1    3.16s  3.50%   3.16s    333MiB  3.87%   333MiB
   constant_Issue_228       1    944ms  1.04%   944ms   70.1MiB  0.82%  70.1MiB
   constant_fix!_wi...      1    558ms  0.62%   558ms   45.0MiB  0.52%  45.0MiB
   constant_Test_do...      1    334ms  0.37%   334ms   19.2MiB  0.22%  19.2MiB
   constant_fix!_an...      1    279ms  0.31%   279ms   20.2MiB  0.24%  20.2MiB
 lp                         1    10.0s  11.1%   10.0s    907MiB  10.6%   907MiB
   lp_dotsort_atom          1    4.44s  4.92%   4.44s    368MiB  4.28%   368MiB
   lp_min_atom              1    680ms  0.75%   680ms   47.0MiB  0.55%  47.0MiB
   lp_sumlargest_atom       1    618ms  0.68%   618ms   49.7MiB  0.58%  49.7MiB
   lp_sumsmallest_atom      1    537ms  0.59%   537ms   46.4MiB  0.54%  46.4MiB
   lp_max_atom              1    461ms  0.51%   461ms   38.3MiB  0.45%  38.3MiB
   lp_minimum_atom          1    345ms  0.38%   345ms   28.3MiB  0.33%  28.3MiB
   lp_dual_abs_atom         1    280ms  0.31%   280ms   18.8MiB  0.22%  18.8MiB
   lp_maximum_atom          1    242ms  0.27%   242ms   12.8MiB  0.15%  12.8MiB
   lp_neg_atom              1    229ms  0.25%   229ms   11.8MiB  0.14%  11.8MiB
   lp_pos_atom              1    104ms  0.12%   104ms   6.38MiB  0.07%  6.38MiB
   lp_dual_norm_inf...      1    101ms  0.11%   101ms   3.99MiB  0.05%  3.99MiB
   lp_dual_norm_1_atom      1   75.9ms  0.08%  75.9ms   3.64MiB  0.04%  3.64MiB
   lp_hinge_loss_atom       1    368μs  0.00%   368μs   49.7KiB  0.00%  49.7KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## SDPA `PARAMETER_UNSTABLE_BUT_FAST`
These tests were run on March 3, 2020 at 17:18 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 965 milliseconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">387</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">390</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">139</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">97</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">61</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">62</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr></table>
```

### Errors

```julia
Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:129
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: 2.9882133696228266 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:351
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:353
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -0.015685407552428726 ≈ 0 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            986ms / 97.7%            106MiB / 99.3%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 affine                     1    331ms  34.3%   331ms   41.1MiB  39.2%  41.1MiB
   affine_Partial_t...      1    207ms  21.5%   207ms   26.7MiB  25.5%  26.7MiB
   affine_permutedd...      1   30.8ms  3.20%  30.8ms    672KiB  0.63%   672KiB
   affine_dot_multi...      1   11.6ms  1.21%  11.6ms   1.68MiB  1.60%  1.68MiB
   affine_multiply_...      1   10.1ms  1.05%  10.1ms   1.38MiB  1.32%  1.38MiB
   affine_satisfy_p...      1   7.34ms  0.76%  7.34ms    880KiB  0.82%   880KiB
   affine_dualvalue         1   6.88ms  0.71%  6.88ms    843KiB  0.78%   843KiB
   affine_index_atom        1   6.31ms  0.66%  6.31ms   1.19MiB  1.13%  1.19MiB
   affine_add_atom          1   6.19ms  0.64%  6.19ms    685KiB  0.64%   685KiB
   affine_transpose...      1   5.99ms  0.62%  5.99ms    918KiB  0.85%   918KiB
   affine_reshape_atom      1   5.73ms  0.60%  5.73ms    924KiB  0.86%   924KiB
   affine_Diagonal_...      1   5.42ms  0.56%  5.42ms    739KiB  0.69%   739KiB
   affine_sum_atom          1   5.35ms  0.56%  5.35ms    824KiB  0.77%   824KiB
   affine_diag_atom         1   3.92ms  0.41%  3.92ms    638KiB  0.59%   638KiB
   affine_hcat_atom         1   3.74ms  0.39%  3.74ms    732KiB  0.68%   732KiB
   affine_conv_atom         1   3.61ms  0.37%  3.61ms    562KiB  0.52%   562KiB
   affine_vcat_atom         1   3.25ms  0.34%  3.25ms    808KiB  0.75%   808KiB
   affine_trace_atom        1   1.86ms  0.19%  1.86ms    259KiB  0.24%   259KiB
   affine_dot_atom_...      1   1.80ms  0.19%  1.80ms    261KiB  0.24%   261KiB
   affine_dot_atom          1   1.77ms  0.18%  1.77ms    237KiB  0.22%   237KiB
   affine_negate_atom       1   1.59ms  0.17%  1.59ms    222KiB  0.21%   222KiB
   affine_kron_atom         1    185μs  0.02%   185μs   30.2KiB  0.03%  30.2KiB
 socp                       1    321ms  33.3%   321ms   24.4MiB  23.2%  24.4MiB
   socp_rational_no...      1    122ms  12.6%   122ms   9.02MiB  8.60%  9.02MiB
   socp_dual_froben...      1   37.3ms  3.88%  37.3ms   1.38MiB  1.31%  1.38MiB
   socp_dual_norm_2...      1   22.5ms  2.33%  22.5ms   1.63MiB  1.55%  1.63MiB
   socp_square_atom         1   22.2ms  2.30%  22.2ms   1.32MiB  1.26%  1.32MiB
   socp_inv_pos_atom        1   21.0ms  2.18%  21.0ms   1.74MiB  1.66%  1.74MiB
   socp_rational_no...      1   20.8ms  2.16%  20.8ms   2.14MiB  2.04%  2.14MiB
   socp_rational_no...      1   14.4ms  1.50%  14.4ms   1.30MiB  1.23%  1.30MiB
   socp_quad_form_atom      1   11.3ms  1.17%  11.3ms   0.96MiB  0.92%  0.96MiB
   socp_fix_multipl...      1   11.1ms  1.16%  11.1ms   1.00MiB  0.95%  1.00MiB
   socp_dual_minima...      1   8.39ms  0.87%  8.39ms    954KiB  0.89%   954KiB
   socp_geo_mean_atom       1   6.95ms  0.72%  6.95ms    565KiB  0.53%   565KiB
   socp_huber_atom          1   6.22ms  0.65%  6.22ms    646KiB  0.60%   646KiB
   socp_sum_squares...      1   5.82ms  0.60%  5.82ms    433KiB  0.40%   433KiB
   socp_fix_and_fre...      1   5.39ms  0.56%  5.39ms    672KiB  0.63%   672KiB
   socp_quad_over_l...      1   4.77ms  0.50%  4.77ms    512KiB  0.48%   512KiB
   socp_norm_consis...      1    302μs  0.03%   302μs   58.9KiB  0.05%  58.9KiB
   socp_sqrt_atom           1   63.8μs  0.01%  63.8μs   22.3KiB  0.02%  22.3KiB
 lp                         1    148ms  15.3%   148ms   19.7MiB  18.7%  19.7MiB
   lp_dotsort_atom          1   39.8ms  4.13%  39.8ms   1.22MiB  1.16%  1.22MiB
   lp_max_atom              1   29.2ms  3.03%  29.2ms   5.23MiB  4.99%  5.23MiB
   lp_min_atom              1   27.9ms  2.89%  27.9ms   5.23MiB  4.98%  5.23MiB
   lp_minimum_atom          1   12.8ms  1.33%  12.8ms   2.27MiB  2.16%  2.27MiB
   lp_sumsmallest_atom      1   8.94ms  0.93%  8.94ms   1.81MiB  1.73%  1.81MiB
   lp_sumlargest_atom       1   6.51ms  0.68%  6.51ms   1.11MiB  1.06%  1.11MiB
   lp_pos_atom              1   6.27ms  0.65%  6.27ms    472KiB  0.44%   472KiB
   lp_dual_abs_atom         1   4.60ms  0.48%  4.60ms    665KiB  0.62%   665KiB
   lp_dual_norm_1_atom      1   4.05ms  0.42%  4.05ms    369KiB  0.34%   369KiB
   lp_neg_atom              1   2.94ms  0.31%  2.94ms    377KiB  0.35%   377KiB
   lp_dual_norm_inf...      1   2.34ms  0.24%  2.34ms    414KiB  0.39%   414KiB
   lp_maximum_atom          1   2.22ms  0.23%  2.22ms    441KiB  0.41%   441KiB
   lp_hinge_loss_atom       1   47.4μs  0.00%  47.4μs   21.4KiB  0.02%  21.4KiB
 sdp                        1    142ms  14.7%   142ms   17.1MiB  16.3%  17.1MiB
   sdp_sum_largest_...      1   34.5ms  3.58%  34.5ms   3.82MiB  3.64%  3.82MiB
   sdp_sdp_variables        1   17.3ms  1.80%  17.3ms   1.68MiB  1.60%  1.68MiB
   sdp_dual_lambda_...      1   9.52ms  0.99%  9.52ms   1.16MiB  1.10%  1.16MiB
   sdp_Issue_198            1   9.05ms  0.94%  9.05ms    688KiB  0.64%   688KiB
   sdp_socp_sumsqua...      1   7.32ms  0.76%  7.32ms    490KiB  0.46%   490KiB
   sdp_Complex_Vari...      1   6.71ms  0.70%  6.71ms   1.71MiB  1.63%  1.71MiB
   sdp_Real_Variabl...      1   5.70ms  0.59%  5.70ms   1.06MiB  1.01%  1.06MiB
   sdp_nuclear_norm...      1   5.70ms  0.59%  5.70ms    853KiB  0.79%   853KiB
   sdp_Partial_trace        1   5.21ms  0.54%  5.21ms    709KiB  0.66%   709KiB
   sdp_matrix_frac_...      1   5.07ms  0.53%  5.07ms    637KiB  0.59%   637KiB
   sdp_socp_norm2_atom      1   4.94ms  0.51%  4.94ms    354KiB  0.33%   354KiB
   sdp_socp_abs_atom        1   4.82ms  0.50%  4.82ms    392KiB  0.36%   392KiB
   sdp_operator_nor...      1   4.75ms  0.49%  4.75ms    629KiB  0.59%   629KiB
   sdp_sigma_max_atom       1   4.74ms  0.49%  4.74ms    629KiB  0.59%   629KiB
   sdp_lambda_min_atom      1   4.49ms  0.47%  4.49ms    511KiB  0.48%   511KiB
   sdp_kron_atom            1   4.09ms  0.42%  4.09ms    851KiB  0.79%   851KiB
   sdp_matrix_frac_...      1   3.95ms  0.41%  3.95ms    569KiB  0.53%   569KiB
   sdp_sdp_constraints      1   3.75ms  0.39%  3.75ms    403KiB  0.38%   403KiB
 constant                   1   22.0ms  2.28%  22.0ms   2.75MiB  2.62%  2.75MiB
   constant_Test_do...      1   5.11ms  0.53%  5.11ms    662KiB  0.62%   662KiB
   constant_fix!_wi...      1   4.55ms  0.47%  4.55ms    626KiB  0.58%   626KiB
   constant_fix!_wi...      1   3.89ms  0.40%  3.89ms    499KiB  0.46%   499KiB
   constant_Issue_228       1   3.73ms  0.39%  3.73ms    436KiB  0.41%   436KiB
   constant_Issue_166       1   2.78ms  0.29%  2.78ms    276KiB  0.26%   276KiB
   constant_fix!_an...      1   1.79ms  0.19%  1.79ms    261KiB  0.24%   261KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## SDPA `PARAMETER_STABLE_BUT_SLOW`
These tests were run on March 3, 2020 at 17:18 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 2 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">308</td>
<td style="text-align:center;color:red;">82</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">390</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">21</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_166</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_228</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_vectors</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_complex_numbers</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Test_double_fix!</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_and_multiply</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">126</td>
<td style="text-align:center;color:red;">13</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_satisfy_problems</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_transpose_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_diag_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_conv_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style="text-align:center;color:green;">17</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">19</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_hcat_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_vcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_index_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_Partial_transpose</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_add_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dualvalue</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_sum_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_reshape_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_multiply_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_trace_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_negate_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">76</td>
<td style="text-align:center;color:red;">21</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_dual_minimal_norm_solutions</td>
<td style="text-align:center;color:green;">15</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">15</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_sum_squares_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_fix_and_free_addition</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_inv_pos_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_quad_over_lin_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_quad_form_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_fix_multiplication</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_huber_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_rational_norm_dual_norm</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_rational_norm_atom_sum</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_rational_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_square_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_dual_frobenius_norm_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_sqrt_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_dual_norm_2_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">15</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_geo_mean_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_norm_consistent_with_Base_for_matrix_variables</td>
<td style="text-align:center;color:green;">8</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">8</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">49</td>
<td style="text-align:center;color:red;">13</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">36</td>
<td style="text-align:center;color:red;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr></table>
```

### Errors

```julia
Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:134
  Expression: ≈(prob.optval, 1.25, atol=atol, rtol=rtol)
   Evaluated: NaN ≈ 1.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:135
  Expression: ≈(evaluate(real(y * sum(x))), 1.25, atol=atol, rtol=rtol)
   Evaluated: NaN ≈ 1.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:136
  Expression: ≈(real(evaluate(x)), 0.5 * ones(5), atol=atol, rtol=rtol)
   Evaluated: [NaN, NaN, NaN, NaN, NaN] ≈ [0.5, 0.5, 0.5, 0.5, 0.5] (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_complex_numbers:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:100
  Expression: ≈(prob.optval, 0.25, atol=atol, rtol=rtol)
   Evaluated: NaN ≈ 0.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_complex_numbers:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:101
  Expression: ≈(evaluate(real(x * y)), 0.25, atol=atol, rtol=rtol)
   Evaluated: NaN ≈ 0.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_complex_numbers:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:102
  Expression: ≈(real(evaluate(x)), 0.5, atol=atol, rtol=rtol)
   Evaluated: NaN ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset constant_Test_double_fix!:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:62
  Expression: ≈(prob.optval, 0.5, atol=atol, rtol=rtol)
   Evaluated: -3.7689660161189877 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset affine_satisfy_problems:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:566
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset affine_satisfy_problems:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:573
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset affine_conv_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:532
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -27.504778994853975 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_conv_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:545
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -27.504778994853975 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:392
  Expression: ≈(p.optval, 11 / 6, atol=atol, rtol=rtol)
   Evaluated: 47.25696284119111 ≈ 1.8333333333333333 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:393
  Expression: ≈(evaluate(sum((dot(/))(x, [1 2 3]))), 11 / 6, atol=atol, rtol=rtol)
   Evaluated: 1.1036225979526837 ≈ 1.8333333333333333 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:459
  Expression: ≈(evaluate(sum(x) + sum([y fill(4.0, 4)])), 96, atol=atol, rtol=rtol)
   Evaluated: 43.43131345510483 ≈ 96 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:460
  Expression: ≈(evaluate([x y fill(2.0, (4, 2))]), fill(2.0, (4, 12)), atol=atol, rtol=rtol)
   Evaluated: [0.6857828311622143 0.6857828348875046 … 2.0 2.0; 0.6857828348875046 0.6857828423380852 … 2.0 2.0; 0.6857828348875046 0.6857828348875046 … 2.0 2.0; 0.6857828348875046 0.6857828348875046 … 2.0 2.0] ≈ [2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0] (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:265
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: -11.369040628240487 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:266
  Expression: ≈((evaluate(sum(x) - 2 * x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 6.687629520893097 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:33
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: -12865.483990179926 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:63
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -519.1957939158169 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:72
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -519.1957939158169 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:166
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: -494.11877922701177 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:167
  Expression: ≈(evaluate(sum(invpos(x))), 2, atol=atol, rtol=rtol)
   Evaluated: 2.1498897106100494 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:175
  Expression: ≈(x.value, fill(3.0, (3, 1)), atol=atol, rtol=rtol)
   Evaluated: [2.3419660553336143; 2.0218029022216797; 2.3247364908456802] ≈ [3.0; 3.0; 3.0] (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:176
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: -24.382328300328346 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:177
  Expression: ≈(evaluate(sum((dot(/))([3, 6, 9], x))), 6, atol=atol, rtol=rtol)
   Evaluated: 8.120029857213023 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:232
  Expression: ≈(p.optval, 6.1464, atol=atol, rtol=rtol)
   Evaluated: -18.342311685838155 ≈ 6.1464 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:233
  Expression: ≈(evaluate(quadform(x, A)), 6.1464, atol=atol, rtol=rtol)
   Evaluated: 25.663898714752705 ≈ 6.1464 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:246
  Expression: ≈(p.optval, 3.7713, atol=atol, rtol=rtol)
   Evaluated: 222.6790752161938 ≈ 3.7713 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:247
  Expression: ≈(evaluate(quadform(x, A)), -1, atol=atol, rtol=rtol)
   Evaluated: -0.019790971691636853 ≈ -1 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:295
  Expression: ≈(p.optval, -2.144087, atol=atol, rtol=rtol)
   Evaluated: -986314.8649570819 ≈ -2.144087 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:296
  Expression: ≈(sum(evaluate(x' * v)), -2.144087, atol=atol, rtol=rtol)
   Evaluated: 0.0028419826998289676 ≈ -2.144087 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:297
  Expression: ≈(evaluate(norm(x, q)), 1, atol=atol, rtol=rtol)
   Evaluated: 0.0017907416049724328 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:298
  Expression: ≈(sum(evaluate(x' * v)), -(sum(abs.(v) .^ qs) ^ (1 / qs)), atol=atol, rtol=rtol)
   Evaluated: 0.0028419826998289676 ≈ -2.1440874584623084 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:128
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -52.90818101216816 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:142
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -52.90818101216816 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:152
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -52.90818101216816 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:58
  Expression: ≈(p.optval, 15.4907, atol=atol, rtol=rtol)
   Evaluated: 13.104286509771367 ≈ 15.4907 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:59
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm_1(x)), 15.4907, atol=atol, rtol=rtol)
   Evaluated: 6.924751497995521 ≈ 15.4907 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:60
  Expression: ≈((p.constraints[1]).dual, [4.7062, 5.4475], atol=atol, rtol=rtol)
   Evaluated: [3.765032172114884; 4.67775245700121] ≈ [4.7062, 5.4475] (atol=0.001, rtol=0.0)

Error in testset socp_geo_mean_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:211
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 392.88127441973126 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset socp_geo_mean_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:212
  Expression: ≈(evaluate(sum(geomean(x, y))), 4, atol=atol, rtol=rtol)
   Evaluated: 3.189058230160427 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:76
  Expression: ≈(p.optval, 130, atol=atol, rtol=rtol)
   Evaluated: 1005.3056664358646 ≈ 130 (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:77
  Expression: ≈((evaluate(objective))[1], 130, atol=atol, rtol=rtol)
   Evaluated: -105.10559432953596 ≈ 130 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:209
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: -26349.615791625576 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:210
  Expression: ≈(vec(x.value), [2; 2; 2; 1], atol=atol, rtol=rtol)
   Evaluated: [1.9954150089761242, 2.003903811564669, 2.007966658566147, 1.0070087391650304] ≈ [2, 2, 2, 1] (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:211
  Expression: ≈(evaluate(dotsort(x, [1, 2, 3, 4])), 19, atol=atol, rtol=rtol)
   Evaluated: 19.041416826075874 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:222
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: -9282.795970864827 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:223
  Expression: ≈(evaluate(dotsort(x, [1, 2, 3, 4])), 19, atol=atol, rtol=rtol)
   Evaluated: 18.98016279330477 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_neg_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:143
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: -3324.750823619811 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_neg_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:144
  Expression: ≈(evaluate(sum(neg(x))), 6, atol=atol, rtol=rtol)
   Evaluated: 6.001668490469456 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:195
  Expression: ≈(p.optval, 12, atol=atol, rtol=rtol)
   Evaluated: 558.4048506733507 ≈ 12 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:196
  Expression: ≈(evaluate(sumsmallest(x, 3)), 12, atol=atol, rtol=rtol)
   Evaluated: 6.4292139038443565 ≈ 12 (atol=0.001, rtol=0.0)

Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:129
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -1060.0123242861591 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:130
  Expression: ≈(evaluate(sum(pos(x))), 3, atol=atol, rtol=rtol)
   Evaluated: 3.501511480193585 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom_both_arguments_variable:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:178
  Expression: ≈(p.optval, 0.5, atol=atol, rtol=rtol)
   Evaluated: -4090.4805512593543 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom_both_arguments_variable:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:179
  Expression: ≈((evaluate(matrixfrac(x, P)))[1], 0.5, atol=atol, rtol=rtol)
   Evaluated: 225.20656734354836 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset sdp_Complex_Variable_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:337
  Expression: ≈(real_diff, zeros(10, 1), atol=atol, rtol=rtol)
   Evaluated: [-0.00034433044493198395; 0.003042846918106079; … ; -0.1418022569268942; 0.07656621001660824] ≈ [0.0; 0.0; … ; 0.0; 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_Complex_Variable_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:340
  Expression: ≈(imag_diff, zeros(10, 1), atol=atol, rtol=rtol)
   Evaluated: [-0.052180659025907516; 0.12174186669290066; … ; -0.023393595591187477; 0.09798192232847214] ≈ [0.0; 0.0; … ; 0.0; 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_kron_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:244
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 60.61443796343372 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_nuclear_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:82
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -6.937286214858657 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_nuclear_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:83
  Expression: ≈(evaluate(nuclearnorm(y)), 3, atol=atol, rtol=rtol)
   Evaluated: 3.9937526843569406 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:190
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: 2.475119917707713 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:191
  Expression: ≈(evaluate(x), ones(3, 3), atol=atol, rtol=rtol)
   Evaluated: [4945.179719160078 3439.3288691083435 3439.3288691085763; 3439.328869108809 4945.179719160311 3439.328869109275; 3439.3288691083435 3439.328869108809 4945.179719160311] ≈ [1.0 1.0 1.0; 1.0 1.0 1.0; 1.0 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:200
  Expression: ≈(p.optval, 8.4853, atol=atol, rtol=rtol)
   Evaluated: 4.939648648155326 ≈ 8.4853 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:214
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 0.8679366435622154 ≈ 0.835965600959115 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:228
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 4.485816917900737 ≈ 4.2102157550886385 (atol=0.001, rtol=0.0)

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:351
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:352
  Expression: ≈(evaluate(ρ), [1.0 0.0; 0.0 1.0], atol=atol, rtol=rtol)
   Evaluated: Complex{Float64}[1.013793881982565 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 1.013793881982565 + 0.0im] ≈ [1.0 0.0; 0.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:353
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -313822.62151487794 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_lambda_min_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:148
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 561.8794809307918 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset sdp_lambda_min_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:149
  Expression: ≈(evaluate(eigmin(y)), 2, atol=atol, rtol=rtol)
   Evaluated: 1.5002992660738528 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset sdp_Partial_trace:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:257
  Expression: ≈(evaluate(ρ), [0.09942819 0.29923607 0 0; 0.299237 0.900572 0 0; 0 0 0 0; 0 0 0 0], atol=atol, rtol=rtol)
   Evaluated: [0.10076723416568711 0.31447103299433365 0.0 0.0; 0.29989178490359336 0.9000547644682229 0.0 0.0; 0.0 0.0 0.0 0.0; 0.0 0.0 0.0 0.0] ≈ [0.09942819 0.29923607 0.0 0.0; 0.299237 0.900572 0.0 0.0; 0.0 0.0 0.0 0.0; 0.0 0.0 0.0 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_Partial_trace:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:258
  Expression: ≈(evaluate(partialtrace(ρ, 1, [2; 2])), [0.09942819 0.29923607; 0.29923607 0.90057181], atol=atol, rtol=rtol)
   Evaluated: [0.10076723416568711 0.31447103299433365; 0.29989178490359336 0.9000547644682229] ≈ [0.09942819 0.29923607; 0.29923607 0.90057181] (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:124
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 0.8679366435622154 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:125
  Expression: ≈(evaluate(eigmax(y)), 4, atol=atol, rtol=rtol)
   Evaluated: 149.26817397773266 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:133
  Expression: ≈(p.optval, 1.5, atol=atol, rtol=rtol)
   Evaluated: -49.58756168845351 ≈ 1.5 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:134
  Expression: ≈((p.constraints[1]).dual, im, atol=atol, rtol=rtol)
   Evaluated: 0.0 + 0.6707351811764969im ≈ im (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:135
  Expression: ≈((p.constraints[2]).dual, 0.75, atol=atol, rtol=rtol)
   Evaluated: -24.62914843480057 + 0.0im ≈ 0.75 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:163
  Expression: ≈(p.optval, 7, atol=atol, rtol=rtol)
   Evaluated: -20857.35444501712 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:164
  Expression: ≈((evaluate(matrixfrac(x, P)))[1], 7, atol=atol, rtol=rtol)
   Evaluated: 9.76379033762197 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:18
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -18.88127952020748 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:37
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: -6599.095200322007 ≈ 1 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            1.76s / 99.5%            131MiB / 99.4%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 affine                     1    481ms  27.4%   481ms   43.4MiB  33.4%  43.4MiB
   affine_Partial_t...      1    283ms  16.2%   283ms   26.7MiB  20.5%  26.7MiB
   affine_dot_multi...      1   42.3ms  2.42%  42.3ms   2.73MiB  2.10%  2.73MiB
   affine_permutedd...      1   31.0ms  1.77%  31.0ms    672KiB  0.51%   672KiB
   affine_multiply_...      1   20.1ms  1.15%  20.1ms   1.73MiB  1.33%  1.73MiB
   affine_sum_atom          1   12.8ms  0.73%  12.8ms   1.03MiB  0.79%  1.03MiB
   affine_satisfy_p...      1   12.8ms  0.73%  12.8ms   1.09MiB  0.84%  1.09MiB
   affine_conv_atom         1   11.8ms  0.67%  11.8ms    807KiB  0.61%   807KiB
   affine_hcat_atom         1   11.0ms  0.63%  11.0ms    964KiB  0.72%   964KiB
   affine_index_atom        1   7.51ms  0.43%  7.51ms   1.19MiB  0.92%  1.19MiB
   affine_dualvalue         1   6.70ms  0.38%  6.70ms    843KiB  0.63%   843KiB
   affine_transpose...      1   6.44ms  0.37%  6.44ms    918KiB  0.69%   918KiB
   affine_add_atom          1   6.00ms  0.34%  6.00ms    685KiB  0.51%   685KiB
   affine_reshape_atom      1   5.95ms  0.34%  5.95ms    924KiB  0.69%   924KiB
   affine_vcat_atom         1   5.74ms  0.33%  5.74ms    808KiB  0.61%   808KiB
   affine_Diagonal_...      1   5.62ms  0.32%  5.62ms    739KiB  0.56%   739KiB
   affine_diag_atom         1   4.22ms  0.24%  4.22ms    638KiB  0.48%   638KiB
   affine_trace_atom        1   1.86ms  0.11%  1.86ms    259KiB  0.19%   259KiB
   affine_dot_atom_...      1   1.86ms  0.11%  1.86ms    261KiB  0.20%   261KiB
   affine_dot_atom          1   1.85ms  0.11%  1.85ms    237KiB  0.18%   237KiB
   affine_negate_atom       1   1.64ms  0.09%  1.64ms    222KiB  0.17%   222KiB
   affine_kron_atom         1    191μs  0.01%   191μs   30.2KiB  0.02%  30.2KiB
 socp                       1    450ms  25.7%   450ms   26.7MiB  20.6%  26.7MiB
   socp_rational_no...      1   95.9ms  5.48%  95.9ms   9.50MiB  7.31%  9.50MiB
   socp_dual_froben...      1   77.3ms  4.41%  77.3ms   1.38MiB  1.06%  1.38MiB
   socp_inv_pos_atom        1   42.0ms  2.40%  42.0ms   2.29MiB  1.76%  2.29MiB
   socp_dual_norm_2...      1   40.0ms  2.28%  40.0ms   1.96MiB  1.50%  1.96MiB
   socp_rational_no...      1   38.2ms  2.18%  38.2ms   2.14MiB  1.64%  2.14MiB
   socp_square_atom         1   31.7ms  1.81%  31.7ms   1.67MiB  1.28%  1.67MiB
   socp_quad_form_atom      1   26.0ms  1.48%  26.0ms   1.40MiB  1.08%  1.40MiB
   socp_rational_no...      1   24.8ms  1.42%  24.8ms   1.30MiB  1.00%  1.30MiB
   socp_fix_multipl...      1   18.3ms  1.05%  18.3ms   1.00MiB  0.77%  1.00MiB
   socp_geo_mean_atom       1   12.8ms  0.73%  12.8ms    792KiB  0.60%   792KiB
   socp_huber_atom          1   11.8ms  0.68%  11.8ms    646KiB  0.49%   646KiB
   socp_dual_minima...      1   9.89ms  0.56%  9.89ms    954KiB  0.72%   954KiB
   socp_sum_squares...      1   7.99ms  0.46%  7.99ms    433KiB  0.33%   433KiB
   socp_quad_over_l...      1   6.47ms  0.37%  6.47ms    512KiB  0.38%   512KiB
   socp_fix_and_fre...      1   6.20ms  0.35%  6.20ms    672KiB  0.50%   672KiB
   socp_norm_consis...      1    349μs  0.02%   349μs   58.9KiB  0.04%  58.9KiB
   socp_sqrt_atom           1   53.6μs  0.00%  53.6μs   22.3KiB  0.02%  22.3KiB
 sdp                        1    359ms  20.5%   359ms   26.5MiB  20.4%  26.5MiB
   sdp_Partial_trace        1    111ms  6.32%   111ms   7.39MiB  5.69%  7.39MiB
   sdp_sum_largest_...      1   64.4ms  3.68%  64.4ms   4.38MiB  3.37%  4.38MiB
   sdp_sdp_variables        1   28.8ms  1.65%  28.8ms   1.91MiB  1.47%  1.91MiB
   sdp_dual_lambda_...      1   23.7ms  1.36%  23.7ms   1.70MiB  1.31%  1.70MiB
   sdp_nuclear_norm...      1   17.0ms  0.97%  17.0ms   1.05MiB  0.81%  1.05MiB
   sdp_Complex_Vari...      1   15.1ms  0.86%  15.1ms   1.94MiB  1.49%  1.94MiB
   sdp_matrix_frac_...      1   12.4ms  0.71%  12.4ms    865KiB  0.65%   865KiB
   sdp_lambda_min_atom      1   11.9ms  0.68%  11.9ms    738KiB  0.55%   738KiB
   sdp_socp_sumsqua...      1   10.5ms  0.60%  10.5ms    490KiB  0.37%   490KiB
   sdp_Issue_198            1   10.4ms  0.59%  10.4ms    796KiB  0.60%   796KiB
   sdp_matrix_frac_...      1   9.32ms  0.53%  9.32ms    793KiB  0.60%   793KiB
   sdp_kron_atom            1   7.44ms  0.43%  7.44ms    971KiB  0.73%   971KiB
   sdp_operator_nor...      1   6.84ms  0.39%  6.84ms    629KiB  0.47%   629KiB
   sdp_socp_norm2_atom      1   6.68ms  0.38%  6.68ms    354KiB  0.27%   354KiB
   sdp_sigma_max_atom       1   6.48ms  0.37%  6.48ms    629KiB  0.47%   629KiB
   sdp_socp_abs_atom        1   6.48ms  0.37%  6.48ms    392KiB  0.29%   392KiB
   sdp_Real_Variabl...      1   5.69ms  0.33%  5.69ms   1.08MiB  0.83%  1.08MiB
   sdp_sdp_constraints      1   4.69ms  0.27%  4.69ms    403KiB  0.30%   403KiB
 lp                         1    324ms  18.5%   324ms   25.7MiB  19.8%  25.7MiB
   lp_dotsort_atom          1    103ms  5.88%   103ms   6.52MiB  5.02%  6.52MiB
   lp_min_atom              1   83.5ms  4.77%  83.5ms   5.23MiB  4.02%  5.23MiB
   lp_max_atom              1   60.0ms  3.43%  60.0ms   5.23MiB  4.03%  5.23MiB
   lp_minimum_atom          1   21.6ms  1.23%  21.6ms   2.49MiB  1.92%  2.49MiB
   lp_sumsmallest_atom      1   16.5ms  0.94%  16.5ms   2.04MiB  1.57%  2.04MiB
   lp_neg_atom              1   9.80ms  0.56%  9.80ms    600KiB  0.45%   600KiB
   lp_pos_atom              1   7.60ms  0.43%  7.60ms    575KiB  0.43%   575KiB
   lp_sumlargest_atom       1   7.57ms  0.43%  7.57ms   1.11MiB  0.85%  1.11MiB
   lp_dual_abs_atom         1   5.18ms  0.30%  5.18ms    665KiB  0.50%   665KiB
   lp_dual_norm_inf...      1   3.81ms  0.22%  3.81ms    414KiB  0.31%   414KiB
   lp_dual_norm_1_atom      1   2.59ms  0.15%  2.59ms    369KiB  0.28%   369KiB
   lp_maximum_atom          1   2.47ms  0.14%  2.47ms    441KiB  0.33%   441KiB
   lp_hinge_loss_atom       1   37.9μs  0.00%  37.9μs   21.4KiB  0.02%  21.4KiB
 constant                   1    137ms  7.85%   137ms   7.67MiB  5.90%  7.67MiB
   constant_fix!_wi...      1    101ms  5.78%   101ms   5.10MiB  3.92%  5.10MiB
   constant_fix!_wi...      1   18.1ms  1.03%  18.1ms    822KiB  0.62%   822KiB
   constant_Test_do...      1   8.83ms  0.50%  8.83ms    782KiB  0.59%   782KiB
   constant_Issue_228       1   4.09ms  0.23%  4.09ms    436KiB  0.33%   436KiB
   constant_Issue_166       1   3.09ms  0.18%  3.09ms    276KiB  0.21%   276KiB
   constant_fix!_an...      1   2.02ms  0.12%  2.02ms    261KiB  0.20%   261KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## SDPA `PARAMETER_DEFAULT` (dualized)
These tests were run on March 3, 2020 at 17:19 (UTC).

Tests with SDPA via SDPA.jl using Dualization.jl.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 41 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">375</td>
<td style="text-align:center;color:red;">15</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">390</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">27</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_166</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_228</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_vectors</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_complex_numbers</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Test_double_fix!</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_and_multiply</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">135</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_satisfy_problems</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_transpose_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_diag_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_conv_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style="text-align:center;color:green;">18</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">19</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_hcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_vcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_index_atom</td>
<td style="text-align:center;color:green;">8</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_Partial_transpose</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_add_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dualvalue</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_sum_atom</td>
<td style="text-align:center;color:green;">8</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_reshape_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_multiply_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_trace_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_negate_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">97</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">60</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">56</td>
<td style="text-align:center;color:red;">8</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr></table>
```

### Errors

```julia
Error in testset constant_fix!_and_multiply:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:75
  Expression: ≈(evaluate(tr(p * x)), 2.0, atol=atol, rtol=rtol)
   Evaluated: 2.003359879968386 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:357
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 1.0056902080035053 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:240
  Expression: ≈(evaluate(c * (X[1:n, 5:(5 + n) - 1])' * c'), s, atol=atol, rtol=rtol)
   Evaluated: [0.009855836792266995] ≈ [0.006336311665178693] (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:279
  Expression: ≈(evaluate(sum(x[2:6])), sum(a[2:6]), atol=atol, rtol=rtol)
   Evaluated: 2.93329174232518 ≈ 2.9423103002535136 (atol=0.001, rtol=0.0)

Error in testset affine_trace_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:319
  Expression: ≈(evaluate(tr(x)), 2, atol=atol, rtol=rtol)
   Evaluated: 2.003359879968386 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:209
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 18.984598810913667 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:222
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 18.984599431184506 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:214
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 3.998125035461271 ≈ 2.4935350578234647 (atol=0.001, rtol=0.0)

Error in testset sdp_operator_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:96
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 3.992324827093398 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_operator_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:97
  Expression: ≈(evaluate(opnorm(y)), 4, atol=atol, rtol=rtol)
   Evaluated: 4.002521303592891 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_Real_Variables_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:312
  Expression: x1 == x2
   Evaluated: [0.6424808282097625; 0.23372199582808798; … ; 0.6861729622297457; 0.17510263699716758] == [0.6424808282097623; 0.233721995828088; … ; 0.6861729622297452; 0.17510263699716813]

Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:69
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 0.9936917468025968 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset sdp_sigma_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:110
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 3.99231148257968 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_sigma_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:111
  Expression: ≈(evaluate(sigmamax(y)), 4, atol=atol, rtol=rtol)
   Evaluated: 4.0025213026063575 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:124
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 3.998125035461271 ≈ 4 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            40.6s / 100%            3.47GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 constant                   1    18.3s  45.1%   18.3s   1.38GiB  39.9%  1.38GiB
   constant_Issue_166       1    17.2s  42.4%   17.2s   1.30GiB  37.6%  1.30GiB
   constant_fix!_wi...      1    205ms  0.51%   205ms   9.36MiB  0.26%  9.36MiB
   constant_fix!_wi...      1    160ms  0.39%   160ms   8.94MiB  0.25%  8.94MiB
   constant_Issue_228       1   99.4ms  0.25%  99.4ms   8.83MiB  0.25%  8.83MiB
   constant_Test_do...      1   87.7ms  0.22%  87.7ms   4.47MiB  0.13%  4.47MiB
   constant_fix!_an...      1   56.8ms  0.14%  56.8ms   3.28MiB  0.09%  3.28MiB
 socp                       1    8.59s  21.2%   8.59s    726MiB  20.4%   726MiB
   socp_dual_minima...      1    4.19s  10.3%   4.19s    266MiB  7.50%   266MiB
   socp_dual_norm_2...      1    520ms  1.28%   520ms   53.1MiB  1.49%  53.1MiB
   socp_rational_no...      1    322ms  0.79%   322ms   24.7MiB  0.70%  24.7MiB
   socp_fix_multipl...      1    257ms  0.63%   257ms   32.2MiB  0.91%  32.2MiB
   socp_dual_froben...      1    245ms  0.60%   245ms   19.6MiB  0.55%  19.6MiB
   socp_square_atom         1    228ms  0.56%   228ms   15.0MiB  0.42%  15.0MiB
   socp_inv_pos_atom        1    200ms  0.49%   200ms   12.4MiB  0.35%  12.4MiB
   socp_quad_form_atom      1    152ms  0.37%   152ms   11.5MiB  0.32%  11.5MiB
   socp_rational_no...      1    114ms  0.28%   114ms   10.5MiB  0.30%  10.5MiB
   socp_sum_squares...      1    110ms  0.27%   110ms   8.35MiB  0.24%  8.35MiB
   socp_rational_no...      1    108ms  0.27%   108ms   7.96MiB  0.22%  7.96MiB
   socp_quad_over_l...      1    108ms  0.27%   108ms   8.02MiB  0.23%  8.02MiB
   socp_geo_mean_atom       1   98.8ms  0.24%  98.8ms   4.67MiB  0.13%  4.67MiB
   socp_huber_atom          1   93.6ms  0.23%  93.6ms   12.9MiB  0.36%  12.9MiB
   socp_fix_and_fre...      1   53.1ms  0.13%  53.1ms   2.86MiB  0.08%  2.86MiB
   socp_norm_consis...      1    447μs  0.00%   447μs   58.9KiB  0.00%  58.9KiB
   socp_sqrt_atom           1   94.5μs  0.00%  94.5μs   22.3KiB  0.00%  22.3KiB
 affine                     1    5.89s  14.5%   5.89s    596MiB  16.8%   596MiB
   affine_Partial_t...      1    572ms  1.41%   572ms    111MiB  3.13%   111MiB
   affine_transpose...      1    524ms  1.29%   524ms   20.6MiB  0.58%  20.6MiB
   affine_dot_multi...      1    394ms  0.97%   394ms   28.2MiB  0.79%  28.2MiB
   affine_reshape_atom      1    329ms  0.81%   329ms   15.7MiB  0.44%  15.7MiB
   affine_multiply_...      1    312ms  0.77%   312ms   24.8MiB  0.70%  24.8MiB
   affine_index_atom        1    278ms  0.69%   278ms   23.9MiB  0.67%  23.9MiB
   affine_sum_atom          1    264ms  0.65%   264ms   21.1MiB  0.59%  21.1MiB
   affine_Diagonal_...      1    200ms  0.49%   200ms   18.8MiB  0.53%  18.8MiB
   affine_vcat_atom         1    150ms  0.37%   150ms   9.03MiB  0.25%  9.03MiB
   affine_add_atom          1    136ms  0.33%   136ms   8.68MiB  0.24%  8.68MiB
   affine_dualvalue         1    132ms  0.33%   132ms   11.2MiB  0.31%  11.2MiB
   affine_conv_atom         1    119ms  0.29%   119ms   8.50MiB  0.24%  8.50MiB
   affine_diag_atom         1    116ms  0.29%   116ms   14.3MiB  0.40%  14.3MiB
   affine_dot_atom          1    108ms  0.27%   108ms   5.99MiB  0.17%  5.99MiB
   affine_hcat_atom         1   90.4ms  0.22%  90.4ms   6.25MiB  0.18%  6.25MiB
   affine_satisfy_p...      1   76.1ms  0.19%  76.1ms   4.40MiB  0.12%  4.40MiB
   affine_negate_atom       1   49.5ms  0.12%  49.5ms   2.44MiB  0.07%  2.44MiB
   affine_trace_atom        1   49.3ms  0.12%  49.3ms   2.85MiB  0.08%  2.85MiB
   affine_dot_atom_...      1   47.1ms  0.12%  47.1ms   3.07MiB  0.09%  3.07MiB
   affine_permutedd...      1   30.9ms  0.08%  30.9ms    672KiB  0.02%   672KiB
   affine_kron_atom         1    259μs  0.00%   259μs   30.2KiB  0.00%  30.2KiB
 sdp                        1    4.78s  11.8%   4.78s    459MiB  12.9%   459MiB
   sdp_matrix_frac_...      1    918ms  2.27%   918ms   68.7MiB  1.93%  68.7MiB
   sdp_Partial_trace        1    259ms  0.64%   259ms   21.5MiB  0.61%  21.5MiB
   sdp_sdp_variables        1    235ms  0.58%   235ms   23.5MiB  0.66%  23.5MiB
   sdp_dual_lambda_...      1    213ms  0.53%   213ms   22.5MiB  0.63%  22.5MiB
   sdp_sum_largest_...      1    174ms  0.43%   174ms   11.8MiB  0.33%  11.8MiB
   sdp_nuclear_norm...      1    148ms  0.37%   148ms   18.7MiB  0.53%  18.7MiB
   sdp_socp_sumsqua...      1    145ms  0.36%   145ms   9.58MiB  0.27%  9.58MiB
   sdp_Complex_Vari...      1    138ms  0.34%   138ms   8.43MiB  0.24%  8.43MiB
   sdp_sigma_max_atom       1    130ms  0.32%   130ms   14.2MiB  0.40%  14.2MiB
   sdp_operator_nor...      1    124ms  0.30%   124ms   13.9MiB  0.39%  13.9MiB
   sdp_matrix_frac_...      1   96.5ms  0.24%  96.5ms   9.07MiB  0.26%  9.07MiB
   sdp_Real_Variabl...      1   91.1ms  0.22%  91.1ms   4.85MiB  0.14%  4.85MiB
   sdp_Issue_198            1   87.9ms  0.22%  87.9ms   5.80MiB  0.16%  5.80MiB
   sdp_sdp_constraints      1   80.1ms  0.20%  80.1ms   9.01MiB  0.25%  9.01MiB
   sdp_socp_abs_atom        1   69.4ms  0.17%  69.4ms   4.51MiB  0.13%  4.51MiB
   sdp_socp_norm2_atom      1   62.5ms  0.15%  62.5ms   4.13MiB  0.12%  4.13MiB
   sdp_kron_atom            1   60.8ms  0.15%  60.8ms   5.83MiB  0.16%  5.83MiB
   sdp_lambda_min_atom      1   60.0ms  0.15%  60.0ms   3.78MiB  0.11%  3.78MiB
 lp                         1    2.99s  7.38%   2.99s    354MiB  10.0%   354MiB
   lp_sumlargest_atom       1    246ms  0.61%   246ms   32.6MiB  0.92%  32.6MiB
   lp_minimum_atom          1    230ms  0.57%   230ms   19.9MiB  0.56%  19.9MiB
   lp_dotsort_atom          1    227ms  0.56%   227ms   21.0MiB  0.59%  21.0MiB
   lp_max_atom              1    205ms  0.51%   205ms   21.8MiB  0.61%  21.8MiB
   lp_dual_abs_atom         1    205ms  0.51%   205ms   16.6MiB  0.47%  16.6MiB
   lp_min_atom              1    179ms  0.44%   179ms   21.8MiB  0.61%  21.8MiB
   lp_sumsmallest_atom      1    139ms  0.34%   139ms   20.4MiB  0.57%  20.4MiB
   lp_pos_atom              1    113ms  0.28%   113ms   6.45MiB  0.18%  6.45MiB
   lp_maximum_atom          1    107ms  0.26%   107ms   12.2MiB  0.34%  12.2MiB
   lp_dual_norm_1_atom      1   75.1ms  0.19%  75.1ms   3.70MiB  0.10%  3.70MiB
   lp_dual_norm_inf...      1   69.4ms  0.17%  69.4ms   3.77MiB  0.11%  3.77MiB
   lp_neg_atom              1   62.6ms  0.15%  62.6ms   4.44MiB  0.13%  4.44MiB
   lp_hinge_loss_atom       1   79.8μs  0.00%  79.8μs   21.4KiB  0.00%  21.4KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## SDPA `PARAMETER_UNSTABLE_BUT_FAST` (dualized)
These tests were run on March 3, 2020 at 17:19 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 2 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">387</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">390</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">139</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">97</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">61</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">62</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr></table>
```

### Errors

```julia
Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:222
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 18.998676701193318 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset sdp_Real_Variables_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:312
  Expression: x1 == x2
   Evaluated: [0.6424808348998353; 0.23372205744585; … ; 0.6861730313747215; 0.17510257718318312] == [0.6424808348998353; 0.23372205744584992; … ; 0.6861730313747203; 0.1751025771831847]

Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:69
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 1.0028860416647376 ≈ 1 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            1.30s / 100%             195MiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 socp                       1    454ms  35.1%   454ms   27.6MiB  14.2%  27.6MiB
   socp_rational_no...      1    206ms  15.9%   206ms   9.51MiB  4.88%  9.51MiB
   socp_dual_froben...      1   51.9ms  4.01%  51.9ms   1.64MiB  0.84%  1.64MiB
   socp_rational_no...      1   32.7ms  2.53%  32.7ms   2.32MiB  1.19%  2.32MiB
   socp_dual_norm_2...      1   24.9ms  1.92%  24.9ms   1.91MiB  0.98%  1.91MiB
   socp_inv_pos_atom        1   22.9ms  1.77%  22.9ms   2.15MiB  1.11%  2.15MiB
   socp_square_atom         1   22.3ms  1.72%  22.3ms   1.69MiB  0.87%  1.69MiB
   socp_rational_no...      1   21.6ms  1.67%  21.6ms   1.46MiB  0.75%  1.46MiB
   socp_quad_form_atom      1   13.0ms  1.01%  13.0ms   1.11MiB  0.57%  1.11MiB
   socp_fix_multipl...      1   12.8ms  0.99%  12.8ms   1.13MiB  0.58%  1.13MiB
   socp_dual_minima...      1   10.7ms  0.83%  10.7ms   1.12MiB  0.58%  1.12MiB
   socp_huber_atom          1   8.12ms  0.63%  8.12ms    838KiB  0.42%   838KiB
   socp_geo_mean_atom       1   7.39ms  0.57%  7.39ms    717KiB  0.36%   717KiB
   socp_sum_squares...      1   6.84ms  0.53%  6.84ms    516KiB  0.26%   516KiB
   socp_fix_and_fre...      1   6.36ms  0.49%  6.36ms    860KiB  0.43%   860KiB
   socp_quad_over_l...      1   5.34ms  0.41%  5.34ms    506KiB  0.25%   506KiB
   socp_norm_consis...      1    292μs  0.02%   292μs   58.9KiB  0.03%  58.9KiB
   socp_sqrt_atom           1   63.2μs  0.00%  63.2μs   22.3KiB  0.01%  22.3KiB
 affine                     1    453ms  35.0%   453ms    114MiB  58.4%   114MiB
   affine_Partial_t...      1    304ms  23.5%   304ms   95.0MiB  48.8%  95.0MiB
   affine_permutedd...      1   30.9ms  2.39%  30.9ms    672KiB  0.34%   672KiB
   affine_dot_multi...      1   14.6ms  1.13%  14.6ms   2.25MiB  1.16%  2.25MiB
   affine_multiply_...      1   11.9ms  0.92%  11.9ms   1.74MiB  0.89%  1.74MiB
   affine_index_atom        1   8.94ms  0.69%  8.94ms   1.61MiB  0.83%  1.61MiB
   affine_satisfy_p...      1   8.27ms  0.64%  8.27ms   1.14MiB  0.59%  1.14MiB
   affine_dualvalue         1   8.26ms  0.64%  8.26ms   1.05MiB  0.54%  1.05MiB
   affine_transpose...      1   7.80ms  0.60%  7.80ms   1.24MiB  0.64%  1.24MiB
   affine_add_atom          1   7.54ms  0.58%  7.54ms    879KiB  0.44%   879KiB
   affine_reshape_atom      1   7.53ms  0.58%  7.53ms   1.20MiB  0.62%  1.20MiB
   affine_sum_atom          1   7.18ms  0.55%  7.18ms   1.06MiB  0.54%  1.06MiB
   affine_Diagonal_...      1   7.00ms  0.54%  7.00ms    916KiB  0.46%   916KiB
   affine_diag_atom         1   4.89ms  0.38%  4.89ms    831KiB  0.42%   831KiB
   affine_conv_atom         1   4.77ms  0.37%  4.77ms    738KiB  0.37%   738KiB
   affine_hcat_atom         1   4.67ms  0.36%  4.67ms   1.03MiB  0.53%  1.03MiB
   affine_vcat_atom         1   4.55ms  0.35%  4.55ms   1.04MiB  0.54%  1.04MiB
   affine_dot_atom_...      1   2.79ms  0.22%  2.79ms    336KiB  0.17%   336KiB
   affine_dot_atom          1   2.40ms  0.19%  2.40ms    298KiB  0.15%   298KiB
   affine_trace_atom        1   2.21ms  0.17%  2.21ms    331KiB  0.17%   331KiB
   affine_negate_atom       1   2.05ms  0.16%  2.05ms    278KiB  0.14%   278KiB
   affine_kron_atom         1    182μs  0.01%   182μs   30.2KiB  0.02%  30.2KiB
 lp                         1    185ms  14.3%   185ms   29.3MiB  15.0%  29.3MiB
   lp_max_atom              1   79.9ms  6.18%  79.9ms   8.42MiB  4.33%  8.42MiB
   lp_min_atom              1   34.9ms  2.70%  34.9ms   8.42MiB  4.32%  8.42MiB
   lp_minimum_atom          1   17.8ms  1.37%  17.8ms   3.57MiB  1.83%  3.57MiB
   lp_sumsmallest_atom      1   12.5ms  0.96%  12.5ms   2.31MiB  1.19%  2.31MiB
   lp_dotsort_atom          1   10.6ms  0.82%  10.6ms   1.64MiB  0.84%  1.64MiB
   lp_sumlargest_atom       1   8.18ms  0.63%  8.18ms   1.44MiB  0.74%  1.44MiB
   lp_dual_abs_atom         1   5.47ms  0.42%  5.47ms    866KiB  0.43%   866KiB
   lp_neg_atom              1   3.92ms  0.30%  3.92ms    526KiB  0.26%   526KiB
   lp_maximum_atom          1   3.05ms  0.24%  3.05ms    583KiB  0.29%   583KiB
   lp_dual_norm_1_atom      1   3.04ms  0.24%  3.04ms    478KiB  0.24%   478KiB
   lp_pos_atom              1   2.99ms  0.23%  2.99ms    465KiB  0.23%   465KiB
   lp_dual_norm_inf...      1   2.93ms  0.23%  2.93ms    549KiB  0.28%   549KiB
   lp_hinge_loss_atom       1   36.4μs  0.00%  36.4μs   21.4KiB  0.01%  21.4KiB
 sdp                        1    172ms  13.3%   172ms   20.5MiB  10.5%  20.5MiB
   sdp_sum_largest_...      1   38.5ms  2.98%  38.5ms   4.68MiB  2.41%  4.68MiB
   sdp_sdp_variables        1   19.4ms  1.50%  19.4ms   1.99MiB  1.02%  1.99MiB
   sdp_Real_Variabl...      1   13.4ms  1.03%  13.4ms   1.35MiB  0.70%  1.35MiB
   sdp_dual_lambda_...      1   11.6ms  0.89%  11.6ms   1.40MiB  0.72%  1.40MiB
   sdp_matrix_frac_...      1   10.2ms  0.79%  10.2ms    791KiB  0.40%   791KiB
   sdp_Complex_Vari...      1   8.94ms  0.69%  8.94ms   1.89MiB  0.97%  1.89MiB
   sdp_socp_sumsqua...      1   8.72ms  0.67%  8.72ms    607KiB  0.30%   607KiB
   sdp_nuclear_norm...      1   7.22ms  0.56%  7.22ms   1.01MiB  0.52%  1.01MiB
   sdp_sdp_constraints      1   6.87ms  0.53%  6.87ms    630KiB  0.32%   630KiB
   sdp_Partial_trace        1   6.18ms  0.48%  6.18ms    814KiB  0.41%   814KiB
   sdp_socp_abs_atom        1   5.70ms  0.44%  5.70ms    475KiB  0.24%   475KiB
   sdp_sigma_max_atom       1   5.52ms  0.43%  5.52ms    821KiB  0.41%   821KiB
   sdp_operator_nor...      1   5.34ms  0.41%  5.34ms    821KiB  0.41%   821KiB
   sdp_matrix_frac_...      1   5.18ms  0.40%  5.18ms    795KiB  0.40%   795KiB
   sdp_socp_norm2_atom      1   5.10ms  0.39%  5.10ms    435KiB  0.22%   435KiB
   sdp_kron_atom            1   4.98ms  0.39%  4.98ms    905KiB  0.45%   905KiB
   sdp_lambda_min_atom      1   4.71ms  0.36%  4.71ms    614KiB  0.31%   614KiB
   sdp_Issue_198            1   4.46ms  0.34%  4.46ms    571KiB  0.29%   571KiB
 constant                   1   29.3ms  2.27%  29.3ms   3.59MiB  1.84%  3.59MiB
   constant_Test_do...      1   6.90ms  0.53%  6.90ms    861KiB  0.43%   861KiB
   constant_fix!_wi...      1   6.26ms  0.48%  6.26ms    860KiB  0.43%   860KiB
   constant_fix!_wi...      1   5.30ms  0.41%  5.30ms    665KiB  0.33%   665KiB
   constant_Issue_228       1   4.85ms  0.38%  4.85ms    554KiB  0.28%   554KiB
   constant_Issue_166       1   3.48ms  0.27%  3.48ms    349KiB  0.17%   349KiB
   constant_fix!_an...      1   2.44ms  0.19%  2.44ms    333KiB  0.17%   333KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## SDPA `PARAMETER_STABLE_BUT_SLOW` (dualized)
These tests were run on March 3, 2020 at 17:19 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 3 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">193</td>
<td style="text-align:center;color:red;">197</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">390</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">18</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_166</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_228</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_vectors</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_complex_numbers</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_Test_double_fix!</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_and_multiply</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">81</td>
<td style="text-align:center;color:red;">58</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_satisfy_problems</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_transpose_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_diag_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_conv_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">19</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_hcat_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_vcat_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_index_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_Partial_transpose</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_add_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_dualvalue</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_sum_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_reshape_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_multiply_atom</td>
<td style="text-align:center;color:green;">10</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_trace_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine_negate_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;color:red;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_dual_minimal_norm_solutions</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">15</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_sum_squares_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_fix_and_free_addition</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_inv_pos_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_quad_over_lin_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_quad_form_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_fix_multiplication</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_huber_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_rational_norm_dual_norm</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_rational_norm_atom_sum</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_rational_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_square_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_dual_frobenius_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_sqrt_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_dual_norm_2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">15</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_geo_mean_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp_norm_consistent_with_Base_for_matrix_variables</td>
<td style="text-align:center;color:green;">8</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">8</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">22</td>
<td style="text-align:center;color:red;">40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;color:red;">36</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr></table>
```

### Errors

```julia
Error in testset constant_Issue_166:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:16
  Expression: ≈(problem.optval, evaluate(sum(c * β)), atol=atol, rtol=rtol)
   Evaluated: 0.0 ≈ 81.00755743202174 (atol=0.001, rtol=0.0)

Error in testset constant_Issue_166:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:18
  Expression: ≈(β.value, zeros(5), atol=atol, rtol=rtol)
   Evaluated: [1.201480296720295; 1.1803238516864303; … ; 1.180323851686322; 1.1785001864794404] ≈ [0.0, 0.0, 0.0, 0.0, 0.0] (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:134
  Expression: ≈(prob.optval, 1.25, atol=atol, rtol=rtol)
   Evaluated: 1.3030979741597548 ≈ 1.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:135
  Expression: ≈(evaluate(real(y * sum(x))), 1.25, atol=atol, rtol=rtol)
   Evaluated: 1030.3947910932302 ≈ 1.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:136
  Expression: ≈(real(evaluate(x)), 0.5 * ones(5), atol=atol, rtol=rtol)
   Evaluated: [412.63657508770336, 411.58734723601174, 412.1105757409506, 412.0211762602695, 412.4340698838437] ≈ [0.5, 0.5, 0.5, 0.5, 0.5] (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_complex_numbers:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:100
  Expression: ≈(prob.optval, 0.25, atol=atol, rtol=rtol)
   Evaluated: 0.10024820454418659 ≈ 0.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_complex_numbers:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:101
  Expression: ≈(evaluate(real(x * y)), 0.25, atol=atol, rtol=rtol)
   Evaluated: 192.57402534595303 ≈ 0.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_complex_numbers:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:102
  Expression: ≈(real(evaluate(x)), 0.5, atol=atol, rtol=rtol)
   Evaluated: 385.1479509846523 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_and_multiply:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:74
  Expression: ≈(prob.optval, 2.0, atol=atol, rtol=rtol)
   Evaluated: 1.994457006920129 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_and_multiply:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:75
  Expression: ≈(evaluate(tr(p * x)), 2.0, atol=atol, rtol=rtol)
   Evaluated: 110.18697399417688 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset affine_satisfy_problems:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:559
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset affine_satisfy_problems:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:585
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:162
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 2.0575612038373947 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:163
  Expression: ≈((evaluate(x' * c))[1], 2, atol=atol, rtol=rtol)
   Evaluated: 11760.449892697092 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:175
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 2.829083550721407 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:176
  Expression: ≈((evaluate(c' * X' * c))[1], 4, atol=atol, rtol=rtol)
   Evaluated: 158638.7285883851 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:194
  Expression: ≈(p.optval, s, atol=atol, rtol=rtol)
   Evaluated: 5.386437386274338 ≈ 12.659587270306425 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:195
  Expression: ≈((evaluate(c * x' * d + d' * x * c' + (c * ((((x')')')')' * d)'))[1], s, atol=atol, rtol=rtol)
   Evaluated: 6961.099340271232 ≈ 12.659587270306425 (atol=0.001, rtol=0.0)

Error in testset affine_diag_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:293
  Expression: ≈(evaluate(sum(diag(x, 1))), 1, atol=atol, rtol=rtol)
   Evaluated: 137.57066143974384 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_diag_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:304
  Expression: ≈(p.optval, 8, atol=atol, rtol=rtol)
   Evaluated: 8.012404108885676 ≈ 8 (atol=0.001, rtol=0.0)

Error in testset affine_diag_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:305
  Expression: ≈(evaluate(sum(diag(x))), 8, atol=atol, rtol=rtol)
   Evaluated: 1720.13928787897 ≈ 8 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:332
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: 4.73661445453763 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:333
  Expression: ≈(evaluate(sum((dot(*))(x, [1, 2, 3]))), 6, atol=atol, rtol=rtol)
   Evaluated: -87.88984349954339 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:344
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: 3.001132340170443 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:345
  Expression: ≈(evaluate(sum((dot(*))(x, eye(3)))), 3, atol=atol, rtol=rtol)
   Evaluated: -437.01898693550504 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:356
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 1.071271426975727 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:357
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 1167.7062183610055 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:368
  Expression: ≈(p.optval, 9, atol=atol, rtol=rtol)
   Evaluated: 5.905289877206087 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:369
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 3.5448914976619927 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:380
  Expression: ≈(p.optval, 9, atol=atol, rtol=rtol)
   Evaluated: 5.905289877206087 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:381
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 3.5448914976619927 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:458
  Expression: ≈(p.optval, 96, atol=atol, rtol=rtol)
   Evaluated: 62.061188377439976 ≈ 96 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:459
  Expression: ≈(evaluate(sum(x) + sum([y fill(4.0, 4)])), 96, atol=atol, rtol=rtol)
   Evaluated: -73.30843906790724 ≈ 96 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:460
  Expression: ≈(evaluate([x y fill(2.0, (4, 2))]), fill(2.0, (4, 12)), atol=atol, rtol=rtol)
   Evaluated: [0.7167573336981183 -0.7090101049135384 … 2.0 2.0; 0.8660320522688152 0.8446854845320106 … 2.0 2.0; -2.2072984698379567 0.5580090055118627 … 2.0 2.0; 0.3380346308384139 0.8648370359304764 … 2.0 2.0] ≈ [2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0] (atol=0.001, rtol=0.0)

Error in testset affine_vcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:477
  Expression: ≈(p.optval, 104, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 199.05867195874453 ≈ 104 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_vcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:478
  Expression: ≈(evaluate(sum(x) + sum([y 4 * eye(4); x -(ones(4, 6))])), 104, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: -82.73943480469553 ≈ 104 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_vcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:479
  Expression: ≈(evaluate([x; y']), 2 * ones(10, 4), atol=atol, rtol=rtol)
   Evaluated: [0.0398438092773441 -0.025061855035411806 -0.06800564665929043 -0.2726382071946287; -0.04327837577364457 -0.07546457391717087 -0.03460491217640982 -0.907637602357545; … ; -2.082096617856201 -2.101530750231942 -2.1583419080711543 -2.045088866706971; -4.318623426938193 -2.6475082034712596 -12.929660831154962 -3.5717608806142573] ≈ [2.0 2.0 2.0 2.0; 2.0 2.0 2.0 2.0; … ; 2.0 2.0 2.0 2.0; 2.0 2.0 2.0 2.0] (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:208
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 2.0575612038373947 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:209
  Expression: ≈((evaluate(x[1] + x[2]))[1], 2, atol=atol, rtol=rtol)
   Evaluated: 11760.449892697092 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:221
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 2.001660556998104 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:222
  Expression: ≈((evaluate(sum(x[I])))[1], 2, atol=atol, rtol=rtol)
   Evaluated: 1029.2226937031842 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:239
  Expression: ≈(p.optval, s[1], atol=atol, rtol=rtol)
   Evaluated: 0.004439969488885254 ≈ 0.006336311665178693 (atol=0.001, rtol=0.0)

Error in testset affine_index_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:240
  Expression: ≈(evaluate(c * (X[1:n, 5:(5 + n) - 1])' * c'), s, atol=atol, rtol=rtol)
   Evaluated: [4256.551001189595] ≈ [0.006336311665178693] (atol=0.001, rtol=0.0)

Error in testset affine_add_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:123
  Expression: ≈(p.optval, 5, atol=atol, rtol=rtol)
   Evaluated: 3.5968270897865295 ≈ 5 (atol=0.001, rtol=0.0)

Error in testset affine_add_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:124
  Expression: ≈(evaluate(x + y), 5, atol=atol, rtol=rtol)
   Evaluated: 253100.93043008982 ≈ 5 (atol=0.001, rtol=0.0)

Error in testset affine_add_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:136
  Expression: ≈(evaluate(eye(2) + x), eye(2), atol=atol, rtol=rtol)
   Evaluated: [187.6798585468003 186.6798585468003; 186.6798585468003 187.6798585468003] ≈ [1.0 0.0; 0.0 1.0] (atol=0.001, rtol=0.0)

Error in testset affine_add_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:147
  Expression: ≈(p.optval, -6, atol=atol, rtol=rtol)
   Evaluated: -8.231485344469547 ≈ -6 (atol=0.001, rtol=0.0)

Error in testset affine_add_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:148
  Expression: ≈(evaluate(y - 5), -6, atol=atol, rtol=rtol)
   Evaluated: 6520.458573417909 ≈ -6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom_for_matrix_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:108
  Expression: ≈(p.optval, 8.8, atol=atol, rtol=rtol)
   Evaluated: 1.5534717440605164 ≈ 8.8 (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom_for_matrix_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:109
  Expression: ≈((evaluate(dot(fill(2.0, (2, 2)), x)))[1], 8.8, atol=atol, rtol=rtol)
   Evaluated: 58.925434014975934 ≈ 8.8 (atol=0.001, rtol=0.0)

Error in testset affine_dualvalue:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:595
  Expression: ≈((p.constraints[1]).dual, 1, atol=atol, rtol=rtol)
   Evaluated: 0.4127054214477539 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dualvalue:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:603
  Expression: ≈((p.constraints[1]).dual, 1, atol=atol, rtol=rtol)
   Evaluated: 0.4127054214477539 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_Diagonal_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:510
  Expression: ≈(p.optval, 21, atol=atol, rtol=rtol)
   Evaluated: 15.066023979336023 ≈ 21 (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:253
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 2.829083550721407 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:254
  Expression: ≈(evaluate(sum(x)), 4, atol=atol, rtol=rtol)
   Evaluated: 158638.72858838507 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:278
  Expression: ≈(p.optval, sum(a[2:6]), atol=atol, rtol=rtol)
   Evaluated: 2.944502184196608 ≈ 2.9423103002535136 (atol=0.001, rtol=0.0)

Error in testset affine_sum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:279
  Expression: ≈(evaluate(sum(x[2:6])), sum(a[2:6]), atol=atol, rtol=rtol)
   Evaluated: -2450.184608123329 ≈ 2.9423103002535136 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:415
  Expression: ≈(p.optval, sum(A .+ c), atol=atol, rtol=rtol)
   Evaluated: 9.108787085860968 ≈ 6.535435569955714 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:416
  Expression: ≈(evaluate(sum(reshape(X, 2, 3) + A)), sum(A .+ c), atol=atol, rtol=rtol)
   Evaluated: 36.21029365364742 ≈ 6.535435569955714 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:427
  Expression: ≈(p.optval, sum(b .+ c), atol=atol, rtol=rtol)
   Evaluated: 6.266831409186125 ≈ 5.984692348149807 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:428
  Expression: ≈(evaluate(sum(vec(X) + b)), sum(b .+ c), atol=atol, rtol=rtol)
   Evaluated: 916146.509489909 ≈ 5.984692348149807 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:443
  Expression: ≈(p.optval, 136, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 133.05639976263046 ≈ 136 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:444
  Expression: ≈((evaluate(c' * reshaped))[1], 136, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 208.41177186905216 ≈ 136 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:63
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -6.332036316394806 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:72
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -6.332036316394806 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_trace_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:318
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 1.994457006920129 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_trace_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:319
  Expression: ≈(evaluate(tr(x)), 2, atol=atol, rtol=rtol)
   Evaluated: 110.18697399417688 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset affine_negate_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:11
  Expression: ≈(evaluate(-x), 0, atol=atol, rtol=rtol)
   Evaluated: 6497.905796560157 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:417
  Expression: ≈(p.optval, 1.5, atol=atol, rtol=rtol)
   Evaluated: 0.14632895588874817 ≈ 1.5 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:418
  Expression: ≈(evaluate(x), [0, 1.5], atol=atol, rtol=rtol)
   Evaluated: [1.5154440593485687, 0.7422779703158824] ≈ [0.0, 1.5] (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:419
  Expression: ≈(evaluate(norm(x, 1)), p.optval, atol=atol, rtol=rtol)
   Evaluated: 2.257722029664451 ≈ 0.14632895588874817 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:433
  Expression: ≈(p.optval, 3 / sqrt(5), atol=atol, rtol=rtol)
   Evaluated: 0.3085743486881256 ≈ 1.3416407864998738 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:434
  Expression: ≈(evaluate(x), [3 / 5, 6 / 5], atol=atol, rtol=rtol)
   Evaluated: [-1.0656107108230408, 2.032805355397536] ≈ [0.6, 1.2] (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:435
  Expression: ≈(evaluate(norm(x, 2)), p.optval, atol=atol, rtol=rtol)
   Evaluated: 2.2951740238931095 ≈ 0.3085743486881256 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:449
  Expression: ≈(p.optval, 1.0, atol=atol, rtol=rtol)
   Evaluated: 0.9181244075298309 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:450
  Expression: ≈(evaluate(x), [1, 1], atol=atol, rtol=rtol)
   Evaluated: [-5.745944283192347, 4.372972141531069] ≈ [1, 1] (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:451
  Expression: ≈(evaluate(norm(x, Inf)), p.optval, atol=atol, rtol=rtol)
   Evaluated: 5.745944283192347 ≈ 0.9181244075298309 (atol=0.001, rtol=0.0)

Error in testset socp_sum_squares_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:112
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -4.827078573405743 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_sum_squares_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:113
  Expression: ≈((evaluate(sumsquares(A * x + b)))[1], 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.49108529977117255 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_fix_and_free_addition:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:365
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 2.911600947380066 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:166
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: -107.6739527657628 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:175
  Expression: ≈(x.value, fill(3.0, (3, 1)), atol=atol, rtol=rtol)
   Evaluated: [2.26029279935321; 2.522986862109354; 2.2873531874025503] ≈ [3.0; 3.0; 3.0] (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:176
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: -2.311553683131933 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:177
  Expression: ≈(evaluate(sum((dot(/))([3, 6, 9], x))), 6, atol=atol, rtol=rtol)
   Evaluated: 7.640074098334605 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:185
  Expression: ≈(x.value, 3, atol=atol, rtol=rtol)
   Evaluated: 2.393121232684783 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:186
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: -0.031513236463069916 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:187
  Expression: ≈(evaluate(sum([3, 6, 9] / x)), 6, atol=atol, rtol=rtol)
   Evaluated: 7.521557936204615 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_quad_over_lin_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:96
  Expression: ≈(p.optval, 17.7831, atol=atol, rtol=rtol)
   Evaluated: 9.159939553588629 ≈ 17.7831 (atol=0.001, rtol=0.0)

Error in testset socp_quad_over_lin_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:97
  Expression: ≈(evaluate(quadoverlin(A * x + b, dot(c, x) + d)), 17.7831, atol=atol, rtol=rtol)
   Evaluated: 622.7799913273017 ≈ 17.7831 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:232
  Expression: ≈(p.optval, 6.1464, atol=atol, rtol=rtol)
   Evaluated: -5.7248939126729965 ≈ 6.1464 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:233
  Expression: ≈(evaluate(quadform(x, A)), 6.1464, atol=atol, rtol=rtol)
   Evaluated: 45.66984744264352 ≈ 6.1464 (atol=0.001, rtol=0.0)

Error in testset socp_fix_multiplication:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:387
  Expression: ≈(o1, 0.7 * norm(a[1:end - 1] - a[2:end]), atol=atol, rtol=rtol)
   Evaluated: -0.05904671922326088 ≈ 1.4 (atol=0.001, rtol=0.0)

Error in testset socp_fix_multiplication:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:396
  Expression: ≈(o2, norm(a .- mean(a)), atol=atol, rtol=rtol)
   Evaluated: -0.3078088350594044 ≈ 1.6733200530681511 (atol=0.001, rtol=0.0)

Error in testset socp_fix_multiplication:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:400
  Expression: o1 <= o2
   Evaluated: -0.05904671922326088 <= -0.3078088350594044

Error in testset socp_huber_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:260
  Expression: ≈(p.optval, 9, atol=atol, rtol=rtol)
   Evaluated: -20.609471794217825 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset socp_huber_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:261
  Expression: ≈(evaluate(sum(huber(x, 1))), 9, atol=atol, rtol=rtol)
   Evaluated: 217.7509779476582 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom_sum:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:323
  Expression: ≈(p.optval, 1.7227, atol=atol, rtol=rtol)
   Evaluated: -1393.5809520015027 ≈ 1.7227 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom_sum:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:324
  Expression: ≈(norm(g, 2) ^ 2, 0, atol=atol, rtol=rtol)
   Evaluated: 4.172610845308658 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:277
  Expression: ≈(p.optval, 1.2717, atol=atol, rtol=rtol)
   Evaluated: 0.005334315821528435 ≈ 1.2717 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:278
  Expression: ≈(evaluate(norm(x, 4.5)), 1.2717, atol=atol, rtol=rtol)
   Evaluated: 1822.3036244325183 ≈ 1.2717 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:128
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -12.585862755775452 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:129
  Expression: ≈(evaluate(sum(square(A * x + b))), 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.43083080037173616 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:142
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -12.585862755775452 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:143
  Expression: ≈(evaluate(sum(broadcast(^, expr, 2))), 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.43083080037173616 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:152
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: -12.585862755775452 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:153
  Expression: ≈(evaluate(sum((dot(*))(expr, expr))), 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.43083080037173616 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_dual_frobenius_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:75
  Expression: ≈(p.optval, sqrt(35), atol=atol, rtol=rtol)
   Evaluated: -40.9204557556659 ≈ 5.916079783099616 (atol=0.001, rtol=0.0)

Error in testset socp_dual_frobenius_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:76
  Expression: ≈(evaluate(norm(vec(m), 2)), sqrt(35), atol=atol, rtol=rtol)
   Evaluated: 3786.134527226669 ≈ 5.916079783099616 (atol=0.001, rtol=0.0)

Error in testset socp_dual_frobenius_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:77
  Expression: ≈((p.constraints[1]).dual, 0.6761, atol=atol, rtol=rtol)
   Evaluated: -14.439724853262305 ≈ 0.6761 (atol=0.001, rtol=0.0)

Error in testset socp_dual_frobenius_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:79
  Expression: ≈((p.constraints[2]).dual, dual, atol=atol, rtol=rtol)
   Evaluated: [0.058853134512901306 0.10853210464119911 … 0.10269268415868282 0.10944969579577446; 0.11619271337985992 0.2052182126790285 … 0.12661656737327576 0.17948893271386623; 0.12040860578417778 0.11640903726220131 … 0.1413174420595169 0.13482586480677128; 0.10853210464119911 0.1310539711266756 … 0.1686931550502777 0.10477489233016968] ≈ [0.169 0.169 … 0.169 0.169; 0.169 0.169 … 0.169 0.169; 0.169 0.169 … 0.169 0.169; 0.169 0.169 … 0.169 0.169] (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:12
  Expression: ≈(p.optval, 0.64888, atol=atol, rtol=rtol)
   Evaluated: -0.22646833956241608 ≈ 0.64888 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:13
  Expression: ≈(evaluate(norm2(A * x + b)), 0.64888, atol=atol, rtol=rtol)
   Evaluated: 135.31523474226637 ≈ 0.64888 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:27
  Expression: ≈(p.optval, 14.9049, atol=atol, rtol=rtol)
   Evaluated: 4.5076640248298645 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:28
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm2(x)), 14.9049, atol=atol, rtol=rtol)
   Evaluated: 58.15994028295006 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:29
  Expression: ≈((p.constraints[1]).dual, [4.4134, 5.1546], atol=atol, rtol=rtol)
   Evaluated: [1.5547420345246792; 1.6896588653326035] ≈ [4.4134, 5.1546] (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:42
  Expression: ≈(p.optval, 14.9049, atol=atol, rtol=rtol)
   Evaluated: 4.5076640248298645 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:43
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm2(x)), 14.9049, atol=atol, rtol=rtol)
   Evaluated: 58.15994028295006 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:44
  Expression: ≈((p.constraints[1]).dual, [4.4134, 5.1546], atol=atol, rtol=rtol)
   Evaluated: [1.5547420345246792; 1.6896588653326035] ≈ [4.4134, 5.1546] (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:58
  Expression: ≈(p.optval, 15.4907, atol=atol, rtol=rtol)
   Evaluated: 3.6039105355739594 ≈ 15.4907 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:59
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm_1(x)), 15.4907, atol=atol, rtol=rtol)
   Evaluated: 72.26094522606292 ≈ 15.4907 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:60
  Expression: ≈((p.constraints[1]).dual, [4.7062, 5.4475], atol=atol, rtol=rtol)
   Evaluated: [1.0734029971063137; 1.6433243937790394] ≈ [4.7062, 5.4475] (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:10
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 0.06961800903081894 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:11
  Expression: ≈(evaluate(abs(x)), 1, atol=atol, rtol=rtol)
   Evaluated: 157.94414637729182 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:12
  Expression: ≈((p.constraints[1]).dual, 1, atol=atol, rtol=rtol)
   Evaluated: 0.06961800903081894 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:23
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 0.6875217165797949 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:24
  Expression: ≈(evaluate(sum(abs(x))), 2, atol=atol, rtol=rtol)
   Evaluated: 595.0634046083151 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:25
  Expression: ≈((p.constraints[1]).dual, 1, atol=atol, rtol=rtol)
   Evaluated: 0.3657632004469633 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:26
  Expression: ≈((p.constraints[2]).dual, 1, atol=atol, rtol=rtol)
   Evaluated: 0.3217585161328316 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:27
  Expression: ≈((p.constraints[3]).dual[1, 1], 0, atol=atol, rtol=rtol)
   Evaluated: 0.3155363965779543 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:28
  Expression: ≈((p.constraints[3]).dual[2, 2], 0, atol=atol, rtol=rtol)
   Evaluated: 0.36046172492206097 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:29
  Expression: ≈((p.constraints[3]).dual[1, 2], (p.constraints[3]).dual[2, 1], atol=atol, rtol=rtol)
   Evaluated: 0.5891739726066589 ≈ 0.6089346334338188 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_inf_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:240
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -382.7510862359777 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_inf_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:241
  Expression: ≈(evaluate(norm_inf(x)), 0, atol=atol, rtol=rtol)
   Evaluated: 0.6049346695834601 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_inf_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:242
  Expression: ≈(norm((p.constraints[1]).dual), 0, atol=atol, rtol=rtol)
   Evaluated: 73.75342224941319 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_inf_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:243
  Expression: ≈(norm((p.constraints[2]).dual), 0, atol=atol, rtol=rtol)
   Evaluated: 73.47459817159933 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_maximum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:43
  Expression: ≈(p.optval, maximum(a), atol=atol, rtol=rtol)
   Evaluated: 0.39547282736748457 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset lp_maximum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:44
  Expression: ≈(evaluate(maximum(x)), maximum(a), atol=atol, rtol=rtol)
   Evaluated: 1221.2217211492493 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset lp_min_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:114
  Expression: ≈(p.optval, min(min_a, min_b), atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 0.47069970886514056 ≈ 0.01 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset lp_min_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:115
  Expression: ≈(evaluate(minimum(min(x, y))), min(min_a, min_b), atol=10atol, atol=atol, rtol=rtol)
   Evaluated: -218329.56209482622 ≈ 0.01 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:58
  Expression: ≈(p.optval, minimum(a), atol=atol, rtol=rtol)
   Evaluated: 0.49045644322177395 ≈ 0.01 (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:59
  Expression: ≈(evaluate(minimum(x)), minimum(a), atol=atol, rtol=rtol)
   Evaluated: -192492.2386380221 ≈ 0.01 (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:76
  Expression: ≈(p.optval, 130, atol=atol, rtol=rtol)
   Evaluated: 2043.2062242031097 ≈ 130 (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:77
  Expression: ≈((evaluate(objective))[1], 130, atol=atol, rtol=rtol)
   Evaluated: -10091.378027681434 ≈ 130 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:157
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 1.997102377936244 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:158
  Expression: ≈(evaluate(sumlargest(x, 2)), 2, atol=atol, rtol=rtol)
   Evaluated: 3115.1920294008155 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:169
  Expression: ≈(p.optval, 4.6, atol=atol, rtol=rtol)
   Evaluated: 0.9640698563307524 ≈ 4.6 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:170
  Expression: ≈(evaluate(sumlargest(x, 2)), 3.6, atol=atol, rtol=rtol)
   Evaluated: 1189.4983369865233 ≈ 3.6 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:209
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: -1692.3562006594148 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:222
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: -4910.117725584656 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:95
  Expression: ≈(p.optval, max(max_a, max_b), atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 0.4630861891491804 ≈ 1.0 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset lp_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:96
  Expression: ≈(evaluate(maximum(max(x, y))), max(max_a, max_b), atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 218465.44579889026 ≈ 1.0 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:183
  Expression: ≈(p.optval, 0.5, atol=atol, rtol=rtol)
   Evaluated: 0.17875470127910376 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:184
  Expression: ≈(evaluate(sumsmallest(x, 4)), 1, atol=atol, rtol=rtol)
   Evaluated: 9774.432357811645 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:195
  Expression: ≈(p.optval, 12, atol=atol, rtol=rtol)
   Evaluated: 123.3131360411644 ≈ 12 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:196
  Expression: ≈(evaluate(sumsmallest(x, 3)), 12, atol=atol, rtol=rtol)
   Evaluated: 7.626015847861886 ≈ 12 (atol=0.001, rtol=0.0)

Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:129
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -9.255867134779692 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:130
  Expression: ≈(evaluate(sum(pos(x))), 3, atol=atol, rtol=rtol)
   Evaluated: 3.486433986483088 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_1_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:256
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -14.8748042806983 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_1_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:257
  Expression: ≈(evaluate(norm_1(x)), 0, atol=atol, rtol=rtol)
   Evaluated: 1.5021957392394656 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_1_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:258
  Expression: ≈(norm((p.constraints[1]).dual), 0, atol=atol, rtol=rtol)
   Evaluated: 2.852863992746481 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_dual_norm_1_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:259
  Expression: ≈(norm((p.constraints[2]).dual), 0, atol=atol, rtol=rtol)
   Evaluated: 2.8901672273508416 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:404
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -2.127505585551262 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:405
  Expression: ≈(evaluate(objective), 0.0, atol=atol, rtol=rtol)
   Evaluated: 19.130684547666906 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_abs_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:409
  Expression: ≈(real_diff, 0.0, atol=atol, rtol=rtol)
   Evaluated: 19.130684547666906 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset sdp_Complex_Variable_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:337
  Expression: ≈(real_diff, zeros(10, 1), atol=atol, rtol=rtol)
   Evaluated: [0.008767749300772926; 0.004069548205619555; … ; 0.03183958026300693; -0.04323500663553825] ≈ [0.0; 0.0; … ; 0.0; 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_Complex_Variable_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:340
  Expression: ≈(imag_diff, zeros(10, 1), atol=atol, rtol=rtol)
   Evaluated: [0.004854953930767458; 0.0006554177391392135; … ; 0.0080466964122545; -0.058792105785241855] ≈ [0.0; 0.0; … ; 0.0; 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_nuclear_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:82
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: -20.040813855826855 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_nuclear_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:83
  Expression: ≈(evaluate(nuclearnorm(y)), 3, atol=atol, rtol=rtol)
   Evaluated: 1491.732271625798 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:190
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: 2.731942679733038 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:191
  Expression: ≈(evaluate(x), ones(3, 3), atol=atol, rtol=rtol)
   Evaluated: [203.7826833331032 137.35805336865187 168.33092329116073; 137.3580533686518 184.32083077310182 143.2605170597577; 168.3309232911607 143.26051705975755 241.57940450437061] ≈ [1.0 1.0 1.0; 1.0 1.0 1.0; 1.0 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:200
  Expression: ≈(p.optval, 8.4853, atol=atol, rtol=rtol)
   Evaluated: 3.9905337654054165 ≈ 8.4853 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:214
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 1.1138481199741364 ≈ -0.18509986251592636 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:228
  Expression: ≈(p1.optval, p2.optval, atol=atol, rtol=rtol)
   Evaluated: 3.993218846619129 ≈ 3.1199277490377426 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_sumsquares_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:385
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -183.47836955823004 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_sumsquares_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:386
  Expression: ≈(evaluate(objective), 0.0, atol=atol, rtol=rtol)
   Evaluated: 223.21902987778384 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_sumsquares_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:390
  Expression: ≈(real_diff, zeros(2, 1), atol=atol, rtol=rtol)
   Evaluated: [13.955930457981133; 5.333951155548615] ≈ [0.0; 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_operator_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:96
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 0.19977053627371788 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_operator_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:97
  Expression: ≈(evaluate(opnorm(y)), 4, atol=atol, rtol=rtol)
   Evaluated: 599.3544033690905 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_lambda_min_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:148
  Expression: ≈(p.optval, 2, atol=atol, rtol=rtol)
   Evaluated: 1.1536480113863945 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset sdp_lambda_min_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:149
  Expression: ≈(evaluate(eigmin(y)), 2, atol=atol, rtol=rtol)
   Evaluated: 0.3529299846973848 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset sdp_Real_Variables_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:312
  Expression: x1 == x2
   Evaluated: [0.6424808341878537; 0.23372204760345078; … ; 0.6861730196332523; 0.1751025881981376] == [0.6424808341878538; 0.2337220476034506; … ; 0.6861730196332521; 0.17510258819813762]

Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:69
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 0.5001638610847294 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset sdp_sigma_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:110
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 0.37475821003317833 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_sigma_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:111
  Expression: ≈(evaluate(sigmamax(y)), 4, atol=atol, rtol=rtol)
   Evaluated: 652.0482976888552 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:124
  Expression: ≈(p.optval, 4, atol=atol, rtol=rtol)
   Evaluated: 1.1138481199741364 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:125
  Expression: ≈(evaluate(eigmax(y)), 4, atol=atol, rtol=rtol)
   Evaluated: 65.43178773183993 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:133
  Expression: ≈(p.optval, 1.5, atol=atol, rtol=rtol)
   Evaluated: -32.234235825017095 ≈ 1.5 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:134
  Expression: ≈((p.constraints[1]).dual, im, atol=atol, rtol=rtol)
   Evaluated: 0.0 + 0.27233848813921213im ≈ im (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:135
  Expression: ≈((p.constraints[2]).dual, 0.75, atol=atol, rtol=rtol)
   Evaluated: -15.932422957383096 + 0.0im ≈ 0.75 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:163
  Expression: ≈(p.optval, 7, atol=atol, rtol=rtol)
   Evaluated: -1.62169548869133 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:164
  Expression: ≈((evaluate(matrixfrac(x, P)))[1], 7, atol=atol, rtol=rtol)
   Evaluated: 9.306858134039047 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_norm2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:366
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -0.36818306148052216 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_norm2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:367
  Expression: ≈(evaluate(objective), 0, atol=atol, rtol=rtol)
   Evaluated: 4.350262905538578 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_socp_norm2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:371
  Expression: ≈(real_diff, 0, atol=atol, rtol=rtol)
   Evaluated: 4.350262905538578 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:18
  Expression: ≈(p.optval, 0, atol=atol, rtol=rtol)
   Evaluated: -336.67011103010736 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:37
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: -1.1458564177155495 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:46
  Expression: ≈(p.optval, 3, atol=atol, rtol=rtol)
   Evaluated: 0.149319589138031 ≈ 3 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            2.05s / 100%             217MiB / 99.5%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 affine                     1    718ms  35.2%   718ms    120MiB  55.6%   120MiB
   affine_Partial_t...      1    349ms  17.1%   349ms   95.0MiB  44.0%  95.0MiB
   affine_dualvalue         1   47.4ms  2.32%  47.4ms   1.28MiB  0.59%  1.28MiB
   affine_dot_multi...      1   43.9ms  2.15%  43.9ms   3.34MiB  1.55%  3.34MiB
   affine_permutedd...      1   31.1ms  1.53%  31.1ms    672KiB  0.30%   672KiB
   affine_reshape_atom      1   27.8ms  1.37%  27.8ms   1.87MiB  0.86%  1.87MiB
   affine_transpose...      1   27.3ms  1.34%  27.3ms   1.90MiB  0.88%  1.90MiB
   affine_add_atom          1   26.3ms  1.29%  26.3ms   1.41MiB  0.65%  1.41MiB
   affine_index_atom        1   22.9ms  1.13%  22.9ms   2.27MiB  1.05%  2.27MiB
   affine_sum_atom          1   21.0ms  1.03%  21.0ms   1.50MiB  0.69%  1.50MiB
   affine_multiply_...      1   19.8ms  0.97%  19.8ms   1.97MiB  0.91%  1.97MiB
   affine_diag_atom         1   17.4ms  0.85%  17.4ms   1.15MiB  0.53%  1.15MiB
   affine_satisfy_p...      1   13.9ms  0.68%  13.9ms   1.37MiB  0.63%  1.37MiB
   affine_vcat_atom         1   13.3ms  0.65%  13.3ms   1.38MiB  0.64%  1.38MiB
   affine_hcat_atom         1   12.9ms  0.63%  12.9ms   1.35MiB  0.63%  1.35MiB
   affine_Diagonal_...      1   12.0ms  0.59%  12.0ms   1.01MiB  0.47%  1.01MiB
   affine_dot_atom_...      1   9.39ms  0.46%  9.39ms    564KiB  0.26%   564KiB
   affine_trace_atom        1   8.04ms  0.39%  8.04ms    554KiB  0.25%   554KiB
   affine_conv_atom         1   5.82ms  0.29%  5.82ms    738KiB  0.33%   738KiB
   affine_negate_atom       1   5.29ms  0.26%  5.29ms    399KiB  0.18%   399KiB
   affine_dot_atom          1   2.70ms  0.13%  2.70ms    298KiB  0.13%   298KiB
   affine_kron_atom         1    186μs  0.01%   186μs   30.2KiB  0.01%  30.2KiB
 socp                       1    671ms  32.9%   671ms   33.4MiB  15.5%  33.4MiB
   socp_rational_no...      1    231ms  11.3%   231ms   9.51MiB  4.40%  9.51MiB
   socp_dual_froben...      1   78.7ms  3.86%  78.7ms   2.07MiB  0.96%  2.07MiB
   socp_inv_pos_atom        1   52.7ms  2.59%  52.7ms   2.92MiB  1.35%  2.92MiB
   socp_dual_norm_2...      1   50.6ms  2.48%  50.6ms   3.10MiB  1.44%  3.10MiB
   socp_square_atom         1   41.8ms  2.05%  41.8ms   2.34MiB  1.09%  2.34MiB
   socp_dual_minima...      1   33.6ms  1.65%  33.6ms   2.10MiB  0.97%  2.10MiB
   socp_rational_no...      1   31.2ms  1.53%  31.2ms   2.54MiB  1.18%  2.54MiB
   socp_quad_form_atom      1   26.5ms  1.30%  26.5ms   1.33MiB  0.61%  1.33MiB
   socp_fix_multipl...      1   24.3ms  1.19%  24.3ms   1.47MiB  0.68%  1.47MiB
   socp_rational_no...      1   22.9ms  1.12%  22.9ms   1.68MiB  0.78%  1.68MiB
   socp_fix_and_fre...      1   22.4ms  1.10%  22.4ms   0.98MiB  0.45%  0.98MiB
   socp_huber_atom          1   18.4ms  0.90%  18.4ms   1.04MiB  0.48%  1.04MiB
   socp_sum_squares...      1   14.9ms  0.73%  14.9ms    743KiB  0.34%   743KiB
   socp_quad_over_l...      1   11.7ms  0.58%  11.7ms    735KiB  0.33%   735KiB
   socp_geo_mean_atom       1   9.73ms  0.48%  9.73ms    717KiB  0.32%   717KiB
   socp_norm_consis...      1    296μs  0.01%   296μs   58.9KiB  0.03%  58.9KiB
   socp_sqrt_atom           1   64.9μs  0.00%  64.9μs   22.3KiB  0.01%  22.3KiB
 sdp                        1    302ms  14.8%   302ms   24.3MiB  11.2%  24.3MiB
   sdp_sum_largest_...      1   62.1ms  3.05%  62.1ms   5.27MiB  2.44%  5.27MiB
   sdp_sdp_variables        1   30.2ms  1.48%  30.2ms   2.34MiB  1.08%  2.34MiB
   sdp_dual_lambda_...      1   28.5ms  1.40%  28.5ms   1.94MiB  0.90%  1.94MiB
   sdp_socp_norm2_atom      1   18.1ms  0.89%  18.1ms    767KiB  0.35%   767KiB
   sdp_Complex_Vari...      1   17.1ms  0.84%  17.1ms   2.12MiB  0.98%  2.12MiB
   sdp_socp_sumsqua...      1   17.0ms  0.83%  17.0ms    939KiB  0.42%   939KiB
   sdp_nuclear_norm...      1   16.3ms  0.80%  16.3ms   1.23MiB  0.57%  1.23MiB
   sdp_socp_abs_atom        1   14.3ms  0.70%  14.3ms    806KiB  0.36%   806KiB
   sdp_matrix_frac_...      1   12.6ms  0.62%  12.6ms   0.99MiB  0.46%  0.99MiB
   sdp_lambda_min_atom      1   11.8ms  0.58%  11.8ms    837KiB  0.38%   837KiB
   sdp_operator_nor...      1   11.5ms  0.56%  11.5ms   1.02MiB  0.47%  1.02MiB
   sdp_Real_Variabl...      1   11.0ms  0.54%  11.0ms   1.35MiB  0.63%  1.35MiB
   sdp_sigma_max_atom       1   10.6ms  0.52%  10.6ms   1.02MiB  0.47%  1.02MiB
   sdp_matrix_frac_...      1   10.2ms  0.50%  10.2ms    791KiB  0.36%   791KiB
   sdp_Partial_trace        1   9.94ms  0.49%  9.94ms    814KiB  0.37%   814KiB
   sdp_sdp_constraints      1   7.44ms  0.37%  7.44ms    630KiB  0.28%   630KiB
   sdp_kron_atom            1   6.80ms  0.33%  6.80ms    905KiB  0.41%   905KiB
   sdp_Issue_198            1   6.48ms  0.32%  6.48ms    571KiB  0.26%   571KiB
 lp                         1    289ms  14.2%   289ms   33.5MiB  15.5%  33.5MiB
   lp_sumsmallest_atom      1   62.1ms  3.05%  62.1ms   2.75MiB  1.27%  2.75MiB
   lp_dual_abs_atom         1   38.1ms  1.87%  38.1ms   1.91MiB  0.89%  1.91MiB
   lp_min_atom              1   36.4ms  1.79%  36.4ms   8.64MiB  4.00%  8.64MiB
   lp_max_atom              1   35.8ms  1.76%  35.8ms   8.64MiB  4.00%  8.64MiB
   lp_minimum_atom          1   31.0ms  1.52%  31.0ms   4.00MiB  1.85%  4.00MiB
   lp_sumlargest_atom       1   20.1ms  0.98%  20.1ms   1.88MiB  0.87%  1.88MiB
   lp_dual_norm_inf...      1   15.2ms  0.75%  15.2ms   0.97MiB  0.45%  0.97MiB
   lp_dual_norm_1_atom      1   15.0ms  0.74%  15.0ms    919KiB  0.42%   919KiB
   lp_dotsort_atom          1   14.1ms  0.69%  14.1ms   1.75MiB  0.81%  1.75MiB
   lp_pos_atom              1   8.96ms  0.44%  8.96ms    689KiB  0.31%   689KiB
   lp_maximum_atom          1   8.59ms  0.42%  8.59ms    810KiB  0.37%   810KiB
   lp_neg_atom              1   3.63ms  0.18%  3.63ms    526KiB  0.24%   526KiB
   lp_hinge_loss_atom       1   46.5μs  0.00%  46.5μs   21.4KiB  0.01%  21.4KiB
 constant                   1   57.7ms  2.83%  57.7ms   4.69MiB  2.17%  4.69MiB
   constant_fix!_wi...      1   15.0ms  0.73%  15.0ms   1.16MiB  0.54%  1.16MiB
   constant_fix!_wi...      1   13.4ms  0.66%  13.4ms   0.97MiB  0.45%  0.97MiB
   constant_Issue_166       1   8.78ms  0.43%  8.78ms    578KiB  0.26%   578KiB
   constant_fix!_an...      1   7.24ms  0.36%  7.24ms    556KiB  0.25%   556KiB
   constant_Test_do...      1   7.17ms  0.35%  7.17ms    861KiB  0.39%   861KiB
   constant_Issue_228       1   6.04ms  0.30%  6.04ms    565KiB  0.26%   565KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## Version information
`versioninfo()`:
```julia
Julia Version 1.3.1
Commit 2d5741174c (2019-12-30 21:36 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) Platinum 8171M CPU @ 2.60GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-6.0.1 (ORCJIT, skylake)
```

Manifest:
```julia
    Status `~/work/ConvexTests.jl/ConvexTests.jl/SDPA/Manifest.toml`
  [1520ce14] AbstractTrees v0.3.2
  [6e4b80f9] BenchmarkTools v0.5.0
  [b99e7846] BinaryProvider v0.5.8
  [49dc2e85] Calculus v0.5.1
  [523fee87] CodecBzip2 v0.6.0
  [944b1d66] CodecZlib v0.6.0
  [bbf7d656] CommonSubexpressions v0.2.0
  [34da2185] Compat v2.2.0
  [e66e0078] CompilerSupportLibraries_jll v0.2.0+1
  [f65535da] Convex v0.13.0
  [cb7cb77b] ConvexTests v0.1.0 [`~/work/ConvexTests.jl/ConvexTests.jl`]
  [1f15a43c] CxxWrap v0.8.1
  [9a962f9c] DataAPI v1.1.0
  [864edb3b] DataStructures v0.17.10
  [e2d170a0] DataValueInterfaces v1.0.0
  [163ba53b] DiffResults v1.0.2
  [b552c78f] DiffRules v1.0.1
  [191a621a] Dualization v0.2.2
  [f6369f11] ForwardDiff v0.10.9
  [92fee26a] GZip v0.5.1
  [cd3eb016] HTTP v0.8.12
  [83e8ac13] IniFile v0.5.0
  [82899510] IteratorInterfaceExtensions v1.0.0
  [682c06a0] JSON v0.21.0
  [7d188eb4] JSONSchema v0.2.0
  [4076af6c] JuMP v0.20.1
  [b8f27783] MathOptInterface v0.9.12
  [fdba3010] MathProgBase v0.7.8
  [739be429] MbedTLS v1.0.0
  [c8ffd9c3] MbedTLS_jll v2.16.0+1
  [d8a4904e] MutableArithmetics v0.2.7
  [77ba4419] NaNMath v0.3.3
  [efe28fd5] OpenSpecFun_jll v0.5.3+2
  [bac558e1] OrderedCollections v1.1.0
  [69de0a69] Parsers v0.3.12
  [b9a10b5b] SDPA v0.2.1
  [169818f4] SemidefiniteModels v0.1.1
  [276daf66] SpecialFunctions v0.10.0
  [90137ffa] StaticArrays v0.12.1
  [f9bf3ced] TableTestSets v0.1.0 #master (https://github.com/ericphanson/TableTestSets.jl)
  [3783bdb8] TableTraits v1.0.0
  [bd369af6] Tables v1.0.2
  [a759f4b9] TimerOutputs v0.5.3
  [3bb67fe8] TranscodingStreams v0.9.5
  [2a0f44e3] Base64 
  [ade2ca70] Dates 
  [8bb1440f] DelimitedFiles 
  [8ba89e20] Distributed 
  [b77e0a4c] InteractiveUtils 
  [76f85450] LibGit2 
  [8f399da3] Libdl 
  [37e2e46d] LinearAlgebra 
  [56ddb016] Logging 
  [d6f4376e] Markdown 
  [a63ad114] Mmap 
  [44cfe95a] Pkg 
  [de0858da] Printf 
  [3fa0cd96] REPL 
  [9a3f8284] Random 
  [ea8e919c] SHA 
  [9e88b42a] Serialization 
  [1a1011a3] SharedArrays 
  [6462fe0b] Sockets 
  [2f01184e] SparseArrays 
  [10745b16] Statistics 
  [8dfed614] Test 
  [cf7118a7] UUIDs 
  [4ec0a83e] Unicode 
```
