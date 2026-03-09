# Chapter 25: Optical Instruments

<!-- Page 713 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 713

Optical Instruments
CHAPTER-OPENING QUESTION-Guess now!
Because of diffraction, a light microscope has a useful magnification of about
(a) $50 \times$;
(b) $100 \times$;
(c) $500 \times$;
(d) $2000 \times$;
(e) $5000 \times$;
and the smallest objects it can resolve have a size of about
(a) 10 nm ;
(b) 100 nm ;
(c) 500 nm ;
(d) 2500 nm ;
(e) 5500 nm .

In our discussion of the behavior of light in the two previous Chapters, we also described a few instruments such as the spectrometer and the Michelson interferometer. In this Chapter, we will discuss some more common instruments, most of which use lenses, including the camera, telescope, microscope, and the human eye. To describe their operation, we will use ray diagrams as we did in Chapter 23. However, we will see that understanding some aspects of their operation will require the wave nature of light.

25-1 Cameras: Film and Digital
The basic elements of a camera are a lens, a light-tight box, a shutter to let light pass through the lens only briefly, and in a digital camera an electronic sensor or in a traditional camera a piece of film (Fig. 25-1). When the shutter is opened for a brief "exposure," light from external objects in the field of view is focused by the lens as an image on the sensor or film.

You can see the image yourself if you remove the back of a conventional camera, keeping the shutter open, and view through a piece of tissue paper (on which an image can form) placed where the film should be.

Of the many optical devices we discuss in this Chapter, the magnifying glass is the simplest. Here it is magnifying part of page 722 of this Chapter, which describes how the magnifying glass works according to the ray model. In this Chapter we examine film and digital cameras, the human eye, eyeglasses, telescopes, and microscopes as well as image resolution, X-rays, and CT scans.

CONTENTS
25-1 Cameras: Film and Digital
25-2 The Human Eye; Corrective Lenses
25-3 Magnifying Glass
25-4 Telescopes
25-5 Compound Microscope
25-6 Aberrations of Lenses and Mirrors
25-7 Limits of Resolution; Circular Apertures
25-8 Resolution of Telescopes and Microscopes; the $\lambda$ Limit
25-9 Resolution of the Human Eye and Useful Magnification
*25-10 Specialty Microscopes and Contrast
25-11 X-Rays and X-Ray Diffraction
*25-12 X-Ray Imaging and Computed Tomography (CT Scan)

FIGURE 25-1 A simple camera.

713

---

<!-- Page 714 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
714

PHYSICS APPLIED
Cameras, film and digital

FIGURE 25-2 Portion of a typical Bayer array sensor. A square group of four pixels ${ }_{\mathrm{GB}}^{\mathrm{RG}}$ is sometimes called a "color pixel."

FIGURE 25-3 A layered or "Foveon" tri-pixel that includes all three colors, arranged vertically so light can pass through all three subpixels.

FIGURE 25-4 Suppose we take a picture that includes a thin black line (our object) on a white background. The image of this black line has a colored "halo" (red above, blue below) due to the mosaic arrangement of color filter pixels, as shown by the colors transmitted to the image. Computer averaging minimizes such color problems (the green at top and bottom of image may average with nearby pixels to give white or nearly so) but the image is consequently "softened" or blurred.

714

Film contains a thin emulsion (= a coating) with light-sensitive chemicals that change when light strikes them. The film is then developed by chemicals dissolved in water, which causes the most changed areas (brightest light) to turn opaque, so the image is recorded on the film. ${ }^{\dagger}$ We might call film "chemical photography" as compared to digital, which is electronic.

Digital Cameras, Electronic Sensors (CCD, CMOS)
In a digital camera, the film is replaced by a semiconductor sensor. Two types are common: CCD (charge-coupled device) and CMOS (complementary metal oxide semiconductor). A CCD sensor is made up of millions of tiny semiconductor pixels ("picture elements")-see Fig. 24-49. A 12-MP (12-megapixel) sensor might contain about 4000 pixels horizontally by 3000 pixels vertically over an area of perhaps $16 \times 12 \mathrm{~mm}$, and preferably larger such as $36 \times 24 \mathrm{~mm}$ like $35-\mathrm{mm}$ film. Light reaching any pixel liberates electrons within the semiconductor ${ }^{\ddagger}$ which are stored as charge in that pixel's capacitance. The more intense the light, the more charge accumulates during the brief exposure time. After exposure, the charge on each pixel has to be "read" (measured) and stored. A reader circuit first reads the charge on the pixel capacitance right next to it. Immediately after, the charge on each pixel is electronically transferred to its adjacent pixel, towards the reader which reads each pixel charge in sequence, one-by-one. Hence the name "charge-coupled device." All this information (the brightness of each pixel) goes to a central processor that stores it and allows re-formation of the image later onto the camera's screen, a computer screen, or a printer. After all the pixel charge information is transferred to memory (Section 21-8), a new picture can be taken.

A CMOS sensor also uses a silicon semiconductor, and incorporates transistor electronics within each pixel, allowing parallel readout, somewhat like the similar MOSFET array that was shown in Fig. 21-29.

Sensor sizes are typically in the ratio $4: 3$ or $3: 2$. A larger sensor is better because it can hold more pixels, and/or each pixel can be larger and hold more charge (free electrons) to provide a wider range of brightness, better color accuracy, and better sensitivity in low-light conditions.

