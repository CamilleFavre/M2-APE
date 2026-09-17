---
layout: default
title: Advanced Microeconometrics
---

[⬅️ Retour à la liste des cours](index.html)

# Advanced Microeconometrics

## Introduction

## Advanced Microeconometrics

## General Documents

## Presentation

### 👨‍🏫 DAVID MARGOLIS PART (8 x 3 hours)
This class presents tools and themes in microeconometrics, emphasizing intuition without avoiding the math. The focus is strictly on **frequentist (not Bayesian) econometrics**.

#### 📚 Course Content & Topics
*   **Models, DGPs, and Estimation:** Loss functions, estimator properties.
*   **Quantile Regression**
*   **Specification:** Testing, cross-validation, endogeneity, unobserved heterogeneity.
*   **Panel Data Techniques:** Multi-level static panels.
*   **Count Data & Duration Models:** Alternative specifications for statistical distributions.
*   **Semi- and Non-Parametric Methods:** Kaplan-Meier, Cox partial hazards, kernel density estimation, density testing.
*   **Numerical Methods:** Integration, simulation, bootstrap, optimization algorithms, indirect inference.

> 💡 **Prerequisites:** Comfort with linear models, matrix algebra, basic limited dependent variable techniques (probit, logit), instrumental variables (IV), and simple static panel data models.

#### 📅 Tentative Schedule (Margolis)
*   **Sept 14:** DGPs, Loss Functions, Estimator properties
*   **Sept 28:** Estimator properties, Quantile regression, MV Normal, Specification testing
*   **Oct 5:** Specification testing, Endogeneity
*   **Oct 12:** Endogeneity, Unobserved heterogeneity, Single-level static panels
*   **Oct 19:** Multi-level static panels
*   **Nov 2:** Count data, Duration models
*   **Nov 9:** Duration models, Semi- and non-parametrics
*   **Nov 16:** Semi- and non-parametrics, Numerical methods
*(Note: Philipp Ketz takes over from Nov 23 to Dec 14. Attendance is taken and excessive absences are penalized).*

#### 📖 Key References
*   **Graduate texts:** Greene (*Econometric Analysis*), Cameron & Trivedi (*Microeconometrics*), Angrist & Pischke (*Mostly Harmless Econometrics*).
*   **Advanced texts:** Wooldridge (*Econometric Analysis of Cross Section and Panel Data*), Davidson & MacKinnon (*Estimation and Inference in Econometrics*).

#### 🎓 Evaluation
**1. Written Report (Max 10 pages)**
*   **Deadline:** Monday, December 7, 2026, at 6:00 PM.
*   **Rules:** Work individually or in pairs. Must use a *new* econometric approach treated in this class (no IV, D-in-D, or RD). Macro/time series topics are not eligible.
*   **Content:** Present the question, show a thorough understanding of the tools/math, test robustness, provide quantitative interpretations (marginal effects), and propose future research directions.

**2. Oral Defense (10-15 minutes)**
*   **Dates:** January 4 and January 11.
*   **Format:** Pure Q&A focused on the methods to ensure deep understanding of the written report. Both authors must answer questions if working in pairs.

---
### 👨‍🏫 Ketz PART (4 x 3 hours)
*(Details to be added)*

## Homeworks and Exams

## Homework and presentation schedule - session 2024/5

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>presentation schedule</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/12QuwTMro6e1dmnVHGWflwyeYt6kAUXBf/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/12QuwTMro6e1dmnVHGWflwyeYt6kAUXBf/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Exam 2

## Part #1

