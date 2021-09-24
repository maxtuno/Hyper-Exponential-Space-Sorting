# HESS (New Feature 2021) polynomial black-box for Hamiltonian Path Problem

HESS is an Algorithm was developed by Oscar Riveros [oscar.riveros@peqnp.science] from 2012 to 2018.

HESS = Hyper Exponential Space Sorting 

(old repository https://github.com/www-PEQNP-science/HESS_HP)

Info:
https://www.youtube.com/watch?v=mA4gv-LuZXw

Example for TSP:
https://colab.research.google.com/drive/1crfbZyVXahi54zzQp0ENN-bNzMzWCYAa

FHCP Challenge Set (Instances for Hamiltonian Cycle but work for Hamiltonian Path)
https://sites.flinders.edu.au/flinders-hamiltonian-cycle-project/fhcp-challenge-set/

# Build

	mkdir build
	cd build
	cmake -DCMAKE_BUILD_TYPE=Release ..
	make

# Usage
	
	./hp instance

	./hc_check instance path
