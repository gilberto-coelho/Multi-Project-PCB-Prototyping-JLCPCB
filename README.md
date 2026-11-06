# Multi-Project PCB Prototyping

**PCB Design | Hardware Development | SMD Electronics | Cost Optimization | Modular Design**

## Project Overview

This project demonstrates a **cost-efficient approach to electronic hardware prototyping** by integrating multiple independent circuit designs into a single PCB manufacturing panel.

During the development of several electronic products, one of the main challenges was the cost of ordering small quantities of different PCBs. Since the objective was to evaluate prototypes rather than manufacture multiple units of each product, ordering every design separately was unnecessarily expensive.

To address this, I developed a multi-project PCB strategy, combining several independent electronic designs into larger manufacturing panels.

**Under the evaluated JLCPCB manufacturing and assembly conditions, this approach was significantly cheaper than ordering each PCB design separately.**

Two PCB layouts were developed:

- **PCB Version 1:** 141 × 164 mm, containing six independent electronic projects.
- **PCB Version 2:** 250 × 240 mm, containing seven independent electronic projects, including revised circuits and a reusable battery power management module.

The project involved electronic circuit design, SMD and through-hole component integration, PCB layout, 3D visualization, modular hardware development, and manufacturing cost optimization.

**All electronic circuit design, PCB layout, and hardware development work presented here was carried out independently.**

---

## 1. Cost-Efficient Prototyping Strategy

### The Problem: High Costs for Small Prototype Quantities

During electronic product development, it is often necessary to manufacture only one or two prototypes of each circuit to evaluate the hardware, verify component placement, and identify potential design improvements.

However, ordering several different PCB designs individually can significantly increase manufacturing costs, particularly when professional PCB assembly (PCBA) is required.

For this project, manufacturing each electronic design separately would have been considerably more expensive than combining them into a single larger PCB.

### The Solution: Multiple Projects on a Single PCB

Instead of placing individual manufacturing orders, I arranged several independent electronic circuits within a single PCB layout.

This allowed multiple hardware prototypes to be included in one manufacturing and assembly order.

The approach was particularly advantageous because of the minimum manufacturing quantities offered by JLCPCB:

- **Minimum PCB manufacturing quantity:** 5 boards.
- **Minimum Economic PCBA assembly quantity:** 2 assembled boards.
- **Result:** 5 fabricated PCBs, with components assembled on only 2 of them, leaving 3 unassembled PCBs.

With six different electronic designs on a single board, ordering five PCBs provided five copies of each circuit, while assembling only two boards provided two assembled prototypes of each project.

The same strategy could be applied to the second PCB version containing seven independent projects.

This avoided placing multiple separate orders, each with its own manufacturing and assembly costs.

### Why Was This Approach Significantly Cheaper?

The main objective was not to manufacture large quantities of electronic products, but to obtain a small number of functional prototypes at the lowest practical cost.

Combining the designs offered several advantages:

- **Substantial cost savings** compared with manufacturing each project separately under the evaluated conditions.
- Consolidation of multiple PCB designs into a single manufacturing order.
- Reduced duplication of manufacturing and assembly setup costs.
- More efficient use of available PCB area.
- Simultaneous prototyping of several independent electronic products.
- Availability of additional bare PCBs for future development or assembly.
- Simplified manufacturing logistics and prototype planning.

**The key advantage was obtaining multiple different electronic prototypes while paying for a single consolidated PCB manufacturing and assembly order, rather than several independent orders.**

### PCB Size and Manufacturing Cost Optimization

PCB dimensions were also considered during the design process because manufacturing and assembly costs depend on board size.

According to JLCPCB's published pricing information, an additional large-board assembly fee applies when the PCB area exceeds **650 cm2 (65,000 mm2)**.

The two PCB versions were designed below this threshold:

| Parameter | PCB Version 1 | PCB Version 2 |
|---|---:|---:|
| Dimensions | 141 × 164 mm | 250 × 240 mm |
| Total area | 231.24 cm2 | 600 cm2 |
| Independent projects | 6 | 7 |
| Above 650 cm2 threshold | No | No |

The second version was designed to accommodate more electronic circuits while remaining below the 650 cm2 large-board assembly fee threshold.

This was an important consideration when balancing available PCB area, the number of integrated projects, and manufacturing costs.

*Note: JLCPCB may apply additional charges for multiple designs, panelization, specific assembly processes, or other manufacturing requirements. The economic advantage described here refers to the configurations and quotations evaluated for this project.*

<br>

