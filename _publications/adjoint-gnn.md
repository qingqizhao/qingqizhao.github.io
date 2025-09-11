---
title: "An End-to-End Differentiable, Graph Neural Network-Embedded Pore Network Model for Permeability Prediction"
short_title: "Differentiable GNN-Embedded Pore Network Model"
layout: single
collection: publications
category: manuscripts
permalink: /publication/adjoint-gnn
excerpt: "Differentiable GNN-embedded pore network model for permeability prediction.<br/><img src='/images/adjoint-pnm.png' width='320'/>"
date: 2025-09-01
venue: "Preprint · ESS Open Archive"
paperurl: "https://essopenarchive.org/users/960205/articles/1329010-an-end-to-end-differentiable-graph-neural-network-embedded-pore-network-model-for-permeability-prediction"
citation: "Qingqi Zhao, Heng Xiao. An End-to-End Differentiable, Graph Neural Network-Embedded Pore Network Model for Permeability Prediction. ESS Open Archive. September 01, 2025."
---

This paper presents a hybrid modeling framework that embeds a graph neural network (GNN) into a pore network model (PNM) for permeability prediction. By replacing analytical conductance formulas with GNN-predicted values, the model preserves physical consistency while eliminating idealized geometric assumptions. 

The end-to-end differentiable architecture, enabled by a discrete adjoint method, allows training solely from bulk permeability data without requiring pore-scale labels, achieving high accuracy, scalability, and physically interpretable feature sensitivities.

![Overview of the proposed GNN-embedded pore network model: a GNN predicts pore-throat conductances from graph features, which feed a physics-based PNM solver to compute bulk permeability. End-to-end training via a discrete adjoint enables learning from only bulk measurements while retaining physical interpretability.](/images/adjoint-pnm.png)



