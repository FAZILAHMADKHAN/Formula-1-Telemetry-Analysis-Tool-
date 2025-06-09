# 🏎️ Formula 1 Telemetry Analysis Tool

This project is a high-throughput, real-time telemetry monitoring system built to stream and analyze car performance data during Formula 1 races. It enables engineers to visualize and react to telemetry in real time through dashboards and automated alerts.

---

## 🎯 Objective

To develop a live telemetry analysis system that:
- Streams over 10,000 sensor data points per second.
- Visualizes race data in interactive dashboards.
- Detects anomalies in real time.
- Improves pit-lane communication and decision-making.

---

## ⚙️ Tech Stack

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Dash, Plotly  
- **Streaming**: MQTT for real-time data ingestion  
- **Frameworks**: Dash (built on Flask)

---

## 🚀 Key Features

- ✅ **Real-Time Streaming**  
  Streams thousands of telemetry data points every second using MQTT protocol.

- 📊 **Interactive Dashboards**  
  Built with Dash and Plotly to visualize critical metrics like speed, throttle, gear, and brake pressure.

- 🕐 **Latency Reduction**  
  Optimized data sync between pit sensors and engineering consoles, reducing delay from 3.5 to 3.15 seconds.

- 🚨 **Anomaly Detection**  
  Detects outliers in real time using z-score and rolling window metrics, triggering engineer alerts automatically.

- 🔄 **Scalable Throughput**  
  Processes high-frequency sensor input with low CPU overhead.

---
