+++
date = "2019-07-18T23:00:00+00:00"
description = "Pixaful website terms. These are NOT our terms of service"
featured_image = "/v1566910638/full-wax-main_ra3gw7.png"
webp_version = "/v1566910638/full-wax-main_ra3gw7.webp"
featured_image2 = "/v1566939500/full-wax-2_xwbcu4.jpg"
webp_version2 = "/v1566939500/full-wax-2_xwbcu4.webp"
v2title = "Responsive website development"
featured_image3 = "/v1566940098/full-wax-3_qpw1oq.jpg"
webp_version3 = "/v1566940098/full-wax-3_qpw1oq.webp"
v3title = "Mobile website development"
ogdescription = ""
ogimage = ""
ogtitle = ""
ogurl = ""
title = "Pixaful Terms"
twittercreator = ""
twitterdescription = ""
twitterimage = ""
twittersite = ""
twittertitle = ""
twitterurl = ""
layout = "terms"
draft = "true"



+++

<h2>Terms and conditions of use</h2>
<p><label><input type="checkbox" id="example1"> Are you sure?</label></p>
    <p class="conditional" data-condition="#example1">
        <label><input type="checkbox" name="example2"> Really super sure?</label>
    </p>
    <p class="conditional" data-condition="#example1 && example2">
        <label>Then type "yay": </label>
        <input type="text" name="yay" placeholder="yay">
    </p>
    <!-- This will be shown only if BOTH examle1 and examle2 are checked AND 'yay' typed in examle3 -->
    <p class="conditional msg" 
       data-condition="#example1 && example2 && yay == 'yay'">
        Both are selected and YAY is typed!
    </p>
    <p>
        <label>Pick two or three:</label>
        <select class="select" name="-example_5">
            <option>....</option>
            <option value="one">One!</option>
            <option value="two">Two!</option>
            <option value="three">Three!</option>
            <option value="four">Four!</option>
        </select>
    </p>
    <!-- NOTE: IE browsers do not support *.includes(...) function. 
        So on production, it is better to use (-example_5 == 'two') || (-example_5 == 'three') -->
    <div class="conditional msg" 
         data-condition="(-example_5 == 'two') || (-example_5 == '-example_5')">
        See?! It works with selects!
    </div>
</body>