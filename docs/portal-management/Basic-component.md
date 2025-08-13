The basic suite includes two types of component styles:
- Some styles do not require system data source configuration, being purely frontend displays or configurable with custom links or related trigger actions: includes basic components such as images, blank spaces, buttons, filter components, and custom links.
- Some styles can be configured with system-preset data sources: the portal integration system provides pre-configured data source interfaces in corresponding formats, including basic components such as personnel, calendars, meetings, messages, custom pages, audio, and video.
- When configuring data sources for styles in the basic suite, custom unified data source configuration is not supported.

1.	Configure the style component of the data source, using audio-visual as an example. Other configurations (personnel, calendar, meetings, messages, custom page components) are similar. 
  Drag in the audio component, select an audio file in the content area (from the audio materials in the asset library). After configuring other styles, appearance, and permissions, preview to see the configuration effect.
<div style={{ display: 'flex', justifyContent: 'left' }}>
  <img src="/img/Basic Component img 1.png" alt="Portal Diagram" width="800" />
</div>
2. Drag in the button component, click **Add Event** in the configuration area, with options for click events and load completion events.

- **Click event:** Clicking the button triggers related actions.
- **Load completion event:** After the current page loads, related actions are triggered.

3. After adding a click or load event, add the corresponding trigger action.

- **Open page:** Clicking the button opens a specific page, with configurable opening methods and link extension parameters.
- **Close window:** Closes the currently open window, with a configurable pop-up interface vocabulary.
- **JavaScript:** Custom JavaScript events.
- **Confirmation dialog:** Triggers a dialog pop-up, with a configurable dialog interface vocabulary.
- **Connected components:** Works with list components and icon components to filter out data that meets the conditions.

> If the current configuration page has list components and icon components added, and a custom data source is configured, then during connection configuration, the corresponding components can be selected to define filtering conditions and filter out related data.

4. After configuring one or more trigger actions, when previewing the page, clicking or completing page loading will execute the corresponding trigger actions in sequence.


**5 Filter Component Configuration**

- **Simple filtering:** Single-condition filtering or multiple conditions filtered by default using "AND" logic.
- **Advanced filtering:** Multiple conditions support configuring "OR" and "AND" logic for filtering.

1. From the basic suite, drag in a filter component and select simple filtering.

2. Add a filter component, with selectable components coming from charts or list groups on this page that have custom data sources configured, as shown below.

3. Set up and add filter items, with configurable option types as shown in the image.

4. For example, add an option filter item, set the option value, and name it according to actual business needs.

5. Configure the filter component to map option values one-to-one with the corresponding fields in the component form.

6. Preview to see the actual filtering component effect.

7. Toggle advanced filtering mode, which supports configuring multiple conditions with AND/OR relationships.