In the most common array of pixels, referred to as a Bayer mosaic, color is achieved by red, green, and blue filters over alternating pixels as shown in Fig. 25-2, similar to what a color LCD or CRT screen does (Sections 17-11 and 24-11). The sensor type shown in Fig. 25-2 contains twice as many green pixels as red or blue (because green seems to have a stronger influence on the human eye's sensation of sharpness). The computer-analyzed color at many pixels is often an average with nearest-neighbor colors to reduce memory size (= compression, see page 489).

Each different color of pixel in a Bayer array is counted as a separate pixel. In contrast, in an LCD screen (Sections 17-11 and 24-11), a group of three subpixels is counted as one pixel, a more conservative count.

An alternative technology, called "Foveon," uses a semiconductor layer system. Different wavelengths of light penetrate silicon to different depths, as shown in Fig. 25-3: blue wavelengths are absorbed in the top layer, allowing green and red light to pass through. Longer wavelengths (green) are absorbed in the second layer, and the bottom layer detects the longest wavelengths (red). All three colors are detected by each "tri-pixel" site, resulting in better color resolution and fewer artifacts.

Digital Artifacts
Digital cameras can produce image artifacts (artificial effects in the image not present in the original) resulting from the electronic sensing of the image. One example using the Bayer mosaic of pixels (Fig. 25-2) is described in Fig. 25-4.
${ }^{\dagger}$ This is called a negative, because the black areas correspond to bright objects and vice versa. The same process occurs during printing to produce a black-and-white "positive" picture from the negative. Color film has three emulsion layers (or dyes) corresponding to the three primary colors. ${ }^{\ddagger}$ Specifically, photons of light knock electrons in the valence band up to the conduction band. This material on semiconductors is covered in Chapter 29.

---

<!-- Page 715 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 715

Camera Adjustments
There are three main adjustments on good-quality cameras: shutter speed, $f$-stop, and focusing. Although most cameras today make these adjustments automatically, it is valuable to understand these adjustments to use a camera effectively. For special or top-quality work, a manual camera is indispensable (Fig. 25-5).

Exposure time or shutter speed This refers to how quickly the digital sensor can make an accurate reading of the images, or how long the shutter of a camera is open and the film or sensor is exposed. It could vary from a second or more ("time exposures") to $\frac{1}{1000} \mathrm{~s}$ or faster. To avoid blurring from camera movement, exposure times shorter than $\frac{1}{100} \mathrm{~s}$ are normally needed. If the object is moving, even shorter exposure times are needed to "stop" the action ( $\frac{1}{1000} \mathrm{~s}$ or less). If the exposure time is not fast enough, the image will be blurred by camera shake. Blurring in low light conditions is more of a problem with cell-phone cameras whose inexpensive sensors need to have the shutter open longer to collect enough light. Digital still cameras or cell phones that take short videos must have a fast enough "sampling" time and fast "clearing" (of the charge) so as to take pictures at least 15 frames per second; preferable is 24 fps (like film) or 30 , 60 , or 120 fps like TV refresh rates (25, 50, or 100 in areas like Europe where 50 Hz is the normal line voltage frequency).
$\boldsymbol{f}$-stop The amount of light reaching the sensor or film depends on the area of the lens opening as well as shutter speed, and must be carefully controlled to avoid underexposure (too little light so the picture is dark and only the brightest objects show up) or overexposure (too much light, so that bright objects have a lack of contrast and "washed-out" appearance). A high quality camera controls the exposure with a "stop" or iris diaphragm, whose opening is of variable diameter, placed behind the lens (Fig. 25-1). The lens opening is controlled (automatically or manually) to compensate for bright or dark lighting conditions, the sensitivity of the sensor or film, ${ }^{\dagger}$ and for different shutter speeds. The size of the opening is specified by the $\boldsymbol{f}$-stop or $\boldsymbol{f}$-number, defined as
$$f \text {-stop }=\frac{f}{D},$$
where $f$ is the focal length of the lens and $D$ is the diameter of the lens opening (see Fig. 25-1). For example, when a $50-\mathrm{mm}$-focal-length lens has an opening $D=25 \mathrm{~mm}$, then $f / D=50 \mathrm{~mm} / 25 \mathrm{~mm}=2$, so we say it is set at $f / 2$. When this lens is set at $f / 5.6$, the opening is only $9 \mathrm{~mm}(50 / 9=5.6)$. For faster shutter speeds, or low light conditions, a wider lens opening must be used to get a proper exposure, which corresponds to a smaller $f$-stop number. The smaller the $f$-stop number, the larger the opening and the more light passes through the lens to the sensor or film. The smallest $f$-number of a lens (largest opening) is referred to as the speed of the lens. The best lenses may have a speed of $f / 2.0$, or even faster. The advantage of a fast lens is that it allows pictures to be taken under poor lighting conditions. Good quality lenses consist of several elements to reduce the defects present in simple thin lenses (Section 25-6). Standard $f$-stops are
$$1.0,1.4,2.0,2.8,4.0,5.6,8,11,16,22 \text {, and } 32$$
(Fig. 25-5). Each of these stops corresponds to a diameter reduction by a factor of $\sqrt{2} \approx 1.4$. Because the amount of light reaching the film is proportional to the area of the opening, and therefore proportional to the diameter squared, each standard $f$-stop corresponds to a factor of 2 change in light intensity reaching the film.
${ }^{\dagger}$ Different films have different sensitivities to light, referred to as the "film speed" and specified as an "ISO (or ASA) number." A "faster" film is more sensitive and needs less light to produce a good image, but is grainier which you see when the image is enlarged. Digital cameras may have a "gain" or "ISO" adjustment for sensitivity. A typical everyday ISO might be 200 or so. Adjusting a CCD to be "faster" (high ISO like 3200) for low light conditions results in "noise," resulting in graininess just as in film cameras.

FIGURE 25-5 On this camera, the $f$-stops and the focusing ring are on the camera lens. Shutter speeds are selected on the small wheel on top of the camera body.

SECTION 25-1 Cameras: Film and Digital
715

---

<!-- Page 716 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 716

FIGURE 25-6 Photos taken with a camera lens (a) focused on a nearby object with distant object blurry, and (b) focused on a more distant object with nearby object blurry.

Focusing Focusing is the operation of placing the lens at the correct position relative to the sensor or film for the sharpest image. The image distance is smallest for objects at infinity (the symbol $\infty$ is used for infinity) and is equal to the focal length, as we saw in Section 23-7. For closer objects, the image distance is greater than the focal length, as can be seen from the lens equation, $1 / f=1 / d_{\mathrm{o}}+1 / d_{\mathrm{i}}$ (Eq. $23-8$ ). To focus on nearby objects, the lens must therefore be moved away from the sensor or film, and this is usually done on a manual camera by turning a ring on the lens.

If the lens is focused on a nearby object, a sharp image of it will be formed, but the image of distant objects may be blurry (Fig. 25-6). The rays from a point on the distant object will be out of focus-instead of a point, they will form a circle on the sensor or film as shown (exaggerated) in Fig. 25-7. The distant object will thus produce an image consisting of overlapping circles and will be blurred. These circles are called circles of confusion. To have near and distant objects sharp in the same photo, you (or the camera) can try setting the lens focus at an intermediate position. For a given distance setting, there is a range of distances over which the circles of confusion will be small enough that the images will be reasonably sharp. This is called the depth of field. For a sensor or film width of 36 mm (including $35-\mathrm{mm}$ film cameras), the depth of field is usually based on a maximum circle of confusion diameter of 0.030 mm , even 0.02 mm or 0.01 mm for critical work or very large photographs. The depth of field varies with the lens opening. If the lens opening is smaller, only rays through the central part of the lens are accepted, and these form smaller circles of confusion for a given object distance. Hence, at smaller lens openings, a greater range of object distances will fit within the circle of confusion criterion, so the depth of field is greater. Smaller lens openings, however, result in reduced resolution due to diffraction (discussed later in this Chapter). Best resolution is typically found around $f / 5.6$ or $f / 8$.

FIGURE 25-7 When the lens is positioned to focus on a nearby object, points on a distant object produce circles and are therefore blurred. (The effect is shown greatly exaggerated.)

EXAMPLE 25-1 Camera focus. How far must a $50.0-\mathrm{mm}$-focal-length camera lens be moved from its infinity setting to sharply focus an object 3.00 m away?
APPROACH For an object at infinity, the image is at the focal point, by definition (Section 23-7). For an object distance of 3.00 m , we use the thin lens equation, Eq. 23-8, to find the image distance (distance of lens to film or sensor).
SOLUTION When focused at infinity, the lens is 50.0 mm from the film. When focused at $d_{\mathrm{o}}=3.00 \mathrm{~m}$, the image distance is given by the lens equation,
$$\frac{1}{d_{\mathrm{i}}}=\frac{1}{f}-\frac{1}{d_{\mathrm{o}}}=\frac{1}{50.0 \mathrm{~mm}}-\frac{1}{3000 \mathrm{~mm}}=\frac{3000-50}{(3000)(50.0) \mathrm{mm}}=\frac{2950}{150,000 \mathrm{~mm}} .$$

We solve for $d_{\mathrm{i}}$ and find $d_{\mathrm{i}}=50.8 \mathrm{~mm}$, so the lens needs to move 0.8 mm away from the film or digital sensor.

EXERCISE A If the lens of Example 25-1 is 50.4 mm from the film or sensor, what is the object distance for sharp focus?

716
CHAPTER 25 Optical Instruments

---

<!-- Page 717 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 717

CONCEPTUAL EXAMPLE 25-2 Shutter speed. To improve the depth of field, you "stop down" your camera lens by two $f$-stops from $f / 4$ to $f / 8$. What should you do to the shutter speed to maintain the same exposure?
RESPONSE The amount of light admitted by the lens is proportional to the area of the lens opening. Reducing the lens opening by two $f$-stops reduces the diameter by a factor of 2 , and the area by a factor of 4 . To maintain the same exposure, the shutter must be open four times as long. If the shutter speed had been $\frac{1}{500} \mathrm{~s}$, you would have to increase the exposure time to $\frac{1}{125} \mathrm{~s}$.
* Picture Sharpness

The sharpness of a picture depends not only on accurate focusing and short exposure times, but also on the graininess of the film, or number of pixels on a digital sensor. Fine-grained films and tiny pixels are "slower," meaning they require longer exposures for a given light level. All pixels are rarely used because digital cameras have averaging (or "compression") programs, such as JPEG, which reduce memory size by averaging over pixels where little contrast is detected. But some detail is inevitably lost. For example, a small blue lake may seem uniform, and coding 600 pixels as identical takes less memory than specifying all 600 . Any slight variation of the water surface is lost. Full "RAW" data uses more memory. Film records everything (down to its grain size), as does RAW if your camera offers it. The processor also averages over pixels in low light conditions, resulting in a less sharp photo.

The quality of the lens strongly affects the image quality, and we discuss lens resolution and diffraction effects in Sections 25-6 and 25-7. The sharpness, or resolution, of a lens is often given as so many lines per millimeter, measured by photographing a standard set of parallel black lines on a white background (sometimes said as "line pairs/mm") on fine-grain film or high quality sensor, or as so many dots per inch (dpi). The minimum spacing of distinguishable lines or dots gives the resolution. A lens that can give 50 lines $/ \mathrm{mm}$ is reasonable, 100 lines $/ \mathrm{mm}$ is very good ( $=100$ dots/ $\mathrm{mm} \approx 2500 \mathrm{dpi}$ ). Electronic sensors also have a resolution and it is sometimes given as line pairs across the full sensor width.

A "full" Bayer pixel (upper left in Fig. 25-2) is 4 regular pixels: for example, to make a white dot as part of a white line (between two black lines when determining lens resolution), all 4 Bayer pixels (RGGB) would have to be bright. For a Foveon, all three colors of one pixel need to be bright to produce a white dot. ${ }^{\dagger}$

EXAMPLE 25-3 Pixels and resolution. A digital camera offers a maximum resolution of $4000 \times 3000$ pixels on a $32 \mathrm{~mm} \times 24 \mathrm{~mm}$ sensor. How sharp should the lens be to make use of this sensor resolution in RAW?
APPROACH We find the number of pixels per millimeter and require the lens to be at least that good.
SOLUTION We can either take the image height ( 3000 pixels in 24 mm ) or the width ( 4000 pixels in 32 mm ):
$$\frac{3000 \text { pixels }}{24 \mathrm{~mm}}=125 \text { pixels } / \mathrm{mm} .$$

We would like the lens to match this resolution of 125 lines or dots per mm, which would be a quite good lens. If the lens is not this good, fewer pixels and less memory could be used.
NOTE Increasing lens resolution is a tougher problem today than is squeezing more pixels on a CCD or CMOS sensor. The sensor for high quality cameras must also be physically larger for better image accuracy and greater light sensitivity in low light conditions.
${ }^{\dagger}$ Consider a $4000 \times 3000$ pixel array. For a Foveon, each "full pixel" (Fig. 25-3) has all 3 colors, each of which can be counted as a pixel, so it may be considered as $4000 \times 3000 \times 3=36 \mathrm{MP}$. For a Bayer sensor, Fig. $25-2,4000 \times 3000$ is 12 MP ( 6 MP of green, 3 MP each of red and blue). There are more green pixels because they are most important in our eyes' ability to note resolution. So the distance between green pixels is a rough guide to the sharpness of a Bayer. To match a $4000 \times 3000$ Foveon ( 36 MP , or 12 MP of tri-pixel sites), a Bayer would need to have about 24 MP (because it would then have 12 MP of green). This "equivalence" is only a rough approximation.

SECTION 25-1
717

---

<!-- Page 718 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 718

PHYSICS APPLIED
When is a photo sharp?

FIGURE 25-8 Single-lens reflex (SLR) camera, showing how the image is viewed through the lens with the help of a movable mirror and prism.

EXAMPLE 25-4 Blown-up photograph. A photograph looks sharp at normal viewing distances if the dots or lines are resolved to perhaps 10 dots $/ \mathrm{mm}$. Would an $8 \times 10$-inch enlargement of a photo taken by the camera in Example 25-3 seem sharp?
APPROACH We assume the image is $4000 \times 3000$ pixels on a $32 \times 24-\mathrm{mm}$ sensor as in Example 25-3, or 125 pixels $/ \mathrm{mm}$. We make an enlarged photo $8 \times 10 \mathrm{in} .=20 \mathrm{~cm} \times 25 \mathrm{~cm}$.
SOLUTION The short side of the sensor is $24 \mathrm{~mm}=2.4 \mathrm{~cm}$ long, and that side of the photograph is 8 inches or 20 cm . Thus the size is increased by a factor of $20 \mathrm{~cm} / 2.4 \mathrm{~cm} \approx 8 \times$ (or $25 \mathrm{~cm} / 3.2 \mathrm{~cm} \approx 8 \times$ ). To fill the $8 \times 10$-in. paper, we assume the enlargement is $8 \times$. The pixels are thus enlarged $8 \times$. So the pixel count of $125 / \mathrm{mm}$ on the sensor becomes $125 / 8=15$ per mm on the print. Hence an $8 \times 10$-inch print would be a sharp photograph. We could go $50 \%$ larger- $11 \times 14$ or maybe even $12 \times 18$ inches.

In order to make very large photographic prints, large-format cameras are used such as $6 \mathrm{~cm} \times 6 \mathrm{~cm}$ ( $2 \frac{1}{4}$ inch square)—either film or sensor—and even $4 \times 5$ inch and $8 \times 10$ inch (using sheet film or glass plates).

EXERCISE B The criterion of 0.030 mm as the diameter of a circle of confusion as acceptable sharpness is how many dots per mm on the sensor?

Telephotos and Wide-angles
Camera lenses are categorized into normal, telephoto, and wide angle, according to focal length and film size. A normal lens covers the sensor or film with a field of view that corresponds approximately to that of normal vision. A "normal" lens for $35-\mathrm{mm}$ film has a focal length of 50 mm . The best digital cameras aim for a sensor of the same size ${ }^{\dagger}(24 \mathrm{~mm} \times 36 \mathrm{~mm})$. (If the sensor is smaller, digital cameras sometimes specify focal lengths to correspond with classic $35-\mathrm{mm}$ cameras.) Telephoto lenses act like telescopes to magnify images. They have longer focal lengths than a normal lens: as we saw in Section 23-8 (Eq. 23-9), the height of the image for a given object distance is proportional to the image distance, and the image distance will be greater for a lens with longer focal length. For distant objects, the image height is very nearly proportional to the focal length. Thus a $200-\mathrm{mm}$ telephoto lens for use with a $35-\mathrm{mm}$ camera gives a $4 \times$ magnification over the normal $50-\mathrm{mm}$ lens. A wide-angle lens has a shorter focal length than normal: a wider field of view is included, and objects appear smaller. A zoom lens is one whose focal length can be changed (by changing the distance between the thin lenses that make up the compound lens) so that you seem to zoom up to, or away from, the subject as you change the focal length.

Digital cameras may have an optical zoom meaning the lens can change focal length and maintain resolution. But an "electronic" or digital zoom just enlarges the dots (pixels) with loss of sharpness.

Different types of viewing systems are used in cameras. In some cameras, you view through a small window just above the lens as in Fig. 25-1. In a single-lens reflex camera (SLR), you actually view through the lens with the use of prisms and mirrors (Fig. 25-8). A mirror hangs at a $45^{\circ}$ angle behind the lens and flips up out of the way just before the shutter opens. SLRs have the advantage that you can see almost exactly what you will get. Digital cameras use an LCD display, and it too can show what you will get on the photo if it is carefully designed.
${ }^{\dagger}$ A " $35-\mathrm{mm}$ camera" uses film that is physically 35 mm wide; that 35 mm is not to be confused with a focal length. $35-\mathrm{mm}$ film has sprocket holes, so only 24 mm of its height is used for the photo; the width is usually 36 mm for stills. Thus one frame is $36 \mathrm{~mm} \times 24 \mathrm{~mm}$. Movie frames on $35-\mathrm{mm}$ film are $24 \mathrm{~mm} \times 18 \mathrm{~mm}$.

718
CHAPTER 25 Optical Instruments

---

<!-- Page 719 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 719

25-2 The Human Eye; Corrective Lenses

The human eye resembles a camera in its basic structure (Fig. 25-9), but is far more sophisticated. The interior of the eye is filled with a transparent gel-like substance called the vitreous humor with index of refraction $n=1.337$. Light enters this enclosed volume through the cornea and lens. Between the cornea and lens is a watery fluid, the aqueous humor (aqua is "water" in Latin) with $n=1.336$. A diaphragm, called the iris (the colored part of your eye), adjusts automatically to control the amount of light entering the eye, similar to a camera. The hole in the iris through which light passes (the pupil) is black because no light is reflected from it (it's a hole), and very little light is reflected back out from the interior of the eye. The retina, which plays the role of the film or sensor in a camera, is on the curved rear surface of the eye. The retina consists of a complex array of nerves and receptors known as rods and cones which act to change light energy into electrical signals that travel along the nerves. The reconstruction of the image from all these tiny receptors is done mainly in the brain, although some analysis may also be done in the complex interconnected nerve network at the retina itself. At the center of the retina is a small area called the fovea, about 0.25 mm in diameter, where the cones are very closely packed and the sharpest image and best color discrimination are found.

Unlike a camera, the eye contains no shutter. The equivalent operation is carried out by the nervous system, which analyzes the signals to form images at the rate of about 30 per second. This can be compared to motion picture or television cameras, which operate by taking a series of still pictures at a rate of 24 (movies) and 60 or 30 (U.S. television) per second. Their rapid projection on the screen gives the appearance of motion.

The lens of the eye ( $n=1.386$ to 1.406 ) does little of the bending of the light rays. Most of the refraction is done at the front surface of the cornea ( $n=1.376$ ) at its interface with air $(n=1.0)$. The lens acts as a fine adjustment for focusing at different distances. This is accomplished by the ciliary muscles (Fig. 25-9), which change the curvature of the lens so that its focal length is changed. To focus on a distant object, the ciliary muscles of the eye are relaxed and the lens is thin, as shown in Fig. 25-10a, and parallel rays focus at the focal point (on the retina). To focus on a nearby object, the muscles contract, causing the center of the lens to thicken, Fig. 25-10b, thus shortening the focal length so that images of nearby objects can be focused on the retina, behind the new focal point. This focusing adjustment is called accommodation.

The closest distance at which the eye can focus clearly is called the near point of the eye. For young adults it is typically 25 cm , although younger children can often focus on objects as close as 10 cm . As people grow older, the ability to accommodate is reduced and the near point increases. A given person's far point is the farthest distance at which an object can be seen clearly. For some purposes it is useful to speak of a normal eye (a sort of average over the population), defined as an eye having a near point of 25 cm and a far point of infinity. To check your own near point, place this book close to your eye and slowly move it away until the type is sharp.

The "normal" eye is sort of an ideal. Many people have eyes that do not accommodate within the "normal" range of 25 cm to infinity, or have some other defect. Two common defects are nearsightedness and farsightedness. Both can be corrected to a large extent with lenses-either eyeglasses or contact lenses.

In nearsightedness, or myopia, the human eye can focus only on nearby objects. The far point is not infinity but some shorter distance, so distant objects are not seen clearly. Nearsightedness is usually caused by an eyeball that is too long, although sometimes it is the curvature of the cornea that is too great. In either case, images of distant objects are focused in front of the retina.

PHYSICS APPLIED
The eye

FIGURE 25-9 Diagram of a human eye.

FIGURE 25-10 Accommodation by a normal eye: (a) lens relaxed, focused at infinity; (b) lens thickened, focused on a nearby object.

SECTION 25-2 The Human Eye; Corrective Lenses
719

---

<!-- Page 720 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
$\_\_\_\_$

720

FIGURE 25-11 Correcting eye defects with lenses. (a) A nearsighted eye, which cannot focus clearly on distant objects (focal point is in front of retina), can be corrected (b) by use of a diverging lens. (c) A farsighted eye, which cannot focus clearly on nearby objects (focus point behind retina), can be corrected (d) by use of a converging lens.

FIGURE 25-12 A cylindrical lens forms a line image of a point object because it is converging in one plane only.

PHYSICS APPLIED
Corrective lenses

A diverging lens, because it causes parallel rays to diverge, allows the rays to be focused at the retina (Figs. 25-11a and b) and thus can correct nearsightedness.

In farsightedness, or hyperopia, the eye cannot focus on nearby objects. Although distant objects are usually seen clearly, the near point is somewhat greater than the "normal" 25 cm , which makes reading difficult. This defect is caused by an eyeball that is too short or (less often) by a cornea that is not sufficiently curved. It is corrected by a converging lens, Figs. 25-11c and d. Similar to hyperopia is presbyopia, which is the lessening ability of the eye to accommodate as a person ages, and the near point moves out. Converging lenses also compensate for this.

Astigmatism is usually caused by an out-of-round cornea or lens so that point objects are focused as short lines, which blurs the image. It is as if the cornea were spherical with a cylindrical section superimposed. As shown in Fig. 25-12, a cylindrical lens focuses a point into a line parallel to its axis. An astigmatic eye may focus rays in one plane, such as the vertical plane, at a shorter distance than it does for rays in a horizontal plane. Astigmatism is corrected with the use of a compensating cylindrical lens. Lenses for eyes that are nearsighted or farsighted as well as astigmatic are ground with superimposed spherical and cylindrical surfaces, so that the radius of curvature of the correcting lens is different in different planes.

EXAMPLE 25-5 Farsighted eye. A farsighted eye has a near point of 100 cm . Reading glasses must have what lens power so that a newspaper can be read at a distance of 25 cm ? Assume the lens is very close to the eye.
APPROACH When the object is placed 25 cm from the lens ( $=d_{\mathrm{o}}$ ), we want the image to be 100 cm away on the same side of the lens (so the eye can focus it), and so the image is virtual, as shown in Fig. 25-13, and $d_{\mathrm{i}}=-100 \mathrm{~cm}$ will be negative. We use the thin lens equation (Eq. 23-8) to determine the needed focal length. Optometrists' prescriptions specify the power ( $P=1 / f$, Eq. 23-7) given in diopters ( $1 \mathrm{D}=1 \mathrm{~m}^{-1}$ ).
SOLUTION Given that $d_{\mathrm{o}}=25 \mathrm{~cm}$ and $d_{\mathrm{i}}=-100 \mathrm{~cm}$, the thin lens equation gives
$$\frac{1}{f}=\frac{1}{d_{\mathrm{o}}}+\frac{1}{d_{\mathrm{i}}}=\frac{1}{25 \mathrm{~cm}}+\frac{1}{-100 \mathrm{~cm}}=\frac{4-1}{100 \mathrm{~cm}}=\frac{1}{33 \mathrm{~cm}} .$$

So $f=33 \mathrm{~cm}=0.33 \mathrm{~m}$. The power $P$ of the lens is $P=1 / f=+3.0 \mathrm{D}$. The plus sign indicates that it is a converging lens.
NOTE We chose the image position to be where the eye can actually focus. The lens needs to put the image there, given the desired placement of the object (newspaper).

FIGURE 25-13 Lens of reading glasses (Example 25-5).

720
CHAPTER 25 Optical Instruments

---

<!-- Page 721 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
721

EXAMPLE 25-6 Nearsighted eye. A nearsighted eye has near and far points of 12 cm and 17 cm , respectively. (a) What lens power is needed for this person to see distant objects clearly, and ( $b$ ) what then will be the near point? Assume that the lens is 2.0 cm from the eye (typical for eyeglasses).
APPROACH For a distant object ( $d_{\mathrm{o}}=\infty$ ), the lens must put the image at the far point of the eye as shown in Fig. 25-14a, 17 cm in front of the eye. We can use the thin lens equation to find the focal length of the lens, and from this its lens power. The new near point (as shown in Fig. 25-14b) can be calculated for the lens by again using the thin lens equation.
SOLUTION (a) For an object at infinity ( $d_{\mathrm{o}}=\infty$ ), the image must be in front of the lens 17 cm from the eye or $(17 \mathrm{~cm}-2 \mathrm{~cm})=15 \mathrm{~cm}$ from the lens; hence $d_{\mathrm{i}}=-15 \mathrm{~cm}$. We use the thin lens equation to solve for the focal length of the needed lens:
$$\frac{1}{f}=\frac{1}{d_{\mathrm{o}}}+\frac{1}{d_{\mathrm{i}}}=\frac{1}{\infty}+\frac{1}{-15 \mathrm{~cm}}=-\frac{1}{15 \mathrm{~cm}} .$$

So $f=-15 \mathrm{~cm}=-0.15 \mathrm{~m}$ or $P=1 / f=-6.7 \mathrm{D}$. The minus sign indicates that it must be a diverging lens for the myopic eye.

FIGURE 25-14 Example 25-6.
(b) The near point when glasses are worn is where an object is placed ( $d_{\mathrm{o}}$ ) so that the lens forms an image at the "near point of the naked eye," namely 12 cm from the eye. That image point is $(12 \mathrm{~cm}-2 \mathrm{~cm})=10 \mathrm{~cm}$ in front of the lens, so $d_{\mathrm{i}}=-0.10 \mathrm{~m}$ and the thin lens equation gives
$$\frac{1}{d_{\mathrm{o}}}=\frac{1}{f}-\frac{1}{d_{\mathrm{i}}}=-\frac{1}{0.15 \mathrm{~m}}+\frac{1}{0.10 \mathrm{~m}}=\frac{-2+3}{0.30 \mathrm{~m}}=\frac{1}{0.30 \mathrm{~m}} .$$

So $d_{\mathrm{o}}=30 \mathrm{~cm}$, which means the near point when the person is wearing glasses is 30 cm in front of the lens, or 32 cm from the eye.

Contact Lenses
Suppose contact lenses are used to correct the eye in Example 25-6. Since

Chysics applied
Contact lenses-different f and $P$ contacts are placed directly on the cornea, we would not subtract out the 2.0 cm for the image distances. That is, for distant objects $d_{\mathrm{i}}=f=-17 \mathrm{~cm}$, so $P=1 / f=-5.9 \mathrm{D}$. The new near point would be 41 cm . Thus we see that a contact lens and an eyeglass lens will require slightly different powers, or focal lengths, for the same eye because of their different placements relative to the eye. We also see that glasses in this case give a better near point than contacts.

EXERCISE C What power of contact lens is needed for an eye to see distant objects if its far point is 25 cm ?

Underwater Vision
When your eyes are under water, distant underwater objects look blurry because at the water-cornea interface, the difference in indices of refraction is very small:
PHYSICS APPLIED
Underwater vision $n=1.33$ for water, 1.376 for the cornea. Hence light rays are bent very little and are focused far behind the retina, Fig. 25-15a. If you wear goggles or a face mask, you restore an air-cornea interface ( $n=1.0$ and 1.376, respectively) and the rays can be focused, Fig. 25-15b.

(a)

(b)

FIGURE 25-15 (a) Under water, we see a blurry image because light rays are bent much less than in air. (b) If we wear goggles, we again have an air-cornea interface and can see clearly.

SECTION 25-2 The Human Eye; Corrective Lenses
721

---

<!-- Page 722 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 722

FIGURE 25-16 When the same object is viewed at a shorter distance, the image on the retina is greater, so the object appears larger and more detail can be seen. The angle $\theta$ that the object subtends in (a) is greater than in (b). Note: This is not a normal ray diagram because we are showing only one ray from each point.

25-3 Magnifying Glass
Much of the remainder of this Chapter will deal with optical devices that are used to produce magnified images of objects. We first discuss the simple magnifier, or magnifying glass, which is simply a converging lens (see Chapter-Opening Photo, page 713).

How large an object appears, and how much detail we can see on it, depends on the size of the image it makes on the retina. This, in turn, depends on the angle subtended by the object at the eye. For example, a penny held 30 cm from the eye looks twice as tall as one held 60 cm away because the angle it subtends is twice as great (Fig. 25-16). When we want to examine detail on an object, we bring it up close to our eyes so that it subtends a greater angle. However, our eyes can accommodate only up to a point (the near point), and we will assume a standard distance of $N=25 \mathrm{~cm}$ as the near point in what follows.

A magnifying glass allows us to place the object closer to our eye so that it subtends a greater angle. As shown in Fig. 25-17a, the object is placed at the focal point or just within it. Then the converging lens produces a virtual image, which must be at least 25 cm from the eye if the eye is to focus on it. If the eye is relaxed, the image will be at infinity, and in this case the object is exactly at the focal point. (You make this slight adjustment yourself when you "focus" on the object by moving the magnifying glass.)

A comparison of part (a) of Fig. 25-17 with part (b), in which the same object is viewed at the near point with the unaided eye, reveals that the angle the object subtends at the eye is much larger when the magnifier is used. The angular magnification or magnifying power, $M$, of the lens is defined as the ratio of the angle subtended by an object when using the lens, to the angle subtended using the unaided eye, with the object at the near point $N$ of the eye ( $N=25 \mathrm{~cm}$ for a normal eye):
$$M=\frac{\theta^{\prime}}{\theta},$$
where $\theta$ and $\theta^{\prime}$ are shown in Fig. 25-17. We can write $M$ in terms of the focal length by noting that $\theta=h / N$ (Fig.25-17b) and $\theta^{\prime}=h / d_{\mathrm{o}}$ (Fig.25-17a), where $h$ is the height of the object and we assume the angles are small so $\theta$ and $\theta^{\prime}$ (in radians) equal their sines and tangents. If the eye is relaxed (for least eye strain), the image will be at infinity and the object will be precisely at the focal point; see Fig. 25-18. Then $d_{\mathrm{o}}=f$ and $\theta^{\prime}=h / f$, whereas $\theta=h / N$ as before (Fig. 25-17b). Thus
$$M=\frac{\theta^{\prime}}{\theta}=\frac{h / f}{h / N}=\frac{N}{f} \cdot \quad\left[\begin{array}{c}
\text { eye focused at } \infty ; \\
N=25 \mathrm{~cm} \text { for normal eye }
\end{array}\right]$$

We see that the shorter the focal length of the lens, the greater the magnification. ${ }^{\dagger}$
${ }^{\dagger}$ Simple single-lens magnifiers are limited to about 2 or $3 \times$ because of blurring due to spherical aberration (Section 25-6).

722

FIGURE 25-18 With the eye relaxed, the object is placed at the focal point, and the image is at infinity. Compare to Fig. 25-17a where the image is at the eye's near point.

CHAPTER 25 Optical Instruments

FIGURE 25-17 Leaf viewed (a) through a magnifying glass, and (b) with the unaided eye. The eye is focused at its near point in both cases.
FIGURE 25-17 Leaf viewed (a) through a magnifying glass, and (b) with the unaided eye. The eye is

---

<!-- Page 723 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 723

The magnification of a given lens can be increased a bit by moving the lens and adjusting your eye so it focuses on the image at the eye's near point. In this case, $d_{\mathrm{i}}=-N$ (see Fig. 25-17a) if your eye is very near the magnifier. Then the object distance $d_{\mathrm{o}}$ is given by
$$\frac{1}{d_{\mathrm{o}}}=\frac{1}{f}-\frac{1}{d_{\mathrm{i}}}=\frac{1}{f}+\frac{1}{N}$$

We see from this equation that $d_{\mathrm{o}}=f N /(f+N)<f$, as shown in Fig. 25-17a, since $N /(f+N)$ must be less than 1 . With $\theta^{\prime}=h / d_{\mathrm{o}}$ the magnification is
$$\begin{aligned}
M=\frac{\theta^{\prime}}{\theta} & =\frac{h / d_{\mathrm{o}}}{h / N} \\
& =N\left(\frac{1}{d_{\mathrm{o}}}\right)=N\left(\frac{1}{f}+\frac{1}{N}\right)
\end{aligned}$$
or
$$M=\frac{N}{f}+1 . \quad\left[\begin{array}{c}
\text { eye focused at near point, } N ; \\
N=25 \mathrm{~cm} \text { for normal eye }
\end{array}\right]$$

We see that the magnification is slightly greater when the eye is focused at its near point, as compared to when it is relaxed.

EXAMPLE 25-7 ESTIMATE A jeweler's "loupe." An 8 -cm-focal-length converging lens is used as a "jeweler's loupe," which is a magnifying glass. Estimate (a) the magnification when the eye is relaxed, and (b) the magnification if the eye is focused at its near point $N=25 \mathrm{~cm}$.
APPROACH The magnification when the eye is relaxed is given by Eq. 25-2a. When the eye is focused at its near point, we use Eq. 25-2b and we assume the lens is near the eye.
SOLUTION (a) With the relaxed eye focused at infinity,
$$M=\frac{N}{f}=\frac{25 \mathrm{~cm}}{8 \mathrm{~cm}} \approx 3 \times$$
(b) The magnification when the eye is focused at its near point ( $N=25 \mathrm{~cm}$ ), and the lens is near the eye, is
$$M=1+\frac{N}{f}=1+\frac{25}{8} \approx 4 \times$$

25-4 Telescopes
A telescope is used to magnify objects that are very far away. In most cases, the object can be considered to be at infinity.

Galileo, although he did not invent it, ${ }^{\dagger}$ developed the telescope into a usable and important instrument. He was the first to examine the heavens with the telescope (Fig. 25-19), and he made world-shaking discoveries, including the moons of Jupiter, the phases of Venus, sunspots, the structure of the Moon's surface, and that the Milky Way is made up of a huge number of individual stars.
${ }^{\dagger}$ Galileo built his first telescope in 1609 after having heard of such an instrument existing in Holland. The first telescopes magnified only three to four times, but Galileo soon made a 30-power instrument. The first Dutch telescopes date from about 1604 and probably were copies of an Italian telescope built around 1590. Kepler (see Chapter 5) gave a ray description (in 1611) of the Keplerian telescope, which is named for him because he first described it, although he did not build it.

FIGURE 25-19 (a) Objective lens (mounted now in an ivory frame) from the telescope with which Galileo made his world-shaking discoveries, including the moons of Jupiter.
(b) Telescopes made by Galileo (1609).

SECTION 25-4 Telescopes
723

---

<!-- Page 724 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 6/27/16 2:54 PM Page 724

FIGURE 25-20 Astronomical telescope (refracting). Parallel light from one point on a distant object ( $d_{\mathrm{o}}=\infty$ ) is brought to a focus by the objective lens in its focal plane. This image ( $\mathrm{I}_{1}$ ) is magnified by the eyepiece to form the final image $\mathrm{I}_{2}$. Only two of the rays shown entering the objective are standard rays (2 and 3) as described in Fig. 23-37.

Several types of astronomical telescope exist. The common refracting type, sometimes called Keplerian, contains two converging lenses located at opposite ends of a long tube, as illustrated in Fig. 25-20. The lens closest to the object is called the objective lens (focal length $f_{\mathrm{o}}$ ) and forms a real image $\mathrm{I}_{1}$ of the distant object in the plane of its focal point $\mathrm{F}_{\mathrm{o}}$ (or near it if the object is not at infinity). The second lens, called the eyepiece (focal length $f$ ), acts as a magnifier. That is, the eyepiece magnifies the image $\mathrm{I}_{1}$ formed by the objective lens to produce a second, greatly magnified image, $\mathrm{I}_{2}$, which is virtual and inverted. If the viewing eye is relaxed, the eyepiece is adjusted so the image $\mathrm{I}_{2}$ is at infinity. Then the real image $\mathrm{I}_{1}$ is at the focal point $\mathrm{F}_{\mathrm{e}}^{\prime}$ of the eyepiece, and the distance between the lenses is $f_{\mathrm{o}}+f_{\mathrm{e}}$ for an object at infinity.

To find the total angular magnification of this telescope, we note that the angle an object subtends as viewed by the unaided eye is just the angle $\theta$ subtended at the telescope objective. From Fig. 25-20 we can see that $\theta \approx h / f_{\mathrm{o}}$, where $h$ is the height of the image $\mathrm{I}_{1}$ and we assume $\theta$ is small so that $\tan \theta \approx \theta$. Note, too, that the thickest of the three rays drawn in Fig. 25-20 is parallel to the axis before it strikes the eyepiece and therefore is refracted through the eyepiece focal point $\mathrm{F}_{\mathrm{e}}$ on the far side. Thus, $\theta^{\prime} \approx h / f_{\mathrm{e}}$ and the total magnifying power (that is, angular magnification, which is what is always quoted) of this telescope is
$$M=\frac{\theta^{\prime}}{\theta}=\frac{\left(h / f_{\mathrm{e}}\right)}{\left(h / f_{\mathrm{o}}\right)}=-\frac{f_{\mathrm{o}}}{f_{\mathrm{e}}}, \quad\left[\begin{array}{c}
\text { telescope } \\
\text { magnification }
\end{array}\right]$$
where we used Eq. 25-1 and we inserted a minus sign to indicate that the image is inverted. To achieve a large magnification, the objective lens should have a long focal length and the eyepiece a short focal length.

EXAMPLE 25-8 Telescope magnification. The largest optical refracting telescope in the world is located at the Yerkes Observatory in Wisconsin, Fig. 25-21. It is referred to as a "40-inch" telescope, meaning that the diameter of the objective is 40 in ., or 102 cm . The objective lens has a focal length of 19 m , and the eyepiece has a focal length of 10 cm . (a) Calculate the total magnifying power of this telescope. (b) Estimate the length of the telescope.
APPROACH Equation 25-3 gives the magnification. The length of the telescope is the distance between the two lenses.
SOLUTION (a) From Eq. 25-3 we find
$$M=-\frac{f_{\mathrm{o}}}{f_{\mathrm{e}}}=-\frac{19 \mathrm{~m}}{0.10 \mathrm{~m}}=-190 \times$$
(b) For a relaxed eye, the image $\mathrm{I}_{1}$ is at the focal point of both the eyepiece and the objective lenses. The distance between the two lenses is thus $f_{\mathrm{o}}+f_{\mathrm{e}} \approx 19 \mathrm{~m}$, which is essentially the length of the telescope.

724
CHAPTER 25 Optical Instruments

---

<!-- Page 725 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
725

EXERCISE D A $40 \times$ telescope has a $1.2-\mathrm{cm}$ focal length eyepiece. What is the focal length of the objective lens?

For an astronomical telescope to produce bright images of faint stars, the objective lens must be large to allow in as much light as possible. Indeed, the diameter of the objective lens (and hence its "light-gathering power") is an important parameter for an astronomical telescope, which is why the largest ones are specified by giving the objective diameter (such as the 10 -meter Keck telescope in Hawaii). The construction and grinding of large lenses is very difficult. Therefore, the largest telescopes are reflecting telescopes which use curved mirror as the objective, Fig. 25-22. A mirror has only one surface to be ground and can be supported along its entire surface ${ }^{\dagger}$ (a large lens, supported at its edges, would sag under its own weight). Often, the eyepiece lens or mirror (see Fig. 25-22) is removed so that the real image formed by the objective mirror can be recorded directly on film or on an electronic sensor (CCD or CMOS, Section 25-1).

FIGURE 25-22 A concave mirror can be used as the objective of an astronomical telescope. Arrangement (a) is called the Newtonian focus, and (b) the Cassegrainian focus. Other arrangements are also possible. (c) The 200-inch (mirror diameter) Hale telescope on Palomar Mountain in California. (d) The 10 -meter Keck telescope on Mauna Kea, Hawaii. The Keck combines thirty-six 1.8 -meter six-sided mirrors into the equivalent of a very large single reflector, 10 m in diameter.

A terrestrial telescope, for viewing objects on Earth, must provide an upright image-seeing normal objects upside down would be difficult (much less important for viewing stars). Two designs are shown in Fig. 25-23. The Galilean type, which Galileo used for his great astronomical discoveries, has a diverging lens as eyepiece which intercepts the converging rays from the objective lens before they reach a focus, and acts to form a virtual upright image, Fig. 25-23a. This design is still used in opera glasses. The tube is reasonably short, but the field of view is small. The second type, shown in Fig. 25-23b, is often called a spyglass and makes use of a third convex lens that acts to make the image upright as shown. A spyglass must be quite long. The most practical design today is the prism binocular which was shown in Fig. 23-28. The objective and eyepiece are converging lenses. The prisms reflect the rays by total internal reflection and shorten the physical size of the device, and they also act to produce an upright image. One prism reinverts the image in the vertical plane, the other in the horizontal plane.
${ }^{\dagger}$ Another advantage of mirrors is that they exhibit no chromatic aberration because the light doesn't pass through them; and they can be ground into a parabolic shape to correct for spherical aberration (Section 25-6). The reflecting telescope was first proposed by Newton.

FIGURE 25-23 Terrestrial telescopes that produce an upright image: (a) Galilean; (b) spyglass, or erector type.

(a)

(b)

SECTION 25-4
725

---

<!-- Page 726 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 726

25-5 Compound Microscope
PHYSICS APPLIED
Microscopes

The compound microscope, like the telescope, has both objective and eyepiece (or ocular) lenses, Fig. 25-24. The design is different from that for a telescope because a microscope is used to view objects that are very close, so the object distance is very small. The object is placed just beyond the objective's focal point as shown in Fig. 25-24a. The image $\mathrm{I}_{1}$ formed by the objective lens is real, quite far from the objective lens, and much enlarged. The eyepiece is positioned so that this image is near the eyepiece focal point $\mathrm{F}_{\mathrm{e}}$. The image $\mathrm{I}_{1}$ is magnified by the eyepiece into a very large virtual image, $\mathrm{I}_{2}$, which is seen by the eye and is inverted. Modern microscopes use a third "tube" lens behind the objective, but we will analyze the simpler arrangement shown in Fig. 25-24a.

FIGURE 25-24 Compound microscope: (a) ray diagram, (b) photograph (illumination comes from below, outlined in red, then up through the slide holding the sample or object).

$\square$

The overall magnification of a microscope is the product of the magnifications produced by the two lenses. The image $\mathrm{I}_{1}$ formed by the objective lens is a factor $m_{\mathrm{o}}$ greater than the object itself. From Fig. 25-24a and Eq. 23-9 for the magnification of a simple lens, we have
$$m_{\mathrm{o}}=\frac{h_{\mathrm{i}}}{h_{\mathrm{o}}}=\frac{d_{\mathrm{i}}}{d_{\mathrm{o}}}=\frac{\ell-f_{\mathrm{e}}}{d_{\mathrm{o}}},$$
where $d_{\mathrm{o}}$ and $d_{\mathrm{i}}$ are the object and image distances for the objective lens, $\ell$ is the distance between the lenses (equal to the length of the barrel), and we ignored the minus sign in Eq. 23-9 which only tells us that the image is inverted. We set $d_{\mathrm{i}}=\ell-f_{\mathrm{e}}$, which is exact only if the eye is relaxed, so that the image $\mathrm{I}_{1}$ is at the eyepiece focal point $\mathrm{F}_{\mathrm{e}}$. The eyepiece acts like a simple magnifier. If we assume that the eye is relaxed, the eyepiece angular magnification $M_{\mathrm{e}}$ is (from Eq. 25-2a)
$$M_{\mathrm{e}}=\frac{N}{f_{\mathrm{e}}},$$
where the near point $N=25 \mathrm{~cm}$ for the normal eye. Since the eyepiece enlarges the image formed by the objective, the overall angular magnification $M$ is the product of the magnification of the objective lens, $m_{\mathrm{O}}$, times the angular magnification, $M_{\mathrm{e}}$, of the eyepiece lens (Eqs. 25-4 and 25-5):
$$\begin{aligned}
M & =M_{\mathrm{e}} m_{\mathrm{o}}=\left(\frac{N}{f_{\mathrm{e}}}\right)\left(\frac{\ell-f_{\mathrm{e}}}{d_{\mathrm{o}}}\right) & & {\left[\begin{array}{c}
\text { microscope } \\
\text { magnification }
\end{array}\right] } \\
& \approx \frac{N \ell}{f_{\mathrm{e}} f_{\mathrm{o}}} . & & {\left[f_{\mathrm{o}} \text { and } f_{\mathrm{e}} \ll \ell\right] }
\end{aligned}$$

The approximation, Eq. 25-6b, is accurate when $f_{\mathrm{e}}$ and $f_{\mathrm{o}}$ are small compared to $\ell$, so $\ell-f_{\mathrm{e}} \approx \ell$, and the object is near $\mathrm{F}_{\mathrm{o}}$ so $d_{\mathrm{o}} \approx f_{\mathrm{o}}$ (Fig. 25-24a). This is a good approximation for large magnifications, which are obtained when $f_{\mathrm{o}}$ and $f_{\mathrm{e}}$ are very small (they are in the denominator of Eq. 25-6b). To make lenses of very short focal length, compound lenses involving several elements must be used to avoid serious aberrations, as discussed in the next Section.

726
CHAPTER 25

---

<!-- Page 727 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 727

EXAMPLE 25-9 Microscope. A compound microscope consists of a $10 \times$ eyepiece and a $50 \times$ objective 17.0 cm apart. Determine ( $a$ ) the overall magnification, (b) the focal length of each lens, and (c) the position of the object when the final image is in focus with the eye relaxed. Assume a normal eye, so $N=25 \mathrm{~cm}$.
APPROACH The overall magnification is the product of the eyepiece magnification and the objective magnification. The focal length of the eyepiece is found from Eq. 25-2a or 25-5 for the magnification of a simple magnifier. For the objective lens, it is easier to next find $d_{\mathrm{o}}$ (part $c$ ) using Eq. 25-4 before we find $f_{\mathrm{o}}$.
SOLUTION (a) The overall magnification is $(10 \times)(50 \times)=500 \times$.
(b) The eyepiece focal length is (Eq. 25-5) $f_{\mathrm{e}}=N / M_{\mathrm{e}}=25 \mathrm{~cm} / 10=2.5 \mathrm{~cm}$. Next we solve Eq. 25-4 for $d_{\mathrm{o}}$, and find
$$d_{\mathrm{o}}=\frac{\ell-f_{\mathrm{e}}}{m_{\mathrm{o}}}=\frac{(17.0 \mathrm{~cm}-2.5 \mathrm{~cm})}{50}=0.29 \mathrm{~cm} .$$

Then, from the thin lens equation for the objective with $d_{\mathrm{i}}=\ell-f_{\mathrm{e}}=14.5 \mathrm{~cm}$ (see Fig. 25-24a),
$$\frac{1}{f_{\mathrm{o}}}=\frac{1}{d_{\mathrm{o}}}+\frac{1}{d_{\mathrm{i}}}=\frac{1}{0.29 \mathrm{~cm}}+\frac{1}{14.5 \mathrm{~cm}}=3.52 \mathrm{~cm}^{-1} ;$$
so $f_{\mathrm{o}}=1 /\left(3.52 \mathrm{~cm}^{-1}\right)=0.28 \mathrm{~cm}$.
(c) We just calculated $d_{\mathrm{o}}=0.29 \mathrm{~cm}$, which is very close to $f_{\mathrm{o}}$.

25-6 Aberrations of Lenses and Mirrors
In Chapter 23 we developed a theory of image formation by a thin lens. We found, for example, that all rays from each point on an object are brought to a single point as the image point. This result, and others, were based on approximations for a thin lens, mainly that all rays make small angles with the axis and that we can use $\sin \theta \approx \theta$. Because of these approximations, we expect deviations from the simple theory, which are referred to as lens aberrations. There are several types of aberration; we will briefly discuss each of them separately, but all may be present at one time.

Consider an object at any point (even at infinity) on the axis of a lens with spherical surfaces. Rays from this point that pass through the outer regions of the lens are brought to a focus at a different point from those that pass through the center of the lens. This is called spherical aberration, and is shown exaggerated in Fig. 25-25. Consequently, the image seen on a screen or film will not be a point but a tiny circular patch of light. If the sensor or film is placed at the point C , as indicated, the circle will have its smallest diameter, which is referred to as the circle of least confusion. Spherical aberration is present whenever spherical surfaces are used. It can be reduced by using nonspherical (= aspherical) lens surfaces, but grinding such lenses is difficult and expensive. Spherical aberration can be reduced by the use of several lenses in combination, and by using primarily the central part of lenses.

For object points off the lens axis, additional aberrations occur. Rays passing through the different parts of the lens cause spreading of the image that is noncircular. There are two effects: coma (because the image of a point is cometshaped rather than a tiny circle) and off-axis astigmatism. ${ }^{\dagger}$ Furthermore, the image points for objects off the axis but at the same distance from the lens do not fall on a flat plane but on a curved surface-that is, the focal plane is not flat. (We expect this because the points on a flat plane, such as the film in a camera, are not equidistant from the lens.) This aberration is known as curvature of field and is a problem in cameras and other devices where the sensor or film is a flat plane. In the eye, however, the retina is curved, which compensates for this effect.
${ }^{\dagger}$ Although the effect is the same as for astigmatism in the eye (Section 25-2), the cause is different. Off-axis astigmatism is no problem in the eye because objects are clearly seen only at the fovea, on the lens axis.

SECTION 25-6 Aberrations of Lenses and Mirrors
727

---

<!-- Page 728 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$ Page 728

Another aberration, distortion, is a result of variation of magnification at different distances from the lens axis. Thus a straight-line object some distance from the axis may form a curved image. A square grid of lines may be distorted to produce "barrel distortion," or "pincushion distortion," Fig. 25-26. The former is common in extreme wide-angle lenses.

FIGURE 25-26 Distortion: lenses may image a square grid of perpendicular lines to produce (a) barrel distortion or (b) pincushion distortion. These distortions can be seen in the photograph of Fig. 23-31d for a simple lens.

FIGURE 25-27 Chromatic aberration. Different colors are focused at different points.

FIGURE 25-28 Achromatic doublet.

All the above aberrations occur for monochromatic light and hence are referred to as monochromatic aberrations. Normal light is not monochromatic, and there will also be chromatic aberration. This aberration arises because of dispersion-the variation of index of refraction of transparent materials with wavelength (Section 24-4). For example, blue light is bent more than red light by glass. So if white light is incident on a lens, the different colors are focused at different points, Fig. 25-27, and have slightly different magnifications resulting in colored fringes in the image. Chromatic aberration can be eliminated for any two colors (and reduced greatly for all others) by the use of two lenses made of different materials with different indices of refraction and dispersion. Normally one lens is converging and the other diverging, and they are often cemented together (Fig. 25-28). Such a lens combination is called an achromatic doublet (or "color-corrected" lens).

To reduce aberrations, high-quality lenses are compound lenses consisting of many simple lenses, referred to as elements. A typical high-quality camera lens may contain six to eight (or more) elements. For simplicity we will usually indicate lenses in diagrams as if they were simple lenses.

The human eye is also subject to aberrations, but they are minimal. Spherical aberration, for example, is minimized because (1) the cornea is less curved at the edges than at the center, and (2) the lens is less dense at the edges than at the center. Both effects cause rays at the outer edges to be bent less strongly, and thus help to reduce spherical aberration. Chromatic aberration is partially compensated for because the lens absorbs the shorter wavelengths appreciably and the retina is less sensitive to the blue and violet wavelengths. This is just the region of the spectrum where dispersion-and thus chromatic aberration-is greatest (Fig. 24-14).

Spherical mirrors (Section 23-3) also suffer aberrations including spherical aberration (see Fig. 23-13). Mirrors can be ground in a parabolic shape to correct for aberrations, but they are much harder to make and therefore very expensive. Spherical mirrors do not, however, exhibit chromatic aberration because the light does not pass through them (no refraction, no dispersion).

25-7 Limits of Resolution; Circular Apertures

The ability of a lens to produce distinct images of two point objects very close together is called the resolution of the lens. The closer the two images can be and still be seen as distinct (rather than overlapping blobs), the higher the resolution. The resolution of a camera lens, for example, is often specified as so many dots or lines per millimeter, as mentioned in Section 25-1.

728
CHAPTER 25 Optical Instruments

---

<!-- Page 729 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 729

Two principal factors limit the resolution of a lens. The first is lens aberrations. As we just saw, because of spherical and other aberrations, a point object is not a point on the image but a tiny blob. Careful design of compound lenses can reduce aberrations significantly, but they cannot be eliminated entirely. The second factor that limits resolution is diffraction, which cannot be corrected for because it is a natural result of the wave nature of light. We discuss it now.

In Section 24-5, we saw that because light travels as a wave, light from a point source passing through a slit is spread out into a diffraction pattern (Figs. 24-19 and 24-21). A lens, because it has edges, acts like a round slit. When a lens forms the image of a point object, the image is actually a tiny diffraction pattern. Thus an image would be blurred even if aberrations were absent.

In the analysis that follows, we assume that the lens is free of aberrations, so we can concentrate on diffraction effects and how much they limit the resolution of a lens. In Fig. 24-21 we saw that the diffraction pattern produced by light passing through a rectangular slit has a central maximum in which most of the light falls. This central peak falls to a minimum on either side of its center at an angle $\theta$ given by
$$\sin \theta=\lambda / D$$
(this is Eq. 24-3a), where $D$ is the slit width and $\lambda$ the wavelength of light used. $\theta$ is the angular half-width of the central maximum, and for small angles (in radians) can be written
$$\theta \approx \sin \theta=\frac{\lambda}{D} .$$

There are also low-intensity fringes beyond.
For a lens, or any circular hole, the image of a point object will consist of a circular central peak (called the diffraction spot or Airy disk) surrounded by faint circular fringes, as shown in Fig. 25-29a. The central maximum has an angular half-width given by
$$\theta=\frac{1.22 \lambda}{D},$$
where $D$ is the diameter of the circular opening. [This is a theoretical result for a perfect circle or lens. For real lenses or circles, the factor is on the order of 1 to 2.] This formula differs from that for a slit (Eq. 24-3) by the factor 1.22. This factor appears because the width of a circular hole is not uniform (like a rectangular slit) but varies from its diameter $D$ to zero. A mathematical analysis shows that the "average" width is $D / 1.22$. Hence we get the equation above rather than Eq. 24-3. The intensity of light in the diffraction pattern from a point source of light passing through a circular opening is shown in Fig. 25-30. The image for a non-point source is a superposition of such patterns. For most purposes we need consider only the central spot, since the concentric rings are so much dimmer.

If two point objects are very close, the diffraction patterns of their images will overlap as shown in Fig. 25-29b. As the objects are moved closer, a separation is reached where you can't tell if there are two overlapping images or a single image. The separation at which this happens may be judged differently by different observers. However, a generally accepted criterion is that proposed by Lord Rayleigh (1842-1919). This Rayleigh criterion states that two images are just resolvable when the center of the diffraction disk of one image is directly over the first minimum in the diffraction pattern of the other. This is shown in Fig. 25-31. Since the first minimum is at an angle $\theta=1.22 \lambda / D$ from the central maximum, Fig. 25-31 shows that two objects can be considered just resolvable if they are separated by at least an angle $\theta$ given by
$$\theta=\frac{1.22 \lambda}{D} . \quad\left[\begin{array}{l}
2 \text { points just resolvable; } \\
\theta \text { in radians }
\end{array}\right]$$

In this equation, $D$ is the diameter of the lens, and applies also to a mirror diameter. This is the limit on resolution set by the wave nature of light due to diffraction. A smaller angle means better resolution: you can make out closer objects. We see from Eq. 25-7 that using a shorter wavelength $\lambda$ can reduce $\theta$ and thus increase resolution.

(a)

(b)

FIGURE 25-29 Photographs of images (greatly magnified) formed by a lens, showing the diffraction pattern of an image for: (a) a single point object; (b) two point objects whose images are barely resolved.

FIGURE 25-30 Intensity of light across the diffraction pattern of a circular hole.

FIGURE 25-31 The Rayleigh criterion. Two images are just resolvable when the center of the diffraction peak of one is directly over the first minimum in the diffraction pattern of the other. The two point objects O and $\mathrm{O}^{\prime}$ subtend an angle $\theta$ at the lens; only one ray (it passes through the center of the lens) is drawn for each object, to indicate the center of the diffraction pattern of its image.

SECTION 25-7 Limits of Resolution; Circular Apertures
729

---

<!-- Page 730 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD
29-08-2014 $15: 16$
Page
730

FIGURE 25-32 Hubble Space Telescope, with Earth in the background. The flat orange panels are solar cells that collect energy from the Sun to power the equipment.

> PHYSICS APPLIED
> How well the eye can see

EXAMPLE 25-10 Hubble Space Telescope. The Hubble Space Telescope (HST) is a reflecting telescope that was placed in orbit above the Earth's atmosphere, so its resolution would not be limited by turbulence in the atmosphere (Fig. 25-32). Its objective diameter is 2.4 m . For visible light, say $\lambda=550 \mathrm{~nm}$, estimate the improvement in resolution the Hubble offers over Earth-bound telescopes, which are limited in resolution by movement of the Earth's atmosphere to about half an arc second. (Each degree is divided into 60 minutes each containing 60 seconds, so $1^{\circ}=3600$ arc seconds.)
APPROACH Angular resolution for the Hubble is given (in radians) by Eq. 25-7. The resolution for Earth telescopes is given, and we first convert it to radians so we can compare.
SOLUTION Earth-bound telescopes are limited to an angular resolution of
$$\theta=\frac{1}{2}\left(\frac{1}{3600}\right)^{\circ}\left(\frac{2 \pi \mathrm{rad}}{360^{\circ}}\right)=2.4 \times 10^{-6} \mathrm{rad} .$$

The Hubble, on the other hand, is limited by diffraction (Eq. 25-7) which for $\lambda=550 \mathrm{~nm}$ is
$$\theta=\frac{1.22 \lambda}{D}=\frac{1.22\left(550 \times 10^{-9} \mathrm{~m}\right)}{2.4 \mathrm{~m}}=2.8 \times 10^{-7} \mathrm{rad},$$
thus giving almost ten times better resolution ( $2.4 \times 10^{-6} \mathrm{rad} / 2.8 \times 10^{-7} \mathrm{rad} \approx 9 \times$ ).

EXAMPLE 25-11 ESTIMATE Eye resolution. You are in an airplane at an altitude of $10,000 \mathrm{~m}$. If you look down at the ground, estimate the minimum separation $s$ between objects that you could distinguish. Could you count cars in a parking lot? Consider only diffraction, and assume your pupil is about 3.0 mm in diameter and $\lambda=550 \mathrm{~nm}$.
APPROACH We use the Rayleigh criterion, Eq. 25-7, to estimate $\theta$. The separation $s$ of objects is $s=\ell \theta$, where $\ell=10^{4} \mathrm{~m}$ and $\theta$ is in radians.
SOLUTION In Eq. 25-7, we set $D=3.0 \mathrm{~mm}$ for the opening of the eye:
$$\begin{aligned}
s=\ell \theta & =\ell \frac{1.22 \lambda}{D} \\
& =\left(10^{4} \mathrm{~m}\right) \frac{(1.22)\left(550 \times 10^{-9} \mathrm{~m}\right)}{3.0 \times 10^{-3} \mathrm{~m}}=2.2 \mathrm{~m}
\end{aligned}$$

Yes, you could just resolve a car (roughly 2 m wide by 3 or 4 m long) and so could count the number of cars in the lot.

EXERCISE E Someone claims a spy satellite camera can see 3-cm-high newspaper headlines from an altitude of 100 km . If diffraction were the only limitation ( $\lambda=550 \mathrm{~nm}$ ), use Eq. 25-7 to determine what diameter lens the camera would have.

25-8 Resolution of Telescopes and Microscopes; the $\lambda$ Limit

You might think that a microscope or telescope could be designed to produce any desired magnification, depending on the choice of focal lengths and quality of the lenses. But this is not possible, because of diffraction. An increase in magnification above a certain point merely results in magnification of the diffraction patterns. This can be highly misleading since we might think we are seeing details of an object when we are really seeing details of the diffraction pattern.

730
CHAPTER 25 Optical Instruments

---

<!-- Page 731 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
$\_\_\_\_$

731

To examine this problem, we apply the Rayleigh criterion: two objects (or two nearby points on one object) are just resolvable if they are separated by an angle $\theta$ (Fig. 25-31) given by Eq. 25-7:
$$\theta=\frac{1.22 \lambda}{D} .$$

This formula is valid for either a microscope or a telescope, where $D$ is the diameter of the objective lens or mirror. For a telescope, the resolution is specified by stating $\theta$ as given by this equation. ${ }^{\dagger}$

EXAMPLE 25-12 Telescope resolution (radio wave vs. visible light).
What is the theoretical minimum angular separation of two stars that can just be resolved by (a) the 200-inch telescope on Palomar Mountain (Fig. 25-22c); and (b) the Arecibo radiotelescope (Fig. 25-33), whose diameter is 300 m and whose radius of curvature is also 300 m . Assume $\lambda=550 \mathrm{~nm}$ for the visible-light telescope in part (a), and $\lambda=4 \mathrm{~cm}$ (the shortest wavelength at which the radiotelescope has operated) in part (b).
APPROACH We apply the Rayleigh criterion (Eq. 25-7) for each telescope.
SOLUTION (a) With $D=200 \mathrm{in} .=5.1 \mathrm{~m}$, we have from Eq. $25-7$ that
$$\theta=\frac{1.22 \lambda}{D}=\frac{(1.22)\left(5.50 \times 10^{-7} \mathrm{~m}\right)}{(5.1 \mathrm{~m})}=1.3 \times 10^{-7} \mathrm{rad},$$
or $0.75 \times 10^{-5} \mathrm{deg}$. (Note that this is equivalent to resolving two points less than 1 cm apart from a distance of 100 km !)
(b) For radio waves with $\lambda=0.04 \mathrm{~m}$ emitted by stars, the resolution is
$$\theta=\frac{(1.22)(0.04 \mathrm{~m})}{(300 \mathrm{~m})}=1.6 \times 10^{-4} \mathrm{rad} .$$

The resolution is less because the wavelength is so much larger, but the larger objective collects more radiation and thus detects fainter objects.
NOTE In both cases, we determined the limit set by diffraction. The resolution for a visible-light Earth-bound telescope is not this good because of aberrations and, more importantly, turbulence in the atmosphere. In fact, large-diameter objectives are not justified by increased resolution, but by their greater light-gathering ability-they allow more light in, so fainter objects can be seen. Radiotelescopes are not hindered by atmospheric turbulence, and the resolution found in (b) is a good estimate.

For a microscope, it is more convenient to specify the actual distance, $s$, between two points that are just barely resolvable: see Fig. 25-31. Since objects are normally placed near the focal point of the microscope objective, the angle subtended by two objects is $\theta=s / f$, so $s=f \theta$. If we combine this with Eq. 25-7, we obtain the resolving power ( $\mathbf{R P}$ ) of a microscope
$$\mathrm{RP}=s=f \theta=\frac{1.22 \lambda f}{D}, \quad \text { [microscope] }$$
where $f$ is the objective lens' focal length (not frequency) and $D$ its diameter. The distance $s$ is called the resolving power of the lens because it is the minimum separation of two object points that can just be resolved-assuming the highest quality lens since this limit is imposed by the wave nature of light. A smaller RP means better resolution, better detail.
${ }^{\dagger}$ Earth-bound telescopes with large-diameter objectives are usually limited not by diffraction but by other effects such as turbulence in the atmosphere. The resolution of a high-quality microscope, on the other hand, normally is limited by diffraction; microscope objectives are complex compound lenses containing many elements of small diameter (since $f$ is small), thus reducing aberrations.

FIGURE 25-33 The $\mathbf{3 0 0}$-meter radiotelescope in Arecibo, Puerto Rico, uses radio waves (Fig. 22-8) instead of visible light.

PHYSICS APPLIED

Why large-diameter objectives
SECTION 25-8 Resolution of Telescopes and Microscopes; the $\lambda$ Limit
731

---

<!-- Page 732 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 732

Wavelength limits resolution

Diffraction sets an ultimate limit on the detail that can be seen on any object. In Eq. 25-8 for the resolving power of a microscope, the focal length of the lens cannot practically be made less than (approximately) the radius of the lens (= $D / 2$ ), and even that is very difficult (see the lensmaker's equation, Eq. 23-10). In this best case, Eq. 25-8 gives, with $f \approx D / 2$,
$$\mathrm{RP} \approx \frac{\lambda}{2} .$$

Thus we can say, to within a factor of 2 or so, that
it is not possible to resolve detail of objects smaller than the wavelength of the radiation being used.

This is an important and useful rule of thumb.
Compound lenses in microscopes are now designed so well that the actual limit on resolution is often set by diffraction-that is, by the wavelength of the light used. To obtain greater detail, one must use radiation of shorter wavelength. The use of UV radiation can increase the resolution by a factor of perhaps 2. Far more important, however, was the discovery in the early twentieth century that electrons have wave properties (Chapter 27) and that their wavelengths can be very small. The wave nature of electrons is utilized in the electron microscope (Section 27-9), which can magnify 100 to 1000 times more than a visible-light microscope because of the much shorter wavelengths. X-rays, too, have very short wavelengths and are often used to study objects in great detail (Section 25-11).

25-9 Resolution of the Human Eye and Useful Magnification
The resolution of the human eye is limited by several factors, all of roughly the same order of magnitude. The resolution is best at the fovea, where the cone spacing is smallest, about $3 \mu \mathrm{~m}(=3000 \mathrm{~nm})$. The diameter of the pupil varies from about 0.1 cm to about 0.8 cm . So for $\lambda=550 \mathrm{~nm}$ (where the eye's sensitivity is greatest), the diffraction limit is about $\theta \approx 1.22 \lambda / D \approx 8 \times 10^{-5} \mathrm{rad}$ to $6 \times 10^{-4} \mathrm{rad}$. The eye is about 2 cm long, giving a resolving power (Eq. 25-8) of $s \approx\left(2 \times 10^{-2} \mathrm{~m}\right)\left(8 \times 10^{-5} \mathrm{rad}\right) \approx 2 \mu \mathrm{~m}$ at best, to about $10 \mu \mathrm{~m}$ at worst (pupil small). Spherical and chromatic aberration also limit the resolution to about $10 \mu \mathrm{~m}$. The net result is that the eye can just resolve objects whose angular separation is around
$$5 \times 10^{-4} \mathrm{rad} . \quad\left[\begin{array}{c}
\text { best eye } \\
\text { resolution }
\end{array}\right]$$

This corresponds to objects separated by 1 cm at a distance of about 20 m .
The typical near point of a human eye is about 25 cm . At this distance, the eye can just resolve objects that are $(25 \mathrm{~cm})\left(5 \times 10^{-4} \mathrm{rad}\right) \approx 10^{-4} \mathrm{~m}=\frac{1}{10} \mathrm{~mm}$ apart. ${ }^{\dagger}$ Since the best light microscopes can resolve objects no smaller than about 200 nm at best (Eq. 25-9 for violet light, $\lambda=400 \mathrm{~nm}$ ), the useful magnification [= (resolution by naked eye)/(resolution by microscope)] is limited to about
$$\frac{10^{-4} \mathrm{~m}}{200 \times 10^{-9} \mathrm{~m}} \approx 500 \times . \quad\left[\begin{array}{c}
\text { maximum useful } \\
\text { microscope magnification }
\end{array}\right]$$

In practice, magnifications of about $1000 \times$ are often used to minimize eyestrain. Any greater magnification would simply make visible the diffraction pattern produced by the microscope objective lens.

EXERCISE F Return to the Chapter-Opening Question, page 713, and answer it again now. Try to explain why you may have answered differently the first time.
${ }^{\dagger}$ A nearsighted eye that needs -8 or -10 D lenses can have a near point of 8 or 10 cm , and a higher resolution up close (without glasses) of a factor of $2 \frac{1}{2}$ or 3, or $\approx \frac{1}{25} \mathrm{~mm} \approx 40 \mu \mathrm{~m}$.

732
CHAPTER 25 Optical Instruments

---

<!-- Page 733 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 733

*25-10 Specialty Microscopes and Contrast
All the resolving power a microscope can attain will be useless if the object to be seen cannot be distinguished from the background. The difference in brightness between the image of an object and the image of the surroundings is called contrast. Achieving high contrast is an important problem in microscopy and other forms of imaging. The problem arises in biology, for example, because cells consist largely of water and are almost uniformly transparent to light. We now briefly discuss two special types of microscope that can increase contrast: the interference and phase-contrast microscopes.

An interference microscope makes use of the wave properties of light in a direct way to increase contrast in a transparent object. Consider a transparent object-say, a bacterium in water (Fig. 25-34). Coherent light enters uniformly from the left and is in phase at all points such as a and b . If the object is as transparent as the water, the beam leaving at d will be as bright as that at c . There will be no contrast and the object will not be seen. However, if the object's refractive index is slightly different from that of the surrounding medium, the wavelength within the object will be altered as shown. Hence light waves at points c and d will differ in phase, if not in amplitude. The interference microscope changes this difference in phase into a difference of amplitude which our eyes can detect. Light that passes through the sample is superimposed onto a reference beam that does not pass through the object, so that they interfere. One way of doing this is shown in Fig. 25-35. Light from a source is split into two equal beams by a half-silvered mirror, $\mathrm{MS}_{1}$. One beam passes through the object, and the second (comparison beam) passes through an identical system without the object. The two meet again and are superposed by the half-silvered mirror $\mathrm{MS}_{2}$ before entering the eyepiece and eye. The path length (and amplitude) of the comparison beam is adjustable so that the background can be dark; that is, full destructive interference occurs. Light passing through the object (beam bd in Fig. 25-34) will also interfere with the comparison beam. But because of its different phase, the interference will not be completely destructive. Thus it will appear brighter than the background. Where the object varies in thickness, the phase difference between beams ac and bd in Fig. 25-34 will be different, thus affecting the amount of interference. Hence variation in the thickness of the object will appear as variations in brightness in the image.

A phase-contrast microscope also makes use of interference and differences in phase to produce a high-contrast image. Contrast is achieved by a circular glass phase plate that has a groove (or a raised portion) in the shape of a ring, positioned so undeviated source rays pass through it, but rays deviated by the object do not pass through this ring. Because the rays deviated by the object travel through a different thickness of glass than the undeviated source rays, the two can be out of phase and can interfere destructively at the object image plane. Thus the image of the object can contrast sharply with the background. Phase-contrast microscope images tend to have "halos" around them (as a result of diffraction from the phase-plate opening), so care must be taken in the interpretation of images.
25-11 X-Rays and X-Ray Diffraction
In 1895, W. C. Roentgen (1845-1923) discovered that when electrons were accelerated by a high voltage in a vacuum tube and allowed to strike a glass or metal surface inside the tube, fluorescent minerals some distance away would glow, and photographic film would become exposed. Roentgen attributed these effects to a new type of radiation (different from cathode rays). They were given the name X-rays after the algebraic symbol $x$, meaning an unknown quantity. He soon found that X-rays penetrated through some materials better than through others, and within a few weeks he presented the first X-ray photograph (of his wife's hand). The production of X-rays today is usually done in a tube (Fig. 25-36) similar to Roentgen's, using voltages of typically 30 kV to 150 kV .

FIGURE 25-34 Object-say, a bacterium-in a water solution.

PHYSICS APPLIED
Interference microscope

FIGURE 25-35 Diagram of an interference microscope.

PHYSICS APPLIED
Phase-contrast microscope

FIGURE 25-36 X-ray tube. Electrons emitted by a heated filament in a vacuum tube are accelerated by a high voltage. When they strike the surface of the anode, the "target," X-rays are emitted.

SECTION 25-11 X-Rays and X-Ray Diffraction
733

---

<!-- Page 734 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
734

FIGURE 25-37 This X-ray diffraction pattern is one of the first observed by Max von Laue in 1912 when he aimed a beam of X-rays at a zinc sulfide crystal. The diffraction pattern was detected directly on a photographic plate.

FIGURE 25-38 X-ray diffraction by a crystal.

Investigations into the nature of X-rays indicated they were not charged particles (such as electrons) since they could not be deflected by electric or magnetic fields. It was suggested that they might be a form of invisible light. However, they showed no diffraction or interference effects using ordinary gratings. Indeed, if their wavelengths were much smaller than the typical grating spacing of $10^{-6} \mathrm{~m}\left(=10^{3} \mathrm{~nm}\right)$, no effects would be expected. Around 1912, Max von Laue (1879-1960) suggested that if the atoms in a crystal were arranged in a regular array (see Fig. 13-2a), such a crystal might serve as a diffraction grating for very short wavelengths on the order of the spacing between atoms, estimated to be about $10^{-10} \mathrm{~m}\left(=10^{-1} \mathrm{~nm}\right)$. Experiments soon showed that X-rays scattered from a crystal did indeed show the peaks and valleys of a diffraction pattern (Fig. 25-37). Thus it was shown, in a single blow, that X-rays have a wave nature and that atoms are arranged in a regular way in crystals. Today, X-rays are recognized as electromagnetic radiation with wavelengths in the range of about $10^{-2} \mathrm{~nm}$ to 10 nm , the range readily produced in an X-ray tube.

X-Ray Diffraction
We saw in Sections 25-7 and 25-8 that light of shorter wavelength provides greater resolution when we are examining an object microscopically. Since X-rays have much shorter wavelengths than visible light, they should in principle offer much greater resolution. However, there seems to be no effective material to use as lenses for the very short wavelengths of X-rays. Instead, the clever but complicated technique of X-ray diffraction (or crystallography) has proved very effective for examining the microscopic world of atoms and molecules. In a simple crystal such as NaCl , the atoms are arranged in an orderly cubical fashion, Fig. 25-38, with atoms spaced a distance $d$ apart. Suppose that a beam of X-rays is incident on the crystal at an angle $\phi$ to the surface, and that the two rays shown are reflected from two subsequent planes of atoms as shown. The two rays will constructively interfere if the extra distance ray I travels is a whole number of wavelengths farther than the distance ray II travels. This extra distance is $2 d \sin \phi$. Therefore, constructive interference will occur when
$$m \lambda=2 d \sin \phi, \quad m=1,2,3, \cdots,$$
where $m$ can be any integer. (Notice that $\phi$ is not the angle with respect to the normal to the surface.) This is called the Bragg equation after W. L. Bragg (1890-1971), who derived it and who, together with his father, W. H. Bragg (1862-1942), developed the theory and technique of X-ray diffraction by crystals in 1912-1913. If the X-ray wavelength is known and the angle $\phi$ is measured, the distance $d$ between atoms can be obtained. This is the basis for X-ray crystallography.

FIGURE 25-39 X-rays can be diffracted from many possible planes within a crystal.

EXERCISE G When X-rays of wavelength $0.10 \times 10^{-9} \mathrm{~m}$ are scattered from a sodium chloride crystal, a second-order diffraction peak is observed at $21^{\circ}$. What is the spacing between the planes of atoms for this scattering?

Actual X-ray diffraction patterns are quite complicated. First of all, a crystal is a three-dimensional object, and X-rays can be diffracted from different planes at different angles within the crystal, as shown in Fig. 25-39. Although the analysis is complex, a great deal can be learned from X-ray diffraction about any substance that can be put in crystalline form.

734
CHAPTER 25 Optical Instruments

---

<!-- Page 735 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 735

X-ray diffraction has been very useful in determining the structure of biologically important molecules, such as the double helix structure of DNA, worked out by James Watson and Francis Crick in 1953. See Fig. 25-40, and for models of the double helix, Figs. 16-39a and 16-40. Around 1960, the first detailed structure of a protein molecule, myoglobin, was elucidated with the aid of X-ray diffraction. Soon the structure of an important constituent of blood, hemoglobin, was worked out, and since then the structures of a great many molecules have been determined with the help of X-rays.
*25-12 X-Ray Imaging and Computed Tomography (CT Scan)
* Normal X-Ray Image

For a conventional medical or dental X-ray photograph, the X-rays emerging from the tube (Fig. 25-36) pass through the body and are detected on photographic film, a digital sensor, or a fluorescent screen, Fig. 25-41. The rays travel in very nearly straight lines through the body with minimal deviation since at X-ray wavelengths there is little diffraction or refraction. There is absorption (and scattering), however; and the difference in absorption by different structures in the body is what gives rise to the image produced by the transmitted rays. The less the absorption, the greater the transmission and the darker the film. The image is, in a sense, a "shadow" of what the rays have passed through. The X-ray image is not produced by focusing rays with lenses as for the instruments discussed earlier in this Chapter.
*Tomography Images (CT)
In conventional X-ray images, a body's thickness is projected onto film or a sensor; structures overlap and in many cases are difficult to distinguish. In the 1970s, a revolutionary X-ray technique was developed called computed tomography (CT), which produces an image of a slice through the body. (The word tomography comes from the Greek: tomos $=$ slice, graph $=$ picture.) Structures and lesions previously impossible to visualize can now be seen with remarkable clarity. The principle behind CT is shown in Fig. 25-42: a thin collimated (parallel) beam of X-rays passes through the body to a detector that measures the transmitted intensity. Measurements are made at a large number of points as the source and detector are moved past the body together. The apparatus is then rotated slightly about the body axis and again scanned; this is repeated at (perhaps) $1^{\circ}$ intervals for $180^{\circ}$. The intensity of the transmitted beam for the many points of each scan, and for each angle, is sent to a computer that reconstructs the image of the slice. Note that the imaged slice is perpendicular to the long axis of the body. For this reason, CT is sometimes called computerized axial tomography (CAT), although the abbreviation CAT, as in CAT scan, can also be read as computer-assisted tomography.

FIGURE 25-40 X-ray diffraction photo of DNA molecules taken by Rosalind Franklin in the early 1950s. The cross of spots suggested that DNA is a helix.

PHYSICS APPLIED
Normal X-ray image

↑ CAUTION
Normal X-ray image is a sort of shadow (no lenses are involved)

FIGURE 25-41 Conventional X-ray imaging, which is essentially shadowing.
© physics applied
Computed tomography images (CT or CAT scans)

FIGURE 25-42 Tomographic imaging: the X-ray source and detector move together across the body, the transmitted intensity being measured at a large number of points. Then the "source-detector" assembly is rotated slightly (say, $1^{\circ}$ ) around a vertical axis, and another scan is made. This process is repeated for perhaps $180^{\circ}$. The computer reconstructs the image of the slice and it is presented on a TV or computer monitor.

*SECTION 25-12 X-Ray Imaging and Computed Tomography (CT Scan)
735

---

<!-- Page 736 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$ Page 736

FIGURE 25-43 (a) Fan-beam scanner. Rays transmitted through the entire body are measured simultaneously at each angle. The source and detector rotate to take measurements at different angles. In another type of fan-beam scanner, there are detectors around the entire $360^{\circ}$ of the circle which remain fixed as the source moves. (b) In still another type, a beam of electrons from a source is directed by magnetic fields at tungsten targets surrounding the patient.

The use of a single detector as in Fig. 25-42 would require a few minutes for the many scans needed to form a complete image. Much faster scanners use a fan beam, Fig. 25-43a, in which beams passing through the entire cross section of the body are detected simultaneously by many detectors. The source and detectors are then rotated about the patient, and an image requires only a few seconds. Even faster, and therefore useful for heart scans, are fixed source machines wherein an electron beam is directed (by magnetic fields) to tungsten targets surrounding the patient, creating the X-rays. See Fig. 25-43b.
* Image Formation

But how is the image formed? We can think of the slice to be imaged as being divided into many tiny picture elements (or pixels), which could be squares (as in Fig. 24-49). For CT, the width of each pixel is chosen according to the width of the detectors and/or the width of the X-ray beams, and this determines the resolution of the image, which might be 1 mm . An X-ray detector measures the intensity of the transmitted beam. Subtracting this value from the intensity of the beam at the source yields the total absorption (called a "projection") along that beam line. Complicated mathematical techniques are used to analyze all the absorption projections for the huge number of beam scans measured (see the next Subsection), obtaining the absorption at each pixel and assigning each a "grayness value" according to how much radiation was absorbed. The image is made up of tiny spots (pixels) of varying shades of gray. Often the amount of absorption is color-coded. The colors in the resulting false-color image have nothing to do, however, with the actual color of the object. The actual images are monochromatic (various shades of gray, depending on the absorption). Only visible light has color; X-rays do not.

Figure 25-44 illustrates what actual CT images look like. It is generally agreed that CT scanning has revolutionized some areas of medicine by providing much less invasive, and/or more accurate, diagnosis.

Computed tomography can also be applied to ultrasound imaging

(b)
(Section 12-9) and to emissions from radioisotopes and nuclear magnetic resonance (Sections 31-8 and 31-9).
*Tomographic Image Reconstruction
How can the "grayness" of each pixel be determined even though all we can measure is the total absorption along each beam line in the slice? It can be done only by using the many beam scans made at a great many different angles. Suppose the image is to be an array of $100 \times 100$ elements for a total of $10^{4}$ pixels. If we have 100 detectors and measure the absorption projections at 100 different angles, then we get $10^{4}$ pieces of information. From this information, an image can be reconstructed, but not precisely. If more angles are measured, the reconstruction of the image can be done more accurately.

736
CHAPTER 25 Optical Instruments

---

<!-- Page 737 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 737

To suggest how mathematical reconstruction is done, we consider a very simple case using the iterative technique ("to iterate" is from the Latin "to repeat"). Suppose our sample slice is divided into the simple $2 \times 2$ pixels as shown in Fig. 25-45. The number inside each pixel represents the amount of absorption by the material in that area (say, in tenths of a percent): that is, 4 represents twice as much absorption as 2 . But we cannot directly measure these values-they are the unknowns we want to solve for. All we can measure are the projections-the total absorption along each beam line-and these are shown in Fig. 25-45 outside the yellow squares as the sum of the absorptions for the pixels along each line at four different angles. These projections (given at the tip of each arrow) are what we can measure, and we now want to work back from them to see how close we can get to the true absorption value for each pixel. We start our analysis with each pixel being assigned a zero value, Fig. 25-46a. In the iterative technique, we use the projections to estimate the absorption value in each square, and repeat for each angle. The angle 1 projections are 7 and 13 (Fig. 25-45). We divide each of these equally between their two squares: each square in the left column of Fig. 25-46a gets $3 \frac{1}{2}$ (half of 7), and each square in the right column gets $6 \frac{1}{2}$ (half of 13).

FIGURE 25-45 A simple $2 \times 2$ image showing true absorption values (inside the squares) and measured projections.

(a)

FIGURE 25-46 Reconstructing the image using projections in an iterative procedure.

(d)

Next we use the projections at angle 2. We calculate the difference between the measured projections at angle 2 ( 6 and 14 ) and the projections based on the previous estimate (top row: $3 \frac{1}{2}+6 \frac{1}{2}=10$; same for bottom row). Then we distribute this difference equally to the squares in that row. For the top row, we have
$$3 \frac{1}{2}+\frac{6-10}{2}=1 \frac{1}{2} \quad \text { and } \quad 6 \frac{1}{2}+\frac{6-10}{2}=4 \frac{1}{2} ;$$
and for the bottom row,
$$3 \frac{1}{2}+\frac{14-10}{2}=5 \frac{1}{2} \quad \text { and } \quad 6 \frac{1}{2}+\frac{14-10}{2}=8 \frac{1}{2} .$$

These values are inserted as shown in Fig. 25-46c. Next, the projection at angle 3 $(=11)$, combined with the difference as above, gives
(upper left) $1 \frac{1}{2}+\frac{11-10}{2}=2$ and (lower right) $8 \frac{1}{2}+\frac{11-10}{2}=9$;
and then for angle 4 we have
(lower left) $5 \frac{1}{2}+\frac{9-10}{2}=5 \quad$ and (upper right) $4 \frac{1}{2}+\frac{9-10}{2}=4$.
The result, shown in Fig. 25-46d, corresponds exactly to the true values. (In real situations, the true values are not known, which is why these computer techniques are required.) To obtain these numbers exactly, we used six pieces of information (two each at angles 1 and 2, one each at angles 3 and 4). For the much larger number of pixels used for actual images, exact values are generally not attained. Many iterations may be needed, and the calculation is considered sufficiently precise when the difference between calculated and measured projections is sufficiently small. The above example illustrates the "convergence" of the process: the first iteration (b to c in Fig. 25-46) changed the values by 2, the last iteration (c to d) by only $\frac{1}{2}$.

*SECTION 25-12 X-Ray Imaging and Computed Tomography (CT Scan)
737

---

<!-- Page 738 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
738

Summary

A camera lens forms an image on film, or on an electronic sensor (CCD or CMOS) in a digital camera. Light is allowed in briefly through a shutter. The image is focused by moving the lens relative to the film or sensor, and the $\boldsymbol{f}$-stop (or lens opening) must be adjusted for the brightness of the scene and the chosen shutter speed. The $f$-stop is defined as the ratio of the focal length to the diameter of the lens opening.

The human eye also adjusts for the available light-by opening and closing the iris. It focuses not by moving the lens, but by adjusting the shape of the lens to vary its focal length. The image is formed on the retina, which contains an array of receptors known as rods and cones.

Diverging eyeglass or contact lenses are used to correct the defect of a nearsighted eye, which cannot focus well on distant objects. Converging lenses are used to correct for defects in which the eye cannot focus on close objects.

A simple magnifier is a converging lens that forms a virtual image of an object placed at (or within) the focal point. The angular magnification, when viewed by a relaxed normal eye, is
$$M=\frac{N}{f},$$
where $f$ is the focal length of the lens and $N$ is the near point of the eye ( 25 cm for a "normal" eye).

An astronomical telescope consists of an objective lens or mirror, and an eyepiece that magnifies the real image formed by the objective. The magnification is equal to the ratio of the objective and eyepiece focal lengths, and the image is inverted:
$$M=-\frac{f_{\mathrm{o}}}{f_{\mathrm{e}}}$$

Questions
1. Why must a camera lens be moved farther from the sensor or film to focus on a closer object?
2. Why is the depth of field greater, and the image sharper, when a camera lens is "stopped down" to a larger $f$-number? Ignore diffraction.
3. Describe how diffraction affects the statement of Question 2. [Hint: See Eq. 24-3 or 25-7.]
4. Why are bifocals needed mainly by older persons and not generally by younger people?
5. Will a nearsighted person who wears corrective lenses in her glasses be able to see clearly underwater when wearing those glasses? Use a diagram to show why or why not.
6. You can tell whether people are nearsighted or farsighted by looking at the width of their face through their glasses. If a person's face appears narrower through the glasses (Fig. 25-47), is the person farsighted or nearsighted? Try to explain, but also check experimentally with friends who wear glasses.

FIGURE 25-47
Question 6.

A compound microscope also uses objective and eyepiece lenses, and the final image is inverted. The total magnification is the product of the magnifications of the two lenses and is approximately
$$M \approx \frac{N \ell}{f_{\mathrm{e}} f_{\mathrm{o}}}$$
where $\ell$ is the distance between the lenses, $N$ is the near point of the eye, and $f_{\mathrm{o}}$ and $f_{\mathrm{e}}$ are the focal lengths of objective and eyepiece, respectively.

Microscopes, telescopes, and other optical instruments are limited in the formation of sharp images by lens aberrations. These include spherical aberration, in which rays passing through the edge of a lens are not focused at the same point as those that pass near the center; and chromatic aberration, in which different colors are focused at different points. Compound lenses, consisting of several elements, can largely correct for aberrations.

The wave nature of light also limits the sharpness, or resolution, of images. Because of diffraction, it is not possible to discern details smaller than the wavelength of the radiation being used. The useful magnification of a light microscope is limited by diffraction to about $500 \times$.
[*X-rays are a form of electromagnetic radiation of very short wavelength. They are produced when high-speed electrons, accelerated by high voltage in an evacuated tube, strike a glass or metal target.]
[*Computed tomography (CT or CAT scan) uses many narrow X-ray beams through a section of the body to construct an image of that section.]
7. In attempting to discern distant details, people will sometimes squint. Why does this help?
8. Is the image formed on the retina of the human eye upright or inverted? Discuss the implications of this for our perception of objects.
9. The human eye is much like a camera-yet, when a camera shutter is left open and the camera is moved, the image will be blurred. But when you move your head with your eyes open, you still see clearly. Explain.
10. Reading glasses use converging lenses. A simple magnifier is also a converging lens. Are reading glasses therefore magnifiers? Discuss the similarities and differences between converging lenses as used for these two different purposes.
11. Nearsighted people often look over (or under) their glasses when they want to see something small up close, like a cell phone screen. Why?
12. Spherical aberration in a thin lens is minimized if rays are bent equally by the two surfaces. If a planoconvex lens is used to form a real image of an object at infinity, which surface should face the object? Use ray diagrams to show why.
13. Explain why chromatic aberration occurs for thin lenses but not for mirrors.
14. Inexpensive microscopes for children's use usually produce images that are colored at the edges. Why?

738
CHAPTER 25 Optical Instruments

---

<!-- Page 739 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 739
15. Which aberrations present in a simple lens are not present (or are greatly reduced) in the human eye?
16. By what factor can you improve resolution, other things being equal, if you use blue light ( $\lambda=450 \mathrm{~nm}$ ) rather than red $(700 \mathrm{~nm})$ ?
17. Atoms have diameters of about $10^{-8} \mathrm{~cm}$. Can visible light be used to "see" an atom? Explain.
18. Which color of visible light would give the best resolution in a microscope? Explain.

MisConceptual Questions
1. The image of a nearby object formed by a camera lens is
(a) at the lens' focal point.
(b) always blurred.
(c) at the same location as the image of an object at infinity.
(d) farther from the lens than the lens' focal point.
2. What is a megapixel in a digital camera?
(a) A large spot on the detector where the image is focused.
(b) A special kind of lens that gives a sharper image.
(c) A number related to how many photographs the camera can store.
(d) A million light-sensitive spots on the detector.
(e) A number related to how fast the camera can take pictures.
3. When a nearsighted person looks at a distant object through her glasses, the image produced by the glasses should be
(a) about 25 cm from her eye.
(b) at her eye's far point.
(c) at her eye's near point.
(d) at the far point for a normal eye.
4. If the distance from your eye's lens to the retina is shorter than for a normal eye, you will struggle to see objects that are
(a) nearby.
(c) colorful.
(b) far away.
(d) moving fast.
5. The image produced on the retina of the eye is $\_\_\_\_$ compared to the object being viewed.
(a) inverted.
(c) sideways.
(b) upright.
(d) enlarged.
6. How do eyeglasses help a nearsighted person see more clearly?
(a) Diverging lenses bend light entering the eye, so the image focuses farther from the front of the eye.
(b) Diverging lenses bend light entering the eye, so the image focuses closer to the front of the eye.
(c) Converging lenses bend light entering the eye, so the image focuses farther from the front of the eye.
(d) Converging lenses bend light entering the eye, so the image focuses closer to the front of the eye.
(e) Lenses adjust the distance from the cornea to the back of the eye.
7. When you closely examine an object through a magnifying glass, the magnifying glass
(a) makes the object bigger.
(b) makes the object appear closer than it actually is.
(c) makes the object appear farther than it actually is.
(d) causes additional light rays to be emitted by the object.
19. For both converging and diverging lenses, discuss how the focal length for red light differs from that for violet light.
20. The 300 -meter radiotelescope in Arecibo, Puerto Rico (Fig. 25-33), is the world's largest radiotelescope, but many other radiotelescopes are also very large. Why are radiotelescopes so big? Why not make optical telescopes that are equally large? (The largest optical telescopes have diameters of about 10 meters.)
8. It would be impossible to build a microscope that could use visible light to see the molecular structure of a crystal because.
(a) lenses with enough magnification cannot be made.
(b) lenses cannot be ground with fine enough precision.
(c) lenses cannot be placed in the correct place with enough precision.
(d) diffraction limits the resolving power to about the size of the wavelength of the light used.
(e) More than one of the above is correct.
9. Why aren't white-light microscopes made with a magnification of $3000 \times$ ?
(a) Lenses can't be made large enough.
(b) Lenses can't be made small enough.
(c) Lenses can't be made with short enough focal lengths.
(d) Lenses can't be made with long enough focal lengths.
(e) Diffraction limits useful magnification to several times less than this.
10. The resolving power of a microscope is greatest when the object being observed is illuminated by
(a) ultraviolet light.
(c) visible light.
(b) infrared light.
(d) radio waves.
11. Which of the following statements is true?
(a) A larger-diameter lens can better resolve two distant points.
(b) Red light can better resolve two distant points than blue light can.
(c) It is easier to resolve distant objects than nearer objects.
(d) Objects that are closer together are easier to resolve than objects that are farther apart.
12. While you are photographing a dog, it begins to move away. What must you do to keep it in focus?
(a) Increase the $f$-stop value.
(b) Decrease the $f$-stop value.
(c) Move the lens away from the sensor or film.
(d) Move the lens closer to the sensor or film.
(e) None of the above.
13. A converging lens, like the type used in a magnifying glass, (a) always produces a magnified image (image taller than the object).
(b) can also produce an image smaller than the object.
(c) always produces an upright image.
(d) can also produce an inverted image (upside down).
(e) None of these statements are true.

MisConceptual Questions
739

---

<!-- Page 740 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page
740
MP
For assigned homework and other learning materials, go to MasteringPhysics.

Problems

25-1 Camera
1. (I) A properly exposed photograph is taken at $f / 16$ and $\frac{1}{100} \mathrm{~s}$. What lens opening is required if the shutter speed is $\frac{1}{400} \mathrm{~s}$ ?
2. (I) A television camera lens has a $17-\mathrm{cm}$ focal length and a lens diameter of 6.0 cm . What is its $f$-number?
3. (I) A $65-\mathrm{mm}$-focal-length lens has $f$-stops ranging from $f / 1.4$ to $f / 22$. What is the corresponding range of lens diaphragm diameters?
4. (I) A light meter reports that a camera setting of $\frac{1}{500} \mathrm{~s}$ at $f / 5.6$ will give a correct exposure. But the photographer wishes to use $f / 11$ to increase the depth of field. What should the shutter speed be?
5. (II) For a camera equipped with a $55-\mathrm{mm}$-focal-length lens, what is the object distance if the image height equals the object height? How far is the object from the image on the film?
6. (II) A nature photographer wishes to shoot a $34-\mathrm{m}$-tall tree from a distance of 65 m . What focal-length lens should be used if the image is to fill the $24-\mathrm{mm}$ height of the sensor?
7. (II) A $200-\mathrm{mm}$-focal-length lens can be adjusted so that it is 200.0 mm to 208.2 mm from the film. For what range of object distances can it be adjusted?
8. (II) How large is the image of the Sun on film used in a camera with (a) a $28-\mathrm{mm}$-focal-length lens, (b) a $50-\mathrm{mm}$ -focal-length lens, and (c) a $135-\mathrm{mm}$-focal-length lens? (d) If the $50-\mathrm{mm}$ lens is considered normal for this camera, what relative magnification does each of the other two lenses provide? The Sun has diameter $1.4 \times 10^{6} \mathrm{~km}$, and it is $1.5 \times 10^{8} \mathrm{~km}$ away.
9. (II) If a $135-\mathrm{mm}$ telephoto lens is designed to cover object distances from 1.30 m to $\infty$, over what distance must the lens move relative to the plane of the sensor or film?
10. (III) Show that for objects very far away (assume infinity), the magnification of any camera lens is proportional to its focal length.

25-2 Eye and Corrective Lenses
11. (I) A human eyeball is about 2.0 cm long and the pupil has a maximum diameter of about 8.0 mm . What is the "speed" of this lens?
12. (II) A person struggles to read by holding a book at arm's length, a distance of 52 cm away. What power of reading glasses should be prescribed for her, assuming they will be placed 2.0 cm from the eye and she wants to read at the "normal" near point of 25 cm ?
13. (II) Reading glasses of what power are needed for a person whose near point is 125 cm , so that he can read a computer screen at 55 cm ? Assume a lens-eye distance of 1.8 cm .
14. (II) An eye is corrected by a $-5.50-\mathrm{D}$ lens, 2.0 cm from the eye. (a) Is this eye near- or farsighted? (b) What is this eye's far point without glasses?
15. (II) A person's right eye can see objects clearly only if they are between 25 cm and 85 cm away. (a) What power of contact lens is required so that objects far away are sharp?
(b) What will be the near point with the lens in place?
16. (II) About how much longer is the nearsighted eye in Example 25-6 than the 2.0 cm of a normal eye?
17. (II) A person has a far point of 14 cm . What power glasses would correct this vision if the glasses were placed 2.0 cm from the eye? What power contact lenses, placed on the eye, would the person need?
18. (II) One lens of a nearsighted person's eyeglasses has a focal length of -26.0 cm and the lens is 1.8 cm from the eye. If the person switches to contact lenses placed directly on the eye, what should be the focal length of the corresponding contact lens?
19. (II) What is the focal length of the eye-lens system when viewing an object (a) at infinity, and (b) 34 cm from the eye? Assume that the lens-retina distance is 2.0 cm .
20. (III) The closely packed cones in the fovea of the eye have a diameter of about $2 \mu \mathrm{~m}$. For the eye to discern two images on the fovea as distinct, assume that the images must be separated by at least one cone that is not excited. If these images are of two point-like objects at the eye's $25-\mathrm{cm}$ near point, how far apart are these barely resolvable objects? Assume the eye's diameter (cornea-to-fovea distance) is 2.0 cm .
21. (III) A nearsighted person has near and far points of 10.6 and 20.0 cm , respectively. If she puts on contact lenses with power $P=-4.00 \mathrm{D}$, what are her new near and far points?

25-3 Magnifying Glass
22. (I) What is the focal length of a magnifying glass of $3.2 \times$ magnification for a relaxed normal eye?
23. (I) What is the magnification of a lens used with a relaxed eye if its focal length is 16 cm ?
24. (I) A magnifier is rated at $3.5 \times$ for a normal eye focusing on an image at the near point. (a) What is its focal length? (b) What is its focal length if the $3.5 \times$ refers to a relaxed eye?
25. (II) Sherlock Holmes is using an $8.20-\mathrm{cm}$-focal-length lens as his magnifying glass. To obtain maximum magnification, where must the object be placed (assume a normal eye), and what will be the magnification?
26. (II) A small insect is placed 4.85 cm from a $+5.00-\mathrm{cm}$-focallength lens. Calculate (a) the position of the image, and (b) the angular magnification.
27. (II) A $3.80-\mathrm{mm}$-wide bolt is viewed with a $9.60-\mathrm{cm}$-focallength lens. A normal eye views the image at its near point. Calculate (a) the angular magnification, (b) the width of the image, and (c) the object distance from the lens.
28. (II) A magnifying glass with a focal length of 9.2 cm is used to read print placed at a distance 8.0 cm . Calculate (a) the position of the image; ( $b$ ) the angular magnification.
29. (III) A writer uses a converging lens of focal length $f=12 \mathrm{~cm}$ as a magnifying glass to read fine print on his book contract. Initially, the writer holds the lens above the fine print so that its image is at infinity. To get a better look, he then moves the lens so that the image is at his $25-\mathrm{cm}$ near point. How far, and in what direction (toward or away from the fine print) did the writer move the lens? Assume his eye is adjusted to remain always very near the magnifying glass.
30. (III) A magnifying glass is rated at $3.0 \times$ for a normal eye that is relaxed. What would be the magnification for a relaxed eye whose near point is (a) 75 cm , and (b) 15 cm ? Explain the differences.

740
CHAPTER 25 Optical Instruments

---

<!-- Page 741 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page 741

25-4 Telescopes
31. (I) What is the magnification of an astronomical telescope whose objective lens has a focal length of 82 cm , and whose eyepiece has a focal length of 2.8 cm ? What is the overall length of the telescope when adjusted for a relaxed eye?
32. (I) The overall magnification of an astronomical telescope is desired to be $25 \times$. If an objective of $88-\mathrm{cm}$ focal length is used, what must be the focal length of the eyepiece? What is the overall length of the telescope when adjusted for use by the relaxed eye?
33. (II) A $7.0 \times$ binocular has $3.5-\mathrm{cm}$-focal-length eyepieces. What is the focal length of the objective lenses?
34. (II) An astronomical telescope has an objective with focal length 75 cm and a +25 -D eyepiece. What is the total magnification?
35. (II) An astronomical telescope has its two lenses spaced 82.0 cm apart. If the objective lens has a focal length of 78.5 cm , what is the magnification of this telescope? Assume a relaxed eye.
36. (II) A Galilean telescope adjusted for a relaxed eye is 36.8 cm long. If the objective lens has a focal length of 39.0 cm , what is the magnification?
37. (II) What is the magnifying power of an astronomical telescope using a reflecting mirror whose radius of curvature is 6.1 m and an eyepiece whose focal length is 2.8 cm ?
38. (II) The Moon's image appears to be magnified $150 \times$ by a reflecting astronomical telescope with an eyepiece having a focal length of 3.1 cm . What are the focal length and radius of curvature of the main (objective) mirror?
39. (II) A $120 \times$ astronomical telescope is adjusted for a relaxed eye when the two lenses are 1.10 m apart. What is the focal length of each lens?
40. (II) An astronomical telescope longer than about 50 cm is not easy to hold by hand. Estimate the maximum angular magnification achievable for a telescope designed to be handheld. Assume its eyepiece lens, if used as a magnifying glass, provides a magnification of $5 \times$ for a relaxed eye with near point $N=25 \mathrm{~cm}$.
41. (III) A $6.5 \times$ pair of binoculars has an objective focal length of 26 cm . If the binoculars are focused on an object 4.0 m away (from the objective), what is the magnification? (The $6.5 \times$ refers to objects at infinity; Eq. 25-3 holds only for objects at infinity and not for nearby ones.)

25-5 Microscopes
42. (I) A microscope uses an eyepiece with a focal length of 1.70 cm . Using a normal eye with a final image at infinity, the barrel length is 17.5 cm and the focal length of the objective lens is 0.65 cm . What is the magnification of the microscope?
43. (I) A $720 \times$ microscope uses a $0.40-\mathrm{cm}$-focal-length objective lens. If the barrel length is 17.5 cm , what is the focal length of the eyepiece? Assume a normal eye and that the final image is at infinity.
44. (I) A $17-\mathrm{cm}$-long microscope has an eyepiece with a focal length of 2.5 cm and an objective with a focal length of 0.33 cm . What is the approximate magnification?
45. (II) A microscope has a $14.0 \times$ eyepiece and a $60.0 \times$ objective lens 20.0 cm apart. Calculate (a) the total magnification, (b) the focal length of each lens, and (c) where the object must be for a normal relaxed eye to see it in focus.
46. (II) Repeat Problem 45 assuming that the final image is located 25 cm from the eyepiece (near point of a normal eye).
47. (II) A microscope has a $1.8-\mathrm{cm}$-focal-length eyepiece and a $0.80-\mathrm{cm}$ objective. Assuming a relaxed normal eye, calculate (a) the position of the object if the distance between the lenses is 14.8 cm , and ( $b$ ) the total magnification.
48. (III) An inexpensive instructional lab microscope allows the user to select its objective lens to have a focal length of $32 \mathrm{~mm}, 15 \mathrm{~mm}$, or 3.9 mm . It also has two possible eyepieces with magnifications $5 \times$ and $15 \times$. Each objective forms a real image 160 mm beyond its focal point. What are the largest and smallest overall magnifications obtainable with this instrument?

25-6 Lens Aberrations
49. (II) An achromatic lens is made of two very thin lenses, placed in contact, that have focal lengths $f_{1}=-27.8 \mathrm{~cm}$ and $f_{2}=+25.3 \mathrm{~cm}$. (a) Is the combination converging or diverging? (b) What is the net focal length?
*50. (III) A planoconvex lens (Fig. 23-31a) has one flat surface and the other has $R=14.5 \mathrm{~cm}$. This lens is used to view a red and yellow object which is 66.0 cm away from the lens. The index of refraction of the glass is 1.5106 for red light and 1.5226 for yellow light. What are the locations of the red and yellow images formed by the lens? [Hint: See Section 23-10.]

25-7 to 25-9 Resolution Limits
51. (I) What is the angular resolution limit (degrees) set by diffraction for the 100 -inch ( 254 - cm mirror diameter) Mt. Wilson telescope $(\lambda=560 \mathrm{~nm})$ ?
52. (I) What is the resolving power of a microscope ( $\lambda=550 \mathrm{~nm}$ ) with a $5-\mathrm{mm}$-diameter objective which has $f=9 \mathrm{~mm}$ ?
53. (II) Two stars 18 light-years away are barely resolved by a $66-\mathrm{cm}$ (mirror diameter) telescope. How far apart are the stars? Assume $\lambda=550 \mathrm{~nm}$ and that the resolution is limited by diffraction.
54. (II) The nearest neighboring star to the Sun is about 4 lightyears away. If a planet happened to be orbiting this star at an orbital radius equal to that of the Earth-Sun distance, what minimum diameter would an Earth-based telescope's aperture have to be in order to obtain an image that resolved this star-planet system? Assume the light emitted by the star and planet has a wavelength of 550 nm .
55. (II) If you could shine a very powerful flashlight beam toward the Moon, estimate the diameter of the beam when it reaches the Moon. Assume that the beam leaves the flashlight through a $5.0-\mathrm{cm}$ aperture, that its white light has an average wavelength of 550 nm , and that the beam spreads due to diffraction only.

Problems
741

---

<!-- Page 742 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 15:16 Page 742
56. (II) The normal lens on a $35-\mathrm{mm}$ camera has a focal length of 50.0 mm . Its aperture diameter varies from a maximum of $25 \mathrm{~mm}(f / 2)$ to a minimum of $3.0 \mathrm{~mm}(f / 16)$. Determine the resolution limit set by diffraction for $(f / 2)$ and $(f / 16)$. Specify as the number of lines per millimeter resolved on the detector or film. Take $\lambda=560 \mathrm{~nm}$.
57. (III) Suppose that you wish to construct a telescope that can resolve features 6.5 km across on the Moon, $384,000 \mathrm{~km}$ away. You have a $2.0-\mathrm{m}$-focal-length objective lens whose diameter is 11.0 cm . What focal-length eyepiece is needed if your eye can resolve objects 0.10 mm apart at a distance of 25 cm ? What is the resolution limit set by the size of the objective lens (that is, by diffraction)? Use $\lambda=560 \mathrm{~nm}$.
*25-11 X-Ray Diffraction
*58. (II) X-rays of wavelength 0.138 nm fall on a crystal whose atoms, lying in planes, are spaced 0.285 nm apart. At what angle $\phi$ (relative to the surface, Fig. 25-38) must the X-rays be directed if the first diffraction maximum is to be observed?
*59. (II) First-order Bragg diffraction is observed at $23.8^{\circ}$ relative to the crystal surface, with spacing between atoms of 0.24 nm . (a) At what angle will second order be observed? (b) What is the wavelength of the X-rays?
*60. (II) If X-ray diffraction peaks corresponding to the first three orders ( $m=1,2$, and 3 ) are measured, can both the X-ray wavelength $\lambda$ and lattice spacing $d$ be determined? Prove your answer.
*25-12 Imaging by Tomography
*61. (II) (a) Suppose for a conventional X-ray image that the X-ray beam consists of parallel rays. What would be the magnification of the image? (b) Suppose, instead, that the X-rays come from a point source (as in Fig. 25-41) that is 15 cm in front of a human body which is 25 cm thick, and the film is pressed against the person's back. Determine and discuss the range of magnifications that result.

General Problems
62. A pinhole camera uses a tiny pinhole instead of a lens. Show, using ray diagrams, how reasonably sharp images can be formed using such a pinhole camera. In particular, consider two point objects 2.0 cm apart that are 1.0 m from a $1.0-\mathrm{mm}$-diameter pinhole. Show that on a piece of film 7.0 cm behind the pinhole the two objects produce two separate circles that do not overlap.
63. An astronomical telescope has a magnification of $7.5 \times$. If the two lenses are 28 cm apart, determine the focal length of each lens.
64. (a) How far away can a human eye distinguish two car headlights 2.0 m apart? Consider only diffraction effects and assume an eye pupil diameter of 6.0 mm and a wavelength of 560 nm . (b) What is the minimum angular separation an eye could resolve when viewing two stars, considering only diffraction effects? In reality, it is about $1^{\prime}$ of arc. Why is it not equal to your answer in (b)?
65. Figure $25-48$ was taken from the NIST Laboratory (National Institute of Standards and Technology) in Boulder, CO, 2.0 km from the hiker in the photo. The Sun's image was 15 mm across on the film. Estimate the focal length of the camera lens (actually a telescope). The Sun has diameter $1.4 \times 10^{6} \mathrm{~km}$, and it is $1.5 \times 10^{8} \mathrm{~km}$ away.

FIGURE 25-48
Problem 65.
66. A $1.0-\mathrm{cm}$-diameter lens with a focal length of 35 cm uses blue light to image two objects 15 m away that are very close together. What is the closest those objects can be to each other and still be imaged as separate objects?
67. A movie star catches a reporter shooting pictures of her at home. She claims the reporter was trespassing. To prove her point, she gives as evidence the film she seized. Her $1.65-\mathrm{m}$ height is 8.25 mm high on the film, and the focal length of the camera lens was 220 mm . How far away from the subject was the reporter standing?
68. A child has a near point of 15 cm . What is the maximum magnification the child can obtain using a $9.5-\mathrm{cm}$-focallength magnifier? What magnification can a normal eye obtain with the same lens? Which person sees more detail?
69. A woman can see clearly with her right eye only when objects are between 45 cm and 135 cm away. Prescription bifocals should have what powers so that she can see distant objects clearly (upper part) and be able to read a book 25 cm away (lower part) with her right eye? Assume that the glasses will be 2.0 cm from the eye.
70. What is the magnifying power of a +4.0-D lens used as a magnifier? Assume a relaxed normal eye.
71. A physicist lost in the mountains tries to make a telescope using the lenses from his reading glasses. They have powers of +2.0 D and +5.5 D , respectively. (a) What maximum magnification telescope is possible? (b) Which lens should be used as the eyepiece?
72. A person with normal vision adjusts a microscope for a good image when her eye is relaxed. She then places a camera where her eye was. For what object distance should the camera be set? Explain.
73. A 50-year-old man uses +2.5-D lenses to read a newspaper 25 cm away. Ten years later, he must hold the paper 38 cm away to see clearly with the same lenses. What power lenses does he need now in order to hold the paper 25 cm away? (Distances are measured from the lens.)

742
CHAPTER 25 Optical Instruments

---

<!-- Page 743 -->

GIAN_PPA7_GE_25_713-743v5.1HR.QXD 29-08-2014 $15: 16$
Page 743
74. Two converging lenses, one with $f=4.0 \mathrm{~cm}$ and the other with $f=48 \mathrm{~cm}$, are made into a telescope. (a) What are the length and magnification? Which lens should be the eyepiece? (b) Assume these lenses are now combined to make a microscope; if the magnification needs to be $25 \times$, how long would the microscope be?
75. An X-ray tube operates at 95 kV with a current of 25 mA and nearly all the electron energy goes into heat. If the specific heat of the $0.065-\mathrm{kg}$ anode plate is $0.11 \mathrm{kcal} / \mathrm{kg} \cdot \mathrm{C}^{\circ}$, what will be the temperature rise per minute if no cooling water is used? (See Fig. 25-36.)
76. Human vision normally covers an angle of roughly $40^{\circ}$ horizontally. A "normal" camera lens then is defined as follows: When focused on a distant horizontal object which subtends an angle of $40^{\circ}$, the lens produces an image that extends across the full horizontal extent of the camera's light-recording medium (film or electronic sensor). Determine the focal length $f$ of the "normal" lens for the following types of cameras: (a) a $35-\mathrm{mm}$ camera that records images on film 36 mm wide; (b) a digital camera that records images on a charge-coupled device (CCD) 1.60 cm wide.
77. The objective lens and the eyepiece of a telescope are spaced 85 cm apart. If the eyepiece is +19 D , what is the total magnification of the telescope?
78. Spy planes fly at extremely high altitudes ( 25 km ) to avoid interception. If their cameras are to discern features as small as 5 cm , what is the minimum aperture of the camera lens to afford this resolution? (Use $\lambda=580 \mathrm{~nm}$.)
79. X-rays of wavelength 0.0973 nm are directed at an unknown crystal. The second diffraction maximum is recorded when the X-rays are directed at an angle of $21.2^{\circ}$ relative to the crystal surface. What is the spacing between crystal planes?
80. The Hubble Space Telescope, with an objective diameter of 2.4 m , is viewing the Moon. Estimate the minimum distance between two objects on the Moon that the Hubble can distinguish. Consider diffraction of light with wavelength 550 nm . Assume the Hubble is near the Earth.
81. You want to design a spy satellite to photograph license plate numbers. Assuming it is necessary to resolve points separated by 5 cm with $550-\mathrm{nm}$ light, and that the satellite orbits at a height of 130 km , what minimum lens aperture (diameter) is required?
82. Given two 12 -cm-focal-length lenses, you attempt to make a crude microscope using them. While holding these lenses a distance 55 cm apart, you position your microscope so that its objective lens is distance $d_{\mathrm{o}}$ from a small object. Assume your eye's near point $N=25 \mathrm{~cm}$. (a) For your microscope to function properly, what should $d_{\mathrm{o}}$ be? (b) Assuming your eye is relaxed when using it, what magnification $M$ does your microscope achieve? (c) Since the length of your microscope is not much greater than the focal lengths of its lenses, the approximation $M \approx N \ell / f_{\mathrm{e}} f_{\mathrm{o}}$ is not valid. If you apply this approximation to your microscope, what $\%$ error do you make in your microscope's true magnification?
*83. The power of one lens in a pair of eyeglasses is -3.5 D . The radius of curvature of the outside surface is 16.0 cm . What is the radius of curvature of the inside surface? The lens is made of plastic with $n=1.62$.

Search and Learn
1. Digital cameras may offer an optical zoom or a digital zoom. An optical zoom uses a variable focal-length lens, so only the central part of the field of view fills the entire sensor; a digital zoom electronically includes only the central pixels of the sensor, so objects are larger in the final picture. Discuss which is better, and why.
2. Redo Examples 25-3 and 25-4 assuming the sensor has only 6 MP . Explain the different results and their impact on finished photographs.
3. An astronomical telescope, Fig. 25-20, produces an inverted image. One way to make a telescope that produces an upright image is to insert a third lens between the objective and the eyepiece, Fig. 25-23b. To have the same magnification, the non-inverting telescope will be longer. Suppose lenses of focal length $150 \mathrm{~cm}, 1.5 \mathrm{~cm}$, and 10 cm are available. Where should these three lenses be placed to make a non-inverting telescope with magnification $100 \times$ ?

ANSWERS TO EXERCISES

A: 6.3 m .
B: 33 dots $/ \mathrm{mm}$.
C: $P=-4.0 \mathrm{D}$.
D: 48 cm .

E: 2 m .
F: (c) as stated on page 732; (c) by the $\lambda$ rule.
G: 0.28 nm .

Search and Learn
743

---

