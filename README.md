Js.css Library 

Introduction: this library was made by Mark Richard or as named (DeadCode). He is Egyptian who’s born in 2011, he start making it at 12/1/2026. He is Full Stack Web Developer , Python Developer , Unity C# Games Developer and , C Developer. The Goal of this Javascript Library is to make using Css More easier. 

 

Link:  

[How to add it] 

In the head in your html file add  

|   

| <script src="(Link)"></script> 

| 

 

[How it Works] --> | 

                                     

Square && Circles 

 

|   

| <div class="square_5_2_rem"></div> 

| 

 

__ First thing Define class 

__ then Choose Between square or circle then add  _ 

__ if you choose square then after it add the height and then the width and then css unit it will be like that class=”square_10_20_px" 

__Else if you choosed circle its other thing 

 

|   

| <div class=" circle_100_100_px "></div> 

| 

 

__ First is circle  then height and then width 

__after them their css unit and then border radius and he’s css unit 

Background Color 

 

                                                                              

 

|   

| <div class="square_80_200_px bg_c_red"></div> 

| 

 

__First Define Background class=”bg_” 

__add C which point to color class = “bg_c_” 

__then the color class = “bg_c_black” 

 

Color 

|   

| <p class="c_red">Hello</p> 

| 

 

__First assign color with c class=”c_” 

__then add the color class=”c_blue” 

 

Opacity 

|   

| <p class="o_0.5">Hello</p> 

| 

 

__First Define opacity with o class = “o_” 

__add opacity (0 to 1) class=”o_0.5” 

Font Size 

|   

| <p class="f_s_2_vw">Hello</p> 

| 

 

__First add f to define Font then add s to define size class=”f_s_” 

__Now add value of font size class = “f_s_10” 

__then add the css unit type class = “f_s_10_vw” (By Default its pixels) 

 

Font Weight 

|   

| <p class="f_w_100">Hello</p> 

| 

 

__First add f to define Font then add w to define weight class = “f_w_” 

__ Now add the value of weight by default its 100 class=”f_w_bold” 

 

Font Style 

 

|   

| <p class="f_st_italic>Hello</p> 

| 

 

__ First add f to define font then add st to define style class = “f 
_st_” 

 

__now add the style class = “f_st_italic”  

 

Font Family 

 

|   

| <p class="f_f_monospace">Hello</p> 

| 

 

__ First add f to define font then add another f  to define family 

Then add the value class =”f-f-monospace” 

 

Text Align 

 

|   

| <p class="t_a_center">Hello</p> 

| 

 

__ t represent text and a define align and then add center (value) class = “t_a_center” 

 

Text Decoration 

 

|   

| <p class="t_d_underline”>Hello</p> 

| 

 

__ t represent text and d define decoration then add the value class = “t_d_underline” 

 

 

 

Text Transform 

|   

| <p class="t_t_uppercase>Hello</p> 

| 

 

__ t is text and the other one is transform and then the value 

Class = “t_t_uppercase” 

 

12. Line Height 

 

|   

| <p class="l_h_10_vw">Hello</p> 

| 

 

__ l is line  

__ h is height 

__ 10 is value 

__ vw is css unit type 

__ class = “l_h_10_vw” 

 

13. Letter Spacing 

|   

| <p class="l_s_10_vw">Hello</p> 

| 

 

__ l means letter and s for spacing and 10 is value and vw is css unit class = “l_s_10_vw” 

14.  Word Spacing 

|   

| <p class="w_s_10_vw">Hello</p> 

| 

 

__w means word and s for spacing and 10 is value and vw is css unit class = “l_s_10_vw” 

 

15. White Space 

|   

| <p class="wh_s_nowrap">Hello</p> 

| 

 

__ wh stands for white and s for spacing and nowrap is the value class=”wh_s_nowrap” 

 

16. Overflow 

|   

| <p class="of_hidden">Hello</p> 

| 

 

__ of is for overflow and hidden is the value class=”of-hidden” 

 

17. Text Overflow 

|   

| <p class="t_of_ellipsis">Hello</p> 

| 

__ t is for text and of overflow and ellipsis is the value class=”t_of_ellipsis” 

18. Max Height && Max Width 

|   

| <p class="m_h_10_px">Hello</p> 

| 

| <p class="m_w_20_vw">Hello</p> 

| 

 

__First One is  m for max and h for height and 10 is the value and px is the css unit type 

 

__Second one is the same but for Max Width 

 

19. Min Height && Min Width 

|   

