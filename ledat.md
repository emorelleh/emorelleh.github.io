---
layout: default
title: LEDAT
description: "Legal-Ecological Damage Assessment Tool (LEDAT) and IDPAm calculator"
permalink: /ledat/
---

<div class="academic-home">

  <aside class="academic-profile">
    <img
      class="profile-photo"
      src="{{ '/assets/images/ledat-logo.jpg' | relative_url }}"
      alt="LEDAT logo"
    >

    <h1>LEDAT®</h1>

    <p class="academic-title">
      Legal-Ecological Damage Assessment Tool
    </p>

    <address class="academic-address">
      Universitat Jaume I (UJI)<br>
      CrimiClima project<br>
      Environmental criminal law, criminology, and ecological evidence
    </address>

    <div class="academic-links">
      <a href="{{ '/ledat-app/' | relative_url }}">Launch app</a>
      <a href="https://crimiclima.uji.es" target="_blank" rel="noopener noreferrer">CrimiClima</a>
      <a href="https://doi.org/10.12688/openreseurope.24170.2" target="_blank" rel="noopener noreferrer">Reference article</a>
      <a href="{{ '/research/' | relative_url }}">Research</a>
      <a href="{{ '/publications/' | relative_url }}">Publications</a>
    </div>
  </aside>

  <div class="academic-main">

    <article class="academic-reading">

      <section id="overview">
        <h2>Overview</h2>

        <p>
          LEDAT® is a Legal-Ecological Damage Assessment Tool developed within the
          Universitat Jaume I as part of the CrimiClima project. It quantifies
          material environmental damage through the IDPAm index, producing a value
          on a 0–12 scale from a structured combination of legal and ecological
          variables together with a limited set of qualifying circumstances
          (“triggers”).
        </p>

        <p>
          The tool is designed as an academic and technical support instrument for
          environmental criminal law, criminology, and environmental assessment.
          It helps users organise case information in a systematic way and compare
          the material seriousness of environmental damage across cases.
        </p>
      </section>

      <section id="what-it-does">
        <h2>What the tool does</h2>

        <p>
          The calculator implements the LEDAT® methodology by combining four legal
          variables and six ecological variables, plus qualifying triggers, in
          order to generate the Material Environmental Damage Index (IDPAm).
        </p>

        <p>
          The result is an orientative index. It does not determine by itself
          whether a case must be classified as a criminal offence or as an
          administrative infringement. Rather, it offers a structured basis for
          assessing the material relevance of the environmental harm under analysis.
        </p>

        <ul class="reference-list">
          <li><strong>0.0 – 3.9</strong><br>Predominantly administrative.</li>
          <li><strong>4.0 – 6.9</strong><br>Grey area.</li>
          <li><strong>7.0 – 10.0</strong><br>High material relevance.</li>
          <li><strong>Above 10</strong><br>Exceptional range.</li>
        </ul>

        <p>
          These interpretative bands are indicative and non-binding. Their purpose
          is to support legal professionals, administrative authorities,
          criminologists, and environmental investigation teams in the objective
          comparison of cases before legal classification.
        </p>
      </section>

      <section id="how-to-use">
        <h2>How to use it</h2>

        <p>
          Users assign a score from 0 to 3 to each variable according to the
          descriptions integrated in the app. They then mark any applicable
          triggers. The calculator generates the IDPAm value in real time.
        </p>

        <p>
          The app also allows users to save cases, review a case history,
          compare cases visually, and export working material in a practical
          format for research or case analysis.
        </p>

        <p>
          Open the tool here:
          <a href="{{ '/ledat-app/' | relative_url }}">Launch LEDAT® / IDPAm calculator</a>.
        </p>
      </section>

      <section id="app">
        <h2>LEDAT app</h2>

        <p>
          The interactive version of the tool is embedded below for direct use
          within this page. It can also be opened separately in a standalone view.
        </p>

        <p>
          <a href="{{ '/ledat-app/' | relative_url }}">Open the app in a separate page</a>
        </p>

        <div style="margin-top:1.5rem;">
          <iframe
            src="{{ '/ledat-app/' | relative_url }}"
            title="LEDAT app"
            width="100%"
            style="min-height:1200px;border:1px solid #e5e7eb;border-radius:12px;background:#fff;"
            loading="lazy">
          </iframe>
        </div>
      </section>

      <section id="methodology">
        <h2>Methodological basis</h2>

        <p>
          LEDAT® is based on the published methodological framework on ecological
          harm and criminal thresholds developed in the context of environmental
          crime judgments and legal-ecological coding.
        </p>

        <p>
          The current web application is based on the published reference article:
        </p>

        <p>
          Morelle-Hungría, E.
          <em>Ecological harm and criminal thresholds: A pilot legal-ecological coding framework for environmental crime judgments</em>.
          <em>Open Research Europe</em>, 2026, 6:209.
          <a href="https://doi.org/10.12688/openreseurope.24170.2" target="_blank" rel="noopener noreferrer">
            https://doi.org/10.12688/openreseurope.24170.2
          </a>
        </p>

        <p>
          The method is presented as part of the CrimiClima project and linked to
          ongoing research on environmental harm, ecological evidence, criminal-law
          thresholds, and interdisciplinary environmental assessment.
        </p>
      </section>

      <section id="institutional-framework">
        <h2>Institutional framework</h2>

        <p>
          LEDAT® is presented here as a research and transfer tool connected to the
          Universitat Jaume I and the CrimiClima project. It forms part of a broader
          academic agenda at the intersection of environmental criminal law, green
          criminology, blue criminology, and ecological justice.
        </p>

        <p>
          In this sense, the calculator should be understood not only as a digital
          utility, but also as a methodological contribution to the assessment of
          material environmental damage in legal and criminological contexts.
        </p>

        <p>
          The method used by LEDAT® and the LEDAT trademark are registered in the
          name of Universitat Jaume I.
        </p>
      </section>

    </article>

    <aside class="academic-toc" aria-label="On this page">
      <p>On this page</p>

      <a href="#overview">Overview</a>
      <a href="#what-it-does">What the tool does</a>
      <a href="#how-to-use">How to use it</a>
      <a href="#app">LEDAT app</a>
      <a href="#methodology">Methodological basis</a>
      <a href="#institutional-framework">Institutional framework</a>
    </aside>

  </div>
</div>
