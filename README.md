# Implementing-DDPM-DDIM

# Results:

## DDPM Content generation:

<p align="center">
  <img src="output/ddpm.gif" alt="Undistorted" width="750"/>
</p>

### DDPM Guided Content Generation:

#### Single token context:

<p align="center">
  <img src="output/contex_output.png" alt="Undistorted" width="450"/>
</p>

#### Multi-token context:

<p align="center">
  <img src="output/multi_contex_op.png" alt="Undistorted" width="450"/>
</p>


## DDIM Content Generation:

<p align="center">
  <img src="output/ddim.gif" alt="Undistorted" width="750"/>
</p>



## DDPM VS DDIM Runtime Comparison:

| Denoising algo. |     "CPU"(s)    |     "GPU"(s)    |
|-----------------|-----------------|-----------------|
|     `DDPM`      | 2min 19s / loop |  2.13 s / loop  |
|     `DDIM`      | 7.91 s / loop   |  115 ms / loop  |


