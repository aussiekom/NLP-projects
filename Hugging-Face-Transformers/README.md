## Hugging Face Transformers Tutorial (Winter '22) - Stanford Course
**[YouTube video course](https://youtu.be/b80by3Xk_A8?si=2Yee9XeMrtsjo8CG)**

This notebook will give an introduction to the Hugging Face Transformers Python library and some common patterns that you can use to take advantage of it. It is most useful for using or fine-tuning pretrained transformer models for your projects.

Hugging Face provides access to models (both the code that implements them and their pre-trained weights), model-specific tokenizers, as well as pipelines for common NLP tasks, and datasets and metrics in a separate datasets package. It has implementations in PyTorch, Tensorflow, and Flax (though we'll be using the PyTorch versions here!) 

We're going to go through a few use cases:
* Overview of Tokenizers and Models
* Finetuning - for your own task. We'll use a sentiment-classification example.


Chris spoke about a few main project types in the lecture:
1. Applying an existing pre-trained model to a new application or task and explore how to approach/solve it
2. Implementing a new or complex neural architecture and demonstrate its performance on some data
3. Analyzing the behavior of a model: how it represents linguistic knowledge or what kinds of phenomena it can handle or errors that it makes

Of these, `transformers` will be the most help for 1. and for 3. (You also can use it to define your own model architectures, but it's a bit tricky and we won't be covering it here.)


**Here are additional resources introducing the library that were used to make this tutorial:**

* [Hugging Face Docs](https://huggingface.co/docs/transformers/index)
  * Clear documentation
  * Tutorials, walk-throughs, and example notebooks
  * List of available models
* [Hugging Face Course](https://huggingface.co/course/)
* [Hugging Face O'Reilly Book](https://www.oreilly.com/library/view/natural-language-processing/9781098103231/)
    * Students have FREE access through the Stanford Library!

