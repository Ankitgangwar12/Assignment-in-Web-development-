debug.buggy.html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Debugged Page - HTML &amp; CSS course assignment">
    <title>Debugged Page</title>
</head>
<body>
    <h1>My Hobbies</h1>
    <p>I like <b>cricket and <i>music</i></b>.</p>
    <img src="photo.jpg" alt="Me playing cricket" width="200">
    <p><a href="https://www.google.com">Search</a></p>
    
    <ul>
        <li>Reading</li>
        <li>Coding</li>
    </ul>

    <table border="1">
        <thead>
            <tr><th>Name</th><th>Age</th></tr>
        </thead>
        <tbody>
            <tr><td>Aarav</td><td>20</td></tr>
        </tbody>
    </table>

    <p>Footer text</p>
</body>
</html>

Code Explanation:

1. Missing <!DOCTYPE html> aur lang attribute:
Yeh HTML5 ka standard declaration hai jo browser ko batata hai ki page kis version me likha hai. lang="en" browser aur screen readers ko page ki language (English) batane ke liye zaroori hota hai.  
2. Missing <meta charset>:
Yeh tag browser ko character encoding (UTF-8) batata hai taaki special characters aur text bina kisi error ke properly display ho sakein.  
3. Unclosed <title>:
<title> tag ko </title> se band karna zaroori hota hai, warna browser ka title bar theek se kaam nahi karta.  
4. Mismatched Heading Tags:
Code me <h1> ko </h2> se close kar diya gaya tha, jo ki rule ke khilaaf hai. Jo tag open ho, wahi closing tag hona chahiye (<h1>...</h1>).  
5. Unclosed <p>:
Paragraph tag ko bina close kiye chhod diya gaya tha, jise </p> se properly band kiya gaya.  
6. Improperly nested <b> aur <i>:
HTML nesting me "Last In, First Out" rule lagta hai. Agar <b> pehle khula aur <i> uske andar khula, toh pehle <i> close hoga aur baad me <b> close hoga (<b>...<i>...</i></b>).  
7. Missing alt attribute:
<img> tag me alt (alternative text) attribute hona zaroori hai taaki agar image load na ho ya screen reader use ho, toh wahan text dikh sake.  
8. Invalid href attribute:
Anchor tag (<a>) ke andar URL bina double quotes ke aur bina https:// protocol ke likha tha, jise theek karke standard format banaya gaya.  
9. Unclosed <ul> / Stray <ol>:
Unordered list (<ul>) ko close kiye bina beech me achanak se ordered list (<ol>) khol di gayi thi, jise fix kiya gaya.  
10. Unclosed <li> items:
List items ko </li> se close karna coding ki ek achhi practice hai taaki structure clean rahe.  
11. Table structure issues:
Table ke andar rows aur cells (<td>/<th>) theek se close nahi the aur <thead>/<tbody> semantic tags gayab the, jise proper table structure me dala gaya.  
12. Stray </div> tag:
Code me ek extra closing </div> tha jiska koi opening <div> upar nahi khula tha, isliye use hata diya gaya.  
