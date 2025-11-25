# ☎️ Mystery Call Box

An interactive project that merges **modern technology** with a **vintage twist**.  
When the user places their phone inside the box, it **locks automatically** using a secret code.  
Beside the box is a **retro 1970s telephone** that rings after the lock is activated.  
When the user answers, they receive a **mysterious voice message** containing clues and a series of **mini-games** they must complete to retrieve the unlock code.  

The project’s goal is to create a unique, playful, and suspenseful **visitor experience** by combining electronics, interaction, and storytelling.

---

## 💡 Project Overview
The Mystery Call Box uses two ESP32 units working together:

- 📦 **ESP32 #1 (Inside the Box)**  
  Controls the locking mechanism and waits for the user to enter the correct unlock code.  
  Once the visitor places something inside the box, the servo motor locks it.

- ☎️ **ESP32 #2 (Inside the Telephone)**  
  Detects when the box is locked, triggers the vintage phone to ring, and plays a pre-recorded audio message using an **MP3 player module**.  
  These audio messages contain the **numbers or clues the visitor needs to unlock the box**.

The user must:
1. Lock the box by placing their device inside  
2. Answer the ringing vintage telephone  
3. Listen to the mysterious MP3 voice message  
4. Extract the hidden numbers  
5. Enter the code to unlock the box  

The challenge combines **storytelling**, **electronics**, and **puzzle solving**.

---

## ⚙️ Components and Parts Used
### 🛠 Hardware
- 🧠 **ESP32 (2 units)**  
  - One inside the mystery box  
  - One inside the vintage telephone  
- 🔒 **Servo Motor** – controls the box locking and unlocking  
- 📞 **Old 1970s Telephone** – rings and delivers audio clues  
- 🔊 **MP3 Player Module (DFPlayer or similar)** – plays voice messages and number clues  
- 🔉 **Speaker** – built into the telephone for audio playback  
- 🔌 Power modules and wiring components   

---

## 💻 Software and Tools Used
- 🔧 **Arduino IDE** – used to program both ESP32 modules  
- 🎙️ **MP3/Audio File Tools** – to prepare voice clues and number sequences  
- 🔁 **ESP32 Serial/Wi-Fi Communication**
- 🎚️ **MP3 Libraries** – for audio playback control  

---

## 👨‍💻 Contributors:
Special thanks to :  
- **Ayman Bakleh** [LinkedIn](https://www.linkedin.com/in/aymanbakleh/)

---

## 🚀 Future Improvements

- Add wireless communication to sync puzzles between box and phone in real time  
- Integrate AI-generated voice messages for dynamic storytelling  
- Add sensors (IR, proximity, or weight detection) for automatic box activation  
- Expand to multi-step puzzle sequences with branching narratives  
- Add LED indicators or sound effects for enhanced immersion

---

## 📸 Demo

**Coming soon!**

---

**Made with ❤️ using ESP32, Arduino IDE, and a touch of mystery.**



