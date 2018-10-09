# StochasticSemiDiscretisation.jl
Julia package to investigate the behaviour of linear stochastic delay equations

This package will provide a tool to simulate linear delay systems with stochastic parameters (Wiener process) or stochastic time delays:

<a href="https://www.codecogs.com/eqnedit.php?latex=\mathrm{d}\mathbf{x}_t&space;=&space;\left(\mathbf{A}&space;\mathbf{x}_t&space;&plus;&space;\mathbf{B}&space;\mathbf{x}_{t-\tau(t)}\right)\mathrm{d}t&space;&plus;\left(\boldsymbol{\sigma}&plus;\boldsymbol{\alpha}\mathbf{x}_t&space;&plus;&space;\boldsymbol{\beta}&space;\mathbf{x}_{t-\tau(t)}\right)\mathrm{d}W_t," target="_blank"><img src="https://latex.codecogs.com/gif.latex?\mathrm{d}\mathbf{x}_t&space;=&space;\left(\mathbf{A}&space;\mathbf{x}_t&space;&plus;&space;\mathbf{B}&space;\mathbf{x}_{t-\tau(t)}\right)\mathrm{d}t&space;&plus;\left(\boldsymbol{\sigma}&plus;\boldsymbol{\alpha}\mathbf{x}_t&space;&plus;&space;\boldsymbol{\beta}&space;\mathbf{x}_{t-\tau(t)}\right)\mathrm{d}W_t," title="\mathrm{d}\mathbf{x}_t = \left(\mathbf{A} \mathbf{x}_t + \mathbf{B} \mathbf{x}_{t-\tau(t)}\right)\mathrm{d}t +\left(\boldsymbol{\sigma}+\boldsymbol{\alpha}\mathbf{x}_t + \boldsymbol{\beta} \mathbf{x}_{t-\tau(t)}\right)\mathrm{d}W_t," /></a>

transforming the underlying differential equation into a mapping. Furthermore, with the use of mapping matrices the first- and second moment stability properties can be approximated.

*The package will be released here, as soon as the corresponding publication is revised, the method is confirmed and accepted.*
