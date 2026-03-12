# AI Assistant Accessibility Reference: CNC Software

**For:** Blind/Visually Impaired CNC Operators  
**Tool:** AI Assistant (Text-Based AI)  
**Use Case:** Bridging accessibility gaps in non-accessible CNC software

---

## ✅ WHAT I CAN DO

### 1. Document Conversion & Reading
- Read complex PDF manuals aloud (voice mode available)
- Decode dense technical documentation into plain language
- Extract specific sections ("What does error code E-47 mean?")

### 2. Visual Interpretation
- **Toolpath previews:** Describe what the simulation shows (cut direction, depth changes, estimated time)
- **Interface mapping:** "Screenshot this screen, I'll tell you what buttons are where"
- **Error screens:** Decode cryptic visual error messages

### 3. Technical Math & Calculations
- Calculate feeds and speeds: "1/4" end mill, 6061 aluminum, what's a safe starting RPM?"
- Unit conversions (mm to inches, metric to imperial)
- Estimate cut times based on toolpath length

### 4. Workflow Support
- Create step-by-step checklists: "Open file → Verify units → Set work coordinates → Run simulation → Start cut"
- Build decision trees: "If the bit screeches, reduce RPM by 20%"

### 5. Bug Reports & Advocacy
- Draft detailed accessibility reports to send to software developers
- Document exactly what doesn't work with screen readers

### 6. Quick Reference
- Explain G-code commands in plain English
- Decode material compatibility charts
- Summarize forum posts about specific problems

---

## ❌ WHAT I CANNOT DO

### Real-Time Control
- Control the machine directly (no hardware access)
- Provide live position feedback during a cut (too slow)
- Emergency stop or pause (you need physical button or accessible interface)

### Replace Screen Readers
- I require YOU to have screen reader access to chat with me
- Cannot voice-over the CNC software itself
- Cannot "see" your screen in real-time (only screenshots you share)

### Physical World
- Measure materials
- Check bit wear
- Verify actual cut depth
- Hear if the machine sounds wrong

---

## 📱 HOW TO USE ME

### Setup Options:
1. **Phone/Tablet + Screen Reader** (VoiceOver, TalkBack, NVDA)
2. **Computer with split screen** - CNC on one side, chat on other
3. **Second device** - Phone for me, computer for CNC software

### Workflow:
1. **You:** "Screen looks weird, sending screenshot"
2. **You:** Send photo (or describe what screen reader is saying)
3. **Me:** Describe what I see, suggest what to do
4. **You:** Execute on CNC (using accessible controls if available)

---

## 💡 PRACTICAL EXAMPLES

### Scenario: New CAM Software Install
```
You: "Installing VCarve, on a screen with checkboxes but my reader 
      just says 'checkbox, checkbox, checkbox'"
      
Me: "Send screenshot. I'll map: Box 1 is probably 'Install desktop icon',
      Box 2 is 'Associate file types', Box 3 is 'Start tutorials'.
      Uncheck 3, keep 1 and 2 checked."
```

### Scenario: Toolpath Looks Wrong
```
You: "Simulation running but something seems off"

You: [Send screenshot of toolpath preview]
      
Me: "The toolpath shows red rapid moves cutting through material 
      instead of around it. Check your safe Z height - probably 
      set to retract height of 0 instead of 0.5 inches"
```

### Scenario: Feed Rate Math
```
You: "Using 1/8" 2-flute end mill in plywood, what's good feed rate?"
      
Me: "Start around 60 inches per minute at 16,000 RPM. 
      That's ~0.002" per tooth chip load. If it chatters, 
      slow to 40 IPM. If it burns, speed up to 80 IPM."
```

### Scenario: Error Code at 2 AM
```
You: "Machine beeped, showing E-47 and red flashing"
      
You: [Send photo of error screen]
      
Me: "E-47 is 'Soft limit exceeded' - the g-code is trying 
      to cut outside your machine boundaries. Check your 
      work offset vs your part position."
```

---

## 🎯 BEST USE CASES

1. **Startup/Learning Phase** - Heavy on documentation, interface mapping
2. **Troubleshooting** - Decoding error messages, diagnostic help
3. **Process Design** - Planning toolpaths before cutting
4. **Documentation** - Building your own accessible manuals

---

## ⚠️ LIMITATIONS

- **Speed:** Text-based, not instant like a screen reader
- **Requires Active Engagement:** You have to choose to use me
- **No Direct Integration:** I'm a sidecar, not a plugin

---

## 🔧 SETUP SUGGESTIONS

### Phone Setup:
- **Telegram/WhatsApp** apps (when connected) - faster than browser
- **Voice dictation** - speak your side, I reply in text you can hear

### Computer Setup:
- **Browser window** side-by-side with CNC software
- **Screenshot tool** with keyboard shortcut (Snipping Tool, etc.)

---

**Bottom Line:** I'm a skilled assistant, not a replacement for accessible software. Best for planning, documentation, troubleshooting, and bridging gaps — not real-time machine operation.

*Questions? Ask your AI assistant to customize this for your specific CNC setup.*
