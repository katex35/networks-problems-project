# Network Problems Project

A comprehensive interactive guide documenting 10 common network problems across OSI layers (L1-L7) with detailed explanations, solutions, and Cisco Packet Tracer simulations.

## 🌐 Live Demo

[View Live Demo](https://networks-problems-project.vercel.app/)

## 📋 Overview

This project serves as an educational resource for network administrators and students learning about network troubleshooting. It covers real-world network problems with:

- **Interactive Web Interface** - Modern, responsive design with image galleries
- **OSI Layer Coverage** - Problems spanning from Physical (L1) to Application (L7) layers
- **Cisco Packet Tracer Simulations** - Downloadable `.pkt` files for hands-on practice
- **Step-by-step Solutions** - Detailed troubleshooting guides for each problem

## 🔧 Network Problems Covered

1. **IP Conflict** (L3) - Duplicate IP address conflicts
2. **MAC Address Conflict** (L2) - Duplicate MAC address issues
3. **VLAN Misconfiguration** (L2) - Incorrect VLAN port assignments
4. **Cable Fault** (L1) - Physical layer connectivity problems
5. **Default Gateway Missing** (L3) - Routing configuration issues
6. **DNS Server Unreachable** (L7) - Domain name resolution failures
7. **IP Routing Missing** (L3) - Static routing problems
8. **DHCP Gateway Misconfiguration** (L3) - Wrong gateway distribution
9. **Switching Loop - STP Disabled** (L2) - Network loops and STP issues
10. **MTU Mismatch** (L2+L3) - Maximum Transmission Unit conflicts

## 🛠️ Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - Interactive features and modal functionality
- **Font Awesome** - Icons and visual elements
- **Google Fonts** - Inter font family for typography

## 📁 Project Structure

```
networks-problems-project/
├── index.html              # Main HTML file
├── images/                 # Problem screenshots organized by folders
│   ├── problem_1/         
│   ├── problem_2/         
│   └── ...                
├── cisco/                  # Cisco Packet Tracer simulation files
│   ├── problem_1_same_ip.pkt
│   ├── problem_2_mac.pkt
│   └── ...
└── README.md              # Project documentation
```

## Deployment

1. Clone the repository:
```bash
git clone https://github.com/katex35/networks-problems-project.git
```

2. Open `index.html` in your browser or serve with a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

## 📖 Usage

1. **Browse Problems** - Use the left sidebar to navigate between network problems
2. **View Screenshots** - Click on images to open them in an interactive modal
3. **Download Simulations** - Click "Download Simulation" buttons to get Cisco Packet Tracer files
4. **Follow Solutions** - Read step-by-step troubleshooting guides


## 🙏 Acknowledgments

- Network diagrams and simulations created with Cisco Packet Tracer
- Icons provided by Font Awesome
- Typography using Google Fonts (Inter)

---
