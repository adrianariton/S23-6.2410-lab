---
jupytext:
  formats: ipynb,markdown//md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.13.8
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

+++ {"id": "glYBmb6VwOSN", "tags": ["remove-cell"]}

# Latex Headers

 - Ensure proper support for certain latex notation
 - Code below

$$\newcommand{\ket}[1]{\left|{#1}\right\rangle}$$
$$\newcommand{\bra}[1]{\left\langle{#1}\right|}$$
$$\newcommand{\braket}[2]{\left\langle{#1}\middle|{#2}\right\rangle}$$
$$\newcommand{\adagger}[0]{\hat{a}^{\dagger}}$$
$$\newcommand{\ahat}[0]{\hat{a}}$$
$$\newcommand{\bdagger}[0]{\hat{b}^{\dagger}}$$
$$\newcommand{\bhat}[0]{\hat{b}}$$
$$\newcommand{\cdagger}[0]{\hat{c}^{\dagger}}$$
$$\newcommand{\chat}[0]{\hat{c}}$$
$$\newcommand{\ddagger}[0]{\hat{d}^{\dagger}}$$
$$\newcommand{\dhat}[0]{\hat{d}}$$
$$\newcommand{\edagger}[0]{\hat{e}^{\dagger}}$$
$$\newcommand{\ehat}[0]{\hat{e}}$$
$$\newcommand{\fdagger}[0]{\hat{f}^{\dagger}}$$
$$\newcommand{\fhat}[0]{\hat{f}}$$

+++ {"id": "bcdff4e6-8251-4c63-9061-40ac42497a11"}

# LAB -- Interference, Entanglement and Quantum-Enhanced Metrology

+++

This lab will: (1) explore the fundamental properties of quantum particles using quantum optics; (2) explore the interactions of quantum particles through interference; and (3) demonstrate how these interactions can be exploited to engineer devices for quantum-enhanced sensing. 

Specific aims are:

 0. Introduction to the quantenkoffer
 1. Understand SPDC generation of entangled photon pairs
 2. Explore interference of a photon with itself
 3. Use the properties of coincidence detection to measure the speed of light
 4. Demonstrate polarization entanglement between two photons
 5. Explore the interference of two single photons: the Hong-Ou-Mandel effect
 6. Develop a NOON state interferometer demonstrating supersensitivty to path length changes

+++

## Aim 0: Introduction to the Quantenkoffer (PRELAB)

In this lab you will be using the [Quantenkoffer](https://qutools.com/quantenkoffer_science-kit/).  This instrument will allow us to explore the properties of single- and entangled photons. 

Before the lab, please familiarize yourself with the online materials.  We will also introduce specific materials throughout each of the aims below, but it is best if you familiarize yourself with the equipment ahead of time. 

+++

## Aim 1: Understand SPDC generation of entangled photon pairs

In this exercise we will explore the spontaneous parametric down-conversion (SPDC) source of the Quantenkoffer.  

### Pre-Lab

The source is shown in {numref}`fig-t3e1-lab-spdc-source`.   A useful animation of the source and detailed description is provided on the [QuTools website](https://qutools.com/spdc-animated-source/).  

:::{figure-md} fig-t3e1-lab-spdc-source
<img src="FIGURES/T3E1-LAB-entanglement-interference/qk-spdc-source.png" alt="QK SPDC Source" class="bg-primary mb-1" width="800px">

A schematic view of the Quantenkoffer's SPDC source.
:::

Before the lab, please first watch this video demonstration of the source.

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=VNoJ-0_c6c8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### Lab Exercise

In the followign steps you will learn about the Quantenkoffer SPDC source through the detection of coincidence events.

 1. After turning the quantenkoffer on, place a periscope on each source port at the left side.  Thes bring up the underlying sources to the surface.
 2. Turn the red HeNe alignment source to full power.  You should now see a red light coming from each arm. This will be used for pre-alignment as it is following almost the same path as the single photon sources which are too weak for your eyes to detect.
 3. Now place a periscope on the two detector ports.  These send the light down to the single-photon detectors housed under the board. 
 4. 
 
Once you have completed these steps, your setup should look like that in {numref}`fig-t3e1-lab-spdc-coincidence-setup`.  
 
:::{figure-md} fig-t3e1-lab-spdc-coincidence-setup
<img src="FIGURES/T3E1-LAB-entanglement-interference/aim1-spdc-coincidence-setup.jpg" alt="QK SPDC Coincidences" class="bg-primary mb-1" width="800px">

What your setup should look like for coincidence detection of the SPDC photons.  Note that here there are between 250K to 300K single electron events in each arm with 14K coincidence events.
:::