# PraticaAzureML
Trabalhando com Machine Learning na Prática no Azure ML

1 - Entrar no site "https://portal.azure.com/#home"  
2 - Procurar por Azure machine learning  
3 - Clicar no botão +create  
4 - Subscription: assinatura gratuita  
5 - resource group: criar novo  
6 - Workspace details: nome=laboratorioai900, region= East Us, storage acount+key vault(chaveiro, onde vão os segredos de chaves e certificados)+Application insights+container registry= deixar do jeito que está.  
7 - Aba Review + create, clicar no botão Create.  
8 - Aguardar o processo de criação dos serviços.  
9 - Após criação clicar no botão go to resource.  
10 - Clicar no botão Launch to Studio.  
11 - Botão 3 riscos, depois botão ML automatizado.  
12 - Na nova página que apareceu clicar no botão Novo trabalho de ML automatizado.  
13 - Mudar o Nome de trabalho de ivory_book_xzj4p6zxbn para mslearn-bike-automl.  
14 - Mudar o nome do experimento Default para mslearn-bike-rental  
15 - Descrição colocar Aprendizado de máquina automatizado para previsão de aluguel de bicicletas  
16 - Em Marcas não colocar nada e botão Avançar  
17 - Selecionar o tipo de tarefa: Regressão(para prever dados numéricos contínuos)  
18 - Selecionar tipos de dados, botão criar  
19 - Definir o nome e o tipo do ativo de dados - Nome=alugueldebicicletas  
20 - Descrição = dados históricos de aluguel de bicicletas  
21 - Tipo=Tabular, botão Avançar  
22 - Fontes de dados de arquivos da web, Avançar  
23 - URL da Web= https://aka.ms/bike-rentals, avançar  
24 - Cabeçalhos de coluna= somente o primeiro arquivo tem cabeçalhos. Esperar o carregamento dos dados. Avançar.  
25 - Esquema deixar como está. Avançar.  
26 - Examinar esquema. Criar. Aguardar. Avançar.  
27 - Configuração de tarefas, coluna de destino(rentals(integer)).  
28 - Configuração adicional= desmarcar todos. Modelos permitidos=Random Forest e Light GBM.  
29 - Limites: Máximo de avaliações=3. Máximo de avaliações simultâneas=3. Máximo de nós=3. Limite de pontuação da métrica=0.085(se atingir esse valor ou menos ele termina). Tempo limite do experimento (minutos)=15. Tempo limite de iteração (minutos)=15. Habilitar encerramento antecipado. Tipo de validação=Divisaão de validação de treinamento. Avançar.  
30 - Computação. Avanço.  
31 - Enviar trabalho de treinamento. Aguardar início e o término.  
