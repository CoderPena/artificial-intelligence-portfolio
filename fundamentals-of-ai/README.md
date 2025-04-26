# Fundamentals of AI

[![English](https://img.shields.io/badge/Language-English-blue)](README.md)
[![Portuguese](https://img.shields.io/badge/Idioma-Português-brightgreen)](README-BR.md)

# I - Introduction to Artificial Intelligence

Artificial Intelligence (AI) is one of the main fields of computer science, dedicated to developing systems capable of performing tasks that traditionally required human intelligence. Among these tasks are logical reasoning, learning, sensory perception, decision-making, and solving complex problems. Since its origins, AI has evolved from a predominantly theoretical concept to a practical application, widely disseminated across sectors such as healthcare, mobility, and digital communication.

The trajectory of AI began with Turing's inquiries (1950), who, by asking "Can machines think?", proposed the Turing Test as a criterion for evaluating the artificial intelligence of computational systems. The formalization of the field occurred in 1956, during the Dartmouth Conference, an event where the term "Artificial Intelligence" was coined and the foundations for the academic development of the discipline were established (McCarthy et al., 1956).

Among the most relevant historical milestones, the development of the Eliza program stands out, created by Joseph Weizenbaum in 1966, which used natural language processing techniques to simulate human conversations. This achievement demonstrated the feasibility of computational systems emulating human interactions in a simple manner. Another remarkable advance was the victory of IBM's supercomputer Deep Blue over world chess champion Garry Kasparov in 1997, highlighting the ability of artificial systems to surpass humans in highly complex strategic tasks (IBM, 1997).

Currently, AI plays a fundamental role in various technologies that permeate contemporary society. Concrete examples of AI applications include:
- Virtual assistants like Siri, Alexa, and Google Assistant;
- Autonomous vehicles developed by Tesla;
- Medical diagnosis support systems.

These advancements attest to the growing impact of artificial intelligence in transforming economic, social, and scientific sectors.

Thus, Artificial Intelligence not only redefines the boundaries between human and computational capabilities but also imposes new ethical, technical, and social challenges that demand continuous academic reflection and innovation.

Within this vast field, specialized subareas have emerged that have enabled impressive advances in how machines acquire and utilize knowledge. To better understand how AI subareas are organized, we will first visualize a layered structure, where each level deepens and specifies learning approaches. Later, we will detail each concept of the structure:

```
Artificial Intelligence [Section I]
   └── Machile Learning (ML) [Section II]
   Types of learning:
   ├── Supervised Learning [Section III]
   ├── Unsupervised Learning [Section IV]
   └── Reinforcement Learning [Section V]
   Specific and powerful techniques:
   └── Neural Networks [Section VI]
       └── Deep Learning [Section VII]
```

**To reinforce:**
- AI is the big umbrella.
- Machine Learning (ML) is an area within AI.
- Within ML, there are three types of learning (supervised, unsupervised, and reinforcement).
- And among the techniques that ML uses to learn, neural networks (especially deep learning) are the most advanced and powerful.

**Mnemonic to remember the hierarchy:**
> "Artificial Intelligence trains Machines, which learn in three ways, and use Neural Networks to think like us."

**How the phrase connects everything:**
- **"Artificial Intelligence"** → the general field.
- **"trains Machines"** → Machine Learning (ML).
- **"which learn in three ways"** → 
  1. Supervised Learning,
  2. Unsupervised Learning,
  3. Reinforcement Learning.
- **"and use Neural Networks"** → the main learning technique.
- **"to think like us"** → refers to Deep Learning (inspired by the human brain).

# II - Machine Learning

Machine Learning (ML) is an area within AI focused on developing algorithms that enable computers to learn from data. Instead of being programmed with rigid rules, machine learning systems automatically adjust their behavior as they are exposed to new information.

Within machine learning, there are three main types of learning, which differ based on how data is presented and how learning occurs:

## Types of Learning:

### III - Supervised Learning
In this type of learning, the system is trained using data that already has known answers (labels). The model learns to map inputs to desired outputs, such as classifying an email as spam or not spam.

### IV - Unsupervised Learning
Here, the system works with unlabeled data. The goal is to discover hidden patterns or structures in the data, such as grouping customers with similar behaviors without previously knowing who these groups are.

### V - Reinforcement Learning
In this scenario, the agent (the system) learns by interacting with the environment, making decisions, and receiving rewards or penalties. The objective is to find a strategy that maximizes rewards over time, such as in training robots or playing games like chess.

## Specific and powerful techniques:

Besides the types of learning, there are specific techniques that are particularly effective within machine learning:

### VI - Neural Networks
Inspired by the functioning of the human brain, neural networks are composed of layers of artificial neurons that process information and learn to recognize complex patterns.

### VII - Deep Learning
Deep Learning is a specialization within neural networks that uses very deep structures (with many hidden layers).  
This approach allows systems to learn highly complex and subtle representations of data, being especially powerful in tasks such as:
- Voice recognition;
- Computer vision;
- Natural language processing.
