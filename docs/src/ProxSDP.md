# ProxSDP

## Tests

<table>
<tr class = "header headerLastRow">
<th style = "text-align: right; ">testset</th>
<th style = "text-align: right; ">pass</th>
<th style = "text-align: right; ">fail</th>
<th style = "text-align: right; ">error</th>
<th style = "text-align: right; ">broken</th>
<th style = "text-align: right; ">total</th>
</tr>
<tr>
<td style = "text-align: left; ">ProxSDP tests</td>
<td style = "color: green; text-align: center; ">306</td>
<td style = "color: red; text-align: center; ">86</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">392</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;constant</td>
<td style = "color: green; text-align: center; ">17</td>
<td style = "color: red; text-align: center; ">11</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">28</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;constant_Issue_166</td>
<td style = "text-align: center; ">0</td>
<td style = "color: red; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;constant_Issue_228</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">1</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">2</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;constant_fix!_with_vectors</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "color: red; text-align: center; ">7</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;constant_fix!_with_complex_numbers</td>
<td style = "color: green; text-align: center; ">9</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;constant_Test_double_fix!</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;constant_fix!_and_multiply</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">2</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;affine</td>
<td style = "color: green; text-align: center; ">120</td>
<td style = "color: red; text-align: center; ">19</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">139</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_satisfy_problems</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_transpose_atom</td>
<td style = "color: green; text-align: center; ">7</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_diag_atom</td>
<td style = "color: green; text-align: center; ">6</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_conv_atom</td>
<td style = "color: green; text-align: center; ">6</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style = "color: green; text-align: center; ">13</td>
<td style = "color: red; text-align: center; ">6</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">19</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_hcat_atom</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_vcat_atom</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_index_atom</td>
<td style = "color: green; text-align: center; ">9</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_Partial_transpose</td>
<td style = "color: green; text-align: center; ">9</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_add_atom</td>
<td style = "color: green; text-align: center; ">9</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_dot_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_dualvalue</td>
<td style = "color: green; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style = "color: green; text-align: center; ">6</td>
<td style = "color: red; text-align: center; ">1</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">7</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_sum_atom</td>
<td style = "color: green; text-align: center; ">9</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_reshape_atom</td>
<td style = "color: green; text-align: center; ">7</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_multiply_atom</td>
<td style = "color: green; text-align: center; ">12</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">12</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_kron_atom</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">2</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_trace_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;affine_negate_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;socp</td>
<td style = "color: green; text-align: center; ">57</td>
<td style = "color: red; text-align: center; ">40</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">97</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_dual_minimal_norm_solutions</td>
<td style = "color: green; text-align: center; ">12</td>
<td style = "color: red; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">15</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_sum_squares_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_fix_and_free_addition</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_inv_pos_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "color: red; text-align: center; ">6</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_quad_over_lin_atom</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_quad_form_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_fix_multiplication</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_huber_atom</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_rational_norm_dual_norm</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_rational_norm_atom_sum</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_rational_norm_atom</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_square_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "color: red; text-align: center; ">6</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_dual_frobenius_norm_atom</td>
<td style = "color: green; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_sqrt_atom</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_dual_norm_2_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "color: red; text-align: center; ">11</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">15</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_geo_mean_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;socp_norm_consistent_with_Base_for_matrix_variables</td>
<td style = "color: green; text-align: center; ">8</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">8</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;lp</td>
<td style = "color: green; text-align: center; ">47</td>
<td style = "color: red; text-align: center; ">15</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">62</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style = "color: green; text-align: center; ">12</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">12</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style = "color: green; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_maximum_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_min_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_minimum_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_dotsort_atom</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "color: red; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">7</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_max_atom</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "color: red; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_neg_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "color: red; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_pos_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style = "color: green; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;sdp</td>
<td style = "color: green; text-align: center; ">65</td>
<td style = "color: red; text-align: center; ">1</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">66</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">2</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_kron_atom</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">2</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style = "color: green; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_Issue_198</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_Complex_Semidefinite_constraint</td>
<td style = "color: green; text-align: center; ">2</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">2</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_Partial_trace</td>
<td style = "color: green; text-align: center; ">9</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">9</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style = "color: green; text-align: center; ">1</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">1</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style = "text-align: center; ">0</td>
<td style = "color: red; text-align: center; ">1</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">1</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style = "color: green; text-align: center; ">6</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">6</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style = "color: green; text-align: center; ">3</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">3</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style = "color: green; text-align: center; ">4</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">4</td>
</tr>
<tr>
<td style = "text-align: left; ">&nbsp;&nbsp;sdp_sdp_variables</td>
<td style = "color: green; text-align: center; ">5</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">0</td>
<td style = "text-align: center; ">5</td>
</tr>
</table>

