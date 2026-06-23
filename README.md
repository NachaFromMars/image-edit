# image-edit — AI image editing: inpaint, outpaint, upscale, restore

> Select the right AI editing technique for any image task — object removal, canvas extension, background removal, resolution upscaling, face restoration, style transfer, or relighting.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
image-edit is a technique-routing skill for AI image editing. It maps your editing goal to the right technique and the best available tools, then guides you through a non-destructive workflow. References cover each technique in depth: inpainting, outpainting, background removal, upscaling, restoration, style transfer.

## Features
| Task | Technique | Tools |
|---|---|---|
| Remove objects/people | Inpainting | DALL-E, SD Inpaint, IOPaint |
| Extend canvas | Outpainting | DALL-E, SD, Photoshop AI |
| Remove background | Segmentation | remove.bg, ClipDrop, Photoroom |
| Increase resolution | Upscaling | Real-ESRGAN, Topaz, Magnific |
| Fix blurry faces | Restoration | GFPGAN, CodeFormer |
| Change art style | Style Transfer | SD img2img, ControlNet |
| Relight scene | Relighting | ClipDrop, IC-Light |

**Principles:** non-destructive (keep originals), work in layers, match resolution, mask precision matters.

## Usage / Quick Start
Describe what you want to do with your image. The skill selects the right technique, checks `tools.md` for provider setup, and walks through the workflow.

## Trigger Keywords (OpenClaw)
remove object from image, extend image, remove background, upscale image, fix face, change image style, relight image

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
