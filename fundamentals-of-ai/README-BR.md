[![Voltar à Home](https://img.shields.io/badge/Home-Início-blue)](../README-BR.md)
# Fundamentos de IA

[![English](https://img.shields.io/badge/Language-English-red)](README.md)
[![Portuguese](https://img.shields.io/badge/Idioma-Português-blue)](README-BR.md)

# I - Introdução à Inteligência Artificial

A Inteligência Artificial (IA) constitui um dos principais campos da ciência da computação, dedicado ao desenvolvimento de sistemas capazes de executar tarefas que, tradicionalmente, exigiram inteligência humana. Entre essas tarefas, destacam-se o raciocínio lógico, a aprendizagem, a percepção sensorial, a tomada de decisões e a resolução de problemas complexos. Desde suas origens, a IA evoluiu de uma concepção predominantemente teórica para uma aplicação prática, amplamente disseminada em setores como a saúde, a mobilidade e a comunicação digital.

A trajetória da IA teve início a partir dos questionamentos de Turing (1950), que, ao perguntar "As máquinas podem pensar?", propôs o Teste de Turing como critério para avaliar a inteligência artificial de sistemas computacionais. A formalização da área ocorreu em 1956, durante a Conferência de Dartmouth, evento em que foi cunhado o termo "Inteligência Artificial" e delineadas as bases para o desenvolvimento acadêmico da disciplina (McCarthy et al., 1956).

Entre os marcos históricos mais relevantes, destaca-se o desenvolvimento do programa Eliza, criado por Joseph Weizenbaum em 1966, que utilizava técnicas de processamento de linguagem natural para simular conversações humanas. Este feito demonstrou a viabilidade de sistemas computacionais emular interações humanas de maneira simples. Outro avanço notável foi a vitória do supercomputador Deep Blue, da IBM, contra o campeão mundial de xadrez Garry Kasparov em 1997, evidenciando a capacidade dos sistemas artificiais de superar seres humanos em tarefas estratégicas de alta complexidade (IBM, 1997).

Atualmente, a IA desempenha um papel fundamental em diversas tecnologias que permeiam a sociedade contemporânea. Exemplos concretos da aplicabilidade da IA incluem:
- Assistentes virtuais como Siri, Alexa e Google Assistant;
- Veículos autônomos desenvolvidos pela Tesla;
- Sistemas de suporte a diagnósticos médicos.

Estes avanços atestam o impacto crescente da inteligência artificial na transformação de setores econômicos, sociais e científicos.

Assim, a Inteligência Artificial não apenas redefine os limites entre capacidades humanas e computacionais, como também impõe novos desafios éticos, técnicos e sociais, que demandam contínua reflexão e inovação acadêmica.

Dentro desse vasto campo, surgiram subáreas especializadas que permitiram avanços impressionantes na forma como as máquinas adquirem e utilizam o conhecimento. Para entender melhor como as subáreas da IA se organizam, inicialmente iremos visualizar uma estrutura em camadas, onde cada nível aprofunda e especifica as abordagens de aprendizado. Posteriormente, iremos detalhar cada conceito da estrutura:

```
Inteligência Artificial [Seção I]
   └── Aprendizado de Máquina (AM) [Seção II]
   Tipos de aprendizado:
       ├── Aprendizado Supervisionado [Seção III]
       ├── Aprendizado Não Supervisionado [Seção IV]
       └── Aprendizado por Reforço [Seção V]
   Técnicas específicas e poderosas:
       └── Redes Neurais [Seção VI]
           └── Deep Learning [Seção VII]
```

**Para reforçar:**
- IA é o grande guarda-chuva.
- Aprendizado de Máquina (AM) é uma área dentro da IA.
- Dentro do AM, temos três tipos de aprendizado (supervisionado, não supervisionado e por reforço).
- E dentro das técnicas que o AM usa para aprender, redes neurais (e especialmente o deep learning) são as mais avançadas e potentes.

**Mnemônico para lembrar a hierarquia:**
> "A Inteligência Artificial treina Máquinas, que aprendem de três jeitos, e usam Redes Neurais para pensar como nós."

**Como a frase conecta tudo:**
- **"A Inteligência Artificial"** → o campo geral.
- **"treina Máquinas"** → Aprendizado de Máquina (AM).
- **"que aprendem de três jeitos"** → 
  1. Aprendizado Supervisionado,
  2. Aprendizado Não Supervisionado,
  3. Aprendizado por Reforço.
- **"e usam Redes Neurais"** → a principal técnica de aprendizado.
- **"para pensar como nós"** → referência ao Deep Learning (inspiração no cérebro humano).

# II - Aprendizado de Máquina

O Aprendizado de Máquina (Machine Learning - ML) é uma área dentro da IA que se concentra em desenvolver algoritmos que permitem aos computadores aprenderem a partir de dados. Em vez de serem programados com regras rígidas, os sistemas de aprendizado de máquina ajustam seu comportamento automaticamente conforme são expostos a novas informações.

Dentro do aprendizado de máquina, existem três principais tipos de aprendizado, que se diferenciam pela forma como os dados são apresentados e como o aprendizado acontece:

## Tipos de Aprendizado:

### III - Aprendizado Supervisionado
Neste tipo de aprendizado, o sistema é treinado utilizando dados que já possuem respostas conhecidas (rótulos). O modelo aprende a mapear entradas para saídas desejadas, como classificar um e-mail como spam ou não spam.
[![Abrir no Colab](https://img.shields.io/badge/Abrir_no-Colab-blue?logo=google-colab)](https://colab.research.google.com/github/CoderPena/artificial-intelligence-portfolio/blob/main/fundamentals-of-ai/1.Iris_Supervised_Learning.ipynb)

### IV - Aprendizado Não Supervisionado
Aqui, o sistema trabalha com dados sem rótulos. O objetivo é descobrir padrões ou estruturas escondidas nos dados, como agrupar clientes com comportamentos semelhantes sem saber previamente quem são esses grupos.

### V - Aprendizado por Reforço
Neste cenário, o agente (o sistema) aprende por meio da interação com o ambiente, tomando decisões e recebendo recompensas ou penalidades. O objetivo é encontrar uma estratégia que maximize as recompensas ao longo do tempo, como no treinamento de robôs ou em jogos como xadrez.

## Técnicas específicas e poderosas:

Além dos tipos de aprendizado, existem técnicas específicas que são particularmente eficazes dentro do aprendizado de máquina:

### VI - Redes Neurais
Inspiradas no funcionamento do cérebro humano, as redes neurais são compostas por camadas de neurônios artificiais que processam informações e aprendem a reconhecer padrões complexos.

### VII - Deep Learning
Deep Learning (Aprendizado Profundo) é uma especialização dentro das redes neurais que utiliza estruturas muito profundas (com muitas camadas ocultas).  
Essa abordagem permite que os sistemas aprendam representações altamente complexas e sutis dos dados, sendo especialmente poderosa em tarefas como reconhecimento de voz, visão computacional e processamento de linguagem natural.
