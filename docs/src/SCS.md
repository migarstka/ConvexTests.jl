Table of contents:

```@contents
Pages = ["SCS.md"]
Depth = 4
```


Compilation warmup gives an estimate of 23 seconds of compilation time.

## SCS 
These tests were run on March 3, 2020 at 17:17 (UTC).

Tests run with `eps=1e-6`.

Excluded problems and classes of problems:
```julia
Regex[r"mip"]
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
<tr><td style="text-align:left;border-right: solid 2px;">SCS tests</td>
<td style="text-align:center;color:green;">421</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">422</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;exp</td>
<td style="text-align:center;color:green;">27</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">27</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">97</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">97</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">62</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp_and_exp</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">65</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">66</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Semidefinite_constraint</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
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
Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:69
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: Inf ≈ 1 (atol=0.001, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            91.9s / 98.3%           8.49GiB / 98.9%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 affine                     1    28.1s  31.1%   28.1s   2.72GiB  32.4%  2.72GiB
   affine_Partial_t...      1    2.84s  3.15%   2.84s    279MiB  3.25%   279MiB
   affine_permutedd...      1    2.77s  3.06%   2.77s    323MiB  3.75%   323MiB
   affine_dot_multi...      1    2.18s  2.41%   2.18s    148MiB  1.73%   148MiB
   affine_multiply_...      1    2.15s  2.38%   2.15s    211MiB  2.46%   211MiB
   affine_hcat_atom         1    2.09s  2.31%   2.09s    182MiB  2.12%   182MiB
   affine_transpose...      1    1.90s  2.10%   1.90s    172MiB  2.00%   172MiB
   affine_vcat_atom         1    1.27s  1.41%   1.27s   99.5MiB  1.16%  99.5MiB
   affine_Diagonal_...      1    1.20s  1.33%   1.20s    107MiB  1.25%   107MiB
   affine_add_atom          1    1.05s  1.16%   1.05s   67.7MiB  0.79%  67.7MiB
   affine_satisfy_p...      1    1.03s  1.14%   1.03s   57.3MiB  0.67%  57.3MiB
   affine_conv_atom         1    827ms  0.92%   827ms   54.1MiB  0.63%  54.1MiB
   affine_index_atom        1    624ms  0.69%   624ms   40.0MiB  0.47%  40.0MiB
   affine_dot_atom          1    589ms  0.65%   589ms   25.6MiB  0.30%  25.6MiB
   affine_reshape_atom      1    572ms  0.63%   572ms   27.8MiB  0.32%  27.8MiB
   affine_dualvalue         1    417ms  0.46%   417ms   33.0MiB  0.38%  33.0MiB
   affine_sum_atom          1    370ms  0.41%   370ms   31.0MiB  0.36%  31.0MiB
   affine_kron_atom         1    270ms  0.30%   270ms   20.0MiB  0.23%  20.0MiB
   affine_diag_atom         1    136ms  0.15%   136ms   14.2MiB  0.16%  14.2MiB
   affine_dot_atom_...      1    112ms  0.12%   112ms   4.94MiB  0.06%  4.94MiB
   affine_negate_atom       1   96.9ms  0.11%  96.9ms   3.80MiB  0.04%  3.80MiB
   affine_trace_atom        1   48.7ms  0.05%  48.7ms   2.60MiB  0.03%  2.60MiB
 sdp                        1    20.2s  22.3%   20.2s   1.78GiB  21.2%  1.78GiB
   sdp_operator_nor...      1    3.05s  3.38%   3.05s    256MiB  2.98%   256MiB
   sdp_sdp_constraints      1    2.78s  3.08%   2.78s    251MiB  2.92%   251MiB
   sdp_Partial_trace        1    2.33s  2.58%   2.33s    221MiB  2.57%   221MiB
   sdp_matrix_frac_...      1    1.16s  1.28%   1.16s   81.4MiB  0.95%  81.4MiB
   sdp_matrix_frac_...      1    968ms  1.07%   968ms   68.2MiB  0.79%  68.2MiB
   sdp_dual_lambda_...      1    793ms  0.88%   793ms   69.1MiB  0.80%  69.1MiB
   sdp_sum_largest_...      1    751ms  0.83%   751ms   45.1MiB  0.53%  45.1MiB
   sdp_Complex_Semi...      1    700ms  0.77%   700ms   24.7MiB  0.29%  24.7MiB
   sdp_Complex_Vari...      1    679ms  0.75%   679ms   33.1MiB  0.39%  33.1MiB
   sdp_socp_sumsqua...      1    657ms  0.73%   657ms   54.4MiB  0.63%  54.4MiB
   sdp_lambda_min_atom      1    603ms  0.67%   603ms   42.1MiB  0.49%  42.1MiB
   sdp_Issue_198            1    425ms  0.47%   425ms   38.6MiB  0.45%  38.6MiB
   sdp_nuclear_norm...      1    361ms  0.40%   361ms   30.9MiB  0.36%  30.9MiB
   sdp_socp_norm2_atom      1    331ms  0.37%   331ms   23.4MiB  0.27%  23.4MiB
   sdp_sdp_variables        1    277ms  0.31%   277ms   23.2MiB  0.27%  23.2MiB
   sdp_socp_abs_atom        1    257ms  0.28%   257ms   16.5MiB  0.19%  16.5MiB
   sdp_kron_atom            1    196ms  0.22%   196ms   19.5MiB  0.23%  19.5MiB
   sdp_sigma_max_atom       1    119ms  0.13%   119ms   13.4MiB  0.16%  13.4MiB
   sdp_Real_Variabl...      1    116ms  0.13%   116ms   5.13MiB  0.06%  5.13MiB
 socp                       1    19.9s  22.0%   19.9s   1.85GiB  22.0%  1.85GiB
   socp_quad_form_atom      1    2.65s  2.93%   2.65s   32.9MiB  0.38%  32.9MiB
   socp_dual_minima...      1    2.40s  2.65%   2.40s    160MiB  1.86%   160MiB
   socp_rational_no...      1    1.92s  2.12%   1.92s    133MiB  1.54%   133MiB
   socp_sum_squares...      1    1.21s  1.33%   1.21s    107MiB  1.25%   107MiB
   socp_inv_pos_atom        1    899ms  1.00%   899ms   69.0MiB  0.80%  69.0MiB
   socp_dual_norm_2...      1    739ms  0.82%   739ms   64.9MiB  0.76%  64.9MiB
   socp_rational_no...      1    671ms  0.74%   671ms   56.6MiB  0.66%  56.6MiB
   socp_quad_over_l...      1    662ms  0.73%   662ms   30.3MiB  0.35%  30.3MiB
   socp_huber_atom          1    532ms  0.59%   532ms   49.2MiB  0.57%  49.2MiB
   socp_fix_multipl...      1    505ms  0.56%   505ms   32.9MiB  0.38%  32.9MiB
   socp_norm_consis...      1    493ms  0.55%   493ms   27.6MiB  0.32%  27.6MiB
   socp_geo_mean_atom       1    378ms  0.42%   378ms   24.2MiB  0.28%  24.2MiB
   socp_dual_froben...      1    360ms  0.40%   360ms   25.4MiB  0.30%  25.4MiB
   socp_square_atom         1    339ms  0.37%   339ms   14.3MiB  0.17%  14.3MiB
   socp_fix_and_fre...      1    321ms  0.36%   321ms   30.2MiB  0.35%  30.2MiB
   socp_rational_no...      1    148ms  0.16%   148ms   9.03MiB  0.11%  9.03MiB
   socp_sqrt_atom           1   47.9ms  0.05%  47.9ms   1.08MiB  0.01%  1.08MiB
 constant                   1    10.4s  11.6%   10.4s   1.04GiB  12.3%  1.04GiB
   constant_Issue_166       1    3.71s  4.11%   3.71s    412MiB  4.80%   412MiB
   constant_fix!_wi...      1    3.41s  3.77%   3.41s    283MiB  3.30%   283MiB
   constant_Issue_228       1    779ms  0.86%   779ms   53.8MiB  0.63%  53.8MiB
   constant_fix!_wi...      1    546ms  0.60%   546ms   44.8MiB  0.52%  44.8MiB
   constant_fix!_an...      1    432ms  0.48%   432ms   43.3MiB  0.50%  43.3MiB
   constant_Test_do...      1    324ms  0.36%   324ms   19.1MiB  0.22%  19.1MiB
 lp                         1    6.15s  6.80%   6.15s    575MiB  6.69%   575MiB
   lp_dotsort_atom          1    1.06s  1.17%   1.06s   89.3MiB  1.04%  89.3MiB
   lp_min_atom              1    663ms  0.73%   663ms   39.1MiB  0.46%  39.1MiB
   lp_sumlargest_atom       1    574ms  0.64%   574ms   48.7MiB  0.57%  48.7MiB
   lp_max_atom              1    430ms  0.48%   430ms   32.3MiB  0.38%  32.3MiB
   lp_minimum_atom          1    328ms  0.36%   328ms   26.9MiB  0.31%  26.9MiB
   lp_sumsmallest_atom      1    268ms  0.30%   268ms   21.9MiB  0.25%  21.9MiB
   lp_dual_abs_atom         1    262ms  0.29%   262ms   18.5MiB  0.22%  18.5MiB
   lp_neg_atom              1    241ms  0.27%   241ms   11.5MiB  0.13%  11.5MiB
   lp_maximum_atom          1    220ms  0.24%   220ms   12.6MiB  0.15%  12.6MiB
   lp_dual_norm_inf...      1    118ms  0.13%   118ms   3.80MiB  0.04%  3.80MiB
   lp_pos_atom              1   82.7ms  0.09%  82.7ms   6.23MiB  0.07%  6.23MiB
   lp_dual_norm_1_atom      1   78.4ms  0.09%  78.4ms   3.49MiB  0.04%  3.49MiB
   lp_hinge_loss_atom       1    243μs  0.00%   243μs   49.7KiB  0.00%  49.7KiB
 exp                        1    3.67s  4.06%   3.67s    303MiB  3.52%   303MiB
   exp_log_atom             1    1.36s  1.51%   1.36s   95.2MiB  1.11%  95.2MiB
   exp_entropy_atom         1    432ms  0.48%   432ms   37.2MiB  0.43%  37.2MiB
   exp_log_sum_exp_...      1    318ms  0.35%   318ms   23.8MiB  0.28%  23.8MiB
   exp_exp_atom             1    302ms  0.33%   302ms   17.8MiB  0.21%  17.8MiB
   exp_logistic_los...      1    255ms  0.28%   255ms   14.0MiB  0.16%  14.0MiB
   exp_log_perspect...      1    242ms  0.27%   242ms   19.9MiB  0.23%  19.9MiB
   exp_relative_ent...      1   67.3ms  0.07%  67.3ms   5.21MiB  0.06%  5.21MiB
 sdp_and_exp                1    1.97s  2.18%   1.97s    154MiB  1.79%   154MiB
   sdp_and_exp_log_...      1    1.85s  2.05%   1.85s    138MiB  1.61%   138MiB
 ──────────────────────────────────────────────────────────────────────────────
```

