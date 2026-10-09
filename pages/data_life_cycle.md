---
title: Research Data Life Cycle
description: Seven RDMkit lifecycle stages with Storage and Management considered throughout biomedical research.
permalink: /data_life_cycle
redirect_from:
  - /data-life-cycle
  - /data-life-cycle/
sidebar: data_management
search_exclude: false
---

<div class="kb-cycle">

<p class="kb-cycle__lead">Explore the seven research data life cycle stages — <strong>Plan, Collect, Process, Analyse, Preserve, Share and Reuse</strong> — with <strong>Storage &amp; Management</strong> at the centre of every stage.</p>

<p class="kb-cycle__intro">The stages follow the <a href="https://rdmkit.elixir-europe.org/data_life_cycle">RDMkit research data lifecycle</a>. The cross-cutting storage concept draws on <a href="https://datamanagement.hms.harvard.edu/plan-design/biomedical-data-lifecycle">Harvard Medical School's Biomedical Data Lifecycle</a>. This version translates the combined approach into introductory guidance for clinical, epidemiological and public health research.</p>

<div class="kb-cycle__draft" role="note"><strong>Content under development:</strong> This NFDI4Health-oriented overview is intended for data steward review. Some linked detailed pages still contain inherited RDMkit guidance and are being adapted to biomedical research contexts.</div>

<section class="kb-cycle__explorer" id="lifecycle-diagram" aria-labelledby="diagram-heading">
 <div class="kb-cycle__explorer-intro">
  <p class="kb-cycle__eyebrow">INTERACTIVE LIFECYCLE</p>
  <h2 id="diagram-heading">Seven stages, one continuous storage responsibility</h2>
  <p>Click a coloured stage to jump to its activities and stage-specific storage considerations. Click the centre to explore storage responsibilities shared across all seven stages.</p>
 </div>
 <div class="kb-cycle__visual-grid">
  <figure class="kb-cycle__figure">
  <svg class="kb-cycle__svg kb-cycle__svg--photo" viewBox="0 0 1254 1254" xmlns="http://www.w3.org/2000/svg" role="group" aria-labelledby="kb-cycle-svg-title kb-cycle-svg-desc">
  <title id="kb-cycle-svg-title">Research data lifecycle: Plan, Collect, Process, Analyse, Preserve, Share, Reuse and Storage Management</title>
  <desc id="kb-cycle-svg-desc">Illustrated seven-stage lifecycle with clickable segments. Choose a stage to jump to its detailed guidance. Choose the centre for storage across all stages. Matching accessible text links are provided to the right and below.</desc>
  <image href="{{ '/assets/img/lifecycle/rdmkit-storage-lifecycle.png' | relative_url }}" x="0" y="0" width="1254" height="1254" preserveAspectRatio="xMidYMid meet"/>
  <a href="#stage-plan" class="kb-cycle__image-hotspot" aria-label="Plan: jump to Plan guidance"><title>Plan: jump to guidance</title><path d="M 651.78 57.54 A 568 568 0 0 1 1067.97 267.0 L 853.7 440.96 A 292 292 0 0 0 639.74 333.28 Z"/></a>
<a href="#stage-collect" class="kb-cycle__image-hotspot" aria-label="Collect: jump to Collect guidance"><title>Collect: jump to guidance</title><path d="M 1086.11 290.57 A 568 568 0 0 1 1181.84 746.55 L 912.24 687.49 A 292 292 0 0 0 863.02 453.07 Z"/></a>
<a href="#stage-process" class="kb-cycle__image-hotspot" aria-label="Process: jump to Process guidance"><title>Process: jump to guidance</title><path d="M 1174.72 775.43 A 568 568 0 0 1 877.9 1134.58 L 755.99 886.97 A 292 292 0 0 0 908.57 702.33 Z"/></a>
<a href="#stage-analyse" class="kb-cycle__image-hotspot" aria-label="Analyse: jump to Analyse guidance"><title>Analyse: jump to guidance</title><path d="M 850.89 1147.01 A 568 568 0 0 1 385.03 1138.88 L 502.61 889.18 A 292 292 0 0 0 742.1 893.36 Z"/></a>
<a href="#stage-preserve" class="kb-cycle__image-hotspot" aria-label="Preserve: jump to Preserve guidance"><title>Preserve: jump to guidance</title><path d="M 358.47 1125.51 A 568 568 0 0 1 74.36 756.22 L 342.9 692.46 A 292 292 0 0 0 488.95 882.31 Z"/></a>
<a href="#stage-share" class="kb-cycle__image-hotspot" aria-label="Share: jump to Share guidance"><title>Share: jump to guidance</title><path d="M 68.25 727.12 A 568 568 0 0 1 179.85 274.75 L 397.13 444.94 A 292 292 0 0 0 339.76 677.5 Z"/></a>
<a href="#stage-reuse" class="kb-cycle__image-hotspot" aria-label="Reuse: jump to Reuse guidance"><title>Reuse: jump to guidance</title><path d="M 198.79 251.82 A 568 568 0 0 1 622.04 57.02 L 624.45 333.01 A 292 292 0 0 0 406.86 433.16 Z"/></a>
  <a href="#storage-across-stages" class="kb-cycle__image-hotspot" aria-label="Storage and Management: jump to cross-cutting storage guidance"><title>Storage and Management across all stages</title><circle cx="627" cy="625" r="282"/></a>
