# SkillsUSA Pennsylvania (Redesign)

## Overview
A modernized, mobile-first redesign of the SkillsUSA Pennsylvania website with a clean UI, improved navigation, and front-end-only demo flows. The project includes the Home page, Login, Create Account, and a redesigned District Signup form.

### Content & Layout Mapping
- **Primary sections preserved:** Deadlines/Calendar, Downloads, State Officers, State Initiative, State Director.
- **Events and programs:** Fall Leadership, Membership, Districts.
- **State Conference:** Countdown module and conference CTA.

## Pages
- `index.html` – Home
- `login.html` – Login demo
- `create-account.html` – Create account demo
- `district-signup.html` – District signup (multi-step form)

## Run Locally
Because this is a static project, any simple file server works.

```bash
python -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Mocked Functionality
All flows are front-end only using `localStorage`:
- **Create Account:** stores a demo user record.
- **Login:** validates against the stored demo user.
- **District Signup:** stores submitted district data and shows a success state.

## Design Notes
- Softened SkillsUSA red as the primary brand color.
- Reusable components for buttons, cards, inputs, alerts, navbar, and footer.
- Accessible focus states, labels, and responsive layouts optimized for mobile-first usage.
