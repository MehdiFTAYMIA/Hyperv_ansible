# Déploiement Automatisé de Machines Virtuelles sur Hyper-V avec Ansible

Ce projet permet d'automatiser le déploiement de machines virtuelles (VM) sur un hôte **Hyper-V** en utilisant **Ansible**. Le déploiement se fait à partir de templates de VHDX, ce qui permet de créer des VMs de manière rapide et reproductible.

## Prérequis

Avant d'exécuter ce projet, assurez-vous que vous disposez des éléments suivants :

- **Ansible** installé sur un serveur Ubuntu ou une machine Linux.
- Accès à un hôte **Hyper-V** (Windows Server ou Windows 10 Pro/Enterprise).
- **WinRM** configuré sur l'hôte Hyper-V pour permettre la connexion à distance avec Ansible.
- **Clé SSH** configurée pour une authentification sécurisée avec GitHub
