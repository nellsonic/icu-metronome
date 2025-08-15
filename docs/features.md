---
title: ICU Metronome — Features Guide
---

## What this is

A metronome app that helps musicians progressively step up the tempo of all the segments of a difficult passage while interleaving them. This allows more effective learning—with lasting performance ready results. See the Resource Links on the main page for more information about Dr. Molly Gebrian, who invented this approach. A demonstration video can also be found there.

## Quick start

1. Set **Start Tempo**, **Target Tempo**, **Step Size** (metronome increment), and **Cycles** (how many segments you wish to work at once).
2. Adjust **Subdivision** and **Volume**, if desired.
3. Press **Generate** → then **Start**.
4. Use arrow keys to navigate (↑/↓ step, ←/→ cycle).  
   *(Keyboard legend hidden on small screens.)*

## Controls

- **Generate**: recomputes steps and cycles.
- **Start/Stop**: toggles playback.
- **Subdivision**: Quarters, 8th’s, Triplets, 16ths, 5’s, 6’s, 7’s.
- **Do not exceed Target Tempo**: Truncates the final step size if that step would exceed the Target Tempo.
- **Start segment**: Pick a segment (ideally near the middle of the passage). Cycles will expand outward from that point, providing a variable practice option. If left blank, cycles will start with segment 1 and add additional segments in forward order by default.
- **Backwards mode**: If checked, cycles start from the final segment and add in reverse. With a start segment selected, backwards mode reverses the usual order of additional segments being added around the start segment.
- **Silence subdivisions above**: Mutes subdivision clicks once the tempo passes the selected threshold, leaving only the main beats. This provides more rhythmic support at slower tempos versus more clarity at faster ones.
- **Link to midpoint**: Sets the silence subdivisions threshold to exactly halfway between the current Start and Target tempos. If Start or Target tempos are changed, the silence point updates automatically to remain centered between them. While checked, any manual change to the 'Silence subdivisions above' value is disabled.