| <p class="mi_h_10_px">Hello</p> 

| 

| <p class="mi_w_20_vw">Hello</p> 

| 

 

__ First one is Min (mi) then h for height and value then css unit 

__  Second is  the same but for min width  

 

20. Margin 

Definition: Margin is the space outside an element’s border. It creates distance between the element and its neighbors. 

Syntax: 

css 

margin: 20px;        /* all sides */ 
margin-top: 10px;    /* only top */ 
margin-left: 5rem;   /* only left */ 
margin: 10px 20px;   /* vertical | horizontal */ 
 

Example: 

html 

<p class="m_top_20_px">Hello</p> 
 

→ Adds 20px space above the paragraph. 

21. Padding 

Definition: Padding is the space inside an element’s border, between the border and the content. 

Syntax: 

css 

padding: 15px;        /* all sides */ 
padding-bottom: 10px; /* only bottom */ 
padding: 10px 20px;   /* vertical | horizontal */ 
 

Example: 

html 

<div class="p_all_10_px">Hello</div> 
 

→ Adds 10px space inside the box around the text. 

22. Border 

Definition: Border is the line drawn around the padding and content of an element. 

Syntax: 

css 

border: 2px solid red; 
border-top: 1px dashed blue; 
 

Example: 

html 

<div class="b_2px_solid_red">Hello</div> 
 

→ Creates a red border, 2px thick, solid style. 

🟢 Border-Radius 

Definition: Border-radius controls the curvature of the corners of an element. 

Syntax: 

css 

border-radius: 10px;   /* rounded corners */ 
border-radius: 50%;    /* perfect circle if width=height */ 
 

Example: 

html 

<div class="br_10_px">Hello</div> 
 

→ Rounds the corners by 10px. 

23. Box-Shadow 

Definition: Box-shadow adds a shadow effect behind an element’s box. 

Syntax: 

css 

box-shadow: 2px 4px 6px gray; 
 

2px → horizontal offset 

4px → vertical offset 

6px → blur radius 

gray → shadow color 

Example: 

html 

<div class="bs_2px_4px_6px_gray">Hello</div> 
 

→ Adds a gray shadow offset by 2px right, 4px down, blurred 6px. 

24. Box-Sizing 

Definition: Box-sizing defines how the browser calculates the element’s total width and height. 

Values: 

content-box → default; width/height apply only to content, padding and border are added outside. 

border-box → width/height include content, padding, and border. 

Syntax: 

css 

box-sizing: border-box; 
 

Example: 

html 

<div class="bx_sz_border-box">Hello</div> 
 

→ Ensures padding and border are included in the element’s total size. 

 

25.Background Image 

Definition: Sets an image as the background of an element. 

Class Pattern: bg_img_<url> 

Example: 

html 

<div class="bg_img_https://example.com/bg.png">Hello</div> 
 

→ Applies the image as background. 

26.Background Repeat 

Definition: Controls if/how the background image repeats. 

Class Pattern: bg_rep_<value> 

Values: repeat, no-repeat, repeat-x, repeat-y. 

Example: 

html 

<div class="bg_rep_no-repeat">Hello</div> 
 

→ Background image shown once, no repetition. 

27.Background Size 

Definition: Defines how the background image is scaled. 

Class Pattern: bg_sz_<value> 

Values: cover, contain, auto, or custom sizes (100% auto). 

Example: 

html 

<div class="bg_sz_cover">Hello</div> 
 

→ Image covers the entire element. 

28.Background Position 

Definition: Sets the starting position of the background image. 

Class Pattern: bg_pos_<value> 

Values: center, top left, bottom right, etc. 

Example: 

html 

<div class="bg_pos_top_left">Hello</div> 
 

→ Image positioned at the top-left corner. 

29.Background Attachment 

Definition: Determines if the background scrolls with the page or stays fixed. 

Class Pattern: bg_att_<value> 

Values: scroll, fixed, local. 

Example: 

html 

<div class="bg_att_fixed">Hello</div> 
 

→ Background stays fixed when scrolling. 

30.Background Clip 

Definition: Defines how far the background extends (border, padding, or content box). 

Class Pattern: bg_clip_<value> 

Values: border-box, padding-box, content-box, text. 

Example: 

html 

<div class="bg_clip_content-box">Hello</div> 
 

→ Background only inside the content box. 

31.Background Origin 

Definition: Sets the origin area for background positioning. 

Class Pattern: bg_org_<value> 

Values: border-box, padding-box, content-box. 

Example: 

