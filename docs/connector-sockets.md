# Connector Socket & Post Specifications

This guide provides technical specifications and terminology for designing and integrating 3D-printable LEGO Technic-compatible accessory mounts.

NOTE: LEGO® is a trademark of the LEGO Group of companies, which does not sponsor,
authorize, or endorse this project or documentation. All references to LEGO®
parts or standards are used strictly for compatibility and descriptive purposes.

---

## 1. Terminology Overview

* **Cross Socket / Axle Port:** Standard LEGO Technic 4-point cross-axle hole (designed to receive standard LEGO Technic cross-axles, e.g., Part 3705)[cite: 4].
* **Round Pin Socket:** Standard LEGO Technic pin-receiving socket featuring a counterbore rim (designed to snap-fit standard friction/smooth pins)[cite: 9].
* **Double-Pin Mounting Post (Mating Component):** Dual LEGO Technic pin pair set at an $8.0\text{ mm}$ center-to-center pitch (two split-barrel friction pins)[cite: 1].

---

## 2. Engineering & Measurement Specifications

Below are nominal dimensions alongside recommended FDM 3D-printing tolerances:

### A. 4-Point Cross Axle Socket (Female)
* **Profile Geometry:** 4-armed symmetric cross (perpendicular slots intersecting at $90^\circ$).
* **Nominal Span (Outer Spline Diameter):** $4.80\text{ mm}$ across opposite arm tips[cite: 4].
* **Arm / Leg Width:** $1.80\text{ mm} - 1.90\text{ mm}$[cite: 4].
* **3D Printing Clearance:** Apply a $+0.15\text{ mm}$ to $+0.20\text{ mm}$ overall offset (target $5.00\text{ mm}$ outer spline diameter inclusive of clearance) so molded or printed cross-axles slide smoothly without binding[cite: 4].

### B. Round Pin Socket (Female)
* **Inner Hole Diameter:** $4.95\text{ mm}$ (Standard fit for a $4.80\text{ mm}$ nominal pin to account for FDM hole shrinkage)[cite: 9].
* **Counterbore / Outer Lip Diameter:** $6.15\text{ mm}$ diameter at a depth of $0.80\text{ mm}$ to accept the pin retention shoulder[cite: 9].
* **Lead-in Chamfer:** $0.30\text{ mm} - 0.50\text{ mm}$ at a $45^\circ$ angle on the inner entrance rim for smooth insertion[cite: 1, 9].
* **Wall Depth:** Requires $\sim 7.80\text{ mm}$ total depth for full internal snap-fit functionality (or internal boss rings on thinner walls).

### C. Dual-Pin Mounting Post (Male)
* **Center-to-Center Pitch:** Exactly **$8.00\text{ mm}$**[cite: 1].
* **Pin Barrel Outer Diameter:** $4.80\text{ mm} - 4.85\text{ mm}$[cite: 1].
* **Retention Bulb Tip Diameter:** $5.10\text{ mm} - 5.20\text{ mm}$ snap-fit lip[cite: 1].
* **Flex Relief Slot:** $1.00\text{ mm} - 1.20\text{ mm}$ vertical center slit passing through the pin to allow compression during snap-fit insertion[cite: 1].