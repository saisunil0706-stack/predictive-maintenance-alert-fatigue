# Predictive Maintenance - Fighting Alert Fatigue

This project demonstrates the common industrial problem of **Alert Fatigue** using the AI4I 2020 Predictive Maintenance dataset.

### What I did:
- Compared Dumb threshold alerts vs Smart rule-based alerts
- Applied Isolation Forest for anomaly detection
- Built a Hybrid system (Rules + ML)
- Showed how combining domain knowledge with ML gives better results

### Results:
| Method              | Total Alerts | Failures Caught |
|---------------------|--------------|-----------------|
| Dumb System         | 5198         | 312/339         |
| Smart Rules         | 2088         | 254/339         |
| Isolation Forest    | 500          | 72/339          |
| Hybrid              | 2213         | 266/339         |

### Key Learning:
Pure Machine Learning is not always the best. In industrial settings, combining simple domain rules with ML usually works better.

### Next Steps:
- Improve the hybrid logic
- Try better models
- Move towards edge / IoT concepts
