```@contents
Pages = ["Tulip.md"]
```

## Tulip Float64
These tests were run on March 2, 2020 at 23:35 (UTC).

Tests run with default parameters in type Float64`.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"socp", r"sdp", r"benchmark"]
```

### Tests

Tests took 1 minute, 13 seconds to run.

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
<tr><td style="text-align:left;border-right: solid 2px;">Tulip tests</td>
<td style="text-align:center;color:green;">229</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">229</td>
</tr></table>
```

### Errors

```julia
```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            73.3s / 99.2%           8.28GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 constant                   1    42.7s  58.7%   42.7s   4.78GiB  57.9%  4.78GiB
   constant_Issue_166       1    30.6s  42.0%   30.6s   3.17GiB  38.5%  3.17GiB
   constant_fix!_wi...      1    3.45s  4.75%   3.45s    308MiB  3.65%   308MiB
   constant_Issue_228       1    691ms  0.95%   691ms   57.0MiB  0.67%  57.0MiB
   constant_fix!_wi...      1    506ms  0.70%   506ms   44.5MiB  0.53%  44.5MiB
   constant_fix!_an...      1    368ms  0.51%   368ms   42.9MiB  0.51%  42.9MiB
   constant_Test_do...      1    283ms  0.39%   283ms   19.0MiB  0.23%  19.0MiB
 affine                     1    23.7s  32.7%   23.7s   2.76GiB  33.5%  2.76GiB
   affine_Partial_t...      1    2.46s  3.38%   2.46s    322MiB  3.81%   322MiB
   affine_permutedd...      1    2.25s  3.09%   2.25s    321MiB  3.80%   321MiB
   affine_multiply_...      1    1.84s  2.53%   1.84s    211MiB  2.50%   211MiB
   affine_dot_multi...      1    1.76s  2.42%   1.76s    144MiB  1.71%   144MiB
   affine_transpose...      1    1.66s  2.29%   1.66s    170MiB  2.02%   170MiB
   affine_hcat_atom         1    1.61s  2.22%   1.61s    181MiB  2.14%   181MiB
   affine_vcat_atom         1    1.07s  1.47%   1.07s    100MiB  1.19%   100MiB
   affine_Diagonal_...      1    996ms  1.37%   996ms    107MiB  1.27%   107MiB
   affine_satisfy_p...      1    949ms  1.31%   949ms   57.9MiB  0.69%  57.9MiB
   affine_add_atom          1    825ms  1.14%   825ms   57.1MiB  0.68%  57.1MiB
   affine_conv_atom         1    685ms  0.94%   685ms   53.0MiB  0.63%  53.0MiB
   affine_index_atom        1    684ms  0.94%   684ms   59.9MiB  0.71%  59.9MiB
   affine_dot_atom          1    484ms  0.67%   484ms   19.2MiB  0.23%  19.2MiB
   affine_reshape_atom      1    481ms  0.66%   481ms   28.2MiB  0.33%  28.2MiB
   affine_sum_atom          1    429ms  0.59%   429ms   40.4MiB  0.48%  40.4MiB
   affine_dualvalue         1    350ms  0.48%   350ms   33.1MiB  0.39%  33.1MiB
   affine_kron_atom         1    222ms  0.31%   222ms   19.9MiB  0.24%  19.9MiB
   affine_diag_atom         1    114ms  0.16%   114ms   14.5MiB  0.17%  14.5MiB
   affine_dot_atom_...      1   88.2ms  0.12%  88.2ms   4.97MiB  0.06%  4.97MiB
   affine_negate_atom       1   75.8ms  0.10%  75.8ms   3.79MiB  0.04%  3.79MiB
   affine_trace_atom        1   38.7ms  0.05%  38.7ms   2.63MiB  0.03%  2.63MiB
 lp                         1    6.30s  8.66%   6.30s    725MiB  8.59%   725MiB
   lp_dotsort_atom          1    1.04s  1.42%   1.04s    109MiB  1.29%   109MiB
   lp_dual_abs_atom         1    595ms  0.82%   595ms   61.2MiB  0.72%  61.2MiB
   lp_min_atom              1    520ms  0.71%   520ms   47.7MiB  0.56%  47.7MiB
   lp_sumlargest_atom       1    502ms  0.69%   502ms   51.2MiB  0.61%  51.2MiB
   lp_sumsmallest_atom      1    488ms  0.67%   488ms   47.0MiB  0.56%  47.0MiB
   lp_max_atom              1    402ms  0.55%   402ms   43.5MiB  0.51%  43.5MiB
   lp_minimum_atom          1    344ms  0.47%   344ms   29.8MiB  0.35%  29.8MiB
   lp_dual_norm_inf...      1    303ms  0.42%   303ms   22.9MiB  0.27%  22.9MiB
   lp_neg_atom              1    231ms  0.32%   231ms   11.7MiB  0.14%  11.7MiB
   lp_maximum_atom          1    189ms  0.26%   189ms   12.8MiB  0.15%  12.8MiB
   lp_pos_atom              1   84.6ms  0.12%  84.6ms   6.41MiB  0.08%  6.41MiB
   lp_dual_norm_1_atom      1   69.9ms  0.10%  69.9ms   3.64MiB  0.04%  3.64MiB
   lp_hinge_loss_atom       1    257μs  0.00%   257μs   49.7KiB  0.00%  49.7KiB
 ──────────────────────────────────────────────────────────────────────────────```

