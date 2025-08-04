# 🛍️ Pesquisa Automatizada de Preços - Google Shopping e Buscapé

Este projeto realiza a leitura de uma lista de produtos a partir de um arquivo Excel (`Buscas.xlsx`) e busca os respectivos preços nas plataformas **Google Shopping** e **Buscapé**, salvando os resultados em uma nova planilha Excel.

## 📌 Objetivo

Autmatizar a coleta de preços de produtos a partir de uma lista definida pelo usuário, facilitando comparações e tomada de decisão de compra.

---

## Estrutura do Projeto

- `Pesquisa_produto_web_vs00.ipynb`: Notebook principal do projeto.
- `Buscas.xlsx`: Planilha com os termos de busca fornecidos pelo usuário (produto, preço mínimo e máximo).
- `Resultado_Pesquisa.xlsx`: Arquivo gerado automaticamente contendo os preços e links encontrados para cada produto.

---

## Como Usar

1. **Preencha o arquivo `Buscas.xlsx`** com os produtos que deseja pesquisar:
   - Coloque um produto por linha.
   - Informe também o **preço mínimo** e **preço máximo** estimado para cada item, para refinar a busca.

2. **Abra o arquivo `Pesquisa_produto_web_vs00.ipynb`** em um ambiente Jupyter Notebook ou VS Code.

3. **Execute todas as células** do notebook.

4. Quando o navegador for aberto automaticamente pelo Selenium:
   - **Resolva manualmente o CAPTCHA** do Google, se solicitado.
   - Aguarde enquanto as buscas são realizadas.

5. Ao final da execução, o arquivo `Resultado_Pesquisa.xlsx` será criado com os preços coletados.

---