## Version information
`versioninfo()`:
```julia
Julia Version 1.3.1
Commit 2d5741174c (2019-12-30 21:36 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) CPU E5-2673 v4 @ 2.30GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-6.0.1 (ORCJIT, broadwell)
```

Manifest:
```julia
    Status `~/work/ConvexTests.jl/ConvexTests.jl/SCS/Manifest.toml`
  [1520ce14] AbstractTrees v0.3.2
  [6e4b80f9] BenchmarkTools v0.5.0
  [b99e7846] BinaryProvider v0.5.8
  [523fee87] CodecBzip2 v0.6.0
  [944b1d66] CodecZlib v0.6.0
  [f65535da] Convex v0.13.0
  [cb7cb77b] ConvexTests v0.1.0 [`~/work/ConvexTests.jl/ConvexTests.jl`]
  [9a962f9c] DataAPI v1.1.0
  [e2d170a0] DataValueInterfaces v1.0.0
  [cd3eb016] HTTP v0.8.12
  [83e8ac13] IniFile v0.5.0
  [82899510] IteratorInterfaceExtensions v1.0.0
  [682c06a0] JSON v0.21.0
  [7d188eb4] JSONSchema v0.2.0
  [b8f27783] MathOptInterface v0.9.12
  [fdba3010] MathProgBase v0.7.8
  [739be429] MbedTLS v1.0.0
  [c8ffd9c3] MbedTLS_jll v2.16.0+1
  [d8a4904e] MutableArithmetics v0.2.7
  [bac558e1] OrderedCollections v1.1.0
  [69de0a69] Parsers v0.3.12
  [c946c3f1] SCS v0.6.6
  [f9bf3ced] TableTestSets v0.1.0 #master (https://github.com/ericphanson/TableTestSets.jl)
  [3783bdb8] TableTraits v1.0.0
  [bd369af6] Tables v1.0.2
  [a759f4b9] TimerOutputs v0.5.3
  [3bb67fe8] TranscodingStreams v0.9.5
  [2a0f44e3] Base64 
  [ade2ca70] Dates 
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
  [6462fe0b] Sockets 
  [2f01184e] SparseArrays 
  [10745b16] Statistics 
  [8dfed614] Test 
  [cf7118a7] UUIDs 
  [4ec0a83e] Unicode 
```
