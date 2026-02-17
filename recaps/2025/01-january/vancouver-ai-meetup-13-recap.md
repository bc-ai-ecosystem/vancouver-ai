# Vancouver AI Community Meetup #13 - Recap
**Date:** January 2024  
**Location:** MacMillan Space Centre, Vancouver  
**Attendees:** ~200 people  
**Milestone:** One Year Anniversary Party (13th consecutive monthly meetup)  

---

## Executive Summary

The 13th Vancouver AI Community meetup marked a pivotal one-year anniversary celebration, showcasing the community's evolution from 80 people in Kris's studio to a sophisticated ecosystem with formal sponsorships, academic partnerships, and government engagement. This milestone event featured the launch of a $3,000 data storytelling competition, comprehensive AI energy consumption research, and powerful political commentary through experimental poetry. The meetup demonstrated successful community scaling while maintaining core values of openness, creativity, and ethical technology development.

---

## Key Highlights

### 🎉 **One Year Anniversary Milestone**
- **Community Growth:** From 80 people in studio to 200+ at professional venue
- **Vision Realized:** "Big tent of AI interested people, skeptics, explorers" successfully created
- **Foundation Established:** Sustainable venue partnership enabling ongoing programming

### ⚡ **AI Energy Transparency Initiative**  
- **Lionel Ringenbach's research:** First comprehensive analysis of AI power consumption with practical measurement tools
- **Key Finding:** ChatGPT daily usage equivalent to 140-1,560 US households' annual energy consumption
- **Solution Provided:** CodeCarbon integration for precise energy monitoring

### 💰 **Corporate Partnership Evolution**
- **Formal Sponsorship Launch:** Segev Law Firm, [[Dimitri Schwartzman]] (real estate), Sons of Vancouver (distillery)
- **Andrew Reid Partnership:** $3,000 data storytelling competition launching
- **Transparent Financial Model:** $5,000 monthly budget breakdown shared publicly

### 🎭 **Political Commentary Through Art**
- **Brittany Mila's poetry:** Powerful critique of power structures and AI governance
- **Open Source Advocacy:** Kush's passionate DeepSeek defense and corporate AI criticism
- **Creative Expression:** Community providing platform for controversial and challenging perspectives

---

## Community Infrastructure Maturation

### Sponsorship Strategy & Financial Transparency

**Revenue Model Breakdown:**
- **Monthly Revenue:** ~$5,000 from ticket sales
- **Monthly Expenses:** ~$5,000 (venue $1K, food $1K, drinks $1K, performers/staff/insurance $2K)
- **Philosophy:** "When money comes into an event like this, they do it on their own terms oftentimes, and they can often suck all the air out of the room"

**Strategic Approach:**
- **Foundation Building:** Centered nonprofits, academia, artists, creatives before introducing corporate money
- **Values Protection:** Ensuring sponsors align with community values rather than dictating direction
- **Venue Partnership:** 15-month Space Center contract enabling stable sponsorship relationships

### Sponsor Integration Success

**Segev Law Firm (Marius Adomnik):**
- **Background:** 45-lawyer firm specializing in crypto, AI, gaming, Web3
- **Personal Connection:** [[Ron Segev]] 20+ year relationship with Kris (band played his 30th birthday, wrote for his 1998 online magazine)
- **Services:** Full-service legal support from incorporation to IPO
- **Commitment:** Initially 6 months, extended to year with potential for higher-level partnership

**[[Dimitri Schwartzman]] (Real Estate):**
- **Family Integration:** [[Matthew Schwartzman]] (18-year-old son) serving as sponsorships/partnerships manager
- **Industry Challenge:** "A lot of people in this business are afraid to try something different, something new"
- **Community Role:** Testing ground for real estate AI applications

**Metacreation Lab (Philippe Pasquier):**
- **Equipment Donations:** $10,000 sound system, two 55" LG screens for demo stations
- **Research Partnership:** Supporting Lionel's lab position, Canada Arts Council grants
- **Student Integration:** Kian's demos and upcoming performance collective

### Volunteer Team Recognition

