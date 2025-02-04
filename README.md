<p align="center"><a href="https://naykel.com.au" target="_blank"><img src="https://avatars0.githubusercontent.com/u/32632005?s=460&u=d1df6f6e0bf29668f8a4845271e9be8c9b96ed83&v=4" width="120"></a></p>

# NAYKEL Vite Starter

<div style="color: red; font-size: 2.5rem; font-weight: bold;">WARNING</div>  

This starter uses JTB, which includes deprecated Sass methods, such as:  

- **Legacy JS API** – Deprecated and will be removed in Dart Sass 2.0.0.  
- **Global built-in functions** – Deprecated and will be removed in Dart Sass 3.0.0.  
- **Color functions** – `darken()`, `lighten()`, and similar functions are deprecated.  

Warnings have been suppressed in `vite.config.js` to save your console from being spammed.  

You can also complexly remove JTB from the project by deleting it from `package.json` and
removing the import from `main.js`.  
