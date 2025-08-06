### 🧠 AI PRD Assistant (Colab Version)
This notebook allows you to automatically generate clean, well-structured PRDs using OpenAI API.  
It includes a basic function calling example: get_user_persona_insight() to enrich your product requirements.  
Perfect for technical PMs, product owners, or AI tool builders.  

### 🔧 Features
✅ Generate PRD from a single product requirement  
✅ Inject insights using custom functions (like persona completion)  
✅ Output in markdown (great for Notion or Docs)  
✅ Modular and clean code, suitable for GitHub or LinkedIn sharing  

### 📂 File Structure (for GitHub)
ai-prd-assistant/  
├── AI_PRD_v2.ipynb             # Main Colab Notebook  
├── README.md                   # Project overview  
├── prd_health_app              # output in Markdown  
└── assets/                     # (Optional) images or demo GIFs  

### 🚀 Example Function: get_user_persona_insight()
This function enriches vague requirements by injecting a relevant user persona based on product type.  
Example Input:  
"I want to build an AI meal planner for busy professionals"  
Function Output:  
"Working professionals aged 25–40, often skipping meals due to tight schedules."  

### 🧩 Functions Used
generate_prd(requirement): main logic to call OpenAI API  
build_prompt(requirement, persona=None): builds clear prompt  
get_user_persona_insight(requirement): finds user persona  
write_to_markdown(prd_text): saves the PRD to .md  

### 💡 How to Use
Set your OPENAI_API_KEY via environment or os.environ  
Provide a single-line requirement  
Auto-call function to enrich data if needed  
Output Markdown PRD  

### ✅ Ready to generate clean PRDs in seconds!
Made for AI PMs who want to ship smarter.  
