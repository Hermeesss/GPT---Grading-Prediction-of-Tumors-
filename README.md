# GPT Grading-Prediction-of-Tumors

## Sobre o Projeto

O **GPT (Grading Prediction of Tumors)** é uma aplicação de desktop projetada para auxiliar na análise de imagens médicas. Utilizando um modelo de Rede Neural Convolucional, a ferramenta analisa imagens de ressonância magnética do crânio para identificar a possível presença de tumores.

O objetivo é fornecer uma análise rápida e prática, que pode ser obtida em poucos cliques, sem a necessidade de conhecimentos técnicos avançados. A aplicação funciona como um recurso de **Diagnóstico Auxiliado por Computador (CAD)**, oferecendo uma segunda opinião baseada nos padrões aprendidos pelo modelo de Inteligência Artificial.

-----

### AVISO IMPORTANTE

Esta ferramenta é um **projeto de estudo** e **não substitui um diagnóstico médico profissional**. Os resultados servem apenas como um auxílio e devem ser interpretados por um especialista. Além disso, o modelo foi treinado exclusivamente com imagens de **ressonância magnética do crânio** e não funcionará corretamente com outros tipos de imagem.

-----

### Pré-requisitos

Para garantir a melhor performance da aplicação, seu sistema deve atender aos seguintes requisitos:

  * **Sistema Operacional:** Windows 10 ou superior
  * **Processador:** Intel Core i5 (4ª geração) | AMD Ryzen 3 ou equivalente
  * **Memória RAM:** 8 GB ou mais
  * **Armazenamento:** 500 MB de espaço livre em disco

-----

## Começando

Siga as instruções abaixo para configurar e executar o projeto em seu ambiente local.

## Como Usar

A aplicação possui uma interface simples e intuitiva, dividida em duas telas principais.

### 1\. Tela Inicial

Ao iniciar a aplicação, a tela inicial será exibida.

*Substitua o placeholder acima pela captura de tela da sua aplicação.*

Clique no botão **'Iniciar'** para avançar para a tela de análise.

### 2\. Tela de Análise

Nesta tela, você encontrará três elementos principais:

*Substitua o placeholder acima pela captura de tela da sua aplicação.*

1.  **Área de Visualização:** Um espaço onde a imagem selecionada (redimensionada para 224x224 pixels) será exibida.
2.  **Botão 'Selecionar arquivo':** Abre o explorador de arquivos para que você possa escolher a imagem de ressonância magnética que deseja analisar.
3.  **Botão 'Checar':** Após carregar a imagem, clique neste botão para iniciar a análise.

### Passo a Passo para Realizar uma Análise

1.  **Inicie o software:** Execute o arquivo da aplicação.
2.  **Carregue uma imagem:**
      * Na tela de análise, clique em **'Selecionar arquivo'**.
      * Navegue até a pasta onde a imagem está salva, selecione-a e clique em **'Abrir'**.
      * A imagem escolhida aparecerá na área de visualização.
3.  **Realize a Análise:**
      * Com a imagem carregada, clique no botão **'Checar'**.
      * Aguarde o processamento. Ao final, uma janela de notificação exibirá o resultado.

### Resultados Possíveis

A análise pode retornar dois resultados:

  * **Tumor detectado:** O modelo identificou características na imagem que são consistentes com a presença de um tumor.
  * **Ausência de tumor:** O modelo não encontrou evidências suficientes para classificar a imagem como contendo um tumor.

-----
