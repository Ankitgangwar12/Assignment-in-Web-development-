personal introduction html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Hi, I'm Aarav - Personal Introduction - HTML & CSS course assignment">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hi, I'm Aarav - Personal Introduction</title>
</head>
<body>
    <header>
        <h1>Hi, I'm Aarav Sharma 👋</h1>
        <p><em>Web development student &bull; Cricket fan &bull; Coffee lover</em></p>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>I am a second-year computer-science student from Meerut. I enjoy building things for the web and am currently learning HTML and CSS.</p>
        </section>

        <section>
            <h2>Quick Facts</h2>
            <ul>
                <li><strong>Age:</strong> 20</li>
                <li><strong>City:</strong> Meerut, India</li>
                <li><strong>Languages:</strong> Hindi, English</li>
            </ul>
        </section>

        <section>
            <h2>My Goals</h2>
            <ol>
                <li>Finish the HTML &amp; CSS course.</li>
                <li>Build and deploy five real websites.</li>
                <li>Learn JavaScript and land a front-end internship.</li>
            </ol>
        </section>

        <section>
            <h2>Contact</h2>
            <p>Email me at <a href="mailto:aarav@example.com">aarav@example.com</a>.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Aarav Sharma</p>
    </footer>
</body>
</html>

• <!DOCTYPE html> aur <html>: Yeh declaration browser ko batati hai ki yeh ek HTML5 document hai. <html lang="en"> root element hai jo webpage ki language English define karta hai.
• <head> Section: Iske andar webpage ki metadata information hoti hai:
• <meta charset="UTF-8">: Text encoding set karta hai taaki characters sahi display hon.
• <meta name="viewport">: Mobile devices par page ko responsive banane ke liye use hota hai.
• <title>: Yeh browser ke tab par page ka title dikhata hai.
• <body> Section: Yeh webpage ka main container hai jiske andar sara visible content hota hai.
• <header> Tag: Iska use top banner ya introductory section banane ke liye kiya gaya hai, jisme main heading (<h1>) aur ek paragraph (<p>) hai jisme text ko italics (<em>) kiya gaya hai.
• <main> Tag: Yeh page ke main content ko wrap karta hai jisme alag-alag <section> elements ka use kiya gaya hai:
About Me: Is section me student ke baare me general description di gayi hai.
Quick Facts: Yeh unordered list (<ul>) aur list items (<li>) ka use karke bullet points me basic details (Age, City, Languages) dikhata hai.
My Goals: Yeh ordered list (<ol>) ka use karke numbered list me goals ko represent karta hai.
Contact: Isme ek anchor tag (<a>) ka use kiya gaya hai jo mailto: attribute ke zariye direct email link provide karta hai.
• <footer> Tag: Yeh webpage ke sabse niche copyright info ya footer details dikhane ke liye use hota hai (&copy; symbol ke liye HTML entity hai).
