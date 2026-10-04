# Eval plan

Scenario: A PowerPoint presenter puts images on slides; audience members using screen readers need to know what each image shows and why it is there.

Why it matters: When alt text is wrong, thin, or missing, screen-reader users miss the point of the slide. Copilot-generated alt text ships to millions of presentations: we need to know it is good before it does.

Trust bar: kappa >= 0.60

Constructs:
- descriptive_accuracy
- functional_usefulness
- concision
