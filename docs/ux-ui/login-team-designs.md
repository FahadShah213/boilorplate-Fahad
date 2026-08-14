# Login and Team Page UX/UI Designs

This document contains the responsive login and team page designs, together with the component-state references required for implementation.

## Responsive views

| Page | Desktop | Tablet | Mobile |
| --- | --- | --- | --- |
| Login | Included | Uses the responsive layout between breakpoints | Included |
| Team | Included | Included | Included |

## Login page

### Desktop

![Login page desktop design](./images/login-desktop.png)

### Mobile

<img src="./images/login-mobile.png" alt="Login page mobile design" width="390">

### Form and button states

The specification covers default, focus, filled, error, hover, disabled, loading, and error-recovery states. It also records the design tokens and accessibility rules used by the login form.

![Login form and button states](./images/login-states.png)

## Team page

### Desktop

![Team page desktop design](./images/team-desktop.png)

### Tablet

<img src="./images/team-tablet.png" alt="Team page tablet design" width="834">

### Mobile

<img src="./images/team-mobile.png" alt="Team page mobile design" width="390">

### Team member card states

The card specification covers standard cards, missing photos, long names and roles, long descriptions, responsive column behaviour, incomplete fields, and copy handling.

![Team member card content variants and layout behaviour](./images/team-card-states.png)

## Implementation notes

- Desktop, tablet, and mobile layouts preserve the same visual hierarchy and content order.
- Team cards change from three columns on desktop to two columns on tablet and one column on mobile.
- Form labels remain visible after a value is entered, and keyboard focus must remain clearly visible.
- Interactive controls should have a minimum touch target of 44 x 44 px.
- Placeholder brand names, slogans, descriptions, and profile copy should be replaced when final content is approved.
- Existing authentication logic and session behaviour are outside the scope of these visual updates.
