# Interpretive Process Ontology

An ontology for representing the development of historical inquiry 
through interpretive processes and products.

## Overview

The Interpretive Process Ontology provides a semantic model for representing some 
of the documentable elements through which historical inquiry develops.

Rather than representing only the outcomes of interpretation, the ontology 
distinguishes different activities and epistemic products involved in historical inquiry, 
including interpretive observations, questions, evidence, hypotheses, and temporary 
interpretive conclusions.

The model is not intended to reproduce historians' cognitive processes exhaustively. 
Instead, it aims to make explicit epistemically distinguishable and documentable 
elements of historical inquiry, their provenance, and their relationships across 
multiple interpretive processes.

The ontology is based on PROV-O and specializes its core classes `prov:Agent`, `prov:Activity`, 
and `prov:Entity` to represent interpreters, interpretive processes and activities, sources 
and focal objects of inquiry, and the interpretive products that emerge throughout the inquiry.

## Motivation

Historical knowledge is not simply extracted from documentary sources. 
Sources acquire evidential relevance through processes of selection, interpretation, 
contextualization, and correlation within a specific historical inquiry.

Existing semantic models provide important concepts and mechanisms for representing historical information, 
provenance, argumentation, beliefs, and interpretive activities. The proposed ontology 
builds on these approaches while focusing specifically on the evolving development of historical inquiry.

It supports the representation of multiple interpretive processes concerning the same object, 
allowing observations, evidence, hypotheses, and temporary conclusions to be shared, reconsidered, 
or developed along different interpretive trajectories.

## Core concepts

The ontology distinguishes three main dimensions of historical inquiry:

- **Interpreter** — the agent responsible for an interpretive process.
- **Interpretive activities** — the processes, subprocesses, and activities through which historical inquiry develops.
- **Interpretive entities and products** — the objects, sources, evidence, observations, questions, hypotheses, and temporary conclusions involved in or generated through interpretation.

The main classes include:

- `at:Interpreter`
- `at:InterpretiveProcess`
- `at:InterpretiveSubprocess`
- `at:InterpretiveActivity`
- `at:FocalInterpretiveObject`
- `at:Source`
- `at:Evidence`
- `at:InterpretiveObservation`
- `at:InterpretiveQuestion`
- `at:Hypothesis`
- `at:TemporaryInterpretiveConclusion`
- `at:InterpretiveTopicOfInterest`

## Case study

The ontology is instantiated through an RDF/OWL instance graph representing multiple historical 
inquiries concerning the frescoes of the First I.R.E. Building in Padua, designed by 
Francesco Mansutti and Gino Miozzo during the post-war reconstruction of the city.

The case study represents different interpretive processes of the same focal object and 
shows how different prior knowledge, research interests, observations, questions, and evidence 
can contribute to different interpretive trajectories and temporary conclusions.

## Relationship to existing ontologies

The ontology adopts **PROV-O** as its reference framework and builds on concepts and approaches 
developed within **CIDOC CRM**, **CRMinf**, **CRMsci**, and **HiCO**.

In particular, HiCO provides an important precedent by modeling interpretation as an activity 
through `hico:InterpretationAct`. The present ontology further articulates the development of 
interpretive inquiry by distinguishing different epistemic products that may emerge throughout 
an interpretive process, such as observations, questions, evidence, hypotheses, and temporary conclusions.

The ontology is intended to complement existing semantic frameworks for cultural heritage and historical information.

## Status

This repository contains the ontology and the RDF/OWL instance graph developed as part of doctoral 
research on the semantic representation of historical interpretation.

The model is currently experimental and under development. Future work will focus on testing its 
reproducibility with multiple historians and more complex case studies, as well as evaluating 
the model through competency questions and SPARQL queries.
