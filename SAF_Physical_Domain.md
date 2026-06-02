---
layout: default
title: "Physical Domain"
parent: "SAF"
nav_order: 1
---

# Physical Context Definition Viewpoint

| Attribute | Description |
| :--- | :--- |
| **Example** | Reference model Infotainment System |

---

## 🎯 Purpose
The Physical Context Definition Viewpoint identifies the various contexts the SOI (System of Interest) is used in, along with the associated external entities sharing a physical interface with the system. For each context, the applicable environmental conditions shall be defined. 

> **Key Benefit:** The physical context helps identify the interface requirements needed to integrate a system into its environment in a given context.

---

## 📐 Applicability
The Physical Context Definition Viewpoint supports the **“Design Definition Process”** activities of the *INCOSE SYSTEMS ENGINEERING HANDBOOK 2023 [§2.3.5.5]* and contributes to the artifacts:
* "System Design Description"
* "System Interface Definition"

---

## 📊 Presentation
A block definition diagram (BDD) depicting the elements available in a specific context. At least one BDD is used per identified context featuring:

* **1x Physical System Block** – representing the system of interest.
* **1x Physical System Context Block** – representing the specific context.
* **Multiple Physical Context Elements** – such as *Physical User*, *Physical External System*, and *Physical Environment* that are present in the Physical System Context.
* **Composition Relationships** – attaching the Physical Context Elements and the Physical System to the Physical System Context block.

---

## 👥 Stakeholders & Concerns

### Target Stakeholders
* Acquirer / Customer
* IV&V Engineer
* Safety & Security Experts
* Supplier
* System Architect

### Core Concerns
* *Which are the external physical entities the system interacts with in the given context?*
* *Which are the given contexts the system is embedded and utilized in?*
* *Which interface partners does the system have?*

---

## 🏷️ Profile Model Reference
The following Stereotypes / Model Elements are used in this Viewpoint:

* `SAF_PhysicalContext`
* `SAF_PhysicalContextRole`
* `SAF_PhysicalUser`
* `SAF_PhysicalExternalSystem`
* `SAF_PhysicalSystem`
* `SAF_PhysicalEnvironment`

---

## 🔗 Related Viewpoints
* **Required Viewpoints:** *[tbd]*
* **Recommended Viewpoints:** *[tbd]*
