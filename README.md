# 🚀 Aurora Siger — Relatório Operacional de Pré-Decolagem

**Projeto:** Ignition Zero — O Início da Aurora  
**Disciplina:** Atividade Integradora — Fase 1  
**Instituição:** FIAP  

---

## 📋 Descrição do Projeto

Este repositório contém o **Relatório Operacional de Pré-Decolagem** da nave Aurora Siger, desenvolvido como atividade integradora da Fase 1 do curso. O projeto simula os sistemas computacionais embarcados de uma missão espacial interplanetária, integrando:

- Análise e organização de **telemetria de voo**
- **Algoritmo de verificação** de condições de decolagem (fluxograma + pseudocódigo)
- **Script Python** funcional com todas as verificações automatizadas
- **Análise energética** da nave com cálculo de autonomia
- **Análise assistida por IA** com identificação de anomalias e riscos
- **Reflexão crítica** sobre ética, impacto social e sustentabilidade tecnológica

---

## 🗂️ Estrutura do Repositório

```
aurora-siger/
│
├── aurora_siger.ipynb     # Notebook principal com todo o código e análises
├── dados_aurora.docx      # Análise assistida por IA (tabela de telemetria + riscos)
└── README.md              # Este arquivo
```

---

## ⚙️ Como Executar o Código

### Opção 1 — Google Colab (recomendado)

1. Acesse o notebook diretamente pelo link:  
   👉 [Abrir no Google Colab](https://colab.research.google.com/github/rlcjuliaguimaraes-collab/aurora-siger/blob/rlcjuliaguimaraes-collab-patch-1/aurora_siger.ipynb)

2. Clique em **"Executar tudo"** (`Runtime > Run all`) ou rode célula por célula com `Shift + Enter`.

3. Não é necessário instalar nenhuma dependência — o notebook usa apenas bibliotecas nativas do Python.

### Opção 2 — Execução local

**Pré-requisitos:**
- Python 3.8 ou superior
- Jupyter Notebook ou JupyterLab

**Passos:**

```bash
# 1. Clone o repositório
git clone https://github.com/rlcjuliaguimaraes-collab/aurora-siger.git

# 2. Entre na pasta do projeto
cd aurora-siger

# 3. Inicie o Jupyter
jupyter notebook aurora_siger.ipynb
```

---

## 🔬 Dados de Telemetria

Os dados simulados da nave Aurora Siger utilizados no projeto:

| Parâmetro               | Valor     | Faixa Segura       | Status     |
|-------------------------|-----------|--------------------|------------|
| Temperatura interna     | 22.5 °C   | 18°C – 30°C        | ✅ Normal   |
| Temperatura externa     | -60.0 °C  | Esperado em altitude | ✅ Normal |
| Integridade estrutural  | 1         | 1 (OK)             | ✅ Normal   |
| Nível de energia        | 87.3 %    | ≥ 80%              | ⚠️ Atenção  |
| Pressão do tanque       | 350.0 kPa | 300 – 400 kPa      | ✅ Normal   |
| Módulo de propulsão     | 1         | 1 (ativo)          | ✅ Normal   |
| Módulo de comunicação   | 1         | 1 (ativo)          | ✅ Normal   |
| Módulo de navegação     | 1         | 1 (ativo)          | ✅ Normal   |

---

## 🖥️ Prints da Execução

### Verificação de decolagem
```
✅ STATUS: PRONTO PARA DECOLAR
```

### Análise energética
```
Energia disponível: 436.5 kWh
Após perdas (5%):   414.7 kWh
Reserva pós-decolagem: 294.7 kWh
```

---

## 🔋 Análise Energética — Resumo dos Cálculos

| Parâmetro                  | Valor        |
|----------------------------|--------------|
| Capacidade total da bateria | 500 kWh      |
| Carga atual                | 87.3 %       |
| Energia disponível         | 436.5 kWh    |
| Perda estimada             | 5 %          |
| Energia após perdas        | 414.7 kWh    |
| Consumo na decolagem       | 120 kWh      |
| **Reserva após decolagem** | **294.7 kWh** |

---

## 🤖 Análise Assistida por IA — Riscos Identificados

| Risco                        | Grau        | Descrição                                                              |
|------------------------------|-------------|------------------------------------------------------------------------|
| Margem energética estreita   | Baixo-Médio | Energia a 87.3%, apenas 7.3pp acima do mínimo. Monitorar continuamente. |
| Temperatura externa          | Informativo | -60°C esperado em altitude. Verificar isolamento térmico.              |
| Ausência de redundância      | Informativo | Módulos ativos sem backup registrado. Recomendar verificação de redundância. |

---

## 📚 Conexão com as Disciplinas da Fase 1

- **Computer Science:** lógica booleana, representação binária, sistemas numéricos aplicados ao algoritmo de verificação
- **Pensamento Computacional e Python:** decomposição do problema, fluxograma, pseudocódigo e automação do checklist de decolagem
- **Prompt e Inteligência Artificial:** triagem assistida por IA, classificação de dados de telemetria e identificação de anomalias
- **Energias Renováveis e Sustentáveis:** análise de autonomia energética, perdas e eficiência dos sistemas embarcados
- **Formação Social e Sustentabilidade:** reflexão sobre ética tecnológica, impacto social da exploração espacial e ESG

---

## ✍️ Autores

Projeto desenvolvido como atividade acadêmica na FIAP — Fase 1.
