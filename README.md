# Redes_Neurais_2026_FEAP

# 🧠 Redes Neurais e IA Aplicada — FEAP

> Repositório oficial de códigos da disciplina **Redes Neurais e IA Aplicada**  
> Curso de Engenharia de Computação · 4º ao 9º Termos (2026)
> Faculdade de Engenharia e Administração Paulista (FEAP)

---

## 📌 Sobre este repositório

Este repositório centraliza todos os códigos, notebooks e exemplos práticos utilizados ao longo da disciplina. O material aqui disponível é complementar às aulas teóricas e serve como referência para estudo, revisão e experimentação.

> **Acesso restrito:** este repositório é destinado exclusivamente aos alunos regularmente matriculados na disciplina.

---

## 🎯 Objetivos da Disciplina

- Compreender os fundamentos matemáticos e computacionais das redes neurais artificiais
- Desenvolver modelos de aprendizado de máquina aplicados a problemas reais
- Implementar arquiteturas clássicas e modernas com PyTorch
- Aplicar técnicas de pré-processamento, avaliação e otimização de modelos
- Introduzir o aluno ao ecossistema de ferramentas e boas práticas em IA

---

## 🗂️ Estrutura do Repositório

```
📦 redes-neurais-ia-aplicada/
├── 📁 aula-01/          # IA Responsável e Fundamentos Biológicos
├── 📁 aula-02/          # O Perceptron e o Início do Aprendizado
├── 📁 aula-03/          # Anatomia de Sistemas de IA e PyTorch
├── 📁 aula-04/          # NLP: Da Teoria dos Embeddings à Análise de Sentimentos
├── 📁 aula-05/          # Mecanismos de Atenção, Transformers e IA Agêntica
├── 📁 aula-06/          # Anatomia da Atenção: Implementação do Scaled Dot-Product
├── 📁 aula-07/          # Do BERT ao Sabiá-3: Fine-tuning e Modelos Brasileiros
├── 📁 aula-08/          # Vision Transformers (ViT) vs. CNNs: A evolução da Visão
├── 📁 aula-09/          # Detecção de Objetos e Segmentação: Aplicações Industriais
├── 📁 aula-10/          # IA Agêntica I: De Chatbots a Agentes Autônomos (Tool Use)
├── 📁 aula-11/          # IA Agêntica II: Sistemas Multiagentes e Orquestração
├── 📁 aula-12/          # MLOps: Ciclo de Vida, Monitoramento e Drift de Modelos
├── 📁 aula-13/          # Edge AI e Otimização: Quantização e Deploy em Dispositivos
├── 📁 aula-14/          # IA Responsável: Explicabilidade (XAI) e Auditoria Ética
├── 📁 aula-15/          # Demo Day: Apresentação dos Projetos Finais de Engenharia
├── 📁 datasets/         # Conjuntos de dados (Tweets, Imagens Médicas, Logs Industriais)
├── 📁 utils/            # Helpers para visualização de atenção e métricas customizadas
└── 📄 README.md         # Guia da disciplina e requisitos de ambiente (PyTorch/Cuda)
```

> A estrutura pode ser atualizada ao longo do semestre conforme novos tópicos forem abordados.

---

## 🛠️ Tecnologias e Requisitos

| Tecnologia | Versão recomendada | Finalidade |
|---|---|---|
| Python | 3.10+ | Linguagem base |
| PyTorch | 2.x | Construção e treinamento de redes neurais |
| scikit-learn | 1.4+ | Pré-processamento, métricas e algoritmos clássicos |
| NumPy | 1.26+ | Operações numéricas |
| Matplotlib / Seaborn | — | Visualização de dados e resultados |

---

## ⚙️ Como Configurar o Ambiente

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/redes-neurais-ia-aplicada.git
cd redes-neurais-ia-aplicada
```

### 2. Crie e ative um ambiente virtual

```bash
python -m venv venv

# Linux / macOS
source venv/bin/activate

# Windows
venv\Scripts\activate
```

### 3. Instale as dependências

```bash
pip install torch torchvision scikit-learn numpy matplotlib seaborn
```

> 💡 **Dica:** para verificar se o PyTorch está reconhecendo GPU, execute:
> ```python
> import torch
> print(torch.cuda.is_available())
> ```

---

## 📚 Conteúdo Programático

| Módulo | Tópicos |
|--------|---------|
| **Fundamentos** | Neurônio artificial, Perceptron, MLP, funções de ativação |
| **Treinamento** | Backpropagation, gradiente descendente, regularização, dropout |
| **Arquiteturas** | CNN, RNN, LSTM, Autoencoders |
| **Ferramentas** | PyTorch: tensores, datasets, DataLoader, treino/avaliação |
| **Aplicações** | Classificação de imagens, séries temporais, NLP básico |
| **Boas práticas** | Avaliação de modelos, métricas, overfitting, transfer learning |

---

## 📋 Boas Práticas para os Alunos

- **Leia o código antes de executar** — entender cada linha é parte do aprendizado
- **Experimente** — altere parâmetros, adicione camadas, mude os datasets
- **Documente suas modificações** — use comentários e células markdown nos notebooks
- **Não copie apenas** — reproduza o raciocínio, não somente o resultado
- **Dúvidas?** Traga para a aula ou abra uma *Issue* no repositório

---

## 🤝 Como Contribuir (alunos)

Alunos podem sugerir melhorias, relatar erros ou propor exemplos adicionais via **Issues** no GitHub. Pull Requests serão avaliados pelo professor antes de serem incorporados.

---

## 👨‍🏫 Professor

**Fernando Gomes de Oliveira Dias Néias**  
Especialista em IA e Computação Quântica  
Faculdade de Engenharia e Arquitetura de Penápolis — FEAP

---

## 📄 Licença e Uso

O conteúdo deste repositório é de uso **exclusivo para fins educacionais** no âmbito da disciplina. A redistribuição ou publicação do material sem autorização expressa do professor não é permitida.

---

*Atualizado continuamente ao longo do semestre. Verifique regularmente por novos conteúdos.*
