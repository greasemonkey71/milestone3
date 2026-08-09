# Milestone 3 - Accessibility & Visual Design

## WAVE Errors Fixed & Documented
1. **Missing Image Alt Text:** Added descriptive `alt` attributes to all image elements
 across all pages so screen reader users can understand the context of visual content.

2. **Missing Language Attribute:** Added `lang="en"` to the `<html>` element on every
 page so screen readers select the correct pronunciation engine.

3. **Empty Link Targets:** Replaced broken `<a href="#">` placeholder links with valid
 internal page anchors so screen reader users aren't left stranded.

4. **Low Text Contrast:** Adjusted navigation and link text colors against dark
 backgrounds to meet WCAG AA contrast standards for visually impaired users.

5. **Form Input Labels:** Explicitly linked every `<input>` and `<textarea>` tag to its
 corresponding `<label>` using matching `for` and `id` attributes so assistive 
 technologies can read field labels when focused.


## Gestalt Principles Applied
1. **Proximity:** Grouped each officer's headshot, name, role, and historical photos
 closely together inside distinct `<article class="officer-card">` containers, visually
  signaling to users that those elements belong to the same person.

2. **Similarity:** Styled all resource cards, info sections, and form elements with
 identical border-radii (8px), dark background cards (`rgba(0,0,0,0.85)`), and
  consistent accent colors (`#e63946` red and `#457b9d` blue), signaling to users that
   these items belong to the same content category.
   