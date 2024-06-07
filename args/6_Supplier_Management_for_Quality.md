# Supplier Management for Quality

## Acceptance Sampling (Logic)

Acceptance sampling is a statistical quality control technique where a random sample is taken from a lot. Based on the sample results, the entire lot is either accepted or rejected. This approach helps in decision-making without inspecting each item individually. It is particularly useful when:

- Testing is destructive.
- 100% inspection is impractical due to time or technological constraints.
- The supplier has a good quality history but needs some reduction from 100% inspection.

#### Operating Characteristic Curve

The Operating Characteristic (OC) curve plots the probability of accepting a lot (Pa) against the lot fraction defective (p). It demonstrates the discriminatory power of the sampling plan, showing the likelihood of accepting lots with various quality levels. Key parameters include:

- **AQL (Acceptable Quality Level):** The maximum defect level considered acceptable as a process average. It is the poorest quality level the consumer would accept for the supplier’s process.
- **LTPD (Lot Tolerance Percent Defective):** The poorest quality level acceptable in an individual lot, specified by the consumer.
- **Alpha ($\alpha$, Producer’s Risk):** The probability of rejecting a good lot, typically 5%.
- **Beta ($\beta$, Consumer’s Risk):** The probability of accepting a bad lot, typically 10%.

## Rectifying Inspection Programs

Rectifying inspection programs involve additional inspections and corrective actions when lots are rejected. Key metrics include:

- **Average Outgoing Quality (AOQ):** The average quality level of outgoing lots after inspection and correction, calculated as: $$\text{AOQ} = \frac{Pa \cdot p \cdot (N-n)}{N}$$
- **Average Total Inspection (ATI):** The total amount of inspection required, calculated as: $$\text{ATI} = n + (1-Pa)(N-n)$$ It is designed to achieve specified AOQL (Average Outgoing Quality Limit) with minimal inspection.

## Military Standard (MIL-STD-105E)

MIL-STD-105E is a widely used acceptance sampling system developed during World War II. It includes several types of sampling plans (single, double, multiple) and inspection levels (normal, tightened, reduced). The standard involves the following steps:

1. **Choose AQL:** Determine the acceptable quality level.
2. **Choose Inspection Level:** Select between general levels (I, II, III) or special levels (S-1, S-2, S-3, S-4).
3. **Determine Lot Size (N):** Based on the vendor’s lot size.
4. **Find Sample Size Code Letter:** Refer to the standard table.
5. **Determine Type of Sampling Plan:** Select between single, double, or multiple sampling plans.
6. **Enter Appropriate Table:** Find the specific plan details.
7. **Determine Normal and Reduced Inspection Plans:** Follow switching rules based on inspection outcomes.

Example: For a lot size N of 2000 and AQL of 1%, using normal inspection at general level II, you would determine the sample size and acceptance number from the standard tables provided in MIL-STD-105E. 
