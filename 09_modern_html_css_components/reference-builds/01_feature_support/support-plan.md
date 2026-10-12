# Support Plan

- Feature being enhanced: CSS anchor positioning.
- Baseline experience: the popover opens as a fixed panel in the lower corner.
- Enhanced experience: the same panel appears above its trigger.
- What remains usable without support? The trigger, content, focus order, and
  light-dismiss behavior.
- Browser or device checks: current Chrome, Firefox, Safari, keyboard, narrow
  viewport, zoom, and a browser with the `@supports` block disabled.
- What would make this enhancement unsafe to ship? If content access or the
  close behavior depended on anchor positioning.
