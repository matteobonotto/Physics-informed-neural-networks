# Physics Informed Neural Networks (PINNs)
Collection of examples of Physics Informed Neural Networks (PINN), for solving Partial Differential Equations (PDEs) via deep neural networks. All the examples are implemented using TensorFlow.

## Examples
1. `E1_PINN_Laplace.ipynb`: Solution of 2d Laplace equation in cartesian coordinates.
2. `E2_main_PINN_Laplace_subclassing.ipynb`: same test case as the previous one without using `tf.keras.Sequential`.
3. `E3_main_PINN_Poisson.ipynb`: solution of 2d Poisson equation in cartesian coordinates.
4. `E4_PINN_magnetostatic_square_coil.ipynb`: solution of the magnetostatic problem in axi-symmetric geometry (single coil of square cross section).
5. `E5_main_PINN_magnetostatic_2coils.ipynb`: solution of the magnetostatic problem in axi-symmetric geometry (2 coils of circular cross section).
 
## References
See the <a href=https://github.com/maziarraissi/PINNs>following repo for further details, as well as these references:
<ul>
  <li>Raissi, Maziar, Paris Perdikaris, and George E. Karniadakis. <a href=https://www.sciencedirect.com/science/article/pii/S0021999118307125>Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations</a> Journal of Computational Physics 378 (2019): 686-707.</li>
  <li>Raissi, Maziar, Paris Perdikaris, and George Em Karniadakis. <a href=https://arxiv.org/abs/1711.10561>Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differential Equations</a> arXiv preprint arXiv:1711.10561 (2017).</li>
  <li>Raissi, Maziar, Paris Perdikaris, and George Em Karniadakis. <a href=https://arxiv.org/abs/1711.10566>Physics Informed Deep Learning (Part II): Data-driven Discovery of Nonlinear Partial Differential Equations</a> arXiv preprint arXiv:1711.10566 (2017).</li>
</ul> 
 
