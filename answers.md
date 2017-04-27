1) Replace the profile image!

var image = $("img.profile-image");
image.replaceWith("<img src='https://placebear.com/400/400'>");

ALSO 1?) Replace.... THE SKY.

var image = $('img[src="images/clouds-man.jpg"]');
<!-- (not sure if this selection is actually correct, but it DOES select the appropriate image...) -->
image.replaceWith("<img src='https://placebear.com/325/225'>");
<!-- MOAR BEAR. -->

2) Change the title!

var headline = $("h1.highlight");
headline.text("Lolbuttslol");
<!-- Yes, I am very mature. -->

3) Change 'Employment'!

var headline = $("#employment h3");
headline.text("Lolbuttslol");
<!-- Still mature. -->

4) No more Time Travel!

var edit = $("#time-travel").parent();
edit.remove();

5) Work that body... Colour-wise.

var body = $('body');
body.css("color", "blue");
<!-- Note: NON-CANADA SPELLING FOR 'COLOUR' -->

6) Change them highlights, gurl.

var high = $(".highlight");
high.css("color", "yellow");

7) Make it mono...space.

var font = $("h1");
font.css("font-family", "monospace");

8) Change the circles.

var icon = $("p.action-icon");
icon.css("color", "red");
<!-- Doesn't seem to produce a discernible change, but the change is showing in the inspector... -->

9) Change form placeholder! IDENTIFY YOURSELF.

var butts = $("input#name");
butts.attr("placeholder", "Identify Yourself!");

10) Change message placeholder! STATE YOUR BUSINESS.

var butts = $("textarea#message");
butts.attr("placeholder", "State your business!");

11) Adding the NEMESIS VALUE.

var butts = $("input#name");
butts.attr("value", "Your Nemesis");

12) Adding Koalamail!

var butts = $("input#email");
butts.attr("value", "koalathebear@gmail.com");

13) SWORDFIGHT BUTTON.

var butts = $("input#submit");
butts.attr("value", "EN GARDE!");

<!-- Will ADD ELEMENTS later. For now, let's commit this shiz. -->
