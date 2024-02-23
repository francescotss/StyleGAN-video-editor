# Analysis of STIT: GAN-based Facial Editing of Real Videos

Implementation and analysis of [Stitch it in Time: GAN-Based Facial Editing of Real Videos](https://stitch-time.github.io/)

>**Paper Abstract**: <br>
> The ability of Generative Adversarial Networks to encode rich semantics within their latent space has been widely adopted for facial image editing. However, replicating their success with videos has proven challenging. Sets of high-quality facial videos are lacking, and working with videos introduces a fundamental barrier to overcome - temporal coherency. We propose that this barrier is largely artificial. The source video is already temporally coherent, and deviations from this state arise in part due to careless treatment of individual components in the editing pipeline. We leverage the natural alignment of StyleGAN and the tendency of neural networks to learn low frequency functions, and demonstrate that they provide a strongly consistent prior. We draw on these insights and propose a framework for semantic editing of faces in videos, demonstrating significant improvements over the current state-of-the-art. Our method produces meaningful face manipulations, maintains a higher degree of temporal consistency, and can be applied to challenging, high quality, talking head videos which current methods struggle with.

## Requirements and Usage

The code is designed to be executed on Google Colab. Simply open the notebook [notebook.ipynb](notebook.ipynb). All the instructions to run trainings and evaluations are provided within the notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francescotss/StyleGAN-video-editor/blob/main/notebook.ipynb)

### Notebook Structure

1. **Code**: In this section, we show all the key components of the pipeline. Our code is a simplification of the original one. We have made significant changes to obtain a streamlined code that follows the pipeline in the paper.
2. **Experiments**:  In this section, we replicate the original results and conduct new experiments pushing the boundaries of the model.
