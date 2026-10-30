Image with alt.html?

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Developer Portfolio</title>
</head>
<body>
    <header>
        <h1>Ankit - Web Developer Portfolio</h1>
    </header>
    
    <main>
        <!-- Profile Section -->
        <section>
            <h2>About Me</h2>
            <img src="images/profile-pic.jpg" width="150" height="150" alt="Priya Verma smiling while working on a laptop in a bright office">
            <p>Hello! I am a passionate front-end developer building modern and accessible web applications.</p>
        </section>

        <!-- Projects Section -->
        <section>
            <h2>Featured Projects</h2>
            <figure>
                <img src="images/weather-app.jpg" width="400" height="250" alt="Interface of the Weather Forecasting app showing live temperature and 5-day forecast">
                <figcaption>Weather Forecast Web App</figcaption>
            </figure>
        </section>

        <!-- Social / Linked Image Section -->
        <section>
            <h2>Connect with Me</h2>
            <a href="https://linkedin.com/">
                <img src="images/linkedin-icon.png" width="50" height="50" alt="Visit Ankit LinkedIn Profile">
            </a>
        </section>
    </main>
</body>
</html>

Explanation:

1.HTML5 Boilerplate & Structure (<!DOCTYPE html>, <html>, <head>, <body>):
  • Yeh kisi bhi web page ka basic structure banata hai. Isme <meta charset="UTF-8"> text encoding ke liye aur <meta name="viewport"> mobile responsiveness ke liye use hota hai.
2.Semantic Tags (<header>, <main>, <section>, <figure>):
  • In tags ka use karke code ko zyada readable aur structured banaya jata hai taaki screen readers aur search engines ko page ka layout achhi tarah samajh aaye.
3.Accessible alt Attributes in Images (<img>):
  • Profile Image: Isme alt text batata hai ki image kis cheez ki hai aur user kya kar raha hai.  
  • Project Image: Yeh user ko project ke interface ke baare mein detail deta hai bina "image of..." likhe.  
  • Linked Image: Jab koi image kisi link (<a>) ke andar hoti hai, toh alt text hamesha yeh batata hai ki us link par click karne se user kahan pahuchega (jaise “Visit Ankit LinkedIn Profile”).  
