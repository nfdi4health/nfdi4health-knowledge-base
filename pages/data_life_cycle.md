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
<div class="nfdi-cycle-wrapper">

<svg class="nfdi-cycle" viewBox="0 0 600 600" role="img" aria-label="NFDI4Health research data life cycle">

<a href="/study-planning">
<path d="M 306.8 40.1 A 260 260 0 0 1 499.0 132.6 L 403.3 213.1 A 135 135 0 0 0 303.5 165.0 Z" fill="#f97316" class="cycle-segment"></path>
</a>

<a href="/data-collection-documentation">
<path d="M 507.5 143.3 A 260 260 0 0 1 554.9 351.2 L 432.4 326.6 A 135 135 0 0 0 407.7 218.6 Z" fill="#fbbf24" class="cycle-segment"></path>
</a>

<a href="/data-processing-quality">
<path d="M 551.9 364.5 A 260 260 0 0 1 418.9 531.2 L 361.7 420.1 A 135 135 0 0 0 430.8 333.5 Z" fill="#84cc16" class="cycle-segment"></path>
</a>

<a href="/storage-access-governance">
<path d="M 406.6 537.1 A 260 260 0 0 1 193.4 537.1 L 244.6 423.1 A 135 135 0 0 0 355.4 423.1 Z" fill="#14b8a6" class="cycle-segment"></path>
</a>

<a href="/analysis-privacy-preserving-computing">
<path d="M 181.1 531.2 A 260 260 0 0 1 48.1 364.5 L 169.2 333.5 A 135 135 0 0 0 238.3 420.1 Z" fill="#3b82f6" class="cycle-segment"></path>
</a>

<a href="/sharing-discovery-publication">
<path d="M 45.1 351.2 A 260 260 0 0 1 92.5 143.3 L 192.3 218.6 A 135 135 0 0 0 167.6 326.6 Z" fill="#8b5cf6" class="cycle-segment"></path>
</a>

<a href="/reuse-secondary-research">
<path d="M 101.0 132.6 A 260 260 0 0 1 293.2 40.1 L 296.5 165.0 A 135 135 0 0 0 196.7 213.1 Z" fill="#f43f5e" class="cycle-segment"></path>
</a>

<circle cx="300" cy="300" r="120" fill="#ffffff" stroke="#e5e7eb" stroke-width="2"></circle>

<text x="300" y="280" text-anchor="middle" class="cycle-centre-title">NFDI4Health</text>
<text x="300" y="310" text-anchor="middle" class="cycle-centre-subtitle">Research Data</text>
<text x="300" y="335" text-anchor="middle" class="cycle-centre-subtitle">Life Cycle</text>

<text x="384.6" y="124.3" class="cycle-label">1. Planning</text>
<text x="490.1" y="256.6" class="cycle-label">2. Collection</text>
<text x="452.5" y="421.6" class="cycle-label">3. Processing</text>
<text x="300.0" y="495.0" class="cycle-label">4. Governance</text>
<text x="147.5" y="421.6" class="cycle-label">5. Analysis</text>
<text x="109.9" y="256.6" class="cycle-label">6. Sharing</text>
<text x="215.4" y="124.3" class="cycle-label">7. Reuse</text>

</svg>

</div>

<style>
.nfdi-cycle-wrapper {
  display: flex;
  justify-content: center;
  margin: 2rem 0 3rem 0;
}

.nfdi-cycle {
  max-width: 720px;
  width: 100%;
  height: auto;
}

.cycle-segment {
  stroke: #ffffff;
  stroke-width: 8;
  transition: opacity 0.2s ease, transform 0.2s ease;
  transform-origin: 300px 300px;
}

.cycle-segment:hover {
  opacity: 0.85;
  transform: scale(1.02);
  cursor: pointer;
}

.cycle-label {
  fill: #ffffff;
  font-size: 18px;
  font-weight: 700;
  text-anchor: middle;
  pointer-events: none;
}

.cycle-centre-title {
  fill: #1f2937;
  font-size: 28px;
  font-weight: 800;
}

.cycle-centre-subtitle {
  fill: #4b5563;
  font-size: 22px;
  font-weight: 600;
}
</style>
