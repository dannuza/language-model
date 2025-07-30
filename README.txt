- IA Generativa Azure AI Foundry - Modelo de Linguagem

Neste projeto, serão implantados dois modelos de linguagens no portal do Azure AI Foundry.

Será criado:

1. Modelo gpt-4o
2. Modelo Phi-4-mini-instruct

- Como usar: Passo a passo

1. Acesse o Portal do Azure AI Foundry
   [https://ai.azure.com]

2. Escolhendo um modelo para iniciar um projeto
   Serão usados os modelos gpt-4o e Phi-4-mini-instruct
   Em catálogo de modelos, selecione "comparar modelos"
   No ícone "Limpar todos os modelos", remova todos os modelos pré-relacionados
   Em "+Modelo para comparar"adicione os modelos citados acima
   Será gerado um gráfico comparando os modelos com base no Índice de Qualidade e no Custo
   
3. Criando um projeto do Azure AI Foundry para usar o modelo
   Na página inicial do Azure AI Foundry, busque por "gpt-4o"e selecione
   Clique em "Usar esse modelo"
   Preencha: Projeto e revise as opções avançadas 
   Clique em "Criar"

4. Criando bate-papo com modelo gpt-4o
   No painel Configuração, confirme o modelo
   Em "Forneça as instruções e contexto do modelo", defina o prompt do sistema, defina o modelo. Ex: Voce é uma calculadora
   Clique em "Aplicar alterações"
   Na janela de bate-papo, digite uma informação ou pergunta referente a definição do modelo.
   O modelo te dará uma resposta
  
5. Criando o outro modelo
   Na barra lateral esquerda, na seção "Meus ativos, selecione Modelos + endpoints
   Vá até "+Implantar modelo"e escolha "Implantar modelo base" e pesquise por phi-4-mini-instruct
   Implante o modelo
   
6. Criando bate-papo com modelo Phi-4
   No painel Configuração, confirme o modelo
   Na caixa de bate-papo fornece a primeira msg

7. Realize comparação adicional nos modelos gerados
   

- Tecnologias Usadas

 1. Microsoft Azure - (https://azure.microsoft.com/)
 2. Azure AI Foundry - (https://ai.azure.com/)
 3. ARM Templates - (https://learn.microsoft.com/azure/azure-resource-manager/templates/overview)
 4. Markdown para documentação

- Autor
  Dannuza Martins Cardoso Silva
 
 


