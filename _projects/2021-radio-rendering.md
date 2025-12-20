---
layout: project
image: /assets/images/FA25Counterflow-lab.jpeg
description: Heat Exchanger Performance: Parallel vs. Counter-flow
technologies: N/A
---

# Heat Exchanger Performance: Parallel vs. Counter-flow

## Introduction

This portfolio examines a water-to-water heat exchanger operating in parallel-flow and counter-flow configurations. The device consists of two internal channels that allow hot and cold water streams to exchange energy through a conductive metal wall without mixing. This report examines the thermodynamic behavior of this system and how changing the flow configurations affects its heat transfer performance by measuring the inlet and outlet temperatures of the hot and cold streams. Ultimately, understanding these thermodynamic differences provides direct insight into the design strategies used in real-world engineering applications.

## Photos and Schematics

### Photographs from the Lab

**Parallel-flow configuration**

![Parallel-flow setup](/assets/images/FA25Parallelflow.png)

**Counter-flow configuration**

![Counter-flow setup](/assets/images/FA25Counterflow.jpeg)

**Close-up of tube connections**

![Close-up of labeled tube connections](/assets/images/FA25Counterflow-lab.jpeg)

### Schematics

**System in counter-flow**

![Counter-flow schematic](/assets/images/function-graph.png)

*(Replace this image with a more accurate schematic later if needed.)*

## Qualitative Description of the Device

The device used in this lab was a metal water-to-water heat exchanger with four plastic tubes creating two isolated internal channels, one for hot water and one for cold water. There are four separate containers set up that act as tanks. One tank has ice and is insulated with Styrofoam, and another contains an immersion heater.

One pump circulates hot (orange) water from the heated tank through tubes 3 and 4, sending it through the heat exchanger into an empty tank. A second pump circulates cold (blue) water from the insulated tank through tubes 1 and 2 into another empty tank. In this system, the heat exchanger allows heat to pass from one water stream to the other by conduction across the metal wall and convection within each water stream, without the streams ever mixing.

By changing which tubes are connected to which ends of the device, we can create:

- **Parallel-flow**, where hot and cold water flow in the same direction.
- **Counter-flow**, where the streams enter from opposite ends and flow in opposite directions.

This setup allows a direct comparison of heat-transfer performance based on the temperature distribution in the two configurations.

## System Diagrams

*(Insert your own control-volume sketches in place of the placeholders below if you scan them as images later.)*

**Control Volume Diagram: Parallel-flow**

> [Sketch or description of the control volume for the parallel-flow configuration]

**Control Volume Diagram: Counter-flow**

> [Sketch or description of the control volume for the counter-flow configuration]

## Mass, Energy, and Entropy Balance Equations

For each configuration, the heat exchanger can be modeled as a steady-flow device with no work and negligible changes in kinetic and potential energy.

**Mass balance**

- Total mass flow in = total mass flow out

**Energy balance (per unit time)**

- \( \dot{Q}_{\text{hot}} + \dot{Q}_{\text{cold}} = 0 \)
- \( \dot{Q} = \dot{m} c_p (T_{\text{out}} - T_{\text{in}}) \)

**Entropy balance (qualitative)**

- Irreversibilities in heat transfer and fluid mixing lead to an overall increase in entropy.
- The configuration that maintains a larger temperature difference along the length of the exchanger can transfer more heat for the same area.

*(You can replace this section with your exact equations if you want to show the full derivation.)*

## Experimental Results

### Measured Temperatures

| Flow Configuration                  | \(T_{h,\text{in}}\) (°C) | \(T_{h,\text{out}}\) (°C) | \(T_{c,\text{in}}\) (°C) | \(T_{c,\text{out}}\) (°C) |
|------------------------------------|--------------------------|---------------------------|--------------------------|---------------------------|
| Parallel-flow (1→2), (3→4)         | 39.0                     | 28.3                      | 22.7                     | 22.8                      |
| Counter-flow (1→2), (4→3)          | 49.3                     | 20.7                      | 11.6                     | 32.0                      |

### Heat Change per Unit Mass

For each configuration the heat gained or lost per unit mass can be computed as:

\[
q = c_p (T_{\text{out}} - T_{\text{in}})
\]

From the calculations performed in the lab:

- **Parallel-flow:**  
  Heat gained by the cold stream per unit mass  
  \( q_c \approx 0.418 \,\text{kJ/kg} \)

- **Counter-flow:**  
  Heat gained by the cold stream per unit mass  
  \( q_c \approx 85.3 \,\text{kJ/kg} \)

This shows that, for the same mass flow rate, the counter-flow configuration allows for a much larger heat transfer.

## Conclusions

The results of this experiment clearly reveal the effect of flow configuration on heat transfer performance.

In the **parallel-flow configuration**, the temperature of the cold water barely increased. The hot water cooled only from 39.0°C to 28.3°C, while the cold water warmed from 22.7°C to just 22.8°C—an increase of only 0.1°C. Once the two streams began to approach one another in temperature, the temperature difference quickly decreased along the length of the heat exchanger. As a result, the cold stream absorbed very little heat, and the heat-transfer rate remained low. The heat gained by the cold stream per unit mass in parallel-flow is only about 0.418 kJ/kg.

In the **counter-flow configuration**, the heat transfer was much larger. The hot water cooled from 49.3°C to 20.7°C, while the cold water increased from 11.6°C to 32.0°C, a rise of 20.4°C. This large temperature rise shows that counter-flow maintains a significant temperature difference between the two streams along the entire length of the heat exchanger. Because the hottest hot water is always in contact with colder water, the temperature gradient remains high, and thus the heat-transfer rate is much larger than in parallel-flow.

The heat gained by the cold water per unit mass in counter-flow is approximately 85.3 kJ/kg, which is more than two orders of magnitude higher than in parallel-flow. Assuming the mass flow rate is the same (since the same pumps were used in both the hot and cold streams), these differences demonstrate that counter-flow heat exchangers cause a larger heat transfer and operate far more effectively than ones in parallel-flow.
