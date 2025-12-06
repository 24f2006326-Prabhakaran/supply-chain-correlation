# Supply Chain Correlation Analysis

## Project Overview
This repository contains a comprehensive correlation analysis and visualization of supply chain data following Excel best practices.

**Analyst:** 24f2006326@ds.study.iitm.ac.in  
**Contact:** 24f2006326@ds.study.iitm.ac.in  
**Email:** 24f2006326@ds.study.iitm.ac.in

## Repository Contents

### Files
1. **README.md** - This documentation file
2. **correlation.csv** - Correlation matrix generated using Excel's Data Analysis ToolPak
3. **heatmap.png** - Excel heatmap visualization with Red-White-Green conditional formatting

## Methodology

### Data Analysis Process

#### Step 1: Enable Data Analysis ToolPak
1. Open Excel
2. File → Options → Add-ins
3. Manage: Excel Add-ins → Go
4. Check "Analysis ToolPak" → OK

#### Step 2: Generate Correlation Matrix
1. Data → Data Analysis → Correlation
2. Input Range: Select all data columns (including headers)
3. Check "Labels in First Row"
4. Output Range: New Worksheet
5. Click OK

#### Step 3: Create Heatmap with Conditional Formatting
1. Copy correlation matrix to new sheet
2. Select correlation values (exclude row/column labels)
3. Home → Conditional Formatting → Color Scales
4. Choose "Red-White-Green Color Scale"
   - **Red**: Low/negative correlation (-1.0)
   - **White**: No correlation (0.0)
   - **Green**: High/positive correlation (1.0)

#### Step 4: Export Results
1. Save correlation matrix as CSV file
2. Take screenshot of heatmap (400x400 to 512x512 pixels)
3. Save screenshot as PNG format

## Correlation Matrix Interpretation

The correlation matrix shows relationships between supply chain variables:
- **1.0**: Perfect positive correlation
- **0.0**: No correlation
- **-1.0**: Perfect negative correlation

### Key Findings
- Strong correlations indicate variables that move together
- Weak correlations suggest independent variables
- Negative correlations show inverse relationships

## Visualization Details

### Heatmap Color Scheme
- **Green cells**: Strong positive correlation (values close to 1.0)
- **White cells**: Weak or no correlation (values close to 0.0)
- **Red cells**: Strong negative correlation (values close to -1.0)

### Image Specifications
- Format: PNG
- Dimensions: 400x400 to 512x512 pixels
- Color Palette: Red-White-Green gradient
- Source: Excel Conditional Formatting

## Technical Details

**Software Used:**
- Microsoft Excel (Data Analysis ToolPak)
- Conditional Formatting (Color Scales)

**Analysis Type:**
- Pearson Correlation Coefficient
- Pairwise correlation between all variables

**Data Quality:**
- All numeric variables
- No missing values
- Labels in first row

## Contact Information

**Primary Contact:** 24f2006326@ds.study.iitm.ac.in

For questions about the analysis methodology or data interpretation, please contact:
- Email: 24f2006326@ds.study.iitm.ac.in
- Analyst: 24f2006326@ds.study.iitm.ac.in

## Repository Structure

```
supply-chain-correlation/
├── README.md           # This file (contains email: 24f2006326@ds.study.iitm.ac.in)
├── correlation.csv     # Correlation matrix data
└── heatmap.png         # Excel heatmap visualization (400x400 to 512x512 px)
```

## Usage Instructions

### Viewing the Correlation Matrix
1. Open `correlation.csv` in Excel or any spreadsheet software
2. Review correlation coefficients between variables
3. Identify strong relationships (|r| > 0.7)

### Interpreting the Heatmap
1. Open `heatmap.png` to view the visualization
2. Green areas indicate positive correlations
3. Red areas indicate negative correlations
4. White areas indicate weak correlations

## Best Practices Applied

✅ Used Excel's Data Analysis ToolPak for standardized calculations  
✅ Applied conditional formatting with appropriate color scheme  
✅ Exported data in CSV format for reproducibility  
✅ Created visual representation for quick interpretation  
✅ Documented methodology and specifications  
✅ Included contact information: 24f2006326@ds.study.iitm.ac.in  

## Notes

- Correlation does not imply causation
- Results are based on linear relationships
- Outliers may affect correlation coefficients
- Always validate findings with domain knowledge

---

**Created by:** 24f2006326@ds.study.iitm.ac.in  
**Last Updated:** December 2024  
**Maintainer:** 24f2006326@ds.study.iitm.ac.in
