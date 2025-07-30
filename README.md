
'''
---

# 🚀 LearnPath: Agentic AI for Personalized Course Pathways

**LearnPath** is an intelligent, agentic AI-powered learning coach built on IBM Cloud that dynamically creates, adapts, and manages personalized learning roadmaps for students and professionals. It leverages IBM’s Granite foundation models via Watsonx.ai and uses Cloudant and Cloud Functions to enable an adaptive, goal-driven educational experience.

---

## 🧠 Problem Statement

Learners often struggle to identify the right sequence of online courses that align with their interests, skill levels, and career goals. With countless options available and little personalized guidance, many waste time on irrelevant content or lose motivation due to poorly structured plans.

---

## 🎯 Solution

LearnPath acts as a virtual mentor that:
- Interacts conversationally with users to understand their interests and goals
- Assesses current skill levels and preferred learning formats
- Generates a personalized, multi-week learning roadmap
- Continuously adapts the plan based on progress, feedback, and evolving preferences

---

## 🌐 Built With

| Feature | IBM Cloud Service |
|--------|------------------|
| 🤖 AI Reasoning | [Watsonx.ai + Granite Model](https://www.ibm.com/products/watsonx-ai) |
| ☁️ Serverless Execution | [IBM Cloud Functions](https://www.ibm.com/cloud/functions) |
| 🗂️ Data Storage | [IBM Cloudant NoSQL DB](https://www.ibm.com/cloud/cloudant) |
| 🔧 Optional Backend/UI | [IBM Code Engine](https://www.ibm.com/cloud/code-engine) |

---

## ⚙️ Key Features

- 🔄 Dynamic and adaptive learning roadmaps
- 🧠 Agentic AI loop (Observe → Think → Act → Reflect)
- 🎓 Personalized to interests, time availability, and skill level
- 📚 Curated learning resources from trusted platforms
- 📈 Progress tracking and continuous plan refinement
- 🛠️ Serverless and cloud-native (Lite tier compatible)

---

## 🛠️ Installation & Deployment

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/learnpath-ai.git
cd learnpath-ai
````

### 2. Set up IBM Cloud Services

* Create an IBM Cloud account (Lite tier)
* Provision:

  * Watsonx.ai instance
  * Cloudant DB
  * Cloud Functions

### 3. Configure Environment

Create a `.env` file:

```env
WATSONX_API_KEY=your_api_key
WATSONX_PROJECT_ID=your_project_id
CLOUDANT_API_KEY=your_cloudant_key
CLOUDANT_URL=https://your-cloudant-url
```

### 4. Deploy Cloud Functions

Use IBM Cloud CLI or deploy via UI using `learnpath_function.py`

---

## 🧪 Example Prompt (Granite Model)

```plaintext
User: I want to become a UI/UX Designer, but I’m a beginner.

AI: Great! Based on your goal, here’s your personalized roadmap:
Week 1: Introduction to UI/UX – [Course links, outcomes, skill tags]
Week 2: Figma & Wireframing...
...
```

---

## 📁 Project Structure

```
learnpath-ai/
│
├── api/                    # Cloud Function handlers
├── prompts/                # Agent instructions and prompt templates
├── ui/                     # (Optional) Frontend for user interaction
├── .env                    # Environment variables
├── README.md
└── requirements.txt
```

---

## ✅ Future Scope

* Mobile app version with push-based learning updates
* Integration with LMS platforms (Moodle, Canvas)
* Career-based certification guidance
* Multi-agent collaboration (e.g., Resume Bot, Project Reviewer)

---

## 👥 End Users

* Students and self-learners seeking career-aligned learning paths
* Educators and career counselors offering personalized guidance
* Institutions needing scalable AI mentorship tools

---

## 📜 License


## 📬 Contact

**Project Lead:** Deepak Kumar Verma
**Email:** deepakkumarvermagg@gmail.com
**GitHub:** https://github.com/Deepak-droid9

```

