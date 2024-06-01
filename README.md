![Example Result](https://github.com/EkaSulistyawan/deep-image-prior-pam/blob/main/example_result.png)

# deep-image-prior-pam

## What is this code about? 
- Try to re-implement the Deep Image Prior (DIP) for a case in scattered undersampled data.
- Scattered is preferable to avoid aliasing, but turns out the learned kernel might not necessarily have any connection with aliasing. It does not operate on the frequency domain

## Present Model Specs
- Platform: Torch
- Model: Encoder-Decoder Network

## Useful Paper
- [https://arxiv.org/abs/1711.10925] (Original DIP Paper, applied on any image)
- [https://arxiv.org/abs/2010.12041] (Implementation of DIP on Photoacoustic Image, though, actually applied on an image)

