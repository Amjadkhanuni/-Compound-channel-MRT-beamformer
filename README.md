NS (BS antennas), NR_list (IRS sizes): change to test different array sizes.

P0_dBm, sigma2_dbm: change TX power or noise floor.

b: number of bits per IRS element (increase to see improvement).

E0_required: harvested-energy constraint. Set to 0 to ignore energy; increase to make constraint active.

Channel model: currently Rayleigh (i.i.d.). To match the paper more closely, replace rand_channel with a Rician + pathloss model and deterministic LoS phases based on geometry.

Monte Carlo: run multiple random channel realizations and average results for smoother curves.
