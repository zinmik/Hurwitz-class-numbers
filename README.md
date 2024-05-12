# Hurwitz-class-numbers
SageMath code supplement to the paper "Sums of Hurwitz class numbers, CM modular forms, and primes of the form x^2+ny^2".
The computation is used in the proof of Proposition 4.3 and Proposition 4.5.

Let HmM be the sum of H(4n-t^2) where where t runs through integers congruent to m (mod M).
The generating function for these sums can be completed to a quasimodular form of weight 2.
By twisting with the principal character chi_{M,0}, one obtains a holomorphic modular form.
We investigate the cases M = 6 and M = 8.
We check that this modular form is equal to a certain linear combination of functions
of the form D|S_{M,m}, where D(tau) := sum sigma(n)*q^n and S_{M,m} is the sieving operator,
and cusp forms Psi_k(chi,tau) = sum(sum_{x^2+ky^2=n}chi(x)x)q^n.

For each m, the computation runs in a separate cell of a Jupyter Notebook.
