# WIDS_5.0_coding_gpt_like_transformer

## Week 1 Resources 


[Python in 1 Hour](https://www.youtube.com/watch?v=kqtD5dpn9C8)
or 
You can also do a course on [kaggle](https://www.kaggle.com/learn/python) about python.
(Just a refresher)

(Optional: You can also watch some short videos or documents on learning some python libraries like [Numpy](https://www.youtube.com/watch?v=QUT1VHiLmmI),

[Pandas](https://www.youtube.com/watch?v=vmEHCJofslg) and [Matplotlib](https://www.youtube.com/watch?v=DAQNHzOcO5A) while we'll mainly focus on pytorch library later on this project)

(We recommend using VS Code or google colab for everything there is no need to use the same code editors as the tutorials)

(Just understand the basics don't need to memorize syntaxes so much)

A simple introduction to neural networks: [watch video 74 and 75](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)

Let's keep this a little lite for the 1st week :)

## Week 2 Resources 

Now that you have an intro to how NNs work, let's deep dive into their specific components in more detail:

[watch videos from 76 to 84](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) (recommended for this wids project)

Additionally, If you want to learn even more beyond this proect timeline:
Here is [The Longer way (The two courses by Stanford and DeepLearning.ai)](https://www.coursera.org/specializations/machine-learning-introduction)

(If you apply for a financial aid on coursera, you can get free certificates for your resume)

If not, you can watch the free versions here:

[Course 1 on youtube](https://www.youtube.com/watch?v=vStJoetOxJg&list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI)

[Course 2 on youtube](https://www.youtube.com/watch?v=ggWLvh484hs&list=PLyoNSC4BT4eVpykPF0Yx8C1Zs50XtD17L)

If you finish early, you can start exploring the tools required to build the transformer: 

[Introduction to Pytorch](https://www.youtube.com/watch?v=OIenNRt2bjg) (Optional for week 2) 

We'd move onto the attention mechanism and working of the decoder-only transformer by the 3rd week.


## Week 3 Resources


[Introduction to PyTorch](https://www.youtube.com/watch?v=OIenNRt2bjg) (Don't stress about syntax too much , Kudos if you already covered this in Week 2!)

**Step 1:** [watch videos 87 and 89](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)

**Step 2:**  [watch video 90](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)

or

If you prefer reading , check out [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)

(Don't try to understand everything word by word but at least learn the major concepts and use the video as a backup if you get stuck)

[PyTorch Tensors in 5 Mins](https://pytorch.org/tutorials/beginner/basics/tensorqs_tutorial.html)
(Skim this. Just understand that Tensors are matrices that run on the GPU)

[Attention in Transformers - 3Blue1Brown](https://www.youtube.com/watch?v=eMlx5fFNoYc)
(Optional but watch this if you want deep understanding through visualization)

# Assignment & Week 4 Resources

Welcome to the mid-term assignment! Before we build a smart Transformer, we are going to build a "Dumb" one: The Bigram Language Model.

## Mid-Term Assignment: The Bigram Model

Build a language model that predicts the next character based only on the current character. It has no memory, so the output will be hilarious gibberish.

1. Watch Andrej Karpathy's (Co-founder of OpenAI) video: [Let's build GPT: from scratch](https://www.youtube.com/watch?v=kCc8FmEb1nY).
2. Code along with him but stop at timestamp **42:13**.
3. You can use the `tinyshakespeare` dataset from the video or I recommend picking your own text file for fun (song lyrics, chat logs, novels, etc.).

**Submission:**
Take a screenshot of the gibberish text your model generates. It should look like broken English. This proves your model is working. Upload the code files and the screenshot in the G-form I'll be sharing soon.

## Week 4 Resources

After completing the assignment, we will continue with Week 4. We'll learn the procedure to upgrade our "dumb" Bigram model into a "smart" GPT by implementing **Masked Self-Attention**.

**Step 1:**
Before coding, you need to understand how the model behaves if we don't mask future words. Watch the [StatQuest: Decoder-Only Transformers](https://www.youtube.com/watch?v=bQ5BoolX9Ag) video. Focus on "Masked Self-Attention" and Query/Key/Value.

**Step 2:**
Resume the Andrej Karpathy tutorial from where you left off (timestamp 42:13) and watch until the end.

**Note**
Don't get intimidated by the math in Week 4. It is complex, but seeing your model generate coherent English after training will be worth it. Good Luck :)

