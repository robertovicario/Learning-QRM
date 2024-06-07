# Design for Quality

## Rationale behind the DFSS Approach

Design for Six Sigma (DFSS) focuses on designing or redesigning products, services, and processes to ensure they meet customer needs and achieve Six Sigma capability from the beginning. The aim is to create resource-efficient designs with high yields that are robust to process variations. DFSS contrasts with DMAIC (Define, Measure, Analyze, Improve, Control), which focuses on improving existing processes by reducing defects. DFSS, on the other hand, focuses on defect prevention by supporting the creation of new products and processes.

### The 4 Phases of the Design Process and the Related Tools

The DFSS design process is divided into four main phases:

1. **Concept Development (PLAN):** Determines product functionality based on customer requirements, technological capabilities, and economic realities. Tools: Quality Function Deployment (QFD), concept engineering.
2. **Design Development (HIGH LEVEL DESIGN):** Focuses on product and process performance issues to meet manufacturing or delivery requirements. Tools: Design Failure Mode and Effects Analysis (DFMEA), Reliability prediction.
3. **Design Optimization (ROBUST DESIGN):** Seeks to minimize the impact of production and use variations, creating a robust design. Tools: Design of Experiment (DOE), Taguchi Loss Function.
4. **Design Verification (TESTING & PRODUCTION):** Ensures that the production system meets the appropriate sigma level. Tools: Process reliability, Reliability testing.

### DFMEA: Aim and Procedure

Design Failure Mode and Effects Analysis (DFMEA) is a tool used to define and guide a logical design process. Its aims are:

- Identifying potential ways a product can fail.
- Estimating the effects of failures and associated risks.
- Recommending and prioritizing corrective design actions to reduce risk.
- Providing a traceable document for design decisions, supporting continuous improvement.

The procedure involves:

1. Identifying failure modes and their effects.
2. Determining failure causes and existing controls.
3. Calculating the Risk Priority Number (RPN) by multiplying the severity, occurrence, and detectability ratings.
4. Prioritizing and assessing corrective actions to reduce high RPN values.

### 4. Reliability: Definition and Measure

Reliability is the probability that a product, piece of equipment, or system performs its intended function for a specified period under stated conditions. It is measured on a scale from 0 to 1, where a higher value indicates higher reliability.

Measures of reliability include:

- **Failure Rate ($\lambda$):** Number of failures per unit of time.
- **Mean Time to Failure (MTTF):** Average time to failure for non-repairable items.
- **Mean Time Between Failures (MTBF):** Average time between failures for repairable items.

### Taguchi Loss Function

The Taguchi Loss Function is a statistical approach to tolerance design emphasizing that quality loss occurs with any deviation from the target value. Taguchi argued that reducing variation is the primary means of improving quality, and larger deviations from the target result in exponentially larger losses. This approach stresses moving quality control upstream to the design phase and designing systems that are insensitive to environmental changes.

### Quality Function Deployment: Aim and Structure of the Tool

Quality Function Deployment (QFD) is a structured approach to design that aims to meet customer requirements throughout the design and production process. The primary focus is to identify customer needs early to avoid redesigning products and processes later.

The structure involves several steps:

1. **Voice of the Customer (VOC):** Listing and refining customer needs, grouped into primary and secondary factors.
2. **Planning Matrix:** Competitive assessment, benchmarking, and assigning overall weighting to customer needs.
3. **Technical Requirements:** Defining how the company will meet each customer need, ensuring they are measurable.
4. **Relationships Matrix:** Linking technical requirements to customer needs and identifying the strength of these relationships.
5. **Correlation Matrix:** Identifying potential conflicts or synergies between technical requirements.
6. **Design Targets:** Establishing specific objectives based on technical priorities and benchmarking.

### Process Capability: Definition and Measure

Process Capability is the range over which the natural variation of a process occurs, determined by common causes. It predicts how well a process can meet specifications and is measured by the proportion of output within design specifications.

Key measures include:

- **Cp (Process Capability Index):** Ratio of the specification range to the process variation (6σ). Cp > 1.34 indicates a capable process.
- **Cpk (Process Capability Index considering centering):** Takes into account the process mean, providing a more accurate capability measure when the process is not centered.