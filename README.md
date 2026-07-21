# 👁️‍🗨️ CVDetect AI — Sistema Inteligente de Análise de Daltonismo

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Artificial Intelligence](https://img.shields.io/badge/Artificial%20Intelligence-IA-purple)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Enabled-green)
![Accessibility](https://img.shields.io/badge/Accessibility-Focused-orange)

## 📌 Sobre o projeto

O **CVDetect AI** é um sistema inteligente que irá auxiliar na **análise da deficiência de visão de cores**, conhecida popularmente como daltonismo.

O nome do projeto é baseado em:

- **CVD** (*Color Vision Deficiency*) → termo técnico utilizado para representar a deficiência de visão de cores;
- **Detect** → representa o objetivo do sistema de identificar possíveis padrões relacionados à percepção visual das cores.

A aplicação combinará conceitos de **Inteligência Artificial, automação, processamento de imagens e acessibilidade**, buscando transformar o processo tradicional de avaliação da percepção cromática em uma experiência mais interativa, automatizada e personalizada.

---

# 🔗 Origem do projeto

O CVDetect AI é uma evolução de um projeto desenvolvido anteriormente na disciplina de **Programação Orientada a Objetos (POO)** da **Universidade Federal de Minas Gerais (UFMG)**.

A primeira versão foi desenvolvida em trio e teve como objetivo criar uma aplicação em Python capaz de simular o **Teste de Ishihara**, utilizando uma interface gráfica para apresentar as lâminas do teste e realizar uma análise automatizada das respostas do usuário.

O projeto original pode ser acessado em:

🔗 [PF-TesteDaltonismo — Projeto Final POO](https://github.com/becardo/PF-TesteDaltonismo)

Nesta nova versão, o projeto está sendo remodelado com foco na integração de **Inteligência Artificial, melhoria da arquitetura do sistema e desenvolvimento de novas funcionalidades inteligentes**.

---

# 🧠 Motivação

A deficiência na visão de cores (Color Vision Deficiency – CVD), popularmente conhecida como daltonismo, é uma alteração visual que compromete a capacidade de distinguir determinadas cores, principalmente combinações envolvendo:

- vermelho e verde;
- azul e amarelo;
- diferentes tonalidades e intensidades de uma mesma cor.

Um dos métodos mais conhecidos para avaliação da percepção cromática é o Teste de Ishihara, composto por lâminas pseudoisocromáticas formadas por pontos coloridos que ocultam números ou padrões. Esse teste é amplamente utilizado para a triagem de alterações do eixo vermelho-verde, sendo eficaz principalmente na detecção de Protanopia, Protanomalia, Deuteranopia e Deuteranomalia.

Entretanto, o Teste de Ishihara apresenta algumas limitações. Além de possuir baixa sensibilidade para alterações do eixo azul-amarelo (Tritanopia e Tritanomalia), ele não permite quantificar com precisão a severidade da deficiência na visão de cores.

Para avaliações mais detalhadas, são utilizados testes como o Farnsworth D-15 e o Farnsworth-Munsell 100 Hue Test. O primeiro auxilia na identificação do tipo de deficiência cromática, enquanto o segundo possibilita uma análise quantitativa da percepção de cores, estimando a gravidade da alteração e o eixo cromático afetado. Ambos consistem na ordenação de discos coloridos pelo paciente, permitindo identificar padrões característicos de erro.

Embora esses testes sejam amplamente consolidados na prática clínica, eles utilizam um conjunto fixo de estímulos visuais. Em avaliações repetidas, essa característica pode favorecer a familiaridade do paciente com o exame e a memorização das respostas, reduzindo seu poder discriminativo e comprometendo a confiabilidade dos resultados.

Entre as soluções digitais atualmente disponíveis, destaca-se o Cambridge Colour Test, um exame computadorizado capaz de adaptar automaticamente a dificuldade das tarefas e estimar limiares de discriminação cromática com elevada precisão.

Diante desse cenário, este projeto propõe o desenvolvimento de uma plataforma inteligente para triagem da deficiência na visão de cores, utilizando Inteligência Artificial para tornar o processo mais adaptativo, personalizado e acessível. Inspirado nos princípios do Cambridge Colour Test, o sistema busca oferecer uma solução:

- mais acessível;
- automatizada;
- adaptativa;
personalizada;
interativa;
didática.

Diferentemente dos testes tradicionais, a proposta não consiste apenas em digitalizar exames existentes, mas em utilizar Inteligência Artificial para selecionar e gerar dinamicamente estímulos visuais de acordo com o desempenho do paciente ao longo da avaliação. Dessa forma, busca-se reduzir os efeitos da repetição de testes, aumentar a capacidade de diferenciação entre os diferentes tipos de deficiência na visão de cores e fornecer um prognóstico probabilístico que auxilie o profissional de saúde na tomada de decisão.

---

# 🚀 Evolução do projeto

## Versão inicial

A primeira versão do projeto consistia em uma aplicação capaz de simular o Teste de Ishihara.

Fluxo:

```
Usuário
   |
   v
Interface gráfica
   |
   v
Visualização das lâminas
   |
   v
Respostas do usuário
   |
   v
Análise automática
   |
   v
Prognóstico de possível daltonismo
```

---

## Nova versão — CVDetect AI

A nova proposta adiciona uma camada inteligente ao sistema:

```
Usuário
   |
   v
Teste de percepção visual
   |                  ^
   v                  |
Coleta de respostas   |
   |                  |
   v                  |
Processamento inteligente
   |
   v
Análise de padrões
   |
   v
Relatório personalizado
```

---

# 🤖 Inteligência Artificial aplicada

A Inteligência Artificial será integrada ao sistema como um mecanismo de apoio à realização do teste, tornando a avaliação mais dinâmica, personalizada e adaptativa.

Entre suas principais aplicações estão:

- Seleção inteligente dos próximos estímulos visuais com base no desempenho do paciente;
- Adaptação automática da dificuldade do teste ao longo da avaliação;
- Identificação de padrões de resposta compatíveis com diferentes tipos de deficiência na visão de cores;
- Estimativa probabilística do tipo e da severidade da alteração cromática;
- Geração automática de relatórios e explicações sobre os resultados obtidos.

A IA não possui o objetivo de substituir os métodos clínicos tradicionais nem o diagnóstico realizado por profissionais especializados. Seu papel é auxiliar o processo de triagem, fornecendo um prognóstico baseado na análise das respostas do paciente e contribuindo para uma avaliação mais eficiente e personalizada.

---

# ⚙️ Funcionalidades

🚧 Avaliação adaptativa com apoio de Inteligência Artificial
🚧 Estimativa probabilística do tipo e da severidade da deficiência na visão de cores
🚧 Seleção dinâmica dos estímulos visuais durante o teste
🚧 Geração automática de relatórios personalizados
🚧 Histórico de avaliações realizadas
🚧 Interface gráfica modernizada e mais acessível
🚧 Explicações didáticas sobre os resultados obtidos
🚧 Arquitetura refatorada para maior escalabilidade e manutenção

## 🚀 Roadmap

- [ ] Refatoração da arquitetura do sistema
- [ ] Nova interface gráfica
- [ ] Banco de dados para histórico de avaliações
- [ ] Geração automática de relatórios
- [ ] Módulo de IA para análise das respostas
- [ ] Sistema adaptativo de seleção de estímulos
- [ ] Estimativa probabilística do diagnóstico
- [ ] Validação do modelo utilizando dados experimentais

---

# 🛠️ Tecnologias utilizadas

## Linguagem

- Python

## Interface gráfica

- Tkinter, QT6

## Conceitos aplicados

- Programação Orientada a Objetos;
- Inteligência Artificial;
- Automação;
- Processamento de imagens;
- Desenvolvimento de soluções acessíveis.

---

# ⚠️ Aviso importante

Este projeto possui finalidade educacional e experimental.

Os resultados gerados representam uma **triagem automatizada/prognóstico inicial** e não devem ser interpretados como diagnóstico médico.

Para uma avaliação definitiva, recomenda-se consultar um profissional oftalmologista.

---

# 👩‍💻 Desenvolvimento

Desenvolvido por:

**Ana Beatriz Soares Cardoso**

Universidade Federal de Minas Gerais (UFMG)

Áreas de interesse:

- Inteligência Artificial;
- Automação;
- Desenvolvimento de sistemas;
- Tecnologia aplicada à saúde;
- Acessibilidade.

---

⭐ O CVDetect AI explora como Inteligência Artificial e desenvolvimento de software podem contribuir para criar soluções tecnológicas mais inclusivas e acessíveis.
