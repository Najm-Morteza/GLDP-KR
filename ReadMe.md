In this repository, MATLAB implementation of the Gaussian-Filtered Local Difference Pattern (GLDP) algorithm with classification based on kernel representation (KR) will be available soon. We proposed this algorithm for a person-independent facial expression recognition system. We introduced it in the paper "Gaussian Filtered Local Difference Pattern with Kernel Representation for Person-Independent Facial Expression Recognition" submitted to the Journal of Ambient Intelligence and Humanized Computing.

---

The files that will be provided include the following:

1. Main.m: runs the proposed algorithm on the Japanese Female
Facial Expression (JAFFE) database.

2. JAFFEData.mat: including facial images and 35 emotion-based landmarks for each image from the JAFFE facial expression database.

3. Fn_GLDP.m: extracts face features with Gaussian filtered local difference pattern algorithm (GLDP).

4. Fn_Gaussian.m: Produces Gaussian low-pass filter.

5. Fn_DerivativeGaussian.m: produces derivative-gaussian high-pass filters.

6. Fn_CountHist.m: calculates the histogram of emotion-based blocks for each image.

7. Fn_KernelRepresentation_L2.m: classifies the feature vectors with the kernel representation algorithm
