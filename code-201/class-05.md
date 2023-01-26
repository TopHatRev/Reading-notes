# Reading 05

### Images in HTML

[Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)  

[Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)  


**APNG	Animated Portable Network Graphics**	image/apng	.apng	Good choice for lossless animation sequences (GIF is less performant). AVIF and WebP have better performance but less broad browser support.
Supported: Chrome, Edge, Firefox, Opera, Safari.
AVIF	AV1 Image File Format	image/avif	.avif	
Good choice for both images and animated images due to high performance and royalty free image format. It offers much better compression than PNG or JPEG with support for higher color depths, animated frames, transparency, etc. Note that when using AVIF, you should include fallbacks to formats with better browser support (i.e. using the <picture> element).
Supported: Chrome, Firefox (still images only: animated images not implemented), Opera, Safari.

**GIF	Graphics Interchange Format**	image/gif	.gif	Good choice for simple images and animations. Prefer PNG for lossless and indexed still images, and consider WebP, AVIF or APNG for animation sequences.
Supported: Chrome, Edge, Firefox, IE, Opera, Safari.
JPEG	Joint Photographic Expert Group image	image/jpeg	.jpg, .jpeg, .jfif, .pjpeg, .pjp	
Good choice for lossy compression of still images (currently the most popular). Prefer PNG when more precise reproduction of the image is required, or WebP/AVIF if both better reproduction and higher compression are required.
Support: Chrome, Edge, Firefox, IE, Opera, Safari.

**PNG	Portable Network Graphics**	image/png	.png	
PNG is preferred over JPEG for more precise reproduction of source images, or when transparency is needed. WebP/AVIF provide even better compression and reproduction, but browser support is more limited.
Support: Chrome, Edge, Firefox, IE, Opera, Safari.

**SVG	Scalable Vector Graphics**	image/svg+xml	.svg	Vector image format; ideal for user interface elements, icons, diagrams, etc., that must be drawn accurately at different sizes.
Support: Chrome, Edge, Firefox, IE, Opera, Safari.
WebP	Web Picture format	image/webp	.webp	Excellent choice for both images and animated images. WebP offers much better compression than PNG or JPEG with support for higher color depths, animated frames, transparency etc. AVIF offers slightly better compression, but is not quite as well-supported in browsers and does not support progressive rendering.
Support: Chrome, Edge, Firefox, Opera, Safari

### Icons
For smaller images such as icons, use a lossless format to avoid loss of detail in a size-constrained image. While lossless WebP is ideal for this purpose, support is not widespread yet, so PNG is a better choice unless you offer a fallback. If your image contains fewer than 256 colors, GIF is an option, although PNG often compresses even smaller with its indexed compression option (PNG-8).

If the icon can be represented using vector graphics, consider SVG, since it scales across various resolutions and sizes, so it's perfect for responsive design. Although SVG support is good, it may be worth offering a PNG fallback for older browsers.

Best choice	Fallback
SVG, Lossless WebP, or PNG	PNG

[Colour in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

[Text Styling in HTML](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

