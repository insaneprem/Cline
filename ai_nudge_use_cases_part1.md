# AI Nudge Engine — Use Cases (Part 1: Cases 1–12)

---

## UC-1: 🔙 Lost in UI — Recovery Nudge

| Dimension | Detail |
|---|---|
| **Category** | Navigation Recovery |
| **Problem** | User accidentally enters an unfamiliar app/overlay/menu and panics — presses random buttons trying to escape |
| **User Behavior Detected** | Burst of `BACK` + random directional keys within 5-10 sec outside normal TV viewing context |
| **AI Understanding** | User is lost in an unfamiliar UI layer and doesn't know how to return to live TV |
| **Suggested Nudge** | 🏠 *"Looks like you're trying to get back. Press **HOME** to return to live TV."* |
| **UX Pattern** | Smart Overlay — center screen, high urgency |
| **Why It Improves UX** | Eliminates panic moments instantly; user feels the TV "understands" them |
| **Business Impact** | ↓ Support calls by 15-20% for navigation issues; ↑ user confidence with the platform |
| **Type** | ✅ Safe / Realistic |

---

## UC-2: 🔊 Auto Volume Leveling Nudge

| Dimension | Detail |
|---|---|
| **Category** | Settings Discovery |
| **Problem** | Different satellite channels broadcast at different volume levels — user constantly adjusts volume after every channel switch |
| **User Behavior Detected** | Volume key presses within 5 sec of every channel change, repeated across 3+ consecutive switches |
| **AI Understanding** | Volume inconsistency across channels is causing repeated manual adjustments |
| **Suggested Nudge** | 🔊 *"Volume keeps changing? Enable **Auto Volume Leveling** for consistent sound."* `[Enable Now]` |
| **UX Pattern** | Contextual Action Card — appears near volume indicator |
| **Why It Improves UX** | Surfaces a hidden setting at the exact moment the user needs it — not as a tutorial, but as a solution |
| **Business Impact** | ↑ Feature adoption for auto-volume (typically <5% usage); ↓ perceived quality complaints |
| **Type** | ✅ Safe / Realistic |

---

## UC-3: 👶 Child Random Press — Lock Nudge

| Dimension | Detail |
|---|---|
| **Category** | Safety & Parental Control |
| **Problem** | A child grabs the remote and presses keys erratically — changes channels, enters menus, messes up settings |
| **User Behavior Detected** | High entropy key press pattern — random mix of all key types in rapid bursts with no logical navigation sequence |
| **AI Understanding** | The interaction pattern is non-human-intentional — likely a child or accidental remote activation |
| **Suggested Nudge** | 🔒 *"Unusual activity detected. **Enable child lock** to prevent accidental changes?"* `[Enable]` `[Ignore]` |
| **UX Pattern** | Smart Overlay with two clear actions |
| **Why It Improves UX** | Prevents settings corruption, channel loss, and parental frustration; proactive safety |
| **Business Impact** | ↑ Parental control feature adoption; ↑ household trust in Samsung TV; ↓ "my TV settings got messed up" support calls |
| **Type** | ✅ Safe / Realistic |

---

## UC-4: 👴 Elderly Simplified Mode Nudge

| Dimension | Detail |
|---|---|
| **Category** | Accessibility |
| **Problem** | Elderly users navigate extremely slowly, press wrong keys often, and get confused by complex menus |
| **User Behavior Detected** | Consistently slow key press intervals (3-5 sec gaps) + frequent `BACK` presses after every 1-2 navigation steps (hesitant trial-and-error) over multiple sessions |
| **AI Understanding** | User's interaction pattern indicates difficulty with the current UI complexity — likely an elderly or less tech-savvy user |
| **Suggested Nudge** | 👴 *"Would you like to switch to **Easy Mode**? Bigger text, simpler menus, fewer steps."* `[Try Easy Mode]` |
| **UX Pattern** | Contextual Action Card — shown during a menu navigation session |
| **Why It Improves UX** | Transforms an overwhelming experience into a comfortable one; user feels cared for, not judged |
| **Business Impact** | ↑ Elderly user retention; ↓ dependency on family members to operate TV; opens 60+ demographic engagement |
| **Type** | ✅ Safe / Realistic |

