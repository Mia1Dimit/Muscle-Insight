# Muscle Insight

Welcome to **Muscle Insight**—a project for advanced, real-time monitoring and analysis of muscle fatigue using surface electromyography (sEMG) signals.

## 🚀 What is Muscle Insight?
Muscle Insight aims to bring deeper understanding and practical monitoring of muscle fatigue to sports, rehabilitation, and daily activity contexts. By leveraging wireless sEMG sensors and state-of-the-art signal analysis, we extract meaningful fatigue metrics and enable real-time feedback.

## 🌟 Key Features

- **sEMG Signal Processing:** Robust algorithms for denoising and feature extraction from sEMG data.
- **Fatigue Metrics:** Multiple time and frequency domain metrics (e.g., mnf_arv_ratio, ima_diff) with research-backed validation.
- **Windowing Strategy:** Flexible window size and overlap for optimal feature tracking (best: 800 samples, 75–87.5% overlap).
- **Calibration & Baseline Analysis:** Per-user calibration with idle and active state comparisons for reliable monitoring.
- **Fatigue Regression Models:** Machine learning regression for continuous fatigue estimation.
- **BLE Integration:** Arduino Bluetooth Low Energy (BLE) communication for wireless, real-time data transfer.
- **Open Documentation:** Extensive notes, results, and research references for transparency and reproducibility.

## 📈 Project Progress

We’ve completed all major design, signal processing, analysis, and implementation steps—including algorithm development, BLE integration, and fatigue regression modeling. For a detailed breakdown, see the task checklist below.

## 📚 Learn More & Resources

- [Electronics Special Issue (Wireless Sensor Network)](https://www.mdpi.com/journal/electronics/special_issues/Wireless_Sensor_Network)
- [Overleaf Project](https://www.overleaf.com/4219964889njyzqnjgshyd#8198bc)
- [Google Docs: Project Notes](https://docs.google.com/document/d/1ecHfYun13XQoTQhuICtWPRKvC5i2IAHv-5Wr92j8-4Q/edit?usp=sharing)

## 📝 Paper

**Title:**  
Developing a Novel Muscle Fatigue Index for Wireless sEMG Sensors: Metrics and Regression Models for Real-Time Monitoring

**Abstract:**  
Muscle fatigue impacts performance in sports, rehabilitation, and daily activities. In this study, we developed a wearable sEMG device and proposed novel metrics and regression models to enable real-time, accurate muscle fatigue monitoring with wireless sensors.

## ✅ Task Checklist

- Project setup, validation
- Window size and overlap research
- Baseline and calibration protocols
- Fatigue metric analysis and regression
- BLE wireless data streaming

---

**Muscle Insight** is open for collaboration and suggestions—let’s advance muscle fatigue monitoring together!