</svg>
  <figcaption>Choose a segment or use the accessible stage links alongside the figure.</figcaption>
  </figure>
  <nav class="kb-cycle__nav" aria-label="Research data lifecycle stages">
   <ol><li><a href="#stage-plan" class="kb-cycle__step" style="--step-color:#ed7d22">
  <span class="kb-cycle__step-number" aria-hidden="true">01</span>
  <span><strong>Plan</strong><small>Prepare a responsible research data strategy</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li><li><a href="#stage-collect" class="kb-cycle__step" style="--step-color:#cf9d13">
  <span class="kb-cycle__step-number" aria-hidden="true">02</span>
  <span><strong>Collect</strong><small>Capture data and documentation consistently</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li><li><a href="#stage-process" class="kb-cycle__step" style="--step-color:#5b9b46">
  <span class="kb-cycle__step-number" aria-hidden="true">03</span>
  <span><strong>Process</strong><small>Clean, organise and quality-check</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li><li><a href="#stage-analyse" class="kb-cycle__step" style="--step-color:#128d83">
  <span class="kb-cycle__step-number" aria-hidden="true">04</span>
  <span><strong>Analyse</strong><small>Generate reproducible evidence</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li><li><a href="#stage-preserve" class="kb-cycle__step" style="--step-color:#2c76ad">
  <span class="kb-cycle__step-number" aria-hidden="true">05</span>
  <span><strong>Preserve</strong><small>Retain what remains useful and accountable</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li><li><a href="#stage-share" class="kb-cycle__step" style="--step-color:#834aa0">
  <span class="kb-cycle__step-number" aria-hidden="true">06</span>
  <span><strong>Share</strong><small>Enable responsible discovery and access</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li><li><a href="#stage-reuse" class="kb-cycle__step" style="--step-color:#c22f53">
  <span class="kb-cycle__step-number" aria-hidden="true">07</span>
  <span><strong>Reuse</strong><small>Evaluate and repurpose existing evidence</small></span>
  <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
</a></li></ol>
   <a class="kb-cycle__storage-link" href="#storage-across-stages"><strong>Storage &amp; Management</strong><span>Continuous responsibilities throughout the life cycle ↗</span></a>
  </nav>
 </div>
</section>

<section class="kb-cycle__storage" id="storage-across-stages" aria-labelledby="storage-heading">
 <p class="kb-cycle__eyebrow">CROSS-CUTTING RESPONSIBILITY</p>
 <h2 id="storage-heading">Storage &amp; Management at every stage</h2>
 <p>Storage is <strong>not an additional life cycle stage</strong> in this model. Its design, protection, maintenance and disposition must be considered repeatedly as research progresses. By contrast, the <em>Preserve</em> stage focuses specifically on selecting, retaining and maintaining records for long-term use or accountable disposition.</p>
 <div class="kb-cycle__storage-grid">
  <div><strong>Storage options</strong><p>Choose approved environments suited to data volume, sensitivity, availability and cost.</p></div>
  <div><strong>Data security</strong><p>Define access control, authentication, safe transfer and confidentiality safeguards.</p></div>
  <div><strong>Data safety</strong><p>Maintain integrity, backup, recovery and incident-response arrangements.</p></div>
  <div><strong>Data retention</strong><p>Document retention periods, responsibilities and project-specific obligations.</p></div>
  <div><strong>Archives &amp; records</strong><p>Identify and maintain essential records, documentation, metadata and formats.</p></div>
  <div><strong>Data destruction</strong><p>Securely dispose of copies when permissible and document disposition decisions.</p></div>
 </div>
 <div class="kb-cycle__resources kb-cycle__storage-resources">
 <a href="{{ '/storage' | relative_url }}">Data storage guidance <span aria-hidden="true">→</span></a>
 <a href="{{ '/data_security' | relative_url }}">Data security guidance <span aria-hidden="true">→</span></a>
 <a href="{{ '/data_deletion' | relative_url }}">Data deletion guidance <span aria-hidden="true">→</span></a>
 </div>
</section>

