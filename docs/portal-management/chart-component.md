---
title: "Chart Component"
sidebar_position: 14
description: "Chart component for portal suite."
---

# Chart Component

## Chart Suite Configuration

The **Chart Suite** currently includes **15 commonly used styles**. It supports both **preset data sources** and **custom unified data sources**.

### Data Source Types

- **Preset Data Source**  
  These are data source interfaces with corresponding data formats integrated into the chart platform.

- **Custom Data Source**  
  You can choose from:
  - Low-code forms
  - Collaborative application forms
  - Data factory forms
  - Integrated interfaces

  After selection, configure the **field mapping** between **display fields** and **data source fields**.


### Connected Component Configuration

Chart components support **connected component configuration**, allowing them to link with list or chart components on the same page. This enables **data filtering** based on interaction rules.

#### Example Workflow:

1. If **Component A** is linked to **Component B**, selecting an option in Component A will cause Component B to display data filtered by that selection.

2. **Add a connected component**:  
   - Only list or chart components **on the current page** with **custom data sources configured** can be selected.

3. **Set filter conditions**:  
   - Add form fields and define matching conditions using **fixed values** or **formula-defined values**.

4. **Preview** the configuration:  
   - Selecting an option in Component A filters Component B's data as per the conditions.
