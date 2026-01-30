# 📊 Dashboard de Análise de Salários na Área de Dados

Um dashboard interativo desenvolvido com **Streamlit** para explorar e analisar dados salariais na área de tecnologia/dados.

## 🎯 Objetivo

Este projeto apresenta uma visualização interativa de dados salariais, permitindo que usuários filtrem e analisem tendências salariais por diversos critérios como ano, senioridade, tipo de contrato e tamanho da empresa.

## ✨ Principais Funcionalidades

- **Filtros Interativos**: Filtre dados por:
  - 📅 Ano
  - 📈 Nível de Senioridade
  - 📋 Tipo de Contrato
  - 🏢 Tamanho da Empresa

- **Métricas Principais (KPIs)**:
  - Salário médio anual (USD)
  - Salário máximo encontrado
  - Total de registros
  - Cargo mais frequente

- **Visualizações Gráficas**:
  - Top 10 cargos por salário médio
  - Distribuição de salários (histograma)

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Streamlit**: Framework web para criar dashboards interativos
- **Pandas**: Manipulação e análise de dados
- **Plotly**: Visualizações gráficas interativas

## 📦 Instalação

### Pré-requisitos
- Python 3.8+
- pip

### Passos

1. **Clone ou baixe este repositório**

2. **Crie um ambiente virtual** (recomendado):
```bash
python -m venv aula04
```

3. **Ative o ambiente virtual**:
   - Windows (PowerShell):
   ```bash
   .\aula04\Scripts\Activate.ps1
   ```
   - Windows (CMD):
   ```bash
   aula04\Scripts\activate.bat
   ```
   - Linux/Mac:
   ```bash
   source aula04/bin/activate
   ```

4. **Instale as dependências**:
```bash
pip install -r requirements.txt
```

## 🚀 Como Executar

Execute o comando abaixo no diretório do projeto:

```bash
streamlit run app.py
```

O dashboard será aberto automaticamente em seu navegador padrão (geralmente em `http://localhost:8501`).

## 📁 Estrutura do Projeto

```
aula04/
├── app.py                      # Aplicação principal do Streamlit
├── requirements.txt            # Dependências do projeto
├── dados-imersao-final.csv     # Dataset com os dados de salários
├── aula04/                     # Ambiente virtual Python
└── README.md                   # Este arquivo
```

## 📊 Dados

O projeto utiliza um dataset com informações salariais incluindo:
- **Salário em USD**
- **Ano**
- **Senioridade** (Junior, Pleno, Senior, etc.)
- **Cargo/Posição**
- **Tipo de Contrato** (CLT, PJ, etc.)
- **Tamanho da Empresa**

## 🎨 Interface

A aplicação possui:
- **Barra Lateral**: Controles de filtro para refinar os dados
- **Seção Principal**: Exibição de métricas gerais e gráficos interativos
- **Layout Responsivo**: Otimizado para diferentes tamanhos de tela

## 📝 Exemplos de Uso

1. Selecione o ano 2023 na barra lateral para analisar salários daquele ano
2. Filtre por "Senior" em senioridade para ver dados de profissionais experientes
3. Compare diferentes tipos de contrato para entender diferenças salariais
4. Explore o gráfico de distribuição para identificar faixas salariais comuns

## 🔄 Atualizações Futuras

- Adicionar mais tipos de gráficos (scatter plot, box plot)
- Implementar análises estatísticas mais avançadas
- Adicionar comparações por região/país
- Exportar dados filtrados em CSV

## 📝 Licença

Este projeto é fornecido como material de estudo.

## 👨‍💻 Autor

Desenvolvido como parte de um projeto educacional.

---

**Dúvidas ou sugestões?** Sinta-se à vontade para melhorar o projeto!
