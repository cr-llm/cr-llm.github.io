---
layout: default
title: Home
---

# Causality and Large Language Models: Opportunities to Advance Causal Reasoning

A Dagstuhl Seminar exploring the intersection of causal reasoning and large language models.

Website: [https://www.dagstuhl.de/seminars/seminar-calendar/seminar-details/26152](https://www.dagstuhl.de/seminars/seminar-calendar/seminar-details/26152)

<div class="key-info">
  <div class="info-item"><strong>Dates:</strong> April 7-10, 2026</div>
  <div class="info-item"><strong>Location:</strong> Schloss Dagstuhl, Wadern, Germany</div>
  <div class="info-item"><strong>Format:</strong> In-person</div>
</div>

## Overview

In addition to code and language reasoning, recent work shows that large language models (LLMs) can achieve promising results on causal reasoning tasks, e.g. in determining cause-effect relationships. This points to a new paradigm for addressing real-world causal tasks by integrating LLMs in the causal inference workflow, but also raises fundamental questions on causal reasoning capabilities of LLMs. That is, given that LLMs are trained on observational data, do LLMs’ capabilities correspond to causal reasoning or are simply a result of dataset memorization; and how reliable are the reasoning outputs? And if not, how can we use causal techniques to improve LLMs’ reasoning capabilities?

To address these questions, this Dagstuhl Seminar would bring together experts from causal machine learning and language models to foster collaboration and identify the key research questions at the intersection of the fields. Specifically, we will focus on two objectives: 1) How to use LLMs’ world knowledge to assist causal inference workflows; 2) How to use causal principles to improve reasoning of LLMs. Recent work provides motivating evidence for both challenges, but a critical question is how to marry the flexibility and unreliability of LLMs with the rigor of causal reasoning algorithms. We hope that solving these challenges will help in wider adoption of causal reasoning and in turn, ensure reliable answers from AI systems.

### Primary Focus Areas

#### 1. Integrating LLMs into Causal ML Workflows
A longstanding problem in causal ML is how to obtain domain knowledge to guide formal specification (e.g., a causal graph) and estimate quantities of interest. For example, in effect inference, obtaining the underlying causal graph or determining special identifying variables (such as instrumental variables) is a key step before applying causal inference techniques in practice. Moreover, in unstructured data settings such as text or image, extracting the key factors that characterize high-level causal relationships is an important representation learning problem. Recent work shows that LLMs can help with providing such domain knowledge. The first part of the seminar will discuss how LLMs may be incorporated in causal ML algorithms for the four key tasks: effect inference, representation learning, causal discovery, and causal attribution.

#### 2. Evaluating and Improving LLM Causal Reasoning
For language models, a key challenge is to improve their reasoning and reliability, including causal reasoning. Recent work shows that incorporating causality, either through providing training data based on causal principles or combining causal tools with LLM generation, can lead to improvement in reasoning capabilities and avoid hallucinations. Thus, an important direction is to develop methods for evaluating causal reasoning and build training algorithms that can significantly improve the reasoning reliability of LLMs. We will discuss the following topics: evaluating (causal) reasoning of LLMs, training algorithms for improving causal reasoning, verification of causal statements from LLMs, and how causal reasoning may improve reliability of LLMs broadly.

## Organizers

<style>
.organizers-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.organizer-card {
  text-align: center;
  padding: 20px 10px;
}

.organizer-photo {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin: 0 auto 15px;
  display: block;
  border: 3px solid #e0e0e0;
}

.organizer-name {
  font-weight: bold;
  font-size: 1.1em;
  margin-bottom: 8px;
}

.organizer-name a {
  color: #2c5aa0;
  text-decoration: none;
}

.organizer-name a:hover {
  text-decoration: underline;
}

.organizer-affiliation {
  font-size: 0.9em;
  color: #666;
  line-height: 1.4;
}
</style>

<div class="organizers-grid">

<div class="organizer-card">
  <img src="https://amitsharma.in/assets/img/prof_pic.jpg" alt="Amit Sharma" class="organizer-photo">
  <div class="organizer-name"><a href="https://amitsharma.in/">Amit Sharma</a></div>
  <div class="organizer-affiliation">Microsoft Research India – Bangalore</div>
</div>

<div class="organizer-card">
  <img src="https://janzing.github.io/dj.jpeg" alt="Dominik Janzing" class="organizer-photo">
  <div class="organizer-name"><a href="https://janzing.github.io/">Dominik Janzing</a></div>
  <div class="organizer-affiliation">Amazon Web Services – Tübingen</div>
</div>

<div class="organizer-card">
  <img src="https://www.andrew.cmu.edu/user/kunz1/images/team/kun-zhang1.jpg" alt="Kun Zhang" class="organizer-photo">
  <div class="organizer-name"><a href="https://www.andrew.cmu.edu/user/kunz1/">Kun Zhang</a></div>
  <div class="organizer-affiliation">Carnegie Mellon University – Pittsburgh</div>
</div>

<div class="organizer-card">
  <img src="https://zhijing-jin.com/home/wp-content/uploads/2025/03/profile_grey.png" alt="Zhijing Jin" class="organizer-photo">
  <div class="organizer-name"><a href="https://zhijing-jin.com">Zhijing Jin</a></div>
  <div class="organizer-affiliation">MPI für Intelligente Systeme – Tübingen & University of Toronto</div>
</div>

</div>
