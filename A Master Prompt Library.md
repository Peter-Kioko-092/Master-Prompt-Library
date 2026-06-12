# Master prompt 1

## **1\. Business Pitch or Proposal Draft**

**Focus:** Persuasive structure and value proposition.

* **Framework:** **CREATE** (Character, Request, Examples, Audience, Type, Extras)  
    
* **Prompt:**  
  Act as a **\[Expert Industry Consultant\]**. I need you to draft a business proposal for **\[Project/Service Name\]**. The goal is to convince **\[Target Stakeholder/Investor\]** to approve the project. Use a tone that is **\[Tone: e.g., Bold and Innovative\]**. Ensure you include sections for Problem Statement, Solution, Market Viability, and ROI. Avoid jargon unless it is specific to **\[Industry\]**.

* **The Fully Populated Prompt:**  
  Act as a **Lead Venture Capital Consultant**. I need you to draft a business proposal for **Project 'Shamba-Smart'**, an AI-driven irrigation and soil health monitoring system. The goal is to convince **the East African Development Bank** to approve a $500k expansion grant. Use a tone that is **Resilient and Professional**. Ensure you include sections for Problem Statement, Solution, Market Viability, and ROI. Avoid jargon unless it is specific to **Precision Agriculture**.

* **Full Example Output:**  
  **PROPOSAL: PROJECT SHAMBA-SMART EXPANSION**  
  **1\. Problem Statement** Small-to-medium scale farmers in semi-arid regions face unpredictable harvest yields due to erratic rainfall patterns and declining soil nutrient density. Existing irrigation solutions are often "dumb" systems that waste water or fail to account for specific crop nitrogen requirements, leading to a 30% average loss in potential annual revenue.  
  **2\. Solution** Shamba-Smart is an integrated Precision Agriculture suite. Using low-cost IoT soil sensors and satellite-linked AI, the system provides real-time moisture mapping and automated drip irrigation. It ensures that water and fertilizer are applied only when and where needed, based on localized data rather than regional averages.  
  **3\. Market Viability** With the East African agricultural sector contributing significantly to regional GDP, there is a massive untapped market for climate-resilient tech. Current pilot programs in Machakos have shown a 25% increase in crop yield within one season.  
  **4\. Projected ROI** For the investor, the $500k grant will facilitate the manufacturing of 5,000 units. We project a break-even point at 14 months post-expansion, with a social ROI of increasing food security for over 10,000 households.

* **Quality Score: 9/10**

* **Justification:** The prompt successfully balances investor-grade financial projections with a tone appropriate for a regional development bank. It clearly bridges the gap between IoT technicality and practical agricultural benefits.




# Master prompt 2

## **2\. Formal Legal or Policy Inquiry**

**Focus:** Precision, objectivity, and risk assessment.

* **Framework:** **CoT** (Chain of Thought)

* **Prompt:**  
  We need to analyze the legal implications of **\[Action/Policy\]** under **\[Specific Regulation/Law\]**. Let's think through this step-by-step:  
  1. Identify the core compliance requirements of **\[Law\]**.  
  2. Evaluate how **\[Action\]** aligns or conflicts with these requirements.  
  3. Identify potential liability risks.  
  4. Suggest mitigation strategies. Please provide the final assessment in a formal memorandum format.

*  **The Fully Populated Prompt:**  
  We need to analyze the legal implications of **storing user biometric data on cloud servers located outside of Kenya** under **the Data Protection Act (2019)**. Let's think through this step-by-step:  
  1. Identify the core compliance requirements of the Act regarding cross-border data transfers.  
  2. Evaluate how offshore cloud storage of sensitive personal data (biometrics) conflicts with these requirements.  
  3. Identify potential liability risks for the company.  
  4. Suggest mitigation strategies. Please provide the final assessment in a formal memorandum format.  
* **Full Example Output:**

 **MEMORANDUM** **SUBJECT:** Legal Risk Assessment of Cross-Border Biometric Data Storage

 **1\. Compliance Requirements:** Section 48 of the Data Protection Act restricts the transfer of personal data outside Kenya unless the Data Commissioner has given a "white-list" approval or the recipient country has "adequate" data protection laws equivalent to Kenya’s.

 **2\. Evaluation of Conflict:** Biometric data is classified as "Sensitive Personal Data." The Act is stricter regarding its transfer. Storing this data offshore without explicit "Informed Consent" from the user specifically mentioning the geographic location of the server is a direct violation.

