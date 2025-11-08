# 🛒 E-commerce Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Dashboard interativo para análise completa de dados de e-commerce com foco em KPIs, comportamento de clientes e performance de vendas.

## 📊 Sobre o Projeto

Este projeto analisa mais de 100.000 pedidos reais de um e-commerce brasileiro, fornecendo insights sobre:

- 📈 Performance de vendas e tendências
- 👥 Segmentação e comportamento de clientes (RFM)
- 📦 Análise de produtos e categorias
- 🚚 Métricas de logística e entregas
- ⭐ Análise de sentimento de reviews
- 💰 Análise de métodos de pagamento

## 🎯 Objetivos

- Criar dashboards interativos profissionais
- Implementar análises avançadas de dados
- Demonstrar habilidades em ciência de dados
- Fornecer insights acionáveis de negócio

## 📂 Estrutura do Projeto

```
ecommerce-analytics-dashboard/
├── data/                   # Dados do projeto
│   ├── raw/               # Dados originais
│   ├── processed/         # Dados processados
│   └── cache/            # Cache para otimização
├── notebooks/             # Jupyter notebooks
├── src/                   # Código fonte
├── dashboard/             # Aplicação Dash
├── reports/               # Relatórios e visualizações
├── tests/                 # Testes unitários
├── config.yaml           # Configurações
└── requirements.txt      # Dependências
```

## 🚀 Instalação

### Pré-requisitos

- Python 3.9 ou superior
- Git
- Conta no Kaggle (para download do dataset)

### Passo a Passo

1. **Clone o repositório**
```bash
git clone <seu-repositorio>
cd ecommerce-analytics-dashboard
```

2. **Crie o ambiente virtual**
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

3. **Instale as dependências**
```bash
pip install -r requirements.txt
```

4. **Configure o Kaggle**
```bash
# Baixe suas credenciais em https://www.kaggle.com/account
# Coloque kaggle.json em ~/.kaggle/
```

5. **Baixe o dataset**
```bash
kaggle datasets download -d olistbr/brazilian-ecommerce -p data/raw/
cd data/raw && unzip brazilian-ecommerce.zip && cd ../..
```

## 📖 Dataset

**Brazilian E-Commerce Public Dataset by Olist**

Este dataset contém informações de 100k pedidos realizados na Olist Store entre 2016-2018.

### Tabelas disponíveis:
- `olist_orders_dataset.csv` - Informações dos pedidos
- `olist_order_items_dataset.csv` - Itens de cada pedido
- `olist_customers_dataset.csv` - Dados dos clientes
- `olist_products_dataset.csv` - Catálogo de produtos
- `olist_sellers_dataset.csv` - Informações dos vendedores
- `olist_order_payments_dataset.csv` - Pagamentos
- `olist_order_reviews_dataset.csv` - Reviews dos clientes
- `olist_geolocation_dataset.csv` - Dados geográficos

## 🛠️ Tecnologias Utilizadas

- **Python 3.9+** - Linguagem principal
- **Pandas** - Manipulação de dados
- **Plotly & Dash** - Visualizações interativas
- **Matplotlib & Seaborn** - Gráficos estáticos
- **Scikit-learn** - Análises e segmentação
- **NLTK** - Processamento de linguagem natural

## 📈 Status do Projeto

- [x] Setup inicial do projeto
- [ ] Análise exploratória dos dados
- [ ] Limpeza e processamento
- [ ] Análise RFM
- [ ] Dashboard básico
- [ ] Dashboard completo
- [ ] Deploy

## 👨‍💻 Autor

**Seu Nome**
- LinkedIn: [seu-linkedin](https://linkedin.com/in/seu-perfil)
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- Email: seu.email@example.com

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

- Dataset fornecido por Olist e Kaggle
- Comunidade Python de análise de dados

---

⭐ Se este projeto foi útil, considere dar uma estrela!
