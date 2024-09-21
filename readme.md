<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>

<p align="center">
Este projeto foi desenvolvido por Rafael Gonçalves como um desafio de engenharia de prompts, onde o objetivo é criar um assistente de personal trainer automatizado que gera treinos personalizados com base em fatores como biotipo corporal, disponibilidade de tempo e tipos de exercícios preferidos. O assistente personaliza os treinos conforme as características e necessidades individuais do usuário, utilizando as melhores práticas de engenharia de prompts.
</p>

## 📋 Índice

- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de Negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

O projeto tem como objetivo criar um assistente de personal trainer automatizado que gera planos de treino personalizados. O usuário informa seu biotipo corporal, a quantidade de dias disponíveis para treino e o tipo de exercício preferido, e o assistente gera um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

Para personalizar o treino, o primeiro passo é identificar o biotipo corporal do usuário. Existem três biotipos principais:

| **Imagem**                                                    | **Biotipo**    | **Descrição**                                                        |
|---------------------------------------------------------------|---------------|----------------------------------------------------------------------|
| <img src=".github/assets/ectomorph.jpg" width="50%" height="50%"> | **Ectomorfo** | Corpo magro, dificuldade para ganhar peso e massa muscular.          |
| <img src=".github/assets/mesomorph.jpg" width="50%" height="50%"> | **Mesomorfo** | Corpo naturalmente musculoso, facilidade para ganhar massa muscular. |
| <img src=".github/assets/endmorph.jpg" width="50%" height="50%">  | **Endomorfo** | Tendência a acumular gordura, dificuldade em perder peso.            |

> **Nota:** Selecione o biotipo que mais se aproxima do seu corpo atual para maximizar a eficiência do treino.

---

## 📅 Dias Disponíveis para Treino

O próximo passo é definir quantos dias por semana o usuário pode treinar. O plano de treino sugerido varia conforme o número de dias disponíveis:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que envolve o corpo todo em uma única sessão.
- **ABC**: Treino dividido em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Treino dividido em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A escolha do tipo de exercício preferido é essencial para personalizar ainda mais o plano de treino. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, utilizando movimentos naturais.                             |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios realizados em máquinas, com foco em isolar grupos musculares.                                       |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, que trabalham vários grupos musculares simultaneamente.   |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ideais para queima de gordura e aumento da resistência.             |

---

## 🛠️ Regras de Negócio

1. **Identifique seu biotipo corporal** conforme a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que você prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais para entender melhor o projeto e as práticas de engenharia de prompts:

- [Fundamentos de Engenharia de Prompts](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas Práticas de Prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

*(Aqui você pode detalhar o prompt exato que deve ser utilizado no projeto para gerar o treino ideal.)*
