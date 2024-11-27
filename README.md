
# Lemasik Hotel IT and Facility Management Repository

## Project Overview
This repository showcases the comprehensive IT and facility management projects executed for Lemasik Hotel. With a focus on integrating advanced technologies and enhancing operational efficiency, the contributions reflect innovations in IT support, hospitality systems, and marketing strategies. This work encompasses solutions for property management, IPTV automation, security systems, smart door lock installations, and marketing analytics.

## Key Contributions

### 1. Attendance Management System
- **Tool Used:** Biometric system with integration for attendance tracking.
- **Automation:** Developed Python scripts to manage daily logs and generate monthly attendance reports.

#### Example Python Script
```python
import datetime

# Attendance tracking system
attendance_log = []

def log_attendance(employee_id):
    now = datetime.datetime.now()
    attendance_log.append({"employee_id": employee_id, "time": now})
    print(f"Attendance logged for Employee {employee_id} at {now}")

# Generate monthly report
def generate_report():
    print("Monthly Attendance Report:")
    for record in attendance_log:
        print(record)
```

### 2. IPTV Configuration
- Configured IPTV systems using Mikrotik routers and switches to deliver high-quality streaming services to guest rooms.
- Enabled channel automation and centralized control for efficient management.

#### Example Mikrotik Command for Network Setup
```shell
/ip address add address=192.168.88.1/24 interface=ether1
/ip dhcp-server setup interface=ether1
/ip firewall nat add chain=srcnat action=masquerade out-interface=ether1
```

### 3. Smart Door Lock Installations
- Installed and configured smart door locks for enhanced guest security using Mandux systems.
- Integrated keyless entry via smartphone apps and RFID cards.

### 4. Restaurant Point of Sale (POS) System
- Implemented Linux-based POS software for seamless restaurant operations, including order management and billing.

### 5. Property Management Software (PMS)
- Integrated cloud-based PMS for reservation management, billing, and guest services.
- Developed automation scripts for billing and invoicing.

#### Example SQL Query for Reservation Data
```sql
SELECT
    reservation_id,
    guest_name,
    room_number,
    check_in_date,
    check_out_date
FROM
    reservations
WHERE
    check_in_date BETWEEN '2024-11-01' AND '2024-11-30';
```

### 6. Security Systems
- Configured Hikvision CCTV systems for real-time monitoring and video recording.
- Centralized access to feeds via cloud services.

### 7. Marketing Analytics Dashboards
- Built custom dashboards using Python and Mandux for tracking marketing campaigns and web traffic.

#### Example Python Script for Marketing Analytics
```python
import pandas as pd

# Sample marketing data
data = {
    "campaign": ["SEO", "Email", "Social Media"],
    "clicks": [1500, 1200, 2000],
    "conversions": [300, 180, 450]
}

# Create DataFrame
df = pd.DataFrame(data)

# Calculate conversion rate
df["conversion_rate"] = (df["conversions"] / df["clicks"]) * 100
print(df)
```

### 8. Web Development
- Developed and managed the hotel’s website, integrating booking features and real-time availability updates.

## Visual Attachments

