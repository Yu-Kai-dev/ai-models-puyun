# ai-models-puyun

`ai-models-puyun` is an [ai-models](https://github.com/ecmwf-lab/ai-models) plugin to run [Metacarbon's PuYun].

PuYun: Medium-Range Global Weather Forecasting Using Large Kernel Attention Convolutional Networks,arXiv:2409.02123v2. https://arxiv.org/abs/2409.02123

PuYun was created by Shengchen Zhu, Yiming Chen, Peiying Yu, Xiang Qu, Yuxiao Zhou, Yiming Ma, Zhizhan Zhao, Yukai Liu, Hao Mi, Bin Wang. It is released by Metacarbon.

### Installation

To install the package, run:

```bash
pip install ai-models==0.6.4
pip install ai-models-puyun
```

This will install the package and its dependencies, in particular the ONNX runtime. The installation script will attempt to guess which runtime to install. You can force a given runtime by specifying the the `ONNXRUNTIME` variable, e.g.:

```bash
ONNXRUNTIME=onnxruntime-gpu pip install ai-models-puyun
```

For the ONNX file: Please contact the email address below and send an email stating your request and purpose. We will contact you and send you the ONNX files of the model:

```
    <zhushengchen@metac-inc.com>
```

When we receive your email, it means that you have accepted the open source license of ECMWF/ai-models.
Please use the parameter '--assets' to loading the models:

```bash
ai-models --assets <local-ONNX-directory>  puyun
```

