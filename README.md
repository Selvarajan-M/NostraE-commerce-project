# Nostra E-commerce

Nostra is a modern and stylish e-commerce platform built with HTML, CSS, and JavaScript. The project includes multiple pages such as home, collection, and contact, each designed to provide an optimal user experience.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [HTML Code](#html-code)
- [CSS Code](#css-code)
- [JavaScript Code](#javascript-code)
- [Contact](#contact)

## Introduction
Nostra E-commerce is designed to offer a seamless shopping experience with a focus on modern design and ease of use. It features a home page, a collection page showcasing products, and a contact page for customer inquiries.

## Features
- **Responsive Design**: Adapts to various screen sizes for a consistent user experience.
- **Navigation**: Easy navigation with a navbar and side navbar.
- **Product Showcase**: Displays new arrivals and most wanted products.
- **Newsletter Subscription**: Users can subscribe to the newsletter for exclusive discounts and updates.
- **Social Media Links**: Connect with users through social media icons in the footer.

## Getting Started
1. Clone the repository from GitHub.
2. Ensure you have an HTML viewer or a web browser to open the `index.html` file.
3. Open `index.html` in your preferred browser to explore the Nostra E-commerce platform.

## Usage
- **Home Page**: Showcases the latest products and services.
- **Collections Page**: Displays a curated list of products.
- **Contact Page**: Provides a form for users to reach out with inquiries.

## HTML Code
### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!--google font-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!--link my css-->
    <link rel="stylesheet" href="style.css">
    <!--font Awesome icons-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <!--Navbar-->
    <nav class="navbar">
        <h1>Nostra</h1>

        <div class="navbar-links">
            <p class="navbar-link"><a href="index.html">Home</a></p>
            <p class="navbar-link"><a href="collection.html">Collections</a></p>
            <p class="navbar-link"><a href="contact.html">Contact</a></p>
        </div>
        <div class="navbar-menu-toggle" onclick="showNavbar()">
            <i class="fa-solid fa-bars"></i>
        </div>
    </nav>
    <!--side navbar-->
    <div class="side-navbar">
        <p style="text-align: right;" onclick="closeNavbar()">
            <i class="fa-solid fa-xmark"></i>
        </p>
    
        <div class="side-navbar-links">
            <p class="side-navbar-link"><a href="index.html">Home</a></p>
            <p class="side-navbar-link"><a href="collection.html">Collections</a></p>
            <p class="side-navbar-link"><a href="contact.html">Contact</a></p>
        </div>
    </div>
    <!--Header-->
    <div class="header">
       <div>
        <h1>Level up your style</h1>
        <p> with our stunning Collection</p>
        <button class="header-button">Shop now</button>
       </div>
       <div>
        <img class="header-img" width="300" height="300" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\fashion.jpg">
       </div>
    </div>
    <!--Service-->
    <div class="service">
        <div class="service-container-1">
            <div>
                <h2>We Provide Best</h2>
                <h2>Customer Experience</h2>
            </div>
            <div>
                <p>|| we ensure that our customers have the best shopping experience</p>
            </div>
        </div>
    </div>
    <div class="service-container-2">
        <div>
            <i class="fa-regular fa-face-smile"></i>
            <h4>Satisfaction Guarantee</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus modi nesciunt beatae repellat quae! Ad?</p>
        </div>
        <div>
            <i class="fa-regular fa-face-smile"></i>
            <h4>New Arrival EveryDay</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus modi nesciunt beatae repellat quae! Ad?</p>
        </div>
        <div>
            <i class="fa-regular fa-face-smile"></i>
            <h4>Fast & Free shipping </h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus modi nesciunt beatae repellat quae! Ad?</p>
        </div>
    </div>
    
    <div><h2 style="padding:20px">New Arrival</h2></div>
    
    <div class="new-arrival">
        <div class="new-arrival-container">
            <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new1.avif">
            <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
        </div>
        <div class="new-arrival">
            <div class="new-arrival-container">
                <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new2.avif">
                <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
            </div>
        </div>
        <div class="new-arrival">
            <div class="new-arrival-container">
                <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new3.avif">
                <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
            </div>
        </div>
        <div class="new-arrival">
            <div class="new-arrival-container">
                <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new4.avif">
                <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
            </div>
        </div>
    </div>
    <div><h2 style="padding:20px">Most Wanted</h2></div>
    
    <div class="new-arrival">
        <div class="new-arrival-container">
            <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new1.avif">
            <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
        </div>
        <div class="new-arrival">
            <div class="new-arrival-container">
                <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new2.avif">
                <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
            </div>
        </div>
        <div class="new-arrival">
            <div class="new-arrival-container">
                <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new3.avif">
                <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
            </div>
        </div>
        <div class="new-arrival">
            <div class="new-arrival-container">
                <img width="200" height="200" src="C:\Users\ELCOT\Desktop\Nostra E-commerce\new4.avif">
                <button>Shop now <i class="fa-solid fa-arrow-right"></i></button>
            </div>
        </div>
    </div>
    <!--News-->
    <div class="news">
        <h2>Join our Newsletter</h2>
        <p
