<img width="1883" height="915" alt="Screenshot 2026-09-03 201847" src="https://github.com/user-attachments/assets/ce16fabf-a842-4c3d-a1ae-6a66d3602ea3" />
<img width="1902" height="917" alt="Screenshot 2026-09-03 201906" src="https://github.com/user-attachments/assets/bae516d4-49a5-4a6d-a1c5-34d1888b9623" />
<img width="1882" height="917" alt="Screenshot 2026-09-03 201922" src="https://github.com/user-attachments/assets/c6f28598-4d62-4cbd-b959-8d214ab25243" />
# Aeromesh — Federated Air Intelligence for BRICS

## Introduction

Aeromesh is a concept platform designed for the **BRICS Sustainability Challenge**. It focuses on improving air-pollution monitoring by combining citizen observations, ground sensors, satellite data, and weather information into a unified view.

The platform is designed around the idea that **air pollution does not stop at national or regional borders**. Aeromesh therefore proposes a federated approach where countries can collaborate through shared AI models without directly sharing their raw citizen, sensor, or personal data.

This repository contains the front-end prototype of the Aeromesh platform. It demonstrates the concept through an interactive, responsive web interface with pollution indicators, data-processing stages, platform features, federation architecture, forecasting, and an action section. The project is explicitly presented as a concept platform with illustrative readings for demonstration.

## Importance of the Code

The code is important because it converts the Aeromesh concept into a **visual and interactive prototype** that can be presented to judges, developers, stakeholders, and potential users.

It demonstrates:

* **Air-pollution monitoring:** Displays example AQI readings for major BRICS cities.
* **Multi-source data integration:** Shows how citizen photos, ground sensors, satellite imagery, and meteorological data can contribute to the system.
* **Pollution hotspot detection:** Communicates the idea of identifying pollution events that fixed monitoring stations may miss.
* **Forecasting:** Demonstrates the proposed 72-hour pollution-spike forecasting capability.
* **Cross-border coordination:** Shows how pollution alerts can be transferred between jurisdictions when a pollution plume crosses a border.
* **Data sovereignty:** Demonstrates the concept of sharing trained model updates instead of raw data between participating countries.
* **Responsive design:** The CSS includes layouts for desktop and mobile screens.

## Technologies Used

### HTML

HTML provides the structure and content of the website, including:

* Navigation bar
* Hero section
* Problem statement
* Processing pipeline
* Platform features
* Federation architecture
* Forecasting section
* Call-to-action section
* Footer

### CSS

CSS controls the visual appearance and responsive behavior of the platform.

It defines:

* Colors and design variables
* Typography
* Buttons
* Cards
* Navigation
* Grid layouts
* Responsive mobile layouts
* Animations
* Accessibility-related focus styling

The project uses **IBM Plex Sans** and **IBM Plex Mono** for its typography.

### JavaScript

JavaScript is used to dynamically create the **federation mesh diagram**.

The script defines five national nodes:

* Brazil
* Russia
* India
* China
* South Africa

It then creates connections between the nodes and animates the connecting lines and nodes when the page loads.

## Main Features

### 1. Pollution Corridor Monitoring

The dashboard displays illustrative pollution readings for cities including São Paulo, New Delhi, Shanghai, Johannesburg, and Moscow.

The readings are visually classified into categories such as Good, Moderate, Unhealthy, and Hazardous.

### 2. Four-Stage Data Pipeline

Aeromesh represents its processing architecture through four stages:

**Ingest → Fuse → Detect & Forecast → Alert & Coordinate**

The system concept combines citizen reports, sensors, satellite information, and meteorological data before detecting pollution hotspots and generating alerts.

### 3. Citizen Reporting

The proposed platform allows citizens to submit photos of visible pollution. The concept includes on-device haze scoring and offline operation so that reports can synchronize when connectivity becomes available.

### 4. Federated Architecture

The federation section demonstrates the central architectural idea of Aeromesh:

> Countries keep their raw data locally while sharing trained model updates.

This approach is intended to support collaboration while maintaining national data sovereignty.

### 5. Pollution Forecasting

The website contains an illustrative six-day AQI forecast showing how pollution levels could increase toward a forecast peak. The forecast visualization is presented as a demonstration rather than live pollution data.

## Uses of the Project

Aeromesh can serve as a prototype for:

1. **Environmental monitoring**
2. **Pollution hotspot identification**
3. **Cross-border pollution coordination**
4. **Citizen-based environmental reporting**
5. **AI-assisted air-quality forecasting**
6. **Environmental awareness**
7. **Government and authority alerting**
8. **Federated AI research**

## Project Structure

Currently, the prototype is implemented as a single HTML file containing:

```text
HTML
 ├── Page structure
 ├── Navigation
 ├── Content sections
 └── Footer

CSS
 ├── Layout
 ├── Colors
 ├── Typography
 ├── Responsive design
 ├── Components
 └── Animations

JavaScript
 └── Federated BRICS mesh visualization
```

## Important Note

This repository currently represents a **concept/prototype interface**. The pollution values shown on the dashboard and forecast are illustrative demonstration values, not a live environmental monitoring service.

The prototype provides the front-end vision of Aeromesh and can later be extended with real sensor APIs, satellite data, weather APIs, machine-learning models, databases, authentication, citizen reporting, and real-time alert systems.

## Future Development

Possible future improvements include:

* Real-time sensor integration
* Satellite API integration
* Weather-data integration
* Machine-learning based AQI forecasting
* Citizen mobile application
* Real-time pollution maps
* Database integration
* Government alert APIs
* Federated-learning infrastructure
* Multilingual public alerts
* Authentication and role-based access
* Real-time dashboards

## Conclusion

Aeromesh demonstrates how multiple environmental data sources can be brought together into a single platform for **earlier pollution detection, forecasting, and coordinated action**.

The prototype provides the foundation for developing a complete environmental intelligence system capable of supporting citizens, researchers, and authorities across BRICS economic corridors.
