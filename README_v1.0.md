# W3M Suno Prompt Creator (v1.0)

The W3M Suno Prompt Creator is a community framework for learning and refining how to write structured prompts for Suno.  
It exists as an open reference and creative lab built by and for artists exploring how to use AI tools with real intent.

This project is not a software tool or generator. It is a shared method for building better AI music, a set of examples, and an invitation to experiment.  
Future versions may introduce interactive tools, but this version focuses on understanding how prompts work and why small choices change what you hear.

The repo includes:
- A base prompt template
- Example prompts contributed by artists
- Clear documentation of how Suno reads and weights each field

Together, these resources form the foundation of the Web3 Metal creative process. They help anyone move from simple one-line prompts to structured and expressive inputs that sound like intent, not accident.

---

## Overview

Suno has two main text fields — **Lyrics and Meta tags** and **Style Prompt**.  
The W3M system treats these like the *script* and the *performance notes*.

- Lyrics field defines what happens and gives the words Suno will sing.  
- Style prompt defines how it should sound, feel, and move.  

This repo explains how to use those fields well, how brackets and section labels work, and how to keep your prompts versioned for iteration and collaboration.

---

## Folder structure
```
w3m-suno-prompt-creator/
├── templates/
│   └── base_template_v1.0.txt
├── examples/
│   ├── thrash_sludge_hybrid_v1.0.txt
│   └── thrash_redemption_v1.0.txt
├── docs/
│   └── w3m-suno-prompt-best-practices_v1.0.md
├── README_v1.0.md
└── LICENSE_v1.0.txt
```

---

## Examples

### *Thrash Sludge Hybrid v1.0*
A fast, gritty blend of thrash and sludge metal.  
Shows how to balance rhythm shifts, tone transitions, and meta-tag direction for dense production textures.

### *Thrash Redemption v1.0*
A detailed 1980s thrash metal prompt demonstrating full structural labeling and emotional continuity across sections.  
Includes multiple riffs, breakdowns, fry-scream cues, and a narrative redemption theme.  
Use this example to study how precise section markers and emotional direction translate into balanced Suno output.

---

## How to use

### Step 1 – Open the project
Click the green Code button near the top of this page.  
Choose Download ZIP if you just want to explore the files, or choose Fork to make your own copy on GitHub.  
Either option gives you a safe workspace. Nothing you do will affect the original.

### Step 2 – Find the base template
Inside the folder called templates, open base_template_v1.0.txt.  
This is your blank prompt sheet. It mirrors how Suno input boxes work. Lyrics and Meta tags first, then Style prompt.  
Read the short comments inside. They will guide you on what to fill out.

### Step 3 – Write your prompt
In the Lyrics part, write your song text or section notes.  
Use square brackets [ ] for things Suno should not sing, like [intro instrumental noise] or [thrash metal].  
In the Style part, describe how the track should sound. Genre, tone, instruments, mix, emotion.  
You can copy from the examples folder if you want a starting point.

### Step 4 – Test and refine
Paste your finished sections into Suno. Lyrics into the Lyrics box. Style into the Style Prompt box.  
Generate your track and listen.  
If something feels off such as tempo, tone, or mix, adjust one thing at a time.  
Save each version with a new number like v1.1 so you can track what worked.

### Step 5 – Share or fork your version
If you use GitHub, upload your finished prompt to the examples folder of your fork.  
Name it clearly, for example ambient_doom_v1.txt.  
You can keep it private or open a pull request to share it with the Web3 Metal community.  
No coding required. You are just editing text files.

### Notes for beginners
GitHub is a shared folder system for creative projects.  
- Fork means make my own copy.  
- Commit means save my changes.  
You can do everything in your browser. No coding tools needed.

---

## Documentation

For detailed explanations of how Suno reads and weights each field, open  
docs/w3m-suno-prompt-best-practices_v1.0.md

It covers:  
- Character limits and field behavior  
- How Suno reads brackets and section labels  
- Weight between Lyrics, Style, and Meta tags  
- Prompt order and emotional emphasis  
- Full examples and versioning tips

---

## Contributing

Pull requests are welcome.  
Follow the template and doc conventions so your work stays compatible with other forks.  
If you create a new genre focused or experimental prompt library, keep the same structure so the ecosystem stays interoperable.

---

## License

MIT License  
Free to fork, remix, and use with attribution.