## Lecture 1 - Class 1: Introduction, Data Generating Processes, Loss Functions (Least Squares, Maximum Likelihood, Method of Moments)

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px; display: flex; justify-content: space-between; align-items: center;">
    <span>📄 <b>Class 1</b></span>
    <!-- Bouton pour afficher/masquer -->
    <button onclick="toggleNotes('doc1')" style="background: #1f6feb; color: white; border: none; padding: 5px 10px; border-radius: 4px; cursor: pointer;">📝 Notes Google Docs</button>
  </summary>
  <br>
  
  <div style="display: flex; gap: 15px; flex-wrap: wrap;">
    <!-- PARTIE GAUCHE : LE PDF (Google Drive) -->
    <div style="flex: 6; min-width: 300px;">
      <iframe src="https://drive.google.com/file/d/11kqHhTunpmfmBqy07aab0GplJV8j4guU/preview" width="100%" height="600px" style="border: 1px solid #333; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
      <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/11kqHhTunpmfmBqy07aab0GplJV8j4guU/view" target="_blank" class="btn-drive">↗️ Ouvrir le PDF en grand</a></p>
    </div>

    <!-- PARTIE DROITE : LE GOOGLE DOC (Éditable) -->
  <div id="notes-panel-doc1" style="flex: 4; min-width: 300px; display: none; flex-direction: column;">
      <h4 style="margin-top: 0; color: #58a6ff;">📝 Mes notes</h4>
      <!-- Le lien vers ton Google Doc avec l'astuce ?rm=minimal -->
      <iframe src="https://docs.google.com/document/d/1It-m5mnKkRBsbTkAgwAgCuMABNR6bryOVvG6AnBeY5M/edit?rm=minimal" width="100%" height="600px" style="border: 1px solid #333; border-radius: 5px; background: white;"></iframe>
      <!-- Un petit lien de secours au cas où -->
      <p style="text-align: center; margin-top: 15px;"><a href="https://docs.google.com/document/d/1It-m5mnKkRBsbTkAgwAgCuMABNR6bryOVvG6AnBeY5M/edit" target="_blank" style="color: #888; font-size: 0.85em;">↗️ Ouvrir le Google Doc dans un nouvel onglet</a></p>
    </div>
  </div>

  <script>
    function toggleNotes(docId) {
      var panel = document.getElementById('notes-panel-' + docId);
      if (panel.style.display === 'none') {
        panel.style.display = 'flex';
      } else {
        panel.style.display = 'none';
      }
    }
  </script>
</details>

## Lecture 2 - Class 2: Loss Functions (Method of Moments), Quantile Regression, Multivariate Normal

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 2</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1hEF1_FW33BDIteRz3Upo1MpuAg2ep8lc/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1hEF1_FW33BDIteRz3Upo1MpuAg2ep8lc/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 3 - Class 3: Specification Testing, Endogeneity, Unobserved Heterogeneity

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 3</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1iK5H-7j4FZ8O8pU26AcSfkSQ6JscaTMG/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1iK5H-7j4FZ8O8pU26AcSfkSQ6JscaTMG/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 4 - Class 4: Unobserved Heterogeneity, Single-Level Static Panels

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 4</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1OIu2n1Gc2KDij7E0D7GKW01R3Y0qHP2I/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1OIu2n1Gc2KDij7E0D7GKW01R3Y0qHP2I/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 5 - Class 5: Single-Level Static Panels (Hausman-Taylor), Multi-Level Static Panels (Nested, Non-Nested), Dynamic Panels, Count Data

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 5</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1wZ0yJuH5Ah9rcAiCgPJyi9V7JeN4bouK/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1wZ0yJuH5Ah9rcAiCgPJyi9V7JeN4bouK/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 6 - Class 6: Count Data, Duration Models

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 6</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/19sY0EVSWg10TdkcLXXEuRj68X5p96pjH/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/19sY0EVSWg10TdkcLXXEuRj68X5p96pjH/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 7 - Class 7: Duration Models (Specification, Likelihood, Inference, Competing Risks); Semi- & Non-Parametric Methods (Durations, Kernels, Komogorov-Smirnov & Log-Rank Tests)

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 7</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1Jnf-FwJ0MWOYQxXtF4hyuMlXyLeWvl_P/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1Jnf-FwJ0MWOYQxXtF4hyuMlXyLeWvl_P/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 8 - Class 8: Semi- & Non-Parametric Methods (Test Emp Dists, Smoothed Hazards, Semi- & Non-Parametric Reg), Numerical Methods (Quadrature, Monte Carlo, Bootstrap, Optim Algos, Indirect Inference)

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Class 8</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1DgfMLJIAoiNfO9X9tU4V-21YIiI1XYnK/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1DgfMLJIAoiNfO9X9tU4V-21YIiI1XYnK/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Tutorial 1 - Jaime Montana's Guide for This Class Using R

