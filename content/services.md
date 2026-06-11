---
title: "Working With Me"
description: "Two ways to engage with Bösger Digital — custom Polarion development and hands-on enablement. Remote-first, results-focused."
---

<style>
  .wwm-subtitle {
    font-size: 1.15rem;
    font-weight: 500;
    color: #2563eb;
    margin: -0.5rem 0 2rem;
  }
  .engage-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
    gap: 1.5rem;
    margin: 0 0 2.5rem;
  }
  /* Selectors are scoped under .engage-grid so they out-specify the
     surrounding `.prose` typography styles (spacing, list markers, etc.). */
  .engage-grid .engage-card {
    background: rgba(255, 255, 255, 0.9);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 1.25rem;
    padding: 1.6rem 1.6rem 1.75rem;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
    position: relative;
    overflow: hidden;
    isolation: isolate;
    display: flex;
    flex-direction: column;
  }
  .engage-grid .engage-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, transparent, rgba(37, 99, 235, 0.05), transparent);
    transition: left 0.6s ease;
    pointer-events: none;
  }
  .engage-grid .engage-card:hover::before {
    left: 100%;
  }
  .engage-grid .engage-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 16px 48px rgba(37, 99, 235, 0.15);
    border-color: rgba(37, 99, 235, 0.3);
  }
  .engage-grid .engage-head {
    display: flex;
    align-items: center;
    gap: 0.8rem;
    margin: 0 0 1rem;
  }
  .engage-grid .engage-icon {
    flex-shrink: 0;
    width: 2.75rem;
    height: 2.75rem;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 0.8rem;
    background: rgba(37, 99, 235, 0.1);
    border: 1px solid rgba(37, 99, 235, 0.25);
    color: #2563eb;
  }
  .engage-grid .engage-icon svg {
    width: 1.4rem;
    height: 1.4rem;
    display: block;
  }
  .engage-grid .engage-tag {
    background: rgba(37, 99, 235, 0.1);
    border: 1px solid rgba(37, 99, 235, 0.3);
    color: #2563eb;
    border-radius: 2rem;
    padding: 0.28rem 0.9rem;
    font-weight: 700;
    font-size: 0.74rem;
    letter-spacing: 0.07em;
    text-transform: uppercase;
  }
  .engage-grid .engage-title {
    font-size: 1.25rem;
    font-weight: 700;
    line-height: 1.25;
    margin: 0 0 0.5rem;
  }
  .engage-grid .engage-lead {
    font-size: 0.96rem;
    line-height: 1.55;
    margin: 0 0 0.9rem;
    color: #4b5563;
  }
  .engage-grid .engage-list {
    list-style: none;
    padding: 0;
    margin: 0 0 1rem;
    display: flex;
    flex-direction: column;
    gap: 0.45rem;
  }
  .engage-grid .engage-list li {
    position: relative;
    padding-left: 1.5rem;
    margin: 0;
    font-size: 0.9rem;
    line-height: 1.45;
    color: #374151;
  }
  .engage-grid .engage-list li::before {
    content: '✓';
    position: absolute;
    left: 0;
    top: 0;
    color: #2563eb;
    font-weight: 800;
  }
  .engage-grid .engage-bestfor {
    margin: auto 0 0;
    padding-top: 0.9rem;
    border-top: 1px dashed rgba(37, 99, 235, 0.25);
    font-size: 0.88rem;
    line-height: 1.5;
    color: #4b5563;
  }
  .engage-grid .engage-bestfor strong {
    color: #2563eb;
  }

  .cta-panel {
    background: linear-gradient(135deg, rgba(37, 99, 235, 0.08), rgba(124, 58, 237, 0.08));
    border: 1px solid rgba(37, 99, 235, 0.2);
    border-radius: 1.25rem;
    padding: 1.75rem;
    margin: 0 0 2rem;
    text-align: center;
  }
  .cta-book {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: #2563eb;
    color: #fff !important;
    font-weight: 700;
    font-size: 1.02rem;
    padding: 0.85rem 1.6rem;
    border-radius: 0.85rem;
    text-decoration: none !important;
    box-shadow: 0 10px 28px rgba(37, 99, 235, 0.28);
    transition: background 0.2s ease, transform 0.2s ease, box-shadow 0.2s ease;
  }
  .cta-book:hover {
    background: #1d4ed8;
    transform: translateY(-2px);
    box-shadow: 0 14px 36px rgba(37, 99, 235, 0.35);
  }
  .cta-direct {
    margin: 1.1rem 0 0;
    font-size: 0.98rem;
    color: #4b5563;
  }

  .wwm-table table {
    width: 100%;
    border-collapse: collapse;
    margin: 0;
  }
  .wwm-table thead {
    display: none;
  }
  .wwm-table td {
    padding: 0.85rem 1rem;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08);
    vertical-align: top;
    font-size: 0.95rem;
  }
  .wwm-table tr td:first-child {
    width: 32%;
    color: #2563eb;
    font-weight: 700;
    white-space: nowrap;
  }
  .wwm-table tr:last-child td {
    border-bottom: none;
  }

  @media (prefers-color-scheme: dark) {
    .engage-grid .engage-card {
      background: rgba(17, 24, 39, 0.9);
      border-color: rgba(55, 65, 81, 0.5);
    }
    .engage-grid .engage-card:hover {
      border-color: rgba(96, 165, 250, 0.4);
      box-shadow: 0 16px 48px rgba(96, 165, 250, 0.12);
    }
    .engage-grid .engage-icon {
      background: rgba(96, 165, 250, 0.12);
      border-color: rgba(96, 165, 250, 0.3);
      color: #60a5fa;
    }
    .engage-grid .engage-tag {
      background: rgba(96, 165, 250, 0.12);
      border-color: rgba(96, 165, 250, 0.35);
      color: #60a5fa;
    }
    .engage-grid .engage-lead,
    .engage-grid .engage-bestfor {
      color: #9ca3af;
    }
    .engage-grid .engage-list li {
      color: #d1d5db;
    }
    .engage-grid .engage-list li::before,
    .engage-grid .engage-bestfor strong {
      color: #60a5fa;
    }
    .cta-panel {
      background: linear-gradient(135deg, rgba(96, 165, 250, 0.1), rgba(167, 139, 250, 0.1));
      border-color: rgba(96, 165, 250, 0.25);
    }
    .cta-direct {
      color: #9ca3af;
    }
    .wwm-table td {
      border-color: rgba(255, 255, 255, 0.1);
    }
    .wwm-table tr td:first-child {
      color: #60a5fa;
    }
  }

  @media (max-width: 640px) {
    .engage-grid {
      grid-template-columns: 1fr;
    }
    .wwm-table tr td:first-child {
      white-space: normal;
    }
  }
