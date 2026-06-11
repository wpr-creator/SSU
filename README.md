# U.S. History — OCS Summer School
### Course Hub · `index.html`

---

## Overview

This is the student-facing landing page for the OCS Summer School U.S. History course (Standards 11.1–11.11). It displays all lesson cards for both semesters and is designed to be opened directly in a browser — no server required.

---

## Structure

```
/
├── index.html          ← Main course hub (this file)
├── README.md           ← This file
└── images/
    └── header_US.jpg   ← Hero banner image (see below)
```

---

## Lesson Files

Each card links to a standalone lesson HTML file. Naming convention:

| Pattern       | Example        | Meaning                     |
|---------------|----------------|-----------------------------|
| `SSU_S1Lxx`   | `SSU_S1L05.html` | Semester 1, Lesson 05     |
| `SSU_S2Lxx`   | `SSU_S2L09.html` | Semester 2, Lesson 09     |

### Semester 1 — Founding Era Through the New Deal (Standards 11.1–11.6)

| Day | File            | Title                                           | Standard(s)         |
|-----|-----------------|-------------------------------------------------|---------------------|
| 1   | SSU_S1L01.html  | Founding the Nation                             | 11.1                |
| 2   | SSU_S1L02.html  | Industrialization and Immigration               | 11.2                |
| 3   | SSU_S1L03.html  | Populism, Progressivism, and Religion           | 11.2–11.3           |
| 4   | SSU_S1L04.html  | America Becomes a World Power                  | 11.4                |
| 5   | SSU_S1L05.html  | The Roaring Twenties                            | 11.5 pt. 1          |
| 6   | SSU_S1L06.html  | Civil Liberties Under Pressure                 | 11.5 pt. 2          |
| 7   | SSU_S1L07.html  | The Great Depression                            | 11.6 pt. 1          |
| 8   | SSU_S1L08.html  | The New Deal and Labor                          | 11.6 pt. 2          |
| 9   | SSU_S1L09.html  | The New Deal, Labor, and the Legacy of Federal Power | 11.6 continued |
| 10  | SSU_S1L10.html  | **Semester 1 Final**                            | 11.1–11.6           |

### Semester 2 — WWII Through Modern America (Standards 11.7–11.11)

| Day | File            | Title                                           | Standard(s)         |
|-----|-----------------|-------------------------------------------------|---------------------|
| 1   | SSU_S2L01.html  | America in World War II                         | 11.7 pt. 1          |
| 2   | SSU_S2L02.html  | The American Home Front and Hard Choices        | 11.7 pt. 2          |
| 3   | SSU_S2L03.html  | Post-War Boom and the New America               | 11.8                |
| 4   | SSU_S2L04.html  | The Cold War at Home and Abroad                 | 11.9 pt. 1          |
| 5   | SSU_S2L05.html  | Cuba, Vietnam, and Cold War Escalation          | 11.9 pt. 2          |
| 6   | SSU_S2L06.html  | The Civil Rights Movement                       | 11.10 pt. 1         |
| 7   | SSU_S2L07.html  | Expanding Civil Rights and Social Movements     | 11.10 pt. 2         |
| 8   | SSU_S2L08.html  | Modern America and Unfinished Business          | 11.11               |
| 9   | SSU_S2L09.html  | America After the Cold War                      | 11.11 continued     |
| 10  | SSU_S2L10.html  | **Semester 2 Final**                            | 11.7–11.11          |

---

## Card Display Logic

Cards are intentionally **reordered each day** to put the current lesson first:

- **Today's card** (Day 5) appears first with a red `TODAY` badge and a highlighted border glow
- **Upcoming cards** (Days 6–9) follow in order
- **Completed cards** (Days 1–4) appear at the end, slightly muted
- **Day 10 Final** always appears last

To update for a new day, adjust the card order in `index.html` and change the "today" class and progress pip count accordingly.

---

## Header Image

```
FILENAME:  header_US.jpg
FOLDER:    images/
SOURCE:    Wikimedia Commons
URL:       https://commons.wikimedia.org/wiki/File:Declaration_of_Independence_(1819),_by_John_Trumbull.jpg
```

"Declaration of Independence" by John Trumbull (1819) — the painting in the U.S. Capitol Rotunda and on the back of the $2 bill. Download the full-size JPG and save as `images/header_US.jpg`.

If the image is missing the hero will fall back to a solid navy background.

---

## Design Notes

- **Fonts**: Barlow Condensed (headings/labels) + Barlow (body) via Google Fonts
- **Colors**: Pastel red (`#b84040`), navy (`#1c2b45`), and clean white — patriotic without being loud
- **JS enhancements**:
  - Scroll-progress bar (top of page)
  - Session progress pips strip (Day X of 10)
  - Intersection Observer scroll-reveal on cards
  - Floating particle animation in hero
- No build tools or dependencies — open `index.html` directly in any browser

---

*OCS Summer School · Social Science · SSU*
