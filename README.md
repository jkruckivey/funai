# 🎯 ML Development Cycle Simulator: Student Instructions

## Overview & Context
You're about to experience how bias cascades through the machine learning development process using an interactive pipeline simulation. This builds on the COMPAS case study you've been analyzing, where algorithmic bias in criminal justice predictions sparked a national debate about fairness in AI systems.

## Learning Objectives
By completing this simulation, you will:
- **Map bias sources** to specific stages in the ML development cycle
- **Experience cascade effects** - how bias at one stage amplifies throughout the pipeline  
- **Compare industry impacts** across medical, financial, hiring, and criminal justice AI systems
- **Analyze trade-offs** between different fairness definitions and business objectives
- **Develop evaluation frameworks** for identifying bias before deployment

---

## 🔧 How to Use the Simulator

### 1. Explore the Pipeline (5 minutes)
- Click on each of the 7 development stages to read detailed explanations
- Notice how the stages flow left-to-right: Data Collection → Deployment → Monitoring
- Each stage explanation includes COMPAS examples and business impact analysis

### 2. Inject Bias at Different Stages (10 minutes)
- Use the bias sliders **directly within each stage box**
- Start with Stage 1 (Data Collection) - move the slider to 6/10
- Watch how the bias "cascades" - downstream stages turn orange to show cascade effects
- Observe the real-time impact on all four industry scenarios in the right panel

### 3. Compare Industry Scenarios (10 minutes)
- Notice how the same bias level affects different industries differently
- **Medical AI** is most sensitive to validation bias (Stage 4)
- **Credit Scoring** is most affected by data preparation bias (Stage 2)  
- **COMPAS Algorithm** shows the highest sensitivity to deployment bias (Stage 6)
- **Hiring AI** suffers most from monitoring bias (Stage 7)

### 4. Explore Preset Scenarios (10 minutes)
- Use the scenario buttons: 🏥 Medical, 💰 Lending, 🏢 Hiring, ⚖️ COMPAS
- Each preset loads realistic bias patterns based on real-world case studies
- **Try the COMPAS scenario** - it replicates the bias sources from the ProPublica investigation

### 5. Experiment with Combinations (5 minutes)
- Try injecting bias at multiple stages simultaneously
- Notice how **compound effects** multiply the overall bias impact
- Pay attention to the cascade multiplier effect in the insights panel

---

## 💡 Key Questions to Consider

**During Simulation:**
- Which stage seems most critical for preventing bias in your industry?
- How do cascade effects change your mitigation strategy priorities?
- When does accuracy vs. fairness become a real trade-off?

**For Reflection:**
- If you were managing the COMPAS deployment, at which stage would you intervene?
- How would you explain these bias sources to non-technical stakeholders?
- What validation approaches could have detected COMPAS bias earlier?

---

## 📊 Understanding the Metrics

- **Bias Level (%)**: Overall system bias calculated using industry-specific multipliers
- **Accuracy (%)**: Model performance degraded by bias injection  
- **Fairness Score (%)**: Measured as equal treatment across demographic groups
- **Insights Panel**: Real-time analysis of your current bias configuration

---

## 🎯 Success Indicators

You've successfully completed the simulation when you can:
- ✅ Explain how bias at Stage 1 affects Stage 7 outcomes  
- ✅ Predict which industry scenarios will be most affected by specific bias sources  
- ✅ Articulate why early-stage intervention is more effective than late-stage fixes  
- ✅ Connect simulation insights back to the COMPAS case study findings  

---

## ⏰ Time Allocation: 40 minutes total
- **Exploration**: 5 minutes  
- **Bias injection experiments**: 10 minutes
- **Industry comparison**: 10 minutes  
- **Preset scenarios**: 10 minutes
- **Reflection & synthesis**: 5 minutes

---

**Ready to begin?** Click on Stage 1: Data Collection to start exploring how bias enters AI systems, then experiment with the bias sliders to see cascade effects in real-time.

## About This Project

This interactive simulator was developed for the **Fundamentals of AI for Business** course at Ivey Business School. It demonstrates how algorithmic bias emerges and propagates through the machine learning development lifecycle, using real-world case studies including the COMPAS recidivism prediction algorithm.

**Course**: Fundamentals of AI for Business  
**Institution**: Ivey Business School, Western University  
**Instructor**: Professor Yasser Rahrovani  

### Key Features
- Interactive 7-stage ML development pipeline
- Real-time bias cascade visualization
- 4 industry scenario comparisons
- COMPAS case study integration
- Responsive design for all devices