# W3M Suno Prompt Best Practices (v1.0)

The W3M Prompt Framework turns creative chaos into something repeatable.
This document explains how to write prompts in Suno two main input areas and how those areas interact.
It also shows how to label song sections, when to use brackets, how weighting works, and what to prioritize in v5.

## 1. Suno two prompt areas

Lyrics and Meta tags field
Where you write lyrics, section notes, and short hints about story or structure.
Up to about 5000 characters.

Style prompt field
Where you describe sound, energy, performance, and production.
Up to about 1000 characters.

Simple rule of thumb
Lyrics tell Suno what to sing. Style tells it how to sound.

Note on limits
These limits match current docs for v4.5 and v5.
If your UI shows different numbers you may be in a limited test.

## 2. The Lyrics and Meta tags field

How Suno reads this
Suno reads everything in this box as one long piece of text.
Text inside square brackets is not sung.
The words inside those brackets are still read as clues about genre or sound.

So
- Brackets stop the model from singing those words
- The words still guide style and tone
- Putting tags at the bottom keeps things tidy for humans

Example
```
Ash on my tongue, smoke in my lungs
The city screams beneath its own weight

[thrash metal] [sludgecore] [distorted vocals] [feedback outro]
```
Suno treats that as one stream of text. It uses all of it to shape melody, phrasing, and mood.

Section labels and structure
Suno does not have built in verse or chorus markers, but you can guide it with short bracketed labels placed before the parts they describe.

Example
```
[intro quick drum fill and feedback]
[verse 1]
Wires hum and walls shake
The signal crawls beneath my skin

[chorus]
Ash on my tongue, smoke in my lungs
The city screams beneath its own weight

[outro slow sludge riff, no vocals]

[thrash metal] [sludgecore] [distorted vocals] [feedback ending]
```
Those labels are not sung. They help Suno pace the song.

Tips
- Keep labels short and clear
- Put the label directly before the section
- Keep global tags like genre at the end so they apply to the whole track

## 3. The Style prompt field

What it controls
This box has more pull over production, tone, and performance.
It shapes instrumentation, energy, mix, and emotional delivery.

Think of it as stage direction for the lyrics.

Example
```
Aggressive thrash pace with sludge weight. Thick guitars and gritty mix.
Vocals barked through a corroded mic.
Starts fast then drops to half speed under heavy fuzz.
Ends in a wall of feedback.
```

Order and emphasis
What you write first tends to set the headline in the model mind.
Front load the core idea, then add texture and mix notes.

Recommended order
1. Core genre or concept fusion
2. Texture and instrumentation
3. Emotion or mood words
4. Mix or structure notes

Example
Experimental death metal fused with free form jazz. Dense and alive.
Bass and drums improvise around blast beat structures.
Recorded raw with open room reverb.

## 4. Prompt weighting in v5

The balance between fields remains the same, but v5 reacts more strongly to emotion words.

- Lyrics field is the main blueprint for melody and rhythm
- Style prompt is the main driver of tone, performance, and production
- Meta tags are gentle steering, they do not override the others

Think of it like this
- Lyrics equals what happens
- Style equals how it feels
- Meta tags equal light guidance

Emotion words in the Style field like furious, pleading, or detached often affect phrasing and vocal tone more than before.

## 5. Combined example Thrash and Sludgecore hybrid

Lyrics and Meta tags field
```
[intro quick drum fill and feedback]
Ash on my tongue, smoke in my lungs
The city screams beneath its own weight
[bridge slow sludge riff]
Power lines hum like prayers gone wrong
I keep walking through the static haze

[thrash metal] [sludgecore] [distorted vocals] [feedback outro]
```

Style prompt field
```
Fast thrash pace with sludge drag. Raw and physical.
Drums swing like collapsing machinery.
Vocals barked through a corroded PA.
Ends in feedback and tape hiss.
```

## 6. Versioning and workflow

Treat each change as a creative commit. Keep notes so you can repeat what works.
```
Prompt version 1.2
Change notes Reduced vocal distortion and slower outro
Result Clearer mids and better separation
```
Store versions in examples or projects folders. Commit often with short messages.

## 7. Forking and contributions

This repo is designed for forking.
Use the base template, follow these practices, and share your styles or experiments.
Consistent structure makes it easy to remix or merge ideas later.

## 8. Quick checklist for sessions

- Write lyrics and section labels in the Lyrics field
- Keep meta tags short and literal
- Lead the Style prompt with the core idea
- Use emotion words when they help
- Save each version clearly
- Export prompts as clean text for reuse
