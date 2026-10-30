# Engines: observations

Each observation says what happened and on which object. Apply it when your object is in the same situation. When the engine version changes, recheck before relying on it. A new observation goes as a line into your engine's section, with the object and the date.

## Midjourney (picture edit: clay, color zones, render)

- A mention of a color or an effect pulls it onto the whole object, even with a negation: "no blue" gave blueness, "not highlights" gave highlights. Name a color once, on its own part. General negations ("no bounce light on the object", "no white haze") work.
- Paleness comes from "matte translucent", "mint", "pearl", "calm materials" and a white surrounding: MJ turns them into pastel and frost. Solid toy plastic comes from "rich saturated color" and "like candy".
- Pastel words: "bubblegum pink", "ice-blue", "mint" are light shades, and "hot" next to them does not save it. Saturated: "deep hot-pink", "deep sky-blue", and in a transparent one add "dark rich <color> in the thickness". Yellow drifts to cream even with "thick solid opaque": hold "rich egg-yolk yellow", "deep golden-yellow", "school-bus yellow, no cream".
- Light described as an object ("a top softbox") MJ may draw as a lampshade above the object. On objects with a dome or an open top, describe light as light.
- MJ complains about long prompts. A prompt cut in half that lost its materials is bad. Cut repeats, not materials; a working length is 90–150 words.
- A reference to the source's color ("gray tribals are chrome") is not read. "Hull: translucent violet plastic" (a part, a colon, a material) works. Name the part by meaning, not by its color on the frame.
- The series parameters (`--sref`, `--chaos`, prohibitions like `--iw`) are taken from the project verbatim; do not make "with sref and without" variants.
- A simple prompt ("put it on a white background, add ambient occlusion, improve the chrome and plastic") works on a finished render with visible materials. On clay the materials must be assigned.
- An empty transparent panel ("acrylic lit from within", "tinted glass" with no filling) comes out pastel with a white center, and the object a flat icon. Inside a transparent part there is always something: glitter in jelly, gel with sparkles, internals, cubes. The filling gives depth and color. Better still: colorless glass + solid colored details inside ("solid opaque bars… stay solid"): the color is carried by the solid detail, not by tinted glass.
- Light that MJ handles well: colored gels on transparent with chrome, backlight through transparent with meaningful internals, studio with a rim, three-point, catalog flash. Colored gels on a flat solid disc only dirty the color. "Bright clean / soft even light" gives a flat boring picture: take the light from the series' successful finals.
- Against glow and overexposure: "glowing", "sparkle", "backlight", "rim light", "crisp highlights", polish on large parts give halos. Large colored parts are satin or matte, glass "almost invisible", chrome "reflecting a dark grey studio", light "soft diffuse, a few small soft highlights". MJ washes glossy color out with a highlight; matte holds.
- Chrome "reflecting a dark grey studio" gives gray streaks; "mirroring white studio walls" with white gloss gives a corridor background made of walls. Chrome next to colored parts and a hologram picks up their color: hold "pure silver mirror chrome, no tint" as a separate phrase for a large part, before the hologram. Chrome in a list of three parts gets lost on the farthest one.
- Glitter and pearl on large parts wash everything out into pastel pearl; a "holographic rainbow" hologram recolors the neighbors: write "subtle sheen". Fine sand holds with "tiny round grains like fine sugar, no flakes"; "metallic flakes" give scales.
- "Embossed metallic foil" does not hold colored metal: you get glossy plastic with a gradient. "Solid thick dichroic glass, edges flashing teal and gold" gives the shimmer without the word "holographic".
- Colorless transparent plastic without what makes glass visible, on a white background, is a lilac-gray ghost. What holds: "thick colourless acrylic, edges bright with refraction, no grey", a thin outline along the edges, caustics.
- Tilting an object: "rotate it 30 degrees", not "tilt"; it gets lost in a long list, so put it closer to the start.
- A CRT screen: "Screen: <picture> as a glowing CRT image, fine scanlines, RGB phosphor dots, curved glass".
- Inflatables: "puffy inflatable vinyl… taut and air-filled, glossy deep saturated <color>" + a welded seam and a valve: solid inflated gloss holds the color, and the seam and the valve make the thing real.
- A frame edit holds the already colored frame: "keep … every detail" copies its materials one to one, and words about new materials do not override them. Grids ≈ the frame after the second round: change the lever, not the words.
- Matte and "frosted / satin" words on a transparent part in a glossy style give cloudy little balls.

## GPT Image, Nano Banana

- Write the prompt by the slots of the `image` skill; Constraints are mandatory and positive: do not name what is unwanted, the engine draws what is named.
- An edit of a blank, "only X, the rest verbatim" with one new phrase, gives almost a copy: the edit is not visible in the preview. Write the edit so that it reads at card size: size, angle and position in numbers. On the second "same thing", change the lever: a different composition and angle, the prompt rewritten whole.
- Describe metaphors in words; give photo references only as the construction of an object.

## Video (Kling, Veo)

- Kling i2v does not generate video shorter than 3 s: for a short clip put the action in the first N s and cut the tail in editing.
- Kling with sound pulls in the background noise of the place: for clean speech, a quiet place.
- A frame for a talking hero: the face sharp, the eyes with no shadow, the mouth open and covered by nothing.
