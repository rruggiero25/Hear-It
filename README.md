![Welcome Michael Scott](https://media.tenor.com/SpXWQo0Mq7EAAAAM/welcome-michael-scott.gif)

# Important Alert

Before continuing, please review the critical instructions below.
[Click here for urgent instructions](https://www.youtube.com/watch?v=Fw6odlNp7_8) 

# ABOUT MY FEATURE

## Inspired by BeAware – Deaf Assistant

I selected BeAware Deaf Assistant as my reference app because it focuses on sound awareness and accessibility – the same direction I wanted for my feature.

But there's a specific reason why it inspired me:
BeAware's alert system is based mainly on sound intensity (a threshold).
It notifies the user when a sound passes that level, but it doesn't identify what the sound actually is. That limitation made me curious. I wanted to explore a version where the system doesn't just react to “a loud sound”, but tries to understand the kind of sound – doorbell, glass break, dog bark – and then alert the user with more context.

---

## The developed feature: Hear It

Hear It is a SwiftUI feature that simulates **environmental sound detection**. It shows alerts with **haptics, LED flashes, and banners**, and keeps a simple history of events. Currently it uses a **mock sound engine**, but it's built to plug in a real ML sound classifier later.

- Shazam-style listening button  
- Auto-dismissing alert banners  
- Recent events history  
- Haptic and LED flash feedback  
- Simple Settings screen to toggle haptics/flash  
- MVVM architecture, ready for a real sound engine

---

## Project Structure

📁 HearIt  
├─ 📄 HearItApp.swift  
├─ 📁 Models  
│  └─ 📄 SoundEvent.swift  
├─ 📁 Engine  
│  ├─ 📄 MockSoundClassifier.swift  
│  ├─ 📄 HapticsTorch.swift  
│  └─ 📄 (Optional) RealSoundAnalyzer.swift  
├─ 📁 ViewModel  
│  └─ 📄 HearItViewModel.swift  
├─ 📁 UI  
│  ├─ 📄 ListeningButton.swift  
│  ├─ 📄 AlertBanner.swift  
│  ├─ 📄 HistoryRow.swift  
│  └─ 📄 SettingsView.swift  
└─ 📁 Screens  
   └─ 📄 HearItHome.swift  

(*just kidding – I'll tidy up this structure someday, but not today*)

---

## Sketch 

[Click here to see the Dropbox folder and the Sketch file](https://www.dropbox.com/scl/fo/rkul57o2w00280xvuvmuy/ADzayciW2Pq70aLMCLy1yPw?rlkey=sowizqrhmn7vlj8x482bb14q8&st=jywlc73a&dl=0)

---
## How to Try It

1. Clone the repo  
```bash
gh repo clone rruggiero25/Hear-It
