# Target Style: Luxury Edible Miniature Worlds

Read this document before designing or generating a dessert with `$dessert-cutout-from-image`.

The target aesthetic is a complete, source-faithful miniature world reconstructed from believable pastry materials and presented as premium restaurant dessert photography. Preserve the original environment and spatial relationships instead of reducing the image to an isolated object.

## Non-Negotiable Shared Direction

- Make the user's uploaded image the only authority for subject matter, scene layout, color palette, emotional atmosphere, and significant details.
- Use a bundled style reference only for edible miniature scale, pastry craftsmanship, plate composition, food textures, scene richness, and photographic presentation.
- Rebuild the complete source environment: primary subject, foreground, middle ground, background, terrain or water surface, relevant plants or architecture, meaningful animals or people, and characteristic light.
- Keep the dessert visibly edible through mousse bases, mirror glaze, chocolate, wafer, gel, sablé, sponge crumbs, sorbet, sugar work, or plated sauces.
- Match detail density to the source: dense urban scenes may be densely detailed; intimate or foggy scenes may be quieter but must retain environmental context.
- Prefer close three-quarter macro food photography, soft directional light, ceramic restaurant plating, tactile micro-textures, and coherent miniature depth.
- Do not copy swans, lighthouse towers, mountain cliffs, boats, trees, or other specific reference subjects unless they also belong to the uploaded source scene.

## Reference 1: Harbor City Architectural Diorama

Image: `assets/style-references/01-harbor-city-edible-diorama.png`

Choose this reference for urban environments, architectural groups, streets, villages, campuses, waterfronts, harbors, docks, industrial landmarks, and complex built landscapes.

### What to Transfer

- A complete miniature town or architectural environment rather than one oversized isolated building.
- Carefully organized foreground harbor water, intermediate boats and docks, and background building clusters.
- A clear landmark hierarchy, such as a tower or lighthouse, without sacrificing surrounding structures.
- Rich but readable building density, varied rooflines, tiny windows, streets, terrain, and edible greenery.
- Architectural construction from wafer, tempered chocolate, biscuit panels, sugar windows, cocoa-butter color, and precise piped details.
- Glossy blue-green gel water, crumb-textured ground, restrained micro-herbs, and a coherent visible plate.
- Warm directional light, premium close-up food photography, and cinematic miniature depth.

### What Not to Copy

Do not add a lighthouse, European harbor, ships, red roofs, or specific buildings unless the source image contains corresponding subjects. Preserve the actual location's architecture, geometry, colors, and landmark arrangement.

## Reference 2: Mountain Lake Landscape Entremet

Image: `assets/style-references/02-mountain-lake-landscape-entremet.png`

Choose this reference for lakes, forests, mountains, beaches, rivers, cliffs, natural shorelines, scenic viewpoints, outdoor visitor scenes, and landscape photographs that benefit from a visible cake or mousse foundation.

### What to Transfer

- A complete landscape reconstructed on a visibly edible circular or irregular entremet.
- A pronounced mousse sidewall or pastry foundation that makes the object unmistakably recognizable as dessert.
- A translucent lake surface with deep-to-shallow color transitions, delicate ripples, and realistic reflective highlights.
- Far-shore chocolate or biscuit cliffs, source-faithful tree placement, foreground beach geometry, and coherent scenic depth.
- Tiny edible human figures when shoreline visitors or human activity are meaningful to the source image.
- Matcha or pistachio moss, sablé sand, chocolate rocks, micro-trees, small gel droplets, and optional restrained sorbet plating.
- Refined white or neutral restaurant plate, subtle surrounding crumbs, and soft natural lighting.

### What Not to Copy

Do not add a lake, pine trees, cliffs, beach visitors, green sorbet, or a circular cake unless those choices fit the uploaded source scene. Round bases are allowed when useful, not mandatory.

## Reference 3: Swan Pond Botanical Diorama

Image: `assets/style-references/03-swan-pond-botanical-diorama.png`

Choose this reference for animals, birds, waterfowl, ponds, wetlands, gardens, flowers, natural habitats, aquatic ecosystems, and botanical landscape scenes.

### What to Transfer

- A complete edible ecosystem, with animal subjects integrated naturally into their environment.
- Deep translucent green gel water, subtle concentric ripples, realistic reflections, and cohesive shoreline boundaries.
- Delicate mousse, meringue, sugar, or white-chocolate animal sculptures with refined edible surface detail.
- Layered moss, lily pads, fine aquatic leaves, tiny flowers, edible dew, and controlled botanical richness.
- Balanced perimeter framing that guides attention toward the principal subject while keeping supporting habitat intact.
- Optional restrained clear gel spheres and tiny gold accents only when they reinforce the original scene.
- Soft natural light, premium ceramic plating, believable pastry materiality, and intimate macro photography.

### What Not to Copy

Do not add swans, lily pads, green water, white flowers, or gold leaf unless they are justified by the uploaded source. Preserve the actual species, vegetation, palette, habitat, and composition.

## Reference Selection

1. Analyze the source image before choosing a reference.
2. Select the architectural reference for primarily built environments.
3. Select the mountain-lake entremet for scenic landscapes or compositions requiring an explicit cake base.
4. Select the swan-pond reference for animals, gardens, ponds, wetlands, and botanical ecosystems.
5. For sparse seas, night scenes, snowfields, or isolated close-up subjects, choose the landscape or botanical reference that best matches the desired plating and environment; never import its unrelated subject matter.
6. When two categories overlap, select the reference that best matches the dominant spatial structure and dessert presentation.

## Multi-Image Prompt Contract

When image generation supports multiple visual inputs, provide:

1. The user's uploaded source image as the content, subject, composition, palette, and atmosphere reference.
2. The selected bundled target-style image as the dessert presentation, miniature-world structure, pastry craftsmanship, plate composition, and photographic styling reference.

State their separate roles explicitly:

> Image 1 determines what appears in the output. Image 2 determines how that content is reconstructed as a premium edible miniature dessert. Preserve Image 1's subjects and layout; borrow only Image 2's plating, pastry materiality, miniature scale, scene completeness, and macro food-photography quality.

If only one reference image can be passed, prioritize the user's uploaded source image and express the selected target-style characteristics explicitly in the prompt.

## Acceptance Criteria

Accept the image only when it:

- clearly resembles a premium edible dessert;
- remains immediately recognizable as the user's original scene;
- preserves a coherent miniature environment and meaningful supporting details;
- maintains believable scale relationships and visual depth;
- uses realistic pastry materials and refined restaurant plating;
- matches the source image's complexity instead of imposing arbitrary minimalism;
- borrows presentation quality, not subject matter, from the bundled target reference.

Reject isolated prop-like objects, synthetic-looking toy models, generic birthday cakes, missing dessert foundations, unrelated copied reference subjects, and scenes whose important environmental context has disappeared.
