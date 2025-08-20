---
title: "Ranking Component"
sidebar_position: 12
description: "Ranking component for portal suite."
---

## Ranking Suite Configuration

The **Ranking Suite** currently includes 4 styles. This suite style supports selecting **preset data sources** and **custom data sources**.

- **Preset data source:** The portal integration system provides pre-configured data source interfaces with corresponding data formats.
- **Custom data source:** Supports selecting low-code forms, collaborative application forms, data factory forms, or integrated interfaces to obtain data sources. Then, configure field mapping between display fields and data source fields.

---

### Custom Data Source Configuration Steps

1. Drag in the **Statistical Ranking Component**.
2. Click the **Custom** button in the configuration area.
3. Select the system data source (e.g., **Low-code Form** data).
4. Configure field mappings between the ranking component's display fields and the data source fields.
5. Set additional options such as:
   - **Sorting**: Define the metric field used for ranking.
   - **Display Fields**: Choose fields for title, subtitle, or numeric values depending on the selected style.
   - **Color and Style**: Customize colors for ranking bars, fonts, or background as supported by the selected style.
6. Preview the configured ranking component to view real data effects.

> 💡 *Note: Some styles may support additional customizations such as icons, thresholds, or special highlight rules.*
<div style={{ display: 'flex', justifyContent: 'left' }}>
  <img src="/img/Ranking Component.png" alt="Portal Diagram" width="800" />
</div>
## 2. Configure Field Mapping Between Display Fields and Data Source Fields

After selecting the custom data source for the **Ranking Suite**, configure the field mappings to connect the display components with the actual data source fields.

### Field Mapping Options:

- **Ranking Object**  
  Specifies the field used to represent the ranking item, such as a *document title* or *author name*.

- **Ranking Field**  
  The statistical field that determines the ranking metric, such as the *number of reads* or *number of documents created* by an author.

- **Default View**  
  Defines the URL that users are redirected to when they click on a ranking item.  
  - **By default**: Automatically uses the document URL.  
  - **Custom**: You can manually set a different link address if needed.

- **Open Method**  
  Determines how the redirect link opens when a ranking item is clicked:  
  - **Default**: Opens in a **new tab**.  
  - **Optionally**: Configure to open in the **current page**.

- **Sorting**  
  Applies only to the **ranking field** (not the object). You can choose to display the results in:  
  - **Ascending** order  
  - **Descending** order

- **Other Common Attributes**  
  Include style-related configurations such as:
  - Display quantity
  - Font settings
  - Refresh interval
  - Component layout  
  These are consistent with other suite configuration options.

