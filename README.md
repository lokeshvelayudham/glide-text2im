# GLIDE

sdsdm
# Usage

To install this package, clone this repository and then run:

```
pip install -e .
```

For detailed usage examples, see the [notebooks](notebooks) directory.

 * The [text2im](notebooks/text2im.ipynb) [![][colab]][colab-text2im] notebook shows how to use GLIDE (filtered) with classifier-free guidance to produce images conditioned on text prompts. The local version of this notebook is ``text2im.py``
 * The [inpaint](notebooks/inpaint.ipynb) [![][colab]][colab-inpaint] notebook shows how to use GLIDE (filtered) to fill in a masked region of an image, conditioned on a text prompt. The local version of this notebook is ``inpaint.py``.
 * The [clip_guided](notebooks/clip_guided.ipynb) [![][colab]][colab-guided] notebook shows how to use GLIDE (filtered) + a filtered noise-aware CLIP model to produce images conditioned on text prompts. The local version of this notebook is ``clip_guided.py``.

[colab]: <https://colab.research.google.com/assets/colab-badge.svg>
[colab-text2im]: <https://colab.research.google.com/github/openai/glide-text2im/blob/main/notebooks/text2im.ipynb>
[colab-inpaint]: <https://colab.research.google.com/github/openai/glide-text2im/blob/main/notebooks/inpaint.ipynb>
[colab-guided]: <https://colab.research.google.com/github/openai/glide-text2im/blob/main/notebooks/clip_guided.ipynb>

# Local versions
The local versions of the notebooks are as close as possible to the original notebooks, which remain unchanged here. Changes to local versions include:

 * No need for "display"
 * Individual images are also saved, as well as the image strip (only upscaled images are saved by default)