### Version information
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
    Status `~/work/ConvexTests.jl/ConvexTests.jl/Tulip/Manifest.toml`
  [14f7f29c] AMD v0.3.1
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
  [40e66cde] LDLFactorizations v0.4.0
  [b8f27783] MathOptInterface v0.9.12
  [739be429] MbedTLS v1.0.0
  [c8ffd9c3] MbedTLS_jll v2.16.0+1
  [d8a4904e] MutableArithmetics v0.2.7
  [bac558e1] OrderedCollections v1.1.0
  [69de0a69] Parsers v0.3.12
  [f9bf3ced] TableTestSets v0.1.0 #master (https://github.com/ericphanson/TableTestSets.jl)
  [3783bdb8] TableTraits v1.0.0
  [bd369af6] Tables v1.0.2
  [a759f4b9] TimerOutputs v0.5.3
  [3bb67fe8] TranscodingStreams v0.9.5
  [6dd1b50a] Tulip v0.3.0
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
  [4607b0f0] SuiteSparse 
  [8dfed614] Test 
  [cf7118a7] UUIDs 
  [4ec0a83e] Unicode 
```
## Tulip BigFloat
These tests were run on March 2, 2020 at 23:36 (UTC).

Tests run with default parameters in type BigFloat`.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"socp", r"sdp", r"benchmark"]
```

### Tests

Tests took 42 seconds to run.

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
<tr><td style="text-align:left;border-right: solid 2px;">Tulip tests</td>
<td style="text-align:center;color:green;">229</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">229</td>
</tr></table>
```

### Errors

