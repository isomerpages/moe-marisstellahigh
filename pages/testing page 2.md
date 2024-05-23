---
title: testing page 2
permalink: /testing-page-2/
variant: markdown
description: ""
---





<title>Image Hover Text</title>
<style>
    .container {
        position: relative;
        display: inline-block;
    }

    .image {
        display: block;
        max-width: 100%;
        height: auto;
    }

    .overlay {
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        background-color: rgba(0, 0, 0, 0.7); /* Adjust opacity here */
        color: white;
        font-size: 100px;
        text-align: center;
        opacity: 0;
        transition: opacity 0.5s;
    }

    .container:hover .overlay {
        opacity: 1;
    }
</style>



<div class="container">
    <img alt="Your Image" src="https://onecms-res.cloudinary.com/image/upload/s--WC6sPN5R--/c_fill,g_auto,h_468,w_830/f_auto,q_auto/v1/cna-migration/maris-stella-data.jpg?itok=n2uDUVnD" class="image">
    <div class="overlay">
        <div class="text">MARIS STELLA HIGH</div>
    </div>
</div>


