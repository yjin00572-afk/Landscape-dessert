---
name: dessert-cutout-from-image
description: Analyze a user-supplied image, extract its dominant visual elements and largest color field, and generate a new fine-dining dessert cutout on a matching solid background. Use when the request is to reinterpret an image as a dessert product shot instead of editing the original image directly.
---

# Dessert Cutout From Image

Use this skill when the user wants an uploaded or referenced image translated into a new dessert concept and final rendered image.

## Outcome

Produce either:

- a finished generated image, or
- if image generation is unavailable or the user asks for prompt-only output, a production-ready prompt plus concise extraction notes

## Required Interpretation

Before generating, identify at least 4 distinct primary subjects, objects, or textures from the source image. Treat them as source motifs, not literal objects that must be copied one-for-one.

For each chosen element:

- note the shape or silhouette cue
- note the material or texture cue
- remap it into an edible dessert component such as mousse, jelly, glaze, crisp, crumble, sponge, tuile, pearl, chocolate decor, or laminated pastry

Identify the single largest color block in the source image and use that exact or closest defensible shade as the final background color. The background must stay solid, flat, clean, and untextured.

## Composition Rules

- Generate one modern fine-dining dessert as an isolated centered cutout object.
- Do not include a plate unless the user explicitly asks for one.
- Do not add props, utensils, hands, packaging, table surfaces, typography, or environmental scenery.
- Use studio product lighting with a restrained soft shadow beneath the dessert so it sits realistically on the background.
- Keep the dessert fully legible with clear depth of field.
- Aim for hyper-real pastry photography with an 8k-level finish.

## Image Workflow

- Inspect the source image first. Use local image inspection when a file path is available, or use the attached conversation image when the image exists only in chat context.
- Write a short internal extraction that includes:
  1. at least 4 source elements
  2. each dessert-material mapping
  3. the dominant background color
- Then generate a brand-new image using the image-generation tool available in the environment.
- Include only the minimum image-reference context needed for accurate grounding.
- If the dominant color cannot be sampled numerically, state that it is visually inferred and keep that inferred shade consistent across the prompt and output.

## Prompt Construction

Ensure the final generation prompt explicitly covers:

- the 4 mapped dessert elements
- centered isolated cutout composition
- solid flat background using the dominant color
- premium pastry textures and materials
- studio lighting and soft grounding shadow
- modern fine-dining presentation
- hyper-real photographic detail

## Style And Rights Boundaries

- Use the source image for structural and color inspiration only.
- Do not claim the result is an edit of, replacement for, or official derivative of the original image.
- Avoid direct artist-style imitation. If the user names an artist, treat the reference as high-level mood, composition, or material inspiration only.
- If rights-sensitive brands, logos, or protected characters appear in the source image, abstract their formal qualities rather than reproducing them literally unless the user clearly has that right and requests it.

## Response Shape

Keep the user-facing response concise:

- mention the extracted elements and chosen background color
- return the generated image when available
- if generation is unavailable, provide a final prompt that can be used directly
