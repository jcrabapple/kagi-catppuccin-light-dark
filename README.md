Copy and paste the contents of custom.css into the Custom CSS box in your Kagi appearance settings.

Your theme will change between light and dark based on your browser and/or system settings.

If you'd like to change the font, add the following CSS and include the name of your desired font:

```
body {
    font-family: Arial, sans-serif !important;
}
```

For example, I like to use the Poppins font:

```
body {
    font-family: Poppins sans-serif !important;
}

```

If you'd like to add back the underlining of the titles in search results, remove or comment out the following lines:

```
/* OPTIONAL disable underline on title links in search result */
.__sri-title .__sri_title_link {
  border-bottom: none;
}
```

So it would look like this:

```
/* OPTIONAL disable underline on title links in search result */
/* .__sri-title .__sri_title_link {
  border-bottom: none;
} */
```
