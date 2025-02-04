# [SIRS Criteria Calculator](https://sirscalc.vercel.app/) 

[![SIRS Criteria Calculator](https://raw.githubusercontent.com/iterating/sirscalc/refs/heads/main/public/portfolio.sirscalc.qr.png)](https://sirscalc.vercel.app/)
**Try it out!**

A modern web application for calculating Systemic Inflammatory Response Syndrome (SIRS) criteria, designed to assist healthcare professionals in rapid patient assessment and early sepsis detection.

I wrote this as a medical student at University of Massachusetts Medical School to lessen cognitive load and improve accuracy while seeing patients in the clinics. 

## What is SIRS?

Systemic Inflammatory Response Syndrome (SIRS) is a serious clinical condition that represents a body-wide inflammatory state. It is often a precursor to sepsis, a life-threatening condition that requires immediate medical attention. A patient is considered to have SIRS when they meet two or more of the following criteria:

- Temperature > 38.0°C (100.4°F) or < 36.0°C (96.8°F)
- Heart rate > 90 beats/minute
- Respiratory rate > 20 breaths/minute
- White blood cell count > 12,000/mm³ or < 4,000/mm³

## Why is this Important?

Early detection of SIRS is crucial because:
- It can be an early warning sign of sepsis
- Quick intervention can significantly improve patient outcomes
- It helps standardize the assessment process
- It reduces the likelihood of missing critical cases
- It supports evidence-based medical decision making

## Features

- **Real-time SIRS Calculation**: Instantly determine if SIRS criteria are met
- **Detailed Criteria Breakdown**: See which specific criteria were met
- **Calculation History**: Track and review previous calculations
- **User-friendly Interface**: Clean, intuitive design for rapid data entry
- **Mobile Responsive**: Use on any device at the bedside
- **Data Persistence**: Secure storage of calculations using Supabase
- **Health Data Interoperability**: Export results in FHIR and HL7 formats
  - FHIR: Export as FHIR Observation resources (JSON)
  - HL7: Export as HL7 v2.5.1 messages (Text)

<a href="https://sirscalc.vercel.app/"><img src="https://raw.githubusercontent.com/iterating/sirscalc/refs/heads/main/public/portfolio.sirscalc.calc.jpg" width="350px"><img src="https://raw.githubusercontent.com/iterating/sirscalc/refs/heads/main/public/portfolio.sirscalc.hl7-fhir-export.jpg" width="350px"></a>


## Tech Stack

- **Frontend**: Javascript, HTML, CSS
- **Backend**: Node.js with Express
- **Database**: Supabase (PostgreSQL)
- **Architecture**: Clean Architecture with Domain-Driven Design
- **Deployment**: Vercel for serverless deployment
- **Healthcare Standards**: FHIR R4, HL7 v2.5.1

## Healthcare Interoperability

The SIRS Calculator supports exporting assessment results in two widely-used healthcare interoperability standards:

### FHIR (Fast Healthcare Interoperability Resources)
- Exports data as FHIR R4 Observation resources
- JSON format for modern API integration
- Includes standardized LOINC codes for SIRS assessment
- Structured data suitable for EHR integration

### HL7 (Health Level 7)
- Exports data in HL7 v2.5.1 format
- Traditional text-based format widely used in healthcare
- Includes MSH, PID, OBR, and OBX segments
- Compatible with legacy healthcare systems

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.