# REPLAY — Football Tactical Analysis

**Machine Learning Engineer · EPFL AI Team**

> This repository is a personal portfolio overview of my contribution to REPLAY, a collaborative project developed within EPFL AI Team. It does not contain the team's private source code, datasets, or internal documentation.

## Overview

REPLAY is a football analysis project designed to transform player and ball tracking data into structured, interpretable tactical information.

The goal is to bridge raw tracking outputs and high-level football analysis through a modular pipeline that extracts tactical features, represents game situations in a structured form, and retrieves relevant match sequences from analytical queries.

## My Role

I contribute to REPLAY as a **Machine Learning Engineer**, focusing on the layer between raw tracking outputs and higher-level tactical analysis.

### Key Contributions

- design and implementation of tactical feature extraction;
- team-shape and spatial-organisation analysis;
- player–ball relationship features;
- zone occupancy and spatial metrics;
- structured tactical queries;
- validation and standardisation of tracking outputs;
- detection of tactical situations across temporal sequences;
- connection of detected events to timestamped match segments;
- contribution to the modular architecture of the ML pipeline.

The objective is to transform low-level player and ball coordinates into structured, interpretable information that can later support tactical search and natural-language interaction.

## Pipeline

<pre>
Computer Vision / Tracking
          ↓
Player & Ball Coordinates
          ↓
Data Validation & Standardisation
          ↓
Tactical Feature Engineering
          ↓
Structured Tactical Representation
          ↓
Query & Retrieval Layer
          ↓
Timestamped Match Situations
          ↓
Higher-Level Analysis / LLM Interface
</pre>

## Tactical Analysis

The ML layer derives interpretable football concepts from tracking data, including:

- team shape and spatial organisation;
- zone occupancy;
- player–ball relationships;
- possession and transitions;
- pressure-related situations;
- tactical events derived from temporal sequences.

The objective is to build reusable and explainable representations that can support both tactical analysis and higher-level natural-language interaction.

## Engineering Approach

The system is designed around modular components separating:

**Tracking Data → Feature Extraction → Tactical Representation → Querying → Retrieval → Analysis**

Technologies and concepts involved include:

`Python` · `Machine Learning` · `Feature Engineering` · `Data Pipelines` · `Structured Queries` · `Football Analytics`

## Current Development

Current work focuses on expanding the tactical feature layer, improving structured situation retrieval, and connecting the ML pipeline with higher-level interfaces for football analysis.

---

### Project Context

**EPFL AI Team · REPLAY**

This repository documents my personal engineering contribution to the project. Team source code, private datasets, and non-public project assets are intentionally not reproduced here.
