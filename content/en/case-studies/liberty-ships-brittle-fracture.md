---
title: "Liberty Ships: When Steel Turned Brittle"
date: 2026-10-07
description: "Why welded WWII cargo ships cracked — sometimes in two — in cold water, and what it taught engineers about fracture."
tags: ["fracture", "steel", "failure analysis", "welding"]
translationKey: "liberty"
math: true
---

<div class="callout"><p><strong>Sample case study.</strong> Use this as a template: keep the six headings, replace the content with your own analysis, or delete this file.</p></div>

## 1. Background

During the Second World War, the United States built around 2,700 *Liberty ships* — simple cargo vessels produced at record speed. A key innovation was replacing riveted hulls with **all-welded hulls**, which saved time and steel.

## 2. The problem

Many of these ships, and the related T2 tankers, developed serious cracks. Some fractured completely in two — in a few cases while sitting calmly in port. The failures were concentrated in **cold waters**, such as the North Atlantic in winter.

## 3. Materials and service conditions

| Factor | Condition |
|---|---|
| Material | Plain carbon ship steel of the era |
| Joining | Continuous welded hull |
| Temperature | Often near or below 0 °C |
| Geometry | Square hatch corners, abrupt section changes |

## 4. Analysis

Body-centred cubic steels show a **ductile-to-brittle transition**: above a certain temperature they deform and absorb energy before breaking; below it they fracture suddenly with little warning. The ship steel's transition temperature was close to the service temperature.

Fracture mechanics expresses the danger. A crack of length \(a\) under stress \(\sigma\) produces a stress intensity

$$K_I = Y\,\sigma\sqrt{\pi a}$$

and fast fracture occurs when \(K_I\) reaches the material's fracture toughness \(K_{IC}\). In the cold, \(K_{IC}\) dropped sharply — so cracks that would have been harmless in warm water became critical.

## 5. Root cause

A combination of three factors:

1. **Steel with poor low-temperature toughness** (high transition temperature).
2. **Stress concentrators** — square hatch corners and weld defects acted as crack starters.
3. **Welded, continuous structure** — unlike riveted plates, a weld gave a running crack an uninterrupted path through the hull.

Constance Tipper's research at Cambridge was central in showing that the steel itself, not just the welding, became brittle below a critical temperature.

## 6. Lessons

- Specify toughness at the *service* temperature (e.g. Charpy impact testing).
- Design out stress concentrations — round the corners.
- Add **crack arrestors** so a running crack cannot cross the whole structure.
- These lessons helped found modern fracture mechanics.
