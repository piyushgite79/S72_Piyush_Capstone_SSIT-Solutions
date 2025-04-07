# S72_Piyush_Capstone_SSIT-Solutions

### **README File for Capstone Project**
### **Overview**  
The **AI-Powered Carbon Footprint Tracker** is a sustainable IT solution designed to help Indian SMEs and individuals monitor, reduce, and optimize their tech-related carbon emissions. The platform aligns with Shree Samarth IT Solutions Pvt. Ltd.'s mission to provide innovative and reliable IT infrastructure solutions that empower businesses to achieve their full potential.  

### **Problem Statement**  
India’s SMEs face two critical challenges:  
1. **Inefficient IT Infrastructure**: Outdated systems waste energy and increase costs.  
2. **Sustainability Blind Spot**: No affordable tools exist to measure and reduce tech-related carbon emissions, despite India’s **2070 net-zero goal** and global ESG compliance pressures.  

### **Solution**  
The MVP focuses on two core features:  
1. **AI-Powered Carbon Footprint Tracker**:  
   - **Energy Monitoring**: Track energy usage of servers, devices, and cloud services (manual input + free APIs).  
   - **Emission Estimation**: AI calculates emissions using India’s regional energy mix (coal vs. renewables).  
   - **Actionable Insights**: Recommendations like "Switch to energy-efficient hardware" or "Optimize cloud usage."  
   - **Gamification**: "Green IT Certificates" and leaderboards to incentivize adoption.  



---

## **Day-by-Day Plan for the Capstone Journey**  

### **Week 1: Planning & Setup**  
#### **Day 1: Research & Scope Finalization**  
- Review company mission and goals to align the MVP with SSIT Solutions' vision.  
- Research free APIs for Indian energy data (e.g., [India Energy Dashboard](https://www.cea.nic.in/)).  
- Define MVP scope: Carbon tracker + Helpdesk system.  

#### **Day 2: Wireframing & Tools Setup**  
- Create wireframes for the UI using **Figma** (free). Focus on:  
  - Input fields for energy usage.  
  - A dashboard for displaying emissions and insights.  
- Set up **GitHub repository** for version control and collaboration.  

#### **Day 3: Frontend Setup**  
- Install necessary tools for frontend development:  
  - **Node.js** (for React.js setup).  
  - **VS Code** (code editor).  
- Initialize a new React.js project using `npx create-react-app`.  

---

### **Week 2: Frontend Development**  
#### **Day 4: Basic UI Structure**  
- Build the basic structure of the carbon tracker UI using **React.js**.  
- Add input fields for energy usage (servers, devices).  

#### **Day 5: Visualizations & Gamification**  
- Use **Chart.js** to create a simple chart for visualizing emissions.  
- Add gamification elements (leaderboards, certificates).  

#### **Day 6: Testing & Responsiveness**  
- Test the UI on mobile and desktop to ensure responsiveness.  

---

### **Week 3: Backend Development**  
#### **Day 7: Backend Setup**  
- Install necessary tools for backend development:  
  - **Node.js + Express.js** (set up a new project using `npm init`).  
  - Install required packages like `express`, `mongoose` (for MongoDB), and `cors`.  

#### **Day 8: API Endpoints**  
- Create basic API endpoints:  
  - `/api/carbon` for carbon emission calculations.  
  - `/api/login` for user authentication (placeholder for now).  

#### **Day 9: Database Integration**  
- Connect to **MongoDB Atlas** (free tier) for database storage.  

---

### **Week 4: AI Integration & Testing**  
#### **Day 10: AI Model Integration**  
- Integrate a pre-trained regression model (TensorFlow Lite) for emission predictions.  

#### **Day 11: Full Flow Testing**  
- Test the full flow: Input energy data → Calculate emissions → Display results on the dashboard.  

#### **Day 12: Debugging & Refinement**  
- Fix bugs and refine the UI/UX based on testing feedback.  

---

### **Week 5: Deployment & Feedback**  
#### **Day 13: Deployment**  
- Deploy the MVP on **Heroku/Vercel** (free tiers).  

#### **Day 14: Initial Feedback**  
- Share the deployed app with a small group of users (e.g., friends, family, or colleagues) for initial feedback.  

#### **Day 15: Iteration**  
- Refine features based on feedback and prepare for launch.  

---

### **Week 6: Final Touches & Launch**  
#### **Day 16: Final Testing**  
- Conduct final testing to ensure everything works as expected.  

#### **Day 17: Documentation**  
- Write documentation for the project (user guide, technical details).  

#### **Day 18: Launch**  
- Officially launch the MVP and promote it through LinkedIn and Instagram.  

---

## **Tech Stack**  
- **Frontend**: React.js, Chart.js, CSS animations.  
- **Backend**: Node.js + Express.js, Python (AI/ML).  
- **Database**: MongoDB Atlas (free tier).  
- **AI/ML**: TensorFlow Lite for carbon predictions.  
- **Hosting**: Heroku/Vercel (free tiers).  

---