---

## UC-5: 🔇 Accidental Mute Recovery Nudge

| Dimension | Detail |
|---|---|
| **Category** | Friction Reducer |
| **Problem** | User accidentally presses MUTE, doesn't notice the small mute icon, thinks audio is broken — frantically presses volume up |
| **User Behavior Detected** | `MUTE` key pressed → followed by 3+ `VOL UP` presses within 10 sec |
| **AI Understanding** | User pressed mute accidentally and doesn't realize the TV is muted — they think volume is broken |
| **Suggested Nudge** | 🔇 *"Your TV is on **MUTE**. Press the mute button again to unmute."* |
| **UX Pattern** | Ghost Toast — bottom-right, auto-dismisses in 5 sec |
| **Why It Improves UX** | Solves a surprisingly common real-world frustration in seconds; makes TV feel intelligent |
| **Business Impact** | ↓ "No audio" support calls (one of the top TV support issues globally) |
| **Type** | ✅ Safe / Realistic |

---

## UC-6: 📺 Channel Number Shortcut Nudge

| Dimension | Detail |
|---|---|
| **Category** | Friction Reducer |
| **Problem** | User wants to go from channel 50 to channel 350 but keeps pressing `CH UP` repeatedly instead of typing the channel number directly |
| **User Behavior Detected** | `CH UP` or `CH DOWN` pressed 15+ times in one continuous streak |
| **AI Understanding** | User is navigating channels linearly to reach a distant channel — they may not know they can type the number directly |
| **Suggested Nudge** | 🔢 *"Going far? **Type the channel number** on your remote for instant switching."* |
| **UX Pattern** | Ghost Toast — appears during the channel surfing streak |
| **Why It Improves UX** | Teaches a fundamental shortcut at the moment of need; saves minutes of frustration |
| **Business Impact** | ↑ User efficiency; ↓ perceived slowness of the TV platform |
| **Type** | ✅ Safe / Realistic |

---

## UC-7: 🔁 Menu Loop Detection — "Can't Find It" Nudge

| Dimension | Detail |
|---|---|
| **Category** | Navigation Recovery |
| **Problem** | User enters the same menu path 3+ times in a session — they're clearly looking for something and can't find it |
| **User Behavior Detected** | Same navigation sequence (e.g., Settings → Display → back → Settings → Display) repeated 3+ times within 5 minutes |
| **AI Understanding** | User is stuck in a navigation loop — they know roughly where a feature should be but can't locate it |
| **Suggested Nudge** | 🔍 *"Looking for something? **Tell us what you need** and we'll take you there."* `[Search Settings]` |
| **UX Pattern** | Contextual Action Card with search shortcut |
| **Why It Improves UX** | Converts frustration into instant resolution; makes the settings menu feel searchable and smart |
| **Business Impact** | ↓ Settings-related support tickets; ↑ feature discoverability; ↑ user satisfaction scores |
| **Type** | ✅ Safe / Realistic |

---

## UC-8: 🌙 Night Eye Comfort Nudge

| Dimension | Detail |
|---|---|
| **Category** | Health & Wellness |
| **Problem** | User is watching TV late at night (11 PM+) with full brightness — causes eye strain and disrupts sleep cycle |
| **User Behavior Detected** | Active viewing session detected after 11 PM with brightness at default/high level; no eye comfort mode enabled |
| **AI Understanding** | Late-night viewing with high brightness is a health concern — user may not know about night mode |
| **Suggested Nudge** | 🌙 *"It's getting late. **Enable Eye Comfort Mode** for reduced blue light and warmer colors?"* `[Enable]` |
| **UX Pattern** | Ghost Toast — subtle, non-intrusive |
| **Why It Improves UX** | Shows the TV cares about user health; surfaces a premium feature at the perfect moment |
| **Business Impact** | ↑ Eye comfort mode adoption; Samsung can market "Health-aware TV" as a differentiator |
| **Type** | ✅ Safe / Realistic |

---

## UC-9: 😤 Frustration Detection — Calm Assist Nudge

