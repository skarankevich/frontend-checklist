# Frontend Checklist

## Structure
* Project has `README.md` with development and deployment `instructions`
* Project has `package-lock.json`
* Project has `robots.txt` in a public root
* Project has `favicon` and icon shows project's logo. Use [Real Favicon Generator](https://realfavicongenerator.net/)

## Code
* There is **no** `linting warnings or errors`

## Build
* Production build runs with `NODE_ENV=production`
* CSS and JS files have unique `hash` in filename e.g. `app.5d41402abc4b2a76b9719d911017c592.js`

## Landing Page
* Website has proper document `title` and meta `description`
* Website has proper `OpenGraph` data: title, description, image

## Design
* App has consistent colors
* App has consistent fonts
* App has consistent wording. For example, if `Sign up`, no `Sign Up`, `Sign-up`, `SignUp`

## Layout
* `Horizontall scrolling` in `responsive` version appears only if window width is less than `320px`
* `Horizontall scrolling` in `desktop only` version appears only if window width is less than `1024px`
* There is **no** `jumping elements` while user interacts with UI

## Responsive Version
* Proper viewport meta tag is used: `<meta name="viewport" content="width=device-width, initial-scale=1">`

## Navigation
* App has no `broken links`
* Every screen has its `own URL` (Login: /login, Restore password: /restore_password, etc)
* App is able to store its `state in URL` and restore it `from URL`

## Forms
* The first field has `autofocus`
* User is able to navigate through form fields by `Tab` button
* Form elements have `active/disabled/valid/invalid` states
* Form submits on `Enter` key press

## Login Form
* User is able to login with `password manager` (browser embedded or external)

## Lists
* UI has `empty data` state
* Data filtering/sorting/pagination stores `state in URL` (share-friendly URLs)
* Filter updating sets pagination to the `first page`

## Content
* `Big image` doesn't brake its wrapper (max-height: 100%; max-width: 100%)
* `Modal` (Popup) layer closes on `Esc` press
* `Gallery` switch images on `arrows` (`<` and `>`) press
* Action `icons` have `title` hint

## Fonts
* All custom fonts have fallback `system fonts`

## Data Format
* `Date` is stored in `UTC` ([ISO 8601](https://en.wikipedia.org/wiki/ISO_8601))

## Data Transfer
* App communicates with server via `JSON`
* App indicates data `fetching` process (`spinner`, logo blinking, etc)
* App displays successful transfer as well as failed

## Offline Mode
* App displays message while it's in `offline mode`
