# WS2812C-2427 KiCad Library

A custom KiCad library for the **WS2812C-2427** addressable RGB LED.
This library provides accurate schematic symbols and PCB footprints for seamless integration into your designs.

---

## 📦 Contents

* ✅ Schematic Symbol
* ✅ PCB Footprint (2427 package)
* ✅ Pin mapping aligned with datasheet
* ✅ Ready for use in KiCad projects

---

## 🔧 About WS2812C-2427

The WS2812C-2427 is a compact, integrated RGB LED with a built-in controller, commonly used in:

* LED strips
* Wearables
* Compact lighting designs
* Decorative and embedded systems

It supports single-wire communication and allows chaining multiple LEDs together.

---

## 📐 Features of This Library

* Accurate pad dimensions for reliable soldering
* Clean footprint layout for compact PCBs
* Proper pin orientation to avoid wiring mistakes
* Designed with manufacturability in mind

---

## 🚀 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/Dubemchukwu/WS2812C-2427-KiCad-Library.git
```

### 2. Add to KiCad

1. Open KiCad
2. Go to **Preferences → Manage Symbol Libraries**
3. Add the `.lib` / `.kicad_sym` file

Then:

4. Go to **Preferences → Manage Footprint Libraries**
5. Add the footprint folder (`.pretty`)

---

## 🔌 Usage

1. Place the WS2812C-2427 symbol in your schematic

2. Assign the included footprint (if not already linked)

3. Connect:

   * VDD → Power
   * GND → Ground
   * DIN → Data input
   * DOUT → Data output

4. Chain multiple LEDs by connecting:

   ```
   DOUT → DIN (next LED)
   ```

---

## ⚠️ Notes

* Ensure proper power supply decoupling (recommended capacitor near VDD)
* Follow signal integrity practices for long LED chains
* Double-check orientation during PCB assembly

---

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome!
Feel free to open an issue or submit a pull request.

---

## ⭐ Support

If you find this library useful, consider giving the repo a star!
