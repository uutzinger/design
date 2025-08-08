# Design Curriculum for Biomedical Engineers
- [Design Curriculum for Biomedical Engineers](#design-curriculum-for-biomedical-engineers)
  - [Student Design Projects](#student-design-projects)
  - [A - Engineering Design Principles](#a---engineering-design-principles)
  - [B - Electrical Design](#b---electrical-design)
  - [C - Software Design](#c---software-design)
  - [D - Mechanical Design](#d---mechanical-design)
  - [E - Design in Biochemistry](#e---design-in-biochemistry)
  - [F - Design in Biology](#f---design-in-biology)
  - [G - Design in Physiology](#g---design-in-physiology)
  - [H - Materials and Biomaterials Design](#h---materials-and-biomaterials-design)
  - [I - Design in Health Sciences](#i---design-in-health-sciences)
- [](#)
  - [J - Imaging Systems Design](#j---imaging-systems-design)
  - [K - Human-Centered Design and Usability](#k---human-centered-design-and-usability)
  - [L - Regulatory and Quality Design](#l---regulatory-and-quality-design)

---

## Student Design Projects
- [A - Design Principles - Wearable fall detection device for elderly patients](./Biomedical/A%20-%20Engineering%20Design%20Principles%20-%20Student%20Project.md)
- [B - Electrical - Low-power ECG acquisition module](./Biomedical/B%20-%20Electrical%20Design%20-%20Student%20Project.md)
- [C - Software - Mobile app for remote patient monitoring](./Biomedical/C%20-%20Software%20Design%20-%20Student%20Project.md)
- [D - Mechanical -  Adjustable prosthetic hand prototype](./Biomedical/D%20-%20Mechanical%20Design%20-%20Student%20Project.md)
- [E - Biochemistry - Portable uric acid detection device using enzymatic biosensor](./Biomedical/E%20-%20Biochemistry%20Design%20-%20Student%20Project.md)
- [F - Biology - Engineering bacteria to detect glucose in saliva](./Biomedical/F%20-%20Design%20in%20Biology%20-%20Student%20Project.md)
- [G - Physiology - Wearable multi-parameter physiological monitor for rehabilitation patients](./Biomedical/G%20-%20Design%20in%20Physiology%20-%20Student%20Project.md)
- [H - Materials - Design and testing of a hydrogel-based wound dressing](./Biomedical/H%20-%20Materials%20and%20Biomaterials%20Design%20-%20Student%20Project.md)
- [I - Health Sciences- Clinical workflow optimization tool for vital signs monitoring](./Biomedical/I%20-%20Design%20in%20Health%20Sciences%20-%20Student%20Project.md)
- [K - Human Centered - Pulse oximeter for elderly user](./Biomedical/K%20-%20Human-Centered%20Design%20and%20Usability%20-%20Student%20Project.md)
- [L - Regualtory - Design history file for class II device](./Biomedical/L%20-%20Regulatory%20and%20Quality%20Design%20-%20Stduent%20Project.md)

---

## A - Engineering Design Principles
Cross-cutting **principles** for medical device development, including **problem definition**, identification of **clinical needs**, and evaluation of **feasibility** and **trade-offs**. Covers **constraints analysis**, **user-centered design**, **risk assessment**, and alignment with **regulatory** and **payer** requirements. Emphasizes **iterative prototyping**, **testing**, and integration of multidisciplinary inputs throughout the design process.

### A-1 Problem Definition and Requirement Analysis <!-- omit in toc -->
 - Unmet clinical need
 - Plausibility (is there evidence that the problem can be addressed)
 - Feasibility (do we have ability to create a solution)
 - User Analysis (intermediate impact on user/patient)
 - Societal Outcomes (impact beyond user/patient)
 - Constraints
 - Functional versus Nonfunctional Requirements
 - Writing Design Specifications

### A-2 Conceptual Design and Ideation <!-- omit in toc -->
 - Brainstorming, Ideation
 - Functional Decomposition
 - Sketching Diagramming
 - Tradeoff Matrices, Decision Making

### A-3 Design Documentation and Communication <!-- omit in toc -->
 - Technical Writing
 - Design Review Presentation
 - Notebook, lab journals, version control
 - System Diagram, Specifications

### A-4 Risk Management and Reliability <!-- omit in toc -->
 - Hazard Analysis
 - Risk prioritization and mitigation
 - Redundancy, Safety Margin, Robustness (Meantime between failure)
 - Tolerance and Uncertainty

### A-5 Prototyping and Integration <!-- omit in toc -->
 - Prototyping (rapid)
 - Iteration
 - Specification Validation & Product Verification (V&V)
 - Test plan for validation and verification
 - Human Subjects Testing

### A-6 Design for Manufacturability <!-- omit in toc -->
 - Materials and Process Selection
 - Assembly Process
 - Minimizing Cost and Complexity
 - Bill of Materials

### A-7 Regulatory and Standard Awareness <!-- omit in toc -->
 - Medical Device Classes
 - Design Controls
 - Design Standards
 - Traceability and Documentation for Regulatory Submission

### A-8 Ethics, Sustainability <!-- omit in toc -->
 - Accessibility and Inclusiveness
 - Environmental Impact
 - Human Subjects Ethics
 - Design for diverse populations

### A-9 Systems Thinking and Integration <!-- omit in toc -->
 - System Interfaces
 - Modularity, Upgradability, Maintenance
 - Compatibility between Components
 - System Level Behavior

---

## B - Electrical Design
Design and development of **electrical systems** for biomedical devices, encompassing **analog and digital circuitry**, **power management**, **sensor integration**, and **PCB layout**. Involves **circuit analysis**, **component selection**, and **system-level integration** of sensors, actuators, and communication interfaces. Emphasizes **safety**, **reliability**, **noise mitigation**, and compliance with **medical electrical standards** for performance in clinical environments.

### B-1 Foundational <!-- omit in toc -->
 - Circuit Schematics
 - Understanding Datasheets and Specifications
 - Circuit Prototyping
 - Soldering and Rework

### B-2 Analog <!-- omit in toc -->
 - Passive Components
 - Active Components
 - Amplifier
 - Filtering
 - Noise mitigation (grounding, shielding, filtering)
 - Signal Conditioning

### B-3 Digital <!-- omit in toc -->
 - Logic, Truth Table, Combinational, Sequential Circuit
 - Flip Flop, Latches, Timers
 - Microcontrollers
 - Single-board Computers
 - Memory and Storage
 - Direct Communication (SPI, I2C, UART, CAN, USB)
 - Wide Area Communication (Cellular, Internet)
 - Long Range Communication (Radio, LoRa)

### B-4 PCB Design and Layout <!-- omit in toc -->
 - Schematic Capture
 - Component Placement
 - Power and Ground Plane 
 - Trace, Via

### B-5 Power Systems <!-- omit in toc -->
 - Linear vs Switching
 - Battery Systems
 - Voltage Regulators
 - Load Analysis
 - Integrity (Decoupling, EMI)

### B-6 Sensor Interfaces and Signal Acquisition <!-- omit in toc -->
 - Measurement Techniques (e.g. Pressure, Acceleration, Temperature, Chemical, Imaging)
 - Analog Front End (Amplification, Filtering, Isolation)
 - Analog-to-Digital Conversion
 - Noise reduction and filtering
 - Sensor fusion

### B-7 Control and Feedback <!-- omit in toc -->
 - Closed Loop Control Basics
 - PID
 - Interfacing of Actuator

### B-8 Safety and Isolation <!-- omit in toc -->
 - Patient Electrical Safety Standards
 - Current Limits
 - Isolation
 - Fail Safe and Fault Detection
 - Water and Fluid Ingress Protection
 - Mechanical Shock Protection

### B-9 Test and Debugging <!-- omit in toc -->
 - Multimeter, Oscilloscope, Function Generator
 - Test Protocol and Test Points
 - In Circuit Debugging

---

## C - Software Design
Design and development of **software systems** for biomedical devices and health applications, from **embedded firmware** to full-scale clinical platforms. Includes **signal processing**, **real-time control**, **communication protocols**, **UI/UX design** for medical interfaces, and secure **data handling**. Emphasizes **safety-critical coding practices**, **regulatory compliance**, and **integration with hardware** and clinical workflows.

### C-1 Software Requirements and Specifications <!-- omit in toc -->
 - User and System Requirements
 - Use Cases
 - Functional and Non-Functional Requirements
 - Constraints (Realtime, Safety Critical and Regulatory)

### C-2 Programming Fundamentals <!-- omit in toc -->
 - Embedded Systems Programming (C, Rust)
 - Application Development (Python, Java)
 - Scripting (bash)
 - Modularity and Libraries
 - Memory Management

### C-3 Software Architecture and Design Patterns <!-- omit in toc -->
 - State Machines
 - Event Driven Programming
 - Producer, Consumer

### C-4 Embedded and Realtime Software <!-- omit in toc -->
 - Working with microcontroller
 - Bare Metal Programming
 - Timing Critical Design
 - Power Management
 - Interrupt Driven Programming

### C-5 Signal Processing and Data Acquisition <!-- omit in toc -->
 - IIR, FIR and Windowing
 - FFT and spectral analysis
 - Feature extraction (ECG)
 - Digital Integration with AFE
 - Sampling Theory

### C-6 User Interfaces and Visualization <!-- omit in toc -->
 - UI frameworks
 - Visualization, Plotting
 - Touch and Voice Interface
 - Indicators

### C-7 Communication and Interfacing <!-- omit in toc -->
 - Serial UART, USB
 - BLE Wi-Fi, wired
 - Parsing and handling binary
 - Client/Server Architecture
 - Secure Communication, Encryption

### C-8 Data Handling and Storage <!-- omit in toc -->
 - Structured Data (JSON, Protocol Buffers)
 - Realtime logging and buffering
 - Data integrity (CRC, journaling)
 - Database integration

### C-9 Testing and Debugging <!-- omit in toc -->
 - Unit testing
 - Integration and System Testing
 - Realtime Debugging
 - Simulators

### C-10 Version Control and Collaboration <!-- omit in toc -->
 - GIt, Github
 - Code Documentation
 - Issue Tracking


### C-11 Machine Learning and Artificial Intelligence (AI) <!-- omit in toc -->
 - Preprocessing for ML pipelines
 - Model Training and Inference
 - Model Deployment
 - Interpretability and Explainability
 - Ethical use of AI

---

## D - Mechanical Design
Design, analysis, and fabrication of **mechanical systems** for biomedical applications, integrating **engineering principles**, **material science**, **biomechanics**, and **manufacturability**. Involves the use of **CAD tools**, **mechanical analysis** (statics, dynamics, FEA), **tolerance specification**, and the creation of **mechanisms, enclosures, and structural components**. Emphasizes **ergonomics**, **environmental durability**, and compliance with **medical device standards**.

### D-1 Design Fundamentals <!-- omit in toc -->
 - Reading and Creating Engineering Drawings and Schematics
 - Understanding Tolerances, Fits, Geometric Dimensioning
 - Use of Units, Precision and Scale
 - Basics of Force, Torque, Motion and Static/Dynamic Loading

### D-2 Computer Aided Design <!-- omit in toc -->
 - 3D Modelling
 - Creating Assemblies and Applying Motion Constraints
 - Generating 2D drawings form 3D models
 - Exporting formats for simulation and fabrication

### D-3 Material Selection <!-- omit in toc -->
 - Properties: Tensile Strength, Modulus, Hardness, Fatigue
 - Compatibility with biological tissues
 - Plastic, Metals, Ceramics, Elastomers
 - Tradeoffs

### D-4 Prototyping and Fabrication <!-- omit in toc -->
 - 3D printing
 - Laser cutting
 - CNC machining
 - Manual: Cutting, Drilling, Tapping, Assembling
 - Casting, Molding, Forming
 - Design for Manufacturability
 - Design for Assembly

### D-5 Mechanism Design <!-- omit in toc -->
 - Linkages, cams, gears, levers
 - Slide-crank, four-bar
 - Linear and rotary motion conversion
 - Spring, dampers and actuators

### D-6 Fluid Systems <!-- omit in toc -->
 - Flow path for gas, liquids
 - Fluid resistance, laminar, turbulent flow
 - Pump and Valves

### D-7 Thermal Systems <!-- omit in toc -->
 - Thermal Management

### D-8 Fasteners and Joints <!-- omit in toc -->
 - Screw, Bolt, Pin
 - Press Fits, Snap Fits, Interference fits
 - Welding, Soldering, Adhesive Bonding
 - Quick release, tool free Assembly

### D-9 Structural Stress Analysis <!-- omit in toc -->
 - Free body diagrams and calculations
 - Stress, strain, deformation
 - Factor of Safety and Fatigue
 - Simple beam, truss, shaft loading
 - Buckling, Torsion in slender elements

### D-10 Finite Element Analysis <!-- omit in toc -->
 - Mesh creation and refinement
 - Boundary conditions and loads
 - Static, Dynamic and Thermal Simulations
 - Interpreting and Validating Simulations

### D-11 Ergonomics <!-- omit in toc -->
 - Design for anthropometry
 - Comfort, adjustment, accessibility
 - Tactile feedback, grip design
 - Minimizing strain

### D-12 Enclosures and Packaging <!-- omit in toc -->
 - Environment Sealing
 - Shielding from EMI, impact and thermal exposure
 - Sterilization Compatibility
 - Aesthetics and Functional Considerations

### D-13 Biomechanics and Implant Design <!-- omit in toc -->
 - Load transfer (bone, muscle, soft tissue)
 - Joint mechanics, prosthetics alignment
 - Orthopedic and Dental Implants

### D-14 Documentation and Standards <!-- omit in toc -->
 - Design Revision tracking and part numbering
 - Medical device standards
 - Drawing Compliance

---

## E - Design in Biochemistry
Design and development of **biochemical systems** for diagnostics, therapeutics, and research applications. Involves **lab-on-chip platforms**, **microfluidic devices**, **biosensors**, and **chemical assay systems**, as well as **reagent formulation**. Emphasizes **integration of biochemical reactions** with transducers, **optimization** for sensitivity and specificity, **biocompatibility**, and compliance with **in vitro diagnostic (IVD) standards**.

### E-1 Biochemical Assay Design <!-- omit in toc -->
- Understanding and designing colorimetric, fluorescent, and luminescent assays
- Kinetics of enzyme-linked assays (e.g., ELISA, lateral flow tests)
- Reagent selection and immobilization strategies
- Optimization of sensitivity, specificity, and dynamic range
- Standard curve creation, sample preparation, and result interpretation

### E-2 Surface Chemistry and Immobilization <!-- omit in toc -->
- Functionalizing surfaces for biomolecule binding (e.g., silanization, SAMs, PEGylation)
- Covalent vs non-covalent attachment strategies
- Microarray spotting and surface patterning
- Surface passivation to reduce non-specific binding
- Stability and shelf-life considerations for bio-functionalized surfaces

### E-3 Lab-on-a-Chip and Microfluidics <!-- omit in toc -->
- Design of microfluidic channels and reaction chambers
- Laminar flow, mixing, and diffusion in microscale systems
- Material selection (e.g., PDMS, COC, PMMA) and bonding techniques
- Capillary action, valves, pumps, and flow control
- Integration of sensors (electrochemical, optical, etc.) with fluidic paths

### E-4 Enzyme and Protein Engineering (Basic Design Literacy) <!-- omit in toc -->
- Understanding enzyme structure–function relationships
- Designing reaction cascades with multiple enzymes
- Stabilization of enzymes and proteins for use in diagnostics
- Site-directed immobilization (e.g., His-tag, biotin-streptavidin)
- Tuning activity and pH dependence for engineered reactions

### E-5 Diagnostic System Integration <!-- omit in toc -->
- Coupling biochemical assays with transducers (e.g., electrochemical, optical, FET-based)
- Signal amplification techniques (e.g., nanoparticle labels, enzyme recycling)
- Calibration and quantification in point-of-care settings
- Environmental tolerance: temperature, humidity, shelf stability
- Designing user-friendly cartridges, test strips, or cassettes

### E-6 Reagent and Buffer Design <!-- omit in toc -->
- Creating stable, pH-buffered environments for reactions
- Surfactant, salt, and additive selection for biological compatibility
- Lyophilization or reagent drying for storage in field-deployable systems
- Formulating wash buffers and blocking solutions for non-specific signal suppression

### E-7 Biocompatibility and Biointerface Engineering <!-- omit in toc -->
- Designing for compatibility with cells, tissues, or blood
- Protein fouling and antifouling coatings
- Biofilm prevention and sterilization effects
- In vitro compatibility testing strategies (e.g., cytotoxicity, hemolysis)

### E-8 Molecular Detection Techniques <!-- omit in toc -->
- Primer design for PCR and isothermal amplification (e.g., LAMP)
- Nucleic acid probe design (e.g., FISH, microarrays, CRISPR-based detection)
- Signal transduction and reporter systems
- Contamination control and sample integrity management

### E-9 Biological Standards and Controls <!-- omit in toc -->
- Use of internal standards and reference samples
- Designing positive and negative controls into test workflows
- Quantitative vs qualitative result handling
- Batch testing and validation planning

### E-10 Safety and Handling <!-- omit in toc -->
- Safe handling of biohazards (e.g., blood, enzymes, RNA/DNA)
- Proper storage and disposal of reagents
- Lab setup for biochemical workflow: sterile zones, contamination prevention
- Use of PPE and biosafety level (BSL) compliance

### E-11 Documentation and Regulatory Awareness <!-- omit in toc -->
- Labeling and traceability of reagents and test lots
- International Organization for Standardization (ISO) standards for in vitro diagnostics (e.g., ISO 13485, ISO 23640)
- Reproducibility documentation (protocol sheets, batch records)
- Clinical validation and performance metrics (LoD, LoQ, sensitivity, specificity)

---

## F - Design in Biology
Design and engineering of **biological systems** at the cellular and molecular level, integrating **synthetic biology**, **genetic circuit design**, **biofabrication**, and **cellular system modeling**. Involves creating and optimizing **living systems** for sensing, actuation, and therapeutic purposes, including **tissue engineering**, **protein engineering**, and **organoid development**. Emphasizes **biosafety**, **ethical considerations**, and integration with engineered devices.

### F-1 Synthetic Biology and Genetic Circuit Design <!-- omit in toc -->
- Understanding genetic components: promoters, terminators, RBS, coding sequences, repressors
- Designing gene circuits: logic gates, toggle switches, oscillators (e.g., repressilators)
- Using synthetic biology design tools (e.g., Benchling, SnapGene, Cello, SBOL)
- Predicting circuit behavior using models (e.g., ODEs, logic simulations)
- Codon optimization and vector selection for expression in bacteria, yeast, or mammalian cells

### F-2 Cellular Engineering <!-- omit in toc -->
- Designing gene delivery systems: plasmids, viral vectors, electroporation
- Cell line selection and engineering (e.g., HEK293, CHO, stem cells)
- Controlling gene expression with inducible systems (e.g., tetracycline, IPTG, optogenetics)
- Creating stable vs transient transfections
- CRISPR/Cas9 and related tools for genome editing

### F-3 Cell Culture and Tissue Engineering Design  <!-- omit in toc -->
- Designing protocols for 2D and 3D cell culture
- Bioreactor design for perfusion, mechanical stimulation, and gas exchange
- Scaffold design: biomaterials, porosity, stiffness, and degradation rate
- Designing for cell adhesion, proliferation, and differentiation
- Interface between living tissue and engineered materials (e.g., tissue-device integration)

### F-4 Interfacing Biology with Devices <!-- omit in toc -->
- Biosensor design using live cells or tissues
- Biohybrid systems: combining actuators or sensors with muscle, neurons, etc.
- Real-time feedback loops between biological signal and digital control
- Stimulation of cells/tissues using electrical, optical, or chemical inputs
- Measurement and quantification of biological response (e.g., calcium imaging, fluorescence, impedance)

### F-5 Modeling Biological Systems <!-- omit in toc -->
- Creating mathematical or computational models of biological circuits
- Understanding and using systems biology models (e.g., for signaling pathways, metabolic networks)
- Using simulation tools: MATLAB SimBiology, COPASI, BioNetGen
- Parameter estimation, sensitivity analysis, and model validation

### F-6 Biomolecular Engineering <!-- omit in toc -->
- Protein engineering basics: structure-function relationship, directed evolution
- Design of ligand-receptor binding systems
- Design of antibody-antigen recognition elements (e.g., for biosensors or targeting)
- Fusion proteins and functional domains for modular bio-design

### F-7 Organoid and Complex System Design <!-- omit in toc -->
- Miniaturized organ systems (e.g., gut-on-a-chip, brain organoids)
- Microenvironment engineering: ECM mimics, growth factors, niche design**
- Interconnection of tissues in multi-organ platforms (body-on-chip)
- Vascularization and nutrient delivery in engineered tissues

### F-8 Evolutionary and Developmental Design Thinking <!-- omit in toc -->
- Designing using principles of natural selection or developmental gradients
- Incorporating feedback and adaptation in biological systems
- Exploiting evolutionary algorithms to optimize biological designs

### F-9 Biosafety and Ethical Design <!-- omit in toc -->
- Designing biological systems with kill-switches or containment controls
- Bioethics in genetic modification, stem cells, and chimeric organisms
- Compliance with biosafety regulations (e.g., NIH guidelines, BSL levels)
- Responsible innovation in synthetic and cellular bioengineering

### F-10 Documentation, Standards, and Reproducibility <!-- omit in toc -->
- Recording constructs using SBOL (Synthetic Biology Open Language)
- Design traceability and DNA part version control
- Standard operating procedures (SOPs) for biological protocols
- Participating in open-source biology communities (e.g., iGEM, BioBricks Foundation)

---

## G - Design in Physiology
Design of **systems** that monitor, interface with, support, or replace **physiological functions**, including **organ systems**, **neural pathways**, and **musculoskeletal structures**. Involves **physiological modeling**, **sensor placement**, and **signal/data acquisition** for diagnostics, therapy, and restoration of function. Covers **prosthetics**, **artificial blood vessels**, **nerve repair**, **joint and bone repair**, **brain–machine interfaces**, and **rehabilitation technologies**. Emphasizes **patient safety**, **functional integration**, and **clinical applicability**.

### G-1 Physiological System Modeling <!-- omit in toc -->
- Block diagram representation of organ systems (e.g., cardiovascular, renal, respiratory)
- Compartment models for fluid, drug, and solute transport (e.g., for dialysis or glucose dynamics)
- Simulation of physiological control loops (e.g., baroreflex, respiratory rate, thermoregulation)
- Use of modeling tools: MATLAB/Simulink, Python, OpenSim, COMSOL

### G-2 Sensor Placement and Physiological Signal Acquisition <!-- omit in toc -->
- Surface and implantable electrode placement (e.g., ECG, EMG, EEG, ECoG)
- Understanding physiological signal characteristics: amplitude, frequency, noise reduction and filtering
- Artifact suppression and signal conditioning (e.g., motion artifacts, EM interference)
- Tissue-electrode interface design and impedance matching
- Sensor placement constraints due to anatomy, motion, and user comfort

### G-3 Organ Support and Replacement System Design <!-- omit in toc -->

- 🫀 Cardiovascular Support
    - Heart function (incl. ventricular assist devices (VADs), total artificial hearts, heart valves
    - Pacemakers and defibrillators
    - Artificial blood vessels and vascular grafts:
        - Design considerations: compliance matching, thrombosis resistance, anastomosis technique
        - Materials: PTFE, Dacron, tissue-engineered vessels

- 🫁 Respiratory Support
    - Mechanical ventilators (invasive and non-invasive)
    - CPAP/BiPAP systems
    - Oxygen delivery and gas exchange systems
    - Understanding of lung mechanics and patient-ventilator interaction

- 🧠 Neural Interfaces and Repair
    - Brain-computer interfaces (BCIs)
    - Cortical and spinal recording/stimulation
    - Peripheral nerve interfaces (e.g., cuffs, intrafascicular arrays)
    - Nerve repair and regeneration:
        - Nerve guidance conduits (synthetic, biological)
        - Scaffold design and growth factor delivery
        - Electroactive polymers for nerve stimulation
        - Assessment of nerve conduction and regeneration

- 🩸 Renal Replacement (Kidney)
    - Dialyzer design: membrane type, flow configuration, solute clearance
    - Hemodialysis vs peritoneal dialysis system architecture
    - Ultrafiltration and volume control
    - Monitoring of electrolytes, urea, creatinine, and toxins

- 🧬 Endocrine Function Replacement
    - Artificial pancreas systems: closed-loop insulin pumps with CGM sensors
    - Modeling of glucose-insulin dynamics
    - Hormone delivery systems with time-release mechanisms

### G-4 Designing for anatomical fit and physiological compliance <!-- omit in toc -->
- Ergonomics for wearable/implantable devices
- Long-term biocompatibility and immune response mitigation
- User interaction with therapeutic systems (e.g., alarms, displays, interface)

### G-5 Closed-loop and Feedback Control Design <!-- omit in toc -->
- Control system design for physiological regulation
    - e.g., insulin dosing, blood pressure, neurostimulation
- PID control, fuzzy logic, and adaptive control in physiological systems
- Redundancy and fail-safes for life-critical systems
- Handling biological variability and personalized parameters

### G-6 Clinical Integration and Constraints <!-- omit in toc -->
- Designing around clinical workflow (e.g., ICU, OR, at-home use)
- Sterilization, disposability, and maintenance requirements
- Risk analysis and mitigation for life-supporting systems
- Interoperability with hospital data systems (e.g., HL7, FHIR, DICOM)

### G-7 Functional Replacement vs Augmentation <!-- omit in toc -->

- Restorative vs assistive technologies
    - e.g., cochlear implants vs hearing aids
    - prosthetic limbs vs exoskeletons
- Enhancing vs mimicking native function
- Ethical considerations in augmentation (e.g., neuroenhancement)

---

## H - Materials and Biomaterials Design
Selection and engineering of **materials** for **contact with biological systems**, either temporarily (catheters, wound dressings) or permanently (implants, prosthetics). Involves **material characterization**, **surface modification**, and **mechanical property optimization** to ensure **biocompatibility**, **durability**, and compliance with **regulatory standards**. Emphasizes **matching material properties** to functional and biological requirements.

### H-1. Material Selection Criteria <!-- omit in toc -->
- **Biocompatibility**  
  - Non-toxic, non-carcinogenic, non-immunogenic  
  - Resistance to corrosion or degradation in body fluids  
  - Minimal leaching of harmful compounds
- **Mechanical Properties**  
  - Strength, elasticity, fatigue resistance, toughness  
  - Matching mechanical properties to tissue (e.g., compliance matching in vascular grafts)
- **Chemical Stability**  
  - Resistance to hydrolysis, oxidation, enzymatic degradation
- **Sterilization Compatibility**  
  - Material integrity under autoclave, gamma irradiation, ethylene oxide, or plasma sterilization
- **Regulatory Approval**  
  - Material must meet standards (e.g., ISO 10993 biocompatibility testing)

### H-2. Classes of Biomaterials <!-- omit in toc -->
- **Metals** – Titanium, stainless steel, cobalt-chrome alloys (implants, fixation devices)  
- **Polymers** – Polyethylene (PE), PTFE, PEEK, silicone (catheters, joint liners, tubing)  
- **Ceramics & Glasses** – Alumina, zirconia, bioactive glass (dental implants, bone fillers)  
- **Composites** – Fiber-reinforced polymers, ceramic-polymer blends (bone plates, prosthetics)  
- **Hydrogels** – PEG, alginate, collagen-based (drug delivery, tissue scaffolds)  
- **Natural Materials** – Collagen, chitosan, silk fibroin (scaffolds, wound dressings)

### H-3. Surface Engineering & Modification <!-- omit in toc -->
- **Coatings** – TiN, diamond-like carbon, hydroxyapatite for improved wear, osteointegration, or hemocompatibility  
- **Surface Roughening or Patterning** – Promoting cell adhesion or preventing bacterial attachment  
- **Chemical Functionalization** – Immobilizing bioactive molecules, anti-fouling PEG layers  
- **Plasma Treatment & Etching** – Modifying surface chemistry for better bonding or wettability

### H-4. Degradable vs. Non-Degradable Materials <!-- omit in toc -->
- **Degradable** (temporary implants, sutures, drug delivery)  
  - Polylactic acid (PLA), polyglycolic acid (PGA), polycaprolactone (PCL)  
  - Designed for predictable resorption time  
- **Non-Degradable** (permanent implants, prosthetics)  
  - Titanium alloys, UHMWPE, ceramics  
  - Designed for long-term stability without significant property loss

### H-5. Tissue-Material Interactions <!-- omit in toc -->
- **Protein Adsorption** – First step in biological response; impacts cell adhesion  
- **Cell Adhesion & Proliferation** – Influenced by surface chemistry/topography  
- **Foreign Body Reaction** – Fibrous encapsulation, inflammation, immune activation  
- **Hemocompatibility** – Preventing thrombosis for blood-contacting devices

### H-6. Testing & Characterization <!-- omit in toc -->
- **Mechanical Testing** – Tensile, compressive, flexural, fatigue, hardness  
- **Surface Characterization** – SEM, AFM, contact angle, XPS  
- **Biocompatibility Testing** – Cytotoxicity, sensitization, irritation, hemolysis, genotoxicity  
- **Degradation Studies** – Mass loss, molecular weight change, pH changes in degradation media

### H-7. Design for Manufacturing & Integration <!-- omit in toc -->
- **Processing Techniques** – Molding, machining, additive manufacturing, extrusion, sintering  
- **Joining Methods** – Welding, adhesive bonding, press-fit assembly  
- **Dimensional Stability** – Shrinkage, warping, thermal expansion  
- **Integration with Electronics** – Encapsulation, hermetic sealing, feedthroughs

### H-8. Special Considerations <!-- omit in toc -->
- **Drug-Eluting Materials** – Incorporating controlled drug release  
- **Smart Materials** – Shape-memory alloys/polymers, stimuli-responsive hydrogels  
- **Anti-Microbial Surfaces** – Silver nanoparticle coatings, quaternary ammonium compounds  
- **Bioresorbable Electronics** – Temporary sensing/therapy devices that dissolve after use

---

## I - Design in Health Sciences
Design of **healthcare workflows**, **clinical interfaces**, and **data management systems** for improved **patient outcomes** and **efficiency**. Covers **integration with clinical systems**, **user interaction**, **epidemiological modeling**, and **health data privacy**. Emphasizes **interoperability**, **usability**, and compliance with **health data regulations**.

### I-1. Workflow Integration <!-- omit in toc -->
- **Clinical Environment Mapping** – Understanding hospital, clinic, and home-care workflows.
- **Device Interoperability** – Using standards such as HL7, FHIR, and DICOM for data exchange.
- **Minimizing Workflow Disruption** – Designing devices/software to fit seamlessly into existing practices.
- **Automation Opportunities** – Reducing clinician workload with smart systems.
- **Clinical Decision Support (CDS)** – Integrating algorithms that assist diagnosis or treatment planning.
- **Training Requirements** – Minimize learning curve; design for quick onboarding.
- **Multi-User Environments** – Support role-based permissions and simultaneous access.
- **Environmental Constraints** – Lighting, noise, mobility limitations in clinical spaces.

### I-2. Epidemiological Modeling <!-- omit in toc -->
- **Data Sources** – Electronic Health Records (EHRs), public health databases, wearable sensors.
- **Model Types** – SIR/SEIR models, agent-based simulations, time-series forecasting.
- **Applications** – Disease outbreak prediction, resource allocation, intervention impact assessment.
- **Integration with Health Policy** – Presenting model outputs for decision-makers in usable formats.

### I-3. Security <!-- omit in toc -->
- **Secure Data Transmission** – Encryption in transit (TLS) and at rest.
- **Access Control** – Role-based permissions, audit logging.
- **Cybersecurity in Healthcare** – Threat modeling, intrusion detection, incident response.

### I-5. Safety & Risk Management <!-- omit in toc -->
- **Clinical Safety** – Avoiding harm from device misuse or malfunction.
- **Infection Control** – Designing for sterilization, disinfection, or disposability.

#
---
## J - Imaging Systems Design
Design and development of **imaging systems** for biomedical applications, encompassing both **clinical imaging** and **non-clinical imaging**. Focuses on **system physics**, **hardware design**, **signal/data acquisition**, and **image processing** to achieve high-quality, reliable, and safe imaging for diagnosis, therapy, and research.

### J-1 Core Skills <!-- omit in toc -->
- **Imaging physics**:
  - **Optical** (geometric optics, physical optics)
  - **Acoustic** (including Doppler principles)
  - **Magnetic** (including k-space principles)
  - **Radiation-based** imaging
- **Imaging system principles**:
  - Linearity and shift-invariance
  - Point spread and transfer functions
  - Reconstruction techniques
  - Spatial sampling and sampling in frequency space
- **Sensor and detector design**
- **Calibration** and **quality assurance** protocols  
- Integration with **data acquisition** and **analysis pipelines**  
- Designing for **ergonomic operation** and **environmental constraints**  

### J-2 Clinical Imaging Systems Design <!-- omit in toc -->
- **Clinical Systems**:
  - X-ray
  - Computed Tomography (**Computed Tomography (CT)**)
  - Magnetic Resonance Imaging (**Magnetic Resonance Imaging (MRI)**)
  - Ultrasound
  - Nuclear medicine (PET, SPECT)
- **Signal processing for clinical system**:
  - Signal acquisition
  - Image reconstruction algorithms
  - Artifact reduction
- **Image quality optimization**
- Compliance with **safety standards** and **regulatory requirements**
- Integration with **hospital Picture Archiving and Communication System (PACS)** and **Electronic Medical Record (EMR) systems**

### J-3 Non-Clinical Imaging Systems Design <!-- omit in toc -->
- **Non-Clinical Systems**:
  - Macroscopy (including small animal observation)
  - Microscopy
  - Fluorescence imaging
  - Nanoscopy (including electron microscopy)
  - Optical Coherence Tomography (**OCT**)
  - Thermal imaging
  - High-speed imaging
- **Signal processing for non-clinical systems**:
  - Resolution enhancement
  - Contrast methods
  - Automation
- Integration with **analytical and image analysis software**

---

## K - Human-Centered Design and Usability
Design with a **human-centered approach** focusing on **accessibility**, **ergonomics**, **user experience**, and **clinical integration** of devices. Involves **user research**, **usability testing**, and **iterative refinement**. Emphasizes **inclusion**, **ease of use**, and **effectiveness** in real-world healthcare settings.

### K-1. Principles of Human-Centered Design (HCD) <!-- omit in toc -->
- **User Involvement from the Start** – Engage stakeholders early through interviews, shadowing, and observation.
- **Iterative Design** – Rapid prototyping and feedback loops to refine design.
- **Context of Use Analysis** – Identify physical, environmental, and workflow conditions under which the device will operate.
- **Inclusive Design** – Accommodate users with different ages, abilities, languages, and technical literacy.

### K-2. Usability Engineering in Healthcare <!-- omit in toc -->
- **ISO 62366 Compliance** – Standard for usability in medical devices.
- **Use-Related Risk Analysis (URRA)** – Identify and mitigate risks caused by design-induced user errors.
- **Task Analysis** – Break down procedures to optimize steps, reduce complexity, and prevent mistakes.
- **Formative vs Summative Usability Testing** – Early-stage feedback vs regulatory submission testing.

### K-3. Accessibility <!-- omit in toc -->
- **Physical Accessibility** – Device size, weight, reach, and control layout.
- **Sensory Accessibility** – Clear visual displays, tactile feedback, auditory cues.
- **Cognitive Accessibility** – Simple, consistent navigation; avoiding overload; using plain language.
- **Regulatory Alignment** – ADA (Americans with Disabilities Act), WCAG (Web Content Accessibility Guidelines) for digital interfaces.

### K-4. Ergonomics <!-- omit in toc -->
- **Anthropometric Data Use** – Designing to fit human size ranges (e.g., 5th to 95th percentile).
- **Posture and Reach** – Minimizing strain, optimizing control placement.
- **Grip and Force Requirements** – Ensuring comfortable operation for intended user population.
- **Long-Term Use Comfort** – Especially critical for wearables or implantables.

### K-5. User Experience (UX) in Clinical Settings <!-- omit in toc -->
- **Information Clarity** – Present only necessary information at the right time.
- **Feedback and Status Indicators** – Provide clear confirmation of actions, alerts for errors or hazards.
- **Error Recovery** – Offer clear steps to correct mistakes without restarting the process.
- **Visual Hierarchy** – Organize interface elements for quick scanning under stress.

---

## L - Regulatory and Quality Design
Design for **regulatory compliance** and **quality management** in biomedical engineering. Involves meeting requirements for **United States Food and Drug Administration (FDA)/Conformité Européenne (CE) marking**, adherence to **ISO 13485**, and **design controls** under 21 CFR Part 820. Emphasizes **risk management**, **documentation**, and **verification** to ensure safe and effective products.

### L-1. Regulatory Frameworks <!-- omit in toc -->
- **United States** – FDA regulations, especially **21 CFR Part 820** (Quality System Regulation).
- **Europe** – EU Medical Device Regulation (MDR) and In Vitro Diagnostic Regulation (IVDR), **CE Marking** requirements.
- **International** – ISO 13485 (Quality Management Systems), ISO 14971 (Risk Management).
- **Other Markets** – Japan PMDA, Health Canada, TGA (Australia).
- **Regulatory Compliance** – HIPAA (US), GDPR (EU), and local privacy laws.
- **Data Anonymization & De-identification** – Removing or masking personal identifiers.

### L-2. Design Controls (per 21 CFR 820.30) <!-- omit in toc -->
- **Design and Development Planning** – Documented plan with deliverables and timelines.
- **Design Inputs** – Clear, measurable requirements based on user needs and intended use.
- **Design Outputs** – Drawings, specifications, and manufacturing instructions meeting inputs.
- **Design Review** – Formal checkpoints to evaluate progress and compliance.
- **Design Verification** – Confirm design outputs meet input requirements.
- **Design Validation** – Confirm device meets user needs and intended use.
- **Design Transfer** – Hand-off to manufacturing with complete, controlled documentation.
- **Design Changes** – Formal change control process with impact analysis.

### L-3. Quality Management System (QMS) <!-- omit in toc -->
- **Document Control** – Managing SOPs, work instructions, records.
- **Training and Competency Records** – Ensuring personnel are trained for their roles.
- **Corrective and Preventive Actions (CAPA)** – System to address and prevent recurring issues.
- **Internal Audits** – Regular checks of QMS compliance.
- **Supplier Management** – Qualification, monitoring, and control of external suppliers.

### L-4. Risk Management <!-- omit in toc -->
- **ISO 14971 Compliance** – Risk analysis, evaluation, control, and residual risk assessment.
- **Hazard Analysis Techniques** – FMEA, FTA, hazard analysis tables.
- **Benefit-Risk Analysis** – Demonstrating that benefits outweigh residual risks.

### L-5. Clinical Evaluation & Post-Market Surveillance <!-- omit in toc -->
- **Clinical Evaluation Reports (CER)** – Required for CE Marking.
- **Post-Market Surveillance (PMS)** – Monitoring device performance after release.
- **Vigilance Reporting** – Reporting adverse events to authorities (MDR, FDA).

### L-6. Regulatory Submissions <!-- omit in toc -->
- **United States** – 510(k), De Novo, PMA applications.
- **Europe** – Technical File / Design Dossier for CE Marking.
- **Documentation Requirements** – Device description, labeling, risk analysis, testing data, manufacturing processes.