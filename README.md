![Welcome Michael Scott](https://media.tenor.com/SpXWQo0Mq7EAAAAM/welcome-michael-scott.gif)

# Important Alert

Before continuing, please review the critical instructions below.

[Click here for urgent instructions](https://www.youtube.com/watch?v=Fw6odlNp7_8) 

# Hear It

Hear It is a SwiftUI app that simulates **environmental sound detection**. It shows alerts with **haptics, LED flashes, and banners**, and keeps a simple history of events. Currently it uses a **mock sound engine**, but it’s built to plug in a real ML sound classifier later.

---

## Features

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

(*just kidding – I’ll tidy up this structure someday, but not today*)

---

## How to Try It

1. Clone the repo  
```bash
gh repo clone rruggiero25/Hear-It
