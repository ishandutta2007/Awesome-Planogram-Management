# Awesome-Planogram-Management

## Similar Projects to Planogram Management Software

**Planogram Management Software** (also called Space Planning or Shelf Planning tools) helps retailers and CPG brands design, visualize, optimize, and execute product placements on store shelves. Features typically include 2D/3D shelf layouts, product libraries with dimensions, financial analysis, compliance checking, and integration with category management and sales data. Leading commercial platforms include Blue Yonder Category Management, Nielsen Spaceman, DotActiv, Quant, RELEX Space Planning, PlanoHero, SmartDraw Planograms, Scorpion Planogram, JDA Space Planning, and Space Planning by SymphonyAI.

Below is a **curated list** of notable platforms and their open-source equivalents. Mature, production-ready open-source planogram software is currently very limited. Most open-source efforts are academic optimization packages, small prototype tools, or general-purpose diagramming solutions that can be adapted for basic shelf planning.

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Blue Yonder Category Management / Space Planning](https://blueyonder.com/)** | Enterprise retail planning suite with advanced space and category management capabilities. | Custom / Quote-based (typically starts at ~$100,000/year for enterprise modules) | No free tier; custom demo on request. |
| **[Nielsen Spaceman](https://nielseniq.com/)** | Long-standing industry-standard planogramming tool tightly integrated with Nielsen data. (now part of Trax / NielsenIQ ecosystem) | Custom / Quote-based | No free tier; custom demo on request. |
| **[DotActiv](https://www.dotactiv.com/)** | Category management and planogram software popular with retailers and CPG teams. | Paid tiers starting at ~$80/month (Lite) up to ~$400/month | **Free tier available**: Limited to 40 products on a single-drop planogram and 20 AI credits (~10 planograms/month). |
| **[Quant](https://www.quantretail.com/)** | Space planning and planogram solution focused on retail execution. | Starts at ~€1,200 per user/year (Quant Basic) | No free tier; 14 to 30-day free trial available. |
| **[RELEX Space Planning](https://www.relexsolutions.com/)** | Part of the RELEX retail planning platform, emphasizing locally optimized planograms and supply-chain integration. | Custom / Quote-based | No free tier; custom demo on request. |
| **[PlanoHero](https://planohero.com/)** | Modern planogram and shelf management platform with AI-assisted features and mobile execution tools. | Lite plan starts at $199/month; custom enterprise quotes. | No free tier; 14-day free trial available (up to 1,500 SKUs). |
| **[SmartDraw Planograms](https://www.smartdraw.com/)** | Easy-to-use diagramming tool with planogram templates and drag-and-drop shelf design. | Starts at ~$9.95/month (individual, billed annually) | No free tier; basic free trial available. |
| **[Scorpion Planogram](https://www.scorpionplanogram.com/)** | Planogram design software with 3D visualization and automation options. | Custom / Quote-based | No free tier; custom demo/trial on request. |
| **JDA Space Planning** / **Space Planning by SymphonyAI** | Enterprise space planning solutions used by large retail organizations (JDA is Blue Yonder heritage). | Custom / Quote-based | No free tier; custom demo on request. |

## 🔓 Open-Source Software

### Specialized / Research Planogram & Shelf Optimization
- **Shelf-Space-Allocation (R package)** — Academic open-source R package for retail shelf-space optimization. Supports data import, optimization algorithms, and basic planogram visualization. Developed for grocery retail research use cases.
- Small GitHub projects for planogram generation and 3D shelf visualization (e.g., community prototypes that allow designing fixtures and placing products with capacity calculations).
- Optimization scripts and knapsack-style solvers (Python/R) that allocate products to shelves based on profit, facings, and space constraints — useful building blocks rather than complete applications.

### General Open-Source Tools That Can Be Adapted
- **[LibreOffice Draw](https://www.libreoffice.org/discover/draw/)** / **Inkscape** / **[Draw.io (diagrams.net)](https://github.com/jgraph/drawio)** — Free diagramming tools that can be used to create basic 2D planograms and shelf layouts manually.
- **[FreeCAD](https://www.freecad.org/)** or **Blender** — Open-source 3D modeling tools that advanced users sometimes adapt for detailed fixture and shelf visualization.
- **[QGIS](https://qgis.org/)** — Powerful open-source GIS that can support store clustering, catchment analysis, and spatial aspects of category management (not shelf-level planograms).

### Emerging & Experimental
- Proof-of-concept systems that combine open-source components, LLMs, and cloud services to auto-generate structured planogram descriptions from merchandising rules or sales data.
- Community experiments in retail shelf optimization using computer vision or reinforcement learning (usually research-oriented).

### Reality Check & Typical Approach
There is currently **no mature, full-featured open-source alternative** that matches commercial planogram platforms in product libraries, retailer submission formats (.psa/.pln), financial analytics, multi-user collaboration, or in-store execution workflows.

Most organizations that want open-source components currently:
1. Use commercial planogram software for the core design and compliance workflow.
2. Supplement with open-source optimization scripts, data analysis (R/Python), or general diagramming tools for internal prototyping.
3. Build lightweight custom tools on top of web frameworks + canvas/WebGL for specific needs.

If you are developing or know of a promising open-source planogram project, contributions to this list are highly welcome.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to planograms, retail space planning, shelf optimization, or category management tools.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open tools in retail space planning are still emerging and need community support! 🛒