**3\. Liability Risks:** Non-compliance risks an administrative fine of up to KES 5 Million. Additionally, the company faces "Reputational Risk" should a data sovereignty audit be performed by the Office of the Data Protection Commissioner (ODPC). 

**4\. Mitigation:** We must implement "Data Residency" by using local cloud availability zones or localized data masking where the biometric templates remain in-country while non-sensitive metadata is processed offshore.

**Quality Score: 10/10**

**Justification:** By identifying biometrics as "Sensitive Personal Data," the response demonstrates a precise understanding of the specific restrictions within the Data Protection Act. The step-by-step logic provides a legally sound roadmap that is immediately ready for a senior review.

# Master prompt 3

## **3\. Project Management Plan**

**Focus:** Logistics, milestones, and task breakdown.

* **Framework:** **ROLE** (Role, Objective, Limits, Execution)

* **Prompt:**  
  **Role:** You are a Senior Project Manager certified in PPD/Agile. **Objective:** Create a comprehensive project timeline for **\[Project Name\]** which lasts **\[Duration\]**. **Limits:** The budget is capped at **\[Amount\]** and we only have a team of **\[Number\]** people. No overtime is permitted. **Execution:** Present this as a week-by-week breakdown with specific milestones and a brief Risk Register for potential bottlenecks.

* **The Fully Populated Prompt:**  
  **Role:** You are a Senior Project Manager certified in Agile.  
  **Objective:** Create a comprehensive project timeline for **the 'Lipa-Sasa' Peer-to-Peer Payment App Launch** which lasts **6 weeks**.  
   **Limits:** The budget is capped at **$10,000** and we only have a team of **4 people (1 Product Owner, 2 Devs, 1 QA)**. No overtime is permitted.   
  **Execution:** Present this as a week-by-week breakdown with specific milestones and a brief Risk Register for potential bottlenecks.  
* **Full Example Output:**  
  **PROJECT TIMELINE: LIPA-SASA P2P LAUNCH**  
  **Week 1-2: Core Sprint & API Integration**  
  * **Tasks:** Finalize M-Pesa B2C/C2B API integrations; Setup encrypted user authentication.  
  * **Milestone:** Successful "Penny-Drop" transaction test in sandbox. **Week 3-4: UI Refinement & QA**  
  * **Tasks:** UI stress testing; Load testing for 1,000 concurrent users; Bug fixing.  
  * **Milestone:** Beta-ready build approved by QA. **Week 5-6: Compliance & Go-Live**  
  * **Tasks:** Final security audit; Submission to App/Play Stores; Marketing "Blast" to waitlist.  
  * **Milestone:** Public launch. **Risk Register:**  
  * *Delay in API Approval:* (High Impact) Mitigation: Daily follow-ups with provider and early documentation submission.  
  * *Server Downtime:* (Medium Impact) Mitigation: Implement auto-scaling on cloud infrastructure.  
      
  * **Quality Score: 8.5/10**  
  * **Justification:** The inclusion of "Penny-Drop" testing as a milestone shows high domain-specific intelligence for the fintech sector. It loses a small margin only because the timeline is extremely aggressive for a team of four without a dedicated DevOps lead.  
  


# Master prompt 4

## **4\. Marketing Copy or Social Media Strategy**

**Focus:** Engagement, SEO, and brand voice.

* **Framework:** **CREATE**  
    
* **Prompt:**  
  **Character:** Creative Director at a top-tier ad agency.                                              **Request:** Develop a 1-week social media strategy for the launch of **\[Product\]**. **Examples:** Use the storytelling style of **\[Brand Name\]**.                                **Audience:** **\[Demographic: e.g., Gen Z Tech Enthusiasts\]**.                               **Type:** A mix of 3 Instagram captions, 2 LinkedIn thought-leadership posts, and 5 Twitter (X) hooks.                                                                                                            **Extras:** Include relevant hashtags and "Call to Action" buttons for each.