## Stacktraces

Error in testset constant_Issue_166:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:16
  Expression: ≈(problem.optval, evaluate(sum(c * β)), atol=atol, rtol=rtol)
   Evaluated: -29.27719973537402 ≈ -28.627291213370853 (atol=0.001, rtol=0.0)

Error in testset constant_Issue_166:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:17
  Expression: ≈(problem.optval, 0.0, atol=atol, rtol=rtol)
   Evaluated: -29.27719973537402 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset constant_Issue_166:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:18
  Expression: ≈(β.value, zeros(5), atol=atol, rtol=rtol)
   Evaluated: [-0.4247160890862542; -0.4247160890862542; … ; -0.4247160890862542; -0.4247160890862542] ≈ [0.0, 0.0, 0.0, 0.0, 0.0] (atol=0.001, rtol=0.0)

Error in testset constant_Issue_228:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:30
  Expression: ≈(prob.optval, 0.0, atol=atol, rtol=rtol)
   Evaluated: -0.9891440369386555 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:120
  Expression: ≈(prob.optval, 2.5, atol=atol, rtol=rtol)
   Evaluated: -0.28483325181683067 ≈ 2.5 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:121
  Expression: ≈(evaluate(real(y * sum(x))), 2.5, atol=atol, rtol=rtol)
   Evaluated: -0.046461776886840694 ≈ 2.5 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:122
  Expression: ≈(evaluate(y), 0.5, atol=atol, rtol=rtol)
   Evaluated: -0.009292355377368139 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:134
  Expression: ≈(prob.optval, 1.25, atol=atol, rtol=rtol)
   Evaluated: -0.07397905709606734 ≈ 1.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:135
  Expression: ≈(evaluate(real(y * sum(x))), 1.25, atol=atol, rtol=rtol)
   Evaluated: -0.47795753260174895 ≈ 1.25 (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:136
  Expression: ≈(real(evaluate(x)), 0.5 * ones(5), atol=atol, rtol=rtol)
   Evaluated: [10.287112646721013, 10.287112646721013, 10.287112646721013, 10.287112646721013, 10.287112646721013] ≈ [0.5, 0.5, 0.5, 0.5, 0.5] (atol=0.001, rtol=0.0)

Error in testset constant_fix!_with_vectors:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/constant.jl:137
  Expression: ≈(evaluate(y), 0.5, atol=atol, rtol=rtol)
   Evaluated: -0.009292355377368139 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:194
  Expression: ≈(p.optval, s, atol=atol, rtol=rtol)
   Evaluated: 16.726833987735304 ≈ 13.8060696071072 (atol=0.001, rtol=0.0)

Error in testset affine_transpose_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:195
  Expression: ≈((evaluate(c * x' * d + d' * x * c' + (c * ((((x')')')')' * d)'))[1], s, atol=atol, rtol=rtol)
   Evaluated: 16.84945166006205 ≈ 13.8060696071072 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:332
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: 5.504697446319852 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:333
  Expression: ≈(evaluate(sum((dot(*))(x, [1, 2, 3]))), 6, atol=atol, rtol=rtol)
   Evaluated: 5.480518126174571 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:368
  Expression: ≈(p.optval, 9, atol=atol, rtol=rtol)
   Evaluated: 4.955476552178062 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:369
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 0.5995824078898512 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:380
  Expression: ≈(p.optval, 9, atol=atol, rtol=rtol)
   Evaluated: 4.955476552178062 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:381
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol=atol, rtol=rtol)
   Evaluated: 0.5995824078898512 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:458
  Expression: ≈(p.optval, 96, atol=atol, rtol=rtol)
   Evaluated: 102.16842451897514 ≈ 96 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:459
  Expression: ≈(evaluate(sum(x) + sum([y fill(4.0, 4)])), 96, atol=atol, rtol=rtol)
   Evaluated: 101.55225384178985 ≈ 96 (atol=0.001, rtol=0.0)