</style>

<p class="wwm-subtitle">Two ways to engage — both remote-first, both results-focused.</p>

<div class="engage-grid"><div class="engage-card"><div class="engage-head"><span class="engage-icon"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg></span><span class="engage-tag">Dev</span></div><h2 class="engage-title">Custom Polarion Development</h2><p class="engage-lead">You need a feature built. I take it from spec to production.</p><ul class="engage-list"><li>Custom Polarion extensions: Java, REST API, Velocity templates, workflow rules</li><li>CI/CD pipelines with automated release documentation (GitHub Actions, Jenkins, Maven)</li><li>AI-assisted development — same quality, faster delivery</li><li>Full lifecycle: requirements, architecture, implementation, testing, deployment</li></ul><p class="engage-bestfor"><strong>Best for:</strong> Teams who know what they need and want a senior developer who delivers without hand-holding.</p></div><div class="engage-card"><div class="engage-head"><span class="engage-icon"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg></span><span class="engage-tag">Enablement</span></div><h2 class="engage-title">Coaching &amp; AI Adoption</h2><p class="engage-lead">Your team has Polarion (or Siemens Polarion X / Copilot) and isn't getting the ROI from it. I run hands-on assessments and coaching sprints that change that.</p><ul class="engage-list"><li>Workflow assessment: where is your team actually losing time in Polarion?</li><li>AI toolchain setup: practical integration of AI into daily Polarion work</li><li>Team coaching sprints: hands-on, not slide-deck-driven</li><li>Built on the same methodology behind avaCopilot</li></ul><p class="engage-bestfor"><strong>Best for:</strong> Teams or individuals who want to get more out of the tools they already have.</p></div></div>

## How to work together

<div class="cta-panel"><!-- TODO: Replace the Calendly URL below with Phillip's real booking link --><a href="https://calendly.com/" target="_blank" rel="noopener noreferrer" class="cta-book">📅 Book a free 30-minute intro call</a><p class="cta-direct">📩 Or reach out directly: <a href="mailto:digital@boesger.com">digital@boesger.com</a> · <a href="https://www.linkedin.com/in/phillip-boesger-90691215a/" target="_blank" rel="noopener noreferrer">LinkedIn</a></p></div>

## Working Style

<div class="wwm-table">

| | |
|---|---|
| **Availability** | Available now · Up to 30h/week |
| **Location** | Remote (DACH) · Up to 20% on-site for workshops/kickoffs |
| **Communication** | Async-first, regular syncs on request |
| **Languages** | German · English |

</div>

## Values

Honest over polished. If something is off, I'll say so early rather than push through. I prefer raising concerns over silently missing a deadline.