## 2. PCB Version 1 — Six Independent Projects

**Board dimensions: 141 × 164 mm**

The first PCB integrated six different electronic projects into a single manufacturing layout.

Each circuit was developed for a specific application, while the combined board was intended to simplify prototyping and reduce manufacturing costs.

### Integrated Electronic Projects

**1. Wireless Water Level Monitoring and Control**

A programmable microcontroller-based system using RF communication for long-distance monitoring and control.

The hardware was designed to support up to four water-level inputs, relay outputs, and audible alarms.

The circuit was also conceived as a reusable wireless control platform. By adapting the inputs and firmware, the same hardware could be used for other applications, such as remote button monitoring, wireless signal transmission, or relay activation.

This approach reduced the need to design a completely new PCB for every customer-specific application.

**2. Cable Length Measurement Device**

A dedicated electronic circuit developed for cable length measurement applications.

**3. AC Power Failure Detector**

An electronic monitoring system designed to detect mains power interruptions and activate a battery-powered audible alarm.

**4. Programmable High-Power Timer**

A programmable electronic timer designed for controlling electric showers or other high-power resistive heating loads.

The design considered electrical loads up to 40 A at 250 V and included programmable operation through a web interface.

**5. Wireless Emergency Alarm System**

A wireless emergency signaling system intended for applications such as bathroom assistance alarms.

The system was designed to transmit an emergency signal to a remote receiver capable of activating an audible alarm.

**6. Magnetic Stirrer Controller**

An electronic control board developed for a magnetic stirring device.

### PCB Design and Visualization

The six circuits were arranged within a single PCB layout, considering component positioning, electrical connections, available board area, and practical manufacturing requirements.

The design included different types of electronic components, including surface-mount devices (SMD) and larger through-hole components.

**Electronic Circuit Overview**

<img width="721" height="661" alt="Projeto 1 A desfoque" src="https://github.com/user-attachments/assets/5d6aa666-3eb2-43e5-aa54-3f3c9cf4faf8" />

<br>

*Selected circuit documentation. Component values and implementation details have been intentionally blurred to protect proprietary design information.*

**2D PCB Layout**

<img width="634" height="741" alt="Projeto 1 B desfoque" src="https://github.com/user-attachments/assets/24f39238-bc3e-467a-99bc-a4201eed3bb1" />

<br>

*PCB layout showing the arrangement of six independent electronic projects within a single manufacturing board.*
*Component values and implementation details have been intentionally blurred to protect proprietary design information.*

**3D PCB Visualization**

<img width="1059" height="832" alt="Projeto 1 C desfoque" src="https://github.com/user-attachments/assets/8946a3dd-f61e-459a-af7c-2490dfb119fe" />

*Three-dimensional visualization of the PCB, including electronic components and their physical arrangement.*

<br>
<br>

**Manufactured PCB**

<table>
  <tr>
    <td width="50%">
      <img width="1329" height="1383" alt="Projeto 1 D1 desfoque" src="https://github.com/user-attachments/assets/a57552ec-45b8-4b0f-ab31-bc46d38f15f7" />
    </td>
    <td width="50%">
      <img width="1314" height="1402" alt="Projeto 1 D2 desfoque" src="https://github.com/user-attachments/assets/4a954217-dcea-4d8b-af4b-6338298fbf0a" />
    </td>
  </tr>
</table>

*Photograph of the manufactured PCB, demonstrating the physical implementation of the multi-project layout.*

<br>

## 3. PCB Version 2 — Revised Designs and Modular Power Management

**Board dimensions: 250 × 240 mm**

Following the initial development, a second and larger PCB layout was designed to integrate revised versions of the electronic circuits and introduce an additional reusable power management module.

This version contained seven independent electronic projects:

1. Wireless water level monitoring and control — revised design.
2. Cable length measurement device — revised design.
3. AC power failure detector — revised design.
4. Programmable high-power timer — revised design.
5. Wireless emergency alarm system — revised design.
6. Magnetic stirrer controller — retained design.
7. Universal lithium battery power management module — new design.

The revisions were intended to improve the electronic designs while maintaining their original functionality and application flexibility.

### Reusable Lithium Battery Power Management Module

One of the main developments in the second PCB version was the introduction of a **universal battery power management module**, designed for reuse across multiple electronic products.

Several of the devices required battery-powered operation. Rather than developing a separate battery management circuit for each product, I designed a common module that could be integrated into compatible electronic boards.

The module architecture included:

