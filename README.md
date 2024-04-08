**<h1>Trabalhando com Machine Learning na Prática no Azure ML</h1>**


<h3>1º Desafio de Machine Learning com a criação de modelo de previsão com pontos de extremidade configurados.</h3>
<br>
<br>

<p>Após criar a conta no portal da Azure e entrar na plataforma da Microsoft Azure, clica em <b>Criar um recurso</b>. Em <b>categorias</b> pode buscar nos itens disponíveis por Machine Learning ou pode pesquisar na barra de pesquisa, que o marketplace irá procurar.
  </p>

<br>
<br>

![image](https://github.com/Edivania88Duarte/laboratorioIA900/assets/120994730/68f56508-731e-461f-97f3-8fa12df6b167)

<br>
<br>

Basta então, clicar em <b>Azure Machine Learning</b> e clicar em <b>criar</b>

<br>
<br>


![image](https://github.com/Edivania88Duarte/laboratorioIA900/assets/120994730/f449dad2-9b2c-46e5-b3ba-02bb4e5e8654)

<br>
<br>
Inicia-se então, o preenchimento das informações como subscrição e detalhes do workspace, como nome, região, entre outras opções que já vem preenchidas automaticamente pela plataforma. Depois basta clicar em <b>Examinar + criar</b>. 
Nesse ponto a validação precisa passar, para seguir ao próximo passo que é clicar em <b>criar</b>. Geralmente leva um tempinho para processar e quando finaliza, direciona para outra página do Azure que mostra o status do deploy.
<br>
<br>  
Finalizado o processo, clica em <b>ir para o recurso</b> e em seguida em <b>Iniciar o estúdio</b>, onde será direcioando à outra página(ml.azure.com), que tem um catálogo de modelos. Clica em
<b>ML automatizado</b> e clica em <b>Novo trabalho de ML automatizado</b>. Segue as configurações já prontas do learning, na documentação. O <b>Nome do trabalho</b> é mslear-bike-automl, por utilizar uma base de dados pública.
Após preencher o novo nome do experimento e a descrição, clica em <b>avançar</b>, seleciona o tipo de tarefa como <b>regressão</b>, preenche os demais dados e na <b>escolha fonte para o ativo de dados</b>, clica em <b>De arquivos da Web</b> e clica em <b>avançar</b> para inserir a <b>URL da Web</b> sugerida
na documentação. Nesse momento, não precisa clicar em mais nada, pois a plataforma já inicia a validação automaticamente e em seguida já leva para a aba de configurações, sendo necessário mudar apenas, a <b>configuração de cabeçalhos de coluna</b> para <b>Somente o primeiro arquivo tem cabeçalhos</b>. 
  <br>
  <br>
  
  ![image](https://github.com/Edivania88Duarte/laboratorioIA900/assets/120994730/e8689d0b-b44b-412a-8b13-69e0917a7174)

  <br>
  <br>

A plataforma irá carregar as informações e então será possível cliclar em <b>avançar</b> para examinar os dados e por fim, clicar em <b>criar</b>. 
  
Após esse processo, aparecerá a mensagem de êxito no campo superior da tela, informando que o experimento foi criado com sucesso e que a atualização pode demorar alguns segundos. Em seguida, é só selecionar o nome do experimento e clicar em <b>avançar</b> para iniciar as configurações de ajuste,
que terão alguns ajustes a serem feitos, conforme a documentação. Após realizar as alterações necessárias, clica em <b>Enviar trabalho de treinamento</b> para que ele comece a executar e finalizar a validação. Geralmente leva um tempo maior para concluir esta etapa, contudo, assim que terminar, já pode clicar cima do nome da tarefa ou ir em 
<b>Tarefas(Jobs)</b> para acessá-lo e então iniciar os testes de integridade, para saber se está ok. Para testar e validar as métricas, clica em <b>modelos</b>, em seguida em <b>métricas</b>. Nesta aba, serão exibidas todas as métricas do experimento, como gráficos que comparam valor previsto com valor verdadeiro, entre outras informações relevantes
para avaliação do cenário. 
Na opçao <b>ponto de extremidade</b> seleciona o nome experimento e clica em <b>testar</b> para inserir o código JSON que se encontra na documentação e então findar o teste, obtendo o resultado da validação.

<br>
<br> 

![image](https://github.com/Edivania88Duarte/laboratorioIA900/assets/120994730/a4199481-f25b-4b66-8733-150baa052d69)

<br>

<h3>Links Importantes:</h3>
<h4>Explore Azure AI Services</h4>
[https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html
](url)
<br>
<h4>Explore Automated Machine Learning in Azure Machine Learning</h4>
[https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html
](url)
 
