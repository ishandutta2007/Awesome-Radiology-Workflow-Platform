# Awesome-Radiology-Workflow-Platform

## Top Radiology Workflow Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on PACS, RIS, Radiology Reporting, AI Triage, Worklist Orchestration & Enterprise Imaging*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Radiology Workflow Platforms**. These tools manage imaging workflows from order entry and modality worklists through image storage (PACS/VNA), viewing, AI-assisted triage and detection, structured reporting, and report distribution.

**Examples** include Rad AI, Nuance PowerScribe, Intelerad, Visage Imaging, Change Healthcare Radiology, Philips IntelliSpace, Merge PACS, RamSoft PowerServer / OmegaAI, Ambra Health, Novarad, Aidoc, Viz.ai, deepc, and Caresyntax (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting PACS, zero-footprint viewers, RIS components, DICOM tooling, and research/AI pipelines — ideal for hospitals, imaging centers, researchers, and developers building transparent, interoperable, or privacy-first radiology solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Rad AI](https://www.radai.com/)**  
  AI-powered radiology reporting platform that generates draft impressions, automates follow-up recommendations, and reduces dictation workload.

- **[Nuance PowerScribe (Microsoft)](https://www.nuance.com/healthcare/diagnostics-solutions/radiology-solutions/powerscribe-one.html)**  
  Industry-leading AI-assisted speech recognition and structured reporting platform with deep PACS/EHR integration and AI marketplace.

- **[Intelerad](https://www.intelerad.com/)**  
  Enterprise imaging and workflow orchestration platform (IntelePACS, cloud VNA via Ambra, worklist management) for multi-site radiology networks.

- **[Visage Imaging](https://visageimaging.com/)**  
  High-performance enterprise viewer (Visage 7) optimized for speed, advanced visualization, and cloud/enterprise reading workflows.

- **[Change Healthcare Radiology / Optum](https://www.changehealthcare.com/)**  
  Enterprise radiology solutions covering PACS, workflow intelligence, and imaging informatics for large health systems.

- **[Philips IntelliSpace / Vue PACS](https://www.philips.com/)**  
  Comprehensive enterprise imaging suite with PACS, advanced visualization, AI orchestration, and workflow tools.

- **[Merge PACS (Merative)](https://www.merative.com/)**  
  Established PACS and enterprise imaging platform with strong workflow and viewing capabilities.

- **[RamSoft PowerServer / OmegaAI](https://www.ramsoft.com/)**  
  Cloud-native PACS, RIS, VNA, and AI-assisted workflow platform with patient engagement features.

- **[Ambra Health (Intelerad)](https://ambrahealth.com/)**  
  Cloud-based medical image management, sharing, and VNA solutions widely used for image exchange and enterprise archiving.

- **[Novarad](https://www.novarad.net/)**  
  NovaPACS and related enterprise imaging solutions focused on workflow, auditability, and multi-specialty support.

- **[Aidoc](https://www.aidoc.com/)**  
  Clinical AI operating system (aiOS) for real-time triage, detection across multiple pathologies, and care coordination inside the radiology workflow.

- **[Viz.ai](https://www.viz.ai/)**  
  AI-powered care coordination platform specializing in stroke, PE, and cardiovascular triage with strong hospital network presence.

- **[deepc](https://deepc.ai/)**  
  AI orchestration and platform layer that integrates multiple radiology AI algorithms into existing PACS/RIS workflows.

- **[Caresyntax](https://caresyntax.com/)**  
  Surgical and procedural workflow platform with imaging and data analytics components relevant to interventional radiology and hybrid environments.

## Open-Source GitHub Projects

- **[Orthanc](https://www.orthanc-server.com/)** / [GitHub](https://github.com/jodogne/Orthanc)  
  Lightweight, highly versatile open-source DICOM server and vendor-neutral archive. Core of many self-hosted PACS deployments, with extensive plugin ecosystem (DICOMweb, PostgreSQL, worklists, etc.). GPLv3.

- **[OHIF Viewer](https://ohif.org/)** / [GitHub](https://github.com/OHIF/Viewers)  
  Zero-footprint, extensible web-based DICOM viewer framework built on Cornerstone3D. Supports DICOMweb, hanging protocols, segmentation, structured reports, and custom workflow modes. Widely used in research and production.

- **[Weasis](https://nroduit.github.io/en/)** / [GitHub](https://github.com/nroduit/Weasis)  
  Powerful open-source multi-platform DICOM viewer (desktop + web) with advanced tools, PACS integration, DICOM SR/RT support, and plugin architecture. EPL/Apache licensed.

- **[dcm4che / dcm4chee Archive](https://www.dcm4che.org/)** / [GitHub](https://github.com/dcm4che)  
  Mature Java-based open-source DICOM toolkit and archive (PACS) implementation used in many enterprise and research deployments.

- **[Sirius RIS](https://github.com/opendicom/sirius-ris)**  
  Open-source Radiology Information System built with modern web technologies (Angular, Node.js, MongoDB) and integrated with OHIF/Orthanc-style stacks. MPL-2.0.

- **[KloudRIS](https://github.com/KloudMedical/KloudRIS)**  
  Open-source, multi-tenant, web-based outpatient RIS and practice management solution designed to manage the full radiology workflow from order to report.

- **[Cornerstone3D / Cornerstone.js](https://www.cornerstonejs.org/)**  
  Foundational open-source JavaScript libraries for medical image rendering, annotation, and advanced visualization used by OHIF and many custom viewers.

- **[Dicoogle](https://www.dicoogle.com/)**  
  Extensible open-source PACS archive that replaces traditional centralized databases with flexible indexing and retrieval mechanisms.

### Additional Strong Open-Source Options

- **Dockerized Orthanc + OHIF stacks** (numerous community compose files) for rapid self-hosted PACS + viewer deployment.
- **DICOM toolkits** (DCMTK, pydicom, Highdicom) for custom routing, anonymization, and AI pipeline integration.
- **Research annotation and AI pipelines** built on OHIF/Orthanc for segmentation, bounding-box labeling, and model evaluation inside clinical workflows.
- Community **AI-assisted reporting prototypes** using local LLMs + DICOM viewers for structured report generation.
- **MITK**, **3D Slicer**, and related open medical imaging platforms for advanced visualization and research.
- Secure proxy, authentication (Keycloak), and worklist gateway projects that harden Orthanc for production use.

**Frameworks for building custom systems**: Combine **Orthanc** (archive + worklists) + **OHIF** or **Weasis** (viewer) + **Sirius RIS / KloudRIS** (workflow) + **Cornerstone3D** extensions + open AI models or orchestration layers. Add Keycloak for SSO, PostgreSQL plugins for scale, and DICOMweb for modern interoperability.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Radiology systems handle protected health information and must comply with HIPAA, GDPR, local regulations, and clinical safety standards.
- Self-hosted open-source solutions require proper security hardening, high availability, DICOM conformance testing, backup strategies, and clinical validation before production use. Open-source tools are excellent for research, teleradiology pilots, and secondary archives but may need commercial support or extensive customization for primary clinical PACS/RIS deployments.

---

**Made for radiologists, imaging IT teams, PACS administrators, AI researchers, and healthcare technologists.**  
Let's make radiology workflow more open, interoperable, and efficient.