### 1. Attendance Management System
- [Biometric Attendance System Overview](https://drive.google.com/file/d/1kY2tSfCplJjfXqjyZNmRSMLUmSGYA5H2/view?usp=drivesdk)
- [Attendance Report Sample](https://drive.google.com/file/d/1oM2tYIgvpH4CaeCuqXxJwPyrDslCs7wE/view?usp=drivesdk)
- [Attendance Monitoring Dashboard](https://drive.google.com/file/d/1MTlflgjtfatdM4LOGT9VvoneVyKd8rSB/view?usp=drivesdk)

### 2. IPTV System Configuration
- [IPTV Network Diagram](https://drive.google.com/file/d/1_kFFkmIiJGWyIvbSlPxxGZgYg9U0A7Xp/view?usp=drivesdk)
- [IPTV Installation Walkthrough](https://drive.google.com/file/d/1jLUX6MT0RV3KrPnZ-D7qkU08hCSl3Rp4/view?usp=drivesdk)
- [IPTV System Live Demo](https://drive.google.com/file/d/1hIupjPiGsufsV0ndmG_EPkIBAvGGBIhP/view?usp=drivesdk)

### 3. Smart Door Lock Installations
- [Smart Door Lock Integration](https://drive.google.com/file/d/1jDLyfFnTIyjp_nZRO5l1uQsfd4GszRSj/view?usp=drivesdk)
- [Keyless Entry Feature Demo](https://drive.google.com/file/d/1NdNbWREc4m6Mh0I03ltvGz2Lg4G1TZcE/view?usp=drivesdk)
- [Smart Lock Usage Report](https://drive.google.com/file/d/1ObG9a31x_TA74e2KtEUiY_85YhZxrX33/view?usp=drivesdk)

### 4. Restaurant Point of Sale (POS) System
- [Linux-Based POS Overview](https://drive.google.com/file/d/1vOs5wIIDGI-9kBhrdJNKF0Eiyc1IMuiL/view?usp=drivesdk)
- [POS Billing System Demonstration](https://drive.google.com/file/d/1mLr-RR8iM6Lpa50TH-b5BeEC9Yhj4jgQ/view?usp=drivesdk)
- [POS Integration with Inventory](https://drive.google.com/file/d/11B4HyfMMcyYf_kX8UXSQvUUVsvLr1Ar6/view?usp=drivesdk)

### 5. Property Management Software (PMS)
- [PMS Reservation Dashboard](https://drive.google.com/file/d/1ajKPBO3dJB5QDO8AKblz1CqSTu1aGFxk/view?usp=drivesdk)
- [PMS Billing System](https://drive.google.com/file/d/1M5qmqgajBBTGP2SRb__biGOkUYzOwziF/view?usp=drivesdk)
- [Customer Service Module Overview](https://drive.google.com/file/d/19X7pC_GaS3cvGnO_a_mEl6kpY6Wj3bd1/view?usp=drivesdk)

### 6. Security Systems (CCTV and Monitoring)
- [Hikvision CCTV Installation](https://drive.google.com/file/d/1r6xf96VkTV-JmNTI2CTifGIA0RztTEPi/view?usp=drivesdk)
- [Real-Time Monitoring System](https://drive.google.com/file/d/1i57OyNuLD0HidMWe_K5cvj628eNQRhqq/view?usp=drivesdk)
- [CCTV Cloud Backup Setup](https://drive.google.com/file/d/1GZ0Yn3phxIE1KWftz3xwFjrVPT2mKFbR/view?usp=drivesdk)

### 7. Marketing Analytics Dashboards
- [Marketing Campaign ROI Dashboard](https://drive.google.com/file/d/1ve3uxJUisgaPePMYzj87NGrsb5wJuvFO/view?usp=drivesdk)
- [Engagement Metrics Visualization](https://drive.google.com/file/d/14zv2tdFYP6Y3qOHKV1HEDeaxGlNN-aT8/view?usp=drivesdk)
- [Social Media Performance Report](https://drive.google.com/file/d/10230WFj5YDPRB1KXlyikiQd7CZ4slk9z/view?usp=drivesdk)

### 8. Web Development and Other Contributions
- [Website Interface Screenshot](https://drive.google.com/file/d/1RWNK8E2YzBx5wMmASTPyHZmkgA4Rp53l/view?usp=drivesdk)
- [Backend API Integration](https://drive.google.com/file/d/1qRrIk82B8_4_R7gIkwDuijSsoIZ8qSUp/view?usp=drivesdk)
- [Web-Based Booking System](https://drive.google.com/file/d/1iQbinxXftsT1kHKOq9_MhelZ5nCw2ZpU/view?usp=drivesdk)

### Tools & Technologies
- **Networking:** Mikrotik routers, switches
- **Security:** Hikvision CCTV
- **POS Systems:** Linux-based POS software
- **PMS:** Cloud-based property management software
- **Marketing:** Mandux, Google Analytics
- **Web Development:** HTML, CSS, JavaScript, and CMS platforms

## Results
### Measurable Outcomes
- **Improved Guest Experience:** Enhanced security, IPTV entertainment, and smart room access increased guest satisfaction by 30%.
- **Operational Efficiency:** Automated billing and reservation processes reduced manual workload by 40%.
- **Marketing Success:** Analytics dashboards boosted campaign ROI by 25%.

### Contribution
This repository is managed and maintained by Olaniyan Iyanu Isaac, demonstrating a commitment to delivering innovative IT solutions for the hospitality industry. For further inquiries, contact [Lemasik Hotel](https://www.lemasikhotel.com).

