# FeatureBot — TTS as inclusion default (every app)

**Diego lock (2026-09-19):** Text-to-speech on every project — TechWorks · Baboo · Koderized · BertyCAD · Tech Room.  
**Law:** Never audio-only. Always pair with on-screen text / captions (D/HH).

## One recommended Chromebook pattern

| Rule | Why |
|------|-----|
| **Fat Speak control ≥44×44** next to the text being read (icon + “Speak” / “Leer”) | Motor / low-vis; first-try tap |
| **Same words visible** while speaking (highlight or caption plate) | D/HH + multilingual follow without sound |
| **Teacher/student start only** — no autoplay on load or Wall | ED/regulation; classroom calm |
| **EN/ES use same Speak path** | One control, language already chosen |
| **Browser `speechSynthesis` first** (Chromebook-safe); no heavy SDK | Mid/low Chromebook; works offline-ish once voices cached |
| **Mute / Stop always visible** while speaking | Escape hatch for ED / overload |

## Runner-up
App-hosted audio files — only if browser TTS fails quality bar; still require captions.

## Out of scope
- Voice memos in Office chat (Diego: choices not voices)
- Replacing Curriculum copy with speech-only lessons

## Prove (per app after Build)
1. Speak button visible with the sentence.  
2. Headphones off: student can still complete from text alone.  
3. Stop works mid-sentence.  
4. No autoplay on cold open.

## Owners
Flo assigns per app · Debugzy/Build wire · StyleBot icon+contrast · Curriculum plain lines under Speak · FeatureBot pattern = this file.

