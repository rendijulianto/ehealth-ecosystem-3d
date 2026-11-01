# 🏥 Ekosistem Kesehatan 3D

An interactive 3D simulation of a community health ecosystem, showing how patients, medicines, and referrals move through a small town.

<!-- Add these once they exist:
![Demo](./docs/demo.gif)

🔗 **Live demo:** [DEMO LINK]
-->

## ✨ Features

- 🏥 **Connected facilities:** Puskesmas, Klinik Pratama, RS Rujukan, Gudang Farmasi, and BPJS Kesehatan
- 🎫 **Moving patient queues** at the Puskesmas and clinic, with number boards and a live waiting count
- 💉 **Service icons** for immunization, general care, pharmacy, emergency, and more
- 🚑 **Random but orderly traffic:** the courier truck, ambulance, cars, and motorcycles pick their own routes, keep their distance, and take turns at junctions
- 🛵 **Ride-hailing drivers** carrying passengers and medicine deliveries
- 🚶 **Pedestrians and zebra crossings:** vehicles stop for people crossing, and people wait for a safe gap
- 🅿️ **Parking lots** with parked cars and motorcycles
- 📡 **BPJS data flows** drawn as animated arcs between facilities
- 💬 **Click-to-open tooltips** with details for each facility and service, on a single full-screen page
- 🎛️ **Display controls:** toggleable layers, adjustable simulation speed, and a light/dark mode switch that the browser remembers

> All data shown is simulated.

## 🎯 Why this project?

Healthcare systems are usually explained with slides and flowcharts. This project makes the system visible, so product teams, policymakers, and the public can see how care actually moves.

## 🎮 Controls

| Action | Mouse | Touch |
| --- | --- | --- |
| Rotate the view | Drag | Drag |
| Zoom | Scroll | Pinch |
| Open details | Click a name or building | Tap a name or building |
| Close details | ×, `Esc`, or click an empty area | × or tap an empty area |

## 🛠️ Tech Stack

- [Three.js](https://threejs.org/) r128, loaded from a CDN
- Plain HTML, CSS, and JavaScript, with no build step
- All signs, icons, and vehicle decals are drawn in code with the Canvas API

## 🚀 Getting Started

There is nothing to install. Clone the repository, then open `index.html` in a browser or serve it locally:

```bash
git clone https://github.com/<username>/ehealth-ecosystem-3d.git
cd ehealth-ecosystem-3d
python3 -m http.server 5173
```

Then open `http://localhost:5173`.

You need a browser with WebGL and an internet connection, because Three.js and the fonts load from CDNs.

## 📁 Project Structure

```
.
├── index.html   # The whole app: styles, 3D scene, and simulation
└── README.md
```

## 🗺️ Roadmap

- [ ] More facility types
- [ ] Configurable scenarios
- [ ] Real-world data integration

## 🤝 Contributing

Issues and pull requests are welcome. Feel free to open an issue with ideas or feedback.

## 📄 License

MIT © [Your Name]
