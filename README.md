# Changelog
- 20th Feb 2025: Update Task 1 window dimensions.

# Assessment 1 (HTML, CSS)

[Please see course website for full spec](https://cgi.cse.unsw.edu.au/~cs6080/NOW/assessments/assignments/ass1)

This assignment is due Friday the 7th of March, 8pm.

Please run `./util/setup.sh` in your terminal before you begin. This will set up some checks in relation to the "Git Commit Requirements".

## Your Task - PicToCode

### 1. Task 1 - Static, fixed size page

Build a page that looks identical to [task1/page.png](task1/page.png). The window width you should work with is 1756 x 1666 pixels. You are only allowed to use HTML and CSS for this task. No external libraries are permitted.

Please build your page in [task1/index.html](task1/index.html). You are welcome to create as many CSS files that you need in the `task1` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

On top of this you are required to:
 * Ensure that the *Created by UNSW CSE* component box has a hover opacity of `0.5`.
 * When your mouse hovers over any of the latest article links, the text should turn #0000FF.

#### Assets

- The asset(s) are provided in `task1/assets`.
- The font used on this page should match exactly. The font used is `sans-serif` for the page.

### 2. Task 2 - Static, fixed size page

Build a page that looks identical to [task2/page.png](task2/page.png). The window width you should work with is 950 x 746 pixels. You are only allowed to use HTML and CSS for this task. No external libraries are permitted.

Please build your page in `task2/index.html`. You are welcome to create as many CSS files that you need in the `task2` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

#### Assets

- The asset(s) are provided in `task2/assets`.
- The font used on this page should match exactly. The font used is `Poppins` for the page.

### 3. Task 3 - Responsive, static page

Build a responsive page that complies with [task3/page_big.png](task3/page_big.png) and [task3/page_small.png](task3/page_small.png). The big page is 2077 x 1889 pixels, and the small page is 637 x 1651 pixels. Your single page (note that you're not using two separate HTML files) should like identical to either of these pages depending on the window sized the browser is at.

Your are expected to have reasonable intermediate states. In other words, if the window size is some combination of widths between 2077 and 637, combined with some combination of heights between 1889 and 1651, the page should still reflect the same general structure.

Please build your page in `task3/index.html`. You are welcome to create as many CSS files that you need in the `task3` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

On top of this you are required to:
 * Ensure that the *Buy Standard* button inverts on hover (e.g., the background and text colors swap)
 * Ensure that the *Be Pro* button inverts on hover (e.g., the background and text colors swap)

#### Assets

- The asset(s) are provided in `task3/assets`.
- The font used on this page should match exactly. The font used is `Arial` for the page.

# Assumptions

- Markers are aware that font rendering can vary between different browsers and operating systems. As long as you have used the correct font specified for the task and made a reasonable effort to match the intended design, we will not penalize minor typography inconsistencies and will show some leniency in this area.