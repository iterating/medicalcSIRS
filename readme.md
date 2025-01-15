# SIRS Criteria Calculator

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

## Technical Stack

- **Frontend**: Javascript, HTML, CSS
- **Backend**: Node.js with Express
- **Database**: Supabase (PostgreSQL)
- **Architecture**: Clean Architecture with Domain-Driven Design
- **Deployment**: Vercel for serverless deployment


## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Healthcare professionals who provided domain expertise
- The medical informatics community for standardizing SIRS criteria
- Open source community for the tools that made this possible