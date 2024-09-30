---
tags:
  - npc
  - key_figure
  - timeline
  - sutel-history
npc_info:
  - cleric
  - masculine
aliases:
  - The Ruby Prince
  - Khemet the Third
---
**Location:** [[Sothis]], [[Palace of the Pharaoh]]
**Role:** Supreme ruler of [[Suthelia]] and High Priest of [[Teancri]]
**Disposition:** Indifferent
**Class:** Cleric (Light)

Demeanor and Character: 

Relations:
Notes: His real name is Pharao Khemet the Third

/* Render the ob-timelines span or div elements as inline blocks that use an italic font */
.ob-timelines { display: inline-block !important; font-style: italic; } 
/* Use the before pseudo element to display attributes of the span or div */ 
.ob-timelines::before { content: "🔖 " attr(data-date) ": " attr(data-title) ". "; color: lilac; font-weight: 500; }

<span class='ob-timelines' data-date='2000-10-10-00' data-title='Another Event' data-class='orange' data-img = 'Timeline Example/Timeline_2.jpg' data-type='range' data-end='2000-10-20-00'> /* Render the ob-timelines span or div elements as inline blocks that use an italic font */
.ob-timelines { display: inline-block !important; font-style: italic; } 
/* Use the before pseudo element to display attributes of the span or div */ 
.ob-timelines::before { content: "🔖 " attr(data-date) ": " attr(data-title) ". "; color: lilac; font-weight: 500; }
A second event! </span>