| Dimension | Detail |
|---|---|
| **Category** | Emotional Intelligence |
| **Problem** | TV is lagging or user can't figure out how to do something — they hammer the same key aggressively |
| **User Behavior Detected** | Same key pressed 8+ times within 3 seconds (aggressive repeated pressing far beyond normal input speed) |
| **AI Understanding** | User is frustrated — either the TV is not responding (lag) or the user expects a different result from the key |
| **Suggested Nudge** | *"The TV may be processing. **Please wait a moment**, or press HOME to start fresh."* |
| **UX Pattern** | Smart Overlay — calming tone, center screen |
| **Why It Improves UX** | Acknowledges frustration; prevents rage-quit (turning TV off); provides a clear exit |
| **Business Impact** | ↓ Negative brand perception from laggy interactions; ↓ "TV is broken" support calls |
| **Type** | ✅ Safe / Realistic |

---

## UC-10: 📅 "Your Show Is Starting" — Routine Reminder Nudge

| Dimension | Detail |
|---|---|
| **Category** | Predictive Assistance / Session Continuity |
| **Problem** | User watches the same channel every week at the same time (e.g., Friday 9 PM drama) but sometimes forgets or is on another channel |
| **User Behavior Detected** | Recurring pattern — same channel tuned at same day+time across 3+ weeks. Current session: user hasn't tuned to that channel by the expected time |
| **AI Understanding** | User has an established routine but hasn't started their regular viewing — they may have forgotten |
| **Suggested Nudge** | 📺 *"Your regular show on **Channel 45** starts in 5 minutes. **Switch now?**"* `[Switch]` `[Not Today]` |
| **UX Pattern** | Contextual Action Card — timed precisely |
| **Why It Improves UX** | TV becomes a personal assistant that knows your habits; no setup required, purely learned |
| **Business Impact** | ↑ Channel loyalty and viewing minutes; ↑ "sticky" user behavior; ↑ perceived intelligence of the platform |
| **Type** | ✅ Safe / Realistic |

---

## UC-11: 🔋 Remote Battery Dying Detection

| Dimension | Detail |
|---|---|
| **Category** | Device Health / Proactive Care |
| **Problem** | Remote battery is weakening — user doesn't know why TV isn't responding, thinks TV is broken, gets frustrated |
| **User Behavior Detected** | Same key pressed 3-4x in rapid succession repeatedly across the session (user pressing harder because key isn't registering on first press) — pattern increasing over days |
| **AI Understanding** | Increasing failed/repeated key presses over multiple sessions suggests remote signal is weakening — likely low battery |
| **Suggested Nudge** | 🔋 *"Your remote seems unresponsive. **Battery might be low** — try replacing the batteries."* |
| **UX Pattern** | Ghost Toast — informational, non-urgent |
| **Why It Improves UX** | Prevents days of frustration where user blames the TV; proactive care that feels genuinely helpful |
| **Business Impact** | ↓ "TV not responding" support calls (a major support volume driver); ↑ brand perception as proactively caring |
| **Type** | ✅ Safe / Realistic |

---

## UC-12: 👂 Hearing Difficulty → Subtitle Nudge

| Dimension | Detail |
|---|---|
| **Category** | Accessibility |
| **Problem** | User is hard of hearing but doesn't have subtitles enabled — keeps increasing volume to uncomfortable levels |
| **User Behavior Detected** | Volume consistently set above 80% across multiple sessions; frequent volume increases during dialogue-heavy content |
| **AI Understanding** | Persistently high volume may indicate hearing difficulty — subtitles could significantly improve the experience |
| **Suggested Nudge** | 👂 *"Subtitles can help you catch every word without high volume. **Enable subtitles?**"* `[Enable]` |
| **UX Pattern** | Contextual Action Card — shown after 3rd session with this pattern |
| **Why It Improves UX** | Genuinely life-improving for hearing-impaired users who may not know subtitles exist or how to enable them |
| **Business Impact** | ↑ Accessibility compliance scores; ↑ elderly/hearing-impaired user satisfaction; differentiator vs. competitors |
| **Type** | ✅ Safe / Realistic |
