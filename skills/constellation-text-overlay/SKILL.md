---
name: constellation-text-overlay
description: Recreate a CapCut constellation title effect with the user's chosen words, star text, one animated connecting stroke, and a staggered reveal over video. Use when someone requests this visual effect or supplies a similar reference tutorial.
---

# Constellation text overlay

Make a short video in which a phrase appears as a constellation: small stars are scattered across the frame, selected stars carry one word each, a single pen stroke connects them in reading order, and the composition draws over the background footage.

## Choose the content

The exact on-screen text is required input. If the user has not specified it for this video, ask **“What exact words should appear on the video?”** before building the effect. Do not silently use the tutorial's text, this skill's examples, or wording from a previous video. Reuse earlier wording only when the user explicitly says to keep it. Preserve their spelling, capitalization, and word order. If footage is also missing, ask for the text and clip together.

After the text is known, ask which color the user wants unless they already chose one. Suggest a specific color based on visible light and dark areas in the supplied footage, plus two alternatives; show swatches or hex values when helpful. Do not choose a new color silently. Check that the chosen line, stars, and words remain readable across the moving footage, and use the same color for all three.

Offer a small set of recognizable shapes before placing stars. Recommend one that fits the footage and let the user choose unless they already named a pattern. Use the sketches in [shape options](references/shape-options.md): **Big Dipper** (four-star bowl and bent handle), **Orion** (hourglass and three-star belt), and **Northern Cross** (long stem and short crossbar). The chosen constellation guides the visual arrangement, not the number of connected stars. For a phrase of N words, select exactly N stars for the animated line, one per word in reading order; the remaining stars are unconnected decoration. Never force the stroke to complete or close a figure just to match the sketch. Do not default to an arbitrary zigzag. Use the same star size throughout.

Use the supplied background footage. One background clip is sufficient; a montage is optional. Keep the constellation inside the visible video area, with clear space around faces and important action. The reference uses bright mint/cyan over a beach montage; that color may not work for other shots.

## Build

1. Put the background clip(s) on the base track and choose a short range in which the constellation will appear. Preview that range so stars do not obscure the main subject.
2. Add one text layer containing `★`. Set its color, size, and opacity. Duplicate it into a loose cluster of stars across the frame. Choose exactly one connected star per word, then add unconnected stars to suggest the constellation and fill the scene. Keep every star the same size and color; vary position rather than scale. The reference places about a dozen stars in total, but density should fit the shot.
3. Add each word of the phrase as its own text layer near its corresponding connected star. Preserve the phrase's reading order along the planned path. Keep each word visually separate from neighboring words and the stroke; check the full rendered word width, not just its anchor point. Place short words such as “in” above and to the right of their associated star when that keeps them clear. A single combined sentence cannot be positioned or revealed word by word.
4. Draw one continuous stroke through those N word stars, with exactly N−1 connections and no branches, repeated stars, or closing segment. For five words, the line visits five stars through four connections, even if the chosen constellation is normally drawn with more stars. Match the star color. Give the line a gentle hand-drawn curve with clean endpoints, without repeated wiggles. Leave a natural open endpoint and let every other star remain unconnected. At 1080×1920, start around 10–12 px thick and adjust for legibility. Use CapCut's drawing tool and **Order In** animation when that editor exposes them. If it does not, use one continuous animated stroke overlay. Check whether CapCut preserves the overlay's transparency; if it turns black, composite the animation into a copy of the background footage before import. Do not approximate the motion with a few successive still images.
5. Animate the words and stars in a staggered sequence while the one stroke grows smoothly from point to point. Let each connection lead to the next word. Keep the final constellation visible long enough to read; for a longer phrase, start with roughly 2–3 seconds after the last word and adjust to the footage's pacing.
6. Preview the first frame, several moments during the stroke animation, each word reveal, line endpoints, any cut between background clips, and the final held frame. Count the connected stars and confirm they equal the word count; verify that the line reaches each word's actual star after any manual repositioning and that decorative stars stay unconnected. Check that the path reads in the intended order, no words collide with each other or the line, all stars have the same visual size, the animation is smooth, and no layer vanishes or turns black. Leave an editable CapCut draft ready for the user to watch. Export only when requested or already authorized.

## Practical constraints

- The original tutorial is a design recipe, not a supplied background asset. Do not reuse tutorial frames as the user's finished footage unless they explicitly request that.
- CapCut versions may name the entrance animation differently. The visible sequence matters more than the preset name.
- If the user wants a reusable template, keep the phrase and color easy to replace and tell them which background clip and text layers to swap.
