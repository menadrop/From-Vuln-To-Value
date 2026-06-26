# from-vuln-to-value

> de la vulnérabilité technique à la valeur business : la simulation complète d'un cycle d'avant-vente sécurité, de la découverte du besoin client à la proposition chiffrée et conforme.

![Status](https://img.shields.io/badge/statut-en%20cours-yellow)
![Type](https://img.shields.io/badge/type-projet%20p%C3%A9dagogique-blue)
![Scope](https://img.shields.io/badge/scope-GRC%20%2B%20technique%20%2B%20avant--vente-purple)
![ISO 27001](https://img.shields.io/badge/r%C3%A9f%C3%A9rentiel-ISO%2027001-informational)
![EBIOS RM](https://img.shields.io/badge/m%C3%A9thode-EBIOS%20RM-informational)
![RGPD](https://img.shields.io/badge/conformit%C3%A9-RGPD-success)
![Made with](https://img.shields.io/badge/made%20with-Python%20%7C%20Markdown-lightgrey)

> [!IMPORTANT]
> projet pédagogique. l'entreprise cliente, son système d'information et toutes les données présentées sont entièrement fictifs. aucun système réel n'a été audité sans autorisation. ce dépôt sert à démontrer une méthode et un savoir-faire, pas à documenter une mission réelle.

---

## pourquoi ce projet

la plupart des portfolios cybersécurité montrent des fragments isolés : un write-up de CTF, une analyse de risque, une politique de sécurité. aucun ne raconte la chaîne complète où une faille technique devient un argument de vente chiffré et conforme.

c'est précisément ce que fait l'ingénieur avant-vente sécurité, et c'est ce que je démontre ici de bout en bout.

je relie trois compétences que l'on trouve rarement réunies dans un même profil junior :

* la **profondeur technique** : je trouve et je prouve les vulnérabilités.
* la **maîtrise GRC** : je rattache chaque risque à un référentiel (ISO 27001, NIS2, EBIOS RM).
* la **fluidité commerciale** : je traduis le risque technique en impact business et en proposition vendable.

## le scénario

je joue le rôle de l'ingénieur avant-vente d'un cabinet de cybersécurité fictif. une PME me consulte pour sécuriser son système d'information. ce dépôt documente toute la chaîne, de la découverte du besoin jusqu'à la proposition remise au comité de direction.

| élément | valeur |
|---|---|
| client fictif | Lumio |
| secteur | e-commerce et marketing digital (vente en ligne B2C) |
| cadre réglementaire applicable | RGPD, ISO 27001, PCI DSS |
| mon rôle | ingénieur avant-vente sécurité |

## l'arc complet

je structure le dépôt comme une vraie mission, module par module.

### 01 - contexte client
fiche d'identité de la PME : secteur, taille, système d'information, enjeux business, contraintes réglementaires. je pose le terrain et le modèle de menace de départ.

### 02 - découverte
compte rendu de l'atelier de cadrage : besoins exprimés, actifs critiques, ébauche de modèle de menace selon la méthode EBIOS Risk Manager. je démontre l'écoute client et la rigueur méthodologique.

### 03 - preuve technique
audit mené sur un lab que je monte moi-même. rapport de findings : vulnérabilités identifiées, preuves, criticité notée en CVSS. c'est ici que s'exprime ma compétence technique.

### 04 - traduction business
mon geste signature. chaque vulnérabilité technique devient un risque business : impact financier estimé, exigence normative violée, probabilité. un tableau qui parle au dirigeant, pas à l'ingénieur.

### 05 - proposition commerciale
le livrable de vente : plan de remédiation priorisé, phasage, chiffrage, ROI sécurité, et une note de synthèse d'une page pour le comité de direction.

### 06 - soutenance
le support de présentation qui synthétise la mission, comme un vrai pitch d'avant-vente.

## structure du dépôt

```
from-vuln-to-value/
├── README.md
├── 01-contexte-client/
├── 02-decouverte/
├── 03-preuve-technique/
├── 04-traduction-business/
├── 05-proposition-commerciale/
└── 06-soutenance/
```

## stack et référentiels

* **technique** : lab de test, outils d'audit, scoring CVSS
* **méthode** : EBIOS Risk Manager (ANSSI)
* **référentiels** : RGPD, ISO 27001 (annexe A), PCI DSS
* **outils** : Python pour l'automatisation de la matrice de risque, Markdown pour les livrables

## avancement

* [x] cadrage du projet
* [ ] 01 - contexte client
* [ ] 02 - découverte
* [ ] 03 - preuve technique
* [ ] 04 - traduction business
* [ ] 05 - proposition commerciale
* [ ] 06 - soutenance

## à propos

Ce projet incarne mon différenciateur : faire le pont entre la réalité technique d'une faille et sa traduction en enjeu business.

GitHub : [menadrop](https://github.com/menadrop)
