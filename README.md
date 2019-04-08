# Does Generative Face Completion Help Face Recognition?

### Encoder-Decoder for Face Completion based on Gated Convolution

This page contains the code along with pre-trained models for solving the face completion task, aka face inpainting, following the method mentioned in _J. Mathai\*, I. Masi\*, W. AbdAlmageed, "[Does Generative Face Completion help Face Recognition?](#) ", in Proc. of IAPR International Conference on Biometrics (ICB) 2019 [1]_.


![Teaser](https://i.imgur.com/Pv0W9mb.png)


## Features
* **Encoder-Decoder** for face completion.
* Single forward pass to get the completed face
* The user can input the part to be completed, the model uses this mask with a gating mechanism

## Dependencies

* [Pytorch](https://pytorch.org)
* [Numpy](http://www.numpy.org/)
* [Python3.6](https://www.python.org/download/releases/3.6/)

The code has been tested on Linux only. On Linux you can rely on the default version of python, installing all the packages needed from the package manager or on Anaconda Python and install required packages through `conda`. 

## Usage

### Run it

```bash
$ python demo.py <image-path>
```

## Current Limitations


## Citation

Please cite our paper with the following bibtex if you use our face inpainter:

``` latex
@inproceedings{mathai2019doesgenerative,
  title={{D}oes {G}enerative {F}ace {C}ompletion {H}elp {F}ace {R}ecognition?},
  author={Mathai, Joe and Masi, Iacopo and Abd-Almageed, Wael},
  booktitle={IAPR International Conference on Biometrics (ICB)},
  year={2019},
}
```

## License and Disclaimer
Please, see [the LICENSE here](LICENSE.txt)

## References

[1] J. Mathai*, I. Masi*, W. AbdAlmageed, "Does Generative Face Completion help Face Recognition? ", in Proc. of IAPR International Conference on Biometrics (ICB) 2019

<sub>\* denotes equal contribution</sub>
    
## Changelog
- April 2019, First  Release 

## Disclaimer

_The SOFTWARE PACKAGE provided in this page is provided "as is", without any guarantee made as to its suitability or fitness for any particular use. It may contain bugs, so use of this tool is at your own risk. We take no responsibility for any damage of any sort that may unintentionally be caused through its use._

## Contacts

If you have any questions, drop an email to _iacopo@isi.edu_ and _jmathai@isi.edu_ or leave a message below with GitHub (log-in is needed).
