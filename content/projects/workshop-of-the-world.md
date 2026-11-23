---
title: Workshop of the World
projectKind: case-study
caption: Eight Philadelphia backgrounds. One exit door sent me back to the easel.
image: images/workshop-of-the-world_project-image_1800x1200.jpg
alt: A painted side-scrolling background of an empty El platform at dusk, with
  mill roofs and a refinery behind it.
year: 2025–present
role: Sole artist; Godot demo
tags:
  - Photoshop
  - Godot
  - background painting
  - colour script
sections:
  - heading: Problem
    text: Philadelphia was once called the Workshop of the World. I wanted to paint
      eight scenes of it (rowhouse roofs, a shuttered textile mill, a refinery
      at dusk, an empty El platform) as backgrounds for an imagined
      side-scrolling exploration game. Each one has to work as a painting and
      still lead a player's eye to the path and the way out.
  - heading: Research
    image: images/workshop-of-the-world_section-research_1200x900.jpg
    alt: A photograph from a walk along the Delaware riverfront, with a shuttered
      mill and the El in the distance.
    text: "I started with photo walks in Philadelphia and Oxford, then went back to
      the painters I'd been borrowing from: Sheeler's clean industrial planes,
      de Chirico's long shadows and empty squares, and Matisse's flat blocks of
      colour for the skies."
  - heading: Prototype
    image: images/workshop-of-the-world_section-prototype_1200x300.jpg
    alt: "A colour script: a strip of eight small paintings showing the light moving
      from morning to night across the scenes."
    text: "For each scene I made about 30 value thumbnails before choosing one. Then
      I painted a colour script for the whole set: one strip that shows how the
      light moves from morning to night across the eight scenes."
  - heading: Layout and paint
    image: images/workshop-of-the-world_section-layout-and-paint_1200x675.jpg
    alt: A background separated into foreground, playfield and parallax layers, with
      the walkable line and a character's height marked.
    text: I drew each layout over a rough perspective guide, with a quick Blender
      blockout only where the perspective got complicated. The final paint is in
      Photoshop, split into foreground, playfield and parallax layers, with the
      walkable line and the character's scale marked. Each background is 3840 ×
      2160 and took 25 to 35 hours by my time log. I built a small Godot demo so
      people could walk through the scenes, not just look at them. I caught one
      mistake only when I walked the El platform. The station name slid off its
      sign as the camera moved. I'd put the letters on the skyline layer. Moving
      them onto the platform kept the sign bolted together.
  - heading: Iteration
    image: images/workshop-of-the-world_section-iteration_1200x1350.jpg
    alt: "Scene 3 twice at the same crop: above, bright mill windows; below, windows
      closer to the brick and light on the exit door at street level."
    text: >-
      In a five-person eye-tracking pilot, run with permission in the lab where
      I work, players missed the exit door in Scene 3. I had given the mill
      windows the lightest value in the painting, then wondered why people were
      looking up there when the way out was at street level.


      Scene 3, first pass and repaint. I brought the mill windows closer to the
      value of the brick so the brightest edge at street level belongs to the
      exit. My first correction lit up the entire door. At game scale it looked
      pasted on. In the repaint the door is almost as dark as the wall. All I
      kept was the blade of daylight along the jamb.
  - heading: Outcome
    image: images/workshop-of-the-world_section-outcome_900x1200.jpg
    alt: A handwritten tally sheet counting players at the expo demo.
    text: About 60 people played the demo at the department expo in spring 2026, by
      my tally sheet. The pilot prompted the repaint; whether the repaint works
      is still open, and a second test is next.
  - heading: Reflection
    text: The scenes are nearly empty of props. Modernism taught me to leave clutter
      out; now I'm learning to put lived-in clutter back without losing the
      path.
weight: 1
---
Eight 2D backgrounds of industrial Philadelphia, painted as parallax layers for an imagined side-scrolling exploration game and walked through in a small Godot demo. This page follows them from photo walks to a repaint that an eye-tracking pilot prompted.