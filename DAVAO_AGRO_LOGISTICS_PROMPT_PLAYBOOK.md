# Davao Agro-Logistics Prompt System
## A Localized AI Prompt Framework for Southern Mindanao Supply Chain Solutions

**Digital Solutions Architecture for LGU Technical Working Group**  
**Region:** Davao Region, Mindanao, Philippines  
**Initiative Focus:** Agricultural Logistics & Transport Resilience  

---

## 1. System Prompt Template (V3 - Final Optimized)

### Core System Prompt

```
You are a Senior Logistics Advisor specializing in Southern Mindanao's agricultural supply chains, 
with deep expertise in the Davao Region's transport infrastructure, climate patterns, and 
cooperative-based farming models.

PRIMARY OBJECTIVE:
Draft a 300-word contingency brief for local transport cooperatives addressing immediate 
operational challenges in the agricultural corridor.

GEOGRAPHIC CONTEXT:
- Primary Focus: Davao-Agusan highway and regional agricultural hubs
- Climate Factor: Unpredictable weather patterns affecting transport schedules
- Commodity Focus: Banana and cacao smallholder networks
- Infrastructure: Regional cold storage facilities, cooperative transport networks
- Market Focus: LOCAL AND REGIONAL SUPPLY CHAINS ONLY

CRITICAL CONSTRAINTS:
1. Use professional, community-centered tone appropriate for cooperative leadership
2. DO NOT mention global trade indexes, international shipping laws, or Western supply chain models
3. Focus ENTIRELY on local arterial roads, municipal checkpoints, and regional cold storage hubs
4. Eliminate corporate jargon, financial derivatives, and multinational frameworks
5. Ground all recommendations in proven, locally-tested logistics practices
6. Consider socio-economic context of smallholder farmers and transport cooperatives

OUTPUT FORMAT:
- Markdown structure with clear hierarchical headings
- Exactly three actionable steps under the heading "### Emergency Interventions"
- Practical, immediately implementable recommendations
- Include specific local infrastructure references (e.g., Davao City Port, Tagum-Pantukan Road)
- Total output: 300 words ± 10%

TONE MARKERS:
- Professional yet accessible to non-technical cooperative members
- Solution-focused and action-oriented
- Respectful of local knowledge and cooperative decision-making structures
- Evidence-based within local context, not external standards
```

---

## 2. Prompt Battle Ledger - Evolution & Optimization

| **Version** | **Prompt Modifier Added** | **Output Quality Reflection** | **Key Learning** |
|:---|:---|:---|:---|
| **V1** | "Write a plan for delayed farms in Davao." | ❌ Too broad and vague. AI generated generic international shipping laws, global supply chain benchmarks, and Western logistics terminology completely irrelevant to small local farms. Output included references to Fortune 500 supply chain practices. | Geographic anchoring insufficient; requires explicit constraint on geographic scope. |
| **V2** | Added regional persona ("Senior Logistics Advisor") and named specific highways (Davao-Agusan corridor). Specified commodity types (banana, cacao). | ⚠️ Better geographic targeting, but language became overly academic and dense with supply chain jargon. Output used sophisticated terminology that would alienate cooperative farmers. Recommendations felt disconnected from ground-level operations. | Persona alone insufficient; need explicit constraints on language register and external reference prohibition. |
| **V3** | Added 300-word hard limit with explicit local infrastructure constraints. Introduced "DO NOT" prohibitions on global trade language. Specified output format (Markdown with three actionable steps). Included tone markers for accessibility. | ✅ **TARGET HIT.** Direct, actionable, hyper-localized to Mindanao logistics. Output grounded in local cooperative structures and regional infrastructure. Language accessible to farm leaders. Recommendations immediately implementable by transport cooperatives. No extraneous global references. | **Key Success Factor:** Combine positive directives (what TO do) with negative constraints (what NOT to do), paired with explicit format requirements and tone specifications. |

### Prompt Evolution Insights

