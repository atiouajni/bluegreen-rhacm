| Category | Niveau | Preparation time | Demo time
|--|--|--| --| 
| Demo | :star::star: :star: :star: :star: | 5 min| 15 min| 

# Deep dive Documentation

# Scenario

**1 - Start with "Observe Environment > Overview"**

    Pitch : 
     - debute sur du datacenter et ajoute du cloud
     - Profiter des avantages d'avoir du multi cloud.
     - Eviter les gros cluster et avoir une stratégie plusieurs petits clusters
     -> RHACM va répondre à ces questions : Comment gérer la complexité de provision de ces clusters, le cycle de vie de ces clusters comme l'upgrade.
     Dans cette vue, on a une vue globale et coherente de tous les clusters existants

**2 - On rentre dans le détails "Automate Infrastructure > Clusters"**

    Pitch :
     - version
     - vendors
     - upgrade
     - Create a cluster > YAML:ON (Openshift Hive)
     - Import cluster

> TAKE AWAY : Gestion du cycle de vie multi-cluster-> Create, import & upgrade

**3 - Maintenant que j'ai mes clusters rentrons dans le détails de ce que j'ai > "recherche"**

    Pitch :
     - Navigation dans IHM (Thanos)
     - Kind:Pod label:app=bluegreen 
     - delete Pod
     - sauvegarder la recherche

**4 - La recherche peut se faire en ligne de commande > Web Terminal**

    Pitch :
     - recherche par mot clés sur tous les clusters
     - oc get pods -n open-cluster-management > logs & terminal

> TAKE AWAY : multi-cluster Observability 

**5 - Day 2 configuration et management - conformité du cluster**

Comment je peux apporter de la consistence et de la gouvernance dans tous mes clusters ?

    Pitch :
    - overview page Govern risk
    - Categories/standard
    - Policy -> inform/enforce  - musthave mustnothave
    - Parler de Open Policy Agent (OPA)

> TAKE AWAY :  Faciliter la mise en conformité

**6 - Application lifecycle > "Manage Applications"**



> TAKE AWAY : Faciliter la gestion et améliorer la disponibilité des applications


FINAL : 
Gérer l'environnement de façon centralisée et automatique
Faciliter la mise en conformité
Améliorer la disponibilité des applications
Réduire les coûts d'exploitation

