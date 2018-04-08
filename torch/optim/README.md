Stochastic Quasi-Newton Methods For Nonconvex Stochastic Optimization

The paper proposes a general framework for methods where we assume that noisy information
about the gradients of the objective function are available via a stochastic first order oracle
(SFO). It is proved that almost sure convergence to stationary points is guaranteed for such
methods. The paper also analyzes the worst-case iteration complexity of this method. When a
randomly chosen iterate is returned as the output of such an algorithm, it is proved that in the
worst case, the SFO-calls complexity is O( −2 ) to ensure that the expectation of the squared
norm of the gradient is smaller than the given accuracy tolerance . Additionally, a specific
algorithm, namely, a stochastic damped limited-memory BFGS (SdLBFGS) method is also
proposed, that falls under the proposed framework. Moreover, the stochastic variance reduced
gradient variance reduction technique is incorporated into the proposed SdLBFGS method and
the SFO-calls complexity is analyzed. Numerical results on a nonconvex binary classification
problem using a support vector machine and a multiclass classification problem using neural
networks are reported. We aim to extend the experiments and benchmark against some of the
popular optimization algorithms already present in PyTorch. The experiments involve running
simple Deep Learning applications in Natural Language Processing using Recurrent Neural
Networks and its variants such as Long Short Term Memory Networks.

