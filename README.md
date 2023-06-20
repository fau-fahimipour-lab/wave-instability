# wave-instability
Simulate a consumer-resource community on a 2-patch spatial patch network. Creates an animation showing the changes in the time series as diffusion rate is increased.

The governing equations are

$\dot{r_i} = r_i (1 - \theta r_i) - \alpha r_i n_i$

$\dot{n_i} = \alpha r_i n_i - n_i - \delta (n_i e^{-\phi n_i} - n_j e^{-\phi n_j})$
