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

* [**Introduction**](../../wiki/Home)
* [**Examples**](../../wiki/Examples)
* [**Dataset Preparation**](../../wiki/Dataset-Preparation)
* [**Model Training** ‐ Introduction](../../wiki/Model-Training--‐--Introduction)
* [**Model Training** ‐ Basics](../../wiki/Model-Training--‐--Basics)
* [**Model Training** ‐ Comparison - Introduction](../../wiki/Model-Training--‐--Comparison---‐--Introduction)
* [**Model Training** ‐ Comparison - [Growth Rate]](../../wiki/Model-Training--‐--Comparison---‐--%5BGrowth-Rate%5D)
* [**Model Training** ‐ Comparison - [Betas]](../../wiki/Model-Training--‐--Comparison---‐--%5BBetas%5D)
* [**Model Training** ‐ Comparison - [Weight Decay]](../../wiki/Model-Training--‐--Comparison---‐--%5BWeight-Decay%5D)
* [**Model Training** ‐ Comparison - [Bias Correction]](../../wiki/Model-Training--‐--Comparison---‐--%5BBias-Correction%5D)
* [**Model Training** ‐ Comparison - [Decouple]](../../wiki/Model-Training--‐--Comparison---‐--%5BDecouple%5D)
* [**Model Training** ‐ Comparison - [Epochs x Repeats]](../../wiki/Model-Training--‐--Comparison---‐--%5BEpochs-x-Repeats%5D)
* [**Model Training** ‐ Comparison - [Resolution]](../../wiki/Model-Training--‐--Comparison---‐--%5BResolution%5D)
* [**Model Training** ‐ Comparison - [Aspect Ratio]](../../wiki/Model-Training--‐--Comparison---‐--%5BAspect-Ratio%5D)
* [**Model Training** ‐ Comparison - [Batch Size]](../../wiki/Model-Training--‐--Comparison---‐--%5BBatch-Size%5D)
* [**Model Training** ‐ Comparison - [Network Rank]](../../wiki/Model-Training--‐--Comparison---‐--%5BNetwork-Rank%5D)
* [**Model Training** ‐ Comparison - [Network Alpha]](../../wiki/Model-Training--‐--Comparison---‐--%5BNetwork-Alpha%5D)
* [**Model Training** ‐ Comparison - [Total Steps]](../../wiki/Model-Training--‐--Comparison---‐--%5BTotal-Steps%5D)
* [**Model Training** ‐ Comparison - [Scheduler]](../../wiki/Model-Training--‐--Comparison---‐--%5BScheduler%5D)
* [**Model Training** ‐ Comparison - [Noise Offset]](../../wiki/Model-Training--‐--Comparison---‐--%5BNoise-Offset%5D)
* [**Model Training** ‐ Comparison - [Min SNR Gamma]](../../wiki/Model-Training--‐--Comparison---‐--%5BMin-SNR-Gamma%5D)
* [**Model Training** ‐ Comparison - [Clip Skip]](../../wiki/Model-Training--‐--Comparison---‐--%5BClip-Skip%5D)
* [**Model Training** ‐ Comparison - [Precision]](../../wiki/Model-Training--‐--Comparison---‐--%5BPrecision%5D)
* [**Model Training** ‐ Comparison - [Number of CPU Threads per Core]](../../wiki/Model-Training--‐--Comparison---‐--%5BNumber-of-CPU-Threads-per-Core%5D)
* [**Model Training** ‐ Comparison - [Checkpoint]](../../wiki/Model-Training--‐--Comparison---‐--%5BCheckpoint%5D)
* [**Model Training** ‐ Comparison - [Regularisation]](../../wiki/Model-Training--‐--Comparison---‐--%5BRegularisation%5D)
* [**Model Training** ‐ Comparison - [Optimizer]](../../wiki/Model-Training--‐--Comparison---‐--%5BOptimizer%5D)
* [**Model Training** ‐ Comparison - [Other Important and Useful Parameters]](../../wiki/Model-Training--‐--Comparison---‐--%5BOther-Important-and-Useful-Parameters%5D)
* [**Model Training** ‐ Comparison - [Summary]](../../wiki/Model-Training--‐--Comparison---‐--%5BSummary%5D)
* [**Model Training** ‐ Comparison - [Final]](../../wiki/Model-Training--‐--Comparison---‐--%5BFinal%5D)
