---
layout: page
title: Art
permalink: /photos/
nav: true
nav_order: 5
images:
  lightbox2: true
---

<style>
  /* Masonry Grid */
  .grid {
    /* Masonry is handled by JS, so we just need to ensure items are sized correctly */
    margin: 0 auto;
  }

  .grid-item {
    width: 100%; /* Mobile first: 1 column */
    margin-bottom: 20px;
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    background-color: #f5f5f5;
  }

  @media (min-width: 768px) {
    .grid-item {
      width: 32%; /* Desktop: 3 columns with some gap space */
    }
    .grid-item--width2 {
      width: 64%; /* Spans 2 columns */
    }
  }

  .grid-item:hover {
    transform: scale(1.02);
    z-index: 1; /* Ensure hovered item is on top */
  }

  .grid-item a {
    display: block;
    cursor: zoom-in;
  }

  .grid-item img {
    width: 100%;
    height: auto;
    display: block;
    /* Natural height, no object-fit or aspect-ratio forced */
  }

  .photo-caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 10px;
    transform: translateY(100%);
    transition: transform 0.3s ease;
    text-align: center;
    font-size: 0.9em;
    pointer-events: none; /* Allow clicks to pass through to the link */
  }

  .grid-item:hover .photo-caption {
    transform: translateY(0);
  }
</style>

<div class="grid">
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/girl.jpeg' | relative_url }}" data-lightbox="photos" data-title="Digital Art">
      <img src="{{ '/assets/img/arts/girl.jpeg' | relative_url }}" alt="Digital Art">
    </a>
    <div class="photo-caption">Digital Art</div>
  </div>
  <div class="grid-item grid-item--width2">
    <a href="{{ '/assets/img/arts/old_man.png' | relative_url }}" data-lightbox="photos" data-title="Oil Painting">
      <img src="{{ '/assets/img/arts/old_man.png' | relative_url }}" alt="Oil Painting">
    </a>
    <div class="photo-caption">Oil Painting on Canvas</div>
  </div>
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/tree.jpeg' | relative_url }}" data-lightbox="photos" data-title="Oil Painting: &quot;Serenity&quot;">
      <img src="{{ '/assets/img/arts/tree.jpeg' | relative_url }}" alt="Oil painting">
    </a>
    <div class="photo-caption">Oil Painting on Canvas</div>
  </div>
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/stair.jpeg' | relative_url }}" data-lightbox="photos" data-title="Oil Painting">
      <img src="{{ '/assets/img/arts/stair.jpeg' | relative_url }}" alt="Oil Painting">
    </a>
    <div class="photo-caption">Oil Painting on Canvas</div>
  </div>
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/fruit.jpeg' | relative_url }}" data-lightbox="photos" data-title="Oil Painting">
      <img src="{{ '/assets/img/arts/fruit.jpeg' | relative_url }}" alt="Oil Painting">
    </a>
    <div class="photo-caption">Oil Painting on Canvas</div>
  </div>
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/clock.jpeg' | relative_url }}" data-lightbox="photos" data-title="Oil Painting">
      <img src="{{ '/assets/img/arts/clock.jpeg' | relative_url }}" alt="Oil Painting">
    </a>
    <div class="photo-caption">Oil Painting on Canvas</div>
  </div>
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/dinner.jpeg' | relative_url }}" data-lightbox="photos" data-title="Oil Painting: &quot;Dinner&quot;">
      <img src="{{ '/assets/img/arts/dinner.jpeg' | relative_url }}" alt="Digital Art">
    </a>
    <div class="photo-caption">Digital Art: The Final Supper</div>
  </div>
  <div class="grid-item">
    <a href="{{ '/assets/img/arts/spongebob.jpeg' | relative_url }}" data-lightbox="photos">
      <img src="{{ '/assets/img/arts/spongebob.jpeg' | relative_url }}" alt="Digital Art">
    </a>
    <div class="photo-caption">Digital Art</div>
  </div>
</div>