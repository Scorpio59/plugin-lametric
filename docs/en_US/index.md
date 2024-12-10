# LaMetric plugin

Plugin to display notifications / information on LaMetric.

# Plugin configuration

Once the plugin is installed, it is necessary to create an "indicator App" on the LaMetric site :

-   1 \. Se rendre à l'adresse : <https://developer.lametric.com>
-   2 \. Create an "INDICATOR APP" :

![lametric1](../images/lametric1.png)

-   3 \. Configure an icon, a name and select **Push** in "Typical communication" :

![lametric2](../images/lametric2.png)

-   4 \. Give a name and a description to your app and check "Private app" then click on "Save" :

![lametric3](../images/lametric3.png)

-   5 \. Publish the application then install it on your LaMetric using the mobile application.

Once the application is published, you have essential information for configuring the plugin.

![lametric4](../images/lametric4.png)

You can then create new equipment in Jeedom and fill in the requested fields :

![lametric5](../images/lametric5.png)

# Using the plugin

2 orders are automatically created when adding equipment :

-   **Message** : Allows sending of messages. The message type command contains 2 fields :
    - **Icon ID** : Corresponds to the number of the desired icon (Do not put the hash ``#``). La liste des icônes disponibles est consultable à cette adresse : <https://developer.lametric.com/icons>).
    - **Text** : Corresponds to the text you want to display.
-   **Clear** : Used to reset the display to empty ("JEEDOM" is then registered).

It is possible to send more messages in one send by separating the icons and the texts by the character : ``|``.

Here is for example a scenario sending 4 different information at once :

![lametric6](../images/lametric6.png)

## Utilisation de la commande notification

Pour la commande notification il est également possible d'ajouté un son  lorsque la notification va s'afficher. Pour cela ajoutez le nom du son de notification ou d'alarme avant de mettre le séparateur **|** avant le premier Id d'icone
La liste des sons est disponible ici, dans la partie 'sound' : <https://lametric-documentation.readthedocs.io/en/latest/reference-docs/device-notifications.html> 

De plus, il est possible de forcer l'affichage de la notification indifiniment jusqu'à que le bouton sur LaMetric soit appuyé ou que la commande **Vider notifications** soit exécutée.

Voici quelques exemples:
![lametric-notifs-exemples](../images/lametric-notifs-exemples.png)