**Core Team Acknowledgment:**
- **[[Kevin Friel]]:** Technical systems and video production
- **Brittany Mila:** Event organization and academic integration  
- **[[Matthew Schwartzman]]:** Sponsorships and partnerships (18-year-old managing corporate relationships)
- **Itamar:** Key volunteer coordinator
- **Multiple Contributors:** [[Jeff Clark]], Roz, Lawrence, and others

**Philosophy:** "We're all doing it kind of like off the side of our desk and the goodness of our heart... no one's making money. We're just into this cause we believe in it."

---

## Technical Innovation Showcase

### Lionel Ringenbach's AI Energy Research

**Research Origin:** Existential dread leaving AI model training unattended for 10 days during technology-free vacation.

**Problem Identification:** "Flying blind" on AI energy consumption due to corporate non-disclosure of usage data.

#### Technical Analysis Framework

**AI Hardware Categories:**
- **GPUs:** Main energy consumers (700W-1,000W for data center models)
- **TPUs:** Growing popularity, unclear energy efficiency  
- **Traditional CPUs:** Negligible power usage for AI workloads

**AI Usage Types:**
1. **Training:** Weeks/months, very power hungry (GPT-3: 10,000 x 700W GPUs)
2. **Fine-tuning:** Hours/days/weeks, moderate power usage
3. **Generation/Inference:** Seconds/minutes (daily usage), but video generation can take hours/days

#### ChatGPT Energy Calculation

**Sam Altman's December Data:**
- 300 million users
- 1 billion requests per day

**Lionel's Testing Methodology:**
- Ran multiple request types (small, medium, large) to measure response times
- **Optimistic scenario:** 2.2 seconds GPU runtime, 4 GPUs per request, 600W power
- **Result:** 1.46 watts per request (worst case: 4.4 watts)

**Daily Impact:** ChatGPT daily usage = 140-1,560 US households' annual energy consumption.

**Microwave Analogy:** Every ChatGPT response like running 4-8 microwaves for entire response duration.

#### Corporate Transparency Crisis

**Data Disclosure Gap:**
- Microsoft, OpenAI, Meta, Google, Amazon, xAI don't disclose energy usage
- Estimated 1-3 million GPUs across major players
- GPU counts sometimes disclosed (xAI: 100K → 200K this year) but energy usage hidden

**Research Contradictions:**
- International Energy Agency: Data centers 1-1.5% of electricity (AI smaller portion)
- Other estimates: AI alone 2.1-3.9% of global CO₂ emissions
- "Seriously large gap between optimistic and pessimistic" perspectives

#### Practical Solution: CodeCarbon

**Free Tool Features:**
- Precise energy monitoring for any computing task
- Integration with Hugging Face training tools
- Location-based CO₂ calculation using local energy mix
- Works on personal laptops (tested on MacBook)
- No overhead or cost for implementation

**Personal Results:** Detailed tracking of StyleGAN model training and image generation energy costs.

**Industry Gap:** Big cloud providers only provide "ballpark estimations" despite hardware manufacturers providing "milliwatt hour" precision.

### [[Kevin Friel]]'s Automated Video Production System

**Project Goal:** Reducing 4-week video editing backlog to 20-30 minutes post-event.

**Technical Architecture:**
- **6K Cinema Camera:** Blackmagic PIXA controlled via phone app
- **Live Streaming:** Direct feed to home edit station running DaVinci Resolve  
- **AI Integration:** V1 LLM handling transcoding, speaker recognition, automated markers
- **API Coordination:** Phone app → camera → DaVinci Resolve → AI editing

**Capability:** 6K master shot providing 4K medium shot, 1080p tight shots from single camera.

**Real-time Processing:** Logos, text overlays, and editing decisions happening during live event.

### AI Filmmaking & Political Commentary (Michael Tippett)

**Mr. Canada Series:** Political satire addressing Canadian civic engagement through AI-generated content.

**Educational Mission:** "People don't really follow politics in Canada... use this technology to make something entertaining that would also help educate people."

**Character Design:** Superhero figure performing "feats of strength" while engaging politicians.

**Production Evolution:** "My shit's better than the last episode... changes every day."

**Notable Achievement:** Jagmeet Singh deepfake generating significant community engagement.

