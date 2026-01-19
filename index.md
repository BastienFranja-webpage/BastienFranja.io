---
layout: page
title: "Bastien Franja | Bioinformaticien"
description: "étudiant en Bioinformatique à l'EFREI | Analyse de données biologiques & développement d'outils informatiques"
background: "banner.png"
---

<div class="intro-section" style="background: linear-gradient(135deg, #f8f9fa 0%, #e8f5e9 100%); padding: 3rem 2rem; border-radius: 8px; margin-bottom: 3rem; border-left: 4px solid #2e7d32;">
  <h1 style="color: #1b5e20; margin-top: 0;">Bienvenue sur mon portfolio scientifique</h1>
  
  <p style="font-size: 1.2rem; line-height: 1.6; color: #2e7d32;">
    Je suis <strong style="color: #1b5e20;">Bastien Franja</strong>, étudiant en bioinformatique en analyse de données médicale et en développement d'outils informatiques pour la recherche en biologie.
  </p>
  
  <p style="font-size: 1.1rem; color: #388e3c;">
    ▶ Spécialisé en analyse NGS (RNA-Seq, scRNA-Seq) <br>
    ▶ Développement de pipeline pour le médical <br>
    ▶ Visualisation de données biologiques
  </p>
</div>

## 🔬 Projets en Bioinformatique

<div class="project-card" style="background: white; border-radius: 8px; padding: 1.5rem; margin-bottom: 1.5rem; box-shadow: 0 2px 8px rgba(46, 125, 50, 0.1); border-top: 3px solid #4caf50;">
  <h3 style="color: #1b5e20; margin-top: 0;">
    <span style="background: #e8f5e9; padding: 4px 8px; border-radius: 4px;">📊</span>
    Analyse de données single-cell RNA-Seq
  </h3>
  
  <div style="display: flex; flex-wrap: wrap; gap: 8px; margin: 1rem 0;">
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      R / Seurat
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Bioconductor
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Python / Scanpy
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      SingleCellExperiment
    </span>
  </div>
  
  <p style="color: #555; line-height: 1.6;">
    Analyse d'expression génique différentielle sur données single-cell de tissus pulmonaires. 
    Identification de nouveaux clusters cellulaires et analyse d'enrichissement fonctionnel.
  </p>
  
  <div style="margin-top: 1rem;">
    <a href="https://github.com/BastienFranja/scRNA-seq-analysis" 
       style="background: #2e7d32; color: white; padding: 8px 16px; border-radius: 4px; text-decoration: none; margin-right: 10px; display: inline-block;">
      📁 Code GitHub
    </a>
    <a href="#" 
       style="background: #4caf50; color: white; padding: 8px 16px; border-radius: 4px; text-decoration: none; margin-right: 10px; display: inline-block;">
      📄 Rapport détaillé
    </a>
  </div>
</div>

<div class="project-card" style="background: white; border-radius: 8px; padding: 1.5rem; margin-bottom: 1.5rem; box-shadow: 0 2px 8px rgba(46, 125, 50, 0.1); border-top: 3px solid #4caf50;">
  <h3 style="color: #1b5e20; margin-top: 0;">
    <span style="background: #e8f5e9; padding: 4px 8px; border-radius: 4px;">⚙️</span>
    Pipeline Snakemake pour RNA-Seq
  </h3>
  
  <div style="display: flex; flex-wrap: wrap; gap: 8px; margin: 1rem 0;">
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Snakemake
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Docker
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      FastQC / Trimmomatic
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      STAR / DESeq2
    </span>
  </div>
  
  <p style="color: #555; line-height: 1.6;">
    Pipeline reproductible pour l'analyse RNA-Seq incluant contrôle qualité, alignement, 
    quantification et analyse d'expression différentielle. Déployable localement et sur cloud.
  </p>
  
  <div style="margin-top: 1rem;">
    <a href="https://github.com/BastienFranja/rnaseq-pipeline" 
       style="background: #2e7d32; color: white; padding: 8px 16px; border-radius: 4px; text-decoration: none; margin-right: 10px; display: inline-block;">
      📁 Code GitHub
    </a>
    <a href="#" 
       style="background: #4caf50; color: white; padding: 8px 16px; border-radius: 4px; text-decoration: none; margin-right: 10px; display: inline-block;">
      🐳 Image Docker
    </a>
  </div>
</div>

<div class="project-card" style="background: white; border-radius: 8px; padding: 1.5rem; margin-bottom: 2rem; box-shadow: 0 2px 8px rgba(46, 125, 50, 0.1); border-top: 3px solid #4caf50;">
  <h3 style="color: #1b5e20; margin-top: 0;">
    <span style="background: #e8f5e9; padding: 4px 8px; border-radius: 4px;">📈</span>
    Dashboard d'analyse génomique
  </h3>
  
  <div style="display: flex; flex-wrap: wrap; gap: 8px; margin: 1rem 0;">
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Python / Dash
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Plotly
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      PostgreSQL
    </span>
    <span style="background: #f1f8e9; color: #33691e; padding: 4px 12px; border-radius: 20px; font-size: 0.9rem;">
      Heroku
    </span>
  </div>
  
  <p style="color: #555; line-height: 1.6;">
    Application web interactive pour visualiser et explorer des données génomiques. 
    Inclut heatmaps, PCA interactif et recherche d'enrichissement fonctionnel.
  </p>
  
  <div style="margin-top: 1rem;">
    <a href="https://github.com/BastienFranja/genomics-dashboard" 
       style="background: #2e7d32; color: white; padding: 8px 16px; border-radius: 4px; text-decoration: none; margin-right: 10px; display: inline-block;">
      📁 Code GitHub
    </a>
    <a href="#" 
       style="background: #4caf50; color: white; padding: 8px 16px; border-radius: 4px; text-decoration: none; display: inline-block;">
      🌐 Démo en ligne
    </a>
  </div>
