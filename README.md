# circuit-syntesis
# SynecticsLab  
## Automated Synthesis of Equivalent Electrical Circuits for Black-Box Objects

**SynecticsLab** is a multidisciplinary initiative that unites people from different fields around a common goal: to create something fundamentally new or to solve emerging technical problems.

This repository presents a MATLAB-based prototype for the automated synthesis of an equivalent electrical circuit of a black-box object from its measured output characteristics.

The current system works with discrete signals, performs preprocessing and filtering, identifies the required response functions, and searches for a circuit model that imitates the observed electrical behavior of the object across a wide frequency range.

The synthesized circuit is intended to reproduce the characteristic impedance response of the object, including amplitude and phase behavior, while remaining physically interpretable and suitable for engineering analysis.

---

## What the current prototype already does

The implemented MATLAB prototype includes:

- generation and handling of discrete signals;
- preprocessing and filtering of measured data;
- extraction and comparison of frequency-response characteristics;
- automatic search for candidate circuit structures;
- parameter optimization for the selected structure;
- evaluation of amplitude and phase matching;
- visualization of the resulting equivalent circuit.

---

## Current scope

The current work is focused on:

- passive electrical objects;
- RLC-based equivalent circuits;
- frequency-domain identification;
- automated synthesis of topology and parameters;
- validation using simulation and bench data.

---

## What has already been completed

- MATLAB simulation pipeline;
- signal generation and processing workflow;
- filtering and response extraction;
- prototype synthesis algorithm;
- bench validation on a reference circuit;

- implementation of a physical test setup using standard RLC components;
- high-frequency excitation of the system;
- data acquisition via ADC on STM32F407 microcontroller;
- validation through comparison of measured and synthesized responses.
---

## Visual materials

The repository includes visual materials showing:

- the Simulink model;
- the signal processing and filtering workflow;
- the experimental setup;
- the synthesized circuit;
- the comparison between measured and modeled responses.

---

## Planned next steps

- completion of bench experiments;
- writing a research paper;
- public release of the project materials;
- transition of the prototype to Python;
- improvement of synthesis accuracy;
- extension to more complex classes of objects.

---

## Project purpose

The goal of this project is to develop a software-hardware tool that can automatically build an equivalent electrical model of an unknown object based on experimental output data.

The long-term direction includes applications such as:
- biological impedance modeling;
- analysis of unknown electrical and material systems;
- automated modeling of passive, active, and nonlinear objects.

---

## Author

**Mulkamanov Erik**  
GitHub/telergam: **@madjronat**