html 

<div class="bg_org_padding-box">Hello</div> 
 

→ Background positioned relative to padding box. 

32.Background Linear Gradient 

Definition: Creates a smooth transition between colors in a straight line. 

Class Pattern: bg_lin_grad_<direction>_<color1>_<color2> 

Example: 

html 

<div class="bg_lin_grad_to_right_red_blue">Hello</div> 
 

→ Gradient from red to blue, left → right. 

33.Background Radial Gradient 

Definition: Colors radiate outward from a center point. 

Class Pattern: bg_rad_grad_<shape>_<color1>_<color2> 

Example: 

html 

<div class="bg_rad_grad_circle_red_blue">Hello</div> 
 

→ Circular gradient from red at center to blue at edges. 

34.Background Conic Gradient 

Definition: Colors rotate around a center point like a pie chart. 

Class Pattern: bg_con_grad_<position>_<color1>_<color2> 

Example: 

html 

<div class="bg_con_grad_at_center_red_blue">Hello</div> 
 

→ Conic gradient centered, red to blue rotation. 

 

 

35.Display 

Definition: Controls how an element is displayed in the layout. 

Class Pattern: d_<value> 

Values: block, inline, inline-block, flex, grid, none. 

Example: 

html 

<div class="d_flex">Hello</div> 
 

→ Displays the element as a flex container. 

36.Position 

Definition: Specifies how an element is positioned in the document. 

Class Pattern: pos_<value> 

Values: static (default), relative, absolute, fixed, sticky. 

Example: 

html 

<div class="pos_absolute">Hello</div> 
 

→ Positions the element absolutely relative to its nearest positioned ancestor. 

37.Visibility 

Definition: Controls whether an element is visible or hidden, but still takes up space. 

Class Pattern: vis_<value> 

Values: visible, hidden, collapse. 

Example: 

html 

<p class="vis_hidden">Hello</p> 
 

→ Text is hidden but the space remains. 

38.Float 

Definition: Moves an element to the left or right, allowing text/content to wrap around it. 

Class Pattern: fl_<value> 

Values: left, right, none. 

Example: 

html 

<img src="pic.jpg" class="fl_left"> 
 

→ Image floats to the left, text flows around it. 

39.Clear 

Definition: Controls how elements behave next to floated elements. 

Class Pattern: cl_<value> 

Values: left, right, both, none. 

Example: 

html 

<div class="cl_both">Hello</div> 
 

→ Prevents the element from sitting next to floated elements on either side. 

40.Z-index 

Definition: Controls the stack order of elements (which one appears on top). 

Class Pattern: z_<number> 

Values: Any integer (0, 10, 100, etc.). Higher values appear above lower ones. 

Example: 

html 

<div class="z_100">Hello</div> 
 

→ Element is layered above others with lower z-index. 

41.Flex 

Definition: Turns an element into a flex container. 

Class Pattern: flex 

Example: 

html 

<div class="flex">...</div> 
 

→ Children are laid out using flexbox. 

42.Flex Direction 

Definition: Defines the direction of flex items in the container. 

Class Pattern: flex_dir_<value> 

Values: row, row-reverse, column, column-reverse. 

Example: 

html 

<div class="flex flex_dir_column">...</div> 
 

→ Items stacked vertically. 

43.Justify Content 

Definition: Aligns items along the main axis. 

Class Pattern: jc_<value> 

Values: flex-start, flex-end, center, space-between, space-around, space-evenly. 

Example: 

html 

<div class="flex jc_space-between">...</div> 
 

→ Items spread out with space between. 

44.Gap 

Definition: Sets spacing between flex/grid items. 

Class Pattern: gap_<value>_<unit> 

Example: 

html 

<div class="flex gap_20_px">...</div> 
 

→ 20px gap between items. 

45.Align Items 

Definition: Aligns items along the cross axis. 

Class Pattern: ai_<value> 

Values: stretch, flex-start, flex-end, center, baseline. 

Example: 

html 

<div class="flex ai_center">...</div> 
 

→ Items centered vertically. 

46.Align Content 

Definition: Aligns multiple flex lines (when wrapping). 

Class Pattern: ac_<value> 

Values: stretch, flex-start, flex-end, center, space-between, space-around. 

Example: 

html 

<div class="flex fw_wrap ac_center">...</div> 
 

→ Lines centered in container. 

47.Flex Wrap 

Definition: Controls whether flex items wrap onto multiple lines. 

Class Pattern: fw_<value> 

