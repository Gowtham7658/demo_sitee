---
layout: default
title: Home
---

<div style="max-width: 1000px; margin: 0 auto;">
    <h1 class="home-title">{{ site.title }}</h1>
    <p class="home-subtitle">{{ site.description }}</p>
    
    <div class="card-grid">
        <a href="{{ '/wiki/technical-architecture/' | relative_url }}" class="card">
            <h3>Technical Architecture</h3>
            <p>Explore the technical architecture patterns, blueprints, and design solutions for enterprise systems.</p>
        </a>
        <a href="{{ '/wiki/technical-patterns/' | relative_url }}" class="card">
            <h3>Technical Patterns</h3>
            <p>Comprehensive collection of reusable patterns and best practices for software design and development.</p>
        </a>
        <a href="{{ '/wiki/getting-started/' | relative_url }}" class="card">
            <h3>Getting Started</h3>
            <p>Quick start guide to begin using the documentation and understanding the architecture framework.</p>
        </a>
        <a href="{{ '/wiki/introduction/' | relative_url }}" class="card">
            <h3>Introduction</h3>
            <p>Overview of the entire project and the approach to technical documentation and knowledge sharing.</p>
        </a>
    </div>
</div>