# Awesome-Augmented-Reality-Remote-Support

# Awesome-Augmented-Reality-Remote-Support

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on AR Visual Guidance, Remote Expert Collaboration & Frontline Assistance*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Augmented Reality Remote Support**. These tools help field technicians, service engineers, and frontline workers connect with remote experts who can see what they see, annotate their view, and guide them through complex repairs or procedures.

**Examples** include TeamViewer Frontline, PTC Vuforia Chalk, Help Lightning, SightCall, Librestream Onsight, CareAR, Scope AR, Atheer, and RealWear Cloud (the category leaders).

**Important lifecycle note**: **Microsoft Dynamics 365 Remote Assist** and **Dynamics 365 Guides** reach **end of support on December 31, 2026** . Subscriptions may be purchased or renewed until **November 1, 2025**. After that date, these products will no longer receive security updates, bug fixes, or technical support.

**Open-source emphasis**: The open-source ecosystem for AR remote support is **emerging and research-focused** rather than production-ready at enterprise scale. **RTC-MR** (WebRTC-based framework for Mixed Reality) provides a modular, scalable foundation for building custom AR remote support applications, validated in the **Health-5G pilot project** where medical specialists guided ambulance personnel in real time using MR glasses . This section documents these focused solutions honestly.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[TeamViewer Frontline](https://www.teamviewer.com/en-cis/products/frontline/)**  
  **Enterprise AR platform for frontline workers with remote assistance, vision picking, assembly, and training.** **Frontline Assist** provides instant remote assistance where experts see what workers see and guide them with live annotations . **Proven at scale**: DHL Supply Chain uses Frontline at 25 sites with 1,500 employees daily (15% productivity increase); Coca-Cola HBC expanded to 35 warehouses in 17 countries (99.99% picking accuracy); Samsung SDS increased picking speed by 30% . Supports mobile devices and smart glasses from most manufacturers, cloud or on-premises deployment .

- **[PTC Vuforia Chalk](https://www.ptc.com/en/products/vuforia/vuforia-chalk)**  
  **AR remote assistance application that connects technicians with experts.** Experts and technicians make digital annotations in a shared live view of a real environment, and these annotations are **anchored in 3D on the physical object**, making multi-step solutions easy to follow . **Henkel case study**: Implemented across 30+ factories with ~200 users, enabling remote knowledge transfer during COVID-19 travel restrictions . Supports mobile devices, tablets, desktops, and hands-free devices.

- **[Help Lightning](https://helplightning.com/)**  
  **Enterprise remote visual guidance platform with patented merged reality.** Blends two real-time video streams (agent and customer) into a collaborative work environment where the agent's hand appears in the customer's field of view for annotation and gesture guidance . **AI capabilities**: VoiceScript AI, IntelliAssist AI, ClearSight AI, SmartFolders AI, SmartTags AI, SmartGuide AI . **Veolia case study**: Each successful remote fix saves an average of **half a day of engineer time**; one engineer personally avoided three onsite trips saving a full day each . **No app download required for customers** — they join from mobile browser .

- **[SightCall VISION](https://sightcall.com/platform/)**  
  **All-in-one visual service platform with live video, AR annotations, and AI-powered insights.** **Xpert Knowledge™** automatically captures real-time visual support sessions and converts them into structured, multimedia tutorials . **Visual AI** transforms any device camera into a problem-solving tool using image recognition and real-time guidance . **Metrics**: Customers report **50% fewer truck rolls, 40% increased first-time fix rate, 69% decreased average resolution time, and 25% increased CSAT** . **Compliance**: SOC 2 Type II, GDPR, HIPAA, CCPA .

- **[Librestream Onsight](https://librestream.com/)**  
  **Secure AR collaboration platform for mission-critical environments.** **Raytheon Technologies case study**: Launched VirtualWorx powered by Onsight, achieving **30% travel cost savings**, improved mission availability, and higher first-time fix rate . Delivers secure two-way voice and video, document sharing, and training between field technicians and subject matter experts .

- **[CareAR](https://www.carear.com/)**  
  **AR platform for service and operations with measurement and annotation tools.** **AR Measurement** enables precise distance measurements in shared sessions . **Freeze Mode** freezes camera view for annotation on still images . **Session recording** captures annotations and notes for documentation . Integrates with ServiceNow, Salesforce, and other CRM systems .

- **[Scope AR WorkLink](https://www.scopear.com/)**  
  **AR work instruction and remote assistance platform.** **WorkLink Scenarios** provide 3D work instructions with AR mode, active tracking, and overlay modes for equipment in front of the worker or standalone 3D rendering . **Make A Call** feature enables licensed users to call another licensed user for remote assistance .

- **[Atheer Lens](https://play.google.com/store/apps/details?id=com.atheer.lens)**  
  **Frontline worker platform connecting remote teams.** **AR remote video assistance** with multi-party sessions, scheduling, recording, and playback . **AR-powered work instructions** created without coding . **Secure chat and group messaging** for peer and expert collaboration . Enterprise-grade security and integrations .

- **[RealWear Cloud](https://www.realwear.com/)**  
  **Assisted reality wearable solutions for industrial frontline workers.** RealWear provides hands-free, head-mounted devices that keep workers' field of view free for work while providing real-time access to information and remote expertise . Integrated with major AR remote support platforms.

## Open-Source GitHub Projects

### Mixed Reality Communication Frameworks

- **[RTC-MR (WebRTC-based framework for Mixed Reality)](https://github.com/)**  
  **Open-source WebRTC-based framework for real-time communication in Mixed Reality environments.** **Academic publication** (SoftwareX, 2024) . **Key features**: **Modular architecture** with decoupled components — connection manager and message manager handle WebRTC complexities; **node-dss signalling server** for lightweight, agile session negotiation; **scalable and flexible** — components can be adapted or extended independently; **supports integration of new communication protocols** or additional security measures without significant changes to other components . **Validated in Health-5G project**: Used in a 5G technology pilot where emergency medical personnel guided by hospital specialists using MR glasses received virtual action protocols and hand-drawn annotations aligned with real-world perceptions . **Addresses common WebRTC issues**: dynamic data channel addition, call termination, message queuing, and event handling . **Best for**: Researchers and developers building custom AR/MR remote support applications.

### Additional Strong Open-Source Options

- **MR Communication**: **RTC-MR** (WebRTC-based, modular, validated in Health-5G) .
- **RealWear Integration**: **RealWear Cloud** supports open APIs for custom AR applications .
- **Research Foundation**: The RTC-MR framework provides a foundation for building custom AR remote support without proprietary licensing.

**Frameworks for building custom systems**: **RTC-MR** provides the core WebRTC communication foundation for MR remote support with modular connection and message managers . For enterprise deployment, integrate with **RealWear** assisted reality devices  or deploy on commercial platforms with APIs (SightCall, Help Lightning). Add **WebRTC** for peer-to-peer communication and **node-dss** for signalling.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AR remote support platforms handle sensitive visual and audio data from field environments; ensure proper consent, data protection compliance, and security controls before deployment.
- **Critical lifecycle notice**: **Microsoft Dynamics 365 Remote Assist** and **Dynamics 365 Guides** reach **end of support on December 31, 2026** . Subscriptions may be purchased or renewed until **November 1, 2025**. Users should migrate to alternatives before that date.
- **Open-source reality**: The open-source ecosystem for AR remote support is **emerging and research-focused**. **RTC-MR** provides a validated foundation for MR communication in critical applications like emergency medical support , but **commercial platforms** (TeamViewer Frontline, Vuforia Chalk, Help Lightning, SightCall, Librestream Onsight) provide **enterprise-grade security, proven deployments at scale, and integrated workflows** that open-source alternatives require significant development to match. The open-source path is best suited for **research, custom application development, or organizations with strong engineering capacity** seeking to build tailored AR remote support solutions.

---

**Made for field service engineers, industrial technicians, healthcare providers, and AR application developers.**
Let's make AR remote support more open, accessible, and capable.
