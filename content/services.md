---
title: "Working With Me"
description: "What to expect when working with Bösger Digital – availability, remote-first collaboration and values."
---

<style>
  .collab-flex {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    margin-bottom: 1.5rem;
    flex-wrap: wrap;
  }
  .collab-box {
    background: rgba(255, 255, 255, 0.9);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 1.25rem;
    padding: 1.5rem;
    margin-bottom: 1rem;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
    flex: 1 1 280px;
    min-width: 260px;
    transform: translateY(0);
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
    isolation: isolate;
  }
  .collab-box::before {
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
  .collab-box:hover::before {
    left: 100%;
  }
  .collab-box:hover {
    transform: translateY(-6px);
    box-shadow: 0 16px 48px rgba(37, 99, 235, 0.15);
    background: rgba(255, 255, 255, 0.95);
    border-color: rgba(37, 99, 235, 0.3);
  }
  .collab-icon {
    font-size: 2.2rem;
    margin-bottom: 0.6rem;
    display: block;
    position: relative;
    z-index: 1;
    transition: transform 0.3s ease;
  }
  .collab-box:hover .collab-icon {
    transform: translateY(-4px);
  }
  .collab-title {
    font-size: 1.12rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
    line-height: 1.3;
  }
  .values-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin: 1.25rem 0;
  }
  .value-chip {
    background: rgba(37, 99, 235, 0.1);
    border: 1px solid rgba(37, 99, 235, 0.3);
    color: #2563eb;
    border-radius: 2rem;
    padding: 0.4rem 1.1rem;
    font-weight: 600;
    font-size: 0.98rem;
    transition: all 0.2s ease;
  }
  .value-chip:hover {
    background: rgba(37, 99, 235, 0.18);
    transform: translateY(-2px);
  }
  @media (prefers-color-scheme: dark) {
    .collab-box {
      background: rgba(17, 24, 39, 0.9);
      border-color: rgba(55, 65, 81, 0.5);
      color: #f3f4f6;
    }
    .collab-box:hover {
      background: rgba(17, 24, 39, 0.95);
      border-color: rgba(96, 165, 250, 0.4);
      box-shadow: 0 16px 48px rgba(96, 165, 250, 0.1);
    }
    .value-chip {
      background: rgba(96, 165, 250, 0.12);
      border-color: rgba(96, 165, 250, 0.35);
      color: #60a5fa;
    }
    .value-chip:hover {
      background: rgba(96, 165, 250, 0.2);
    }
  }
  @media (max-width: 700px) {
    .collab-flex {
      flex-direction: column;
      gap: 1.2rem;
      margin: 0;
      padding: 0;
    }
    .collab-box {
      padding: 1.2rem;
      margin-bottom: 1rem;
      min-width: unset;
      flex: 1 1 auto;
      width: 100%;
      box-sizing: border-box;
    }
    .collab-title {
      font-size: 1.05rem;
    }
    h1, h1#title, h1.title, h1:first-child {
      font-size: 1.35rem !important;
      padding: 0 1rem;
    }
    .cta-white {
      font-size: 1.75rem !important;
      padding: 0 1rem;
    }
    .cta-white a {
      font-size: 2.25rem !important;
    }
  }
  @media (max-width: 480px) {
    .collab-box {
      padding: 1rem;
      margin-bottom: 0.8rem;
      border-radius: 1rem;
    }
    .collab-title {
      font-size: 1rem;
    }
    h1, h1#title, h1.title, h1:first-child {
      font-size: 1.2rem !important;
    }
    .cta-white {
      font-size: 1.5rem !important;
    }
    .cta-white a {
      font-size: 1.8rem !important;
    }
  }
  h1.title, h1#title, h1:first-child {
    display: none !important;
  }
  .cta-white {
    color: #fff !important;
    text-shadow: 0 2px 8px rgba(0,0,0,0.18);
  }
</style>

Collaboration should be straightforward, reliable and built on trust. Here's what you can expect when we work together.

<div class="collab-flex">
  <div class="collab-box">
    <span class="collab-icon">🗓️</span>
    <div class="collab-title">Availability</div>
    I work up to 30 hours per week. That scope allows me to go deep and deliver real results – without spreading thin across too many parallel commitments.
  </div>
  <div class="collab-box">
    <span class="collab-icon">🌍</span>
    <div class="collab-title">Remote-First by Design</div>
    I work remotely from wherever I am in the world. That's not a limitation – it's how I do my best, most focused work. Whenever on-site presence makes sense, especially for workshops or project kickoffs, we can make it happen.
  </div>
  <div class="collab-box">
    <span class="collab-icon">📡</span>
    <div class="collab-title">Always Reachable</div>
    No matter where I'm working from, communication and coordination are always possible. Regular syncs, async updates, structured handoffs – whatever rhythm works best for your team.
  </div>
  <div class="collab-box">
    <span class="collab-icon">🔧</span>
    <div class="collab-title">Adaptable by Nature</div>
    Requirements shift. Priorities change. Unexpected things come up. That's normal in real engineering work. I don't need everything defined upfront – as long as we communicate openly, we can figure things out together.
  </div>
</div>

## My Values

These aren't buzzwords. They're the things I actually try to live by in every engagement.

<div class="values-row">
  <span class="value-chip">Openness</span>
  <span class="value-chip">Communication</span>
  <span class="value-chip">Transparency</span>
  <span class="value-chip">Quality</span>
</div>

I prefer honest conversations over polished status updates. If something's off, I'll say so. If I need more context, I'll ask. I'd rather raise a concern early than silently push through something that doesn't feel right.


