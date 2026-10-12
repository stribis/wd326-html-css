![SAE Institute](https://s3-eu-west-1.amazonaws.com/euwebsite2015sae-che/wp-media-folder-sae-switzerland/wp-content/uploads/sites/26/2022/05/sae-institute-logo-light-664x200-1-3.png)

# Web Design & Development 0326

Code repository for the HTML and CSS lessons of the WD 326 class.

## Exercise Structure

Each lesson keeps its existing material and adds two workshop folders:

- `code-studio/` contains student instructions and starter files.
- `reference-builds/` contains matching completed versions with teaching comments.

Exercise numbers and folder names match between the two locations. Open each
exercise folder directly with a local development server unless its README
includes a build command.

## Lessons

1. `01_html_foundations`
2. `02_css_foundations`
3. `03_flexbox_layout`
4. `04_box_model_positioning`
5. `05_typography_visual_polish`
6. `06_media_on_the_web`
7. `07_data_media_forms`
8. `08_accessibility_workshop`
9. `09_modern_html_css_components`
10. `10_css_motion_animation`
11. `11_css_frameworks`
12. `12_modern_css_sass`

See [EXERCISE-INVENTORY.md](EXERCISE-INVENTORY.md) for the complete exercise
map and quality checklist.

## Sass Exercises

Lessons using Sass include a local `package.json`. Run `npm install` in that
exercise folder, then use the documented `sass:build` or `sass:watch` script.
Do not edit generated CSS directly and do not commit `node_modules`.