## Tutorial 2 - Sample Graded Paper

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Sample Graded Paper</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1Q35ExnYYj89N9ZQCyQTfLw-fUkBiyihg/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1Q35ExnYYj89N9ZQCyQTfLw-fUkBiyihg/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Tutorial 3 - Accessing the Master's Student Server (in French)

Graduate-level texts:
Other higher-level texts:

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Accessing the Master's Student Server - Installation and Configuration</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1YkvDKwWfrbAFaYbuMEV6yNrTRhr-x_YL/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1YkvDKwWfrbAFaYbuMEV6yNrTRhr-x_YL/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Part #2

## Lecture 1 - General introduction

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>General introduction</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1SET313CNOlh3RA1ic8RIxvakufH3O_TE/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1SET313CNOlh3RA1ic8RIxvakufH3O_TE/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Chapter 1: introduction</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/14YGpgHWIK1gxTyIgsuySQSWb1C_AFMVh/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/14YGpgHWIK1gxTyIgsuySQSWb1C_AFMVh/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Chapter 2: basic concepts</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1JtnE8tE36URmi03MayYHNYazLWOP5GLg/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1JtnE8tE36URmi03MayYHNYazLWOP5GLg/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 2 - Univariate robust statistics

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Chapter 3: univariate robust statistics</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/11gAXYC9uME2sRPjeL_h8b5X-Uc-ml9BW/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/11gAXYC9uME2sRPjeL_h8b5X-Uc-ml9BW/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 3 - Robust linear regressions

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Robust linear regressions</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1HbcEJUJ7Zs2VMP_xq0l_M_wdri2GY-D7/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1HbcEJUJ7Zs2VMP_xq0l_M_wdri2GY-D7/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 4 - Robust regressions and binary dependant variable

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Robust logistic regressions</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1yKMG7zAo0PnkHpkQujMVcRMGgajRS_-P/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1yKMG7zAo0PnkHpkQujMVcRMGgajRS_-P/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Lecture 5 - Panel data

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Robust panel regression</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1oX-yG1nlfsf0kk_qh2Qqi3W7nQQVjJ2v/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1oX-yG1nlfsf0kk_qh2Qqi3W7nQQVjJ2v/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Grouped patterns of Heterogeneity</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1Dw1CT74G1oLH_OfxZ9O7DOUW29ZreoZz/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1Dw1CT74G1oLH_OfxZ9O7DOUW29ZreoZz/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

## Tutorial 1 - illustrations

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>Roblogit package</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1tuR2fDYOEYdUu_QQaWcB2vH_oAULQI8v/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1tuR2fDYOEYdUu_QQaWcB2vH_oAULQI8v/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>rawdata</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1HDAzHizvm4kr6MG-qH5qOeIBRn59FfFi/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1HDAzHizvm4kr6MG-qH5qOeIBRn59FfFi/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>simu_xtrobreg</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/1c5vR84ZBXoDl4Y9bE4zYNljMUVgs_65e/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/1c5vR84ZBXoDl4Y9bE4zYNljMUVgs_65e/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

<details>
  <summary style="cursor: pointer; padding: 10px; background-color: #1a1a1a; border-radius: 5px; margin-bottom: 5px;">📄 <b>set of examples: command</b></summary>
  <br>
  <iframe class="pdf-viewer" src="https://drive.google.com/file/d/126YAdP3EFTOosT16AJpBpRWfnjiBTMVf/preview" width="100%" height="600px" style="border: none; border-radius: 5px;" allow="autoplay" loading="lazy"></iframe>
  <p style="text-align: center; margin-top: 15px;"><a href="https://drive.google.com/file/d/126YAdP3EFTOosT16AJpBpRWfnjiBTMVf/view" target="_blank" class="btn-drive">↗️ Ouvrir le document sur Google Drive</a></p>
</details>

---

[⬅️ Retour à la liste des cours](index.html)
