---
title: "An End-to-End Differentiable, Graph Neural Network-Embedded Pore Network Model for Permeability Prediction"
collection: publications
category: manuscripts
permalink: /publication/adjoint-gnn
excerpt: "This paper presents a hybrid modeling framework that embeds a graph neural network (GNN) into a pore network model (PNM) for permeability prediction. By replacing analytical conductance formulas with GNN-predicted values, the model preserves physical consistency while eliminating idealized geometric assumptions. The end-to-end differentiable architecture, enabled by a discrete adjoint method, allows training solely from bulk permeability data without requiring pore-scale labels, achieving high accuracy, scalability, and physically interpretable feature sensitivities."
# thumbnail for the /publications/ list
teaser: "/images/adjoint-pnm.png"
# banner for the single publication page
header:
  image: "/images/adjoint-pnm.png"
  teaser: "/images/adjoint-pnm.png"
  caption: "Overview of the proposed GNN-embedded pore network model: a GNN predicts pore-throat conductances from graph features, which feed a physics-based PNM solver to compute bulk permeability. End-to-end training via a discrete adjoint enables learning from only bulk measurements while retaining physical interpretability."
  # classes: wide   # (optional) makes the banner span wider
date: 2025-09-01
venue: "Preprint · ESS Open Archive"
paperurl: "https://essopenarchive.org/users/960205/articles/1329010-an-end-to-end-differentiable-graph-neural-network-embedded-pore-network-model-for-permeability-prediction"
citation: "Qingqi Zhao, Heng Xiao. An End-to-End Differentiable, Graph Neural Network-Embedded Pore Network Model for Permeability Prediction. ESS Open Archive. September 01, 2025."
---


