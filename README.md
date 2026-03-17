# -Genesys-Schedule-Emergency-Routing-IVR
This project demonstrates a Genesys Cloud IVR flow with schedule-based routing and emergency handling.
## Schedule Check and Emergency Routing

Vohra Group operates Monday through Friday 10:00AM to 04:00PM IST. Vohra Group and company  will be closed during all National Holidays. In emergency situation, there should be an option to override this routing behaviour. During all the non working situation, customer should get an option to leave voicemail.
## 🔄 Features
- Schedule Check (Business Hours / Closed Hours)
- Closed Office Message Handling
- Emergency Call Routing (High Priority)
- Dynamic IVR Decision Logic

## 📞 Call Flow Logic
1. Incoming call received
2. Schedule Check:
   - Open → Route to Normal Queue
   - Closed → Play Closed Office Message
3. Emergency Handling:
   - If emergency condition triggered → Route to Emergency Queue

## 🛠 Technologies Used
- Genesys Cloud CX (Architect)
- IVR Call Flow
- Queue Routing
