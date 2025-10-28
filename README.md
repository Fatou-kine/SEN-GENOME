# SENGENOME Pipeline - Variant Calling avec DeepVariant

Pipeline complet pour l'analyse de variants à partir de données WGS utilisant DeepVariant.

## 📋 Fonctionnalités

- Alignement BWA-MEM
- Prétraitement avec Samtools et Picard
- Appel de variants avec DeepVariant
- Filtrage avec BCFtools  
- Phasing avec WhatsHap
- Annotation avec ANNOVAR
- Nettoyage automatique des fichiers intermédiaires
- Reprise intelligente des analyses

## 🚀 Installation

### Prérequis
- Python 3.8+
- Docker
- BWA, Samtools, BCFtools, Picard, WhatsHap, ANNOVAR

### Installation
```bash
git clone https://github.com/Fatou-kine/SEN-GENOME
cd SEN-GENOME
pip install -r requirements.txt
