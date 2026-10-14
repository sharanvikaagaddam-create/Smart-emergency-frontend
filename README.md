# Emergency Frontend

This folder contains copies of the emergency system's HTML pages, separated from the
Spring Boot project. The backend project remains in `../emergency-system/`.

## Files

The HTML files are in this folder. Their styles and scripts are currently embedded
in the pages; there are no separate CSS, JavaScript, or image assets yet.

## Important

These pages still use Thymeleaf attributes and Spring form routes. They are separated
as frontend source files, but they are not yet a standalone frontend application and
must be rendered/served by the Spring Boot backend for forms and dynamic content to
work.
