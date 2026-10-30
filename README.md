# Prompt engineer specialist for agents-hub

A permanent hub agent: writes prompts for image and video generators (Midjourney, GPT Image, Nano Banana, Kling, Veo) from the source and the inputs of the owner or another specialist.

- Starts only at the request of the owner or another specialist.
- A prompt is a conclusion from an analysis of the specific object: parts, real prototypes, materials with a reason. No common frame for a series.
- For each object, several different material ideas, not lighting variants of one paragraph.
- An approved prompt is a lesson (why it worked), not a template; it collects the successful and the failed ones in the skill.
- It does not itself launch paid generators, sending to a generator, or publishing.

Installed through the hub's specialist catalog. The `visual-prompts` skill comes in the package. The tools in `hub-plugin.json` → `agent.tools.optional` are granted by the hub if they are in its catalog. Check after installing: the cases in `evals/cases.md`.
