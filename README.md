# 🏃‍➡️☀️ SOUND TERRARIUM — Web Edition

A tiny sound-reactive world that runs directly in your browser.  
No M5Stack hardware required.

🎤 **On smartphones and desktop browsers**, SOUND TERRARIUM can use the microphone to shape the terrain.  
⌨️ On a computer, use the keyboard; on iPhone and Android, use the on-screen controls.

## 🎵 Built-in Metronome

The battery-status placeholder has been retired. On the Cardputer ADV, the battery indication was not accurate enough to be genuinely useful, so the space was repurposed for something that belongs more naturally in a sound-reactive world: a **built-in metronome**.

The Web Edition mirrors that design.

- **B** — metronome ON / OFF
- **← / →** — −1 / +1 BPM
- **Hold ← / →** — continuous BPM change on a physical keyboard
- **↓ / ↑** — volume −10 / +10
- Default tempo: **120 BPM**
- BPM range: **40–200**
- Default volume: **80%**
- Volume range: **20–100%**

While the metronome is running, its BPM is shown in a fixed position. When volume is changed, the same position temporarily shows the volume (for example, **80% VOL**) before returning to BPM. The display disappears when the metronome is stopped and does not move when **I** hides or shows the Information overlay.

The generated click is also fed into SOUND TERRARIUM's audio analysis, so the metronome itself can create terrain. Event SFX and the metronome can continue together.

## 🌱 Ground Perspective

Fourteen restrained ground grains add depth without changing the sound-generated landscape:

- **6 small grains** — 1 × 1 px, moving with the terrain
- **5 medium grains** — 2 × 2 px, moving at about 1.7× terrain speed
- **3 large grains** — 3 × 3 px, moving at about 2.7× terrain speed

The grains are **black by day** and **dark navy by night**.

## 🔊 Event Sound Effects

The Web Edition includes small retro-style event SFX generated with Web Audio. No prerecorded audio files are required.

- **J** — manual jump
- **M** / Sunday 9 PM shooting star — synthetic “KIRAAN” + sparkling tail
- **UFO flight** — retro square-wave sweep
- **UFO beam** — rising electronic sound
- **Runner abduction** — short synthetic “Aaa!”
- **X** — event SFX ON / OFF

The metronome is independent of **X**, so event SFX can be disabled without stopping the beat.

## 🌠 Sunday 9 PM Shooting Star

Every Sunday at 9 PM local time, a special shooting star crosses the SOUND TERRARIUM sky when the weather allows. The same special meteor can be triggered manually at any time with **M**. Existing major meteor-shower events remain separate.

**For everyone who kept running this week.**  
**Something good may be waiting for you next week. 🌠**

▶ **Try it in your browser:**  
https://kariagepompadour.github.io/SOUND-TERRARIUM-Web/

---

*Current update: retired the battery-status placeholder and added the built-in metronome, with adjustable BPM and volume, fixed BPM/VOL display, keyboard long-hold BPM adjustment, and coexistence with the existing retro event SFX.*
