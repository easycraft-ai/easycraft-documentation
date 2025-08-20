---
title: "List Component"
description: "List component for portal suite."
---

## List Suite Configuration

The **List Suite** currently includes 9 styles, such as plain text lists, image-text lists, and table components. This suite supports selecting **preset data sources** or **custom data sources**.

- **Preset data source:** The portal integration system provides pre-configured data source interfaces with corresponding data formats.
- **Custom data source:** Supports selecting low-code forms, collaborative application forms, data factory forms, or integrated interfaces to obtain data sources. Then, configure field mapping between display fields and data source fields.

---

### Table Component Custom Data Source Configuration

1. Drag and drop a table component and select **Custom**.
2. Select **Low-code Form** in the Unified Data Source.
3. Add fields to display in the table from the form.
4. Configure display properties for table fields:

| Field                   | Field Description                                                                 |
|-------------------------|----------------------------------------------------------------------------------|
| **Field**               | Select fields from the currently bound data source.                              |
| **Column Header Text**  | Modify the display name of the column header.                                    |
| **Alignment**           | Table column data alignment selection.                                           |
| **Column width**        | Can be adaptive or select a fixed value (unit: px).                              |
| **Line break method**   | How text is displayed when the content exceeds the column width.                 |
| **Column header color** | Choose the color of the table header.                                            |
| **Column text color**   | Content display color, can be set using a formula.                               |
| **Format**              | Numeric type data display format.                                                |

5. Preview the table settings effect.