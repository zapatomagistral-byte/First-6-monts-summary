# 🚀 6 Months of Deep Learning: From Zero Python to Replicating SOTA Vision Architectures

So this is a summary of what I have done in the last six months, moving from zero Python knowledge to somewhat replicating ConvNeXt V1.

---

## 📈 The Journey & Repository Index

### 1. 🐣 [First_MLPs](https://github.com/zapatomagistral-byte/First_MLPs.git)
So this repo contains the first two things I did in deep learning: first, an MLP for image classification on the MNIST dataset made fully in NumPy, and then a low-level PyTorch implementation of the same architecture for the same dataset. 

This was honestly pretty painful, mostly the NumPy version, because starting out in deep learning without any prior math knowledge forced me to first learn derivatives and the linear algebra concepts behind deep learning, which easily took me basically the second month entirely (the first one was learning basic Python).

> [!NOTE]
> **My learning & coding style:** The way I code is that I usually study the topic until I understand it, often for a couple of days, and then I try to replicate it off the top of my head in code. To be honest, in most cases, I coded assisted by AI—not to copy and paste the core logic, but just to keep recalling what I learned while I coded. This coding method is what I did for basically everything I did in my first 6 months. Also to note that commenting was assisted by AI and variable names were translated from spanish to english

> **On Git and timing:** All of this README (and the READMEs inside each repo) was written assisted by AI (mostly to make it look good) and all of this was written after the 6 months. I also had to learn Git while I learned everything else, so I decided to just upload everything at once when it felt right to do it, which was a bit intimidating but it is what it is.

---

### 2. 🧱 [First_CNN](https://github.com/zapatomagistral-byte/First_CNN.git)
This was the next logical step to do, done about 3 weeks after the first project. I decided to tackle Convolutional Neural Networks (CNNs), and at the same time start learning how PyTorch is actually used. 

However, I didn't go high-level with `nn.Module` yet; instead, I went with pure `nn.functional`. It was a real pain to handle every single weight separately for a network like this, but again, when you study previously for a couple of weeks, it is not that hard to make the code work.

---

### 3. 📦 [Module_CNN](https://github.com/zapatomagistral-byte/Module_CNN.git)
This was the next step: moving into using `nn.Module`. Since I already knew how a CNN worked, this was just a matter of learning the `nn.Module` class, which wasn't too hard either. Not much comment on it.

---

### 4. 🛡️ [ResNET_Replica](https://github.com/zapatomagistral-byte/ResNET_Replica.git)
This was the first time I tried to approach state-of-the-art architectures. The whole story is in the repo's README, but as a summary, it was pretty straightforward to code after studying the paper for a couple of days. Still, it was the hardest thing I had done so far (if you exclude that NumPy project).

---

### 5. 👑 [ConvNeXTv1_Replica](https://github.com/zapatomagistral-byte/ConvNeXTv1_Replica.git)
This was the next logical step, but it was by far the hardest one. I kind of rushed it—I made it in the same week I finished ResNet. 

Long story short: it was a great learning experience which showed me the point where deep learning stopped being just "get a better architecture" or "plug it into Colab and wait." I had to optimize code for the GPU and face a lot of other pains in making it work. It is all well explained in the repo's README.

---

## 🧠 Overall Reflection & Looking Forward

Overall, this has been a great learning experience. I am pretty proud of the timeframe in which I made all of this. Still, I know it is not *thaat* surprising, as having a Google account nowadays gives you access to basically top-tier robotics and AI professors (Frontier LLMs) that will clear any doubt you have in a second for free.

Looking forward, I will probably stop coding by hand. I think I have finally reached the point where I can start to really think about how to engineer solutions to deep learning problems (which is my dream and what i want to work on) and leave the coding itself to an agent, just still verifying it myself. I will most likely pause on computer vision right now and go towards NLP or World Models.

---

### 💬 Request for Feedback
I would be really thankful if you could give some feedback on my journey, as it is something I don't usually get.

Thank you for reading!
