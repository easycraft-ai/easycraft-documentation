The carousel kit currently has 4 styles. All kit styles support selecting preset data sources or custom data sources.

- **Preset data source:** The portal integration system provides pre-configured data source interfaces with corresponding data formats.
- **Custom unified data source:** Supports selecting low-code forms, collaborative application forms, data factory forms, or integrated interfaces as data sources, followed by field mapping between display fields and data source fields.



### Using Preset Data Source

- Drag in a carousel kit style, configure the component content area, and select a preset data source interface.

1. Select preset data sources from those provided by the respective system or module.

2. After selection, the corresponding data source interface content parameters will load automatically for attribute configuration.



### Using Custom Unified Data Source

- Select a custom unified data source, divided into basic data fields and common property fields.

1. Data source fields can be selected from low-code application forms, system application forms, data factory application forms, or integrated interfaces.

> The following operations use a low-code form data source as an example. After selection, basic data fields and common property fields will load.

2. Configure one-to-one mapping for basic data fields.

- Basic data: After selecting a unified data source, the component displays all fields supported by the data source interface. For different styles, some fields may be invalid. Configure display fields based on style requirements.

3. Configure common property fields:

- Sorting: Supports increasing or decreasing sorting by any field in the form.
- Data filtering: Filters selected form data source data according to specified rules, effective for all styles globally.
- Icons: Some styles allow icon settings and icon redirect URLs, effective for specific styles locally.
- Additional information: Some styles include additional fields for mapping corresponding form fields, effective for specific styles locally.
- Maximum display: Sets the maximum number of documents displayed on the component, effective for all styles globally.
- Refresh time: The interval at which the component automatically refreshes its content. Leave empty for no refresh. Decimal values are configurable. Global styles apply.
- Custom button: All components support configuring custom redirect URLs and custom button names. Global styles apply.
- Content fields: Some styles support configurable display fields for content, while others have no related configurations.

4. After configuration, click **Preview** to see the real data effect.