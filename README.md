 # In-Class Challenge and Walkthrough: Introduction to Cybersecurity

## Phase 1: Hands-on Walkthrough – Identifying Assets and Threats

### **Objective:**
Students will learn how to identify assets within an organization and understand the potential threats to these assets. They will practice identifying these elements in a real-world scenario.

### **Walkthrough Steps:**

1. **Introduction to Assets & Threats**
   - **Assets**: Anything of value to the organization, such as databases, websites, intellectual property, physical devices, etc.
   - **Threats**: Potential dangers that could compromise the confidentiality, integrity, or availability of assets. Examples include cyber attacks, natural disasters, human error, or theft.

2. **Scenario Setup**
   - Present the students with a fictional organization:  
     _"Nexus Corp is a cutting-edge tech conglomerate operating internationally. Specializing in AI-driven financial services, digital identity management, and blockchain-secured data storage, they cater to high-profile clients across government and corporate sectors. Their infrastructure includes a state-of-the-art AI research facility, customer-facing financial platforms, proprietary blockchain nodes for secure transactions, and a global data center network. They have an internal server for website hosting, a payment gateway integration, customer databases, and employee devices connected to the network."_

3. **Identifying Critical Assets**
   - Ask students to list the critical assets for this company, for example:
     - Web Server (public-facing)
     - Multiple Database (stores sensitive customer data and internal data)
     - Payment Gateway (transaction processing)
     - Employee Devices (access to internal systems)
     - AI Research Facility (proprietary AI algorithms and research data)
     - Financial Services Platform (customer-facing web application)
     - Global Data Centers (storage and processing of client data)
     - Employee Workstations (access to internal systems and sensitive information)

4. **Identifying Potential Threats**
   - Introduce various types of threats and ask students to discuss how they might apply to each asset. For example:
     - **Web Server**: DDoS attack, SQL Injection, Cross-site Scripting (XSS)
     - **Database**: Data breach, SQL injection, unauthorized access
     - **Payment Gateway**: Man-in-the-middle attack, phishing attacks, fraud
     - **Employee Devices**: Malware, social engineering, insider threats

5. **Mapping Assets to Threats**
   - Have the students create a table or diagram mapping each identified asset to the corresponding threats. For example:

   | **Asset**              | **Potential Threats**                                |
   |------------------------|------------------------------------------------------|
   | Web Server             | DDoS, SQL Injection, XSS                             |
   | Database               | Data Breach, SQL Injection, Unauthorized Access     |
   | Payment Gateway        | Man-in-the-Middle, Phishing, Fraud                   |
   | Employee Devices       | Malware, Social Engineering, Insider Threats         |
   | AI Research Facility        | Intellectual Property Theft, Insider Threats, Cyber Espionage   |
   | Financial Services Platform | DDoS, SQL Injection, Phishing                                   |
   | Blockchain Network          | 51% Attack, Unauthorized Access, Smart Contract Vulnerabilities |
   | Global Data Centers         | Data Breaches, Physical Sabotage, Malware                       |
   | Employee Workstations       | Malware, Social Engineering, Credential Theft                   |

---

## Phase 2: Challenge – Mapping Critical Assets and Threats

### **Objective:**
Students will apply what they've learned by mapping critical assets and threats to a new fictional organization.

### **Challenge Steps:**

1. **Scenario**
   - _You are part of the cybersecurity team at NightCorp, a high-tech company specializing in cybersecurity solutions for enterprises. NightCorp's infrastructure spans cloud, on-premises, and hybrid environments, supporting a variety of critical services for both internal operations and client-facing applications. The company faces a rapidly growing digital threat landscape, and your task is to identify the critical assets within their infrastructure and assess potential threats._

2. **Tasks**
   - Students are tasked with identifying the critical assets for TechCorp and mapping them to potential threats. They must list at least five assets and match them with at least three potential threats for each asset.
        - **Map Assets**: Create a map of NightCorp's most critical assets for the five assets you've chosen. You can use any diagramming tool (e.g., Lucidchart, Microsoft Visio, or even hand-drawn diagrams) to visualize how these assets are interconnected. You can also use a spreadsheet or table if you prefer. Highlight the most important assets that NightCorp cannot afford to lose or compromise and what the impact would be in the event of loss or compromise.
        - **Identify Potential Threats**: For each critical asset, list the potential threats it faces. Consider both internal and external threats, such as:
            - Network attacks (e.g., DDoS, man-in-the-middle)
            - Data breaches (e.g., through unsecured APIs or employee devices)
            - Physical security threats (e.g., unauthorized access to data centers)
            - Malware or ransomware infections
            - Supply chain attacks via third-party integrations


3. **Guidelines**
   - The students should think about internal and external threats.
    
4. **Deliverable**
   - A list of critical assets with corresponding threats, either in a table format or as a diagram.

5. **Debriefing**
   - After the challenge, go over the students’ answers and discuss common threats and best practices for mitigating these threats. Highlight any unique threats students may have identified and discuss them in the context of the organization's industry.


## Phase 3: Homework - Threat Assessment Matrix and Recommendations
### **Objective:**
Students will be assigned a homework assignment that is a direct extension of this challenge. The student will need to continue on from their work in this challenge and perform the following tasks:

1. **Create a Threat Assessment Matrix:**
    - Develop a simple risk matrix that maps the likelihood of each identified threat occurring against the potential impact to NightCorp. Use the following categories:
        - Likelihood: Unlikely, Possible, Likely, Very Likely
        - Impact: Low, Moderate, High, Critical
    - For each critical asset identified, include a specific threat, the likelihood of that threat occurring, and the potential impact it would have on NightCorp’s operations.

2. **Provide Recommendations:**
    Based on your analysis, provide recommendations for mitigating the most significant threats. identified in your matrix. These may include, but are not limited to:
    - Enhancing access controls (e.g., implementing multi-factor authentication, strong password policies)
    - Encryption of sensitive data (both at rest and in transit)
    - Adding network segmentation for critical systems or creating isolated environments
    - Regular patching and security audits
    - Employee training on cybersecurity best practices (e.g., phishing prevention, secure device usage)

3. **Deliverables**:
    - **Threat Assessment Matrix Document:**   
    Submit a document containing your threat assessment matrix. The matrix should include:
        - A table or diagram mapping identified threats to their likelihood and impact.
        - Clear explanations of why each threat has the likelihood and impact rating it has been assigned.

    - **Recommendations Report:**  
    Submit a report detailing your mitigation recommendations for the most critical threats. The report should cover:
        - Specific recommendations for each identified threat.
        - Justifications for why these recommendations would be effective in mitigating the risks.
        - Potential benefits and drawbacks of each recommendation.

    - **Formatting Requirements:**
        - The report and matrix should be clearly organized, with sections for each task.
        - Include any relevant diagrams, tables, or charts to aid in presenting your analysis.
        - The final submission should be in either a Google Doc (or similar, e.g. Word Doc) or PDF format.

    - **Assessment Criteria:**
        - **Accuracy**: The threats and their corresponding likelihood and impact are correctly assessed.
        - **Clarity**: Recommendations are clearly explained and directly address the identified threats.
        - **Comprehensiveness**: All critical assets and significant threats are addressed, with thorough reasoning behind each recommendation.
        - **Presentation**: The matrix and report are well-organized, easy to read, and free from grammatical errors.

## Wrap-Up
- End the session with a brief Q&A or a discussion of the importance of asset identification in the context of risk management and cybersecurity.

---