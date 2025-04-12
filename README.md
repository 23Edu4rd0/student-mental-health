# Student Mental Health Analysis  

Este projeto tem como objetivo analisar dados relacionados à saúde mental de estudantes, utilizando **SQL** e **Python**, com foco em responder perguntas específicas sobre o comportamento dos alunos em relação ao estresse, ansiedade e outros fatores psicológicos.  

---

## 📌 Sobre o Projeto  

Este projeto foi desenvolvido como parte de um estudo de caso para análise de dados no ambiente **DataCamp Datalab**. O dataset utilizado contém informações de alunos, como:  

- Estado de saúde mental (**PHQ score**)  
- Tempo de estadia (**stay**)  
- Participação em dormitório internacional (**inter_dom**)  
- Outras informações relevantes sobre os estudantes  

A análise foi feita utilizando **SQL** para manipulação e extração dos dados, com foco em:  

- Cálculo de médias dos **PHQ scores**.  
- Agrupamento por tempo de estadia (**stay**).  
- Filtros por participação em dormitório internacional (**inter_dom**).  
- Exploração de possíveis correlações entre variáveis.  

---

## 🛠️ Tecnologias Utilizadas  

- **SQL** (para consultas e análise no DataCamp Datalab)  
- **Python** (para processamento adicional)  
- **Pandas** (em etapas posteriores de análise)  
- **Jupyter Notebook** (para documentação interativa)  

---

## 🚀 Como Executar  

### Pré-requisitos  
- Ambiente **DataCamp Datalab** (ou um ambiente Python com Jupyter Notebook)  
- Git (opcional, para clonar o repositório)  

### Passos  

1. **Clone o repositório** (opcional):  
   ```bash
   git clone https://github.com/23Edu4rd0/student-mental-health.git
   cd student-mental-health
   ```

2. **Importe os dados**:  
   - Utilize o arquivo `students.csv` no DataCamp Datalab ou em um notebook Jupyter.  

3. **Execute as análises**:  
   - Abra o `notebook.ipynb` e execute as células para reproduzir as queries SQL e análises em Python.  

---

## 📂 Estrutura do Repositório  

```
student-mental-health/
│
├── dados.sql               # Script SQL para criar tabelas + importar dados
├── notebook.ipynb          # Notebook com a análise SQL e Python
├── students.csv            # Base de dados utilizada
└── README.md               # Documentação principal
```

---

## 📊 Resultados da Análise  

Através das análises realizadas, foi possível identificar:  

### Limitações e Achados
- Dados Insuficientes para Conclusões no caso de estudantes internacionais

### Tendência observada, mas não estatisticamente válida:

- A aparente "melhora" nos PHQ scores em tempos de estadia mais longos (5+ anos) não é confiável, pois a amostra é extremamente pequena (apenas 7 registros).
- Não podemos afirmar causalidade ou padrões reais nesses grupos.

### Viés na Distribuição

- Maioria dos dados concentrada em 1-4 anos de estadia (ex: 85% dos registros), enquanto grupos com 5+ anos representam menos de 5%.

### Possíveis Conclusões (com ressalvas) 

✅ Estudantes internacionais com 1-2 anos realmente apresentam PHQ scores mais altos (dados robustos).

⚠️ Qualquer afirmação sobre alunos com 5+ anos é especulativa — pode ser ruído estatístico.
