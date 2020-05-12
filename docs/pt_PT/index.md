# Plugin LaMetric

Plugin para exibir notificações / informações sobre LaMetric.

# Configuração do plugin 

Após a instalação do plug-in, é necessário criar um "aplicativo indicador" no site LaMetric :

-   1 \. Se rendre à l'adresse : <https://developer.lametric.com>
-   2 \. Crie um "INDICATOR APP" :

![lametric1](../images/lametric1.png)

-   3 \. Configure um ícone, um nome e selecione Enviar "Comunicação típica" :

![lametric2](../images/lametric2.png)

-   4 \. Dê um nome e uma descrição ao seu aplicativo e marque "Aplicativo particular" e clique em "Salvar" :

![lametric3](../images/lametric3.png)

-   5 \. Publique o aplicativo e instale-o no seu LaMetric usando o aplicativo móvel.

Depois que o aplicativo é publicado, você tem informações essenciais para configurar o plugin.

![lametric4](../images/lametric4.png)

Você pode criar um novo equipamento no Jeedom e preencher os campos solicitados :

![lametric5](../images/lametric5.png)

# Usando o plugin 

2 pedidos são criados automaticamente ao adicionar equipamento :

-   **Mensagem** ⇒ Permite o envio de mensagens. O comando do tipo de mensagem contém 2 campos : 
    - **ID do ícone** : Correspond au numéro de l'icône souhaitée (Ne pas mettre le \# ; liste des icônes disponibles ici : <https://developer.lametric.com/icons>)
    - **Texto** : Corresponde ao texto que você deseja exibir
-   **Vazio** ⇒ Permite restaurar o display para vazio ("JEEDOM" é registrado)

É possível enviar mais mensagens em um envio, separando os ícones e os textos pelo caractere : **|**

Aqui está, por exemplo, um cenário que envia 4 informações diferentes em um único envio :

![lametric6](../images/lametric6.png)
