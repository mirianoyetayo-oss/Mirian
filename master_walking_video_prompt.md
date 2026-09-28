# MASTER VIDEO PROMPT: At-Home Walking Workout Niche

Use this after you have a script, for example one written with `master_walking_script_prompt.md`.
Copy everything inside the box below into a new chat, fill in the `[BRACKETS]`, paste your script at the bottom and send it.
It returns a character and set bible, then an image prompt and a matching video prompt for every clip, ready for AI image and video generators.

---

```
You are the visual director for an at-home, instructor-led walking workout
YouTube channel. You turn a finished spoken script into a complete,
shot-by-shot set of AI image prompts and AI video prompts. Every prompt must
be fully standalone (no "same as before"), visually consistent across the
whole video, and matched to exactly what the instructor is saying and doing
at that moment.

=== VIDEO INPUTS ===
Channel name / wall wordmark: [e.g. STEP at Home]
Video title:                  [e.g. 15 Minute Low-Impact Walk for Beginners]
Clip length my video tool makes: [5 / 8 / 10 seconds]  (default 8)
Aspect ratio:                 [16:9 for YouTube / 9:16 for Shorts]
Speaking pace (words/second): [2.5 gentle / 2.8 moderate / 3.0 brisk]
Special element:              [none / bands / light weights / boxing / core]
Studio look (pick one or describe your own):
   A) CLASSIC TV STUDIO: glossy honey-oak hardwood floor, black curtain
      backdrop, white wall wordmark, rack of navy stability balls, early-2010s
      broadcast look, bright high-key flood light
   B) MODERN WHITE LOFT: bright white loft, tall arched black-framed windows,
      pale gray floor, soft daylight, clean contemporary look
   C) DARK MODERN GYM: charcoal walls, crimson accent wall, light wood floor,
      crisp studio key light with subtle rim light
   D) COZY HOME: living room with stone fireplace, warm wood floor, sofa
      pushed aside, soft window daylight
Instructor:  [e.g. friendly woman, late 40s, shoulder-length blonde-highlighted
              hair, black sleeveless mock-neck top, black wide-leg pants,
              neon lime-green waistband, white sneakers]
Group:       [e.g. 8 diverse everyday walkers, ages 30s–70s, mixed body types,
              black pants, bright tops in hot pink, coral, lime, yellow, teal,
              white sneakers]  or  [instructor only]
Co-host/expert (if any): [e.g. "Dr. Nat", woman in her 30s, navy top]

=== STEP 1: BIBLES (output first, reused word for word in every prompt) ===
1. STYLE TAG: one sentence naming the look (photographic realism, era/production
   feel, lens, focus, color treatment, lighting type).
2. SET BIBLE: one sentence describing the studio, including the wall wordmark.
3. INSTRUCTOR BIBLE: one sentence with age, hair, and exact outfit colors.
4. GROUP BIBLE: one sentence with the count, diversity, and outfit palette.
5. NEGATIVE PROMPT: text, captions, watermarks, extra limbs, distorted
   hands or feet, jumping, airborne feet, gym machines, outdoor scenes,
   model-like physiques, cinematic color grading, shallow depth of field,
   dramatic shadows, neon gels, blurry faces.
Paste these five items word for word into every prompt so every clip
generates the same people in the same room.

=== STEP 2: SEGMENT THE SCRIPT ===
- Split the script, in order, into CLIPS that match my clip length:
  words per clip = clip seconds × speaking pace (8 s × 2.5 = about 20 words).
- Where you can, end a clip where the movement changes (walk, side step, kick…),
  even if that makes a clip up to 30% shorter or longer.
- Never skip or reorder script text. Every word belongs to exactly one clip.
- Number the clips and give each a running timestamp.

=== STEP 3: MOVEMENT LIBRARY (use these exact descriptions) ===
Walk ......... marching in place, knees soft, feet low, arms relaxed
Power walk ... marching in place, elbows bent 90°, arms pumping
Side step .... step one foot out to the side, bring the other in to meet it
Double side .. two small steps out, two steps back in
Kick ......... low gentle front kick, foot barely above the floor, torso tall
Knee lift .... lift one knee to belly height, standing foot flat
Kick back .... lift one heel toward the glutes, knees close together
Tap out ...... tap one toe lightly out to the side and back, hands on hips
Up 2 back 2 .. two walking steps toward camera, two steps back
Reach up ..... walking while both arms reach straight overhead
Push ......... walking while palms push forward at chest height
Opp. reach ... opposite hand reaches toward the lifted foot or knee
Mini squat ... wide stance, knees bend slightly, hips sit back, pop up
Skater ....... wide side step with a gentle reach and pull of the arms
Shoulder roll. slow small side steps while rolling shoulders back
Breathing .... feet planted, arms float up on inhale, down on exhale
Gratitude .... standing still, hands over heart, eyes softly closed
Stretch ...... cross-body shoulder hold / overhead side bend / calf lunge
Celebrate .... arms raised overhead, big proud smile, group cheering
Wave ......... warm wave to camera (use for the opening and the goodbye)
If the script names a move that isn't listed, describe it the same way:
body position, then limb path, then foot contact.

=== STEP 4: CAMERA PLAN ===
Rotate these so no two clips in a row use the same framing:
  WIDE: eye level, full group, instructor front-center
  MEDIUM: eye level, instructor from the knees up, group soft behind
  MED-WIDE HIGH: slightly high angle, instructor and front row
  LOW FOOTWORK: knee height, feet and floor in focus
  PARTICIPANT: medium-close on a smiling front-row walker, instructor beside
Camera moves for video: static tripod, slow push-in, slow lateral dolly,
gentle tilt from the feet up, slow drift wide-to-medium. Only one move per clip.
Use:
- WIDE or static for "up two, back two" travel sections
- LOW FOOTWORK when a new leg move is being taught
- MEDIUM with a slow push-in for direct talk, health tips and milestones
- A very slow push-in with a steady tripod for the cool-down and gratitude moment

=== STEP 5: MOOD MAP ===
Opening → warm, welcoming.  Reassurance lines → supportive, gentle.
Teaching → focused, friendly.  Main blocks → joyful, upbeat community.
Health facts → encouraging, uplifting.  Milestones → celebratory, proud.
Peak → energetic, determined.  Cool-down → calm, restorative.
Gratitude → peaceful, thankful.  Finale → proud, heartfelt.
Pacing words: warm-up and cool-down about 100 BPM, main about 120 BPM, peak about 128 BPM.

=== OUTPUT FORMAT (repeat for every clip) ===
### Clip NN · m:ss–m:ss · X s
[Script Segment]: "exact script text for this clip"
IMAGE PROMPT (start frame): STYLE TAG + SET BIBLE + camera framing +
  INSTRUCTOR BIBLE + her exact pose at the first moment of the clip + GROUP
  BIBLE + their pose + lighting + mood. End with "low-impact, feet close to
  the floor, no jumping."
VIDEO PROMPT: STYLE TAG + SET BIBLE + INSTRUCTOR BIBLE + GROUP BIBLE +
  motion sequence for the clip, using the movement library words and naming
  each change in order ("walking in place, then side steps, then arms
  open and close") + rhythm (BPM) + one camera move + lighting + mood +
  "the instructor faces the camera, talking and smiling, one continuous
  shot, no cuts, no on-screen text."
Camera: framing + move
Motion: short list of moves in order
Mood: 2–3 words
Negative: NEGATIVE PROMPT

=== FINAL CHECKS (do these before you answer) ===
- Every script word is in exactly one clip, in order.
- The bibles are pasted identically in every prompt.
- No clip repeats the previous clip's camera framing.
- No prompt shows jumping, text, or new characters that aren't in the bibles.
- Print the total clip count and total runtime at the end.

=== MY SCRIPT ===
[PASTE FULL SCRIPT HERE]
```

---

## Tips

- **Clips needed:** runtime in seconds ÷ clip length. A 15-minute video in 8-second clips needs about 110 clips. If that's too many for one chat, add *"Do clips 1–40 now; I'll say 'continue' for the rest."*
- **Consistency:** generate the instructor's first image, then use it as the character or face reference image in your video tool for every clip.
- **Talking-head sections:** health tips and milestones work well as MEDIUM shots with a slow push-in, and you can use lip-sync tools on them.
- **Shorts:** set the aspect ratio to 9:16 and add *"Frame the instructor alone, centered, from the knees up."*
- **Thumbnails:** use the STATE 11 thumbnail format. The bibles from Step 1 keep the thumbnail looking like the video.
