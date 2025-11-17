# extra-o_temporal_ndvi
Repositório associado ao projeto FAPESP 2024/13710-0, desenvolvido no âmbito do grupo MAPEAR – IGCE/UNESP Rio Claro.

Este repositório reúne scripts e documentos relacionados ao desenvolvimento de metodologias para remoção de nuvens em imagens de satélite e extração temporal de NDVI, com aplicação à Terra Indígena Apyterewa (PA).

Conteúdo do repositório

Scripts em Python e Jupyter Notebook para substituição de nuvens (Landsat-8);

Script complementar para extração temporal de NDVI no Google Earth Engine;

Relatório Final FAPESP;

Artigo enviado ao SBSR;

Documentação geral do projeto.

Extensão do processamento: Extração temporal de NDVI

Este módulo complementa o tratamento das imagens, permitindo transformar o NDVI já calculado em séries temporais organizadas para monitoramento ambiental.

Etapas:

Seleção do ponto de interesse;

Aplicação da máscara de nuvens e sombras;

Substituição de pixels mascarados;

Cálculo do NDVI por data;

Extração do valor de NDVI no ponto escolhido;

Construção do gráfico temporal NDVI × Tempo;

Exportação da tabela final (.csv).

Finalidade

Analisar a dinâmica da vegetação ao longo do tempo;

Gerar insumos para estudos ambientais e monitoramento de mudanças;

Criar séries temporais consistentes para análises comparativas.

Informações do projeto

Pesquisador Responsável: Prof. Danilo Marques de Magalhães

Bolsista: Helena Zotelli

Financiamento: FAPESP – Processo 2024/13710-0

Período: 01/10/2024 – 30/09/2025
