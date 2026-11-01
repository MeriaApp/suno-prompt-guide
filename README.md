# Suno Prompt Guide (v6)

A free, open reference for writing Suno prompts that get the song you meant: the three boxes, how to write the voice, 24 genre kits, 6 use-case kits and 12 voice lines to copy, plus what 12,843 real songs made with HookGenius show about how people prompt. Every number comes with how it was measured (last section).

Written by Jesse Meria, founder of [HookGenius](https://hookgenius.app/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide). Updated 1 November 2026. Licensed [CC BY 4.0](LICENSE): copy it, change it, publish it, with credit. Data files are in [`data/`](data/).

> HookGenius is an independent product and is not affiliated with, endorsed by or sponsored by Suno, Inc. "Suno" is used only to describe compatibility.

## Contents
1. [The three boxes](#the-three-boxes)
2. [Write the voice in four parts](#write-the-voice-in-four-parts)
3. [What 12,843 real songs show](#what-12843-real-songs-show)
4. [Genre kits](#genre-kits)
5. [Kits by what you are making](#kits-by-what-you-are-making)
6. [Voice lines](#voice-lines)
7. [Direct the song section by section](#direct-the-song-section-by-section)
8. [Use your own voice](#use-your-own-voice)
9. [When Suno ignores part of your prompt](#when-suno-ignores-part-of-your-prompt)
10. [How the numbers were measured](#how-the-numbers-were-measured)
11. [Cite this guide](#cite-this-guide)

## The three boxes

Suno v6 Custom mode has three text boxes. The limits below were read off the live v6 composer.

| Box | Limit | What goes in it |
|---|---|---|
| **Style** | 1,000 characters | The sound: genre and era, tempo, who sings and how, the instruments, the production, the mood. |
| **Lyrics** | 5,000 characters | Your words, with section tags like `[Verse]` and `[Chorus]` on their own lines. |
| **Exclude Styles** | 1,000 characters | Everything you do not want. "No autotune" goes here, never in Style. |

One complete prompt (an R&B slow jam). Paste each part into its box:

**Style**

```text
Late-90s R&B slow jam, 68 BPM, a smooth female lead with breathy verses and controlled runs on the last word of a line, layered harmonies on the chorus, Rhodes electric piano and a warm round bass, programmed drums with a soft finger-snap backbeat, close dry vocal with a little plate reverb on the harmonies, intimate and late-night
```

**Exclude Styles**

```text
trap hi-hats, distorted bass, rap verse
```

**Lyrics box: the layout**

```text
[Intro | Rhodes alone, a hummed line]

[Verse 1 | breathy, behind the beat]
(your lines here)

[Pre-Chorus | harmonies enter softly]
(your lines here)

[Chorus | layered harmonies, runs on the last word]
(your lines here)

[Verse 2 | same feel, a little more open]
(your lines here)

[Chorus | layered harmonies]
(your lines here)

[Bridge | key lift, the lead alone with Rhodes]
(your lines here)

[Chorus | ad-libs over the harmonies]
(your lines here)

[Outro | Rhodes and a hummed line]
```

## Write the voice in four parts

The voice is where a song lands or misses, and it is the part most people leave to chance. A voice line names four things:

| Part | What it says | Examples |
|---|---|---|
| **Who** | The voice type and range. | a low male baritone · a bright female alto · a male and female duet |
| **Texture** | What the voice is made of. | raspy · breathy · smooth · a little grit on the high notes |
| **Delivery** | How the words come out, and where they sit against the beat. | half-spoken verses · belted chorus · rapped just behind the beat |
| **Placement** | Where the vocal sits in the mix. | close and dry · wide reverb on the hook · doubled in the chorus |

Put the voice near the front of the Style box, before the instruments:

```text
Early-70s Southern soul, 70 BPM, a warm female alto with a little rasp, singing just behind the beat, close and dry in the verses and doubled in the chorus, Rhodes electric piano and a walking upright bass, brushed drums, a muted trumpet answering the vocal lines, tape-warm room sound, tender and nostalgic
```

## What 12,843 real songs show

HookGenius writes the Style and lyrics for songs people describe in their own words. These counts come from 12,843 songs real people made with it (our own testing left out), read on 1 November 2026.

**The genres people make**, counted once under the genre each Style names first:

| Genre | Share of songs |
|---|---|
| Hip-hop and rap | 15.4% |
| Electronic and dance | 11.6% |
| Pop | 9.6% |
| Rock, punk and metal | 8.9% |
| R&B and soul | 7.8% |
| Country, folk and Americana | 7.5% |
| Indie and alternative | 7.4% |
| Cinematic and orchestral | 6.5% |

801 of the 12,843 named no genre in their opening and count only in the total.

**How the Style describes the voice** (12,845 Style prompts; one can do several):

| The Style says… | Share |
|---|---|
| A texture: rasp, breath, grit, smoke | 55.2% |
| How close or dry the vocal sits | 28.0% |
| Harmonies or doubled vocals | 28.3% |
| A register: chest, head voice, falsetto | 18.1% |
| Where the voice sits against the beat | 16.9% |

**Other findings**

- People write more than you would think: typed descriptions had a median of 41 words (5,885 typed briefs); 15% were under ten words and 46% ran past 50.
- The Style prompts HookGenius sends to Suno use a median of 595 of the 1,000 characters.
- 47% of songs started from an artist or a song someone named (6,015 of 12,893). Naming them in the Style box is unreliable; describe the sound instead (see the fixes below).
- 24% of songs with a language set included one other than English (2,665 of 11,074).
- In a separate 2026 study of 3,483 tracks, three in four creators left the voice on the default.

## Genre kits

In the order people make them. Each genre has one full kit (Style, Exclude Styles and a lyric layout) and two variations.

### Hip-hop and rap (15.4%)

The genre people ask us for most, and the one where the voice decides everything. Say whether the verses are rapped or half-sung, where the delivery sits against the beat, and how dry the vocal is.

#### Late-night melodic trap

Style:

```text
Melodic trap, 140 BPM in half-time, a smooth male tenor with light pitch correction, sung hooks and rapped verses that sit just behind the beat, gliding 808 bass under dark atmospheric synth pads, crisp rolling hi-hats with short triplet runs, a filtered piano loop in the intro, wide reverb on the hook and a close dry verse vocal, moody and reflective
```

Exclude Styles: `live drums, acoustic guitar, choir, cheerful pop`

Lyrics box layout:

```text
[Intro | filtered piano loop, 808 enters on the last bar]

[Verse 1 | rapped, close and dry, sparse hi-hats]
(your lines here)

[Hook | sung, wide reverb, full 808 and hats]
(your lines here)

[Verse 2 | rapped, a little more urgent, triplet hats]
(your lines here)

[Hook | sung, same as before]
(your lines here)

[Bridge | half-sung, drums drop out, pads only]
(your lines here)

[Hook | sung, everything back in]
(your lines here)

[Outro | piano loop alone, fades]
```

#### 90s boom bap storytelling

Style:

```text
Mid-90s East Coast boom bap, 92 BPM, a confident male rapper with a conversational storytelling flow and clear diction, dusty sampled jazz piano and an upright bass loop, hard swung drums with a crunchy snare, vinyl crackle, scratched hook phrases from a turntable, mono-leaning mix with the vocal up front, nostalgic and gritty
```

Exclude Styles: `autotune, 808 slides, synth pads, trap hi-hats`

#### Bright party rap

Style:

```text
Upbeat West Coast party rap, 98 BPM, a playful female rapper with a bouncy, rhythmic flow and call-and-response ad-libs, rubbery synth bass and a talk-box style lead, handclaps on two and four, a whistled melody in the hook, group chant on the chorus, bright polished mix, sunny and confident
```

Exclude Styles: `dark pads, distorted 808, slow tempo`

More: [more hip-hop prompts](https://hookgenius.app/learn/suno-hip-hop-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### Electronic and dance (11.6%)

Dance tracks live on arrangement. Name the build and the drop in the lyric layout, and keep the Style box to the sound: tempo, kick, bass, the lead, and how much vocal there is.

#### Melodic house with a vocal chop

Style:

```text
Melodic house, 122 BPM, warm four-on-the-floor kick and rolling sub bass, a plucked synth arpeggio that slowly opens its filter, airy pads, a chopped female vocal used as an instrument with one short sung line in the breakdown, long builds with a snare roll and riser into each drop, spacious club mix, euphoric and warm
```

Exclude Styles: `rap verses, acoustic guitar, dubstep wobble`

Lyrics box layout:

```text
[Intro | kick and hats, filter closed]

[Build | arpeggio opens, snare roll, riser]

[Drop | full bass and lead, vocal chop as hook]
(your lines here)

[Breakdown | pads only, one sung line, no kick]
(your lines here)

[Build | longer this time, riser and noise sweep]

[Drop | everything in, the biggest moment]
(your lines here)

[Outro | kick and bass, filter closes]
```

#### Liquid drum and bass

Style:

```text
Liquid drum and bass, 174 BPM, a soft breathy female vocal floating over fast rolling breakbeats, deep smooth reese bass, lush Rhodes chords and string pads, rain-like texture in the intro, the vocal sung in long held notes against the fast drums, clean wide mix, melancholy and hopeful
```

Exclude Styles: `heavy distortion, rap, four-on-the-floor kick`

#### Dark warehouse techno

Style:

```text
Dark warehouse techno, 132 BPM, instrumental, a pounding distorted kick and rumbling sub, metallic percussion and an off-beat open hat, a hypnotic one-note synth stab that mutates slowly, industrial noise sweeps, long tension with a stripped breakdown before the return, raw and relentless
```

Exclude Styles: `vocals, singing, piano, bright pop synths`

More: [more dance prompts](https://hookgenius.app/learn/suno-edm-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### Pop (9.6%)

Pop prompts fail by being vague. Give the era, the tempo, the one instrument the song is built around, and what the voice does in the chorus that it does not do in the verse.

#### Bedroom pop heartbreak

Style:

```text
Bedroom pop, 96 BPM, an intimate female vocal sung soft and close in the verses that opens up into a doubled chorus, clean electric guitar with a little chorus effect, soft programmed drums, warm bass, a lo-fi tape texture on the whole mix, small harmonies on the last chorus line, bittersweet and catchy
```

Exclude Styles: `belting, EDM drop, rap verse`

Lyrics box layout:

```text
[Intro | guitar alone, tape hiss]

[Verse 1 | close soft vocal, drums enter halfway]
(your lines here)

[Pre-Chorus | bass climbs, vocal lifts]
(your lines here)

[Chorus | doubled vocal, full drums, the hook line twice]
(your lines here)

[Verse 2 | same feel, one new guitar figure]
(your lines here)

[Chorus | doubled, harmonies on the last line]
(your lines here)

[Bridge | drums out, vocal and guitar only]
(your lines here)

[Chorus | biggest, then stops on the last word]
(your lines here)
```

#### 80s synth-pop anthem

Style:

```text
Mid-80s synth-pop, 118 BPM, a bright male tenor with an earnest, soaring chorus, gated reverb snare, punchy drum machine, analog synth bass in eighth notes, shimmering poly-synth chords and a memorable lead synth riff, a short saxophone solo after the second chorus, big glossy mix, nostalgic and euphoric
```

Exclude Styles: `trap hi-hats, autotune, modern 808`

#### Acoustic pop love song

Style:

```text
Acoustic pop ballad, 72 BPM, a warm male vocal sung gently with a natural, unpolished tone, fingerpicked acoustic guitar carrying the song, soft piano entering in the second verse, light strings in the final chorus, close intimate recording with a short room reverb, tender and hopeful
```

Exclude Styles: `drums in the first verse, electric guitar, synths`

More: [more pop prompts](https://hookgenius.app/learn/suno-pop-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### Rock, punk and metal (8.9%)

Rock lives in the guitar tone and the room. Say how distorted, how many guitars, whether the drums are tight or loose, and whether the singer is clean, raspy or screaming.

#### 2000s pop-punk

Style:

```text
2000s pop-punk, 168 BPM, a bright male vocal with a slight nasal snarl and gang-shout backing vocals on the chorus, two palm-muted distorted guitars panned wide, driving bass following the root, fast tight punk drums with a double-time chorus, short stop before the last chorus, loud and energetic, defiant and fun
```

Exclude Styles: `synths, slow ballad, growled vocals`

Lyrics box layout:

```text
[Intro | one guitar, then the band crashes in]

[Verse 1 | palm-muted, fast, vocal up front]
(your lines here)

[Pre-Chorus | drums build, guitars open up]
(your lines here)

[Chorus | double-time, gang shouts]
(your lines here)

[Verse 2 | same drive, a little louder]
(your lines here)

[Chorus | gang shouts]
(your lines here)

[Bridge | half-time breakdown, bass and voice]
(your lines here)

[Chorus | stop for one beat, then the last chorus]
(your lines here)
```

#### Grunge slow burn

Style:

```text
Early-90s grunge, 84 BPM, a raspy, weary male baritone that goes from mumbled verses to a strained, shouted chorus, a clean chorus-effect guitar in the verses and thick fuzz guitars in the chorus, heavy loose drums with a big room sound, distorted bass, raw live-band mix, brooding and heavy
```

Exclude Styles: `polished pop production, synths, falsetto`

#### Melodic metalcore

Style:

```text
Melodic metalcore, 150 BPM, harsh screamed verses and a soaring clean male chorus, down-tuned chugging guitars with a melodic lead line, fast double-kick drums with blast beats in the bridge, a heavy breakdown with half-time drums before the final chorus, tight modern metal production, intense and cathartic
```

Exclude Styles: `acoustic guitar, pop drums, rap`

More: [more rock prompts](https://hookgenius.app/learn/suno-rock-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### R&B and soul (7.8%)

R&B is about feel. Tell Suno where the vocal sits against the beat, what kind of runs it does, and whether the drums are programmed or played.

#### Late-90s slow jam

Style:

```text
Late-90s R&B slow jam, 68 BPM, a smooth female lead with breathy verses and controlled runs on the last word of a line, layered harmonies on the chorus, Rhodes electric piano and a warm round bass, programmed drums with a soft finger-snap backbeat, close dry vocal with a little plate reverb on the harmonies, intimate and late-night
```

Exclude Styles: `trap hi-hats, distorted bass, rap verse`

Lyrics box layout:

```text
[Intro | Rhodes alone, a hummed line]

[Verse 1 | breathy, behind the beat]
(your lines here)

[Pre-Chorus | harmonies enter softly]
(your lines here)

[Chorus | layered harmonies, runs on the last word]
(your lines here)

[Verse 2 | same feel, a little more open]
(your lines here)

[Chorus | layered harmonies]
(your lines here)

[Bridge | key lift, the lead alone with Rhodes]
(your lines here)

[Chorus | ad-libs over the harmonies]
(your lines here)

[Outro | Rhodes and a hummed line]
```

#### Neo-soul groove

Style:

```text
Neo-soul, 86 BPM, a warm male vocal with a relaxed, conversational delivery and falsetto lifts, live drums played loose and behind the beat, muted electric guitar licks, round upright-style bass, Rhodes chords with extended jazz harmony, a short horn line in the chorus, warm analog tape mix, easy and joyful
```

Exclude Styles: `autotune, EDM synths, 808`

#### Modern alt R&B

Style:

```text
Modern alternative R&B, 78 BPM, a hushed male vocal with falsetto in the hook and pitched-down vocal layers as texture, sparse minimal beat with a deep sub bass and crisp snaps, hazy reverb-washed synth pads, a short reversed guitar phrase between lines, lots of space in the mix, moody and cool
```

Exclude Styles: `big pop chorus, live band, belting`

More: [more R&B prompts](https://hookgenius.app/learn/suno-rnb-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### Country, folk and Americana (7.5%)

Here the story carries the song, so the Style box should stay out of its way. Name the instruments, the era of the production and the voice, and let the lyrics tell it.

#### Modern country story song

Style:

```text
Modern country, 92 BPM, a warm male baritone with a slight Southern drawl and plain-spoken storytelling delivery, acoustic guitar strumming, pedal steel answering the vocal lines, warm bass and a steady drum groove with a rimshot verse and full kit chorus, a short fiddle fill before the bridge, clean Nashville production, nostalgic and proud
```

Exclude Styles: `rap, synths, autotune`

Lyrics box layout:

```text
[Intro | acoustic and pedal steel]

[Verse 1 | rimshot groove, the story starts]
(your lines here)

[Chorus | full kit, the title line]
(your lines here)

[Verse 2 | the story moves forward]
(your lines here)

[Chorus | full kit]
(your lines here)

[Bridge | fiddle fill, then drums drop out]
(your lines here)

[Chorus | last time, with a changed final line]
(your lines here)
```

#### Front-porch folk

Style:

```text
Intimate indie folk, 80 BPM, a soft female vocal close to the microphone with a gentle harmony from a second voice in the chorus, fingerpicked acoustic guitar, a light banjo roll in the second verse, upright bass, brushed snare entering late, a recording that sounds like one room, wistful and calm
```

Exclude Styles: `electric guitar, heavy drums, polished pop`

#### Desert Americana

Style:

```text
Dusty Americana, 104 BPM, a gravelly male vocal with a laid-back half-spoken verse and a fuller chorus, twangy baritone electric guitar with tremolo, acoustic rhythm guitar, a loose shuffling drum groove, harmonica in the intro and the outro, wide open reverb like an empty desert, restless and free
```

Exclude Styles: `synths, pop drums, rap`

More: [more country prompts](https://hookgenius.app/learn/suno-country-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### Indie and alternative (7.4%)

Indie prompts are about texture: which guitar, how much reverb, how present the voice is. A specific era and one unusual instrument go further than a list of moods.

#### Dream pop haze

Style:

```text
Dream pop, 90 BPM, a breathy female vocal sitting inside the mix with long reverb tails, shimmering chorus-drenched electric guitars, a steady simple drum machine pulse, warm melodic bass, swelling synth pads, soft vocal harmonies an octave up in the chorus, washed-out lo-fi warmth, hazy and nostalgic
```

Exclude Styles: `rap, sharp EDM drums, belting`

Lyrics box layout:

```text
[Intro | guitar shimmer and pads]

[Verse 1 | voice low in the mix, pulse beat]
(your lines here)

[Chorus | octave harmonies, pads swell]
(your lines here)

[Verse 2 | a second guitar enters]
(your lines here)

[Chorus | octave harmonies]
(your lines here)

[Instrumental | guitar melody over pads]

[Chorus | fullest, then fades into reverb]
(your lines here)
```

#### Garage indie rock

Style:

```text
2000s garage indie rock, 132 BPM, a cool, slightly detached male vocal with a sharp shouted chorus, two scrappy overdriven guitars with angular riffs, a tight driving bass, fast dance-punk drums with an open hi-hat, handclaps in the chorus, raw and close live-room sound, restless and fun
```

Exclude Styles: `synth pads, ballad, autotune`

#### Sad indie piano

Style:

```text
Sparse indie ballad, 70 BPM, a fragile male vocal sung quietly with audible breath, felt piano recorded close with the pedal noise left in, soft cello entering in the second verse, a distant reverb guitar swell in the bridge, drums held back until the last chorus and then only a soft kick, tender and devastating
```

Exclude Styles: `heavy drums, synths, upbeat tempo`

More: [more indie prompts](https://hookgenius.app/learn/suno-indie-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

### Cinematic and orchestral (6.5%)

Score-style tracks need a shape more than a hook. Describe how it starts, where it peaks and what carries the melody, and say plainly if you want no singing at all.

#### Epic trailer build

Style:

```text
Epic cinematic trailer music, 90 BPM, instrumental, a lone piano motif that grows into full orchestra, low brass swells, driving staccato strings, massive taiko and orchestral percussion hits, a wordless choir on the final climax, long rising tension with a silent beat before the last hit, huge wide hall reverb, heroic and powerful
```

Exclude Styles: `pop drums, rap, sung lyrics`

Lyrics box layout:

```text
[Intro | lone piano motif]

[Build | strings ostinato, low brass]

[Build | percussion enters, tension rises]

[Drop | full orchestra and choir, the motif in brass]

[Breakdown | one silent beat]

[Outro | final hit, piano motif returns alone]
```

#### Fantasy village theme

Style:

```text
Gentle fantasy orchestral theme, 76 BPM, instrumental, a solo flute melody over plucked harp and pizzicato strings, warm French horn answering phrases, light hand percussion, a soft string swell in the middle, bright and open hall sound, peaceful and adventurous
```

Exclude Styles: `drum kit, electric guitar, vocals`

#### Dark thriller score

Style:

```text
Dark thriller score, 120 BPM, instrumental, a pulsing synth bass ostinato under tense string tremolos, ticking percussion and sharp metallic hits, brass stabs on the downbeats, a rising dissonant string line, hybrid orchestral and electronic production, urgent and suspenseful
```

Exclude Styles: `vocals, melodic pop, acoustic guitar`

More: [more cinematic prompts](https://hookgenius.app/learn/suno-epic-cinematic-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide)

## Kits by what you are making

Background music has a different job from a song: steady, no surprises, and vocals left out where a voice would compete with someone talking.

### YouTube background

```text
Calm lo-fi hip-hop, 78 BPM, instrumental, dusty jazz piano chords, soft swung drums with a gentle snare, warm bass, vinyl crackle and light tape wobble, the same steady groove from start to end, relaxed and focused
```

Exclude Styles: `vocals, singing, loud drops, sudden changes`

### Podcast intro, 15 seconds

```text
Short upbeat podcast intro, 110 BPM, instrumental, punchy funk bass and tight drums, bright electric guitar stabs, a quick brass hit at the end, clean modern mix, confident and friendly
```

Exclude Styles: `vocals, long intro, slow fade`

### Wedding first dance

```text
Romantic soul ballad, 70 BPM, a warm male and female duet trading verses and singing the last chorus together, piano and soft strings, gentle live drums entering in the second verse, warm close recording, tender and joyful
```

Exclude Styles: `rap, EDM, heavy guitar`

### Short video hook

```text
Catchy dance-pop, 124 BPM, a bright female vocal with a short chanted hook in the first five seconds, punchy kick and clap, bouncy synth bass, a playful vocal chop riff, loud polished mix, fun and confident
```

Exclude Styles: `slow intro, ballad, long instrumental start`

### Study beat

```text
Ambient study music, 70 BPM, instrumental, soft felt piano and warm synth pads, a gentle low-volume pulse, distant rain texture, slow evolving chords, calm and steady
```

Exclude Styles: `vocals, drums, sudden changes, bright leads`

### Game level loop

```text
Upbeat chiptune game music, 140 BPM, instrumental, bright square-wave lead melody, bouncy triangle bass, crunchy 8-bit drums, a short arpeggio fill every four bars, loops cleanly, playful and adventurous
```

Exclude Styles: `vocals, orchestra, realistic drums`

## Voice lines

Each voice line on its own, then inside a complete Style.

### Low male

#### Deep baritone crooner

Voice line: *a deep, smooth male baritone crooning slowly, a lot of air on the low notes, close and warm*

```text
Smoky jazz ballad, 66 BPM, a deep, smooth male baritone crooning slowly, a lot of air on the low notes, close and warm, brushed drums, upright bass, soft piano chords, a tenor sax answering each line, late-night club room sound, intimate and wistful
```

Exclude Styles: `autotune, falsetto, modern pop drums`

#### Gravelly storyteller

Voice line: *a gravelly, weathered male baritone, half-spoken in the verses and fuller in the chorus, unhurried*

```text
Dusty Americana, 92 BPM, a gravelly, weathered male baritone, half-spoken in the verses and fuller in the chorus, unhurried, acoustic guitar, pedal steel, a loose shuffle on the drums, warm bass, wide open room reverb, reflective and tired
```

Exclude Styles: `autotune, pop polish, synths`

### High male

#### Falsetto R&B lead

Voice line: *a soft male tenor that floats up into falsetto on the hook, breathy and close, small runs on the last word*

```text
Modern R&B, 74 BPM, a soft male tenor that floats up into falsetto on the hook, breathy and close, small runs on the last word, warm sub bass, snaps and a minimal beat, hazy synth pads, a reversed guitar phrase between lines, spacious and moody
```

Exclude Styles: `belting, rap verse, rock guitar`

#### Raspy rock tenor

Voice line: *a raspy male tenor that strains and shouts on the chorus, ahead of the beat, doubled for the chorus*

```text
Arena rock, 128 BPM, a raspy male tenor that strains and shouts on the chorus, ahead of the beat, doubled for the chorus, two crunchy overdriven guitars, driving bass, big live drums with a room sound, gang vocals on the last chorus, defiant and loud
```

Exclude Styles: `synth pads, falsetto, autotune`

### Low and mid female

#### Smoky alto

Voice line: *a smoky, low female alto, unhurried and behind the beat, close-miked with a short room reverb*

```text
Slow electric blues, 70 BPM, a smoky, low female alto, unhurried and behind the beat, close-miked with a short room reverb, a clean electric guitar with tremolo answering her lines, organ pads, upright bass, brushed drums, after-hours and sultry
```

Exclude Styles: `autotune, bright pop production, rap`

#### Conversational indie alto

Voice line: *a plain, conversational female alto, almost spoken in the verses, doubled softly in the chorus, dry and close*

```text
Bedroom indie pop, 98 BPM, a plain, conversational female alto, almost spoken in the verses, doubled softly in the chorus, dry and close, clean chorus-effect guitar, soft programmed drums, warm bass, a lo-fi tape texture, wry and catchy
```

Exclude Styles: `belting, EDM drop, choir`

### High female

#### Belting pop soprano

Voice line: *a powerful female soprano, soft and close in the verses, opening into a full belt on the last chorus*

```text
Big pop ballad, 72 BPM, a powerful female soprano, soft and close in the verses, opening into a full belt on the last chorus, grand piano, swelling strings, a key change before the final chorus, live drums entering in the second verse, polished wide mix, triumphant and emotional
```

Exclude Styles: `rap, autotune, lo-fi texture`

#### Airy dream-pop soprano

Voice line: *an airy, breathy female soprano sitting inside the mix with long reverb tails, harmonies an octave up*

```text
Dream pop, 90 BPM, an airy, breathy female soprano sitting inside the mix with long reverb tails, harmonies an octave up, shimmering guitars, a steady drum machine pulse, warm bass, swelling pads, hazy and nostalgic
```

Exclude Styles: `belting, rap, sharp EDM drums`

### Rap delivery

#### Laid-back storyteller flow

Voice line: *a relaxed male rapper with a conversational storytelling flow, sitting just behind the beat, clear diction, dry and up front*

```text
Boom bap, 90 BPM, a relaxed male rapper with a conversational storytelling flow, sitting just behind the beat, clear diction, dry and up front, dusty jazz piano sample, upright bass loop, swung drums with a crunchy snare, vinyl crackle, nostalgic
```

Exclude Styles: `autotune, singing hook, synth pads`

#### Sung hook, rapped verses

Voice line: *a female voice that raps the verses in a quick, bouncy flow and sings the hook, light pitch correction, ad-libs panned wide*

```text
Melodic rap, 140 BPM in half-time, a female voice that raps the verses in a quick, bouncy flow and sings the hook, light pitch correction, ad-libs panned wide, gliding 808 bass, rolling hi-hats, bright plucked synth melody, playful and confident
```

Exclude Styles: `live band, slow ballad, choir`

### More than one voice

#### Male and female duet

Voice line: *a male and female duet trading verses, his voice low and warm, hers higher and bright, both together on the last chorus*

```text
Soul-pop duet, 84 BPM, a male and female duet trading verses, his voice low and warm, hers higher and bright, both together on the last chorus, piano and Rhodes, warm bass, live drums with a soft backbeat, light strings in the bridge, tender and hopeful
```

Exclude Styles: `rap, EDM synths, autotune`

#### Gospel lead with choir

Voice line: *a soulful female lead with call-and-response from a full choir, the choir answering every line of the chorus*

```text
Contemporary gospel, 76 BPM, a soulful female lead with call-and-response from a full choir, the choir answering every line of the chorus, Hammond organ, piano, bass and live drums building from soft to full, handclaps in the last chorus, uplifting and joyful
```

Exclude Styles: `autotune, trap drums, solo-only vocal`

## Direct the song section by section

The Style box describes the song as a whole. When something should change, a quiet verse and a big chorus, the drums dropping out in the bridge, write a short direction inside the section tag in the Lyrics box. This is how HookGenius writes them:

```text
[Verse 1 | close and dry, half-spoken, almost a whisper]
(your lines here)

[Pre-Chorus | voice lifts, a second voice joins quietly]
(your lines here)

[Chorus | full voice, doubled, wide reverb]
(your lines here)

[Bridge | voice alone over piano, falsetto on the last line]
(your lines here)

[Chorus | biggest, ad-libs over the top]
(your lines here)
```

## Use your own voice

Suno's Voices feature puts your own voice on the songs it makes. From Suno's help article [Voices: Use Your Voice in Suno](https://help.suno.com/en/articles/11362369), read 1 November 2026:

1. Click Add Voice in Create, then Create Voice.
2. Give it your voice: a song from your Suno library that already has your voice, a live recording, or an uploaded file. A clip of 15 seconds to 4 minutes works, and you choose the best 2 minutes. Suno says vocals without music work best, and it will split the vocal out of a file that has music.
3. Read a short phrase aloud. Suno compares it with your singing to check it is the same person.
4. Name the voice, confirm you have the rights to it, and save.
5. Write the song as usual: your lyrics, your style descriptors, a title.

Suno's own steps still ask for style descriptors, so the voice line still has a place in the Style box.

## When Suno ignores part of your prompt

**Put what you do not want in Exclude Styles, not in Style.** When a Style prompt says “no reverb” or “no autotune”, Suno does not reliably honour it, and sometimes renders the very thing. We measured it over 585 generations. Every kit in this guide keeps the Style box to what you want and lists the rest under Exclude Styles.

**Describe the artist instead of naming them.** Names in the Style box are unreliable. We have seen Suno read an ordinary word as a name: “capo”, as in a guitar capo, came back with a German rapper’s genre tags. Write what you hear in their music instead: the era, the tempo, the voice, the instruments, the production.

**Say who is singing and how.** In our 2026 data study of 3,483 tracks, three in four creators left the voice on the default. Yet the voice is where a song lands or misses: who sings, how high or low, breathy or belted, ahead of the beat or behind it, close and dry or far away. The Style prompts HookGenius writes use a median of 595 of the 1,000 characters, so there is room for all of it.

**Put the arrangement in the lyric layout.** The Style box says what the song sounds like. Changes over time, a drop, drums cutting out in the bridge, a key lift, read better as short directions inside the section tags: [Bridge | drums drop out, voice and piano].

**Two instructions that disagree cancel out.** “Intimate” and “stadium-sized”, “lo-fi” and “glossy”: when two words pull opposite ways, Suno has to choose, and it may not choose yours. Read your prompt once just for contradictions.

**Suno keeps giving you the wrong voice.** Name the voice early in the Style box, before the instruments, and put the voice you do not want in Exclude Styles: “male vocals” when you want a woman singing, “female vocals” when you want a man. Every voice line in this guide sits near the front of its Style.

**The voice is right but the delivery is flat.** Add one delivery phrase: where it sits against the beat (“just behind the beat”), how much it pushes (“half-spoken verses, belted chorus”), or one texture (“a little rasp”). Pick one clear phrase rather than stacking five adjectives.

**The vocal is buried.** Say where it sits: “vocal up front”, “close and dry”, “doubled in the chorus”. Then check that the instruments in your Style are not all described as huge and wide.

## How the numbers were measured

- **Corpus:** the style prompt of every song made in HookGenius by a real user, read from our generation records on 1 November 2026. Accounts used for our own testing are excluded. Counts only; no one's words are published.
- **Genres:** the opening 120 characters of each Style, matched against genre families; each song counts once, under the family named first. Spot-checked by reading random openings before publishing.
- **Voice descriptions:** each Style read for a texture word, a placement phrase, a register, harmonies or doubles, and where the voice sits against the beat.
- **"No X" in Style:** 585 generations, 2026-08-25.
- **Box limits:** read off the live Suno v6 composer.
- **Suno Voices:** Suno's own help article, read on the date above.
- Data files: [`data/genre-demand.csv`](data/genre-demand.csv), [`data/voice-descriptions.csv`](data/voice-descriptions.csv), [`data/kits.json`](data/kits.json).

## Cite this guide

Meria, J. (2026). *Suno Prompt Guide (v6)*. HookGenius. https://github.com/MeriaApp/suno-prompt-guide

The same material, with a real song beside its prompt, is on the web at [https://hookgenius.app/suno-prompts/](https://hookgenius.app/suno-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide) and [https://hookgenius.app/learn/suno-vocal-prompts/](https://hookgenius.app/learn/suno-vocal-prompts/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide). If you would rather describe the song in a sentence and get the whole prompt written, that is what [HookGenius](https://hookgenius.app/?utm_source=github&utm_medium=guide&utm_campaign=suno-prompt-guide) does (five free songs).

Corrections and additions are welcome as issues or pull requests.
