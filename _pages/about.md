---
layout: about
title: about
permalink: /
subtitle: Electrical Engineering Student • University of Utah

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Salt Lake City, Utah</p>

selected_papers: false # no academic publications yet - re-enable once _bibliography/papers.bib has real entries
social: true # includes social icons at the bottom of the page

research_statement: >
  Electrical Engineering student focused on power electronics, embedded control, and mixed-signal design — from GaN-based fast chargers to autonomous sensor-driven robotics.

education:
  enabled: true
  items:
    - school: University of Utah
      degree: Bachelor of Science in Electrical Engineering
      dates: August 2022 – December 2026
      details: "GPA: 3.72/4.0"

skills:
  enabled: true
  categories:
    - title: Software
      items: KiCad (Proficient), LTSpice (Proficient), MATLAB (Proficient), Quartus (Proficient), EasyEDA (Proficient)
    - title: Lab Equipment
      items: Oscilloscope (Proficient), Multimeter (Proficient), Power Supply (Proficient), Function Generator (Intermediate)
    - title: Programming Languages
      items: Java (Proficient), Verilog (Proficient), Python (Intermediate)
    - title: World Languages
      items: English (Fluent), Vietnamese (Fluent)

experience:
  enabled: true
  items:
    - title: Electrical Technician Intern
      org: Savill Engineering Vietnam, Ho Chi Minh City, Vietnam
      dates: Jun 2025 – Aug 2025
      bullets:
        - Participated in the maintenance of MEP technical systems inside and outside the building.
        - Practiced ATS operation under the supervision of a senior technician.
        - Prepared weekly technical reports under guidance and review of the Chief Engineer.
        - Completed learning assessments on ATS, UPS, FAS, and generator systems.

projects:
  enabled: true
  items:
    - title: Miniaturized 65W GaN USB-C Fast Charger — Senior Project
      tech: LTspice, KiCad, EasyEDA
      dates: Jan 2026 – Current
      bullets:
        - Designed a custom 65W dual-port USB Power Delivery charger with a JW1565 GaN power IC in a high-efficiency flyback topology.
        - Built a complete LTspice schematic including EMI filter, snubber network, transformer design, primary GaN switch, synchronous rectifier controller, and USB-PD controller.
        - Designed and implemented a planar transformer to improve power density compared to conventional wound magnetics.
        - Designed a multi-layer PCB in KiCad and EasyEDA, targeting a footprint smaller than commercial chargers.
    - title: Autonomous Multi-Sensor Mobile Robot
      tech: Arduino Nano 33 IoT, MATLAB
      dates: Oct 2025 – Dec 2025
      bullets:
        - Built an autonomous mobile robot integrating line following, wall following, and color sensing using an Arduino Nano 33 IoT.
        - Developed control algorithms in MATLAB and applied structured finite state machine logic for task sequencing and path planning.
        - Designed a custom 3D-printed enclosure to house all sensors and electronics.
    - title: Automated Fan Controller System
      tech: LTSpice
      dates: Mar 2025 – Apr 2025
      bullets:
        - Designed a temperature-controlled fan system using CD 4007 NMOS transistors.
        - Simulated and validated temperature sensing across various temperature ranges using LTSpice.
        - Implemented the final design on a breadboard, achieving 2x faster threshold response than a design using basic logic gate control.

competitions:
  enabled: false # no competitions listed in current resume

announcements:
  enabled: false # placeholder template news items - enable once _news/ has real entries
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

awards:
  enabled: false # no awards listed in current resume

services:
  enabled: false # no services listed in current resume

miscellaneous:
  enabled: false # no additional links provided in current resume
---

I'm an Electrical Engineering student at the University of Utah, expected to graduate in December 2026. I'm interested in power electronics and embedded systems, with hands-on project experience ranging from a GaN-based 65W USB-C fast charger to an autonomous multi-sensor mobile robot. I previously interned as an Electrical Technician at Savill Engineering Vietnam, working on MEP system maintenance and ATS/UPS/FAS/generator systems.
