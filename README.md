# Semiconductor-Packaging
# 📦 Packaging Evolution: From Basics to 3D Integration  

Semiconductor packaging is the **final stage of chip fabrication**, where a completed semiconductor die is enclosed in a protective package.  
This step transforms a fragile silicon die—fabricated in a cleanroom—into a **robust component** that can be integrated into real-world electronic systems and products.  

---

## 🔑 Key Functions of Semiconductor Packaging  

- 🛡 **Protection**  
  Safeguards the die against:  
  - Physical and mechanical damage  
  - Humidity and corrosion  
  - Contaminants and chemical exposure  
  - Electrostatic discharge (ESD)  

- ⚡ **Electrical Connectivity**  
  Provides reliable connections between the die and the external environment using:  
  - Leads (pins)  
  - Solder balls  
  - Lands  

- 🔩 **Mechanical Support**  
  Ensures the die is securely mounted and connected within the system.  

- 🌡 **Thermal Dissipation**  
  Conducts heat away from the die to maintain safe operating conditions.  

---
# Why semiconductor packaging needed?
<img width="1610" height="767" alt="image" src="https://github.com/user-attachments/assets/7cd0bdf1-830d-428a-bd2d-3d29fa356285" />

# 1.1 Introduction to Semiconductor Packaging and Industry Overview  

The **semiconductor manufacturing process** is broadly divided into two stages:  

- **Front-End Process**  
  - Refers to **wafer fabrication**, where transistors and active devices are created.  
  - Even this stage is often split further:  
    - **Front-End of Line (FEOL):** CMOS device formation.  
    - **Back-End of Line (BEOL):** Metal wiring layers that connect the transistors.  

- **Back-End Process**  
  - Involves **packaging** and **testing**.  
  - Packaging transforms the fabricated wafer into a usable product.  
  - Testing ensures reliability and performance.  

---

## 🧩 Packaging and Testing Flow  

The packaging and testing phase starts with **wafer testing**, followed by:  

1. **Wafer Test** – Identifying good vs. defective dies.  
2. **Packaging Process** – Encapsulating good dies into protective packages.  
3. **Package Testing** – Final quality checks before shipping.  

📊 *The figure below illustrates the relationship between the semiconductor manufacturing process and the semiconductor industry:*  
# Packaging and Testing Industry
<img width="1607" height="748" alt="image" src="https://github.com/user-attachments/assets/78d20837-5b5e-4287-accf-c1cbba8462a5" />

## 1.2 Semiconductor Industry Landscape  

The semiconductor ecosystem involves multiple types of companies, each playing a distinct role in the **design-to-product pipeline**:  

- 🖥 **Fabless Companies**  
  - Focus only on **chip design**.  
  - Do not own manufacturing facilities.  
  - Examples: **Nvidia**, **Qualcomm**, **Apple**.  

- 🏭 **Foundries**  
  - Manufacture wafers based on designs provided by fabless companies.  
  - Global leaders: **TSMC**, **GlobalFoundries**, **UMC**.  

- 📦 **OSAT (Outsourced Assembly and Test)**  
  - Specialize in **packaging and testing** semiconductor products.  
  - Major players: **ASE**, **Amkor**.  

- 🔄 **IDMs (Integrated Device Manufacturers)**  
  - Handle the **entire process**: design, wafer production, packaging, and testing.  
  - Examples include companies like **Intel** and **Samsung**.  

---

