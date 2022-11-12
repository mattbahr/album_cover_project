# Album Cover GAN
I trained a generative adversarial network on a small dataset of abstract paintings to produce album art for my band. The network was based on a model from one of TensorFlow's tutorials, and I tweaked the architecture to meet my specifications.

The final output selected as our album cover was a combination of three of the images produced during training. Note that the album title and band name were added after the fact, and that the network did not produce them.

The code was run inside a Docker container with GPU-enabled TensorFlow pre-configured. All paths are hard-coded to point to volumes within the container.

Here is a link to the dataset that the network was trained on: https://www.kaggle.com/datasets/bryanb/abstract-art-gallery

I realize now that a GAN probably isn't the best method for producing abstract art, as the whole point of the network is to produce hyper-realistic images, and there's no realism to an abstract painting; however, I'm super happy with the end result. The album cover came out pretty cool so I don't think I'd change anything about how I did this.
