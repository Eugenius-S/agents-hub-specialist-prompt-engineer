---
name: visual-prompts
description: Prompts for image and video generators (Midjourney, GPT Image, Nano Banana, Kling, Veo and others) from an analysis of the specific object, with no template. Use when you need to write, rewrite or fix prompts for an image or a video from a source (clay, color zones, a render, a brief), or when the owner approved a prompt and the rest must be made.
---

# Visual prompts

A prompt is a conclusion from an analysis of the specific object, not a filled-in frame. What prompts of different objects may share is only the constants the owner set (parameters, background, sref, language) and facts about the engine. Everything else in each prompt comes from its object.

## 1. Inputs

- Open each source separately. If there is no picture or no choice from the owner, stop for that object.
- The frame lives where the owner sees it (the object's final folder at the requester). If you were sent a path into a temporary or dated subfolder, ask to put the frame into the final one.
- Write out the series frame: parameters, background, language, style. The source is the project's style skill, the project files and the owner's words. The frame is not the text of a prompt. Project guides with "samples" and "templates" are a history of observations: take facts from them, not the structure.
- The series requirements go into every prompt by meaning but in your own words (for example: a white background with no shadows and no reflection on the floor, sharpness, "no new materials and objects").
- Take the colors of the parts as they are on the frame. Do not add details that are not on the frame without the owner's word.
- What the input is:
  - clay: there are no materials, the prompt assigns them;
  - color zones: there is color, the prompt assigns the material;
  - a finished render: the materials are visible, the prompt only improves.

  The input decides what the prompt must say. A simple prompt that worked on a render will not work on clay.

## 2. Analysis of the object: before the first prompt

Briefly, into the task record (`hub task note`), not into the prompts file, which holds only prompts:
- what the thing is, what it does and what the viewer should feel;
- **how such things were really made:** 3–5 real prototypes of this thing from the style's era, what the body and parts were made of, which special editions and runs came out. A gamepad: transparent bodies with a visible board, rubberized grips, limited chrome and glow-in-the-dark editions. If you do not know, search the web, do not invent;
- **how it would be cool:** from the prototypes and the meaning of the thing, 6–8 material ideas: "what if it had been released like this". An idea is a whole version of the entire object (body, main parts, filling) with its own reason in this thing. Jelly on a food item, because it is food; jelly on a gamepad, an accident;
- the parts by zones of the picture. For each: its purpose, what such a part is made of in the real thing and what the style gives it. For key parts, 2–3 candidates with a reason ("the cassette window is clear plastic: you can see the tape");
- check neighbors for contrast of textures: smooth and ribbed, gloss and matte, metal and plastic. One part has one material: a body that "tries to be glass and chrome and glow at once" is a defect;
- engine risks on this object: what it will wash out, what it will mix up, where a mention of a color will spread. For each risk, how you hold it in the prompt. For example, a translucent body drifts to pastel: in the prompt you hold the depth of color in the thickness;
- do not leave transparent parts empty: there is always something inside, glitter, gel with little stars, a board, a picture tube. An empty transparent panel comes out as a flat pastel icon.

## 3. Material ideas

- Per object, 5 prompts, 5 different material ideas from the analysis, unless the owner named another N. An idea changes the material of the body and the main parts, not one button.
- Variants that differ only in light, render or background are forbidden. Failure: five prompts with one material paragraph: studio, backlight, three-point, gels, sun.
- Light and render are not an axis of variants. In each prompt, one light that shows the material of that idea best: transparent with filling, backlight; solid gloss, catalog flash (what the engine already handles well is in engines.md). The heading names the material idea, not the light. Prompt numbers are digits only (`### MJ-<number>. <idea>`), variations take the following numbers: the sending scripts pick a prompt by number.
- At least one idea is an experiment: a material or an idea the series has not had yet. Something already tried and not chosen is not an experiment; check the series files.
- The idea stays within the series' style code (the project's style skill). Materials of another era and craft, where the style does not know them, are not an idea but a departure from the style.
- The series' usual materials only if the analysis of this thing demands them, and no more than one such idea per object.
- Exception: the owner directly asks to "play with light and render" on an approved prompt; then you do not touch the materials, you change the light and the engine. Only on the owner's words.
- An idea that needs a new part (a dome, packaging, a stand) does not go into a frame-edit prompt: "No new objects" cuts it, and without it the engine invents at random. Write to whoever makes the frame so they build it into the source.
- Structure and length fit the idea: somewhere three sentences are enough, somewhere a list of parts is needed.
- **Check before hand-over:** write out the object's ideas one per line (in `hub task note`).
  1. Two ideas have the same body material (only the filling, color or highlight differs): rewrite one.
  2. An idea = a finding of the object + the style code. The style's material families repeat between objects; that is no coincidence. The coincidence to catch is a shared finding: a heading that fits another object of the series without edits. Compare with the headings of objects already written: if an idea is like that, rewrite it from the analysis of this thing.
  3. Whole phrases match other prompts, apart from the frame: rewrite.
  4. For each idea name the reason in this thing in one phrase. "Cool", "fits the era", "a material from another industry" are not a reason. No reason: replace the idea.
  5. Risk words from engines.md (pearl, frost, "bubblegum", "ice-blue", negations that name a color): remove them or hold the risk another way.

