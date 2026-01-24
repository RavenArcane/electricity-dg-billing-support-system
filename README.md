# ⚡ Towal Tower Electricity & DG Billing Support System

An Excel-based utility management system for commercial buildings to track electricity and diesel generator (DG) consumption across multiple offices, calculate accurate bills, and generate monthly reports.

## 📋 What This Does

**Solves the problem:** How to accurately track and bill electricity consumption for multiple offices/tenants in a commercial building, including backup generator usage during power cuts.

**Key Benefits:**
- Track daily electricity consumption for each office
- Monitor diesel generator usage during power outages
- Calculate accurate bills with Indian electricity factors (MSEB)
- Generate monthly consumption reports with charts
- Maintain a complete audit trail for the electricity board

## 📸 View the File

**[Access Electricity & DG Billing System](https://1drv.ms/x/c/3b61701caabf1310/IQC7buxmhsBiQ4nSEDPMyGSQARM89o-5plJi5-EEjc-5siw?e=7zXXsv)**

> **Password for settings sheet: `123`**

## 📊 Screenshots

### Dashboard - Monthly Consumption Summary
<img width="1341" height="635" alt="Supporting Worksheet" src="https://github.com/user-attachments/assets/55f3fecf-6d0d-4d29-a64d-828cf78ee31f" />

*Select month, office, and type (Electricity/DG) to view consumption charts and cost breakdowns*

### Detailed Billing Calculations
<img width="1338" height="634" alt="Raw Data Worksheet" src="https://github.com/user-attachments/assets/e3e8017f-4b40-4a58-9070-994ecccd0269" />

*All offices' consumption data with MSEB adjustment factors and cost calculations*

### Daily Meter Readings Entry
<img width="1337" height="628" alt="Raw Dump Worksheet" src="https://github.com/user-attachments/assets/fea837a4-f337-41c1-b4ff-511d04e868d9" />

*Simple entry form for daily opening and closing meter readings*

### Consumption Feedback & Notes
<img width="1345" height="653" alt="Consu  FeedBack Worksheet" src="https://github.com/user-attachments/assets/869ae984-b278-4c92-acbb-32fd82c47a9e" />

*Document why consumption increased or decreased each month*

## ✨ Main Features

### 1. Interactive Dashboard
- **Select Month**: Choose any month (Jan-24 to Jul-24)
- **Select Office**: Pick specific office (102, 309, 310, 311, etc.)
- **Select Type**: Electricity or DG (Diesel Generator)
- **View Charts**: Daily consumption bars, cost trends, comparisons
- **See Totals**: Monthly consumption with adjustment factors applied

### 2. Daily Meter Readings
Security guards simply record:
- Opening meter reading (start of day)
- Closing meter reading (end of day)
- System automatically calculates consumption and cost

### 3. Multi-Office Tracking
- Track 20+ offices separately (102, 309, 310, 311, 312, 313, 314, 315, etc.)
- Each office gets individual bill
- Compare consumption across offices

### 4. Indian Billing Factors (MSEB Compliance)
- **Adjustment Factor for Electricity**: 0.987937707 or 1.0068
- **Adjustment Factor for DG**: 1.064232000
- Ensures accurate billing per MSEB requirements

### 5. DG (Diesel Generator) Tracking
- Track diesel consumption during power cuts
- Separate rates for diesel (₹29.32, ₹31.26 per liter)
- Calculate DG backup costs separately

### 6. Consumption Types
Track separately:
- **Electricity**: General office power
- **HVAC**: Air conditioning/heating
- **AC**: Separate AC units
- **DG**: Diesel generator backup

### 7. Automated Calculations
- Consumption = Closing Reading - Opening Reading
- Billable Units = Consumption × Adjustment Factor
- Cost = Billable Units × Rate
- Monthly totals automatic

### 8. Consumption Feedback
Document reasons for consumption changes:
- "Increased due to 3 extra working days"
- "Summer month - higher AC usage"
- "Rate increased from ₹20.58 to ₹23.08"
- "More employees joined"

## 🚀 How to Use

### Quick Start (3 Steps)

**Step 1: Set Up (One-Time)**
1. Download the file from the link above
2. Go to "Validations" sheet (Password: 123)
3. Add your office numbers and current electricity rates

**Step 2: Daily Entry (Security Guard - 5 Minutes)**
1. Go to "Daily Readings" sheet
2. Enter date, office number, opening reading, closing reading
3. System calculates consumption and cost automatically

**Step 3: View Reports (Anytime)**
1. Go to "Supporting" (Dashboard) sheet
2. Select month, office number, and type
3. View charts and totals instantly

### Monthly Billing Process

**End of Each Month:**
1. **Verify** all daily readings are entered
2. **Check** Raw Data sheet for calculation accuracy
3. **Add** consumption feedback explaining any variations
4. **Generate** bills using dashboard totals
5. **Backup** the file for audit records

## 📊 What You'll See

### Dashboard Shows:
- **Daily consumption table** (all 31 days)
- **Bar charts** showing consumption by day
- **Cost comparison** charts (month-over-month)
- **Total consumption** with adjustment factors
- **Monthly bill amounts** for electricity and HVAC

### Example Output:
```
Office: 319
Month: May-24
Type: Electricity

Total Consumption: 2,764.20 units
Adjustment Factor: 1.0068
Billable Units: 2,782.99 units
Rate: ₹20.58 per unit
Total Cost: ₹57,273.91

Month Comparison:
March-24: ₹2,697.63
April-24: ₹2,782.99
May-24: ₹2,966.94
```

## 💡 Key Benefits

✅ **Accurate Billing**: MSEB-compliant adjustment factors  
✅ **Time Saving**: Automatic calculations reduce manual work  
✅ **Audit Ready**: Complete daily reading history  
✅ **Transparency**: Tenants can see daily consumption breakdown  
✅ **Easy Entry**: Security guards just enter 2 numbers daily  
✅ **Multi-Tenant**: Track 20+ offices separately  
✅ **DG Backup**: Track diesel costs during power cuts  
✅ **Cost Analysis**: Visual charts show consumption patterns  

## 🔧 Customization

### Add New Offices:
1. "Validations" sheet → Add office number
2. Start entering daily readings for that office

### Update Electricity Rates:
1. "Validations" sheet (Password: 123)
2. Change rate value
3. All calculations update automatically

### Change Adjustment Factors:
1. "Validations" sheet → Update factor value
2. New factor applies to all new calculations

## 📈 Use Cases

**Property Managers:**
- Bill each tenant based on actual consumption
- Track which offices use most electricity
- Justify costs with detailed reports

**Facility Managers:**
- Monitor daily consumption patterns
- Identify unusual spikes (investigate issues)
- Plan for seasonal variations (summer AC costs)

**Finance Teams:**
- Accurate cost allocation per department
- Budget forecasting with historical data
- Variance analysis month-over-month

**Audit Compliance:**
- Complete daily reading records
- Documented consumption feedback
- MSEB billing factor compliance

## 💼 Technical Skills Demonstrated

- Excel advanced formulas (VLOOKUP, SUMIFS)
- Data validation and dropdown menus
- Dynamic dashboards with charts
- Multi-sheet data management
- Automated calculations and reporting
- Indian utility billing knowledge (MSEB)
- Audit trail documentation
- User-friendly interface design

## 📞 Contact

For customization or questions:
- [**GitHub**](https://github.com/heysubu)
- **Email**: suubhamghadge@gmail.com
- [**LinkedIn**](https://www.linkedin.com/in/subhamghadge/)

## 📄 License

MIT License - Free to use and modify

---

### 🌟 Project Stats

![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoft-excel)
![Utility Management](https://img.shields.io/badge/Utility-Management-blue)
![Multi--Office](https://img.shields.io/badge/Multi--Office-Support-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

**⚡ Simplify Your Electricity Billing - Accurate, Automated, Audit-Ready**

**⭐ If this helps your facility management, please star this repository!**

**💬 Questions? Open an issue and I'll help you get started!**
