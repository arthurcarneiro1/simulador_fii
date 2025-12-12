
```markdown
# 📈 Simulador de Investimentos em Fundos Imobiliários (FII) – Excel

Este repositório contém uma ferramenta criada em Excel para simulação de investimentos em Fundos Imobiliários (FIIs).  
O objetivo é fornecer ao usuário uma forma simples e intuitiva de analisar diferentes cenários de aporte, rendimento e tempo de investimento, permitindo decisões mais informadas sobre o futuro do seu patrimônio.

---

## 🧠 **Objetivo do Projeto**

Este simulador foi desenvolvido como parte de um laboratório de aprendizagem, com foco em:

- Construção de ferramentas financeiras no Excel;
- Aplicação de cálculos de rendimento mensal e dividendos;
- Criação de automações e fórmulas financeiras;
- Documentação técnica clara usando Markdown;
- Uso do GitHub como ferramenta de versionamento e compartilhamento.

---

## 📊 **Descrição da Planilha**

A planilha inclui:

### **1. Área de Configurações**
Permite definir:
- 💰 Salário mensal  
- 📈 Rendimento da carteira  
- 💡 Sugestão automática de investimento (ex.: 30% do salário)

### **2. Parâmetros da Simulação**
O usuário pode informar:
- Valor investido mensalmente  
- Tempo do investimento (anos)  
- Taxa de rendimento mensal  
- Retorno acumulado previsto

### **3. Resultado da Simulação**
A planilha calcula automaticamente:
- 🏦 Patrimônio acumulado ao final do período  
- 💵 Total investido  
- 📊 Crescimento mês a mês  
- 📥 Projeção dos dividendos mensais

---

## 🧮 **Principais Fórmulas Financeiras Utilizadas**

### **Crescimento do patrimônio**
```

FV = PMT * [((1 + i)^n - 1) / i]

```

### **Rendimento mensal**
```

Rendimento = Patrimônio acumulado anterior × taxa mensal

```

### **Dividendos estimados**
```

Dividendos = Patrimônio acumulado × taxa de dividend yield

```

---

## 🚀 **Como Utilizar**

1. Baixe o arquivo da planilha:  
   - `Simulador_Investimentos_Fundos_Imobiliarios.xlsx`

2. Abra no Excel (Windows ou Mac).

3. Preencha os campos da seção **Configurações** e **Investimento Mensal**.

4. A planilha calculará automaticamente:
   - Patrimônio final
   - Rendimento acumulado
   - Dividendos mensais estimados

5. Ajuste os parâmetros para comparar diferentes cenários de investimento.

---

## 📁 Estrutura do Repositório

```

/
│── README.md
│── Simulador_Investimentos_Fundos_Imobiliarios.xlsx


```

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel**
- Fórmulas financeiras
- Layout e organização de dashboards
- **Git & GitHub**
- Markdown para documentação

---

## 📸 Capturas de Tela (opcional)

Inclua-as na pasta `/images` e adicione aqui no README, por exemplo:

```

![Tela principal](images/tela-app.png)

```

---

## 📚 Recursos Utilizados no Desafio

- Material do laboratório
- Documentação oficial do Excel
- GitHub Docs
- Material complementar de Git e GitHub

---

## 🏁 Conclusão

Este projeto demonstra o uso de Excel como uma ferramenta poderosa para simulação de investimentos e planejamento financeiro.  
Além de aplicar conceitos de fórmulas financeiras, reforça boas práticas de documentação e uso do GitHub.

Se quiser ampliar a ferramenta, ideias incluem:
- Tabelas dinâmicas
- Gráficos automáticos
- Simulações múltiplas
- Comparação entre FIIs diferentes

---

✉️ **Se quiser, posso ajudar você a:**
- Criar imagens para a pasta `/images`  
- Melhorar ou auditar sua planilha  
- Criar versões avançadas do simulador  
- Montar automaticamente o repositório inteiro  
```

---
