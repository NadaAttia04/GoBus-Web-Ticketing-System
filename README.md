# 🚌GoBus-Web-Ticketing-System
A modern web-based ticket booking platform for Go Bus Egypt, featuring real-time trip tracking, online seat reservation, secure payments, and multilingual support.
<img width="1600" height="765" alt="image" src="https://github.com/user-attachments/assets/f4b1f7bd-bb59-42c3-bc03-b85a0e1ca677" />
<img width="1600" height="773" alt="image" src="https://github.com/user-attachments/assets/99059aa2-17b9-4e19-abc3-48b533d8fa8f" />
<img width="1600" height="771" alt="image" src="https://github.com/user-attachments/assets/18615895-0836-4368-bf12-0741bad5d674" />
<img width="1600" height="762" alt="image" src="https://github.com/user-attachments/assets/078ddd0e-c0c0-492e-8674-65b0487b6bfe" />
<img width="1600" height="769" alt="image" src="https://github.com/user-attachments/assets/9cd407d6-1e43-44d9-9125-6b74fbd88455" />
<img width="1600" height="463" alt="image" src="https://github.com/user-attachments/assets/b6735996-aeb2-45d7-87c7-001e1e908f19" />
<img width="1600" height="563" alt="image" src="https://github.com/user-attachments/assets/e6ba9f51-9c74-4914-8fe4-23fd5468c30c" />
<img width="1600" height="380" alt="image" src="https://github.com/user-attachments/assets/8e5f78ec-f375-49e7-b9e1-46fd7b85c102" />
<img width="1600" height="380" alt="image" src="https://github.com/user-attachments/assets/66962d33-a016-4098-b15a-b05b53da496b" />
<img width="1600" height="631" alt="image" src="https://github.com/user-attachments/assets/11bec479-5db1-4dee-909a-10cf3cc9a4c7" />
<img width="1600" height="380" alt="image" src="https://github.com/user-attachments/assets/4ecffec5-d07a-4df6-95e9-3f04e778a6ca" />
<img width="1600" height="379" alt="image" src="https://github.com/user-attachments/assets/0183acdb-387d-4778-bc0d-3f9daa990246" />
<img width="1600" height="769" alt="image" src="https://github.com/user-attachments/assets/b0d206d0-2671-4757-9660-ecd9ab8892f9" />
<img width="1600" height="761" alt="image" src="https://github.com/user-attachments/assets/0347682d-7d3e-48ec-b2ee-353fe228c621" />

## 1. Introduction
The **Go Bus Web Ticketing System** is a digital platform inspired by the prominent **Go Bus** company in Egypt.  
Its mission is to enhance the public transportation experience by providing a **fully online, secure, and user-friendly ticket booking solution** for intercity bus travelers.  
The system addresses common manual transport challenges by introducing **modern web technologies** and streamlining every aspect of the ticket reservation process.

---

## 2. Problem Statement

### Challenges Before Digitalization
- **Inaccurate Schedules:** Buses were frequently late, causing discomfort and passenger anxiety.  
- **Overcrowding:** Difficulties in securing seats, especially during peak hours.  
- **Lack of Integration & Information:** Limited integration with other transport services and outdated route/timetable details.  
- **High Costs & Inefficiency:** Traditional booking was time-consuming and sometimes costly.  
- **Service Disruptions:** Poor communication regarding trip changes or cancellations.

### Proposed Solution
- **Real-Time Bus Tracking:** Users can view live bus locations and timetables.  
- **Online Seat Reservation & Payment:** Supports cards, mobile wallets, and cash-on-delivery.  
- **Automated Customer Notifications:** Alerts for schedules, changes, and promotions.  
- **Comprehensive Customer Accounts:** Manage bookings, feedback, and support access.

---

## 3. System Objectives
- Digitize the end-to-end bus ticket booking process.  
- Provide real-time and accurate travel information.  
- Increase company efficiency and reduce manual errors.  
- Ensure accessibility (multi-language & cross-device).  
- Strengthen competitiveness by meeting global online booking standards.

---

## 4. System Analysis

### Feasibility Study
Survey results from Go Bus regular customers:
- **78%** prefer booking tickets online.  
- **62%** struggled with the old system interface.  
- **55%** require live trip updates.  
- **70%** favor mobile access.  
- **60%** desire more secure payment options.

