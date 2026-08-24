# XXD Panel 025 | Gestalt Positive–Negative Morandi Screenprint

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for the current task. Lock one principal subject or inseparable relation, its main action, and at least three source-specific cues; then distil one environment, structure, object, or symbolic image most closely related to that same source. Never borrow a hidden image, palette, copy, or composition from samples, old outputs, or another input.

## Subject at first glance, hidden image at second

Preserve the subject's most recognisable clear outer contour. Integrate the hidden image through contour interlock, negative-space cutout, shared boundary, and figure-ground reversal so both become one complete graphic. From a distance the subject must read first; only on closer view should the second scene or image emerge. One shape's edge must naturally become the other's boundary.

Never place two objects side by side, stack them transparently, double-expose them, or combine two independent icons and call it an illusion. The hidden layer must come from source fact or a grounded symbolic relation and must not damage first-level subject recognition.

## One anchor and breathing figure-ground shift

Keep one visual anchor, one principal silhouette, and generous pale paper. Let source pose, direction, weight, and contour flow choose offset placement, local crop, vertical nesting, or edge alignment. Supporting elements remain minimal; visual pleasure comes from the instant switch between first seeing and seeing again, not from decoration count.

Reject several equal focal points, complex scenery, even filling, direct collage, icon arrays, explanatory arrows, and template centring.

## Two to four Morandi pastels

Extract and soften the source's most spirited colour relation into two to four Morandi pastels: mist pink, soft apricot, grey green, sage, pale terracotta, cream yellow, mist blue, grey violet, or other source-supported low-saturation composites. Use a pale paper base and build hierarchy through overall temperature, value difference, and area ratio.

Colours must stay clean, soft, and airy. Reject dirty grey, heavy ageing, fluorescent colour, high-contrast commercial palettes, rainbow colour, fixed palettes, and gradients.

## Crisp flats and physical screenprint touch

Keep contours crisp and colour shapes flat while retaining slight paper fibre, screenprint grain, ink coverage, and small registration shift. Physical print evidence stays restrained and never becomes a cheap dirty filter. Reject gradients, digital blur, realistic shadow, 3D volume, smooth CGI, impasto, and excessive distress.

## Typography belonging to 025

Automatic copy derives one short title from supported identity, place, action, mood, state, or symbolism, adding only sparse supplied place, number, state word, or micro-annotation when useful. Places, dates, provenance, and factual numbers require user input or reliable evidence and are never invented.

Run type along the subject contour, negative-space boundary, horizontal baseline, or whitespace axis. It may enter the graphic, be interrupted by a contour, or occlude with a colour shape so type becomes part of the figure-ground structure. Use native-script equivalents of small intelligent editorial typography; never force Latin tracking, rotation, or word splitting onto other scripts. Exact user wording stays verbatim; text-free output contains no text or pseudo-text.

## Mode and hard gate


Hard gate: one clear source-bound subject silhouette; one source-grounded hidden environment, structure, object, or symbolic image; both become one graphic through contour interlock, negative-space cutout, shared boundary, and figure-ground reversal; subject reads first and hidden layer second; one visual anchor and generous whitespace; two to four source-derived Morandi pastels; crisp flat colour plus slight paper fibre, screenprint grain, ink coverage, and registration shift; type enters contour, negative space, or whitespace axis; no side-by-side pair, transparent stacking, double exposure, multiple focal points, complex illustration, gradient, realistic shadow, 3D, cartoon, commercial promotion, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
