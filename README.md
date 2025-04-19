# Hospital Dashboard

![Dashboard Preview](https://img.shields.io/badge/Status-Active-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

A modern, responsive web application for hospital management that helps track patients, doctors, and streamline daily hospital operations.

## 📋 Overview

The Hospital Dashboard is a comprehensive web-based management system designed for healthcare facilities. It provides real-time statistics, patient tracking, doctor management, and token system management all in one place. With an intuitive interface and responsive design, it allows hospital staff to efficiently manage daily operations.

## ✨ Features

### 📊 Real-time Statistics
- Display current patient counts for General Ward and ICU
- Track number of consulting patients
- Monitor current token numbers for each doctor

### 👨‍⚕️ Doctor Management
- Add new doctors with qualifications and visiting hours
- Track doctor's patient count and current token
- Remove doctors when they're no longer providing services
- Each doctor is assigned a unique serial letter (A, B, C, etc.)

### 🏥 Patient Management
- Admit patients to General Ward or ICU
- Record reason for admission
- Add consulting patients and assign them to doctors
- Discharge patients with discharge notes
- Token system for managing consulting patient queues

### ⏰ Time Management
- Display real-time date and time
- Set and display doctor visiting hours
- Report and display delays in doctor schedules

### 📱 User Interface
- Modern, responsive design
- Context menus for additional options
- Modal dialogs for data entry
- Notification system for important alerts

### 📊 Data Export
- Export patient data to CSV for reporting and analysis

### 💾 Data Persistence
- All data is stored in local storage for persistence between sessions

## 🚀 How to Use

### Doctor Management
1. Click "Add Doctor" to register a new doctor
2. Fill in the doctor's name, qualification, and visiting hours
3. Right-click on a doctor's card to access additional options
4. Use the +/- controls to adjust patient count
5. Use token controls to manage current token numbers

### Patient Management
1. Click "Admit Patient" to admit a new patient
2. Choose between General Ward or ICU
3. Click "Add Consulting Patient" to register outpatient consultations
4. Use "Discharge Patient" to release patients from the ward

### Reporting Delays
1. Click "Report Delay" on a doctor's card
2. Enter the delay duration in minutes
3. A notification will appear showing the doctor's delay

### Exporting Data
1. Click "Export Patient Data" to download a CSV file
2. The file includes all patient records with admission and discharge details

## 🔧 Technical Details

The dashboard is built using:
- HTML5, CSS3, and JavaScript
- Local storage for data persistence
- Responsive design principles for all device sizes
- No external dependencies required

## 🔒 Privacy & Security

All data is stored locally in the browser's storage. No information is transmitted to any server, ensuring complete privacy of sensitive patient information.

## 🎨 Customization

The dashboard can be easily customized by modifying the CSS styles or extending the JavaScript functionality to meet specific hospital requirements.

## 📝 License

This project is released under the MIT License.

---

Designed and developed for enhancing healthcare management through technology.
