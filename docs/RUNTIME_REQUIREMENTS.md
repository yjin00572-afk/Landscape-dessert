# Runtime Requirements

## Core Requirement

This repository contains the **skill logic**, not the image-generation model.

To produce images, the host environment must provide:

- access to the user's uploaded image
- multimodal image understanding
- an image-generation or image-editing capability

## Expected Host Behavior

In direct-generation mode, the host model should:

1. read the uploaded image
2. follow `SKILL.md`
3. build the image-specific dessert concept internally
4. invoke the available image-generation tool
5. pass the uploaded image as reference when supported

## Portability

The skill intentionally avoids depending on one specific image provider. The exact runtime wiring depends on the platform.

## Limitation

Generative image systems are stochastic. This repository stabilizes design logic, material language, composition rules, quality bar, and visual-identity preservation rather than guaranteeing pixel-identical outputs.