</div>

## 🧬 Compétences Techniques

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; margin: 2rem 0;">
  <div style="background: white; border-radius: 8px; padding: 1.5rem; box-shadow: 0 2px 8px rgba(46, 125, 50, 0.1);">
    <h4 style="color: #1b5e20; margin-top: 0; border-bottom: 2px solid #c8e6c9; padding-bottom: 0.5rem;">
      <span style="color: #4caf50;">▸</span> Bioinformatique
    </h4>
    <ul style="color: #555; list-style: none; padding-left: 0;">
      <li style="padding: 4px 0;">• RNA-Seq / scRNA-Seq</li>
      <li style="padding: 4px 0;">• Analyse différentielle</li>
      <li style="padding: 4px 0;">• Enrichissement fonctionnel</li>
      <li style="padding: 4px 0;">• Métagénomique</li>
    </ul>
  </div>
  
  <div style="background: white; border-radius: 8px; padding: 1.5rem; box-shadow: 0 2px 8px rgba(46, 125, 50, 0.1);">
    <h4 style="color: #1b5e20; margin-top: 0; border-bottom: 2px solid #c8e6c9; padding-bottom: 0.5rem;">
      <span style="color: #4caf50;">▸</span> Programmation
    </h4>
    <ul style="color: #555; list-style: none; padding-left: 0;">
      <li style="padding: 4px 0;">• Python (Biopython, Scanpy)</li>
      <li style="padding: 4px 0;">• R (tidyverse, Bioconductor)</li>
      <li style="padding: 4px 0;">• Bash / Linux</li>
      <li style="padding: 4px 0;">• Snakemake / Nextflow</li>
    </ul>
  </div>
  
  <div style="background: white; border-radius: 8px; padding: 1.5rem; box-shadow: 0 2px 8px rgba(46, 125, 50, 0.1);">
    <h4 style="color: #1b5e20; margin-top: 0; border-bottom: 2px solid #c8e6c9; padding-bottom: 0.5rem;">
      <span style="color: #4caf50;">▸</span> Visualisation
    </h4>
    <ul style="color: #555; list-style: none; padding-left: 0;">
      <li style="padding: 4px 0;">• ggplot2 / Plotly</li>
      <li style="padding: 4px 0;">• ComplexHeatmap</li>
      <li style="padding: 4px 0;">• PCA / t-SNE / UMAP</li>
      <li style="padding: 4px 0;">• Cytoscape</li>
    </ul>
  </div>
</div>

## 📞 Contact

<div style="background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%); padding: 2rem; border-radius: 8px; margin-top: 2rem; text-align: center;">
  <h3 style="color: #1b5e20; margin-top: 0;">Travaillons ensemble</h3>
  
  <p style="color: #2e7d32; margin-bottom: 1.5rem;">
    Ouvert aux collaborations scientifiques, stages et opportunités professionnelles
  </p>
  
  <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 1.5rem;">
    <a href="mailto:bastien.franja@example.com" 
       style="background: white; color: #2e7d32; padding: 10px 20px; border-radius: 6px; text-decoration: none; border: 2px solid #4caf50; display: inline-flex; align-items: center;">
       ✉️ bastien.franja@gmail.com
    </a>
    
    <a href="https://linkedin.com/in/bastien-franja" 
       style="background: #2e7d32; color: white; padding: 10px 20px; border-radius: 6px; text-decoration: none; display: inline-flex; align-items: center;">
       🔗 LinkedIn
    </a>
    
    <a href="https://github.com/BastienFranja" 
       style="background: #4caf50; color: white; padding: 10px 20px; border-radius: 6px; text-decoration: none; display: inline-flex; align-items: center;">
       💻 GitHub
    </a>
  </div>
  
  <p style="margin-top: 1.5rem; color: #666; font-size: 0.9rem;">
    📍 Disponible pour des positions en Île-de-France ou en télétravail
  </p>
</div>

<div style="text-align: center; margin-top: 2rem; padding-top: 1rem; border-top: 1px solid #e0e0e0; color: #757575; font-size: 0.9rem;">
  <p>
    <strong>Portfolio de Bastien Franja</strong> | 
    Bioinformaticien & Développeur d'outils computationnels
  </p>
  <p style="color: #9e9e9e;">
    Dernière mise à jour : {{ site.time | date: "%d/%m/%Y" }}
  </p>
</div>
