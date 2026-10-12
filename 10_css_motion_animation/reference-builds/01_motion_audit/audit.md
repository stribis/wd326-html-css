# Motion Audit

| Element | Trigger | Purpose | Duration / repeat | Properties | Decision |
| --- | --- | --- | --- | --- | --- |
| Logo | Page load | None | 1s forever | `rotate` | Remove |
| Announcement | Page load | Draw attention to deadline | 600ms forever | background, color | Keep once as entrance |
| Ticket button | Page load | None until interaction | 700ms forever | `translate` | Move to hover/focus |
| Decorative spinner | Page load | Atmosphere | 2s forever | `rotate` | Remove; keep still texture |
| Session cards | Page load | None | 900ms forever | `translate` | Remove |
| Status badges | Page load | Emphasize live state | 500ms forever | `scale` | Limit to live badge and three loops |

## Reduced Motion Plan

- Information that must remain visible: deadline text, live label, and focus.
- Motion that can be removed: all entrance displacement and status scaling.
- Motion that should become instant state feedback: button focus and hover use
  visible outline or color without movement.