---

## Academic Research Integration

### UBC Cognitive Systems Innovation (Brittany Mila)

**Course:** COGS 401 seminar class integrating AI into academic curriculum.

**Educational Philosophy:** "I don't really care if students can summarize an article... I want them to leave there with better critical thinking skills."

**Assignment Innovation:**
- Students use AI (LLM) to summarize academic articles
- Graded on prompt engineering quality
- Graded on critical evaluation of AI summary (what it did well/poorly)
- **Result:** "It worked. It did what I wanted it to. And they don't seem to hate it."

**Significance:** First documented case in community of professor proactively integrating AI into curriculum rather than fighting against student usage.

### Northeastern University Synthetic Personas Research (Mirjana Pripa)

**Research Focus:** Understanding LLM agent value in complex social virtual reality environments.

**Background:** "I got into VR because I really didn't like what I experienced in VR, and I felt we can make this better."

#### Technical Innovation Areas

**AI Moderation:** Real-time hate speech flagging for platforms lacking sufficient human moderators.

**Language Practice:** Using VR agents for English/Serbian language learning in immersive environments.

**Connection Research:** "If it feels robotic, if it feels awkward. If it doesn't move, even in random patterns, you don't connect."

#### Synthetic Personas for Sensitive Populations

**Down Syndrome Research Project:**
- Web-based interface for interacting with personas representing people with Down syndrome
- **Challenge:** LLM biases + representing marginalized community
- **Data Source:** Small data from lived experiences shared on Twitter and forums
- **Application:** UX designers gathering requirements without directly interviewing vulnerable populations

**Ethical Framework:**
1. **Ability-focused representation:** Showcasing capabilities rather than disabilities
2. **Professional validation:** Working with speech/language pathologists to identify stereotypes
3. **Community approval:** People with Down syndrome vetting representations for authenticity

**Platform Expansion:** Ready to support other sensitive population groups requiring ethical persona development.

#### LLM Personality Research

**Findings:** Extensive personality testing reveals political leanings (left/right/center) varying by temperature settings.

**Consistency Problem:** Cannot guarantee same performance with identical settings across sessions.

**Critical for Research:** Synthetic personas used as research participants require consistent behavior for valid results.

---

## Technology Philosophy Debates

### Open Source Advocacy vs. Corporate Control

**Kush's DeepSeek Defense:**
- **Timeline:** January 2025 DeepSeek release creating industry disruption
- **Criticism:** "China bad because it's China" discourse representing xenophobia rather than technical evaluation
- **Open Source Values:** "The honor, the love, the joy of sharing knowledge, of researching in open"
- **Corporate Critique:** OpenAI/US companies "holding us by the balls, not letting us in on research"

**Technical Achievement:** 100-person Chinese team releasing fully open-source model with detailed research paper.

**Community Response:** Kris acknowledging legitimacy while maintaining nuanced perspective on geopolitical concerns.

**Wanda's Counter-Perspective:** Personal experience with Chinese government (Beijing airport Rolls Royce treatment) creating caution about state involvement.

### Energy Consciousness vs. Innovation Speed

**Lionel's Research Impact:** Providing first concrete tools for measuring AI environmental impact.

**Corporate Accountability:** Major tech companies deliberately obscuring energy usage data.

**Local Alternative:** BC's "good energy mix" making local AI development more environmentally responsible.

**Community Action:** CodeCarbon integration enabling informed decision-making about AI usage.

---

## Creative Expression & Political Commentary

### Brittany Mila's Political Power Critique

**Poem Theme:** "Discernment" regarding power structures and AI governance.

**Key Lines Analysis:**
- **Brain maturity myth:** "Age 25 just happened to be the upper limit of participants in that particular study"
- **10% brain usage debunked:** "Demonstrably false... looking at the people in power, how could you be faulted for believing it?"
- **Power accountability:** "Fragile men... seeking to be called patriarchs, call me daddy, but give me all the accountability of a child"
- **AI consciousness warning:** "Robots now recreating images based on human brainwaves with near perfect accuracy"

**Political Commentary:** Direct critique of current leadership and warning about AI development in hands of "people in power."

