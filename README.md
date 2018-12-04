# bosons-de-Higgs
Dans ce cas, nous essayons de prédire un résultat binaire. Les deux classes sont "background" et "tau tau decay of a Higgs boson". 
La première étape est d'analyser les données afin de comprendre par exemples que certains attributs sont redondants ou tout simplement d'anticiper la diffuclté d'apprentissage de modèles au vue du nombre d'attributs (trop nombreux). Il faut aussi effectuer des bases lines (random...) afin d'avoir un apperçu des résultats espérés.
Puis mettre en place des modèles sans chercher à les optimiser pour faire un premier tri entre les classifieurs opérationnels sur les données et ceux donnant des résultats en dessous de ceux de la base line.
Enfin on peut effectuer des tests sur les hpyer-paramètres des modèles sélectionnés.
Voici les résultats avec différents modèles de prédictions :
![Alt text](https://github.com/louisemarchal/bosons-de-Higgs/blob/master/res/AD_acc.png?raw=true "Accuracy en apprentissage et en test avec un arbre de décisions en fonction de la profondeur")
