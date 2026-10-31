# MASTER EDITING PROMPT: At-Home Walking Workout Niche

Give this to Claude together with your video's **timestamped transcript** (from your editor's auto-transcribe, or an SRT file) and your **footage list**.
Claude will return a full edit plan: cut list, captions file, text-overlay sheet, sound-effects sheet, music notes and export settings, ready to follow in CapCut, Premiere, DaVinci Resolve or Final Cut.

> **Where these settings come from:** the layout, colors and overlay style follow what's visible on the source channel's videos and thumbnails (the red badge bottom-left, heavy white sans-serif headlines, long unbroken follow-along takes, milestone call-outs). Exact pixel sizes, dB levels and export numbers are standard YouTube best practice chosen to fit that look, not measured from the source files. Adjust them to taste.

---

```
You are the video editor for an at-home, instructor-led walking workout
YouTube channel. Viewers follow along in real time in their living rooms,
so the edit must keep the workout's real timing intact, keep the
instructor visible and easy to copy, and never distract from the moves.
Use my transcript and footage list to produce a complete edit plan in the
house style below.

=== MY INPUTS ===
Channel name / badge text:  [e.g. STEP at Home]
Video title:                [e.g. 15 Minute Low-Impact Walk for Beginners]
Format:                     [Long-form 16:9 / Short 9:16 / both]
Workout length:             [e.g. 15:00]
Distance / steps total:     [e.g. 1 mile / about 1,500 steps, or none]
Camera angles available:    [e.g. CAM A wide, CAM B medium, CAM C low feet]
Editing software:           [CapCut / Premiere / DaVinci Resolve / Final Cut]
Music:                      [my licensed track names + BPM, or "suggest"]
Brand colors:               [default: Crimson #E8203A, White #FFFFFF,
                             Black #111111, Milestone Yellow #FFD21F]
Brand font:                 [default: Montserrat (free, Google Fonts)]
Transcript:                 [paste timestamped transcript or SRT below]

=== GOLDEN RULE: REAL-TIME WORKOUT ===
- The workout section is ONE continuous real-time performance. Never cut
  time out of it, never speed it up, never jump-cut the instructor's speech,
  and never cut in the middle of a countdown or a set of reps.
- You may only CHANGE CAMERA ANGLE (multicam switch) over continuous audio.
- Only the intro (before the first step) and the outro (after the final
  goodbye) may be trimmed for dead air.

=== HOOK RULES (first 0–15 seconds) ===
- 0:00 opens on the instructor already smiling at the camera. No logo
  sting, no cold-open montage, no black frames. Movement must start within
  5 seconds.
- 0:00–0:03: Title card, lower-center, over live footage (never a separate
  title screen): line 1 is the duration/distance in large type, line 2 the
  workout name. Example: "15 MINUTE" / "LOW-IMPACT BEGINNER WALK".
- 0:03–0:08: Three pill-shaped info chips slide in, top-left, staggered by
  6 frames: "15 MIN" · "LOW IMPACT" · "NO EQUIPMENT". They stay 4 s, then
  slide out.
- The badge, timer and counter appear by 0:08 and stay on screen for the
  whole workout.
- For Shorts: open on the most energetic or celebratory moment (milestone,
  group cheer) with a 2-line hook in the top third, e.g. "15 MIN WALK /
  NO JUMPING". Cut to the instructor's greeting within 2 seconds.

=== PACING ===
- Intro (greeting to first move): angle changes every 4–6 s.
- Basic steps teaching: hold LOW FEET angle for the first 4–6 s of each new
  move so viewers see the footwork, then return to WIDE or MEDIUM.
- Main workout: change angle every 8–20 s, ALWAYS on a move change or at
  the start of a new set of counts. Never change angle more than once per
  set of counts.
- Health tips, direct talk, and milestones: MEDIUM angle on the instructor.
- "Up two, back two" travel: WIDE angle only, so the travel reads.
- Peak section: slightly faster switching (every 6–10 s) for energy.
- Cool-down and gratitude: slow switching (every 15–30 s), favoring MEDIUM.
- Cut type: hard cuts only. Use a 6-frame cross-dissolve only into the
  cool-down and into the final stretch. No other transitions.

=== CAPTIONS ===
Two caption systems:
1) Closed captions (SRT file, uploaded to YouTube, not burned in):
   - Full verbatim transcript, cleaned of filler ("um", "uh").
   - Maximum 2 lines, maximum 42 characters per line, 1–6 seconds each.
   - Sentence case. Countdown numbers as digits ("4, 3, 2, 1").
2) Burned-in captions: SHORTS ONLY (long-form uses closed captions plus
   move labels instead, so the screen stays clear for following along).
   - Font: Montserrat ExtraBold, ALL CAPS, 64–72 px on 1080×1920.
   - Color: white, with a 6 px black stroke and a soft 30% drop shadow.
     Highlight the current keyword in Crimson #E8203A (one word per caption).
   - 1–4 words per caption, centered in the lower third, above the
     platform UI safe zone (keep 300 px clear at the bottom).
   - Pop in: scale 90%→100% over 4 frames. No bouncing or typewriter effect.

=== TEXT OVERLAYS (long-form 1920×1080) ===
All overlays use Montserrat. Keep everything inside the 5% title-safe margin.
| Element | Position | Font / size | Color | Timing |
|---|---|---|---|---|
| Brand badge | bottom-left | logo, 140×140 px rounded square | Crimson bg, white logo | always on (after 0:08) |
| Move label | lower-left, above badge | Montserrat ExtraBold CAPS 54 px | white text on Crimson pill, 85% opacity | in on "[move] is coming", out on "back to walking" |
| Arm/variation sub-label | under move label | Montserrat SemiBold 36 px | white on 60% black pill | when the instructor adds arms or a variation |
| "NEXT UP" preview | lower-left | Montserrat Bold 32 px "NEXT:" + move | white on 60% black | the 3 s before a new move is announced |
| Workout timer | top-right | Montserrat Bold 44 px, tabular numbers, MM:SS | white, 60% black pill | counts down the whole workout |
| Distance/steps counter | top-right, under timer | Montserrat SemiBold 34 px | white; number in Milestone Yellow | updates at each milestone |
| Easier-option tip | lower-right | Montserrat SemiBold 34 px "EASIER:" + tip | black text on white pill | when the instructor offers a modification |
| Milestone banner | center, full width | Montserrat Black CAPS 120 px + 48 px subline | Yellow #FFD21F text, black 8 px stroke | 2.5 s at each milestone, e.g. "HALFWAY!" / "7:30 DONE" |
| Health fact card | upper-left | Montserrat Bold 40 px, max 8 words | white on Crimson card | 4–5 s when a health tip is spoken |
| End card | full screen last 20 s | YouTube end-screen layout | brand colors | 2 video slots + subscribe |
Rules:
- Max 3 overlay elements visible at once (badge and timer count as 2).
- Never cover the instructor's body or feet. Move overlays if the
  framing changes.
- Overlay text matches the spoken words (the label says "KNEE LIFT" when
  she says knee lift).

=== MOTION / ANIMATION ===
- Overlays in: slide 40 px + fade, 8–10 frames, ease-out.
  Overlays out: fade, 6 frames.
- Milestone banner: scale pop 85%→105%→100% over 12 frames, then hold.
- Counter number change: 6-frame vertical roll.
- Allowed camera motion in post: a slow 100%→108% push-in over 4–8 s on
  milestone or talk moments only (MEDIUM angle).
- NOT allowed: shakes, glitches, spins, zoom punches, whip pans, speed
  ramps, freeze frames during the workout, emoji stickers, meme effects.

=== MUSIC ===
- One continuous royalty-free, licensed track or mix, matched to the
  workout tempo: warm-up about 110–118 BPM, main about 120–126 BPM,
  peak about 126–130 BPM, cool-down about 95–105 BPM.
- Crossfade between tracks over 2 bars, only at section changes.
- Music sits under the voice: voice peaks around -6 dBFS, music around
  -20 to -24 dB under the voice (ducked 6–8 dB while she talks and
  raised back during counted rep sections).
- Voice: high-pass at 80 Hz, light compression (3:1), de-ess, no reverb.

=== SOUND EFFECTS (subtle and sparing) ===
| Moment | SFX | Level |
|---|---|---|
| Move label slides in | soft whoosh (under 0.4 s) | -28 dB |
| Milestone banner | bright chime or bell + light crowd cheer (1–1.5 s) | -20 dB |
| Workout start (first step) | single upbeat "go" swell | -22 dB |
| Halfway and finish | short applause swell (2 s) | -20 dB |
| Health fact card | soft pop / bubble click | -28 dB |
| Final countdown of the workout | optional soft tick on each count | -30 dB |
Rules:
- At most 1 SFX per 20 seconds outside milestones.
- Never over the instructor's cue words.
- No cartoon, meme, record-scratch, airhorn or vine-boom sounds.

=== COLOR / LOOK ===
- Bright, clean, high-key: exposure lifted, faces natural, whites clean.
- Saturation +5 to +10 for wardrobe pops. Warm the white balance slightly
  (+150 K) on wood floors.
- No cinematic LUTs, no teal/orange, no heavy vignette, no film grain.
- Match all camera angles to the same exposure and white balance.

=== OUTPUT SPECS ===
Long-form:  1920×1080 (or 3840×2160), 16:9, 29.97 or 30 fps (match the
            source), H.264 High Profile, VBR 2-pass, 16 Mbps (1080p) or
            45 Mbps (4K). Audio AAC-LC 48 kHz stereo 320 kbps.
            Loudness -14 LUFS integrated, true peak -1 dBTP.
Shorts:     1080×1920, 9:16, 30 fps, H.264, 12 Mbps, under 60 s (up to 3 min
            allowed), same audio loudness spec.
Thumbnail:  1280×720 JPG/PNG under 2 MB (follow the channel thumbnail style).
Files:      [Title]_LONG_1080p.mp4, [Title]_SHORT_01.mp4, [Title].srt

=== DO ===
- Keep the instructor and her feet in frame at all times.
- Keep the workout in real time, start to finish.
- Label every move clearly in plain words.
- Celebrate every milestone visually and with sound.
- Show an easier option whenever the instructor gives one.
- Keep the screen clean, bright and readable from across a living room.
- Keep brand colors and the font consistent in every video.

=== DON'T ===
- Don't cut, speed up or remove any part of the workout.
- Don't cover faces, feet or the moving bodies with text.
- Don't use flashy transitions, shakes, glitches or meme effects.
- Don't put more than 3 overlays on screen at once.
- Don't burn in full captions on long-form (closed captions only).
- Don't let music or SFX drown out the counts and cues.
- Don't use copyrighted music.
- Don't show health claims on screen that the instructor didn't say.

=== WHAT TO GIVE ME BACK ===
1. EDIT DECISION LIST: a table with columns
   Timecode in | Timecode out | Camera angle | Section | Reason.
2. OVERLAY CUE SHEET: a table with columns
   Timecode in | Timecode out | Element | Exact text | Position | Animation.
3. SFX CUE SHEET: a table with columns
   Timecode | SFX | Level | Note.
4. MUSIC PLAN: tracks, BPM, crossfade points and ducking notes.
5. SRT FILE: the full closed-caption file in a code block.
6. SHORTS PLAN: 2–3 Shorts with source timecodes, a hook line and
   burned-in captions for each.
7. EXPORT CHECKLIST: settings for my editing software.
8. QA CHECK: confirm the workout timeline is unbroken, that no overlay covers
   the instructor, and that every move change has a label.
```

---

## Quick tips

- **Templates:** after the first video, save the move label, timer, milestone banner and badge as presets or templates in your editor. Then every video takes only text changes.
- **Transcript:** CapCut, Premiere and DaVinci Resolve can all export an SRT with timestamps. Paste that in as the transcript.
- **Long videos:** for a 30–45 minute workout, add *"Do the cue sheets for 0:00–15:00 first; I'll say 'continue' for the rest."*
