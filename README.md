# WIP: Stable Diffusion: text-to-person

> How to Generate High Quality Real People in Stable Diffusion

![Introduction.jpg](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/blob/master/Images/Introduction.jpg)

Many of you might heard of `Stable Diffusion` and its ability to generate various high-quality images. However, not everyone is attracted by creating random pictures of cute catgirls and everything else. Don't you think it would be much more interesting if we could train the neural network to create images... of ourselves? Or our favorite actors and musicians? Or our deceased relatives? Specific individuals, in general, rather than some abstract images based on what the neural network was trained on. This is what we will be doing, attempting to determine the most optimal workflow and automate it as much as possible.

In the end, our task boils down to several subtasks:

- preparing a dataset for training the model;
- searching for the most optimal and versatile parameters for training, as well as directly training the model;
- generating images using the trained model and automating this process.

### CONTENT

Due to the huge number of images the guide is divided into many pages. Please, read it in the specified order.

* [**Introduction**](./Home)
* [**Examples**](./Examples)
* [**Dataset Preparation**](./Dataset-Preparation)
* [**Model Training** ‐ Introduction](./Model-Training--‐--Introduction)
* [**Model Training** ‐ Basics](./Model-Training--‐--Basics)
* [**Model Training** ‐ Comparison - Introduction](./Model-Training--‐--Comparison---‐--Introduction)
* [**Model Training** ‐ Comparison - [Growth Rate]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BGrowth-Rate%5D)
* [**Model Training** ‐ Comparison - [Betas]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BBetas%5D)
* [**Model Training** ‐ Comparison - [Weight Decay]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BWeight-Decay%5D)
* [**Model Training** ‐ Comparison - [Bias Correction]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BBias-Correction%5D)
* [**Model Training** ‐ Comparison - [Decouple]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BDecouple%5D)
* [**Model Training** ‐ Comparison - [Epochs x Repeats]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BEpochs-x-Repeats%5D)
* [**Model Training** ‐ Comparison - [Resolution]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BResolution%5D)
* [**Model Training** ‐ Comparison - [Aspect Ratio]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BAspect-Ratio%5D)
* [**Model Training** ‐ Comparison - [Batch Size]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BBatch-Size%5D)
* [**Model Training** ‐ Comparison - [Network Rank]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BNetwork-Rank%5D)
* [**Model Training** ‐ Comparison - [Network Alpha]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BNetwork-Alpha%5D)
* [**Model Training** ‐ Comparison - [Total Steps]](https://github.com/InfluxOW/Stable-Diffusion-Text-To-Person/wiki/Model-Training--%E2%80%90--Comparison---%E2%80%90--%5BAspect-Ratio%5D)