**Call to Action:** "Be a nuisance to power for as long as you can."

### Community Memorial: Ender

**Legacy:** Black Square Labs founder who passed away in previous year.

**Contributions:** Spacesuits, space helmets, textile production, art collaborations with Kris.

**Community Response:** Memorial patches/stickers available, special recognition during anniversary event.

**Historical Connection:** Present during New Year's Eve studio alarm incident setting up first meetup.

---

## Professional Development & Training

### [[Nicole Donnelly]] AI Adoption Philosophy

**Background:** Professional snowboarder → AI adoption specialist with global training reach.

**Core Mission:** "Bringing joy to a billion people" through AI-enabled work-life balance.

**Training Experience:**
- **2015 Start:** Had to buy lunch to get people to attend AI workshops
- **Current Scale:** 10,000+ people trained across 30+ countries
- **Philosophy:** "So that you can snowboard more, work less, get more of your brain back"

#### Work-Life Balance Revolution

**80/20 Problem:** "80% of time doing work we don't really want to do, that's busy work."

**AI Solution:** Three-hour spreadsheet project reduced to 20 minutes.

**Team Implementation:** Entire team taking Fridays off through AI automation.

**Vision:** "80% of time you get to work on things you love, work in your magic. 20% is the BS."

#### Educational Impact Statistics

**University Study:** Nursing students using AI study buddy had 80% lower dropout rates.

**Age Range:** From 20-year-old university students to 75-year-old technology adopters.

**Practical Applications:** Family allergy tracking + AI recipe generation for inclusive holiday meals.

#### Business Ethics Model

**Employee Treatment Philosophy:**
- Global contractor team with generous policies
- Paid time off for law school exams and studying
- Two weeks paid Christmas break (employee tears of gratitude)
- **Principle:** "When we can do more for other people, they'll be happier and stick with us"

**Silicon Valley Resistance:** Big tech company fired Nicole's team after success, attempted to recruit trainers for higher wages - trainers declined due to lifestyle/flexibility priorities.

### Government & Economic Development Focus

**BC Economic Development Training:** Working with provincial economic developers experiencing 2-year average job span due to burnout.

**AI Solution:** Four-day work weeks while maintaining full pay through AI efficiency gains.

**Cross-Border Exchange:** Seattle-Vancouver partnerships for different regional AI development approaches.

**Allen Institute Connection:** AI House physical space becoming available for Seattle meetups.

---

## Government Relations & Funding Strategy

### BC + AI Center Consortium Development

**Coalition Leadership:**
- **[[Loki Jorgenson]] (Circle Innovation):** Government relations and SME AI adoption
- **[[Kris Krüg]]:** Creative industries focus and community organizing
- **Multiple Universities:** UBC Emerging Media Lab, SFU Metacreation Lab, Northeastern Vancouver

**Funding Target:** Federal "tens of millions of dollars" from Justin Trudeau AI investment commitments.

**Economic Focus:** "Making economic impact... through productivity that small and medium businesses in BC are capable of expressing."

**Industry Context:** BC's creative economy (11 of top 12 video game headquarters) facing AI disruption requiring proactive adaptation.

### Creative Industries Disruption Response

**Economic Reality:** "Generating special effects, explosions, and fucking laser beams is a lot easier than it used to be."

**Historical Model:** BC's current economy built through deliberate sector investment (VFS, DigiBC tax credits, Center for Digital Media) rather than organic growth.

**At-Risk Workers:** Junior designers and developers in visual effects, games, animation industries.

**Strategic Response:** "Put all our eggs in one basket and build something significant" through coordinated AI adoption.

---

## Advanced Technical Applications

### Synthetic Audiences Development

**Kris's Google Journalism Lab:** Training program exploring synthetic audience creation for media targeting.

**Practical Application:** "Million people that are like the people I want to target... run whole business plans or future models on synthetic audience."

**Research Evolution:** Nine months of development from initial concept to practical implementation understanding.

### AI-Powered Personal Development

**Bryce's Consciousness AI:** Five years of human consciousness research integrated into GPT-4 training.

