<br/> <div align="center"> <img src="./logo (1).png" alt="Edge-To-Music AI Logo" width="180"> </div>

<h1 align="center">Edge-To-Music AI</h1>

<p align="center">
  Transform architecture into sound.<br/>
  Upload a building → AI guesses cultural style → edges become melody → browser performs it in real time.<br/><br/>
  2nd Place • Music & AI Hackathon (Nara, 2025) <br/><br/>
  <a href="https://hackathon-2025-edge-music.vercel.app/"><strong>WEB LINK TO DEMONSTRATION</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Tenk1Kun/Music-AI-Hackathon">Source Code</a>
</p>

---

## What this project does

This system turns architectural form into a clear, monophonic musical line:

- Upload an image  
- Classify Japan vs Austria style (temple vs chalet)  
- Extract contours using Canny (OpenCV.js / WASM)  
- Map image axes → musical dimensions  
  - **y → pitch**  
  - **x → onset timing**  
  - **edge magnitude → velocity**  
- Play in-browser (Tone.js Transport)  
- Zero backend — privacy-safe, low latency  

“Architecture is frozen music.” Here, music melts architecture back into sound.

---

## Example Output

<div align="center">
  <img src="./screenshotmusicai.png" width="800" alt="Demo screenshot"/><br/>
  <i>Temple edges → koto line, 96.4% confidence</i>
</div>

---

## Summary

- Cultural architecture features → musical language  
- Edge geometry as gesture  
- Real-time browser audio AI, zero backend  
- Human-centered sonification  
- Built in 24 hours at an international hackathon 

---

## Built With

- **Next.js + TypeScript** — UI & routing  
- **TensorFlow.js** — style classifier  
- **OpenCV.js (WASM)** — edge detection  
- **Tone.js** — musical engine & scheduling  
- **Vercel** — hosting

---

## Pipeline

<div align="center">
  <img src="./musicpipeline.png" width="750" alt="Music AI Pipeline Diagram"/><br/>
  <i>Full architecture-to-music conversion pipeline</i>
</div>

## Who Uses/Studies This

- Computational creativity researchers  
- AI-music artists  
- Architecture & design students  
- Sonification & HCI explorers  
- Hackathon & WebAudio community

---

**Leon Kattendick**  
- Implemented: `preprocessImage.ts`, `loadModel.ts`, `cannyConverter.ts`, `page.tsx`  
- Led: web visuals / UI integration  
- Also: contributed to `edgeToEvents.ts`  
- GitHub: [LeonKattendick](https://github.com/LeonKattendick)

**Koya Takemura**  
- Trained the classification model  
- Implemented: `toneUtil.ts`  
- Primary author of: `edgeToEvents.ts` (band mapping, scale logic, scheduling interfaces)  
- Integration: end-to-end musical mapping & playback

**Jana**  
- Designed the **SurroundSound** logo

**Steffi**  
- Created and delivered the project **presentation**

**Mungunshagai Tumurbaatar**  
- Contributed **ideas** and **website** support

---
Note: This is a public copy of the original private repository, created specifically for Georgia Tech portfolio submission. Community metrics (stars, forks, etc.) do not reflect actual project engagement.

---

## License

© 2025 Koya Takemura and Contributors. All Rights Reserved.  