Error in testset affine_hcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:460
  Expression: ≈(evaluate([x y fill(2.0, (4, 2))]), fill(2.0, (4, 12)), atol=atol, rtol=rtol)
   Evaluated: [2.138806346044747 2.138806346044747 … 2.0 2.0; 2.138806346044747 2.138806346044747 … 2.0 2.0; 2.138806346044747 2.138806346044747 … 2.0 2.0; 2.138806346044747 2.138806346044747 … 2.0 2.0] ≈ [2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0; 2.0 2.0 … 2.0 2.0] (atol=0.001, rtol=0.0)

Error in testset affine_vcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:477
  Expression: ≈(p.optval, 104, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 87.2175463730942 ≈ 104 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_vcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:478
  Expression: ≈(evaluate(sum(x) + sum([y 4 * eye(4); x -(ones(4, 6))])), 104, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 87.28627904204994 ≈ 104 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_vcat_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:479
  Expression: ≈(evaluate([x; y']), 2 * ones(10, 4), atol=atol, rtol=rtol)
   Evaluated: [1.974645179141233 1.974645179141233 1.974645179141233 1.974645179141233; 1.974645179141233 1.974645179141233 1.974645179141233 1.974645179141233; … ; 1.3374013878971038 1.3374013878971038 1.3374013878971038 1.3374013878971038; 1.3374013878971038 1.3374013878971038 1.3374013878971038 1.3374013878971038] ≈ [2.0 2.0 2.0 2.0; 2.0 2.0 2.0 2.0; … ; 2.0 2.0 2.0 2.0; 2.0 2.0 2.0 2.0] (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom_for_matrix_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:108
  Expression: ≈(p.optval, 8.8, atol=atol, rtol=rtol)
   Evaluated: 7.1546899501383265 ≈ 8.8 (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom_for_matrix_variables:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:109
  Expression: ≈((evaluate(dot(fill(2.0, (2, 2)), x)))[1], 8.8, atol=atol, rtol=rtol)
   Evaluated: 7.111746521413027 ≈ 8.8 (atol=0.001, rtol=0.0)

Error in testset affine_Diagonal_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:510
  Expression: ≈(p.optval, 21, atol=atol, rtol=rtol)
   Evaluated: 36.67649411479496 ≈ 21 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:443
  Expression: ≈(p.optval, 136, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 201.73249259462992 ≈ 136 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/affine.jl:444
  Expression: ≈((evaluate(c' * reshaped))[1], 136, atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 201.73249259462997 ≈ 136 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:433
  Expression: ≈(p.optval, 3 / sqrt(5), atol=atol, rtol=rtol)
   Evaluated: 1.3362571467148914 ≈ 1.3416407864998738 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:435
  Expression: ≈(evaluate(norm(x, 2)), p.optval, atol=atol, rtol=rtol)
   Evaluated: 1.3419261294382518 ≈ 1.3362571467148914 (atol=0.001, rtol=0.0)

Error in testset socp_dual_minimal_norm_solutions:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:436
  Expression: ≈(dot(b, (p.constraints[1]).dual), p.optval, atol=atol, rtol=rtol)
   Evaluated: 1.3269277410800895 ≈ 1.3362571467148914 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:175
  Expression: ≈(x.value, fill(3.0, (3, 1)), atol=atol, rtol=rtol)
   Evaluated: [2.9749693337605394; 3.0000015263090507; 2.932496365009088] ≈ [3.0; 3.0; 3.0] (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:176
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: 9.091072054928876 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:177
  Expression: ≈(evaluate(sum((dot(/))([3, 6, 9], x))), 6, atol=atol, rtol=rtol)
   Evaluated: 6.07747025121533 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:185
  Expression: ≈(x.value, 3, atol=atol, rtol=rtol)
   Evaluated: 2.9748011972687736 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:186
  Expression: ≈(p.optval, 6, atol=atol, rtol=rtol)
   Evaluated: -3.768681102802426 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_inv_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:187
  Expression: ≈(evaluate(sum([3, 6, 9] / x)), 6, atol=atol, rtol=rtol)
   Evaluated: 6.050824511071924 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset socp_quad_over_lin_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:96
  Expression: ≈(p.optval, 17.7831, atol=atol, rtol=rtol)
   Evaluated: 38.45070101959378 ≈ 17.7831 (atol=0.001, rtol=0.0)

Error in testset socp_quad_over_lin_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:97
  Expression: ≈(evaluate(quadoverlin(A * x + b, dot(c, x) + d)), 17.7831, atol=atol, rtol=rtol)
   Evaluated: 18.752738396066306 ≈ 17.7831 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:246
  Expression: ≈(p.optval, 3.7713, atol=atol, rtol=rtol)
   Evaluated: 2.3263213500021656 ≈ 3.7713 (atol=0.001, rtol=0.0)

Error in testset socp_quad_form_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:247
  Expression: ≈(evaluate(quadform(x, A)), -1, atol=atol, rtol=rtol)
   Evaluated: -0.43649526677636563 ≈ -1 (atol=0.001, rtol=0.0)

Error in testset socp_huber_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:260
  Expression: ≈(p.optval, 9, atol=atol, rtol=rtol)
   Evaluated: 12.843733713493485 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset socp_huber_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:261
  Expression: ≈(evaluate(sum(huber(x, 1))), 9, atol=atol, rtol=rtol)
   Evaluated: 10.105373135260155 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:295
  Expression: ≈(p.optval, -2.144087, atol=atol, rtol=rtol)
   Evaluated: -2.1349775408156817 ≈ -2.144087 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:296
  Expression: ≈(sum(evaluate(x' * v)), -2.144087, atol=atol, rtol=rtol)
   Evaluated: -2.1339284502211457 ≈ -2.144087 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:297
  Expression: ≈(evaluate(norm(x, q)), 1, atol=atol, rtol=rtol)
   Evaluated: 0.9963571780294527 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_dual_norm:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:298
  Expression: ≈(sum(evaluate(x' * v)), -(sum(abs.(v) .^ qs) ^ (1 / qs)), atol=atol, rtol=rtol)
   Evaluated: -2.1339284502211457 ≈ -2.1440874584623084 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom_sum:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:323
  Expression: ≈(p.optval, 1.7227, atol=atol, rtol=rtol)
   Evaluated: 1.7696364195115328 ≈ 1.7227 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom_sum:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:324
  Expression: ≈(norm(g, 2) ^ 2, 0, atol=atol, rtol=rtol)
   Evaluated: 0.020404939656503494 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:277
  Expression: ≈(p.optval, 1.2717, atol=atol, rtol=rtol)
   Evaluated: 1.174004036582356 ≈ 1.2717 (atol=0.001, rtol=0.0)

Error in testset socp_rational_norm_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:278
  Expression: ≈(evaluate(norm(x, 4.5)), 1.2717, atol=atol, rtol=rtol)
   Evaluated: 1.2652507542180864 ≈ 1.2717 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:128
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.34335626999777763 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:129
  Expression: ≈(evaluate(sum(square(A * x + b))), 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.422738879613945 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:142
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.34335626999777763 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:143
  Expression: ≈(evaluate(sum(broadcast(^, expr, 2))), 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.422738879613945 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:152
  Expression: ≈(p.optval, 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.34335626999777763 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_square_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:153
  Expression: ≈(evaluate(sum((dot(*))(expr, expr))), 0.42105, atol=atol, rtol=rtol)
   Evaluated: 0.422738879613945 ≈ 0.42105 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:12
  Expression: ≈(p.optval, 0.64888, atol=atol, rtol=rtol)
   Evaluated: 0.3451432866863095 ≈ 0.64888 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:13
  Expression: ≈(evaluate(norm2(A * x + b)), 0.64888, atol=atol, rtol=rtol)
   Evaluated: 0.6507806377720051 ≈ 0.64888 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:27
  Expression: ≈(p.optval, 14.9049, atol=atol, rtol=rtol)
   Evaluated: 21.596659004411 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:28
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm2(x)), 14.9049, atol=atol, rtol=rtol)
   Evaluated: 21.179025218462847 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:29
  Expression: ≈((p.constraints[1]).dual, [4.4134, 5.1546], atol=atol, rtol=rtol)
   Evaluated: [0.0; 0.0] ≈ [4.4134, 5.1546] (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:42
  Expression: ≈(p.optval, 14.9049, atol=atol, rtol=rtol)
   Evaluated: 21.596659004411 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:43
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm2(x)), 14.9049, atol=atol, rtol=rtol)
   Evaluated: 21.179025218462847 ≈ 14.9049 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:44
  Expression: ≈((p.constraints[1]).dual, [4.4134, 5.1546], atol=atol, rtol=rtol)
   Evaluated: [0.0; 0.0] ≈ [4.4134, 5.1546] (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:58
  Expression: ≈(p.optval, 15.4907, atol=atol, rtol=rtol)
   Evaluated: 13.89252955868904 ≈ 15.4907 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:59
  Expression: ≈(evaluate(norm2(A * x + b) + lambda * norm_1(x)), 15.4907, atol=atol, rtol=rtol)
   Evaluated: 14.115129700260953 ≈ 15.4907 (atol=0.001, rtol=0.0)

Error in testset socp_dual_norm_2_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/socp.jl:60
  Expression: ≈((p.constraints[1]).dual, [4.7062, 5.4475], atol=atol, rtol=rtol)
   Evaluated: [0.4964391928448735; 0.43025116701608623] ≈ [4.7062, 5.4475] (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:76
  Expression: ≈(p.optval, 130, atol=atol, rtol=rtol)
   Evaluated: 43.51940032004327 ≈ 130 (atol=0.001, rtol=0.0)

Error in testset lp_minimum_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:77
  Expression: ≈((evaluate(objective))[1], 130, atol=atol, rtol=rtol)
   Evaluated: 43.89202654217595 ≈ 130 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:169
  Expression: ≈(p.optval, 4.6, atol=atol, rtol=rtol)
   Evaluated: 2.3347623180610992 ≈ 4.6 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:170
  Expression: ≈(evaluate(sumlargest(x, 2)), 3.6, atol=atol, rtol=rtol)
   Evaluated: 3.311311022724815 ≈ 3.6 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:209
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 20.296470880307382 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:210
  Expression: ≈(vec(x.value), [2; 2; 2; 1], atol=atol, rtol=rtol)
   Evaluated: [2.1442017272756204, 2.1442017272756204, 2.1442017272756204, 0.8565069852917632] ≈ [2, 2, 2, 1] (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:211
  Expression: ≈(evaluate(dotsort(x, [1, 2, 3, 4])), 19, atol=atol, rtol=rtol)
   Evaluated: 20.154322530772347 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:222
  Expression: ≈(p.optval, 19, atol=atol, rtol=rtol)
   Evaluated: 20.296470880307382 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:223
  Expression: ≈(evaluate(dotsort(x, [1, 2, 3, 4])), 19, atol=atol, rtol=rtol)
   Evaluated: 20.15432253077315 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:95
  Expression: ≈(p.optval, max(max_a, max_b), atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 0.9472650739375278 ≈ 1.0 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset lp_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:96
  Expression: ≈(evaluate(maximum(max(x, y))), max(max_a, max_b), atol=10atol, atol=atol, rtol=rtol)
   Evaluated: 0.9817365326794771 ≈ 1.0 (atol=0.01, atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:183
  Expression: ≈(p.optval, 0.5, atol=atol, rtol=rtol)
   Evaluated: -0.5288680528979821 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:184
  Expression: ≈(evaluate(sumsmallest(x, 4)), 1, atol=atol, rtol=rtol)
   Evaluated: 1.0913652824126006 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:195
  Expression: ≈(p.optval, 12, atol=atol, rtol=rtol)
   Evaluated: 11.773787356235928 ≈ 12 (atol=0.001, rtol=0.0)

Error in testset lp_sumsmallest_atom:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/lp.jl:196
  Expression: ≈(evaluate(sumsmallest(x, 3)), 12, atol=atol, rtol=rtol)
   Evaluated: 11.860404589750047 ≈ 12 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/IJj5u/src/problem_depot/problems/sdp.jl:69
  Expression: ≈(p.optval, 1, atol=atol, rtol=rtol)
   Evaluated: 1.0142050785326817 ≈ 1 (atol=0.001, rtol=0.0)
