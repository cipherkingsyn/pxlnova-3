<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>proxy-generator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin: 20px;
        }
        a {
            display: block;
            margin-top: 20px;
            font-size: 18px;
            color: #007bff;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <h1>Click the Button to Get a Random Link!</h1>
    
    <button onclick="generateRandomLink()">Get Random Link</button>

    <a id="random-link" href="#" target="_blank" style="display:none;">Click Here to Visit the pxlnova link</a>

    <script>
        function generateRandomLink() {
            const links = [
                "https://pxlnova-b8z.pages.dev",
                "https://pxlnova11.pages.dev",
                "https://pxlnova4-emp.pages.dev",
                "https://pxlnovaea2.pages.dev",
                "https://canvas-90c.pages.dev",
                "https://i-know-were-you-live.pages.dev",
                "https://clever1.pages.dev",
                "https://pxlnovae.pages.dev",
                "https://skibdi.pages.dev",
                "https://pxlnova3.pages.dev",
                "https://pxlnova4.pages.dev/",
                "https://pxlnova2.pages.dev/",
                "https://pxlnova-keb.pages.dev/",
                "https://stitch-is-in-this-website.pages.dev/",
                "https://pxlnova223.pages.dev/",
                "https://pxlnova-biggychees.pages.dev/",
                "https://pxlnova22.pages.dev/",
                "https://ding-dong-eat-em-up.pages.dev/",
                "https://new-algebra.pages.dev/",
                "https://pxlnova2-lll.pages.dev/",
                "https://teacher-dont-giv-me-detention.pages.dev/",
                "https://youlikefart.pages.dev/",
                "https://vaderhopethisworks.pages.dev/",
                "https://pxlnova-6.pages.dev/",
                "https://pxlnova-8.pages.dev/",
                "https://pxlnova-3.pages.dev/"
            ];

            const randomLink = links[Math.floor(Math.random() * links.length)];

        
            const linkElement = document.getElementById("random-link");
            linkElement.href = randomLink;
            linkElement.style.display = "block";
            linkElement.textContent = `Click Here to Visit: ${randomLink}`;
        }
    </script>

</body>
</html>

#### credits

* [szvy - original search files from her](https://github.com/szvy)
* [TIW - original code came from them](https://github.com/KwazyMotoo/TIW-Static)
* [UV - original code also came from them](https://github.com/titaniumnetwork-dev/Ultraviolet-App)
