# MasterSketchTo3D

SolidWorks VBA macro that reads an assembly-level sketch and generates virtual stiffener parts from the closed rectangular contours it contains.

## Branch convention

Always develop on **`claude/dev`** — do not create new branches with random suffixes.
If `claude/dev` does not exist locally, create it from `main`:

```
git checkout main && git pull origin main
git checkout -b claude/dev
```

If it already exists, just switch to it and pull:

```
git checkout claude/dev && git pull origin claude/dev
```

When the user is happy, merge `claude/dev` → `main` and push.
