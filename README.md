# real_truck_loading_instances
# The name of each instance include 'inst3d_id' if it is light ('_l') or heavy ('_h').
# Id instances from 10*(k-1) to 10*k-1 have k different types of products, k between 1 and 15.
# The structure of each instance is as follows:

# First line: #camion num_trucks (number of truck types, 1 in all cases)
# Second line: id; W; L; H; Q; delta_1; delta_2; Q_1; Q_2; W_max; L_max; H_max
# Third line: #pallet |J| (number of types of pallets, 4 in all cases)
# Following |J| lines: id; w_j; l_j; h_j; q_j
# Next line: #productos |I| (number of types of products)
# Next |I| lines: id; n_i; l_i; w_i; h_i; q_i; r_x; r_y; r_z; n'_i; n_i0; n_i1; n_i2; n_i3
# Last line: min(V_1, V_3); min(V_1, V_2, V_3, V_4)
