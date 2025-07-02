#  Relative Gene Expression Analysis Using the ΔΔCt Method

This project applies the **ΔΔCt (Delta-Delta Ct)** method to analyze qPCR data and measure relative gene expression.

---

##  Method Overview

1. **Ct Measurement**  
   Ct = the PCR cycle at which fluorescence surpasses background.

2. **ΔCt Calculation**  
   `ΔCt = Ct_target - Ct_reference`  
   Normalizes target gene expression to a housekeeping gene (*Tubulin*).

3. **ΔΔCt Calculation**  
   `ΔΔCt = DCt_treated - ΔCt_control`  
   Compares treatment vs. control after normalization.

4. **Fold Change**  
   `Fold Change = 2^(-ΔΔCt)`  
   Fold change > 1 = upregulation; < 1 = downregulation.

---

## Results

The Excel file includes:
- Ct values for each sample
- ΔCt and ΔΔCt calculations
- Fold Change per gene
[2025_Excercise_qPCR - Yael Merlis.xlsx](https://github.com/user-attachments/files/21023756/2025_Excercise_qPCR.-.Yael.Merlis.xlsx)


---

#


