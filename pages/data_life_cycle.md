---
title: Research Data Life Cycle
permalink: /data_life_cycle
redirect_from:
  - /data-life-cycle
  - /data-life-cycle/
sidebar: data_management
search_exclude: false
---

# NFDI4Health Research Data Life Cycle

The NFDI4Health Knowledge Base organises guidance according to the biomedical research data life cycle, with a specific focus on clinical, epidemiological, and public health research involving sensitive personal health data.

Effective research data management in health research requires more than generic data handling. It requires planning for FAIR implementation, governance, metadata interoperability, secure data processing, controlled sharing, and responsible reuse.

This section provides practical guidance for each stage of the research lifecycle.

You will find:

- explanation of each lifecycle phase
- FAIR implementation guidance
- governance and GDPR considerations
- related NFDI4Health services
- practical recommendations
- self-learning modules
- how-to implementation support

The lifecycle helps researchers, data stewards, and research support teams understand where NFDI4Health services support the research workflow.

## Explore the lifecycle
<div class="lifecycle-hero-clean">

<p class="lifecycle-intro-clean">
The NFDI4Health research data life cycle provides a framework for managing health research data in a FAIR, secure, and responsible manner across all stages of research.
</p>

<p class="lifecycle-hint-clean">
ⓘ Click on a phase in the cycle to explore guidance and related resources.
</p>

<div class="cycle-wrapper-clean">

<svg viewBox="0 0 700 700" class="cycle-svg-clean" aria-label="NFDI4Health research data life cycle">

<a href="/study-planning">
<path class="seg seg1" d="M350 45 A305 305 0 0 1 588 160 L465 265 A145 145 0 0 0 350 205 Z"/>
<text x="465" y="190" class="label">Planning</text>
</a>

<a href="/data-collection-documentation">
<path class="seg seg2" d="M608 180 A305 305 0 0 1 640 390 L485 355 A145 145 0 0 0 480 282 Z"/>
<text x="565" y="335" class="label">Collection</text>
</a>

<a href="/data-processing-quality">
<path class="seg seg3" d="M635 420 A305 305 0 0 1 492 625 L420 480 A145 145 0 0 0 485 382 Z"/>
<text x="530" y="535" class="label">Processing</text>
</a>

<a href="/storage-access-governance">
<path class="seg seg4" d="M462 638 A305 305 0 0 1 238 638 L282 482 A145 145 0 0 0 418 482 Z"/>
<text x="350" y="590" class="label">Governance</text>
</a>

<a href="/analysis-privacy-preserving-computing">
<path class="seg seg5" d="M208 625 A305 305 0 0 1 65 420 L215 382 A145 145 0 0 0 280 480 Z"/>
<text x="170" y="535" class="label">Analysis</text>
</a>

<a href="/sharing-discovery-publication">
<path class="seg seg6" d="M60 390 A305 305 0 0 1 92 180 L220 282 A145 145 0 0 0 215 355 Z"/>
<text x="135" y="335" class="label">Sharing</text>
</a>

<a href="/reuse-secondary-research">
<path class="seg seg7" d="M112 160 A305 305 0 0 1 350 45 L350 205 A145 145 0 0 0 235 265 Z"/>
<text x="235" y="190" class="label">Reuse</text>
</a>

<circle cx="350" cy="350" r="138" fill="#ffffff" stroke="#e5e7eb" stroke-width="3"/>

<text x="350" y="330" text-anchor="middle" class="centre-title">NFDI4Health</text>
<text x="350" y="368" text-anchor="middle" class="centre-sub">Research Data</text>
<text x="350" y="398" text-anchor="middle" class="centre-sub">Life Cycle</text>

</svg>

</div>

</div>

<style>
.lifecycle-hero-clean {
  margin: 1.5rem 0 2.5rem 0;
  text-align: center;
}

.lifecycle-intro-clean {
  max-width: 760px;
  margin: 0 auto 0.75rem auto;
  font-size: 1.05rem;
  line-height: 1.6;
}

.lifecycle-hint-clean {
  color: #c23669;
  font-weight: 600;
  margin-bottom: 1.5rem;
}

.cycle-wrapper-clean {
  display: flex;
  justify-content: center;
  align-items: center;
}

.cycle-svg-clean {
  max-width: 640px;
  width: 100%;
  height: auto;
}

.seg {
  stroke: #ffffff;
  stroke-width: 14;
  transition: transform 0.2s ease, opacity 0.2s ease;
  transform-origin: 350px 350px;
}

.seg:hover {
  transform: scale(1.025);
  opacity: 0.9;
  cursor: pointer;
}

.seg1 { fill: #f97316; }
.seg2 { fill: #fbbf24; }
.seg3 { fill: #84cc16; }
.seg4 { fill: #14b8a6; }
.seg5 { fill: #3b82f6; }
.seg6 { fill: #8b5cf6; }
.seg7 { fill: #f43f5e; }

.label {
  fill: #ffffff;
  font-size: 24px;
  font-weight: 800;
  text-anchor: middle;
  pointer-events: none;
}

.centre-title {
  fill: #1f2937;
  font-size: 34px;
  font-weight: 900;
}

.centre-sub {
  fill: #4b5563;
  font-size: 25px;
  font-weight: 700;
}

@media (max-width: 800px) {
  .cycle-svg-clean {
    max-width: 100%;
  }

  .label {
    font-size: 20px;
  }

  .centre-title {
    font-size: 28px;
  }

  .centre-sub {
    font-size: 21px;
  }
}
</style>
