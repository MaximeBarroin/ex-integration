# ex-integration
 exercice proposé par Antoine pour apprendre l'intégration continue avec github actions


Ex 1 :

Créer un repository sur github que vous nommerez : ex-intégration.

Le repository contiendra un README par défaut.

Cloner le repository

Créer 2 branches en plus de la main (dev et support)

Créer plusieurs Workflows :


	
1 Qui se déclenche à tt les push et qui lance un echo : Je fais des tests"
	
1 qui se déclenche à l'ouverture d'un pull_request de vers la main et qui fait un echo 'Je fait des test et ensuite le build"
	
1 qui se déclenche à la fermeture d'un pull_request  vers la main et qui fait un echo "Je déploi l'app"
	
Un qui se déclenche sur la branche support et qui fait deux jobs qui font 3 step que vous souhaitez chacun en récuperrant le repo au préalable.