📖 **Reference**: *[SK Hynix Newsroom – Semiconductor Back-End Process, Episode 3](https://news.skhynix.com/semiconductor-back-end-process-episode-1-understanding-semiconductor-testing/)*  

## 1.2 Understanding Package Requirements and Foundational Package Types  

### 1.2.1 Package Requirements  

Selecting the right **semiconductor package** is a critical step in electronic system design.  
The choice of package directly impacts:  

- ⚡ **Performance** – Signal integrity, power delivery, and speed.  
- 💲 **Cost** – Balancing manufacturing complexity with affordability.  
- 🌡 **Thermal Management** – Ability to dissipate heat effectively.  
- 📏 **Size** – Enabling compact designs in modern electronics.  
- 🛡 **Reliability** – Ensuring long-term durability under environmental stress.  

# Product requirements
<img width="1606" height="750" alt="image" src="https://github.com/user-attachments/assets/f56248fb-7a48-41a8-aa1a-a93e1569154a" />

### 1.2.1 Package Requirements  

The criteria for **semiconductor package selection** generally fall into the following categories:  

#### 📌 Application-Specific Requirements  
- Type of die: **Logic / Memory / Power**  
- System-specific functionality needs  

#### ⚡ Electrical Requirements  
- **I/O Pin Count** – Sufficient connections for system design  
- **Signal Integrity** – Especially critical for high-speed I/Os  
- **Power Delivery** – Stable and efficient power distribution  

#### 🌡 Thermal Requirements  
- **Thermal Dissipation** – Ability to manage heat under load  
- **Operating Temperature Range** – Suitability for target environment  

#### 🔩 Mechanical & Physical Constraints  
- **Form Factor** – Footprint and height limitations within the system  
- **System Integration Needs** – Support for advanced approaches such as:  
  - **MCM (Multi-Chip Module)**  
  - **SiP (System-in-Package)**  
  - **2.5D / 3D Packaging** for tighter integration  

#### 💲 Cost Considerations  
- **Package Cost** – Direct cost of packaging  
- **Assembly Cost** – Board/system-level assembly and testing costs  

#### 🛡 Reliability & Durability  
- **Mechanical Stress** – Resistance to handling and mounting stress  
- **Thermal Cycling** – Stability under repeated heating/cooling cycles  
- **Environmental Factors** – Moisture, humidity, and other stressors  

### 1.2.2 Typical Package Structure  

A **semiconductor package** provides the critical bridge between the silicon die and the external system.  
The structure of a typical chip package includes several hierarchical layers, each serving a specific role in protection, connectivity, and integration.  

📊 *The figure below shows the structure of a typical chip package and its connection hierarchy:*  
<img width="1612" height="761" alt="image" src="https://github.com/user-attachments/assets/82257568-e3e4-42f9-a099-becbc7e72ad6" />


#### 🔍 Key Components in the Package Hierarchy  
- **Silicon Die** – The active semiconductor device fabricated in the foundry.  
- **Die Attach** – Adhesive or solder that secures the die to the package substrate.  
- **Interconnects** – Wire bonds, flip-chip bumps, or TSVs (Through-Silicon Vias) for electrical connections.  
- **Substrate** – Provides mechanical support and routes signals between die and external pins/balls.  
- **Encapsulation / Mold Compound** – Protects against mechanical and environmental damage.  
- **Leads / Balls (I/O Interface)** – External pins, solder balls, or lands that connect the package to the PCB.  

### 1.2.2 Typical Package Structure  

A typical **IC package** consists of the following elements:  

- 🧩 **Die** – The semiconductor die itself.  
- 🪛 **Carrier / Substrate** – Provides both mechanical support and electrical contact.  
- 🔗 **Die-to-Carrier Interconnections** – Bond wires or solder bumps connecting the die to the substrate.  
- 📡 **Carrier-to-Board Interconnections** – Connect the package to the PCB using pins, leads, solder balls, or lands.  
- 🛡 **Mold Compound** – Epoxy or plastic encapsulation that protects from moisture, contaminants, and physical damage.  

---

### 🛠 Mounting Technologies  

#### 1️⃣ Through-Hole Mounting  
- **TO**: Transistor Outline  
- **SIP**: Single In-line Package  
- **DIP**: Dual In-line Package  
- **PGA**: Pin Grid Array  

#### 2️⃣ Surface Mount Technology (SMT)  
- **(T)SOT**: (Thin) Small Outline Transistor  
- **(T)SOP**: (Thin) Small Outline Package  
- **SOIC**: Small Outline IC Package  
- **QFN**: Quad Flat No-leads  
- **QFP**: Quad Flat Package  
- **PBGA**: Plastic Ball Grid Array  
- **LGA**: Land Grid Array  
- **FCBGA**: Flip Chip Ball Grid Array  
- **CSP**: Chip Scale Package  

#### 3️⃣ Advanced Packages  
- **PoP**: Package on Package (Qualcomm Snapdragon, Apple A-Series, Samsung Exynos)  
- **MCM**: Multi-Chip Module (e.g., Intel Broadwell)  
- **SiP**: System-in-Package (e.g., Apple S1)  
- **CoWoS**: Chip-on-Wafer-on-Substrate (e.g., Nvidia GP100, GV100, GA100)  

---

## 1.3 Evolving Package Architectures – From Single Chip to Multi-Chip Modules  

### 1.3.1 Classification and Anatomy of Semiconductor Packages  

Semiconductor packages can be broadly grouped into two main categories:  

#### 🧩 Conventional Packages  
- The wafer is **sawed into dice first**.  
- Each die is then packaged individually.  
- Commonly used in traditional ICs such as **DIP, QFP, and BGA**.  

#### 🧩 Wafer-Level Packages (WLP)  
- A part or all of the **packaging process is performed at the wafer level** before dicing.  
- Results in smaller, thinner, and more cost-effective solutions.  
- Widely adopted in **mobile and consumer electronics** due to their compactness.  

---

📊 *Illustration Placeholder:*  
<img width="1075" height="846" alt="image" src="https://github.com/user-attachments/assets/0f1fce1b-aac6-423e-9bbb-85158e4c35bb" />

📖 **Reference**: *[SK Hynix Newsroom: Semiconductor Back-End Process Episode 3](https://news.skhynix.com/semiconductor-back-end-process-episode-3-understanding-the-different-types-of-semiconductor-packages/)*  

---

### 🔍 Key Distinction  

- **Conventional Packaging:** Package after dicing → larger form factor, mature, well-established.  
- **Wafer-Level Packaging:** Package before dicing → smaller footprint, better electrical/thermal performance, increasingly dominant in advanced applications.  

### 1.3.2 Classification by Package Medium  

📖 *Reference: SK Hynix Newsroom – Semiconductor Back-End Process, Episode 3*  

Depending on the **medium of the package**, semiconductor packages can be categorized as follows:  

---

#### 🔗 Leadframe-Based Packages  
- **DIP (Dual In-line Package):** Traditional design, wirebond connections, external leads.  
- **QFN (Quad Flat No-leads):** Compact, features exposed thermal pads for heat dissipation.  
- **Leadframe CSP & QFP:** Scaled for higher density, widely used in SMT (Surface Mount Technology).  

---

#### 🧩 Laminate-Based Packages  
- **PBGA (Plastic Ball Grid Array):** Wirebonded to laminated substrates.  
- **Flip-Chip PBGA:** Superior signal integrity and thermal performance compared to wirebond PBGA.  
- **LGA / FCCSP:** Common in modern devices requiring high density and thin profiles.  

---

#### 🚀 Advanced Substrate Packages  
- **2D:** Dies placed side-by-side on the same substrate.  
- **2.1D:** Incorporates **RDL (Redistribution Layers)** for improved routing.  
- **2.3D:** Uses **organic interposers** for better integration.  
- **2.5D:** Employs **silicon interposers** for high-speed interconnects (e.g., **CoWoS** from TSMC/Nvidia).  

---
# Anatomy of Packaging
📊 *Illustration Placeholder:*  
<img width="1892" height="905" alt="image" src="https://github.com/user-attachments/assets/459ca457-6dba-46b8-af6e-7ca801714ba1" />

## 1.4 Interposers, RDLs, and 2.5D/3D Packaging Approaches  

Advanced packaging techniques have emerged to overcome the limitations of conventional single-die packages.  
Two key enablers of this evolution are **interposers** and **redistribution layers (RDLs)**, which allow denser interconnects and heterogeneous integration.  

---

### 1.4.1 Redistribution Layers (RDL)  

**RDL (Redistribution Layer)** is a thin metal layer added on top of a die or wafer to **reroute I/O pads to new locations**.  
This enables more flexible bump layouts, which is especially important for **fan-out packages** or **wafer-level chip scale packaging (WLCSP)**.  

#### 📌 Applications  
- **FO-WLP / FO-BGA**: Fan-out wafer-level / ball grid array packaging  
- **PLP**: Panel-level packaging  
- **Multi-die integration**  
- **System-in-Package (SiP)**  

#### 🌟 Advantages  
- Allows larger bump pitch for finer pad layouts  
- Reduces overall package size and thickness  
- Enables multi-chip placement and interconnect on a single substrate  

---

### 1.4.2 Interposers  

An **interposer** is a **passive or active intermediate layer** placed between the die and the substrate.  
It provides dense routing, reliable power delivery, and efficient die-to-die communication.  

#### 🧩 Types  
- **Silicon Interposers** – High-density, widely used in 2.5D packaging  
- **Organic Interposers** – Lower cost, less dense  
- **Glass Interposers** – Promising thermal/electrical characteristics  

#### ⚙️ Functions  
- Routes signals between multiple dies (e.g., **chiplets**)  
- Provides **thermal expansion management**  
- Enables **high-bandwidth communication**  

#### 🔀 Passive vs Active Interposers  
- **Passive:** Provide only routing and vias (no logic).  
- **Active:** Can integrate **power delivery, clocking, or memory logic**.  

---

### 1.4.3 2.5D and 3D Integration  

#### ⚡ 2.5D Integration  
- Multiple dies (e.g., **CPU + HBM**) placed **side-by-side** on a **common interposer**.  
- Interposer provides interconnects instead of the substrate.  
- Popular in **HPC and AI** applications.  
- 📌 Examples: **AMD Instinct MI series**, **NVIDIA GPUs with HBM** (CoWoS).  

#### ⚡ 3D Integration  
- Dies are **stacked vertically** and connected using **Through-Silicon Vias (TSVs)**.  
- Enables ultra-high integration density.  
- Widely used in **3D NAND**, **HBM memory stacks**, and even **logic-on-logic** integration.  

---

📊 *Illustration Placeholder:*  
<img width="1602" height="770" alt="image" src="https://github.com/user-attachments/assets/5cc389fd-ea56-4e55-b1c2-c4ba9a7e9ed1" />

## 1.5 Comparative Analysis and Selecting the Right Packaging Solution  

Choosing the correct semiconductor package depends on balancing **performance, cost, thermal needs, size, and reliability**.  
The table below compares various IC package types and their **typical applications**.  

| Package Type | Mounting Style | Key Features | Typical Applications |
|--------------|----------------|---------------|-----------------------|
| **DIP (Dual In-line Package)** | Through-hole | Simple, low-cost, large footprint | Legacy ICs, prototyping, consumer electronics |
| **QFP (Quad Flat Package)** | Surface mount | Higher pin counts, thinner profile | Microcontrollers, ASICs, consumer devices |
| **QFN (Quad Flat No-leads)** | Surface mount | Compact, exposed thermal pad, good heat dissipation | RF ICs, power management, portable electronics |
| **PBGA (Plastic Ball Grid Array)** | Surface mount | High I/O density, good thermal performance | CPUs, GPUs, networking chips |
| **FCBGA (Flip-Chip BGA)** | Surface mount | High performance, excellent signal integrity | High-speed processors, FPGAs, AI accelerators |
| **CSP (Chip Scale Package)** | Surface mount | Very small, package size ≈ die size | Mobile devices, memory chips |
| **LGA (Land Grid Array)** | Surface mount | High pin density, reliable contact | Server CPUs, high-performance computing |
| **PoP (Package-on-Package)** | Stacked surface mount | Stacks logic + memory, saves board area | Smartphones, tablets (e.g., Qualcomm, Apple) |
| **SiP (System-in-Package)** | Heterogeneous integration | Combines multiple dies into one package | Wearables, IoT, compact consumer devices |
| **MCM (Multi-Chip Module)** | Substrate-based | Integrates multiple dies side by side | High-performance computing, networking |
| **2.5D Package (Silicon Interposer)** | Interposer-based | High bandwidth die-to-die interconnects | GPUs + HBM, AI accelerators |
| **3D Package (TSV Stacked)** | Vertical stacking | Ultra-dense, low latency | HBM memory stacks, 3D NAND, logic stacking |

---

# Comparison
📊 *Illustration Placeholder:*  
<img width="1366" height="823" alt="image" src="https://github.com/user-attachments/assets/82a9efef-f04f-4f4b-b64e-18cef077187b" />

Selecting the right **semiconductor packaging** depends on multiple criteria, including **performance, reliability, form factor, and cost**.  
The choice of package has a direct impact on system-level integration, thermal management, and overall product lifecycle.  

# 2 From Wafer to Package: Assembly and Manufacturing Essentials  

This section explores the **semiconductor supply chain** and provides a detailed look into a **package manufacturing unit**, often referred to as **ATMP (Assembly, Testing, Marking, and Packaging)**.  

---

## 2.1 Setting the Stage – Supply Chain and Facilities  

### 2.1.1 Semiconductor Supply Chain Overview  

The semiconductor supply chain is a **multi-step process** that transforms **raw silicon wafers** into fully functional electronic products.  
The major steps include:  

1. **Raw Materials**  
   - Silicon ingots are created from purified sand (SiO₂).  
   - These ingots are sliced into wafers.  

2. **Wafer Fabrication (Front-End)**  
   - CMOS transistor creation (FEOL).  
   - Metal wiring formation (BEOL).  

3. **Wafer Testing**  
   - Electrical tests to identify good vs defective dies before packaging.  

4. **Assembly & Packaging (ATMP)**  
   - Dies are attached to substrates/carriers.  
   - Interconnections are formed (wirebond, flip-chip, TSV, etc.).  
   - Encapsulation protects the device.  

5. **Final Testing**  
   - Ensures performance, reliability, and compliance with specifications.  

6. **System Integration**  
   - Packaged ICs are mounted on PCBs and integrated into electronic systems.  

---

### 2.1.1 Semiconductor Supply Chain Overview  

The semiconductor supply chain is a **multi-step ecosystem** that transforms raw materials into fully functional electronic systems. Each stage involves specialized companies, inputs, and outputs.  

---

#### 1️⃣ Design – Chip Design & Verification  
- **Input:** Product requirements, **EDA tools**, Foundry PDKs, IP libraries  
- **Process:** Front-end design, verification, layout generation  
- **Output:** **GDSII layout file** taped out to foundry for mask creation and wafer fabrication.  
  - Test programs are also prepared for wafer and package-level testing.  
- **Examples:** *Nvidia, AMD, MediaTek, Intel, TI, Apple, ARM*  

---

#### 2️⃣ Wafer Fabrication (Foundry)  
- **Input:** GDSII layout, silicon wafers, equipment, gases, chemicals, raw materials  
- **Process:** ICs are fabricated on wafers using **photolithography, deposition, etching, doping**  
- **Output:** Processed wafers containing patterned dies  
- **Examples:** *TSMC, Samsung, Intel, GlobalFoundries*  

---

#### 3️⃣ Packaging Assembly & Test (ATMP)  
- **Input:** Singulated dies, test programs, substrate materials (e.g., **ABF, BT resin**), solder bumps  
- **Process:** Dies are **diced, bonded, encapsulated, and tested**  
- **Output:** Packaged ICs (e.g., **BGA, QFN, FCBGA, 2.5D/3D**)  
- **Examples:** *ASE, Amkor, JCET, Shinko, Ibiden*  

---

#### 4️⃣ Board Assembly & Test  
- **Input:** Packaged ICs, test programs, ATE (Automated Test Equipment) systems  
- **Process:** Packaged ICs are mounted on boards; **board-level validation** ensures performance  
- **Output:** Qualified ICs, sorted into performance bins (binning improves profitability and yield)  
- **Examples:** *ASE, Powertech, Amkor, UTAC*  

---

#### 5️⃣ System Integration & Distribution  
- **Input:** Packaged, tested ICs; PCBs; passive components  
- **Process:** **SMT (Surface Mount Technology)** assembly, system-level integration, validation  
- **Output:** Complete electronic systems (e.g., **smartphones, servers, networking equipment**)  
- **Examples:**  
  - **OEMs (Original Equipment Manufacturer):** Apple, Cisco  
  - **ODMs (Original Design Manufacturer):** Foxconn, Pegatron  
  - **EMS (Electronics Manufacturing Services):** Flex, Jabil  

---

📊 *Illustration Placeholder:*  
# Review of Supply Chain
<img width="1615" height="761" alt="image" src="https://github.com/user-attachments/assets/2cfebcfe-d544-4cec-906f-812e025848ed" />

### 2.1.2 Introduction to a Package Manufacturing Unit (ATMP)  

The **ATMP (Assembly, Testing, Marking, and Packaging)** process forms the backbone of semiconductor back-end manufacturing.  
It ensures that individual dies are transformed into reliable, tested, and packaged ICs ready for system integration.  

---

#### 🛠 Core Activities in ATMP  
1. **Assembly** – Die preparation, attachment to substrate/carrier, and interconnect formation (wirebond, flip-chip, TSV).  
2. **Testing** – Electrical validation of the assembled device to ensure functionality and yield.  
3. **Marking** – Laser or ink-based marking for device identification, traceability, and branding.  
4. **Packaging** – Final encapsulation, finishing, and preparation for shipment.  

---

#### 🏭 Types of ATMP Facilities  
- **OSATs (Outsourced Assembly and Test):**  
  *ASE, Amkor, JCET, TATA Electronics*  
- **In-House ATMP (IDMs):**  
  *Intel, Samsung, Micron*  
- **Foundry-Linked ATMP:**  
  *TSMC, Samsung Foundry*  

---

#### 📐 Typical Layout of an ATMP Facility  

A package manufacturing unit typically consists of the following zones:  
- **Wafer Sort & Prep Area** – Incoming wafers are inspected and tested.  
- **Die Preparation & Assembly Area** – Dicing, die attach, and interconnect formation.  
- **Molding & Encapsulation Section** – Protective encapsulation of ICs.  
- **Testing & Burn-in Section** – Electrical validation under stress conditions.  
- **Marking & Final Packaging Area** – Device labeling, singulation, and tape/reel packaging.  
- **Shipping & Logistics** – Outbound quality check and distribution.  

---

📊 *Illustration Placeholder:*  
# Typical layout of an ATMP:
<img width="1646" height="527" alt="image" src="https://github.com/user-attachments/assets/a860ba2b-6455-4065-b048-46c9cdbb27a8" />

#### 📐 Typical Layout of an ATMP Facility  

A package manufacturing unit (ATMP) is typically organized into specialized zones, each handling a key stage of the process:  

---

##### 🏗 Material Preparation & Storage  
- Incoming **wafers, substrates, leadframes, mold compounds, and consumables**  
- Inspection and controlled storage to maintain material integrity  

---

##### 🧼 Processing Zone (Clean Room: ISO Class 6 & 7)  
Major activities performed in the cleanroom environment:  
- **Die Attach & Mount** – Attaching singulated dies to the carrier/substrate  
- **Wire Bonding or Flip-Chip Bonding** – Electrical interconnections between die and substrate  
- **RDL Formation** – Redistribution layers for advanced packaging needs  
- **Encapsulation / Molding** – Protective packaging to safeguard against environmental stress  

---

##### 🔬 Testing Area  
- **Electrical Tests** – Functional validation and yield monitoring  
- **Burn-in Tests** – Stress testing under elevated voltage/temperature to screen out weak dies  
- **Reliability Chamber Testing** – Long-term reliability checks (thermal cycling, humidity, etc.)  

---

##### 📦 Warehouse & Logistics  
- **Storage of packaged ICs** in controlled environments  
- Outbound logistics and shipment preparation  

---

## 2.2 Wafer Pre-Preparation – Grinding and Dicing  

The **wafer pre-preparation process** is the first step inside an **ISO Class 7 cleanroom** of an ATMP (Assembly, Testing, Marking, and Packaging) facility.  
This stage prepares fully fabricated wafers for assembly and packaging by thinning and separating the dies.  

---

### 🧩 Key Processes  

#### 1️⃣ Wafer Grinding  
- Purpose: Reduces wafer thickness to meet package form-factor requirements.  
- Performed on the wafer backside using precision grinders.  
- Ensures proper **thermal dissipation**, **mechanical stability**, and compatibility with **advanced packaging (e.g., WLCSP, 2.5D/3D ICs)**.  

#### 2️⃣ Wafer Dicing  
- Purpose: Separates the wafer into individual dies.  
- Methods include:  
  - **Blade Dicing** – Diamond-coated saw blades cut along scribe lines.  
  - **Laser Dicing** – High precision, reduces mechanical stress.  
  - **Stealth Dicing** – Laser penetrates inside the wafer, followed by stress-induced separation.  
- Outcome: Singulated dies ready for **die attach and bonding** steps.  

---

📊 *Illustration Placeholder:*  
# Inside Clean Room Area
<img width="1612" height="765" alt="image" src="https://github.com/user-attachments/assets/9166ccc8-a435-4312-82c5-919bdcec4af7" />

### 🧩 Wafer Pre-Preparation Process Flow  

Inside the **ISO Class 7 cleanroom**, wafers undergo a series of precision operations to prepare them for die attach and packaging.  

---

#### 1️⃣ Incoming Wafer Carrier  
- Wafers arrive in **protective carriers** to prevent contamination and mechanical damage before processing.  

#### 2️⃣ Wafer Inspection  
- Visual and optical inspection checks for:  
  - Surface defects  
  - Contamination  
  - Mechanical cracks or edge damage  

#### 3️⃣ Wafer Front Tape Lamination  
- A **protective tape** is laminated on the **device (front) side** of the wafer.  
- Prevents damage to the circuits during grinding and dicing.  

#### 4️⃣ Wafer Backside Grinding  
- Backside is thinned using a **rotating grinding wheel**.  
- Typical reduction: **~700 μm → ~200 μm**.  
- Benefits: improved thermal performance, flexibility, and suitability for **advanced packaging (WLCSP, 2.5D/3D ICs)**.  

#### 5️⃣ Tape Frame Mounting  
- After grinding, wafers are mounted on a **ring frame** using adhesive tape.  
- Stabilizes the wafer and keeps dies in place during dicing.  

#### 6️⃣ Two-Step Wafer Dicing  
- **6.1 Laser Grooving**  
  - Laser precisely cuts grooves along **scribe lines**.  
  - Weakens wafer structure to prepare for blade cutting.  
- **6.2 Blade Dicing**  
  - High-precision diamond blade separates the wafer into **individual dies**.  
  - Ensures accurate singulation with minimal chipping.  

---

## 2.3 Wire Bond Packaging – Die Attach to Molding  

### 2.3 Wire Bond Packaging – Detailed Process Flow  

Wire bond packaging involves multiple precision steps to transform singulated dies into fully packaged ICs.  

---

#### 1️⃣ Die Attach  
- The individual **die** is attached to a **substrate or lead frame** using epoxy.  
  - **1.1** Epoxy is dispensed in a controlled pattern to avoid voids (trade-off: pattern complexity vs processing speed).  
  - **1.2** The die is picked up by a **pick-up head**.  
  - **1.3** The die is placed on the **Die Attach Film (DAF)**.  

---

#### 2️⃣ Curing  
- The die-attached unit is subjected to a **heating process**.  
- Purpose: cures the epoxy to form a **strong and stable mechanical bond** between the die and substrate.  

---

#### 3️⃣ Wire Bonding  
- Fine **gold or aluminum wires** (15–30 μm) connect the die pads to the substrate.  
- Performed using **thermal and ultrasonic energy**.  
- Steps:  
  - **3.1** Formation of a **ball bond** using an **EFO (Electronic Flame-Off) spark**.  
  - **3.2** Ball is bonded to the **die pad** (pressure + vibration + heat).  
  - **3.3** A **wire loop** is created.  
  - **3.4** A **crescent bond** is formed on the substrate side.  

---

#### 4️⃣ Molding (Transfer Molding)  
- An **epoxy mold compound (EMC)** is injected to encapsulate the die and wires.  
- Ensures full coverage and protection against:  
  - Environmental stress (moisture, contamination)  
  - Mechanical stress  
  - Thermal cycling  

---

#### 5️⃣ Marking (Laser)  
- The **molded package surface** is marked with:  
  - Identification codes  
  - Logos  
  - Batch numbers  
- Typically done using **laser engraving**.  

---

#### 6️⃣ Singulation  
- The **molded wafer** is cut into **individual ICs**.  
- A high-precision **dicing blade** is used:  
  - Thin blades minimize chipping.  
  - Precision ensures maximum yield.  

---

📊 *Illustration Placeholder:*  
# Activities inside clean room area
<img width="1613" height="787" alt="image" src="https://github.com/user-attachments/assets/c96c43f9-3b10-434f-b80f-c79d982af80e" />

---

## 2.4 Flip Chip Assembly – Bump Formation and Underfill  

**Flip chip packaging** is an advanced assembly technique that improves **electrical performance**, **I/O density**, and **thermal efficiency** by mounting the die **face-down** on the substrate.  
Unlike wire bonding, which relies on fine wires, flip chip uses **solder bumps** to form direct interconnects between the die and the substrate.  

---

### 2.4 Flip Chip Assembly – Detailed Process Flow  

Flip chip packaging replaces wire bonds with **solder bumps**, mounting the die **face-down** on the substrate for improved electrical, thermal, and mechanical performance.  

---

#### 1️⃣ Bump Formation on Silicon (Si)  
- **1.1** Solder bumps are deposited on the die pads.  
- **1.2** Bumps are **reflowed** to create strong electrical and mechanical connections.  

---

#### 2️⃣ Chip Flip and Placement  
- **2.1** The die is flipped **upside down** (active side facing substrate).  
- **2.2** Solder bumps are aligned with the substrate bond pads.  
- **2.3** Flux is dispensed on the substrate to aid solder wetting and bonding.  

---

#### 3️⃣ Solder Reflow  
- The die-substrate assembly is **heated** so solder bumps melt and form reliable interconnects.  

---

#### 4️⃣ Flux Cleansing  
- Residual flux is removed using **solvent spray**.  
- Prevents **corrosion** and ensures package reliability.  

---

#### 5️⃣ Underfill Process  
- **Underfill Dispensing:** Epoxy underfill is applied between die and substrate.  
- **Underfill Cure:** Heat treatment cures the material, improving:  
  - Mechanical strength  
  - Thermal conductivity  
  - Resistance to stress during thermal cycling  

---

#### 6️⃣ Molding  
- A **protective mold compound** encapsulates the package.  
- Provides resistance to moisture, mechanical shock, and contaminants.  

---

#### 7️⃣ Marking  
- **Laser marking** adds:  
  - Part number  
  - Lot number  
  - Batch code  
  - Date of manufacture  
- Ensures traceability in supply chain.  

---

#### 8️⃣ Ball Mounting and Final Reflow  
- **Solder balls** are mounted on the underside of the substrate.  
- Final **reflow** ensures firm attachment of balls → ready for **PCB mounting**.  

---

📊 *Illustration Placeholder:*  
# Activities in clean room area
<img width="1613" height="778" alt="image" src="https://github.com/user-attachments/assets/467b4114-42c2-476f-85f5-fac65dfe2bd4" />

---

## 2.5 Wafer-Level Packaging (WLP) and Conclusion  

**Wafer-Level Packaging (WLP)** is a technique where the entire packaging process is completed **at the wafer level before dicing**.  
This approach offers:  
- 📏 Smaller package size  
- 💲 Lower cost  
- ⚡ Improved electrical performance due to shorter interconnects  

---

### 🧩 Types of WLP  

#### 1️⃣ Fan-in WLP (FI-WLP)  
- I/O pads are **redistributed within the die area**.  
- Solder bumps are confined inside the footprint of the die.  
- Suitable for low to medium I/O count devices.  
- Commonly used in **mobile and consumer electronics**.  

#### 2️⃣ Fan-out WLP (FO-WLP)  
- Uses **RDLs (Redistribution Layers)** to extend I/O pads **beyond the die area**.  
- Enables **higher I/O density** without increasing die size.  
- Supports heterogeneous integration (multi-die, SiP).  
- Widely adopted in **high-performance, compact devices**.  

---

### 🔄 FO-WLP Process Flow  

1. **Wafer Reconstitution** – Known Good Dies (KGD) are placed on a carrier.  
2. **Encapsulation** – The dies are molded into an epoxy panel.  
3. **RDL Formation** – Redistribution layers reroute I/O pads to new bump locations.  
4. **Bump Formation** – Solder bumps are formed at redistributed pads.  
5. **Singulation** – The reconstituted wafer is diced into individual WLP packages.  

---

📊 *Illustration Placeholder:*  
# Activities inside clean room area
<img width="1617" height="785" alt="image" src="https://github.com/user-attachments/assets/7079a545-661f-41d3-b096-05fd7632a9cc" />

### 2.5.1 FO-WLP Process Flow  

Fan-Out Wafer-Level Packaging (FO-WLP) extends the die footprint using **Redistribution Layers (RDLs)**, enabling higher I/O density and advanced system integration.  

---

#### 1️⃣ Reconstitution Process  
- **1.1** Diced wafer is taken.  
- **1.2** Only **known-good dies (KGDs)** are selected and placed onto a temporary carrier.  
- **1.3** Dies are **molded into epoxy** to form a single **reconstituted wafer**, after which the carrier is released.  

---

#### 2️⃣ RDL (Redistribution Layer) Preparation  
- **2.1** Deposition of **dielectric and metal layers** on the reconstituted wafer.  
- **2.2** Multiple RDL layers are patterned, similar to **BEOL metallization** in CMOS fabrication.  
- Function: redistributes I/O pads to match new solder bump layouts.  

---

#### 3️⃣ Solder Ball Attach  
- Solder balls are mounted onto the final RDL pads.  
- Provides surface-mount connectivity for PCB integration.  

---

#### 4️⃣ Final Laser Marking & Singulation  
- Each packaged die is **laser-marked** with part numbers, lot codes, and date codes for traceability.  
- The reconstituted wafer is **diced (singulated)** into individual FO-WLP packages.  

---

# 3 Labs: Thermal Simulation of Semiconductor Packages with ANSYS Tools  

## 3.1 Introduction and Getting Started with ANSYS Electronics Desktop  

**ANSYS Electronics Desktop (AEDT)** is a powerful **multi-physics simulation environment** that integrates:  

- 📡 **Electromagnetic (EM) Simulation**  
- ⚡ **Signal and Power Integrity Analysis**  
- 🌡 **Thermal Simulation**  
- 🛠 **Electro-Mechanical Simulation**  

All of these are combined into a **single, unified platform**, making AEDT one of the most widely used tools for:  
- Designing high-speed electronic circuits and systems  
- Analyzing package performance under electrical, thermal, and mechanical stresses  
- Optimizing IC packaging for **reliability, performance, and thermal efficiency**  

---

## 3.2 Setting Up a Flip-Chip BGA Package  

In this lab exercise, we will use an existing **Flip-Chip Ball Grid Array (FC-BGA) package** available within the **ANSYS Icepak Toolkit** for thermal simulation.  

---

### 🛠 Step-by-Step Instructions  

#### Step 1: Launch Icepak in AEDT  
1. Open **ANSYS Electronics Desktop (AEDT)**.  
2. From the project launcher, select **Icepak** as the active tool.  
3. Create a **new project** and save it to your working directory.  

---

📊 *Illustration Placeholder:*  
<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/9456dd2c-d222-4745-a214-1cd26afb9f63" />


#### Step 2: Import the Flip-Chip BGA Package  

We will use a pre-defined **Flip-Chip BGA (FC-BGA) package** model available in the Icepak Toolkit.  

---

##### Step 2.1: Create a Flip-Chip BGA Package  
1. In AEDT, go to the **Icepak** interface.  
2. Navigate to:  
   **Toolkit → Geometry → Packages → Flipchip_BGA**  
3. Select the **Flipchip_BGA** option.  
4. Enter the package parameters (default values can be used for this exercise).  
5. Confirm and generate the package geometry.  

---

📊 *Illustration Placeholder:*  
<img width="1917" height="1028" alt="image" src="https://github.com/user-attachments/assets/1a600893-c49c-4701-9627-356d7f76a7ee" />

##### Step 2.2: Configure the Package  

1. Once you select **Flipchip_BGA** in the toolkit, the **Package Configuration** window will open.  
2. In this window, you can set the dimensions and properties for:  
   - **Package** (overall size and height)  
   - **Substrate** (layers, thickness, material)  
   - **Die** (dimensions, power dissipation settings)  
   - **Die Underfill** (material and thickness for thermal stability)  
   - **Solder Balls** (count, pitch, diameter, material)  
3. Review the configuration values.  
   - For this exercise, you may use **default values** or enter custom parameters based on the lab sheet.  
4. Once configuration is complete, click **OK** to generate the **Flip-Chip BGA package model** in the 3D workspace.  

---

📊 *Illustration Placeholder:*  
## Package Configuration 
<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/9cf583ad-1774-43f7-bee7-582b2f6f9d59" />
<img width="1911" height="1027" alt="image" src="https://github.com/user-attachments/assets/c498aad5-ff2f-45c6-b18c-d560836a4835" />
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/8e70a8ba-7661-4581-b6c1-637fcd3895cf" />
<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/7772f281-e1fe-4956-8d06-873b72899c3d" />

# Package generated in Icepak
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/bcfc530c-6e36-46fc-b692-64a35653b390" />

###### Step 3 : Exploring the 3D Package Model Structure in Icepak
#### Substrate
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/985ac4a9-fb6a-4af1-878c-77ee555a1ea2" />
</br>
#### Die Underfill
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/33ac7e97-f2d3-4db9-b78e-7743467f5d20" />
#### Via
<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/76587d45-54be-41a6-b108-96df254201b7" />
#### Die
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/2c3b7c74-9543-41b1-b8a1-3d54d646d2f6" />

## 3.3 Material Definitions and Thermal Power Sources  

### Step 4: Material Definitions  

In this step, you will **review and modify the material definitions** for the different components of the package model.  
By default, Icepak assigns generic material properties, but for accurate simulation, these should be verified and updated.  

---

### 🧩 Typical Material Assignments  

| Component        | Material        | Thermal Conductivity (W/m·K) | Density (kg/m³) | Specific Heat (J/kg·K) |
|------------------|-----------------|------------------------------|-----------------|-------------------------|
| **Die**          | Silicon (Si)    | ~150                         | 2330            | 700                     |
| **Substrate**    | BT Resin / ABF  | ~0.3 – 0.4                   | 1900            | 1200                    |
| **Underfill**    | Epoxy Resin     | ~0.3 – 0.5                   | 1200            | 1000                    |
| **Solder Bumps** | SAC305 Alloy    | ~58                          | 7400            | 220                     |
| **Solder Balls** | SAC305 Alloy    | ~58                          | 7400            | 220                     |
| **Mold Compound**| Epoxy (EMC)     | ~0.5 – 1.0                   | 1900            | 1000                    |
| **Copper Traces**| Copper (Cu)     | ~400                         | 8960            | 385                     |

---

### 🔍 Instructions in Icepak  

1. In the **Project Manager**, expand the **Model Tree** and select each component (die, substrate, bumps, etc.).  
2. Open **Properties → Material Assignment**.  
3. Review the default material and replace it with the correct one from the **Icepak Material Library**.  
4. If needed, create **Custom Materials** by entering the thermal conductivity, density, and specific heat values.  

---

📊 *Illustration Placeholder:*  
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/1669d2d5-8bbc-4f02-922c-67597e7f5fb9" />

### Step 5.1: Add / Assign Source Thermal Model for the Die  

1. In the **Project Manager** sub-window, expand the **Thermal** section.  
2. Locate **BGA1_die_source** under the sources list.  
3. Double-click or right-click → **Properties** to open the configuration window.  
4. Define the **thermal condition** for the die. Example settings may include:  
   - **Power Dissipation:** e.g., `5 W` (adjust as per exercise)  
   - **Heat Source Type:** Uniform (applied evenly across die area)  
   - **Die Temperature Monitoring:** Enabled for simulation output tracking  

---

📊 *Illustration Placeholder:*  
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/b6ef0daf-f63c-4b4f-8cc3-3a154932654a" />

### Step 5.2: Add / Assign Source Thermal Model for the Substrate  

To simulate realistic thermal conditions, a **fixed ambient temperature** boundary is applied to the substrate.  

---

#### 🛠 Instructions  
1. In the **Project Manager**, expand the tree:  
   `Models → Flipchip_BGA1_Group → Solids`  
2. Right-click on **Flipchip_BGA1_substrate**.  
3. Select **Assign Thermal Source**.  
4. In the configuration window:  
   - **Source Type:** Fixed Temperature  
   - **Temperature:** Ambient (e.g., `25°C`)  

---

✅ This ensures the substrate acts as a **heat spreader to the environment**, maintaining system stability during thermal simulation.  

📊 *Illustration Placeholder:*  
#### Add Source Thermal Model for Substrate
<img width="1913" height="1030" alt="image" src="https://github.com/user-attachments/assets/3bc84483-c537-4882-81eb-fdf915aa031f" />
#### Boundary condition on thermal
<img width="1916" height="1032" alt="image" src="https://github.com/user-attachments/assets/389c695f-7baa-4694-9376-663c3bef361c" />
#### Remove Boundary Source so that we dont have multiple boundary conditions
<img width="1915" height="1027" alt="image" src="https://github.com/user-attachments/assets/0fefd986-86e8-4015-864c-dc7b286950ea" />

## Step 6: Add Thermal Monitors for Package Components  

Thermal monitors allow you to **track temperature distribution** at key components during the simulation.  
They provide real-time data such as **junction temperature (Tj)** and substrate temperatures, which are critical for thermal analysis.  

---

### 🛠 Instructions  

1. In the **Project Manager**, expand the tree:  
   `Models → Flipchip_BGA1_Group → Solids`  

2. Right-click on **Flipchip_BGA1_substrate**.  
   - Choose **Assign Monitor → Point...**  
   - In the sub-window, select **Temperature** as the monitor type.  

3. Repeat the same steps for:  
   - **Die** → to monitor junction temperature.  
   - **Die Underfill** → to observe thermal stress and heat dissipation effectiveness.  

---

### ✅ Notes  
- Monitors should be placed at **critical heat paths** (die, underfill, substrate) to capture accurate results.  
- Multiple monitors can be used to compare **temperature gradients** across layers.  

---

📊 *Illustration Placeholder:*  
#### Monitors
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/d42a458b-507d-4daf-9db8-1a8931e88606" />
#### On the substrate
<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/d9e411db-5f65-4a74-9988-eb5d489bea1c" />
#### Adding Point Monitor: Temperature
<img width="1917" height="1032" alt="image" src="https://github.com/user-attachments/assets/feb8f324-2ab2-410e-bca5-68a52dc22ba8" />
#### Assigning the monitor on the die
<img width="1918" height="1028" alt="image" src="https://github.com/user-attachments/assets/7fb2a8f7-4057-4535-8477-bee7fd5871ef" />
#### Also assign monitor for the underfill
<img width="547" height="468" alt="image" src="https://github.com/user-attachments/assets/b39d95f0-578a-49fc-a213-b5e03ddf5a7f" />
<img width="1916" height="1028" alt="image" src="https://github.com/user-attachments/assets/ff4312b3-ce90-460b-95e3-76dc3bc88c14" />

## 3.4 Meshing and Running the Thermal Analysis  

Meshing is the process of dividing the geometry into smaller computational cells for simulation.  
The accuracy and stability of the thermal analysis strongly depend on mesh quality.  

---

### Step 7.1: Generate Mesh  

1. Go to the **Simulation** tab.  
2. Click on **Generate Mesh**.  
3. If prompted, **save the project** before proceeding.  
4. Wait for mesh generation to complete.  
5. Review the console/log window for any **errors or warnings**:  
   - If warnings are minor (e.g., small element size mismatch), note them.  
   - If errors occur, debug by refining geometry or adjusting mesh settings.  

---

### Step 7.2: Review Mesh Quality Metrics  

Once the mesh is generated, review its quality to ensure it is suitable for accurate simulation.  
Key metrics include:  

- **Face Alignment** – Ensures cell faces align properly with geometry boundaries.  
- **Skewness** – Measures deviation of cells from the ideal shape (lower skewness = better quality).  
- **Volume** – Checks for distorted or very small cell volumes that may cause solver instabilities.  

✅ Mesh should have:  
- Low skewness (preferably < 0.85).  
- No negative volumes.  
- Well-aligned faces in critical heat transfer paths (die, bumps, underfill, substrate).  

---

📊 *Illustration Placeholder:*  
#### Mesh Generation
<img width="1917" height="1028" alt="image" src="https://github.com/user-attachments/assets/c9a3f872-8b11-4aaa-88fd-d277bd9b3e2e" />
#### Properties of Mesh
##### Mesh Quality - Face Alignment
<img width="501" height="663" alt="image" src="https://github.com/user-attachments/assets/8cef8231-02b1-4249-8e2b-163b7aa79a24" />
##### Mesh Quality - Skewness
<img width="501" height="662" alt="image" src="https://github.com/user-attachments/assets/9d71f669-1048-4a2b-ba2b-c8cc7da22699" />
##### Mesh Quality - Volume
<img width="498" height="662" alt="image" src="https://github.com/user-attachments/assets/13b78f05-ddd1-4be2-b97f-a2d15301fad8" />

### Step 8: Add Thermal Analysis  

With the geometry, materials, sources, and mesh prepared, the next step is to set up the **thermal solver**.  

---

#### 🛠 Instructions  
1. In the **Project Manager**, right-click on **Analysis**.  
2. Select **Add Analysis Setup**.  
3. The solver configuration window will open.  
4. For this exercise, use the **default solver settings**:  
   - Analysis type: **Steady-State Thermal**  
   - Convergence criteria: Default values  
   - Iteration settings: Default values  
5. Click **OK** to finalize the analysis setup.  

---

✅ Notes:  
- Advanced users may modify solver controls (e.g., convergence tolerances, iteration limits, solver type), but for this lab we will keep defaults.  
- Ensure the project is **saved** before running the simulation.  

---

📊 *Illustration Placeholder:*  
<img width="770" height="697" alt="image" src="https://github.com/user-attachments/assets/f74ff6dd-6e43-401f-a018-31c1b45f24eb" />

## 3.5 Viewing Results and Exploring Other Package Types  

Before running the solver, it is important to **validate the simulation setup** to ensure all definitions, boundary conditions, and monitors are properly assigned.  

---

### Step 9: Validate the Simulation Setup  

1. In the **top ribbon toolbar**, click on the **Validate** button.  
2. Icepak will check for:  
   - Missing material assignments  
   - Unassigned thermal sources  
   - Boundary condition inconsistencies  
   - Monitor setup errors  
   - Mesh validity  
3. Review the validation results in the message window.  
   - ✅ If all checks pass → proceed to solver run.  
   - ⚠️ If warnings appear → note them, but simulation can often continue.  
   - ❌ If errors are flagged → return to earlier steps to fix issues.  

---

📊 *Illustration Placeholder:*  
<img width="555" height="332" alt="image" src="https://github.com/user-attachments/assets/dab2a29e-1828-488d-af1d-89ad9845488d" />

### Step 10: Run the Simulation and Plot the Temperature Map  

With validation complete, you can now run the thermal analysis and view the results.  

---

#### 🛠 Instructions  

1. In the **top ribbon toolbar**, click on **Analyze All**.  
2. Wait for the simulation to complete.  
   - ✅ Successful run → proceed to visualization.  
   - ⚠️ Warnings → review but often ignorable.  
   - ❌ Errors → return to setup and correct issues.  

---
#### Assigning Mesh Seperately for Underfill
<img width="827" height="255" alt="image" src="https://github.com/user-attachments/assets/d53085f4-b881-4f2b-81c9-b42e7e1e9999" />
<img width="1917" height="1027" alt="image" src="https://github.com/user-attachments/assets/5978ac61-aa18-4a33-abe1-c647932a85b4" />
<img width="1917" height="1028" alt="image" src="https://github.com/user-attachments/assets/d184ecfb-0ee2-4b57-94f8-cd59f2b1fec3" />
<img width="1913" height="1027" alt="image" src="https://github.com/user-attachments/assets/0660266c-8765-4fdf-bd6c-47d2d7a14406" />
#### After adding to a particular region the mesh
<img width="1916" height="1027" alt="image" src="https://github.com/user-attachments/assets/4c910e47-437b-4e9c-aefc-895fd2fda0b9" />

1. Then again Generate Mesh
2. Then again Validate
<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/fb873916-5681-460f-9c8c-68a43e86461c" />
3. Then analyze again to do the calculation


#### 📊 Plotting the Temperature Map  

1. In the 3D view, select the entire **Flip-Chip BGA package** by drawing a rectangle with the left mouse button.  
2. Right-click and navigate to:  
   **Plot Fields → Temperature → Temperature**  
3. Configure the plot options:  
   - **Name & Folder:** Enter descriptive labels for saving plots.  
   - **Plot on Surface Only:** Enabled (for surface heat maps).  
   - **Surface Smoothing:** Enable **Gaussian Smoothing** for cleaner visuals.  
4. Apply settings → the **temperature distribution map** will be displayed across the package.  

---

✅ This visualization helps identify:  
- **Hotspots** on the die or solder joints  
- **Thermal gradients** across the substrate  
- **Heat flow paths** in the package  

---

📊 *Illustration Placeholder:*  
##### Plot Fields
<img width="1916" height="935" alt="image" src="https://github.com/user-attachments/assets/71b86857-71b0-4769-84e5-158fe882988c" />
##### Field Plot Settings
<img width="737" height="538" alt="image" src="https://github.com/user-attachments/assets/6bd182f9-2705-42bd-99e3-d682a78e8726" />
##### Field Plot - Top view
<img width="1915" height="1013" alt="image" src="https://github.com/user-attachments/assets/7f40fb7b-a171-49bc-90ee-dd8c348a30c4" />
##### Field Plot - Bottom view
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/70938ebc-a67d-4011-8aa7-f007c3bd3bf1" />
























