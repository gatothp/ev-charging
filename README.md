# EV Charging Calculator

A simple, interactive web-based calculator to estimate energy requirements, charging time, and electricity costs for your electric vehicle.

## Features

- 📊 **Weekly Charging** - Calculate your weekly energy needs based on vehicle specifications and driving distance
- 💰 **Charging Cost** - Estimate the time and cost of a single charging session
- ℹ️ **Detailed Information** - Learn about supported EV models, how the calculator works, and get support
- 🌐 **Bilingual Support** - Available in English and Indonesian (Bahasa Indonesia)
- 📱 **Mobile Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- 🔒 **100% Private** - All calculations are done locally in your browser; no data is sent to any server

## Supported EV Models

- BYD Atto 1 - 38.88 kWh, 9.77 km/kWh
- BYD M6 - 44.9 kWh, 8.5 km/kWh
- Chery Q - 42.7 kWh, 9.35 km/kWh
- GAC Aion V - 51.0 kWh, 8.2 km/kWh
- Geely EX2 - 38.0 kWh, 9.1 km/kWh
- Jaecoo J5 - 60.9 kWh, 7.57 km/kWh
- Wuling Air EV - 37.9 kWh, 9.5 km/kWh
- **Custom** - Enter your own vehicle specifications

## Getting Started

1. Open `index.html` in your web browser to access the home page
2. Choose from three main tools:
   - Click the **Weekly Charging** card to calculate your weekly energy needs
   - Click the **Charging Cost** card to estimate charging time and cost
   - Click the **Learn More** card for app information and support

## How to Use

### Weekly Charging
1. Select your vehicle model or choose "Custom" to enter custom specs
2. Enter your weekly driving distance (km)
3. Adjust charging efficiency if needed
4. Set your charge level per session (percentage)
5. View instant calculations of weekly energy requirements and number of charging sessions needed

### Charging Cost
1. Enter your charging power (in kW or Ampere)
2. Set your battery capacity
3. Choose starting and target charge levels
4. Enter your electricity price per kWh
5. Adjust charging efficiency if needed
6. Get precise estimates of charging time and total cost

## Navigation

- **Home Icon (🏠)** - Return to the home page
- **Weekly Charging Icon (📊)** - Go to weekly charging calculator
- **Charging Cost Icon (💰)** - Go to charging cost calculator
- **About Icon (ℹ️)** - View app information and support
- **Language Toggle (🇮🇩 Bahasa)** - Switch between English and Indonesian

## Technical Details

- **Framework**: Pure HTML, CSS, and JavaScript (no dependencies)
- **Compatibility**: All modern web browsers (Chrome, Firefox, Safari, Edge)
- **Data Storage**: None - all calculations are performed locally
- **Performance**: Instant calculations with real-time updates

## Supported Calculations

### Weekly Charging Tab
- Weekly driving energy = Distance per week ÷ Vehicle efficiency
- Grid energy = Weekly energy ÷ Charging efficiency
- Full charging sessions = Weekly energy ÷ (Battery capacity × Charge level)

### Charging Cost Tab
- Energy to add = Battery capacity × (Target charge - Start charge) ÷ 100
- Grid energy = Energy to add ÷ Charging efficiency
- Charging time = Grid energy ÷ Charging power
- Total cost = Grid energy × Price per kWh

## Important Notes

- Charging time assumes constant charging power; actual power may vary, especially with DC fast charging
- Vehicle efficiency varies with speed, temperature, traffic, terrain, and driving style
- PLN tariff examples provided are for reference and should be verified against current rates
- Charging efficiency accounts for losses between grid electricity and battery storage

## Contact & Support

For questions, feedback, suggestions, or technical support:
- **Email**: gatothp@yahoo.com

## Privacy

This calculator respects your privacy:
- No personal data is collected, stored, or transmitted
- All calculations happen entirely on your device
- Your data is always secure

## File Structure

```
ev-charging/
├── index.html              # Home page
├── weekly-charging.html    # Weekly charging calculator
├── charging-cost.html      # Charging cost calculator
├── about.html              # About and support page
├── README.md               # This file
└── .git/                   # Git repository
```

## Browser Requirements

- JavaScript enabled
- Modern CSS support (CSS Grid, Flexbox)
- ES6+ JavaScript support

## License

This project is open source and available for personal and educational use.

---

**EV Charging Calculator** - Making EV charging estimation simple, transparent, and accessible to everyone.
