+++
title = ""
render = true
template = "about.html"
+++

**Stay informed. Get involved.** \
\
Do you live in Beacon Hill, Seattle, WA? \
\
Do you want updates about neighborhood news, community events, and opportunities to get involved? \
\
**Sign up!** \
\
Every one has a role to play in building this community. Let us know if you have particular interests or expertise and we’ll do our best to follow up and plug you in! Please contact us at [beaconhillsolidarity@proton.me](mailto:beaconhillsolidarity@proton.me).

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
</head>
<body>
    <h1>Contact Us</h1>
    <form action="/submit-contact-form" method="POST">
        <p>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="user_name" required>
        </p>
        <p>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="user_email" required>
        </p>
        <p>
            <label for="message">Message:</label><br>
            <textarea id="message" name="user_message" rows="5" required></textarea>
        </p>
        <p>
            <button type="submit">Send Message</button>
        </p>
    </form>
</body>
</html>

