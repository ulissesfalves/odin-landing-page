# Odin Landing Page Project

## Overview

Welcome to the Odin Landing Page project! This repository contains the code for a simple yet elegant landing page designed as part of The Odin Project curriculum.

## Features

- Responsive design that looks great on both desktop and mobile devices.
- Modern, clean, and accessible HTML and CSS.
- Easy to customize with your own content and style.

## Preview

Visit the live website [here](https://ulissesfalves.github.io/odin-landing-page/)

## Usage

This landing page can be used as a starting point for your own project or as a learning resource to understand the basics of web development. Happy coding!

<script>
document.addEventListener('DOMContentLoaded', function() {
    var links = document.querySelectorAll('a');
    links.forEach(function(link) {
        if (link.hostname !== window.location.hostname) {
            link.setAttribute('target', '_blank');
            link.setAttribute('rel', 'noopener noreferrer');
        }
    });
});
</script>