# Dashboard de Compras com Python e Streamlit

Este projeto apresenta uma aplicação interativa para geração, visualização e análise de dados de compras, utilizando dados artificiais gerados via Python e visualizações desenvolvidas com **Streamlit**.

## Descrição

A proposta é simular um sistema de BI (Business Intelligence) que percorre desde a criação de um conjunto de dados até a análise de vendas com filtros e tabelas dinâmicas. O projeto pode ser usado como material de aprendizado ou base para aplicações reais em ambientes corporativos.

---

## Estrutura do Projeto

```
projeto-compras/
│
├── datasets/                     # Arquivos CSV e Excel gerados automaticamente
│   ├── compras.csv
│   ├── lojas.csv
│   └── produtos.csv
│
├── gera_dataset.py              # Geração dos dados artificiais
├── 1-visualizando_tb.py         # Visualização inicial do DataFrame
├── 2-selecionando_colunas.py    # Filtros por colunas e valores
├── 3-adicionando_linhas.py      # Adição dinâmica de novas compras
├── 4-volume_dados.py            # Análise geral de vendas e destaques
├── 5-tb_dinamica.py             # Tabela dinâmica com métricas agregadas
```

---

## Como Executar

1. **Clone o repositório ou envie os arquivos ao seu GitHub**

2. (Opcional) Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências:**
   ```bash
   pip install pandas streamlit names
   ```

4. **Gere os dados artificiais (execute uma única vez):**
   ```bash
   python gera_dataset.py
   ```

5. **Execute os arquivos desejados com Streamlit:**
   ```bash
   streamlit run 1-visualizando_tb.py
   ```

   Substitua o nome do script conforme a funcionalidade que deseja acessar.

---

## Funcionalidades

| Script                        | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `gera_dataset.py`            | Gera dados simulados de compras, lojas e produtos                        |
| `1-visualizando_tb.py`       | Exibe o dataset completo em formato de tabela                            |
| `2-selecionando_colunas.py`  | Permite selecionar colunas e filtrar os dados interativamente            |
| `3-adicionando_linhas.py`    | Adiciona novas linhas ao dataset com preenchimento via interface         |
| `4-volume_dados.py`          | Mostra KPIs gerais, loja e vendedor com maiores volumes de vendas        |
| `5-tb_dinamica.py`           | Geração de tabela dinâmica com filtros, métricas e totalizações          |

---

## Requisitos

- Python 3.7 ou superior
- Bibliotecas:
  - `pandas`
  - `streamlit`
  - `names`

---

##  Base do Projeto

Este projeto foi desenvolvido como prática das aulas do curso **"Domine a Análise de Dados: De Numpy e Pandas a Streamlit e Bancos de Dados, tudo com Python na prática!"**, ministrado pelo instrutor **Code TI** na Udemy.

---

##  Autor

Desenvolvido por **Paulo Henrique P. Cunha**  
Analista de Dados
[LinkedIn](https://www.linkedin.com/in/paulohenriquepcunha)  
[GitHub](https://github.com/paulohenriquecunha)  

---

##  Licença

Este projeto está licenciado sob a Licença MIT.
