# ⭐️Playwright framework for E-commerce automated tests ⭐️

Overview
This project aims to ensure the reliability and functionality of the E-commerce website through automated testing. Leveraging the Playwright framework with TypeScript, we strive to streamline the testing process, identifying potential issues early on and maintaining a robust, error-free web application.


## Overview

This project aims to ensure the reliability and functionality of the E-commerce website 

## 🚀 Scope

- **End-to-end testing:** Simulate real user interactions to validate the entire user journey.

- **Smoke testing:** Conduct basic, quick checks on functionalities to ensure the software's fundamental features are operational. These tests are designed to provide a rapid assessment of system stability and readiness for more comprehensive testing, serving as a preliminary validation step before delving into deeper testing scenarios.

- **Backend API testing:** Ensure the robustness and reliability of your backend infrastructure by meticulously examining each endpoint and functionality.

- **Integration testing:** Validate the seamless interaction between different components of your system to ensure smooth data flow and functionality across interconnected modules.

- **Scenario Coverage:** Cover various user journeys, including login to account, fund transfers, and balance verification.

- **Continuous Integration:** Integrate the testing suite into the continuous integration pipeline for quick feedback.

  ![test_pyramid_redesign](https://github.com/user-attachments/assets/7c0bfa09-9802-4cc9-bff5-484a7448ae21)<svg viewBox="0 0 800 600" xmlns="http://www.w3.org/2000/svg">
  <!-- Background -->
  <rect width="800" height="600" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="400" y="50" text-anchor="middle" font-family="Arial, sans-serif" font-size="28" font-weight="bold" fill="#2c3e50">
    THE TEST PYRAMID USED IN
  </text>
  <text x="400" y="85" text-anchor="middle" font-family="Arial, sans-serif" font-size="28" font-weight="bold" fill="#2c3e50">
    THE PROJECT
  </text>
  
  <!-- E2E Tests - Top (Purple) -->
  <polygon points="300,150 500,150 400,120" fill="#8b5cf6" opacity="0.9"/>
  <text x="180" y="140" font-family="Arial, sans-serif" font-size="18" fill="#2c3e50">E2E tests</text>
  <path d="M 260 135 Q 280 130 300 140" stroke="#2c3e50" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
  
  <!-- Smoke Tests - Second level (Blue) -->
  <polygon points="270,200 530,200 500,150 300,150" fill="#3b82f6" opacity="0.8"/>
  <text x="550" y="180" font-family="Arial, sans-serif" font-size="18" fill="#2c3e50">Smoke tests</text>
  <path d="M 550 185 Q 540 175 530 185" stroke="#2c3e50" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
  
  <!-- API Tests - Third level (Green) -->
  <polygon points="240,250 560,250 530,200 270,200" fill="#10b981" opacity="0.8"/>
  <text x="150" y="230" font-family="Arial, sans-serif" font-size="18" fill="#2c3e50">API tests</text>
  <path d="M 210 235 Q 225 230 240 240" stroke="#2c3e50" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
  
  <!-- Integration Tests - Bottom (Orange) -->
  <polygon points="210,300 590,300 560,250 240,250" fill="#f59e0b" opacity="0.8"/>
  <text x="610" y="280" font-family="Arial, sans-serif" font-size="18" fill="#2c3e50">Integration</text>
  <text x="610" y="300" font-family="Arial, sans-serif" font-size="18" fill="#2c3e50">tests</text>
  <path d="M 610 285 Q 600 275 590 285" stroke="#2c3e50" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
  
  <!-- Arrow marker definition -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#2c3e50"/>
    </marker>
  </defs>
</svg>

