# Contributing to CodeGlob Docs
These are the guidlines you need to follow when you contribute.
## Contents
- [General](#general)
- [New Pages](#new-pages)
- [Modifying Existing Pages](#modifying-existing-pages)
  - [Fixing Typos](#fixing-typos)
  - [New Sections](#new-sections)
  - [Adding Clarification](#adding-clarification)
- [When You're Done...](#when-youre-done)

## General
- Make sure you specify what you have added/changed.
- Try and make sure your wording is clear enough for others to understand.
- Only CHANGE when necessary. You can ADD what you feel will improve the docs.
- Do NOT delete whole files unless absolutely necessary. If so, mention why in your PR description.

## New Pages
- Name the file with the title of your page. E.g. a page about snippets should be called `snippets.html`.
- Try to keep your CSS and JavaScript in the same file like this:
```
<html>
  <head>
    <title>CodeGlob Docs</title>
    
    <style>
    
      /* Styling goes here */
    
    </style>
  </head>

  <body>
  
    <!-- HTML here -->
    
    <script>
    
      // JS here
      
    </script>
  </body>
</html>
```
If you cannot do this for any reason, mention so and why in the description when you are opening the pull request.
- Always try to use the template (docs template coming soon!)
- Try to add a hyperlink to this new page. Make sure to specify WHERE it is, and if you cannot add a hyperlink, mention so and we will add one where we think is best.

## Modifying Existing Pages
### Fixing Typos
- If you are fixing a typo, mention so in the pull request description OR (more preferably) open an Issue on the [main CodeGlob repository](https://github.com/hamdivazim/CodeGlob).
- ONLY modify what is necessary and DO NOT change anything else if you only intend to fix a typo.

### New Sections
- This is when you are adding a new part to a specific topic. E.g. adding how to _edit_ snippets. This would be a new section under _Snippets_.
- Make sure you add an `<h2>` tag with the heading of your new section.

### Adding Clarification
- If you feel a sentence or paragraph is unclear, you can help others to understand it better by making it clearer.
- Make sure you specify which _line number(s)_ you have modified.

## When You're Done...
- Open a pull request on this repository with your changes.
- Make sure you have specified what you've changed/added in the description.
- Wait patiently for a CodeGlob dev to merge your changes 😄