```julia
```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            42.2s / 100%            6.85GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 constant                   1    25.8s  61.1%   25.8s   2.71GiB  39.6%  2.71GiB
   constant_Issue_166       1    21.7s  51.3%   21.7s   2.29GiB  33.5%  2.29GiB
   constant_fix!_wi...      1    1.72s  4.08%   1.72s    134MiB  1.92%   134MiB
   constant_fix!_wi...      1    1.55s  3.68%   1.55s    183MiB  2.61%   183MiB
   constant_fix!_an...      1    133ms  0.32%   133ms   19.0MiB  0.27%  19.0MiB
   constant_Issue_228       1   96.3ms  0.23%  96.3ms   13.6MiB  0.19%  13.6MiB
   constant_Test_do...      1   83.4ms  0.20%  83.4ms   9.93MiB  0.14%  9.93MiB
 affine                     1    11.2s  26.6%   11.2s   2.63GiB  38.5%  2.63GiB
   affine_Partial_t...      1    2.72s  6.44%   2.72s   1.52GiB  22.2%  1.52GiB
   affine_transpose...      1    1.37s  3.25%   1.37s    122MiB  1.74%   122MiB
   affine_vcat_atom         1    724ms  1.72%   724ms   91.4MiB  1.30%  91.4MiB
   affine_dot_multi...      1    693ms  1.64%   693ms   95.2MiB  1.36%  95.2MiB
   affine_Diagonal_...      1    618ms  1.46%   618ms   78.4MiB  1.12%  78.4MiB
   affine_sum_atom          1    479ms  1.14%   479ms   66.8MiB  0.95%  66.8MiB
   affine_multiply_...      1    449ms  1.06%   449ms   56.6MiB  0.81%  56.6MiB
   affine_index_atom        1    431ms  1.02%   431ms   77.7MiB  1.11%  77.7MiB
   affine_reshape_atom      1    424ms  1.00%   424ms   51.3MiB  0.73%  51.3MiB
   affine_hcat_atom         1    378ms  0.90%   378ms   65.7MiB  0.94%  65.7MiB
   affine_dualvalue         1    284ms  0.67%   284ms   38.6MiB  0.55%  38.6MiB
   affine_add_atom          1    212ms  0.50%   212ms   27.3MiB  0.39%  27.3MiB
   affine_conv_atom         1    161ms  0.38%   161ms   19.9MiB  0.28%  19.9MiB
   affine_dot_atom_...      1    134ms  0.32%   134ms   18.5MiB  0.26%  18.5MiB
   affine_dot_atom          1    128ms  0.30%   128ms   16.4MiB  0.23%  16.4MiB
   affine_diag_atom         1    111ms  0.26%   111ms   30.8MiB  0.44%  30.8MiB
   affine_satisfy_p...      1   94.6ms  0.22%  94.6ms   13.0MiB  0.19%  13.0MiB
   affine_negate_atom       1   58.0ms  0.14%  58.0ms   4.23MiB  0.06%  4.23MiB
   affine_trace_atom        1   40.7ms  0.10%  40.7ms   6.32MiB  0.09%  6.32MiB
   affine_permutedd...      1   36.2ms  0.09%  36.2ms   4.58MiB  0.07%  4.58MiB
   affine_kron_atom         1   28.9ms  0.07%  28.9ms   3.17MiB  0.05%  3.17MiB
 lp                         1    5.21s  12.3%   5.21s   1.50GiB  22.0%  1.50GiB
   lp_max_atom              1    908ms  2.15%   908ms    453MiB  6.47%   453MiB
   lp_min_atom              1    833ms  1.97%   833ms    387MiB  5.52%   387MiB
   lp_sumlargest_atom       1    441ms  1.04%   441ms   80.8MiB  1.15%  80.8MiB
   lp_minimum_atom          1    421ms  1.00%   421ms    137MiB  1.95%   137MiB
   lp_dotsort_atom          1    408ms  0.97%   408ms   83.2MiB  1.19%  83.2MiB
   lp_dual_abs_atom         1    266ms  0.63%   266ms   36.7MiB  0.52%  36.7MiB
   lp_dual_norm_inf...      1    254ms  0.60%   254ms   24.0MiB  0.34%  24.0MiB
   lp_sumsmallest_atom      1    238ms  0.56%   238ms   98.2MiB  1.40%  98.2MiB
   lp_neg_atom              1    115ms  0.27%   115ms   19.2MiB  0.27%  19.2MiB
   lp_maximum_atom          1   91.3ms  0.22%  91.3ms   25.9MiB  0.37%  25.9MiB
   lp_pos_atom              1   85.1ms  0.20%  85.1ms   14.1MiB  0.20%  14.1MiB
   lp_dual_norm_1_atom      1   66.6ms  0.16%  66.6ms   11.5MiB  0.16%  11.5MiB
   lp_hinge_loss_atom       1    293μs  0.00%   293μs   49.7KiB  0.00%  49.7KiB
 ──────────────────────────────────────────────────────────────────────────────```

### Version information
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
    Status `~/work/ConvexTests.jl/ConvexTests.jl/Tulip/Manifest.toml`
  [14f7f29c] AMD v0.3.1
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
  [40e66cde] LDLFactorizations v0.4.0
  [b8f27783] MathOptInterface v0.9.12
  [739be429] MbedTLS v1.0.0
  [c8ffd9c3] MbedTLS_jll v2.16.0+1
  [d8a4904e] MutableArithmetics v0.2.7
  [bac558e1] OrderedCollections v1.1.0
  [69de0a69] Parsers v0.3.12
  [f9bf3ced] TableTestSets v0.1.0 #master (https://github.com/ericphanson/TableTestSets.jl)
  [3783bdb8] TableTraits v1.0.0
  [bd369af6] Tables v1.0.2
  [a759f4b9] TimerOutputs v0.5.3
  [3bb67fe8] TranscodingStreams v0.9.5
  [6dd1b50a] Tulip v0.3.0
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
  [4607b0f0] SuiteSparse 
  [8dfed614] Test 
  [cf7118a7] UUIDs 
  [4ec0a83e] Unicode 
```