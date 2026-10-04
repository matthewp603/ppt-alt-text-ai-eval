# Rubric v2

## Changelog
- v2 (2026-10-02): descriptive_accuracy: a missed salient detail caps accuracy at 1 (from INPUT-06 adjudication).

## descriptive_accuracy
Definition: The alt text correctly describes what is actually visible: objects, setting, and the salient visual details a sighted person would notice.
2 = All salient elements named correctly; nothing invented. A listener could picture the scene.
1 = Broadly correct but misses a salient detail, or one minor inaccuracy. A missed salient detail caps accuracy at 1.
0 = Misidentifies the subject or scene, or invents prominent details not present.
Boundary: If the missing detail IS the point of the image (the sun rays in a sunset photo), two reasonable graders can still disagree on what counts as 'the point': that disagreement is rubric material, not grader error.

## functional_usefulness
Definition: The alt text serves the listener's actual need in context: a PowerPoint audience member on a screen reader learns what the image is doing on the slide, not just what it looks like.
2 = Conveys both content and function: why this image is on this slide.
1 = Describes content accurately but gives no functional framing.
0 = Content-free ('image of...') or misleading about the image's purpose.
Boundary: Pure description with zero functional signal is a 1, not a 0. 0 is reserved for misleading or content-free text.

## concision
Definition: The alt text is appropriately brief: complete in one breath, roughly under 125 characters, with no filler phrases like 'image of' or 'in this image we can see'.
2 = About 125 characters or fewer, no filler; nothing a listener would want cut.
1 = 125-200 characters, or one filler phrase; still listenable.
0 = Over ~200 characters, or padded with filler.
Boundary: Character count is a guide, not a law: a 140-char text with zero waste can be a 2; a 90-char text with 'image of a' filler is a 1.
