# Busca de Estabelecimentos e Serviços Especializados para Vítimas de Violência Sexual

Este projeto utiliza Ciência de Dados para mapear e analisar a rede de atendimento a vítimas de violência sexual no Brasil, cruzando a oferta de serviços com indicadores reais de criminalidade.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/otaviofabbrodata)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=otaviofabbro2@gmail.com)

---

## 📌 Contexto do Projeto

O acesso a serviços especializados de atendimento a vítimas de violência sexual no Brasil enfrenta desafios críticos de **desigualdade territorial**. Muitas vezes, a informação sobre onde buscar ajuda não está acessível ou centralizada.

Desenvolvido na intersecção entre as **Ciências Sociais** e a **Ciência de Dados**, este projeto visa:
1. **Localizar:** Criar uma ferramenta interativa para busca de estabelecimentos por UF e Município.
2. **Visualizar:** Mapear a distribuição geográfica desses serviços através de mapas de pontos e coropléticos.
3. **Analisar:** Cruzar a infraestrutura disponível com a taxa de estupro (por 100 mil mulheres) de 2024, identificando lacunas críticas de cobertura.

---

## 🚀 Principais Funcionalidades

* **Buscador Interativo:** Interface construída com `ipywidgets` para consulta rápida de endereços e serviços por localidade.
* **Mapas de Alta Resolução:** Uso da biblioteca `Altair` para visualizações geoespaciais precisas do território brasileiro.
* **Análise de Demanda vs. Oferta:** Correlação estatística entre o número de estabelecimentos e os índices de violência por estado.
* **Hierarquia da Rede:** Visualizações em *Treemaps* para entender a composição proporcional da rede de apoio (Saúde, Segurança, Assistência Social).

---

## 📊 Fontes de Dados

A análise integra duas bases de dados oficiais de alta relevância:

1.  **Infraestrutura (CNES):** Cadastro Nacional de Estabelecimentos de Saúde, via API Elastic CNES (Ministério da Saúde).
2.  **Segurança Pública (FBSP):** 19º Anuário Brasileiro de Segurança Pública (2025), fornecendo as taxas de criminalidade de 2024.

---

## 🛠️ Tecnologias e Ferramentas

O projeto foi desenvolvido em **Python**, utilizando as seguintes bibliotecas:

* **Manipulação de Dados:** `Pandas`, `NumPy`
* **Visualização Estática e Dinâmica:** `Altair`, `Plotly`, `Folium`
* **Interatividade:** `ipywidgets`
* **Geospatial:** `Geopandas` (para tratamento de GeoJSON/TopoJSON)

---

## 📂 Como executar o projeto

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```
2.  Instale as dependências necessárias:
    ```bash
    pip install pandas altair plotly folium ipywidgets geopandas
    ```
3.  Abra o arquivo `.ipynb` em seu ambiente Jupyter, VS Code ou Google Colab.

---

## 👨‍💻 Autor

**Otávio Fabbro**
*Bacharel em Ciências Sociais (FFLCH-USP) & Especialista em Ciência de Dados (ICMC-USP)*

Interessado na aplicação de dados para impacto social e políticas públicas. Sinta-se à vontade para entrar em contato para trocas de conhecimento ou oportunidades profissionais!

---
*Este projeto é parte de um esforço contínuo para masterizar ferramentas de análise e engenharia de dados (Python, SQL, Power BI) aplicadas a contextos sociais complexos.*


