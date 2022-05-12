# Notes for Nathan

If you make a repo named "nabellows.github.io" and upload the attached files, [github pages](https://pages.github.com/) should do the heavy lifting. 

## CSS
CSS is a pain, but I'm using CSS variables for colors, so it should be slightly easier. go to `comp.css`, and all the color definitions should be at the top of the file. in case they're not, here's the default:

```css
:root{
    /* unused */
    --emp-content: #93a1a1; 
    /* default text color */
    --base-content: #c9c9c9;
    /* text color for hovered top row tabs, background color */
    --bkgnd-color: #1e1e1e;
    /* default background color of the top nav */
    --base02: 	#2d2d2d;
    /* unused */
    --base01: #586e75;
    /* unused */
    --base00: #657b83;
    /* unused */
    --base0: 	#839496;
    /* background color for hovered top row tabs */
    --base1: 	#93a1a1;
    /* unused */
    --base2: 	#eee8d5;
    /* unused */
    --base3: #fdf6e3;
    /* color of "Home" text on top bar when on index.html */
    --sol-red:  #d16969;
    /* color of "Projects" text on top bar when on projects.html */
    --sol-orng: #CE9178;
    /* color of "Work Experience" text on top bar when on work.html */
    --sol-yel:  #d7ba7d;
    /* color of "Gen. Ed. Reflection" text on top bar when on gen_ed_ref.html */
    --sol-grn:  #4EC9B0;
    /* unused */
    --sol-cyn:  #2aa198;
    /* color of "Cumulative Reflection" text on top bar when on cumulative_ref.html */
    /* also used for unvisited link text color */
    --sol-blu:  #4FC1FF;
    /* color of "Ethics Paper" text on top bar when on ethics.html */
    /* also used for visited text color */
    --sol-vio:  #C586C0;
    /* unused */
    --sol-mag:  #d33682;
}
```
## Font 
If you don't like the default font, you can find a new one on [Google Fonts](https://fonts.google.com/). When you find one you like, follow the instructions on the site to add it to your portfolio site. Keep in mind that you'll have to add the `<link>` tags to every html page you want that font on. Make sure that you replace the default font `<link>` tag as well # Portfolio
