[![Back to Home](https://img.shields.io/badge/Home-Home-blue)](../README.md)
# AI Fundamentals

[![English](https://img.shields.io/badge/Language-English-red)](README.md)
[![Portuguese](https://img.shields.io/badge/Language-Português-blue)](README-BR.md)

# I - Introduction to Artificial Intelligence

Artificial Intelligence (AI) is one of the main fields of computer science, dedicated to developing systems capable of performing tasks that traditionally required human intelligence. These tasks include logical reasoning, learning, sensory perception, decision-making, and solving complex problems. Since its origins, AI has evolved from a predominantly theoretical concept to practical applications widely used in sectors such as healthcare, mobility, and digital communication.

The trajectory of AI began with Turing's questions (1950), who, by asking "Can machines think?", proposed the Turing Test as a criterion for evaluating the artificial intelligence of computational systems. The field was formalized in 1956 during the Dartmouth Conference, where the term "Artificial Intelligence" was coined, and the foundations for the academic development of the discipline were laid (McCarthy et al., 1956).

Among the most relevant historical milestones is the development of the Eliza program, created by Joseph Weizenbaum in 1966, which used natural language processing techniques to simulate human conversations. This achievement demonstrated the feasibility of computational systems emulating human interactions in a simple way. Another notable advancement was the victory of IBM's Deep Blue supercomputer against world chess champion Garry Kasparov in 1997, showcasing the ability of artificial systems to surpass humans in highly complex strategic tasks (IBM, 1997).

Today, AI plays a fundamental role in various technologies that permeate contemporary society. Concrete examples of AI applications include:
- Virtual assistants like Siri, Alexa, and Google Assistant;
- Autonomous vehicles developed by Tesla;
- Medical diagnostic support systems.

These advancements attest to the growing impact of artificial intelligence in transforming economic, social, and scientific sectors.

Thus, Artificial Intelligence not only redefines the boundaries between human and computational capabilities but also introduces new ethical, technical, and social challenges that demand continuous reflection and academic innovation.

### Historical Evolution of Artificial Intelligence
The trajectory of Artificial Intelligence has been marked by three crucial moments:
- 1950s: The concept of AI is born with Alan Turing and the Dartmouth Conference.
- 1980s: Machine Learning (ML) gains prominence, with algorithms capable of learning patterns from data.
- 2010s: Deep Learning emerges as an advanced technique, using deep neural networks to learn highly complex patterns in large volumes of data.

These advancements were fundamental in transforming AI from a theoretical field to a practical and ubiquitous reality in today's society.

### Ethical Challenges of Artificial Intelligence
With the growth of AI applications, important ethical challenges also arise:
- Bias and Discrimination: Algorithms may reproduce biases present in training data, leading to unfair decisions.
- Data Privacy: The collection and use of large volumes of personal information raise concerns about security and misuse.
- Explainability and Transparency: AI systems often operate as "black boxes," making it difficult to understand the decisions they make.

Addressing these challenges is essential for the responsible development of artificial intelligence and to ensure its ethical adoption by society.

### Conceptual Map
Within this vast field, specialized subareas have emerged, enabling impressive advancements in how machines acquire and use knowledge. To better understand how AI subareas are organized, we will first visualize a layered structure, where each level deepens and specifies learning approaches. Later, we will detail each concept in this structure:

<pre>
Artificial Intelligence [Section I]
   └── Machine Learning (ML) [Section II]
       └── Types of learning:
           ├── Supervised Learning [Section III]
           ├── Unsupervised Learning [Section IV]
           └── Reinforcement Learning [Section V]
   └── Specific and powerful techniques:
       └── Neural Networks [Section VI]
           └── Deep Learning [Section VII]
</pre>

**To reinforce:**
- AI is the overarching umbrella.
- Machine Learning (ML) is a subfield within AI.
- Within ML, there are three types of learning (supervised, unsupervised, and reinforcement).
- And among the techniques ML uses to learn, neural networks (and especially deep learning) are the most advanced and powerful.

**Mnemonic to remember the hierarchy:**
> "Artificial Intelligence trains Machines, which learn in three ways, and use Neural Networks to think like us."

**How the phrase connects everything:**
- **"Artificial Intelligence"** → the general field.
- **"trains Machines"** → Machine Learning (ML).
- **"which learn in three ways"** → 
  1. Supervised Learning,
  2. Unsupervised Learning,
  3. Reinforcement Learning.
- **"and use Neural Networks"** → the primary learning technique.
- **"to think like us"** → reference to Deep Learning (inspired by the human brain).

# II - Machine Learning

Machine Learning (ML) is a subfield of AI that focuses on developing algorithms that enable computers to learn from data. Instead of being programmed with rigid rules, machine learning systems automatically adjust their behavior as they are exposed to new information.

## Machine Learning Process
The development of machine learning models follows a structured flow:

1. **Data Collection**: Gather relevant information from various sources.
2. **Data Preparation**: Clean, transform, and organize the data for use.
3. **Data Splitting**: Divide into training and testing sets.
4. **Model Training**: Adjust the model using the training set.
5. **Model Evaluation**: Test the model on new data to verify its generalization capability.

This sequence is crucial for building reliable and effective machine learning systems.

Within machine learning, there are three main types of learning, differentiated by how data is presented and how learning occurs:

## Types of Learning:

### III - Supervised Learning
In this type of learning, the system is trained using data that already has known answers (labels). The model learns to map inputs to desired outputs, such as classifying an email as spam or not spam.  

> 🚀 **Hands-on Exercise**  
> Explore a real classification case using Python:    
> **Predicting plant species with the Iris dataset**  
> ▶ [![Open in Colab](https://img.shields.io/badge/Open_in-Colab-blue?logo=google-colab)](https://colab.research.google.com/github/CoderPena/artificial-intelligence-portfolio/blob/main/01.fundamentals-of-ai/1.Iris_Supervised_Learning.ipynb)

### IV - Unsupervised Learning
Here, the system works with unlabeled data. The goal is to discover hidden patterns or structures in the data, such as grouping customers with similar behaviors without previously knowing who these groups are.

### V - Reinforcement Learning
In this scenario, the agent (the system) learns through interaction with the environment, making decisions and receiving rewards or penalties. The goal is to find a strategy that maximizes rewards over time, as in robot training or games like chess.

## Specific and Powerful Techniques

Beyond the types of learning, there are specific techniques that are particularly effective within machine learning.

### VI - Neural Networks
Inspired by the functioning of the human brain, neural networks are composed of layers of artificial neurons that process information and learn to recognize complex patterns.

#### Types of Neural Networks
There are specialized types of neural networks, designed for different types of data:

- **Convolutional Neural Networks (CNNs)**: Used for image and video analysis, extracting visual patterns like edges, textures, and objects.

- **Recurrent Neural Networks (RNNs)**:
Specialized in sequential data, such as text or audio, allowing consideration of order and context in processed information.

These architectures are the foundation for advanced applications in computer vision, natural language processing, and speech recognition.

### VII - Deep Learning
Deep Learning is a specialization within neural networks that uses very deep structures (with many hidden layers).  
This approach enables systems to learn highly complex and subtle representations of data, being especially powerful in tasks like speech recognition, computer vision, and natural language processing.