**Mission:** "How do we rewrite the beliefs, deeper structures, identities that keep us doing the same stupid shit over and over again?"

**Data Integration:** Personal research textbooks and findings fed into AI system for consciousness exploration.

**Izzy Egan's HannaHR:** 10,000 hours of proprietary HR consulting data trained into subscription AI service launching during event.

### Experimental Creative Technology

**CompoVision System:** Lionel's AI robot eyes creating prompts from physical objects, generating images based on what users show it.

**Technical Challenge:** Power issues preventing demonstration, illustrating real-world complexity of experimental technology.

**Keffia Performance Collective:** Kian (SFU), Philippe, and Vijay preparing April performance after 600-person China debut.

---

## International Recognition & Partnerships

### Cross-Border AI Community Network

**Seattle Integration:** Nicole's invitation for Vancouver community to participate in Allen Institute AI House programming.

**Philosophical Exchange:** "Way that everybody thinks across the border is totally different" enabling valuable knowledge sharing.

**Training Collaboration:** BC government economic developer workshops representing international consultation model.

### Academic Publication & Research

**Patrick Penn's Research:** Continuing community study for BC Studies journal publication.

**Book Integration:** "Regenerating Learning" featuring community members and methodology.

**International Reach:** Northeastern University research connecting Vancouver community to global academic networks.

### Arts Festival Recognition

**Mu Tech Montreal:** AI Ecology Lab residency opportunity for electronic arts festival (largest in North America).

**China Performance Success:** 600-person audience at world's largest music conservatory (5,000 students) in Hangzhou.

**April 2024 Performance:** North America premiere of AI musical agents performance.

---

## Community Values Integration

### Memorial Culture

**Ender's Recognition:** Black Square Labs founder memorialized through patches/stickers, community members receiving free memorial items.

**Historical Significance:** Present during first studio meetup setup, representing community's founding spirit.

**Cultural Practice:** Grieving and honoring community members who've passed away.

### Political Engagement Philosophy

**"Big Tent" Approach:** Including "skeptics, explorers, people trying to understand what the heck is going on."

**Controversial Discussion Welcome:** Open source advocacy, corporate criticism, government skepticism all given platform.

**Values Protection:** Maintaining community direction despite corporate sponsorship integration.

### Indigenous Leadership Continuity

**Gabriel George's Absence:** Traffic preventing ceremonial opening, but Loki providing territory acknowledgment.

**Ongoing Recognition:** Musqueam, Squamish, Tsleil-Waututh territories acknowledged despite speaker absence.

**Cultural Integration:** Indigenous leadership as structural expectation rather than optional addition.

---

## Educational Innovation

### Classroom AI Integration Success

**Brittany's COGS 401 Model:**
- Explicit AI encouragement rather than prohibition
- Prompt engineering as graded skill
- Critical evaluation of AI outputs as primary learning objective
- **Student Response:** Positive reception without resistance

**Educational Philosophy Shift:** From "criminalizing children" with AI detection tools to teaching critical AI literacy.

### Hollyhock AI & Consciousness Gathering

**Orain's Leadership Retreat Integration:**
- October 2024 inaugural gathering planned
- 60 curated participants: artists, technologists, policy makers, activists
- **Mission:** "Serve collective humanity and collective growth, not perpetuate efficiency oriented, profit driven world"

**Advisor Recruitment:** Seeking "global majority" representation for scholarship allocation and cultural guidance.

**Three-Year Program:** Long-term commitment to exploring AI consciousness intersection.

---

## Open Source Technology Movement

### Kush's DeepSeek Advocacy Campaign

**Technical Achievement:** Chinese team releasing open-source model with full research methodology.

**Industry Impact:** "Changing entire landscape and sending... trillion dollar... companies" into response mode.

**Community Education:** Reading group formation for technical paper analysis.

**Philosophy:** "Building upon shoulders of others, then sharing all the stuff that you do."

### Local AI Development

**Philippe's Artist Tools:** Open source models enabling complete creator ownership of AI tools and outputs.

**Kris's Portrait Models:** Two StyleGAN models trained exclusively on personal photography, enabling full ownership of generated content.

