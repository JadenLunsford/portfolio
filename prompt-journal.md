# Prompt Journal

Log your Copilot prompts here as you work. This is your record of the prompting process — not just what worked, but what didn't, and how you iterated.

**There are no wrong answers here.** The goal is to practice prompt writing and reflect on it honestly.

---

## How to fill this in

For each entry, note:
- **Where** you used Copilot (inline chat, Ask mode, Edit mode, Agent mode, inline completion)
- **What you asked** (copy/paste the prompt if you can)
- **What you got** (brief summary — did it work? was it close? way off?)
- **What you changed** (did you refine the prompt? edit the output manually?)

---

## Phase 1 — Setup & Orientation

### Entry 1
- **Feature/task:** Hero heading text
- **Copilot feature used:** Agent mode
- **Prompt:**
  > can you edit the code so that it says Hello, my name is Jaden lunsford. keep the waving hand as well and put ttwo exclamation markss behind the waving hand
- **Result:** It updated the hero heading correctly and kept the waving hand at the end.
- **What I changed or did next:** I later refined the hero area with a typing effect and image swaps.

---

## Phase 2 — Guided Tasks

### Entry 2 — About section
- **Copilot feature used:** Agent mode
- **Prompt:** For the about me section can you swap the camera icon with the dancingsonic in the images folder.
- **Result:** It properly added the gif image to the about me section.
- **What I changed or did next:** I kept the circular image layout and later swapped in the actual photo file.

---

### Entry 3 — Projects
- **Copilot feature used:** Agent mode
- **Prompt:**
  > In the projects section, can you add the book.gif as an image right next to the word projects in the header. without throwing off the code and messing it up.
- **Result:** It added the GIF next to the Projects heading without changing the grid layout.
- **What I changed or did next:** I adjusted the icon sizing so the heading stayed aligned.

---

### Entry 4 — Dark mode
- **Copilot feature used:** Ask mode
- **Prompt:** There was a dark mode toggle button that was added and a dark mode theme. The button is there but when it is pressed dark mode is toggled. could you scan the code to identify why the dark mode theme is unresponsive.
- **Result:** It correctly identified the selector mismatch in the code.
- **What I changed or did next:** I switched to agent mode and had it update the theme logic.

---

### Entry 5 — Responsive layout
- **Copilot feature used:** Agent mode
- **Prompt:**
  > can you add the lightmode image in the image file to the background of the hero section when light mode is toggled instead of the current background. can you also add the darkmode image in the image file to the background of the hero section when dark mode is toggled.
- **Result:** It switched the hero background to different images based on the current theme.
- **What I changed or did next:** I corrected the filenames and folder capitalization so the images could load properly.

---

## Phase 3 — Independent Feature

**Feature I chose:** Hero text animation and image swaps

### Entry 6
- **Copilot feature used:** Agent mode
- **Prompt:**
  > can you add this, without throwing off the code
- **Result:** It added the type-on effect for the hero name without changing the rest of the page.
- **What I changed or did next:** I kept the animation limited to the name so the line length and layout stayed stable.

### Entry 7
- **Copilot feature used:** Agent mode
- **Prompt:**
  > can you add a photo to the camera icon in the about me section. Use aboutme.jpg in the Images folder.
- **Result:** It swapped the placeholder camera icon for the image in the About Me section.
- **What I changed or did next:** I kept the circular image styling and adjusted the size so it fit the layout.

### Entry 8 — A prompt that didn't work well
- **Copilot feature used:** Agent mode
- **What I asked:**
  > I just saved an image into the file titled background image, can you set it as he image?
- **What went wrong:** The image was not actually in the expected folder yet, so the first attempt could not load it.
- **How I fixed it (revised prompt or manual edit):** I moved the file into the Images folder and updated the CSS path to match the exact filename and folder name.

---

## Reflection

**1. What feature are you most proud of?**

I am most proud of the hero section because it now feels customized and polished without breaking the rest of the starter code. The name types in, the background changes with the theme, and the text still reads clearly over the image.

---

**2. Describe a time Copilot gave you something wrong or unhelpful. What did you do?**

*(Be specific — this is one of the most valuable things to reflect on.)*

---

**3. What did you learn about writing better prompts?**

*(What made a prompt work well? What made one fail?)*

---

**4. What's one part of the codebase you now understand better than at the start?**

---

**5. What would you build or improve next?**