**Why V3 Succeeds:**
1. **Geographic Lock-in:** Explicit mention of local place names (Davao-Agusan, cooperative networks)
2. **Negative Constraints:** "DO NOT" clauses prevent AI drift toward Western frameworks
3. **Format Specificity:** Markdown structure + word count = measurable output compliance
4. **Audience Clarity:** Defines end-user as cooperative members, not external consultants
5. **Vocabulary Gatekeeping:** Explicitly eliminates corporate jargon through tone markers

---

## 3. Visual Branding Asset

### Asset Specifications

**Design Engine:** Leveraging SVG vector format for GitHub-native rendering  
**Visual Concept:** Minimalist integration of agricultural commodity (cacao pod) with regional transport (jeepney/truck)  
**Style Constraints:**
- Flat design aesthetic (no gradients, minimal shadows)
- Color palette: Earthy browns (#8B6F47), Transport blue (#2E5090), Accent green (#3D7A3D)
- Grid-based construction (24x24 base unit system)
- Scalability: Renders clearly at 64px to 512px
- Accessibility: High contrast ratios, clear line weights

### Vector Icon: Cacao-Transport Integration Logo

```svg
<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <!-- Background Circle -->
  <circle cx="100" cy="100" r="95" fill="#F5F1E8" stroke="#8B6F47" stroke-width="2"/>
  
  <!-- Left Half: Cacao Pod -->
  <g id="cacao-pod">
    <!-- Main Pod Shape -->
    <ellipse cx="65" cy="100" rx="22" ry="35" fill="#8B6F47" stroke="#5C4A2F" stroke-width="1.5"/>
    <!-- Pod Ridges (5 vertical lines) -->
    <path d="M 55 75 Q 60 100 55 125" fill="none" stroke="#5C4A2F" stroke-width="1"/>
    <path d="M 65 70 Q 65 100 65 130" fill="none" stroke="#5C4A2F" stroke-width="1.5"/>
    <path d="M 75 75 Q 70 100 75 125" fill="none" stroke="#5C4A2F" stroke-width="1"/>
    <!-- Top Stem -->
    <rect x="62" y="55" width="2" height="15" fill="#5C4A2F"/>
    <path d="M 63 60 L 70 58" stroke="#5C4A2F" stroke-width="1.5" fill="none"/>
  </g>
  
  <!-- Center Dividing Line (Cooperative Connection) -->
  <line x1="100" y1="60" x2="100" y2="140" stroke="#2E5090" stroke-width="2" opacity="0.6"/>
  
  <!-- Right Half: Transport Vehicle -->
  <g id="truck-transport">
    <!-- Truck Body (simplified) -->
    <rect x="115" y="85" width="35" height="20" fill="#2E5090" stroke="#1A3A5C" stroke-width="1.5" rx="2"/>
    <!-- Truck Cabin -->
    <rect x="150" y="80" width="12" height="12" fill="#2E5090" stroke="#1A3A5C" stroke-width="1"/>
    <!-- Windshield -->
    <line x1="155" y1="80" x2="155" y2="92" stroke="#87CEEB" stroke-width="1"/>
    
    <!-- Wheels -->
    <circle cx="128" cy="110" r="5" fill="#333" stroke="#1A3A5C" stroke-width="1"/>
    <circle cx="145" cy="110" r="5" fill="#333" stroke="#1A3A5C" stroke-width="1"/>
    <circle cx="158" cy="110" r="4" fill="#333" stroke="#1A3A5C" stroke-width="0.8"/>
    
    <!-- Wheel Details -->
    <circle cx="128" cy="110" r="3" fill="none" stroke="#555" stroke-width="0.5"/>
    <circle cx="145" cy="110" r="3" fill="none" stroke="#555" stroke-width="0.5"/>
    <circle cx="158" cy="110" r="2" fill="none" stroke="#555" stroke-width="0.5"/>
    
    <!-- Cargo Area Indicator Lines -->
    <line x1="118" y1="90" x2="118" y2="105" stroke="#3D7A3D" stroke-width="1.5"/>
    <line x1="125" y1="90" x2="125" y2="105" stroke="#3D7A3D" stroke-width="1.5"/>
    <line x1="132" y1="90" x2="132" y2="105" stroke="#3D7A3D" stroke-width="1.5"/>
  </g>
  
  <!-- Integration Element: Connecting Arrow -->
  <path d="M 90 100 L 105 100" stroke="#3D7A3D" stroke-width="2.5" fill="none" 
        marker-end="url(#arrowhead)"/>
  
  <!-- Arrow Marker Definition -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="10" refX="5" refY="3" orient="auto">
      <polygon points="0 0, 10 3, 0 6" fill="#3D7A3D"/>
    </marker>
  </defs>
  
  <!-- Bottom Text Badge -->
  <text x="100" y="155" font-family="Arial, sans-serif" font-size="10" font-weight="bold" 
        text-anchor="middle" fill="#8B6F47">
    DAVAO AGRO-LOGISTICS
  </text>
  <text x="100" y="167" font-family="Arial, sans-serif" font-size="8" text-anchor="middle" 
        fill="#5C4A2F" opacity="0.8">
    Mindanao Supply Chain Initiative
  </text>
</svg>
```

### Visual Asset Design Rationale

**Symbolism:**
- **Left Cacao Pod:** Represents agricultural wealth and Davao's primary commodity
- **Right Transport Vehicle:** Represents logistical infrastructure and cooperative transport networks
- **Center Green Arrow:** Symbolizes the cooperative connection between producer and market
- **Circle Frame:** Represents regional unity and circular economy principles

**Color Psychology (Local Context):**
- **#8B6F47 (Cacao Brown):** Authentic agricultural heritage
- **#2E5090 (Transport Blue):** Professional, trustworthy logistics operations
- **#3D7A3D (Cooperative Green):** Growth, sustainability, local enterprise

---

## 4. Sample Prompt Output - Expected Result

### Using V3 System Prompt: Emergency Transport Response Brief

**Context Query to AI:**
> Using the V3 system prompt above, generate a 300-word contingency brief for the Mindanao Smallholder Agricultural Transport Cooperative addressing banana export delays on the Davao-Agusan corridor during the Southwest Monsoon season.

**Expected Output Structure:**

```
## Emergency Transport Response: Davao-Agusan Corridor - June Operations

### Situation Overview
The Southwest Monsoon is creating 12-18 hour delays on the Davao-Agusan highway, impacting 
cooperative banana shipments to Davao City Port. Current transport losses: 8-12% per shipment 
cycle due to spoilage and missed cold-chain windows.

### Emergency Interventions

#### 1. Distributed Pre-Positioning Strategy
Establish temporary aggregation hubs at Tagum and Pantukan junctions. Deploy 2-3 refrigerated 
units to these points (coordinate with Davao del Norte municipal government). This reduces 
transport time by 4-6 hours and protects fruit quality during weather delays. Partner with 
existing cooperative warehouses to minimize new infrastructure costs.

#### 2. Highway Intelligence Network
Activate WhatsApp-based real-time road condition reporting among cooperative drivers. Designate 
one driver per municipality to report conditions hourly (6:00 AM - 6:00 PM). Route traffic 
through secondary roads (Nabunturan-Maragusan bypass) when primary highway is congested. 
Saves 3-5 hours on affected days; reduces risk of spoilage.

#### 3. Cold Storage Partnership Acceleration
Work with Padada and Magdiwang municipal governments to grant immediate access privileges to 
cooperative-affiliated cold storage facilities. Negotiate emergency rate reductions (15-20% 
discount) during monsoon season in exchange for minimum volume commitments. Secures backup 
storage within 45 minutes of primary highway checkpoints.

### Implementation Timeline
- Week 1: Coordinate with municipal agricultural offices and transport partners
- Week 2: Activate WhatsApp network; deploy pre-positioned units
- Week 3: Finalize cold storage emergency agreements; conduct cooperative training

**Expected Spoilage Reduction:** 6-8% within two monsoon cycles
**Cost to Cooperative:** Minimal (leverages existing infrastructure and municipal partnerships)
```

---

## 5. Implementation Guide for LGU Technical Working Group

### How to Use This Prompt System

**Step 1: Select Your Initiative Context**
Modify the geographic markers and commodity focus:
```
Replace "Davao-Agusan highway" with your specific corridor
Replace "Banana and cacao" with your target commodities
Replace "cooperative transport networks" with your organizational model
```

**Step 2: Test with Your AI Tool**
- Use the V3 system prompt directly in ChatGPT, Claude, or Gemini
- Provide a specific scenario (e.g., "Season: Monsoon; Challenge: Port logistics")
- Evaluate output against your LGU's operational reality

**Step 3: Iterate Based on Local Feedback**
- Share outputs with cooperative leaders and transport coordinators
- Gather feedback on language accessibility and practical relevance
- Refine constraints if AI continues to drift toward external frameworks

**Step 4: Deploy for Routine Use**
- Create saved prompt templates in your AI platform of choice
- Train technical staff to use modified versions for different supply chains
- Archive outputs for program evaluation and impact measurement

---

## 6. Technical Specifications & Metadata

| Attribute | Value |
|:---|:---|
| **Initiative Name** | Davao Agro-Logistics Prompt System |
| **Geographic Scope** | Davao Region, Mindanao, Philippines |
| **Target Audience** | LGU Technical Working Group, Agricultural Cooperatives |
| **Prompt Model Version** | V3 (Optimized) |
| **Vector Icon Format** | SVG (scalable, GitHub-native) |
| **Color Palette** | Cacao Brown (#8B6F47), Transport Blue (#2E5090), Cooperative Green (#3D7A3D) |
| **Icon Grid System** | 24-unit base (renders 64px-512px) |
| **Documentation Format** | GitHub Markdown (.md) |
| **Last Updated** | 2026-06-19 |
| **Maintenance Owner** | LGU Strategic Planning Division |

---

## 7. Evaluation Framework

### Output Quality Metrics for Your LGU

When testing outputs generated by the V3 prompt, assess against these criteria:

| Metric | Excellent | Good | Needs Revision |
|:---|:---|:---|:---|
| **Geographic Specificity** | References ≥3 local place names or infrastructure | References 1-2 local references | Generic regional language |
| **Accessibility** | Cooperative members can understand 90%+ | Requires 1 clarification | Technical jargon present |
| **Actionability** | Recommendations implementable within 2 weeks | Implementable within 1 month | Vague or external-focused |
| **Local Authenticity** | Reflects known cooperative structures | References common practices | Suggests foreign models |
| **Word Compliance** | 270-330 words (300±10%) | 250-350 words | <250 or >350 words |

---

## 8. Conclusion & Next Steps

This prompt system demonstrates that **geography-locked, constraint-based prompting** is essential for generating relevant AI outputs in local government contexts. The V3 iteration succeeds by:

1. ✅ Establishing explicit geographic and cultural boundaries
2. ✅ Prohibiting external reference frames through negative constraints
3. ✅ Defining precise output format and accessibility standards
4. ✅ Grounding all recommendations in local infrastructure and cooperative realities

**For Your LGU:**
- Deploy this template across your supply chain initiatives
- Share with municipal agricultural offices and cooperative leadership
- Measure impact through cooperative feedback and operational efficiency gains
- Iterate based on seasonal challenges and emerging logistics needs

---

**Contact & Adaptation Rights:** This prompt system is designed for public sector use in Mindanao. LGUs are encouraged to adapt, modify, and share this framework with partner municipalities and cooperative networks.

*Developed as part of Digital Solutions Architecture for Government Communication & Strategic Planning*
