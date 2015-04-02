# Beginner-Code-for-HTML-and-CSS
A simple example on using HTML and CSS to imitate a given page



﻿<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <style>
        #wrapper {
            margin: 0 auto;
            max-width: 100%;
            width: 680px;
            background: white;
        }

        #lefthalf {
            background: #869C80;
            width: 680px;
            position: absolute;
            left: 0;
            top: 0;
            height: 100%;
        }

        .image {
            position: absolute;
            top: 0px;
            left: 0px;
            bottom: 2px;
            width: 680px;
            height: 99px;
        }

        h1 {
            position: absolute;
            left: 30px;
            top: 0px;
            width: 600px;
            color: #252f33;
            
            
            font-family: Georgia, serif;
        }

        .section {
            position: absolute;
            top: 147px;
            left: 0;
            bottom: 2px;
            height: 100px;
            width: 800px;
            line-height: 10px;
            padding-left: 21px;
            padding-top: 9px;
            padding-bottom: 15px;
            font-family: Verdana, Geneva, sans-serif;
            color: #2c4969;
        }

        .paragraph1 {
            position: absolute;
            top: 54px;
            left: 0;
            padding-left: 21px;
            padding-bottom: 13px;
            width: 800px;
            color: #101214;
            line-height: 10px;
            font-size: 13px;
            font-family: Arial, Helvetica, sans-serif;
        }

        .paragraph2 {
            position: absolute;
            top: 81px;
            left: 0;
            padding-left: 21px;
            padding-bottom: 13px;
            width: 800px;
            color: #101214;
            line-height: 10px;
            font-size: 13px;
            font-family: Arial, Helvetica, sans-serif;
        }

        .image2 {
            position: absolute;
            top: 98px;
            left: 0px;
            width: 100%;
        }

        nav {
            width: 680px;
            font-family: Arial, Helvetica, sans-serif;
            color: #252f33;
        }

            nav ul {
                list-style-type: none;
                width: 680px;
            }

                nav ul li {
                    float: left;
                   
                }

                    nav ul li a {
                        position: relative;
                        top: 83px;
                        font-weight: 600;
                        font-size: 14px;
                        color: black;
                        text-decoration: none;
                        text-align: center;
                        width: 90px;
                        height: 27px;
                        margin: 15px;
                        left: -40px;
                        display: block;
                        padding-top: 3px;
                        color: #252f33;
                    }
    </style>
    <meta charset="utf-8" />
    <title>HOMEWORK 3</title>
    </head>
<body>
    <div id="wrapper">
    <div id="lefthalf">
    <div class ="image">
        <img src="header.png" />
        <h1><b>A Blue Green Web Page</b></h1>
    </div>
    <div class ="image2">
        <img src="bar.png" />
    </div>
    <nav>
	    <ul>
	        <li><a href="X.html#Info">Info</a></li>
		    <li><a href="X.html#About">About</a></li>
		    <li><a href="X.html#Portfolio">Portfolio</a></li>
		    <li><a href="X.html#Services">Services</a></li>
		    <li><a href="X.html#Contact">Contact</a></li>
		</ul>
        
	</nav>
    </div>
        </div>
    <div class="section">
        <h2>The Article Title</h2>
        <div class="paragraph1">
        <p>You may use this template on any site, anywhere,</p></div>
        <div class="paragraph2">
    <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
        </div>
    </div>
	<noscript>
<div style="display: block; font-family: Verdana, Geneva, Arial; font-size: 10px">
The University of Southern California does not screen or control the content on this website and thus does not guarantee the accuracy, integrity, or quality of such content.  All content on this website is provided by and is the sole responsibility of the person from which such content originated, and such content does not necessarily reflect the opinions of the University administration or the Board of Trustees
</div>
</body>
    <noscript>
</html>
