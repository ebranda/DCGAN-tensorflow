# DCGAN in Tensorflow

Fork of https://github.com/carpedm20/DCGAN-tensorflow for use with Spell remote.


## Prerequisites

Need to include the following (for backwards compat):
pip install tqdm
pip install pillow==5.0.0
pip install scipy==1.0.1


## Usage

To train a model (using dataset folder "./data/myimagesfolder" and 256 pixel high images):

    $ python main.py --dataset myimagesfolder --input_height=256 --output_height=256 --train --crop