## 4. A successful prompt is a lesson, not a template

The owner approved a prompt or gave their own:
1. Name in one line why it worked on that object and that input.
2. Carry over the principle, not the text. Whether it applies to the next object is decided by the analysis of that object.
3. A new principle goes first to one object; show it. The rest after a "yes".
4. What was approved is a fact about one object of one style, not a "default" technique. Do not use it more often because it passed. Do not carry observations of one style over to another.
5. Save approved prompts verbatim in the object's file. Delete the rest of the batch only when the owner rejected them or closed the batch: "this one is good" does not mean "the rest are trash".
6. **Collect the successful ones yourself.** A successful one is the prompt of a picture the owner took into the final or chose, and the prompts the owner sent themself. In the same turn append to `references/approved-<style>.md` (create it if missing): `## <Object>, MJ-n, <date>`, the path to the frame and the final, the prompt verbatim, one "why it worked" line, based on what is visible in the final, not on the prompt text. Failed ones go into `references/rejected-<style>.md`: "meh" (not chosen) is a weak signal, "negative" (the owner said it is bad) comes with the owner's words verbatim and a "what did not work" line. Before analyzing a new object of a style, read both files as facts, not as a frame. If a finding repeats in many successful ones, put it in engines.md as a line, with the objects.
7. Do not assemble a series' prompts with a script from a common frame. Failure: in seconds, seven objects got one formula "<body>: translucent deep saturated <color> plastic…" and an identical tail.

## 5. The owner's remark

- Only what is named changes. A complaint about an object's result means you edit that object's prompt. Do not touch frames, sources and other objects; the general style and the skill change only on the words "for all".
- The owner's words are inputs, not ready text. "Brighter" means finding what in this prompt causes the paleness, not inserting "bright" into all of them.
- The same remark a second time: do not patch it with a phrase, change direction.
- Do not derive a general rule from one choice in a form.
- "The visuals changed, rewrite the prompts": write the object's prompts anew from the new frame: open it, make a new analysis, replace this object's old prompts, do not patch them.
- Grids repeat the frame a second round in a row: words in an edit prompt do not override the material of an already colored frame. Do not write a third round in words: change the lever (another engine, a recolor of the frame, a prompt without "keep every detail" that holds only shape, angle and composition) or tell the requester what ran into the frame.

## 6. Engine and kind of work

- Facts about engines are in [references/engines.md](references/engines.md). They are observations with a reason, not phrases to copy.
- Video (Kling, Veo, Seedance, Runway): analysis first: what in the frame can move, how and why. Write by the `video` and `kling-video-prompts` skills, if granted.
- GPT Image and Nano Banana pictures go by the `image` skill, if granted.

## 7. Hand-over

- Prompts go into the object's file in the project folder; the path is by the rules of the project or of whoever asked. The analysis goes to `hub task note`.
- In chat: the full path to the file and one line per idea. Do not dump walls of prompts into chat.
- The requester or the owner sends the prompts to the generator; you do not launch generators or publishing yourself.

## 8. The skill is alive

You agreed something new with the owner (a rule, a format, a technique, what they approved or rejected): in the same turn edit this file or engines.md, in place of the outdated text, with no "currently valid" layers.
