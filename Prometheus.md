# Prometheus

/etc/prometheus/    -> contient le fichier de configuration (configmap sur le fichier de conf)
/prometheus/        -> contient la base de donnée (a externaliser dans le cadre de kub)
port 9090

Lancement : ./prometheus --config.file=prometheus.yml

Utilisation de consul pour des routes dynamiques

https://prometheus.io/docs/practices/naming/    -> explique comment nommer les métriques    (côté développeur)

https://github.com/prometheus/prometheus/wiki/Default-port-allocations -> liste des exporters


Video 5 installation manuel d'un node exporter sur un serveur à monitorer

# Grafana

/etc/grafana/grafana.ini    -> fichier de configuration grafana
grafana.db                  -> base de donnée en SQL lite positionné au même endroit que le fichier ini
port 3000 par défaut login admin/admin
-> 1er chose ajout source de donnée 


# TODO
* Installer prometheus
* Installer Grafana
* Installer un serveur avec un node exporter