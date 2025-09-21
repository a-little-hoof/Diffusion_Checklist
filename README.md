# Diffusion_Checklist
Everything You Should Know About Diffusion Models

## VAE
- Explain the Evidence Lower Bound (ELBO).

## GAN
- What should the optimal discriminator satisfy?

## Diffusion Models

### Basics
- Write down the forward SDE and the reverse SDE.
- Write down the Fokker-Planck equation.
- Derive the probability flow ODE from the reverse SDE using the Fokker-Planck equation.
- Write down the VP-SDE and VE-SDE, and explain their connections to DDPM and NCSN.
- Prove the equivalence between score matching (SM) and denoising score matching (DSM).
- Explain the maximum likelihood training of diffusion models.
- What is the relationship between SM/DSM and maximum likelihood training?
- Explain Tweedie's formula.
- Use Tweedie's formula to transform epsilon prediction into x_0 prediction.
- Derive the optimal denoiser.
- Explain how DDIM accelerates the sampling procedure.
- Explain how DPM-Solver accelerates the sampling procedure. Why is DDIM a special case of DPM-Solver?

### Sampling
- In diffusion models, more sampling steps do not necessarily mean better results.
- Training and sampling of diffusion models doesn't require the same noise schedule.

## Diffusion Schrödinger Bridge
- What is Doob's h-transform?

## Flow Matching
- Write down the close form formula of velosity.

## One-Step/Few-Step Models
- Explain the idea of consistency models (CM).
- Explain the idea of MeanFlow (MF) and how to calculate the mean velocity during training.
- What is the relationship between MF and CM?

## Relevant Papers
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
- [Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502)
- [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456)
- [Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/abs/2206.00364)
- [Understanding Diffusion Models: A Unified Perspective](https://arxiv.org/abs/2208.11970)
- [A Connection Between Score Matching and Denoising Autoencoders](https://ieeexplore.ieee.org/abstract/document/6795935)
- [Interpretation and generalization of score matching](https://arxiv.org/pdf/1205.2629)
- [Maximum Likelihood Training of Score-Based Diffusion Models](https://arxiv.org/abs/2101.09258)
- [DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps](https://arxiv.org/abs/2206.00927)
- [Flow Matching for Generative Modeling](https://arxiv.org/abs/2210.02747)
- [Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow](https://arxiv.org/abs/2209.03003)
- [Mean Flows for One-step Generative Modeling](https://arxiv.org/abs/2505.13447)
- [Consistency Models](https://arxiv.org/abs/2303.01469)
- [Improved Techniques for Training Consistency Models](https://arxiv.org/abs/2310.14189)
- [Simplifying, Stabilizing and Scaling Continuous-Time Consistency Models](https://arxiv.org/abs/2410.11081)

