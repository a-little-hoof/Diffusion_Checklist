# Diffusion Checklist

## VAE
- Explain the ELBO.

## GAN
- Prove that the optimal discriminator satisfies \( D^*(x) = \frac{q(x)}{q(x) + p_{\theta}(x)} \).

## Diffusion Models
- Write down the forward SDE and the reverse SDE.
- Write down Fokker-Planck equation.
- Derive the probabilty flow ODE from the reverse SDE using Fokker-Planck equation.
- Write down the VP-SDE and VE-SDE, and explain their connections to DDPM and NCSN.
- Prove the equivalence between score matching (SM) and denoising score matching (DSM).
- Explain the maximum likelihood training of diffusion models.
- What is the relationship between SM/DSM and maximum likelihood training?
- Explain Tweedie's formula.
- Use Tweedie's formula to transform epsilon prediction into \( x_0 \) prediction.
- Explain how DDIM accelerates the sampling procedure.
- Explain how DPM-Solver accelerates the sampling procedure. Why DDIM is a special case of DPM-Solver?


## Flow Matching

## One-Step/Few-Step Models
- Explain the idea of consistency models (CM).
- Explain the idea of MeanFlow (MF) and how to calculate the mean velocity during training.
- What is the relationship between MF and CM?