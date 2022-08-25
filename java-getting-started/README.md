<html>
    <head>
    <style>
        body {
            background-color: hsl(0 0% 100%);
            color: hsl(0 0% 30%);
            background-image: url('https://img.wallpapersafari.com/desktop/1680/1050/20/36/fcCy7G.jpg');
            background-color: hsl(0 0% 100% / .6);
            background-blend-mode: screen;
        }
        h1 {
            width: fit-content;
            color: hsl(0 0% 0%);
            position: relative;
            overflow: hidden;
        }
        h1::before, h1::after {
            content: '';
            position: absolute;
            background: hsl(185 60% 65%);
            height: .1rem;
            width: 100%;
            inset: auto auto 0 0;
            border-radius: 100vmax;
            animation: slide 2.5s linear infinite;
        }
        h1::after {
            animation-delay: 2s;
        }
        @keyframes slide {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(100%);
            }
        }
    </style>
    </head>
    <body>
        <h1>Lab Report</h1>
        <p>
            I started by installing Eclipse as my IDE of choice, together with Maven and the Java SDK. I already had a Git client installed, so this step was skipped. My OS is Windows 11.
        <p>
        <p>
            I validated that these tools/programs were installed correctly by creating a Hello World program in Eclipse. I then used the windows terminal to run java -version and mvn -v to verify that these were installed and added to the PATH variable. Although I had some trouble remembering certain passwords, I encountered no technical issues during these steps.
        </p>
        <p>
            After initial setup I followed the link to create my Heroku account and started the java project tutorial. The steps here were quite straight forward and I followed along until the end, making sure everything worked as intended. I did break the project for a while by deleting the .git folder as I wanted to have all class projects as seperate folders in a single git repo, forgetting that Heroku relies upon the git repo in the specific projects. After fixing this everything worked as before.
        </p>
        <a href="https://salty-cove-57802.herokuapp.com">Heroku app link</a>
    </body>
</html>