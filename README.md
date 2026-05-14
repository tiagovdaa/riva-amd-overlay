# Asus ROG AMD Overlay for RivaTuner

A sleek and modern RivaTuner Statistics Server overlay designed specifically for AMD-based gaming systems with Asus ROG components. This overlay seamlessly integrates with your gaming setup to display system performance metrics with the iconic Asus ROG and AMD Radeon branding.

## 📋 Overview

The **Asus ROG AMD Overlay** is a custom overlay solution for RivaTuner Statistics Server (RTSS) that combines aesthetic design with practical system monitoring. Perfect for gamers running AMD Ryzen processors and Radeon GPUs on Asus ROG motherboards or systems.

### Features

- 🎨 **Asus ROG Themed Design** - Professional styling that matches your Asus ROG aesthetic
- 🎮 **AMD Radeon & Ryzen Branding** - Dedicated graphics for AMD hardware recognition
- 📊 **Performance Monitoring** - Display GPU/CPU usage, temperatures, and fan speeds
- 🎯 **Gaming-Focused Layout** - Optimized for minimal screen clutter during gameplay
- ⚡ **Customizable Gauges** - Various ring and arc gauge styles for data visualization
- 🖥️ **Low Overhead** - Efficient overlay that won't impact gaming performance

## 🚀 Installation

### Prerequisites

- [RivaTuner Statistics Server](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html) installed
- [HWInfo](https://www.hwinfo.com/) installed (for hardware monitoring data)
- AMD CPU and/or GPU
- Windows operating system

### Installation Steps

1. **Download the Overlay**
   - Clone or download this repository
   - Extract the files to your preferred location

2. **Copy to RivaTuner Directory**
   ```
   Copy "Asus ROG.ovl" to:
   RivaTuner Statistics Server/Plugins/Client/Overlays
   ```

3. **Restart RivaTuner**
   - Close RivaTuner Statistics Server completely
   - Reopen the application

4. **Activate the Overlay**
   - In RTSS, go to **Settings** → **Overlays**
   - Select **"Asus ROG"** from the available overlays
   - Click **"OK"** to apply

## 📁 Project Structure

```
riva-amd-overlay/
├── Asus ROG.ovl          # Main overlay file
├── Asus ROG.png          # Preview/thumbnail image
├── README.md             # This file
├── LICENSE               # GNU General Public License v3
└── .git/                 # Version control
```

## 🎮 Usage

Once installed and activated:

1. **Launch any game** - The overlay will display automatically during gameplay
2. **Monitor Performance** - Watch real-time metrics for your AMD system
3. **Toggle Visibility** - Use RTSS hotkeys to show/hide the overlay (default: Ctrl+O)
4. **Customize in RTSS** - Adjust overlay position and properties through RTSS settings

## 🔧 Compatibility

| Component | Support |
|-----------|---------|
| **CPU** | AMD Ryzen (all generations) |
| **GPU** | AMD Radeon RX (all generations) |
| **Motherboard** | Asus ROG (recommended) or any Intel/AMD platform |
| **OS** | Windows 7 / 8 / 10 / 11 |
| **RTSS** | v7.0.0 and newer |

## 📜 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

## 💡 Tips

- **Performance**: The overlay has minimal performance impact. You can usually enable it without noticeable FPS loss.
- **Positioning**: Adjust the overlay position in RTSS settings to avoid obstructing important game UI elements.
- **Customization**: You can edit the `.ovl` file with a text editor for advanced customization (requires basic understanding of overlay syntax).

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Overlay not appearing | Restart RTSS after installation |
| Text is hard to read | Adjust overlay opacity in RTSS settings |
| Performance impact | Ensure you're running the latest RTSS version |
| File not recognized | Verify the `.ovl` file is in the correct directory |

## 🔗 Resources

- [RivaTuner Statistics Server](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)
- [Asus ROG Official Site](https://rog.asus.com/)
- [AMD Radeon Gaming](https://www.amd.com/en/gaming)

## 💬 Support

For issues, questions, or suggestions:
1. Check the troubleshooting section above
2. Review the RTSS documentation
3. Open an issue in this repository

---

**Happy gaming with your AMD + Asus ROG setup!** 🎮🚀