- Lithium battery charging management.
- Voltage conversion from the battery to regulated supply levels, such as 5 V or 12 V.
- Integration with an external power supply.
- Support for battery-powered operation.
- A reusable hardware interface for different electronic products.

The main advantage was **hardware modularity**.

For products requiring only an external power supply, the additional battery management module could be omitted, reducing component and assembly costs.

For products requiring battery operation, the module could be integrated without redesigning the main electronic circuit.

This approach was intended to simplify product customization, reduce duplicated development work, and support different power supply configurations using a common hardware platform.

### PCB Layout and 3D Design

The second PCB incorporated the revised electronic designs and the additional power management module into a larger 250 × 240 mm layout.

The board area of 600 cm² was selected to accommodate the electronic designs while remaining below JLCPCB's published 650 cm² threshold for the additional large-board assembly fee.

The design process considered the integration of multiple independent circuits, component placement, electrical routing, and mechanical arrangement.

**Electronic Circuit Overview**

<img width="649" height="814" alt="Projeto 2 A desfoque" src="https://github.com/user-attachments/assets/bc4fda57-9dc4-4802-b612-fdb0b7cd127f" />

*Selected electronic design documentation, with proprietary circuit details intentionally obscured.*

<br>

**2D PCB Layout**

<img width="808" height="778" alt="Projeto 2 B desfoque" src="https://github.com/user-attachments/assets/515b7db2-3803-49b9-9634-f397fd5067d3" />

*Layout of the revised multi-project PCB, containing seven independent electronic designs.*

<br>

**3D PCB Visualization**

<img width="1123" height="772" alt="Projeto 2 C desfoque" src="https://github.com/user-attachments/assets/20cf07e7-5d39-4f90-9fc4-f5ab2e9d1ccc" />

*Three-dimensional visualization of the larger PCB, showing component distribution and hardware integration.*

<br>

## 4. PCB Manufacturing and Assembly Considerations

The PCB designs were developed with practical manufacturing and assembly requirements in mind.

Particular attention was given to:

- Board dimensions and manufacturing price thresholds.
- Multi-design PCB organization.
- Component placement and available assembly space.
- Integration of SMD and through-hole components.
- PCB routing and electrical connections.
- Manufacturing quantities and minimum assembly requirements.
- Component selection and assembly costs.
- Reusable circuit architectures.
- Design revisions and prototype planning.

### PCB and PCBA Manufacturing Quantities

For the selected JLCPCB prototyping workflow, the minimum PCB manufacturing quantity was five boards, while the Economic PCBA service allowed a minimum assembly quantity of two boards.

This made it possible to manufacture five copies of the combined PCB layout while assembling components on only two.

For the first PCB version, containing six independent circuits, this configuration could provide:

- 5 fabricated copies of each of the 6 circuit designs.
- 2 assembled prototypes of each circuit design.
- 3 additional unassembled copies of each circuit design.

For the second version, the same approach could provide two assembled prototypes of each of the seven electronic designs, with additional bare PCBs available for future development.

The strategy was particularly effective because only a few assembled prototypes were required during the initial hardware development stage.

### Manufacturing Cost Optimization

The manufacturing strategy was selected after evaluating the costs of ordering the electronic designs separately versus combining them into larger PCBs.

**For these prototypes, consolidating the designs into two multi-project PCB layouts resulted in substantial estimated savings compared with placing separate manufacturing and assembly orders for each electronic project.**

The savings were especially relevant because the objective was low-volume prototyping rather than production.

The exact economic advantage depends on the PCB specifications, number of independent designs, assembly quantities, components, and manufacturing service selected.

This approach demonstrates how manufacturing constraints and cost analysis can influence PCB design decisions during electronic product development.

<br>

## Project Documentation and Confidentiality

This repository presents selected examples of electronic hardware and PCB design work developed in the context of commercial product development.

The objective is to demonstrate PCB design capabilities, engineering methodology, modular hardware development, and cost-efficient prototyping strategies.

Although the electronic designs were developed independently, permission to publicly share the selected project information and images was explicitly requested and granted by the company.

To protect proprietary information and commercial interests, complete circuit schematics, component specifications, PCB manufacturing files, firmware, and detailed implementation information are not publicly available.

Some images have been intentionally blurred or simplified to prevent disclosure of sensitive electronic design details.

<br>

## Author

**Gilberto Coelho**

Electronics & Embedded Systems Developer

This project was independently developed as part of commercial electronic product development, focusing on PCB design, reusable hardware architectures, and cost-efficient prototyping of multiple electronic systems.