<section class="kb-cycle__stage-content" aria-labelledby="stage-content-heading">
 <p class="kb-cycle__eyebrow">GUIDANCE BY STAGE</p>
 <h2 id="stage-content-heading">Activities and storage considerations</h2>
 <p>Each stage includes a short explanation, practical considerations, storage responsibilities and a biomedical example. Follow the related guidance links for more detail.</p>
 <section class="kb-cycle__phase" id="stage-plan" aria-labelledby="heading-plan" style="--step-color:#ed7d22">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">01</span>
    <div><h3 id="heading-plan">Plan</h3><p>Prepare a responsible research data strategy</p></div>
  </header>
  <p>Plan data management from study design through project closure. Describe what information will be generated or reused, which rules apply, and who is accountable.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Define data types, governance responsibilities and study data flows.</li>
<li>Prepare and maintain a data management plan, including metadata and documentation arrangements.</li>
<li>Assess study-specific ethics, consent, confidentiality and access requirements.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Estimate volume, growth, sensitivity, costs and storage duration.</li>
<li>Select approved storage locations, access roles, backups and secure-transfer arrangements.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> DMP, responsibilities matrix and initial storage/security plan.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> A multicentre cohort study selects an institutionally approved storage environment and documents where coded data and identification keys may be held.</p>
  <div class="kb-cycle__resources"><a href="{{ '/planning' | relative_url }}">Read Plan guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/storage' | relative_url }}">Data storage guidance <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section><section class="kb-cycle__phase" id="stage-collect" aria-labelledby="heading-collect" style="--step-color:#cf9d13">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">02</span>
    <div><h3 id="heading-collect">Collect</h3><p>Capture data and documentation consistently</p></div>
  </header>
  <p>Collect or acquire clinical, epidemiological and public health information using defined methods and documented instruments.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Use consistent collection procedures, validated instruments and controlled terminology where suitable.</li>
<li>Record variables, units, provenance, data dictionaries and collection dates.</li>
<li>Check completeness and quality at the point of capture.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Secure incoming data, including protected transfer from collection systems to approved storage.</li>
<li>Use appropriate authentication, permissions, backups and separation of direct identifiers when needed.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> Collection protocol, dataset inventory and codebook.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> A survey team transfers responses from the collection platform to approved project storage using role-based access and verifies that the transferred files are intact.</p>
  <div class="kb-cycle__resources"><a href="{{ '/collecting' | relative_url }}">Read Collect guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/metadata' | relative_url }}">Documentation and metadata <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section><section class="kb-cycle__phase" id="stage-process" aria-labelledby="heading-process" style="--step-color:#5b9b46">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">03</span>
    <div><h3 id="heading-process">Process</h3><p>Clean, organise and quality-check</p></div>
  </header>
  <p>Process raw or acquired data into well-defined formats suitable for analysis, preserving the origin and meaning of observations.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Perform reproducible cleaning, validation and harmonisation steps.</li>
<li>Document corrections, transformations and missing-data handling.</li>
<li>Version scripts, datasets and relevant metadata to support traceability.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Maintain an immutable or controlled raw-data copy and clearly separated working versions.</li>
<li>Store intermediate outputs and logs securely; apply suitable backup and recovery procedures.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> Data-quality report, transformation log and analysis-ready version.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> A registry team validates values and retains raw extracts separately from cleaned datasets, with versioned processing scripts.</p>
  <div class="kb-cycle__resources"><a href="{{ '/processing' | relative_url }}">Read Process guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/services/data-quality' | relative_url }}">Data Quality Assessments <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section><section class="kb-cycle__phase" id="stage-analyse" aria-labelledby="heading-analyse" style="--step-color:#128d83">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">04</span>
    <div><h3 id="heading-analyse">Analyse</h3><p>Generate reproducible evidence</p></div>
  </header>
  <p>Explore and model data to answer research questions while keeping analytical workflows documented and appropriately controlled.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Predefine suitable statistical or computational approaches where appropriate.</li>
<li>Record code, software versions, parameters and derivation of results.</li>
<li>Use secure or privacy-preserving computing arrangements where data sensitivity requires them.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Store working datasets, computational environments, analysis code and outputs with defined permissions.</li>
<li>Protect temporary files and exports, and review disclosure risk before moving results outside secure environments.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> Analysis plan, reproducible scripts and documented results.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> A clinical analysis runs inside a protected computing environment; outputs are reviewed before export and are linked to the exact analysis script.</p>
  <div class="kb-cycle__resources"><a href="{{ '/analysing' | relative_url }}">Read Analyse guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/data_security' | relative_url }}">Data security guidance <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section><section class="kb-cycle__phase" id="stage-preserve" aria-labelledby="heading-preserve" style="--step-color:#2c76ad">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">05</span>
    <div><h3 id="heading-preserve">Preserve</h3><p>Retain what remains useful and accountable</p></div>
  </header>
  <p>Preserve selected research data and documentation for the required period so they remain understandable, trustworthy and usable.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Identify significant records, formats, metadata and documentation for retention.</li>