* **The Fully Populated Prompt:**  
  **Character:** Creative Director at a top-tier digital agency.                                         **Request:** Develop a 1-week social media strategy for the launch of **'Meroa Eco-Silk' collection**.                                                                                                     **Examples:** Use the storytelling style of **Patagonia mixed with Vogue**                 . **Audience:** **High-net-worth individuals interested in sustainable luxury**.              **Type:** A mix of 3 Instagram captions and 2 LinkedIn thought-leadership posts. **Extras:** Include relevant hashtags and "Call to Action" buttons.

* **Full Example Output:** **Instagram Post 1 (The Craft):** "True luxury doesn't cost the Earth. Discover the Meroa Eco-Silk collection—where heritage weaving meets 100% biodegradable silk."                                                                                                           **CTA:** Shop the Collection \[Link\]. \#SustainableLuxury \#MeroaEco \#QuietLuxury **LinkedIn Post 1 (The Industry Shift):**                                                                   "The fashion industry is at a crossroads. We believe that transparency is the new 'Couture.' At Meroa, we tracked every thread from the farm to the final stitch. Sustainability isn't a trend; it's the future of the luxury market."                                                                                                                            **CTA:** Read our Impact Report \[Link\]. \#EthicalFashion \#SupplyChainTransparency

* **Quality Score: 9/10**  
* **Justification:** The output perfectly captures the "Quiet Luxury" persona by prioritizing craftsmanship and ethics over aggressive sales tactics. It creates a cohesive brand narrative that works across both visual-heavy and text-heavy social platforms.

# Master prompt 5

## **5\. Technical Documentation or Code Review**

**Focus:** Clarity, syntax accuracy, and best practices.

* **Framework:** **CoT** (Chain of Thought)

* **Prompt:**  
  Review the following code for **\[Language/Framework\]**: **\[Insert Code Block\]**. First, explain what the code is currently doing. Second, identify any inefficiencies or security vulnerabilities (e.g., SQL injection, memory leaks). Third, provide an optimized version of the code. Finally, write a brief technical README section for this module.

**The Fully Populated Prompt:**  
Review the following code for **Node.js/Express**:

JavaScript  
app.post('/login', (req, res) \=\> {  
  const { username, password } \= req.body;  
  const user \= db.find(u \=\> u.username \=== username && u.password \=== password);  
  if (user) { res.send('Logged in'); }  
  else { res.status(401).send('Invalid'); }  
});  
First, explain what the code is currently doing. Second, identify any inefficiencies or security vulnerabilities. Third, provide an optimized version of the code. Finally, write a brief technical README section for this module.

**Full Example Output:**  
 **1\. Explanation:** This code creates an HTTP POST endpoint for logins. It extracts credentials from the request body and performs a plain-text comparison against a database array.

 **2\. Vulnerabilities:**

* **Plain Text Passwords:** This is a critical failure. Passwords should never be stored or compared in plain text.  
* **No Hashing:** If the DB is breached, all user accounts are compromised.  
* **Timing Attacks:** Simple string comparison can be exploited to guess valid usernames. 


**3\. Optimized Version:**

JavaScript  
const bcrypt \= require('bcrypt');  
app.post('/login', async (req, res) \=\> {  
  const { username, password } \= req.body;  
  const user \= await db.users.findOne({ username });  
  if (user && await bcrypt.compare(password, user.passwordHash)) {  
    res.status(200).json({ message: 'Success' });  
  } else {  
    res.status(401).json({ error: 'Unauthorized' });  
  }  
});

**4\. README:**  
**Auth Module**  
**Security Standards:** Uses `bcrypt` for salted password hashing. Implements asynchronous comparison to prevent blocking the event loop.

* **Quality Score: 9.5/10**  
* **Justification: The AI correctly prioritized the critical security failure of plain-text storage and provided a production-ready fix using industry-standard hashing. The explanation is concise enough for a senior dev to skim while remaining educational for a junior.**

# Quick reference card

## **📋 Quick Reference Card**

| Use Case | Recommended Framework | Best For... |
| :---- | :---- | :---- |
| **Business Pitch** | **CREATE** | High-stakes persuasion and "big picture" ideas. |
| **Legal/Policy** | **CoT** | Ensuring no logical steps or risks are missed. |
| **Project Planning** | **ROLE** | Organizing people, time, and constraints. |
| **Marketing Copy** | **CREATE** | Maintaining a specific brand voice and style. |
| **Tech/Code Review** | **CoT** | Deep-diving into logic and finding hidden errors. |

