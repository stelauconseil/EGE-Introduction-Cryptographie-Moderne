# WannaCry Nightmare Puzzle

## A. Difficulté 3/5 - Se joue à 5 participants

> En 2017, le monde a été frappé par une attaque de ransomware sans précédent appelé WannaCry, qui a infecté des centaines de milliers d'ordinateurs dans plus de 150 pays. Le ransomware était particulièrement dangereux, car il utilisait un assemblage cryptographique redoutablement efficace pour chiffrer les fichiers des victimes, rendant ainsi la récupération des données impossible sans la clé de déchiffrement correcte.

> Sauras-tu reconstruire cet assemblage ? 

## B. Pour aller plus loin

### 1. Timeline des événements relatifs au Ransomware WannaCry

* NSA discovered the vulnerability in SMB protocol
and created the EternalBlue exploit
* Shadow Brokers steals NSA tools which includes the
EternalBlue code on January 2017
* Microsoft cancels the February 2017 patch cycle for
the first time!
* Microsoft releases the patch for the SMB protocol
vulnerability on March 14, 2017
* Shadow Brokers release the vulnerability on April 14, 2017 (Exactly after one month of the patch, this suggests that there were some communications between Microsoft and Shadow Brokers)
* WannaCry spread all over the internet on May 12, 2017.
* The kill switch had been discovered and sink hold (register the domain name to stop the malware) on the same day.
* The ransom money in the three bitcoin accounts were withdrawn on August 2, 2017 (possibly to Bitcoin mixer, money laundering service)
* The US government publicly accused the North Korean government of mounting WannaCry attack on December 19, 2017
* The US Justice Department charges Park Jin Hyok, believed to be a high-profile member of the Lazarus group, of launching WannaCry attack on September 6, 2018

https://people-ece.vse.gmu.edu/coursewebpages/ECE/ECE646/F19/project/F18_presentations/Session_III/Session_III_Report_3.pdf

### 2. La "petite" histoire cryptographique

Plus important encore que l'efficacité du modèle, et d'un point de vue cryptographique, la clé privée du bi-clé asymétrique de la victime n'est pas correctement effacée sur certaines versions de Windows 😮😧😶🫣

**Bug ? Feature ? Backdoor ?** Tout est envisageable dans cette affaire.

Ce bug de Windows a permis à de nombreuses victimes de récupérer leurs fichiers chiffrés 👍

Outils de récupération de la clé privée asymétrique des postes victimes
https://github.com/aguinet/wannakey