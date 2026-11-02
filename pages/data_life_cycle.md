---
title: Research Data Life Cycle
description: Seven RDMkit lifecycle stages with Storage and Management considered throughout biomedical research.
permalink: /data_life_cycle
redirect_from:
  - /data-life-cycle
  - /data-life-cycle/
sidebar: data_management
search_exclude: false
contributors: [Atinkut A. Zeleke]
---

<div class="kb-cycle">
  <p class="kb-cycle__lead">Explore the seven research data life cycle stages — <strong>Plan, Collect, Process, Analyse, Preserve, Share and Reuse</strong> — with <strong>Storage &amp; Management</strong> at the centre of every stage.</p>
  <p class="kb-cycle__intro">The stages follow the <a href="https://rdmkit.elixir-europe.org/data_life_cycle">RDMkit research data lifecycle</a>. The cross-cutting storage concept draws on <a href="https://datamanagement.hms.harvard.edu/plan-design/biomedical-data-lifecycle">Harvard Medical School's Biomedical Data Lifecycle</a>. This version translates the combined approach into introductory guidance for clinical, epidemiological and public health research.</p>
  <div class="kb-cycle__draft" role="note">
    <strong>Content under development:</strong> This NFDI4Health-oriented overview is intended for data steward review. Some linked detailed pages still contain inherited RDMkit guidance and are being adapted to biomedical research contexts.</div>
  <section class="kb-cycle__explorer" id="lifecycle-diagram" aria-labelledby="diagram-heading">
    <div class="kb-cycle__explorer-intro">
      <p class="kb-cycle__eyebrow">INTERACTIVE LIFECYCLE</p>
      <h2 id="diagram-heading">Seven stages, one continuous storage responsibility</h2>
      <p>Click a coloured stage to jump to its activities and stage-specific storage considerations. Click the centre to explore storage responsibilities shared across all seven stages.</p>
    </div>
    <div class="kb-cycle__visual-grid">
      <figure class="kb-cycle__figure">
        <svg xmlns="http://www.w3.org/2000/svg" class="kb-cycle__svg kb-cycle__svg--photo" viewBox="0 0 1254 1254" role="group" aria-labelledby="kb-cycle-svg-title kb-cycle-svg-desc">
          <title id="kb-cycle-svg-title">Research data lifecycle: Plan, Collect, Process, Analyse, Preserve, Share, Reuse and Storage Management</title>
          <desc id="kb-cycle-svg-desc">Illustrated seven-stage lifecycle with clickable segments. Choose a stage to jump to its detailed guidance. Choose the centre for storage across all stages. Matching accessible text links are provided to the right and below.</desc>
          <image href="{{ '/assets/img/section-icons/rdmkit-storage-lifecycle.png' | relative_url }}" x="0" y="0" width="1254" height="1254" preserveAspectRatio="xMidYMid meet"/>
          <!-- Hotspot contours are traced from the actual RDMkit-style PNG and inset 5 px,
               so the blue hover outline follows the stage shapes without crossing the white separators. -->
          <a href="#stage-plan" class="kb-cycle__image-hotspot" aria-label="Plan: jump to Plan guidance">
            <title>Plan: jump to guidance</title>
            <path d="M 647 41 L 716 178 L 716 186 L 644 325 L 694 333 L 730 345 L 756 357 L 801 386 L 842 425 L 996 392 L 1065 250 L 1042 221 L 1005 184 L 960 147 L 915 117 L 863 90 L 824 74 L 755 54 L 695 44 Z" stroke-linejoin="round"/>
          </a>
          <a href="#stage-collect" class="kb-cycle__image-hotspot" aria-label="Collect: jump to Collect guidance">
            <title>Collect: jump to guidance</title>
            <path d="M 1088 277 L 1024 410 L 1017 417 L 863 451 L 888 492 L 899 518 L 909 552 L 916 604 L 915 645 L 911 670 L 1031 773 L 1186 738 L 1196 686 L 1200 638 L 1199 575 L 1195 537 L 1182 473 L 1165 419 L 1144 370 L 1118 322 Z" stroke-linejoin="round"/>
          </a>
          <a href="#stage-process" class="kb-cycle__image-hotspot" aria-label="Process: jump to Process guidance">
            <title>Process: jump to guidance</title>
            <path d="M 1177 771 L 1025 806 L 1018 804 L 902 705 L 883 752 L 851 800 L 808 843 L 762 874 L 756 1023 L 885 1136 L 896 1131 L 947 1098 L 985 1068 L 1038 1017 L 1067 983 L 1106 928 L 1128 890 L 1157 828 Z" stroke-linejoin="round"/>
          </a>
          <a href="#stage-analyse" class="kb-cycle__image-hotspot" aria-label="Analyse: jump to Analyse guidance">
            <title>Analyse: jump to guidance</title>
            <path d="M 375 982 L 382 1153 L 440 1177 L 484 1190 L 541 1201 L 603 1206 L 653 1205 L 718 1197 L 770 1185 L 818 1169 L 857 1152 L 725 1035 L 731 889 L 673 907 L 633 912 L 605 912 L 565 907 L 538 900 L 501 886 Z" stroke-linejoin="round"/>
          </a>
          <a href="#stage-preserve" class="kb-cycle__image-hotspot" aria-label="Preserve: jump to Preserve guidance">
            <title>Preserve: jump to guidance</title>
            <path d="M 182 659 L 62 755 L 80 813 L 100 862 L 131 921 L 159 964 L 191 1005 L 240 1056 L 264 1077 L 302 1106 L 350 1136 L 343 973 L 352 963 L 472 870 L 429 840 L 387 796 L 358 751 L 337 699 Z" stroke-linejoin="round"/>
          </a>
          <a href="#stage-share" class="kb-cycle__image-hotspot" aria-label="Share: jump to Share guidance">
            <title>Share: jump to guidance</title>
            <path d="M 311 299 L 162 271 L 131 315 L 113 346 L 84 408 L 69 451 L 54 512 L 46 573 L 45 643 L 49 688 L 55 723 L 170 631 L 180 627 L 329 666 L 325 631 L 325 604 L 333 548 L 351 497 L 367 467 L 383 444 Z" stroke-linejoin="round"/>
          </a>
          <a href="#stage-reuse" class="kb-cycle__image-hotspot" aria-label="Reuse: jump to Reuse guidance">
            <title>Reuse: jump to guidance</title>
            <path d="M 682 183 L 611 43 L 590 42 L 557 45 L 492 56 L 450 67 L 399 85 L 348 109 L 304 135 L 259 168 L 230 193 L 182 244 L 332 273 L 344 289 L 407 417 L 446 382 L 495 353 L 560 331 L 608 325 Z" stroke-linejoin="round"/>
          </a>
          <a href="#storage-across-stages" class="kb-cycle__image-hotspot" aria-label="Storage and Management: jump to cross-cutting storage guidance">
            <title>Storage and Management across all stages</title>
            <circle cx="618" cy="616" r="275"/>
          </a>
        </svg>
        <figcaption>Choose a segment or use the accessible stage links alongside the figure.</figcaption>
      </figure>
      <nav class="kb-cycle__nav" aria-label="Research data lifecycle stages">
        <ol>
          <li>
            <a href="#stage-plan" class="kb-cycle__step" style="--step-color:#ed7d22">
              <span class="kb-cycle__step-number" aria-hidden="true">01</span>
              <span>
                <strong>Plan</strong>
                <small>Prepare a responsible research data strategy</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
          <li>
            <a href="#stage-collect" class="kb-cycle__step" style="--step-color:#cf9d13">
              <span class="kb-cycle__step-number" aria-hidden="true">02</span>
              <span>
                <strong>Collect</strong>
                <small>Capture data and documentation consistently</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
          <li>
            <a href="#stage-process" class="kb-cycle__step" style="--step-color:#5b9b46">
              <span class="kb-cycle__step-number" aria-hidden="true">03</span>
              <span>
                <strong>Process</strong>
                <small>Clean, organise and quality-check</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
          <li>
            <a href="#stage-analyse" class="kb-cycle__step" style="--step-color:#128d83">
              <span class="kb-cycle__step-number" aria-hidden="true">04</span>
              <span>
                <strong>Analyse</strong>
                <small>Generate reproducible evidence</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
          <li>
            <a href="#stage-preserve" class="kb-cycle__step" style="--step-color:#2c76ad">
              <span class="kb-cycle__step-number" aria-hidden="true">05</span>
              <span>
                <strong>Preserve</strong>
                <small>Retain what remains useful and accountable</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
          <li>
            <a href="#stage-share" class="kb-cycle__step" style="--step-color:#834aa0">
              <span class="kb-cycle__step-number" aria-hidden="true">06</span>
              <span>
                <strong>Share</strong>
                <small>Enable responsible discovery and access</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
          <li>
            <a href="#stage-reuse" class="kb-cycle__step" style="--step-color:#c22f53">
              <span class="kb-cycle__step-number" aria-hidden="true">07</span>
              <span>
                <strong>Reuse</strong>
                <small>Evaluate and repurpose existing evidence</small>
              </span>
              <span class="kb-cycle__step-arrow" aria-hidden="true">↗</span>
            </a>
          </li>
        </ol>
        <a class="kb-cycle__storage-link" href="#storage-across-stages">
          <strong>Storage &amp; Management</strong>
          <span>Continuous responsibilities throughout the life cycle ↗</span>
        </a>
      </nav>
    </div>
  </section>
  <section class="kb-cycle__storage" id="storage-across-stages" aria-labelledby="storage-heading">
    <p class="kb-cycle__eyebrow">CROSS-CUTTING RESPONSIBILITY</p>
    <h2 id="storage-heading">Storage &amp; Management at every stage</h2>
    <p>Storage is <strong>not an additional life cycle stage</strong> in this model. Its design, protection, maintenance and disposition must be considered repeatedly as research progresses. By contrast, the <em>Preserve</em> stage focuses specifically on selecting, retaining and maintaining records for long-term use or accountable disposition.</p>
    <div class="kb-cycle__storage-grid">
      <div>
        <strong>Storage options</strong>
        <p>Choose approved environments suited to data volume, sensitivity, availability and cost.</p>
      </div>
      <div>
        <strong>Data security</strong>
        <p>Define access control, authentication, safe transfer and confidentiality safeguards.</p>
      </div>
      <div>
        <strong>Data safety</strong>
        <p>Maintain integrity, backup, recovery and incident-response arrangements.</p>
      </div>
      <div>
        <strong>Data retention</strong>
        <p>Document retention periods, responsibilities and project-specific obligations.</p>
      </div>
      <div>
        <strong>Archives &amp; records</strong>
        <p>Identify and maintain essential records, documentation, metadata and formats.</p>
      </div>
      <div>
        <strong>Data destruction</strong>
        <p>Securely dispose of copies when permissible and document disposition decisions.</p>
      </div>
    </div>
    <div class="kb-cycle__resources kb-cycle__storage-resources">
      <a href="{{ '/storage' | relative_url }}">Data storage guidance <span aria-hidden="true">→</span>
      </a>
      <a href="{{ '/data_security' | relative_url }}">Data security guidance <span aria-hidden="true">→</span>
      </a>
      <a href="{{ '/data_deletion' | relative_url }}">Data deletion guidance <span aria-hidden="true">→</span>
      </a>
    </div>
  </section>
  <section class="kb-cycle__stage-content" aria-labelledby="stage-content-heading">
    <p class="kb-cycle__eyebrow">GUIDANCE BY STAGE</p>
    <h2 id="stage-content-heading">Activities and storage considerations</h2>
    <p>Each stage includes a short explanation, practical considerations, storage responsibilities and a biomedical example. Follow the related guidance links for more detail.</p>
    <section class="kb-cycle__phase" id="stage-plan" aria-labelledby="heading-plan" style="--step-color:#ed7d22">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">01</span>
        <div>
          <h3 id="heading-plan">Plan</h3>
          <p>Prepare a responsible research data strategy</p>
        </div>
      </header>
      <p>Plan data management from study design through project closure. Describe what information will be generated or reused, which rules apply, and who is accountable.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Define data types, governance responsibilities and study data flows.</li>
            <li>Prepare and maintain a data management plan, including metadata and documentation arrangements.</li>
            <li>Assess study-specific ethics, consent, confidentiality and access requirements.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Estimate volume, growth, sensitivity, costs and storage duration.</li>
            <li>Select approved storage locations, access roles, backups and secure-transfer arrangements.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> DMP, responsibilities matrix and initial storage/security plan.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> A multicentre cohort study selects an institutionally approved storage environment and documents where coded data and identification keys may be held.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/planning' | relative_url }}">Read Plan guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/storage' | relative_url }}">Data storage guidance <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
    <section class="kb-cycle__phase" id="stage-collect" aria-labelledby="heading-collect" style="--step-color:#cf9d13">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">02</span>
        <div>
          <h3 id="heading-collect">Collect</h3>
          <p>Capture data and documentation consistently</p>
        </div>
      </header>
      <p>Collect or acquire clinical, epidemiological and public health information using defined methods and documented instruments.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Use consistent collection procedures, validated instruments and controlled terminology where suitable.</li>
            <li>Record variables, units, provenance, data dictionaries and collection dates.</li>
            <li>Check completeness and quality at the point of capture.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Secure incoming data, including protected transfer from collection systems to approved storage.</li>
            <li>Use appropriate authentication, permissions, backups and separation of direct identifiers when needed.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> Collection protocol, dataset inventory and codebook.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> A survey team transfers responses from the collection platform to approved project storage using role-based access and verifies that the transferred files are intact.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/collecting' | relative_url }}">Read Collect guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/metadata' | relative_url }}">Documentation and metadata <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
    <section class="kb-cycle__phase" id="stage-process" aria-labelledby="heading-process" style="--step-color:#5b9b46">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">03</span>
        <div>
          <h3 id="heading-process">Process</h3>
          <p>Clean, organise and quality-check</p>
        </div>
      </header>
      <p>Process raw or acquired data into well-defined formats suitable for analysis, preserving the origin and meaning of observations.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Perform reproducible cleaning, validation and harmonisation steps.</li>
            <li>Document corrections, transformations and missing-data handling.</li>
            <li>Version scripts, datasets and relevant metadata to support traceability.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Maintain an immutable or controlled raw-data copy and clearly separated working versions.</li>
            <li>Store intermediate outputs and logs securely; apply suitable backup and recovery procedures.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> Data-quality report, transformation log and analysis-ready version.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> A registry team validates values and retains raw extracts separately from cleaned datasets, with versioned processing scripts.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/processing' | relative_url }}">Read Process guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/services/data-quality' | relative_url }}">Data Quality Assessments <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
    <section class="kb-cycle__phase" id="stage-analyse" aria-labelledby="heading-analyse" style="--step-color:#128d83">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">04</span>
        <div>
          <h3 id="heading-analyse">Analyse</h3>
          <p>Generate reproducible evidence</p>
        </div>
      </header>
      <p>Explore and model data to answer research questions while keeping analytical workflows documented and appropriately controlled.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Predefine suitable statistical or computational approaches where appropriate.</li>
            <li>Record code, software versions, parameters and derivation of results.</li>
            <li>Use secure or privacy-preserving computing arrangements where data sensitivity requires them.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Store working datasets, computational environments, analysis code and outputs with defined permissions.</li>
            <li>Protect temporary files and exports, and review disclosure risk before moving results outside secure environments.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> Analysis plan, reproducible scripts and documented results.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> A clinical analysis runs inside a protected computing environment; outputs are reviewed before export and are linked to the exact analysis script.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/analysing' | relative_url }}">Read Analyse guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/data_security' | relative_url }}">Data security guidance <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
    <section class="kb-cycle__phase" id="stage-preserve" aria-labelledby="heading-preserve" style="--step-color:#2c76ad">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">05</span>
        <div>
          <h3 id="heading-preserve">Preserve</h3>
          <p>Retain what remains useful and accountable</p>
        </div>
      </header>
      <p>Preserve selected research data and documentation for the required period so they remain understandable, trustworthy and usable.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Identify significant records, formats, metadata and documentation for retention.</li>
            <li>Document preservation responsibilities, integrity checks and access restrictions.</li>
            <li>Apply approved retention and disposition rules, including defensible deletion when appropriate.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Choose suitable long-term preservation or archive storage and review format sustainability.</li>
            <li>Record retention schedules, backup/integrity checks and secure destruction procedures when retention ends.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> Preservation package, retention schedule and disposition record.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> A completed clinical study retains essential records under its approved retention policy and securely disposes of temporary working copies when permitted.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/preserving' | relative_url }}">Read Preserve guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/data_deletion' | relative_url }}">Data deletion guidance <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
    <section class="kb-cycle__phase" id="stage-share" aria-labelledby="heading-share" style="--step-color:#834aa0">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">06</span>
        <div>
          <h3 id="heading-share">Share</h3>
          <p>Enable responsible discovery and access</p>
        </div>
      </header>
      <p>Make data or metadata findable and reusable under access conditions appropriate to the study, participants and legal framework.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Describe studies and datasets using clear, interoperable metadata.</li>
            <li>Set access conditions, reuse permissions, citation details and data availability statements.</li>
            <li>Publish documentation or metadata and establish a suitable repository or controlled-access route.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Choose secure repository or access infrastructure with a clear preservation and service plan.</li>
            <li>Verify the release copy, retention expectations and permissions; restrict personal data as required.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> Published metadata, access statement and citable research resource.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> An epidemiological study publishes metadata in the Health Study Hub while research data remain in an approved environment with controlled access.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/sharing' | relative_url }}">Read Share guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/services/health-study-hub' | relative_url }}">Health Study Hub <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/services/metadata-schema' | relative_url }}">NFDI4Health Metadata Schema <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
    <section class="kb-cycle__phase" id="stage-reuse" aria-labelledby="heading-reuse" style="--step-color:#c22f53">
      <header class="kb-cycle__phase-header">
        <span class="kb-cycle__phase-index" aria-hidden="true">07</span>
        <div>
          <h3 id="heading-reuse">Reuse</h3>
          <p>Evaluate and repurpose existing evidence</p>
        </div>
      </header>
      <p>Reuse data for secondary research only after assessing fitness for purpose, provenance, documentation and any applicable conditions.</p>
      <div class="kb-cycle__phase-columns">
        <div>
          <h4>Key considerations</h4>
          <ul>
            <li>Find candidate datasets and review their variable definitions, quality and documentation.</li>
            <li>Check permitted access, reuse purposes, agreements and attribution requirements.</li>
            <li>Document harmonisation, transformation and secondary-analysis decisions.</li>
          </ul>
        </div>
        <div class="kb-cycle__storage-note">
          <h4>Storage considerations</h4>
          <ul>
            <li>Use storage and access controls aligned with the original data-use conditions.</li>
            <li>Keep working copies traceable, protect them appropriately and dispose of them as agreed.</li>
          </ul>
        </div>
      </div>
      <p class="kb-cycle__output">
        <strong>Typical outputs:</strong> Reuse suitability assessment, access record and analysis provenance.</p>
      <p class="kb-cycle__example">
        <strong>Biomedical example:</strong> Researchers obtain two cohort datasets under access agreements, record harmonisation choices and keep permitted copies in restricted project storage.</p>
      <div class="kb-cycle__resources">
        <a href="{{ '/reusing' | relative_url }}">Read Reuse guidance <span aria-hidden="true">→</span>
        </a>
        <a href="{{ '/services/health-study-hub' | relative_url }}">Health Study Hub <span aria-hidden="true">→</span>
        </a>
      </div>
      <a class="kb-cycle__return" href="#lifecycle-diagram">↑ Back to lifecycle figure</a>
    </section>
  </section>
  <section class="kb-cycle__attribution" aria-labelledby="attribution-heading">
    <h2 id="attribution-heading">Sources and adaptation</h2>
    <p>
      <strong>Conceptual adaptation:</strong> The seven stage labels and ordering follow <a href="https://rdmkit.elixir-europe.org/data_life_cycle">RDMkit (ELIXIR)</a>. The central, continuous role of storage and its considerations are inspired by the <a href="https://datamanagement.hms.harvard.edu/plan-design/biomedical-data-lifecycle">Harvard Medical School Biomedical Data Lifecycle</a>, developed by the LMA Research Data Management Working Group.</p>
    <p>The interactive diagram and explanatory text on this page are newly prepared for the NFDI4Health Knowledge Base; the Harvard graphic has not been reproduced. RDMkit content is published under CC BY 4.0 except where otherwise noted; Harvard identifies its original lifecycle illustration as CC BY-NC 4.0. Consult the original sources for their full attribution and reuse terms.</p>
    <p class="kb-cycle__closing">Lifecycle stages may overlap or recur. Documentation, FAIR principles, ethical governance and secure data management remain relevant throughout the research process.</p>
  </section>
</div>
