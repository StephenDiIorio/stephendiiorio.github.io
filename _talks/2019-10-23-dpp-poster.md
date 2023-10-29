---
title: "Modeling Collisional Ionization Using a Modified Binary-Encounter-Bethe Model in the Particle-in-Cell Code OSIRIS"
collection: talks
type: "Poster"
permalink: /talks/2019-10-23-poster-2
venue: "61<sup>st</sup> Annual meeting of the APS Division of Plasma Physics"
date: 2019-10-23
location: "Fort Lauderdale, Florida"
---

Collisions, and subsequently collisional ionization, have become necessary to a proper understanding of plasma dynamics in a variety of situations. For example, collisional ionization must be used to properly model electron bunch propagation over long distances (up to several meters or more) outside vacuum. To correctly simulate these problems, it is important to develop and implement computational models that accurately depict the complex atomic physics of these interactions. However, difficulties can arise when the atomic structure and electron configuration of an atom greatly alters the binding energy and cross sections to be used in these formulations. We have implemented a collisional ionization routine in the particle-in-cell code OSIRIS that draws on examples and advancements from other particle-in-cell codes. We use a modified binary-encounter-Bethe model to calculate atomic cross-sections along with the Monte Carlo collisional scheme in order to model inter- and intra-species collisional ionization in both relativistic and non-relativistic regimes. We present details of the implementation and results from running OSIRIS using this new collisional ionization module.
