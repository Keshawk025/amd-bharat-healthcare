# System Design: AMD Architecture

## Tech Stack
- **Frontend**: Flutter (Kiosk UI & Mobile App)
- **Backend**: FastAPI (Python) for high-performance AI orchestration
- **Database**: PostgreSQL for secure patient records
- **AI Core**: Gemini 1.5 Pro / Amazon Bedrock for NLP and Diagnosis
- **Hardware**: Raspberry Pi + Stepper Motors + Thermal Label Printer

## Workflow Design
1. **Patient Interface**: User selects language and enters symptoms via voice.
2. **AI Analysis**: Backend sends encrypted data to the LLM for diagnosis.
3. **Validation**: System checks local inventory for medication availability.
4. **Dispensing**: Actuators release the pills into printed "Smart Sachets".
