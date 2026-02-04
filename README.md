# FOSDEM 2026 Summary and Insights

**Generated**: 2026-02-01  
**Total Talks Analyzed**: 320 (171 Saturday, 149 Sunday)  
**Total Pages**: 8,956 (4,670 Saturday, 4,286 Sunday)

---

## Executive Summary

FOSDEM 2026 featured a diverse range of talks covering cutting-edge open source technologies. The conference showed strong emphasis on AI/ML, web development, and programming languages, with significant representation across systems programming, security, networking, and infrastructure topics.

---

## Key Findings

### 1. Dominant Themes

**Top 5 Most Represented Themes:**
1. **AI & ML** (310 talks) - Nearly every talk touched on AI/ML in some capacity
2. **Web Development** (289 talks) - Strong focus on modern web technologies
3. **Programming Languages** (282 talks) - Discussions across multiple languages
4. **Databases & Storage** (226 talks) - Data persistence and management
5. **Open Source Community** (174 talks) - Community building and collaboration

### 2. Technology Stack Insights

**Most Mentioned Technologies:**
- **C/C++** (320 mentions) - Still the foundation of systems programming
- **AI/ML** (307 mentions) - Pervasive across many domains
- **Go** (267 mentions) - Strong presence in cloud-native and infrastructure
- **HTTP/HTTPS** (462 combined) - Web protocols remain central
- **Git/GitHub** (406 combined) - Version control and collaboration tools
- **Rust** (107 mentions) - Growing adoption in systems programming
- **Python** (58 mentions) - Lower than expected, possibly due to keyword matching limitations

### 3. Infrastructure & Systems

**Systems-Level Topics:**
- **Kernel & Systems** (162 talks) - Deep dives into Linux kernel and system internals
- **Virtualization** (97 talks) - QEMU, KVM, and virtualization technologies
- **Containers & Orchestration** (85 talks) - Docker, Kubernetes, and container ecosystems
- **Networking** (104 talks) - Protocols, routing, and network infrastructure

### 4. Security Landscape

**Security Topics** (113 talks):
- Security appears in ~35% of talks, showing it's a cross-cutting concern
- Topics likely include: cryptography, authentication, vulnerability management, secure coding practices

---

## Gaps and Opportunities

### Underrepresented Areas

Based on theme distribution, the following areas may have fewer dedicated talks:

1. **DevOps** (69 talks) - Lower representation despite being critical
   - **Opportunity**: More CI/CD, automation, and infrastructure-as-code content
   - **Gap**: Integration of DevOps practices with emerging technologies

2. **Containers & Orchestration** (85 talks) - Moderate representation
   - **Opportunity**: Advanced Kubernetes patterns, service mesh, and edge computing
   - **Gap**: Container security and multi-cloud orchestration

3. **Embedded & IoT** (140 talks) - Moderate but could be stronger
   - **Opportunity**: Real-time systems, edge AI, and IoT security
   - **Gap**: Integration of embedded systems with cloud infrastructure

### Emerging Trends Not Fully Captured

1. **WebAssembly (WASM)** - Mentioned in at least one talk (`fosdem26-wasm.pdf`)
   - **Gap**: Limited coverage despite growing importance
   - **Opportunity**: WASM in edge computing, serverless, and browser applications

2. **Post-Quantum Cryptography** - One talk identified (`pqc_fosde_kqchfmr.pdf`)
   - **Gap**: Critical topic with limited coverage
   - **Opportunity**: Migration strategies and implementation guidance

3. **Zero Trust Architecture** - Multiple talks identified
   - **Trend**: Growing focus on security models
   - **Opportunity**: Practical implementation guides

---

## Day-by-Day Comparison

### Saturday Highlights
- **Total Talks**: 171
- **Total Pages**: 4,670
- **Average Pages per Talk**: ~27 pages
- **Strong Themes**: AI/ML (167), Programming Languages (154), Web Development (152)

**Saturday Focus Areas:**
- Strong emphasis on development tools and languages
- Kernel and systems programming well represented
- Good balance of infrastructure and application topics

### Sunday Highlights
- **Total Talks**: 149
- **Total Pages**: 4,286
- **Average Pages per Talk**: ~29 pages
- **Strong Themes**: Similar distribution to Saturday

**Sunday Focus Areas:**
- Continuation of Saturday themes
- Slightly more focused on specific implementations
- Community and collaboration topics

---

## Notable Talk Examples

### Security & Supply Chain
1. **"Bringing Automatic Detection of Backdoors to the CI Pipeline"** (Sunday, 48 pages)
   - Focus: Automated backdoor detection in CI/CD pipelines
   - Context: Addresses recent supply chain attacks (xz-utils, PHP, etc.)
   - Keywords: Security, CI/CD, supply chain security

2. **"ROSA: Finding Backdoors with Fuzzing"** (Saturday, 42 pages)
   - Focus: Using fuzzing techniques to detect code-level backdoors
   - Approach: Graybox fuzzing with specialized oracles
   - Keywords: Security, fuzzing, backdoor detection

3. **"A day in the life of a SBOM"** (Sunday, 40 pages)
   - Focus: Software Bill of Materials lifecycle and management
   - Keywords: SBOM, supply chain, security

