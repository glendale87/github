# Contributing to Casual Minecraft Builds

Thank you for contributing to the **Casual Minecraft** build repository.

This repository accepts:

- Viewer-submitted builds
- Improvements to existing builds
- Documentation enhancements

Please review all requirements before submitting a pull request.

---

## 📦 Build Submission Requirements

Your submission **must include**:

- At least one schematic file (`.schem` or `.litematic`)
- A `README.md` file containing:
  - At least one image preview of the build
  - A complete material list the build
  - Minecraft version compatibility
  - Creator information:
    - Minecraft username or social handle
    - Optional social links (YouTube, Twitch, Discord, TikTok, X, etc.)

Incomplete submissions will not be merged.

---

## 📁 Required Folder Structure

Your folders must follow this exact structure:

```
[category]/
└── build-name--username/
    ├── schematics/
    ├── images/
    └── README.md
```

### Category Rules

`[category]` must match one of the existing repository categories. If a category needs to be added, please open an issue or include it in your Pull Request with an explanation.

### Folder Naming Rules

To ensure cross-platform compatibility and consistency:

- Use **lowercase letters only**
- Use **hyphens** instead of spaces
- Include your **Minecraft or social username**
- Do **not** use special characters or uppercase letters

Format:  
`build-name--username`

Example:  
`simple-starter-base--casual`

### Subfolders

Subfolders must be named exactly:

```
schematics/
images/
```

- Schematics go in `schematics/`
- Screenshots/previews go in `images/`

### Schematic File Names

- Use **lowercase letters only**
- Use **hyphens** instead of spaces
- Include a **version number**: `_v<major>.<minor>`
- Allowed formats: `.schem` or `.litematic`
- Do **not** use words like `final`, `fixed`, `new`, or extra descriptors in the name

Format:  
`build-name_vX.Y.format`

Examples:

```
starter-iron-farm_v1.0.litematic
starter-iron-farm_v1.1.schem
single-iron-farm_v1.0.litematic
```

### Image File Names

- Use **lowercase letters only**
- Use **hyphens** instead of spaces
- Allowed formats: `.png` (preferred) or `.jpg`

There **must** be one image named `preview.png` or `preview.jpg` that best shows the build. This file will be displayed in the build folder's `README.md` and may be used to showcase the build in the category `README.md` file.

## 🧱 Material List Standards

Material lists must:

- Be complete and accurate
- Match the included schematic(s)
- Reflect survival-obtainable quantities
- Generalizations are acceptable for blocks if the variant doesn't matter
  - `Building Block` instead of `Stone`, `Cobblestone`, etc.
  - `Trapdoor` instead of `Oak Trapdoor`
  - `Slab` instead of `Stone Slab`

If multiple schematics are included, each must have its own clearly labeled material list section inside `README.md`.

---

## 🧱 Build Quality Guidelines

All submitted builds must:

- Be original work
- Function properly in the listed Minecraft version(s)
- Not be copied from other creators
- Be clearly organized

Highly technical builds should include notes about:

- Lag impact
- Multiplayer compatibility
- Known limitations

---

## 📺 Build Consideration

Submitting a build does **not** guarantee:

- Merge approval
- Immediate review
- A YouTube feature

High-quality, original, survival-friendly builds are prioritized.

---

## 🛠 Making Improvements

You may also submit pull requests to:

- Fix typos
- Improve documentation clarity
- Update version compatibility
- Improve material list formatting
- Add missing build notes

---

## 🚫 What Will Be Rejected

The following submissions will not be accepted:

- Stolen or copied builds
- Incomplete folder structures
- Missing material lists
- Broken or untested redstone
- Joke or meme builds without clear labeling

---

Thank you for helping grow the **Casual Minecraft** community and build repository.
