# TP 23 : Migration de Eureka vers Consul

## Objectifs
* Comprendre la logique d’une migration de service discovery (Eureka → Consul).
* Configurer Consul pour enregistrer et découvrir des microservices.
* Conteneuriser et déployer l’ensemble avec Docker et Docker Compose.

## Prérequis
* Docker et Docker Compose installés.
* Java 11+ et Maven installés.
* Git installé.
* Un IDE (IntelliJ IDEA, Eclipse, VS Code).
* Le dépôt Git contient les projets Client, Gateway et Server_Eureka.

## Ce qui sera obtenu à la fin
* Consul exécuté localement et accessible via son interface Web.
* Les microservices démarrent et se déclarent dans Consul.
* La découverte se fait via Consul (au lieu d’Eureka).
* Une base solide pour conteneuriser le tout avec Docker Compose.

## Importation et lancement des projets (état initial : Eureka)
<img width="960" height="501" alt="Capture d&#39;écran 2026-01-11 134719" src="https://github.com/user-attachments/assets/4a519516-ad55-432b-acbc-fefa82875c8e" />
<img width="930" height="467" alt="Capture d&#39;écran 2026-01-11 135555" src="https://github.com/user-attachments/assets/2c9b399f-d5d7-4851-ad7e-a88cc4422517" />
<img width="933" height="467" alt="Capture d&#39;écran 2026-01-11 135616" src="https://github.com/user-attachments/assets/608d66e5-ba1d-49b4-bd55-37e7364b2e16" />
<img width="931" height="465" alt="Capture d&#39;écran 2026-01-11 135628" src="https://github.com/user-attachments/assets/f5a09718-b99a-4fad-90ff-fd93be3ee8f0" />
<img width="932" height="462" alt="Capture d&#39;écran 2026-01-11 135641" src="https://github.com/user-attachments/assets/896b15f2-1167-4c57-b667-a8a1bcf4c34e" />
<img width="960" height="472" alt="Capture d&#39;écran 2026-01-11 135707" src="https://github.com/user-attachments/assets/1b5085e2-52f8-4c40-9fd5-8ac21fb20f59" />

## Installation et démarrage de Consul (mode développement)
<img width="960" height="479" alt="image" src="https://github.com/user-attachments/assets/8726076c-c987-4acb-8e40-81f67a40a9e2" />
<img width="455" height="478" alt="Capture d&#39;écran 2026-01-11 140525" src="https://github.com/user-attachments/assets/bbc84b1d-d9c4-4616-9920-359008554e1b" />
<img width="864" height="457" alt="Capture d&#39;écran 2026-01-11 140601" src="https://github.com/user-attachments/assets/aef17c35-6b94-4ca2-8de3-6a0a44d36cbf" />
<img width="960" height="473" alt="Capture d&#39;écran 2026-01-11 140623" src="https://github.com/user-attachments/assets/65267799-3f4d-499d-9128-a248fc322908" />

## Migration des services : remplacer Eureka par Consul
<img width="960" height="472" alt="Capture d&#39;écran 2026-01-11 142843" src="https://github.com/user-attachments/assets/1ecf893f-8e57-4fcd-8226-b38550ecbab3" />


## Auteur
* Nom : BEN-LAGHFIRI Majeda
* Cours: Architecture Microservices : Conception, Déploiement et Orchestration
* Date : Janvier 2026
* Encadré par : Pr.Mohamed LACHGAR
