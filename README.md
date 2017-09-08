# EZGAN Tensorflow Example

Quick running example for training your own Generative Adversarial Network to generate images using MNIST handwritten character dataset as training data.

Inspired by [jonbruner/ezgan](https://github.com/jonbruner/ezgan) and [llSourcell/Generative_Adversarial_networks_LIVE](https://github.com/llSourcell/Generative_Adversarial_networks_LIVE).
* Modifications were made to support Tensorflow 1.3 (primarily issues with scope variable exceptions)

## Quickstart

* Ensure you have virtualenv installed `pip install virtualenv`
  * `virtualenv --version`
  * `# 15.1.0`
* Ensure you have `python3`
  * `which python3`
  * `# /usr/local/bin/python3`
* Setup the virtual environment with python3
  * `virtualenv -p /usr/local/bin/python3 venv`
* Activate the environment, install dependencies
  * `source venv/bin/activate`
  * `pip install -r requirements.txt`
* Run the Jupyter Notebook & follow steps outlined in the document
  * `./venv/bin/jupyter notebook`
* Run the Tensorboard visualizations
  * `./venv/bin/tensorboard --logdir=tensorboard/gan`

## License

[MIT License](/LICENSE)

```text
Copyright (c) 2017 Alexander Wong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```