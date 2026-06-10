[Rapport-seance1md.md](https://github.com/user-attachments/files/28798967/Rapport-seance1md.md)
# Rapport de la Séance 1 - Administration Système Moderne et DevOps

## Étudiant

**Nom :** Jordan Kasidika

## Résumé : Différence entre un SysAdmin classique et un ingénieur DevOps/SRE

Un administrateur système (SysAdmin) est responsable de l'installation, de la configuration, de la maintenance et de la surveillance des serveurs et des systèmes informatiques. Son travail consiste principalement à assurer le bon fonctionnement des infrastructures informatiques et à résoudre les problèmes techniques lorsqu'ils surviennent.

À l'inverse, un ingénieur DevOps ou SRE (Site Reliability Engineer) adopte une approche orientée automatisation et collaboration. Il utilise des outils comme Git, Vagrant, Docker ou encore les pipelines CI/CD afin d'automatiser le déploiement, la configuration et la supervision des infrastructures. Son objectif est d'améliorer la rapidité des mises en production, la fiabilité des services et la disponibilité des applications tout en réduisant les interventions manuelles.

Ainsi, le SysAdmin gère principalement les systèmes, tandis que le DevOps/SRE automatise et optimise leur gestion grâce aux pratiques modernes du cloud et de l'infrastructure as code.

---

![Screenshot 2026-06-10 154648](/C:/Users/Hp/Desktop/Screenshot%202026-06-10%20154648.jpg)

# Vérification de la machine virtuelle Vagrant

## Résultat de la commande `uname -a`

```bash
Linux ubuntu-jammy 5.15.0-179-generic #189-Ubuntu SMP Tue May 5 18:20:56 UTC 2026 x86_64 x86_64 x86_64 GNU/Linux
```

## Résultat de la commande `free -h`

```bash
               total        used        free      shared  buff/cache   available
Mem:           957Mi       173Mi       222Mi       0.0Ki       561Mi       634Mi
Swap:             0B          0B          0B
```

---

## Conclusion

Au cours de cette séance pratique, j'ai appris à déployer une machine virtuelle Ubuntu 22.04 à l'aide de Vagrant et VirtualBox, à me connecter en SSH, à vérifier les informations système et les ressources matérielles, ainsi qu'à contrôler le cycle de vie de la machine virtuelle avec les commandes `vagrant up`, `vagrant halt` et `vagrant destroy`. Cette expérience m'a permis de comprendre les bases de l'automatisation de l'infrastructure et des environnements de développement modernes.
