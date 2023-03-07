# NextWordPredGPT2
In February 2019, OpenAI started quite a storm through its release of a new transformer-based language model called GPT-2. GPT-2 is a transformer-based generative language model that was trained on 40GB of curated text from the internet.
Let’s see GPT-2 in action!

Before we can start using GPT-2, let’s know a bit about the PyTorch-Transformers library. We will be using this library we will use to load the pre-trained models.

PyTorch-Transformers provides state-of-the-art pre-trained models for Natural Language Processing (NLP).

Most of the State-of-the-Art models require tons of training data and days of training on expensive GPU hardware which is something only the big technology companies and research labs can afford. But by using PyTorch-Transformers, now anyone can utilize the power of State-of-the-Art models!


Installing PyTorch-Transformers on your Machine
Installing Pytorch-Transformers is pretty straightforward in Python. You can simply use pip install:

pip install pytorch-transformers
or if you are working on Colab:

!pip install pytorch-transformers

NOTE:
Since most of these models are GPU-heavy, I would suggest working with Google Colab to run the code with GPU support.

Let’s build our own sentence completion model using GPT-2. We’ll try to predict the next word in the sentence:

“what is the fastest car in the _________”

I chose this example because this is the first suggestion that Google’s text completion gives. The code for doing the same is in the repository.
