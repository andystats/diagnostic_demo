# Understanding Diagnostic Tests: A Bayesian Approach

An interactive educational tool for teaching Bayesian methods through diagnostic testing examples, based on Gerd Gigerenzer's approach to communicating statistical risk.

## Overview

This interactive demonstration helps students understand how diagnostic tests work from a Bayesian perspective, connecting concrete medical examples to fundamental statistical concepts. The tool progresses from basic mathematical foundations through interactive exploration to real-world applications.

## Educational Structure

### Page 1: The Math Basics
- Introduction to key concepts: Prevalence, Sensitivity, Specificity
- Mathematical notation and definitions
- Predictive values (PPV and NPV)
- Interactive flip cards reveal mathematical formulas

### Page 2: Interactive Explorer
- Real-time manipulation of test characteristics
- Visual "Theater of 1000" representation
- Scaled Venn diagrams
- Immediate feedback on how parameters affect outcomes

### Page 3: A Worked Example
- Step-by-step walkthrough of Gigerenzer's classic breast cancer screening example
- Natural frequency approach for intuitive understanding
- Progressive revelation of the calculation process
- Visual reinforcement with dots and diagrams

### Page 4: Bayesian Methods Framework
- Connection between diagnostic testing and general Bayes' theorem
- Prior updating with evidence (positive and negative test results)
- Advanced concepts: sequential testing and test comparison
- Mathematical foundations for broader applications

## Key Learning Objectives

Students will understand:
- How prevalence (prior probability) dramatically affects test interpretation
- The counterintuitive nature of false positives in low-prevalence conditions
- Bayesian updating: how posterior probabilities become new priors
- The mathematical connection between diagnostic testing and general Bayesian inference
- Natural frequency representations as an intuitive communication tool

## Technical Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Interactive Visualizations**: D3.js-powered graphics and animations
- **Mathematical Rendering**: Beautiful LaTeX notation via KaTeX
- **Progressive Disclosure**: Concepts build naturally from simple to complex

## Usage in Class

This tool works well for:
- **Lecture Supplement**: Project during class to illustrate concepts
- **Student Exploration**: Individual or group investigation of parameter effects
- **Homework Assignment**: Students can experiment with different scenarios
- **Discussion Starter**: Generate questions about surprising results (low PPV despite high sensitivity/specificity)

## Based on Research

The worked example and natural frequency approach are based on:
- **Gigerenzer, G.** *Calculated Risks: How to Know When Numbers Deceive You*
- Research on effective risk communication in medical contexts
- Evidence-based approaches to teaching Bayesian reasoning

## Running the Demo

Simply open `index.html` in a web browser. No server setup required - all dependencies are loaded from CDN.

## Educational Impact

Students often find Bayesian reasoning counterintuitive initially. This tool addresses common misconceptions by:
1. Starting with concrete, relatable medical scenarios
2. Using visual representations (dots, diagrams) alongside mathematics
3. Allowing hands-on experimentation with parameters
4. Connecting specific examples to general principles
5. Emphasizing the critical role of prior probabilities

The natural frequency approach helps students develop intuition that transfers to other Bayesian applications in statistics, data science, and research methodology.