**Community Priority:** Local model training preferred over corporate platform dependence.

---

## Future Trajectory Indicators

### Surrey AI Community Launch

**March 11, 2024 Launch:** Legion No. 9, Surrey, second Tuesday monthly 6-9pm.

**Accessibility Mission:** Serving people "changing a clutch" or living in Maple Ridge/White Rock unable to travel downtown.

**Partnership Model:** Sister organization rather than replication, maintaining connection to main community.

**Support Network:** Kevin, Victor, Michelle Diamond planning attendance for launch support.

### International Collaboration Expansion

**SF AI Salon Partnership:** Film screening collaboration ("The Thinking Game" about Google DeepMind).

**Seattle AI House:** Physical space collaboration opportunities with Allen Institute.

**Government Consulting:** Nicole's BC government workshops representing international expertise exchange.

### Technology Development Acceleration

**Automated Production Systems:** Kevin's video editing automation, Lionel's energy monitoring tools.

**Creative AI Integration:** Performance collectives, political commentary, consciousness exploration.

**Academic Validation:** University partnerships providing research credibility and student integration.

---

## Critical Success Factors

1. **Values-First Sponsorship:** Maintaining community direction while integrating corporate support
2. **Transparent Financial Operations:** Public budget disclosure building trust and sustainability
3. **Academic Integration:** University partnerships providing research credibility
4. **International Network:** Cross-border collaboration expanding influence and knowledge
5. **Youth Leadership:** 18-year-old managing corporate partnerships demonstrating generational integration
6. **Technical Innovation:** Real-world AI applications solving community production challenges
7. **Political Commentary Platform:** Safe space for controversial discussions and artistic expression
8. **Environmental Consciousness:** Energy monitoring tools enabling responsible AI development
9. **Open Source Advocacy:** Community preference for transparent, controllable technology
10. **Memorial Culture:** Honoring deceased community members while celebrating growth

---

## Memorable Quotes

**[[Kris Krüg]]:** "We are the people that self selected and come out and I appreciate you responding to the call."

**[[Nicole Donnelly]]:** "My big mission in life is bringing joy to a billion people... so that you can snowboard more, work less, get more of your brain back."

**Brittany Mila:** "Be a nuisance to power for as long as you can."

**Kush:** "Open source is the honor, the love, the joy of sharing knowledge, of researching in open."

**Lionel Ringenbach:** "We're kind of flying blind... if those big companies don't disclose the numbers, how could we actually know?"

**[[Loki Jorgenson]]:** "There is a need for us to come together... to bring all of our talents and capabilities and resources, pool them in order to do something special."

---

## Community Development Model Success

The January 2024 one-year anniversary demonstrated the Vancouver AI Community's successful evolution into a sophisticated ecosystem capable of:

### **Financial Sustainability**
- Transparent budget model enabling sponsor integration without value compromise
- Diversified support base reducing dependence on single funding sources
- Young leadership managing corporate relationships effectively

### **Technical Innovation**
- Real-world AI applications solving actual community production challenges
- Energy monitoring tools enabling responsible development choices
- Creative applications pushing artistic and political expression boundaries

### **Academic Integration**
- University partnerships providing research validation and student development
- Innovative educational approaches modeling future of AI-integrated learning
- International research collaboration expanding community influence

### **Political Engagement**
- Government consortium development for provincial AI center funding
- Cross-border partnerships and consultation opportunities
- Platform for controversial discussions and corporate accountability

### **Cultural Preservation**
- Indigenous leadership expectations maintained despite scheduling challenges
- Memorial practices honoring deceased community members
- Values-based approach to technology development and corporate partnerships

The Vancouver AI Community has successfully navigated the critical transition from grassroots gathering to institutional influence while preserving the creative, inclusive, and ethically-driven culture that enabled its initial growth. The one-year anniversary represented not just celebration, but demonstration of a sustainable model for community-driven AI development that prioritizes human values alongside technological advancement.

**Next Milestone:** February 2024 continuation of government funding development and Surrey AI launch preparation.

## 📢 Feedback Highlights

Curious what the community thought? Check out the **[Event Feedback & Sentiment Report](feedback.md)**.
