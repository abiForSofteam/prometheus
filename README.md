# PROMETHEUS
**##Monitoring avec prometheus**

"Prometheus est devenu le fournisseur et le récepteur de métriques dominant dans l' espace Kubernetes ." De nombreuses technologies exposent déjà leurs métriques au format de données Prometheus. D'autres proposent aux exportateurs de transformer les métriques de leur interface de surveillance dans un format compatible Prometheus. Cependant, le grand nombre de technologies et de mesures rend difficile d’en tirer le meilleur parti. Les deux principaux problèmes avec lesquels les utilisateurs sont confrontés sont :

Maintenir le fonctionnement de l'infrastructure Prometheus et maintenir à jour les configurations d'alerte pour toutes les métriques à l'échelle de l'entreprise
Mettre les métriques analysées en contexte avec d'autres piliers d'observabilité, par exemple, des traces de microservices dans le pod qui exposent les métriques
Dynatrace prend désormais en charge les métriques Prometheus des pods Kubernetes, plaçant ces métriques dans le contexte plus large des microservices et des pods, et permettant des alertes améliorées avec une référence auto-adaptative de ces métriques.