### Public Sector & Open Source
4. **"EU OS: learnings from 1 year advocating for a common Desktop Linux for the public sector"** (Saturday, 29 pages)
   - Focus: Migration to Linux in European public sector
   - Challenges: Windows 10 EOL, hardware obsolescence, regulatory requirements
   - Keywords: Linux, public sector, migration, sovereignty

### Enterprise & Infrastructure
5. **"Software Supply Chain Strategy at Deutsche Bahn"** (Saturday, 17 pages)
   - Focus: Managing 100,000+ OSS components across large enterprise
   - Context: Cyber Resilience Act (CRA) compliance
   - Scale: 60,000+ repositories, 40,000+ containers
   - Keywords: Supply chain, enterprise, compliance

### Confidential Computing
6. **"Standardization and Open-source Implementation of Attested TLS for Confidential Computing"** (Sunday, 27 pages)
   - Focus: Attested TLS for confidential computing environments
   - Organizations: TUDresden, GA4GH, Flashbots
   - Keywords: Security, TLS, confidential computing

### Community & Education
7. **"Bridging the Gap: Student Societies and Infrastructure Management"** (Sunday)
   - Focus: Managing infrastructure with 4-year maximum tenure
   - Challenge: Knowledge transfer in student-run organizations
   - Solution: Documentation, challenges, and structured onboarding
   - Keywords: Education, infrastructure, knowledge management

## Notable Talk Categories

### Systems & Kernel
- Linux kernel development
- eBPF and observability
- Virtualization (QEMU, KVM, virtio)
- GPU virtualization
- Hotpatching and live updates

### Networking
- IPv6 deployment
- BGP and routing protocols
- DNS and network protocols
- Network security

### Security
- Zero trust architecture
- Post-quantum cryptography
- Security best practices
- Vulnerability management

### Development Tools
- Git workflows
- CI/CD pipelines
- Code analysis and linting
- Build systems

### AI & ML
- AI integration in various domains
- Machine learning frameworks
- AI-powered development tools
- Ethical AI considerations

### Web Technologies
- Modern web frameworks
- API design
- WebRTC
- Progressive web applications

---

## Insights and Recommendations

### 1. AI/ML Integration is Pervasive
- AI/ML appears in nearly every domain, not just dedicated AI tracks
- **Insight**: AI is becoming a fundamental tool across all software domains
- **Recommendation**: Consider dedicated tracks for AI integration patterns

### 2. Systems Programming Remains Strong
- C/C++ and Rust continue to dominate systems-level work
- Kernel development and low-level optimization are well-represented
- **Insight**: Foundation technologies remain critical despite higher-level abstractions
- **Recommendation**: Continue strong support for systems programming tracks

### 3. Security is Cross-Cutting
- Security appears in ~35% of talks but may need more dedicated focus
- **Insight**: Security is recognized as important but may benefit from dedicated deep-dives
- **Recommendation**: Consider security-focused tracks or workshops

### 4. Web Development is Evolving
- Strong representation of modern web technologies
- API design and REST/GraphQL patterns well-covered
- **Insight**: Web development continues to evolve rapidly
- **Recommendation**: Track emerging web standards and frameworks

### 5. Community and Collaboration
- Open source community topics well-represented
- Git/GitHub usage shows strong collaboration focus
- **Insight**: Community building is recognized as critical
- **Recommendation**: Continue emphasis on community tracks

---

## Technical Depth Analysis

### High-Depth Topics (Based on Page Count)
Talks with 30+ pages likely represent deep technical dives:
- Kernel internals
- Complex system architectures
- Detailed implementation guides
- Comprehensive framework overviews

### Medium-Depth Topics (15-30 pages)
- Tool introductions and tutorials
- Best practices and patterns
- Case studies and experiences

### Quick Talks (<15 pages)
- Lightning talks
- Quick introductions
- Concept overviews

---

## Recommendations for Future FOSDEM Events

### 1. Emerging Technology Tracks
- **WebAssembly**: Dedicated track for WASM applications
- **Post-Quantum Cryptography**: Migration strategies and implementations
- **Edge Computing**: Integration of edge, cloud, and embedded systems

### 2. Cross-Domain Integration
- **AI + Security**: AI-powered security tools and secure AI systems
- **Embedded + Cloud**: IoT-to-cloud integration patterns
- **Systems + Web**: Low-level web performance optimization

### 3. Practical Workshops
- Hands-on sessions for complex topics
- Migration guides (e.g., post-quantum crypto)
- Best practices workshops

### 4. Community Building
- Maintain strong community tracks
- Focus on contributor onboarding
- Open source sustainability discussions

---

## Conclusion

FOSDEM 2026 demonstrated a healthy and diverse open source ecosystem with strong representation across:
- **Foundation Technologies**: Systems programming, kernel development
- **Modern Applications**: Web development, AI/ML integration
- **Infrastructure**: Cloud, containers, networking
- **Community**: Collaboration and open source culture

The conference successfully balanced deep technical content with practical applications, showing that open source continues to drive innovation across all software domains.

**Key Takeaway**: The pervasive nature of AI/ML across talks suggests it's becoming a fundamental tool, while traditional systems programming and infrastructure topics remain strong, indicating a healthy balance between innovation and foundational technologies.

---

Please respect the Licences associated with each talk.
Dumps taken from schedule page : https://fosdem.org/2026/schedule/
