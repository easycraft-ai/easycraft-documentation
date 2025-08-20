---
title: "Statistics Component"
sidebar_position: 13
description: "Statistics component for portal suite."
---

# Statistics Component

## Statistics Suite Configuration

The **Statistics Suite** currently includes **2 styles**. It supports both **preset data sources** and **custom data sources**.

### Data Source Types

- **Preset Data Source**  
  The portal integration system provides pre-configured data source interfaces with predefined formats.

- **Custom Data Source**  
  You can choose from:
  - Low-code application forms
  - Collaborative application forms
  - Data factory forms
  - Integrated interfaces

  Once selected, configure field mappings between **display fields** and **data source fields**.



### Steps to Configure the Statistics Suite:

1. **Drag in the Statistics Suite** component and select **Custom Data Source**.

2. **Add Three Sets of Data Sources**:  
   - For each, select the **Low-Code Application - Leave Form** as the data source.
   - Set filters based on **Leave Type** (e.g., Sick Leave, Annual Leave).
   - Perform **statistics** using the **Document Title** field.
   - Configure a **redirect URL** for each data point to enable click-through behavior.
<div style={{ display: 'flex', justifyContent: 'left' }}>
<img src="/img/Statistics.png" alt="Portal Diagram" width="800" />
</div>

3. **Preview** the configuration to check the effect.