Values: nowrap, wrap, wrap-reverse. 

Example: 

html 

<div class="flex fw_wrap">...</div> 
 

→ Items wrap to new lines if needed. 

48.Align Self 

Definition: Overrides align-items for a single flex item. 

Class Pattern: as_<value> 

Values: auto, flex-start, flex-end, center, stretch, baseline. 

Example: 

html 

<div class="flex"> 
  <div class="as_flex-end">Item</div> 
</div> 
 

→ That item aligns to the bottom. 

 

49.Grid Utilities 

grid → Turns an element into a grid container (display: grid). 

g_tc_1fr_2fr_100px → Sets grid-template-columns: 1fr 2fr 100px. 

g_tr_100px_auto_1fr → Sets grid-template-rows: 100px auto 1fr. 

g_ar_100px → Sets grid-auto-rows: 100px. 

g_ac_200px → Sets grid-auto-columns: 200px. 

g_col_1_3 → Places item from column line 1 to 3 (grid-column: 1 / 3). 

g_row_2_4 → Places item from row line 2 to 4 (grid-row: 2 / 4). 

j_items_center → Aligns items horizontally (justify-items: center). 

p_items_center → Aligns items both horizontally and vertically (place-items: center). 

50. Transition Utilities 

tr_opacity_300ms_ease_0ms → Smoothly changes opacity over 300ms with ease timing. 

Ready transitions (10): 

tr_fast → 150ms ease 

tr_medium → 300ms ease 

tr_slow → 600ms ease 

tr_bounce → springy bounce effect 

tr_fade → opacity transition 

tr_slide → transform slide 

tr_color → text color transition 

tr_bg → background-color transition 

tr_shadow → box-shadow transition 

tr_scale → scaling transition 

51. Animation Utilities 

anim_td_fade_in_600ms_ease_1 → Fades in over 600ms, ease timing, 1 iteration. 

Ready animations (10): 

td_fade_in → fade in 

td_fade_out → fade out 

td_slide_up → slide upward 

td_slide_down → slide downward 

td_slide_left → slide left 

td_slide_right → slide right 

td_zoom_in → zoom in 

td_zoom_out → zoom out 

td_bounce → bounce effect 

td_spin → full rotation 

52. Pseudo-Classes & Pseudo-Elements 

Hover: hov_bg_c_red (red background on hover), hov_opacity_0_6 (opacity 0.6 on hover). 

Active: act_opacity_0_6 → opacity when clicked. 

Visited: vis_c_blue → visited link turns blue. 

Focus: foc_b_2px_solid_blue → blue border on focus. 

Disabled: dis_opacity_0_5 → faded disabled element. 

First letter: fl_first-letter → styles the first letter. 

Before/After: bf_before, af_after → insert content via data-before and data-after. 

53. CSS Variables 

:root { --name: red; --primary: #4f46e5; --radius: 8px; } 

Usage: 

use_var_bg → background: var(--name) 

use_var_color → color: var(--primary) 

use_var_radius → border-radius: var(--radius) 

🔧54.Transform Utilities 

tf_t_x_10px_y_20px → translate by 10px X, 20px Y. 

tf_r_45deg → rotate 45 degrees. 

tf_s_1_2 → scale X=1, Y=2. 

tf_sk_10deg_5deg → skew 10° X, 5° Y. 

tf_o_center_center → transform origin at center. 

55.Filter Utilities 

flt_blur_4px → blur by 4px. 

flt_brightness_120% → increase brightness. 

flt_contrast_110% → increase contrast. 

flt_grayscale_100% → grayscale effect. 

flt_hue_90deg → hue rotation. 

flt_invert_100% → invert colors. 

flt_opacity_60% → opacity filter. 

flt_saturate_150% → increase saturation. 

flt_sepia_80% → sepia tone. 

56. Responsive Utilities 

Visibility: 

sm_hidden → hidden on small screens 

md_block → block on medium screens 

lg_block → block on large screens 

Font sizes: 

sm_f_s_14 → 14px on small 

md_f_s_16 → 16px on medium 

lg_f_s_18 → 18px on large 

57. Shapes (10+) 

shape_circle → circle 

shape_ellipse → ellipse 

shape_triangle_up → upward triangle 

shape_triangle_right → right-pointing triangle 

shape_square → square 

shape_rectangle → rectangle 

shape_pentagon → pentagon 

shape_hexagon → hexagon 

shape_star → star 

shape_cross → cross 

shape_diamond → diamond 

shape_parallelogram → parallelogram 
