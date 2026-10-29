Semantic html Code?

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Resume - Aarav Sharma (Semantic) - HTML & CSS course assignment">
    <title>Resume - Aarav Sharma (Semantic)</title>
</head>
<body>
    <header>
        <h1>Aarav Sharma</h1>
        <p>Aspiring Web Developer</p>
        <address>
            Meerut, Uttar Pradesh, India<br>
            <a href="mailto:aarav@example.com">aarav@example.com</a> | <a href="tel:+919000000000">+91 90000 00000</a>
        </address>
    </header>

    <main>
        <section id="objective">
            <h2>Objective</h2>
            <p>Motivated student seeking an entry-level <strong>front-end developer</strong> role.</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <article>
                <h3>B.Tech in Computer Science</h3>
                <p>ABC Institute of Technology &middot; <time datetime="2023">2023</time> - <time datetime="2027">2027</time></p>
            </article>
            <article>
                <h3>Senior Secondary (XII)</h3>
                <p>City Public School &middot; 84%</p>
            </article>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>Git &amp; GitHub</li>
                <li>VS Code</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <article>
                <h3>Personal Portfolio</h3>
                <p>Multi-page website using semantic HTML and responsive CSS.</p>
            </article>
            <article>
                <h3>Student Registration Form</h3>
                <p>Form using all common HTML input types.</p>
            </article>
        </section>
    </main>

    <footer>
        <p><small>I hereby declare that the above information is true.</small></p>
    </footer>
</body>
</html>
 Code Explanation:

• Document Type aur Structure (<!DOCTYPE html> & <html>): Yeh browser ko batata hai ki yeh ek modern HTML5 document hai. lang="en" attribute webpage ki primary language English set karta hai.
• <head> aur Meta Tags: Isme webpage ki metadata hoti hai, jaise character encoding (UTF-8), mobile responsiveness ke liye viewport settings, aur <title> jo browser tab me show hota hai.
• <header> Tag: Yeh section resume ke top par user ki basic details (jaise naam, designation, aur contact info) ko represent karta hai. Contact details ke liye <address> tag ka use kiya gaya hai.
• <main> Tag: Yeh web page ka main container hota hai jo resume ke saare core sections ko wrap karta hai.
• Semantic Elements (<section> aur <article>):
<section> tags ka use alag-alag thematic parts (jaise objective, education, skills, aur projects) ko divide karne ke liye kiya gaya hai.
<article> tags ka use self-contained content (jaise individual degree details ya project details) ke liye kiya gaya hai.
• <time> Tag: Yeh dates (datetime="2023") ko machine-readable format me represent karne ke liye use hota hai.
• <footer> Tag: Yeh resume ke bottom part ko define karta hai jisme declaration message diya gaya hai.