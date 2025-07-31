+++
title = ""
render = true
template = "about.html"
+++

**Stay informed. Get involved.** \
\
Do you live in Beacon Hill, Seattle? \
\
Do you want updates about neighborhood news, community events, and opportunities to get involved? \
\
**Sign up!** \
\
Every one has a role to play in building this community. Let us know if you have particular interests or expertise and we’ll do our best to follow up and plug you in!

<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="contact form example">
  <title>Contact Form Example</title>

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/purecss@3.0.0/build/pure-min.css" integrity="sha384-X38yfunGUhNzHpBaEBsWLO+A0HDYOQi8ufWDkZ0k9e0eXz/tH3II7uKZ9msv++Ls" crossorigin="anonymous">

</head>

<body>
  <!-- <h2 class="content-head is-center">Contact Us!</h2> -->
  <aside>
       <p>
          <!--  We would <em>love</em> to hear from you! </p> -->
           <p>Please use the <b><em>Contact Form</em></b>
           to send us a message.
       </p>
   </aside>

<!-- START HERE -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/purecss@3.0.0/build/pure-min.css" 
integrity="sha384-X38yfunGUhNzHpBaEBsWLO+A0HDYOQi8ufWDkZ0k9e0eXz/tH3II7uKZ9msv++Ls" crossorigin="anonymous">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">

   <!-- Style The Contact Form How Ever You Prefer -->
 <link rel="stylesheet" href="style.css">

  <form class="gform pure-form pure-form-stacked" method="POST" data-email="example@email.net"
  action="https://script.google.com/macros/s/AKfycbzxFPzo_BroXFUH18UWW1r3K2L7wlfqMyUd-zuBLysy30jjhiPfGyvCHgfOHSe7RTxK/exec">
    <!-- change the form action to your script url -->

<div class="form-elements">
    <fieldset class="pure-group">
        <label for="name"> <b>Name:</b> </label>
        <input id="name" name="name" placeholder="Waylon Joseph Smithers, Jr." />
        </fieldset>

<fieldset class="pure-group">
    <label for="message"> <b>Message:</b> </label>
    <textarea id="message" name="message" rows="10"
    placeholder="Tell us what's on your mind..."></textarea>
</fieldset>

<fieldset class="pure-group">
    <label for="email"> <b>Email Address: </b> </label>
    <input id="email" name="email" type="email" value=""
    required placeholder="burns.charles@nuke.com"/>
</fieldset>

<fieldset class="pure-group honeypot-field">
    <label for="honeypot">To help avoid spam, utilize a Honeypot technique with a hidden text field; must be empty to submit the form! Otherwise, we assume the user is a spam bot.</label>
    <input id="honeypot" type="text" name="honeypot" value="" />
</fieldset>

<button class="button-success pure-button button-xlarge">
    <i class="fa fa-paper-plane"></i>&nbsp;Send</button>
</div>

<!-- Customise the Thankyou Message People See when they submit the form: -->
<div class="thankyou_message" style="display:none;">
<h2><em>Thanks</em> for contacting us!
We will get back to you soon!</h2>
</div>

</form>

<!-- Submit the Form to Google Using "AJAX" -->
<script data-cfasync="false" src="form-submission-handler.js"></script>
<!-- END -->

</body>
</html>
