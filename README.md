# 🏃‍➡️☀️ SOUND TERRARIUM — Web Edition

A tiny sound-reactive world that runs directly in your browser.  
No M5Stack hardware required.

🎤 **On smartphones**, SOUND TERRARIUM uses the built-in microphone.  
💻 **On desktop Chrome**, you can share tab audio to make the world react directly to music and other browser audio.


## 🌱 Ground Perspective

The terrain now has a subtle sense of depth without changing the
sound-generated landscape itself.

Fourteen sparse ground grains are divided into three depth layers:

- **6 small grains** — 1 × 1 px, moving with the terrain
- **5 medium grains** — 2 × 2 px, moving at about 1.7× terrain speed
- **3 large grains** — 3 × 3 px, moving at about 2.7× terrain speed

A clear band immediately below the surface keeps the distant horizon
uncluttered. The grains are **black by day** and **dark navy by night**, so
they read as texture and parallax rather than stars or glowing particles.

## 🔊 Event Sound Effects

The Web Edition now includes small retro-style event sound effects
generated with Web Audio. No prerecorded audio files are required.

- **J** — manual jump: a very quiet 8-bit chirp
- **M** / Sunday 9 PM shooting star — a bright synthetic **"KIRAAN"** followed by a quieter sparkling tail
- **UFO flight** — fast retro square-wave sweep inspired by late-1970s arcade flying-saucer sounds
- **UFO beam** — very quiet rising electronic sound
- **Runner abduction** — a short synthetic "Aaa!" as the runner is lifted

Press **X** to toggle all effects. The Information overlay shows
**SFX ON** or **SFX OFF** at the lower-right beside **BAT OK**.

On browsers, audio playback requires a user gesture before scheduled
sounds can play. Pressing **START MICROPHONE** or using a manual control
activates the browser audio context.

## 🌠 Sunday 9 PM Shooting Star

Every Sunday at 9 PM local time, a special shooting star crosses the SOUND TERRARIUM sky. When SFX is enabled and browser audio has been activated, a bright synthetic "KIRAAN" is followed by a quieter sparkling tail lasting about 2.43 seconds.

It is a small moment at the end of the week — a time to look back on the week that has passed and make a wish for the week ahead.

If the weather is clear or cloudy, a single shooting star crosses the little sky. In rain, snow, or thunder, that week's star remains unseen.

The special meteor now has a longer, gently widening trail that fades smoothly into the sky for a more romantic shooting-star effect. Under a fully dark sky it glows in warm yellow; against a brighter sky it appears white for better visibility.

The same special meteor can also be triggered manually at any time with **M (Meteor)**. **X** toggles all event sound effects. The automatic Sunday 9 PM event remains separate: it still happens on its own when the weather allows.

The Sunday event follows local time rather than the day/night cycle, so the shooting star may also appear at 9 PM during bright summer evenings at high latitudes.

Existing **major meteor-shower events are unchanged** and remain separate from this single special meteor.

**For everyone who kept running this week.**  
**Something good may be waiting for you next week. 🌠**

▶ **Try it in your browser:**  
https://kariagepompadour.github.io/SOUND-TERRARIUM-Web/

---
*Current update: added restrained three-layer ground perspective grains,
refined the shooting-star synthesis into a longer **"KIRAAN" → quieter
sparkle** effect, and updated the UFO flight sound with a faster retro
square-wave sweep. Existing major meteor-shower events and other controls are
unchanged.*
