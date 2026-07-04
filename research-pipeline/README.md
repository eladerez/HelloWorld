# ML Research Pipeline

This folder is maintained automatically by a daily **ML Research Scout** Claude Code Routine.

It is unrelated to the Android app in the rest of this repository.

## What This Is

Every day at 9am, a cloud Claude Code agent runs a three-phase research pipeline:

1. **Scout** — Searches arXiv, CVPR, ICCV, NeurIPS, ICLR, ICML, and ML research discussions for open problems and promising ideas in the target research areas.
2. **Novelty check** — Verifies each candidate claim against prior art, filtering out already-published work.
3. **Research instructions** — Drafts a concrete research plan (method, datasets, baselines, metrics, compute budget) for each surviving novel claim.

## Target Research Areas

- Diffusion models
- Computer vision
- Transformers
- LLMs (Large Language Models)
- VLA (Vision-Language-Action models)
- VLM (Vision-Language Models)

## Output

All findings are appended daily to `paper_candidates_and_instructions.docx` as a new dated section. The file is updated in-place (same path, new commit) so the full history is preserved in git.

## Do Not Edit Manually

This folder's contents are managed by the automated routine. Manual edits may be overwritten on the next daily run.