<li>Document preservation responsibilities, integrity checks and access restrictions.</li>
<li>Apply approved retention and disposition rules, including defensible deletion when appropriate.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Choose suitable long-term preservation or archive storage and review format sustainability.</li>
<li>Record retention schedules, backup/integrity checks and secure destruction procedures when retention ends.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> Preservation package, retention schedule and disposition record.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> A completed clinical study retains essential records under its approved retention policy and securely disposes of temporary working copies when permitted.</p>
  <div class="kb-cycle__resources"><a href="{{ '/preserving' | relative_url }}">Read Preserve guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/data_deletion' | relative_url }}">Data deletion guidance <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section><section class="kb-cycle__phase" id="stage-share" aria-labelledby="heading-share" style="--step-color:#834aa0">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">06</span>
    <div><h3 id="heading-share">Share</h3><p>Enable responsible discovery and access</p></div>
  </header>
  <p>Make data or metadata findable and reusable under access conditions appropriate to the study, participants and legal framework.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Describe studies and datasets using clear, interoperable metadata.</li>
<li>Set access conditions, reuse permissions, citation details and data availability statements.</li>
<li>Publish documentation or metadata and establish a suitable repository or controlled-access route.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Choose secure repository or access infrastructure with a clear preservation and service plan.</li>
<li>Verify the release copy, retention expectations and permissions; restrict personal data as required.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> Published metadata, access statement and citable research resource.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> An epidemiological study publishes metadata in the Health Study Hub while research data remain in an approved environment with controlled access.</p>
  <div class="kb-cycle__resources"><a href="{{ '/sharing' | relative_url }}">Read Share guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/services/health-study-hub' | relative_url }}">Health Study Hub <span aria-hidden="true">→</span></a>
<a href="{{ '/services/metadata-schema' | relative_url }}">NFDI4Health Metadata Schema <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section><section class="kb-cycle__phase" id="stage-reuse" aria-labelledby="heading-reuse" style="--step-color:#c22f53">
  <header class="kb-cycle__phase-header">
    <span class="kb-cycle__phase-index" aria-hidden="true">07</span>
    <div><h3 id="heading-reuse">Reuse</h3><p>Evaluate and repurpose existing evidence</p></div>
  </header>
  <p>Reuse data for secondary research only after assessing fitness for purpose, provenance, documentation and any applicable conditions.</p>
  <div class="kb-cycle__phase-columns">
    <div><h4>Key considerations</h4><ul><li>Find candidate datasets and review their variable definitions, quality and documentation.</li>
<li>Check permitted access, reuse purposes, agreements and attribution requirements.</li>
<li>Document harmonisation, transformation and secondary-analysis decisions.</li></ul></div>
    <div class="kb-cycle__storage-note"><h4>Storage considerations</h4><ul><li>Use storage and access controls aligned with the original data-use conditions.</li>
<li>Keep working copies traceable, protect them appropriately and dispose of them as agreed.</li></ul></div>
  </div>
  <p class="kb-cycle__output"><strong>Typical outputs:</strong> Reuse suitability assessment, access record and analysis provenance.</p>
  <p class="kb-cycle__example"><strong>Biomedical example:</strong> Researchers obtain two cohort datasets under access agreements, record harmonisation choices and keep permitted copies in restricted project storage.</p>
  <div class="kb-cycle__resources"><a href="{{ '/reusing' | relative_url }}">Read Reuse guidance <span aria-hidden="true">→</span></a>
<a href="{{ '/services/health-study-hub' | relative_url }}">Health Study Hub <span aria-hidden="true">→</span></a></div>
  <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
</section>
</section>

<section class="kb-cycle__attribution" aria-labelledby="attribution-heading">
 <h2 id="attribution-heading">Sources and adaptation</h2>
 <p><strong>Conceptual adaptation:</strong> The seven stage labels and ordering follow <a href="https://rdmkit.elixir-europe.org/data_life_cycle">RDMkit (ELIXIR)</a>. The central, continuous role of storage and its considerations are inspired by the <a href="https://datamanagement.hms.harvard.edu/plan-design/biomedical-data-lifecycle">Harvard Medical School Biomedical Data Lifecycle</a>, developed by the LMA Research Data Management Working Group.</p>
 <p>The interactive diagram and explanatory text on this page are newly prepared for the NFDI4Health Knowledge Base; the Harvard graphic has not been reproduced. RDMkit content is published under CC BY 4.0 except where otherwise noted; Harvard identifies its original lifecycle illustration as CC BY-NC 4.0. Consult the original sources for their full attribution and reuse terms.</p>
 <p class="kb-cycle__closing">Lifecycle stages may overlap or recur. Documentation, FAIR principles, ethical governance and secure data management remain relevant throughout the research process.</p>
</section>

</div>
