Figure 1: Performance comparison with CK-SVD with sparsity levels 4 and 8 (288 dictionary atoms)
trained on measurements from one fixed measurement matrix. All trainable models have been
trained on a training set of 10000 compressed and noisy piecewise function with an SNR of 10dB.
The observation dimension is M and the piecewise smooth functions have a dimension of 256.

<img src="figure1_fixed_measurement_matrix_for_all_page-0001.jpg" width=60% height=60%>

---

Figure 2: Performance comparison with CK-SVD with sparsity levels 2, 4 and 8 (288 dictionary
atoms) trained on measurements from varying measurement matrices for every training sample,
respectively. All trainable models have been trained on a training set of 10000 compressed and
noisy piecewise function with an SNR of 10dB. The observation dimension is M and the piecewise
smooth functions have a dimension of 256.

<img src="figure2_varying_measurement_matrices_for_ck_svd_page-0001.jpg" width=60% height=60%>

---

Figure 3: Performance comparison with CK-SVD with sparsity levels 4 and 8 (128 dictionary atoms)
trained on measurements from varying measurement matrices for every training sample, respectively.
All trainable models have been trained on a training set of 5000 compressed MNIST images. The
observation dimension is M and the MNIST images have a dimension of 784. (The simulations for
CK-SVD4 for M = 200 have not finished yet.)

<img src="figure3_varying_measurement_matrices_for_all_mnist_page-0001.jpg" width=60% height=60%>

---

Figure 4: Performance of sVaeCom trained on a training set of 1000 grayscaled celebA 64 × 64 (i.e.,
N = 4096) cropped and centered images. The model has been trained on measurements from
varying measurement matrices for every training sample, respectively. It is compared with Lasso,
whose hyperparameter is tuned based on a ground-truth dataset.

<img src="figure_4_performance_on_celebA_page-0001.jpg" width=60% height=60%>

---

Figure 5: Exemplary reconstructed images from the grayscaled celebA dataset. sVaeCom has been
trained on solely 1000 compressed training samples. The measurement dimension M equals 512.
The images have a dimension of 4096. The hyperparameter of Lasso has been tuned on a ground
truth dataset.

<img src="figure_5_celebA_qualitative_M512_page-0001.jpg" width=80% height=80%>

---

Figure 6: Exemplary reconstructed images from the grayscaled celebA dataset. sVaeCom has been
trained on solely 1000 compressed training samples. The measurement dimension M equals 1024.
The images have a dimension of 4096. The hyperparameter of Lasso has been tuned on a ground
truth dataset.

<img src="figure_6_celebA_qualitative_M1024_page-0001.jpg" width=80% height=80%>
