# Weather-Driven AI Operations Planner  
**Beachside Coffee & Ice Cream Kiosk Automation**

## Overview

In this project, I built an automated AI workflow in **Zapier** that helps a beachside coffee and ice cream kiosk plan daily operations using real-time weather data.

Every morning, the system sends a simple, decision-ready email with:

- Product stocking recommendations  
- Staffing suggestions  
- Promotional ideas  

The objective: reduce manual planning, improve daily decisions, and align operations with weather-driven demand.

---

## Problem

For a beachside kiosk, weather directly impacts:

- Foot traffic  
- Product demand (hot drinks vs cold treats)  
- Staffing needs  
- Daily revenue potential  

Manual weather checks and guesswork lead to:

- Overstocking or understocking  
- Poor staffing allocation  
- Missed revenue opportunities  
- Reactive instead of proactive decisions  

The business needed a structured, automated decision-support system.

---

## Solution Architecture

### 1. Weather Data Trigger

Each morning, Zapier pulls updated weather data, including:

- Temperature forecast  
- Precipitation probability  
- Wind conditions  
- Cloud coverage  

This acts as the primary operational input.

---

### 2. AI Analysis Layer

Weather data is sent to an AI model inside the workflow.

The AI evaluates conditions and generates:

- High-demand product predictions  
- Low-demand product warnings  
- Recommended staffing levels  
- Suggested promotional messaging  

Instead of raw data, the owner receives clear recommendations.

---

### 3. Email Output

Zapier compiles the AI output into a structured, easy-to-read email delivered each morning.

Email sections include:

- **Weather Summary**
- **Product Strategy**
- **Staffing Plan**
- **Promotion Recommendation**

The output is operational, not technical.

---

## Example Scenarios

### Hot, Sunny Day
- Increase ice cream inventory  
- Reduce hot coffee stock  
- Add one extra staff member  
- Promote cold combo specials  

### Rainy or Windy Day
- Reduce ice cream prep  
- Increase hot beverage focus  
- Lean staffing schedule  
- Push comfort drink promotions  

---

## Workflow Summary

1. Scheduled morning trigger  
2. Pull weather forecast  
3. Send structured data to AI  
4. Generate operational recommendations  
5. Deliver formatted email to owner  

Total manual effort required: zero.

---

## Business Impact

- Faster daily planning  
- Data-backed decisions  
- Reduced waste  
- Better labor allocation  
- Increased revenue alignment with demand  

The kiosk owner no longer checks weather apps or makes reactive decisions. The system delivers clarity before the day begins.

---

## Technology Stack

- Zapier (Automation Orchestration)  
- Weather API (Forecast Data Source)  
- AI Model (Decision Logic Layer)  
- Email Integration (Delivery Layer)  

---

## Scalability

This system can be expanded to:

- Track daily revenue vs weather patterns  
- Predict inventory restock thresholds  
- Automate supplier order suggestions  
- Send SMS alerts for extreme weather shifts  
- Generate weekly performance summaries  

---

## Conclusion

This project demonstrates how AI-driven automation can convert environmental data into actionable operational strategy.

The result: smarter planning, lower waste, improved staffing efficiency, and better revenue positioning — delivered automatically every morning.
