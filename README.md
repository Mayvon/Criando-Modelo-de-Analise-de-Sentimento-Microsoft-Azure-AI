
# **Guia: Análise de Sentimentos com Azure Cognitive Services a Partir de um Arquivo Local**

Este guia descreve como realizar a análise de sentimentos de um texto armazenado localmente, utilizando o Azure Cognitive Services. O texto analisado é um comentário público sobre o aplicativo **Solar Coca-Cola**, extraído da Google Play.

---

## **Passo 1: Estrutura do Projeto**

1. **Diretório de Trabalho**
   - O texto está armazenado no diretório `inputs` com o nome do arquivo `Francisco-de-Assis.txt`.

2. **Conteúdo do Arquivo**
   - O arquivo contém o seguinte texto:
     ```
     Pode melhorar muito, os produtos estão embaralhados fazendo que perca muito tempo nos pedidos. 
     O app é lento de mais, as vezes trava. 
     Se por acaso o cliente errar o pedido e finalizar, o mesmo tem até a opção de cancelar o pedido. 
     Porém não cancela e no dia seguinte o pedido chega. 
     Funciona, mas tem potencial para melhorar muito ainda.
     ```

---

## **Passo 2: Pré-requisitos**

1. **Ferramentas Necessárias**
   - Azure Subscription ativa.
   - Azure Language Studio configurado.

2. **Setup**
   - Obtenha sua **Subscription Key** e **Endpoint** no Azure Portal.

---

## **Passo 3: Configuração do Código**

1. Instale as dependências:
   ```bash
   pip install azure-ai-textanalytics
   ```

2. Configure o código Python para processar o texto armazenado em `Francisco-de-Assis.txt`.

3. Execute o script e obtenha os resultados da análise.

---

## **Passo 4: Visualização dos Resultados no Azure Language Studio**

Os resultados obtidos pelo serviço de análise de sentimentos são apresentados em gráficos e dados detalhados no Azure. 

**Exemplo de Resultado Geral**
![Análise de Sentimentos - Resultado Geral](./print-1.png)

**Exemplo de Resultado Detalhado**
![Análise de Sentimentos - Detalhe](./print-2.png)

---

## **Passo 5: Conclusão**

Este guia demonstrou como realizar a análise de sentimentos utilizando o Azure Cognitive Services para um texto local. Essa abordagem pode ser expandida para outros cenários, como análise em tempo real ou processamento de grandes volumes de texto.
