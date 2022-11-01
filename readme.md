# Learning Tactic 
better to use top-down approach means learning how to implement a method before going back and covering the theory.
In summary, you don’t need to understand everything about the specific architecture of an LSTM cell; as a human, it shouldn’t be your job to understand it. Just keep in mind what the *LSTM cell is meant to do: allow past information to be reinjected at a later time.*
# Agenda
1. build a neural network
# Advices
1. The level of mathematical detail presented is much much more than is required to get started. If you are a stronger programmer than mathematician, go straight to the code. 
2. TensorFlow + MPI is probably the least newbie friendly framework pairing I could think of. If TensorFlow doesn't break your debugger with it's internal graph compilation, MPI certainly will. You might as well be writing in C. My personal recommendation is PyTorch + Ray.  For reference, the Neural MMO infrastructure is built on Ray, and the experiment code is all in PyTorch.
3. from pdb import set_trace as T. It's the single best software engineering trick I know. RL is a pain to get working -- take advantage of interactive debugging.

For newcomers to Deep Learning
RL is probably the area of deep learning least friendly to newcomers. The major RL algorithms are dead simple, but they require a ton of code to get anything working. And debugging bad RL training loops is a nightmare.  I'd suggest going through the [Stanford CS231N](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) lecture videos first and getting comfortable training a few CNNs and LSTMs. 

# Learning Topic

## Machine Learning
- https://www.deeplearning.ai/

## Reinforcement Learning && Deeping Learning
- https://spinningup.openai.com/en/latest/index.html
- http://karpathy.github.io/2016/05/31/rl/
- https://www.udemy.com/course/artificial-intelligence-az/learn/lecture/7264680#overview
- https://www.superdatascience.com/pages/artificial-intelligence

# Inpiration
- AI playlist
- Andrea Ng
- Lex Fridman
- Fei Fei Li
