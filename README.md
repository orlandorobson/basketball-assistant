# Basketball Assistant

An AI-powered assistant that helps athletes and coaches track, analyse, and improve basketball training.  
This prototype logs training sessions via **Google Forms → Google Sheets → Dashboard → AI feedback**.  

---

## Current Status (v0.2)
- ✅ Google Form → Sheets → Log integration working
- ✅ Automatic KPIs and charts (shooting %, weak-hand %, RPE)
- ✅ Weekly Export tab prepared for AI feedback
- 🔄 Next step: Automating weekly coach notes with GPT

---

##  Features
- Log sessions quickly with a phone-friendly form  
- Automatic calculation of shooting %, weak-hand %, training load  
- Dashboard with charts (progress over time)  
- Weekly feedback loop: export → GPT → coaching notes  

---

##  Roadmap
- **v0.3** → Hugging Face demo (public AI coach feedback)  
- **v0.4** → WhatsApp bot for daily logging (Twilio)  
- **v0.5** → Automated weekly AI feedback (Apps Script/n8n)  
- **v0.6** → Player profiles + personalization  
- **v0.7** → Multi-player support (team dashboard)  

---

##  Tech Stack
- **Google Forms / Sheets** → data collection & storage  
- **Google Sheets formulas** → KPIs & automation (FILTER, ARRAYFORMULA)  
- **ChatGPT** → weekly AI feedback  
- **(Upcoming)** Hugging Face Spaces, n8n, Lovable, GitHub Actions  

---

##  Next Steps
- [ ] Connect KPIs to live form log  
- [ ] Publish a simple Hugging Face demo  
- [ ] Prototype a WhatsApp bot for logging  

---

##  Dashboard View
![Dashboard Screenshot](Dasdhboard%20v0.1.png)

---

## Author
Built by [@orlandorobson](https://github.com/orlandorobson) as part of an EdTech + AI learning journey (towards GITEX 2025, Dubai).
