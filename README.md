# SSU — US History

A two-semester United States History course from the founding of the nation through modern America and unfinished business.

## Course Schedule

| Day | Title | Standards | EQ | Status |
|-----|-------|-----------|-----|--------|
| Semester 1 Day 1 | Founding the Nation | 11.1 | How did Enlightenment ideas shape a new kind of government, and does it still work? | Coming Soon |
| Semester 1 Day 2 | Industrialization and Immigration | 11.2 | How did industrialization transform who Americans were, where they lived, and what they could demand? | Coming Soon |
| Semester 1 Day 3 | Populism, Progressivism, and Religion | 11.2 continued and 11.3 | How did ordinary people and religious movements push America to live up to its own ideals? | Coming Soon |
| Semester 1 Day 4 | America Becomes a World Power | 11.4 | What pushed the United States from isolation to empire, and who paid the price? | Coming Soon |
| Semester 1 Day 5 | The Roaring Twenties | 11.5 pt 1 | How did prosperity, technology, and cultural explosion make the 1920s one of the most contradictory decades in American history? | Coming Soon |
| Semester 1 Day 6 | Civil Liberties Under Pressure | 11.5 pt 2 | How can a decade of prosperity also be a decade of fear and repression? | Coming Soon |
| Semester 1 Day 7 | The Great Depression | 11.6 pt 1 | How did economic collapse devastate American families and shake faith in the system? | Coming Soon |
| Semester 1 Day 8 | The New Deal and Labor | 11.6 pt 2 | How far should the government go to help people in a crisis, and did the New Deal go far enough? | Coming Soon |
| Semester 1 Day 9 | Final Exam | — | — | Coming Soon |
| Semester 2 Day 1 | America in World War II | 11.7 pt 1 | How did the attack on Pearl Harbor pull the United States into a war it had tried to avoid? | Coming Soon |
| Semester 2 Day 2 | The American Home Front and Hard Choices | 11.7 pt 2 | How did WWII transform American society at home, and were all the sacrifices equally shared? | Coming Soon |
| Semester 2 Day 3 | Post-War Boom and the New America | 11.8 | How did WWII change what American life looked like, and who got left out of the new prosperity? | Coming Soon |
| Semester 2 Day 4 | The Cold War at Home and Abroad | 11.9 pt 1 | How did fear of communism reshape American foreign policy and daily American life? | Coming Soon |
| Semester 2 Day 5 | Cuba, Vietnam, and Cold War Escalation | 11.9 pt 2 | Why did the United States fight wars in countries most Americans couldn't find on a map? | Coming Soon |
| Semester 2 Day 6 | The Civil Rights Movement | 11.10 pt 1 | How did ordinary Americans use law, protest, and personal sacrifice to change a country not living up to its own promises? | Coming Soon |
| Semester 2 Day 7 | Expanding Civil Rights and Social Movements | 11.10 pt 2 | How did the Black civil rights movement inspire other Americans to demand their own equality? | Coming Soon |
| Semester 2 Day 8 | Modern America and Unfinished Business | 11.11 | What major problems has America still not solved, and why does history matter for solving them? | Coming Soon |
| Semester 2 Day 9 | Final Exam | — | — | Coming Soon |

## File Naming Convention

HTML lesson files follow this pattern (zero-padded lesson numbers):

- Regular lessons: `SSU_S1L01.html` through `SSU_S1L08.html`
- Final exam: `SSU_S1L09_Final.html`
- Semester 2 uses `S2` instead of `S1` (e.g. `SSU_S2L01.html`, `SSU_S2L09_Final.html`)

## Image Folder and Naming Convention

Lesson images live under `images/` organized by semester and lesson:

```
images/
  S1/
    L01/
    L02/
    ...
    L08/
  S2/
    L01/
    ...
    L08/
```

Name image files: **`{Semester}{Lesson}_DescriptiveName.jpg`**

Example: `images/S1/L01/S1L01_Constitution.jpg`

See [images/README.md](images/README.md) for full details.

## Flipping a Lesson Live

On `index.html`, each day is a card with class `day-card`. The lesson link is already in place. To publish a lesson:

1. Open `index.html`
2. Find the card for that day
3. Add the class **`live`** — change `class="day-card"` to `class="day-card live"`

That is the only change required. Locked cards (without `live`) appear grayed out with a lock icon and are not clickable. Live cards use full styling, a hover effect, and link to the lesson HTML file.
