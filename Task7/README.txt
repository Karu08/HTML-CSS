Pure CSS Carousel/Slider - TASK 7

Objective:
To develop an image carousel that cycles through slides automatically and manually.


Properties used:
1) display: flex; - Used on .slides to align images side by side in a row

2) overflow: hidden; - Hides the overflow (so only one slide shows at a time)

3) transition: transform - Smooth sliding effect when slide changes

4) transform: translateX() - Moves the slide container left/right to show different slides

5) @keyframes slide - Defines how the .slides container moves automatically

6) animation: slide 9s infinite; - Runs the auto-slide animation repeatedly

7) :not(:has(input:checked)) - Applies animation only when no radio button is selected(i.e. auto mode)


Files in this folder:
1. task7.html