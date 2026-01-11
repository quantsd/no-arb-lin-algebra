# no-arb-lin-algebra
Trial project: finding arbitrages using matrix algebra
Summary:
- No arbitrage ⇔ existence of a positive state price vector
- Can solve via nullspace / LP / Farkas’ Lemma

We build payoff matrices for:
- Simple securities
- Options (discretized states)

and compute rank deficiencies or nullspace portfolios to show:
- Arbitrage portfolios explicitly
- Sensitivity to mispricing