### SWOT Analysis
**Strengths:** Established brand, loyal customer base, diverse routes.  
**Weaknesses:** Outdated legacy system, limited mobile features.  
**Opportunities:** Demand for online travel services, international expansion.  
**Threats:** Competitors, cybersecurity risks, user resistance to change.

---

## 5. Requirements

### 5.1 Business Requirements
- Modernize digital image and engagement process.  
- Expand target customer reach (including non-locals).  
- Streamline operations and minimize manual input.

### 5.2 User Requirements
- Search, select, and reserve seats easily.  
- Access real-time route maps, schedules, and seat availability.  
- Receive notifications and updates about trips.  
- Manage bookings and profiles (Arabic/English).  
- Use secure and flexible payment options.

### 5.3 System Requirements
- **Frontend:** HTML5, CSS3, JavaScript (React.js or similar).  
- **Backend:** Node.js or Python, PostgreSQL or MongoDB.  
- **Mobile Compatibility:** Native-like experience on smartphones and tablets.  
- **Third-Party Integrations:** Payments, SMS/email notifications, GPS tracking.  
- **Admin Dashboard:** Route, schedule, pricing management & analytics.

---

## 6. Functional & Non-Functional Requirements

### Functional Requirements
- User account creation, authentication, and management.  
- Dynamic trip and seat booking system.  
- Integrated payment gateway (cards, wallets, cash).  
- Admin dashboard for route, schedule, and pricing control.  
- Customer support and feedback modules.

### Non-Functional Requirements
- Page load ≤ 2 seconds.  
- Scalable for peak travel periods.  
- High reliability (99.9% uptime).  
- Secure data transmission (SSL, regular security audits).  
- Accessibility compliance (WCAG 2.1).

---

## 7. High-Level Architecture & System Design

### Key Entities
- **Passenger:** Personal and ticketing details.  
- **Employee:** Manages bookings and payments.  
- **Driver:** Associated with bus and trip details.  
- **Bus & Trip:** Vehicle info, route, timing, seat counts.  
- **Booking & Payment:** Links users to rides, seats, and payment status.

### Key Diagrams
- **Context Diagram:** Overall system interactions.  
- **DFD (Level 0/1):** Data flow from inquiry to booking confirmation.  
- **Use Case Diagram:** User/admin actions — login, booking, feedback, cancellation.  
- **ERD:** Backend data structure visualization.

---

## 8. Testing
- **User Login:** Valid and invalid credentials.  
- **Trip Search:** Accurate trip availability results.  
- **Booking Scenarios:** Tests for both cash and card payments.  
- **Cancel/Confirm Actions:** Ensure notifications and data updates.  
- **Multi-device Browsing:** Verify mobile and cross-platform performance.

---

## 9. User Interface
- Modern, intuitive interface with smooth booking flow.  
- Includes trip planners, booking overview, and printable QR-coded tickets.  
- **Multi-language toggle (Arabic/English).**  
- Seamless experience across mobile and desktop.

---

## 10. Conclusion
The **Go Bus Web Ticketing System** represents a major digital transformation in Egypt’s public transport sector.  
It combines **advanced web technologies** with real user needs to deliver a **secure, reliable, and convenient** platform for passengers and administrators alike — with room for scalability and continuous improvement.

---

## 🚀 How to Run the Project

### 1. Clone the Repository
git clone https://github.com/your-username/GoBus-Web-Ticketing-System.git  
cd GoBus-Web-Ticketing-System

### 2. Install Dependencies
# For backend:
cd backend  
npm install

# For frontend:
cd frontend  
npm install

### 3. Configure Environment Variables
# Create a .env file in both backend and frontend directories, and add your configurations:
DB_URI=your_database_connection_string  
JWT_SECRET=your_secret_key  
PAYMENT_API_KEY=your_payment_gateway_key

### 4. Run the Project
# Start backend:
npm run start

# Start frontend:
npm run dev

### 5. Access the App
# Visit:
http://localhost:3000  
to explore the system locally.

---

## 🔮 Future Enhancements
- **AI-based Demand Prediction:** Use AI models to predict peak times and optimize bus schedules.  
- **Mobile Application:** Develop native iOS/Android apps for easier on-the-go booking.  
- **Voice Assistant Integration:** Enable voice-based ticket booking.  
- **Loyalty & Reward System:** Offer points and discounts for frequent travelers.  
- **Smart Notification System:** Personalized alerts for offers, delays, and trip updates.  
- **Multi-City Integration:** Expansion to other transport networks and cities.

---

