---
markmap:
  colorFreezeLevel: 3
---

# Ray-Optics

## I. Fundamental Principles of Light and Reflection
### A. Nature of Reflection and Governing Laws
#### Light falling on a surface undergoes three phenomena
  - reflection (bouncing back), absorption, and refraction (bending)
##### a. The law of reflection states that the angle of incidence ($i$) is always equal to the angle of reflection ($r$)
##### b. The incident ray, the normal at the point of incidence, and the reflected ray must all lie within the same plane
##### c. These laws remain valid for any kind of surface geometry, including regular smooth surfaces or diffused rough surfaces
#### Vector representation of the laws of reflection allows for complex three-dimensional calculations
##### a. The incident ray can be treated as a vector with $i$, $j$, and $k$ components
##### b. The mathematical formula for the reflected ray vector ($R_2$) is $R_2 = R_1 - 2(R_1 \cdot n)n$, where $n$ is the unit vector along the normal
##### c. Components of a ray parallel to the reflecting surface remain unchanged, while components perpendicular to the surface reverse in direction
### B. Characteristics of Image Formation in Plane Mirrors
#### Geometric properties of images formed by a single plane mirror
##### a. The image distance from the mirror is always equal to the object distance from the mirror
##### b. The size of the image produced is identical to the size of the original object
##### c. The line connecting the object and its image is always perpendicular to the mirror's surface, making the mirror a perpendicular-bisector of that line
#### Nature and orientation of images in plane mirrors
##### a. The object and image are always of opposite nature; for example, a real object produces a virtual image
##### b. Images are laterally inverted, meaning the left side of the object appears as the right side of the image
##### c. For clock-related problems, the time shown in a mirror image can be found by subtracting the real time from 12:00:00 (or 11:59:60)
## II. Dynamic Optics and Multi-Mirror Systems
### A. Rotation of Mirrors and Incident Rays
#### Impact of rotating the mirror on the reflected ray
##### a. If a mirror is rotated by an angle $\theta$, the reflected ray rotates by an angle of $2\theta$
##### b. The rotation of the reflected ray occurs in the same rotational sense (clockwise or anticlockwise) as the mirror's rotation
##### c. This doubling effect occurs because both the normal and the relative angle of incidence change simultaneously
#### Impact of rotating the incident ray
##### a. If an incident ray is rotated by an angle $\theta$, the reflected ray also rotates by the same angle $\theta$
##### b. Unlike mirror rotation, the reflected ray rotates in the opposite rotational sense to the incident ray
##### c. When both the mirror and the ray are rotated, the net rotation of the reflected ray is the algebraic sum of the individual effects
### B. Number of Images and Field of View
#### Mathematical determination of the number of images formed between two inclined mirrors
##### a. The first step involves calculating the ratio $x = 360 / \theta$, where $\theta$ is the angle between the mirrors
##### b. If $x$ is an even number, the number of images ($n$) is always $x - 1$, regardless of the object's position
##### c. If $x$ is an odd number, $n = x - 1$ if the object is on the angle bisector (symmetrical), and $n = x$ if the object is not on the bisector
#### Field of view and minimum mirror requirements
##### a. An image is formed regardless of mirror size or location, but it is only visible if the eye is within the "field of view" created by the reflected rays
##### b. To see one's full height ($H$), a person requires a plane mirror with a minimum vertical size of $H/2$
##### c. This mirror must be placed such that its bottom edge is at a height of half the eye-level from the ground
## III. Spherical Mirror Optics
### A. Geometry and Focal Properties of Spherical Mirrors
#### Definitions and types of spherical mirrors derived from a hollow sphere
##### a. A concave mirror has its reflecting surface on the inner side (converging), while a convex mirror reflects from the outer bulged side (diverging)
##### b. The centre of the sphere is the centre of curvature ($C$), and the geometric centre of the mirror is the pole ($P$)
##### c. For paraxial rays, which are rays very close to the principal axis, the focal length ($f$) is exactly half of the radius of curvature ($R$)
#### Sign convention and mirror formula application
##### a. All distances are measured from the pole, with the direction of the incident ray taken as positive
##### b. The mirror formula $1/v + 1/u = 1/f$ relates the object distance ($u$), image distance ($v$), and focal length ($f$)
##### c. Unlike lenses, the focal length of a spherical mirror is independent of the surrounding medium
### B. Magnification and Motion in Spherical Mirrors
#### Categorisation of magnification types
##### a. Lateral (transverse) magnification ($m$) is the ratio of image height to object height, given by $m = -v/u$
##### b. Longitudinal magnification applies to objects placed along the principal axis and is calculated as $-v^2/u^2$ for small objects
##### c. A negative magnification indicates an inverted image, while a positive magnification indicates an erect image
#### Velocity of images in spherical mirror systems
##### a. The velocity of an image relative to the mirror along the x-axis (parallel to the principal axis) is $-m^2$ times the relative velocity of the object
##### b. The velocity of an image perpendicular to the principal axis is $m$ times the velocity of the object
##### c. To find the velocity relative to the ground, the mirror's own velocity must be added vectorially to the relative image velocity
## IV. Refraction at Plane Surfaces
### A. Refractive Index and Snell's Law
#### Fundamental changes during refraction across a medium interface
##### a. Refraction is caused by the change in the speed of light as it enters a different medium, while the frequency of light remains constant
##### b. The absolute refractive index ($\mu$) is the ratio of the speed of light in a vacuum ($c$) to its speed in the medium ($v$)
##### c. Wavelength ($\lambda$) changes during refraction such that $\mu = \lambda_{vacuum} / \lambda_{medium}$
#### Governing equations for light bending
##### a. Snell's Law states that $\mu_1 \sin(i) = \mu_2 \sin(r)$ is constant across any interface
##### b. Light bending towards the normal occurs when moving from a rarer to a denser medium, whereas it bends away when moving from a denser to a rarer medium
##### c. For small angles, the relation simplifies to $i / r = \mu_2 / \mu_1$
### B. Apparent Depth and Total Internal Reflection (TIR)
#### Visual shifts caused by refraction at plane boundaries
##### a. When viewing an object in a denser medium from a rarer medium, the object appears closer; the apparent depth is the real depth divided by $\mu$
##### b. If the viewer is in a denser medium looking at an object in a rarer medium, the object appears further away at a distance of $\mu$ times the real height
##### c. The normal shift produced by a glass slab of thickness $t$ is $t(1 - 1/\mu)$, which is independent of the object's distance from the slab
#### Conditions and applications of Total Internal Reflection
##### a. TIR occurs only when light travels from a denser to a rarer medium and the angle of incidence exceeds the critical angle ($\theta_c$)
##### b. The critical angle is defined as $\theta_c = \sin^{-1}(\mu_{rarer} / \mu_{denser})$
##### c. A point source underwater creates a "circle of illumination" on the surface, with a radius $R = h \cdot \tan(\theta_c)$, where $h$ is the depth
## V. Refraction at Spherical Surfaces and Thin Lenses
### A. Curved Surface Refraction and Lens Construction
#### The general refraction formula for a single spherical interface
##### a. The relationship is given by $\mu_{final}/v - \mu_{initial}/u = (\mu_{final} - \mu_{initial})/R$, where $R$ is the radius of curvature
##### b. Sign conventions for $u$, $v$, and $R$ are the same as those used for spherical mirrors, with all distances measured from the pole
##### c. Lateral magnification for a single spherical surface is $(\mu_{initial} / \mu_{final}) \cdot (v / u)$
#### Classification and nomenclature of thin lenses
##### a. A lens is "convex" if it is thicker at the centre and "concave" if it is thinner at the centre
##### b. Specific names depend on surface combinations, such as bi-convex, plano-convex, or concavo-convex
##### c. A lens's behaviour (converging vs. diverging) depends on the ratio of its refractive index to that of the surrounding medium; if the medium is denser, the lens's nature reverses
### B. Thin Lens Formulae and Combinations
#### Mathematical tools for lens analysis
##### a. The Lens Maker's Formula, $1/f = (\mu_{lens} / \mu_{medium} - 1)(1/R_1 - 1/R_2)$, is used to determine focal length based on physical construction
##### b. The standard Lens Formula $1/v - 1/u = 1/f$ determines image position
##### c. Magnification for a thin lens is simply $v/u$ for height and $v^2/u^2$ for longitudinal length
#### Specialized lens scenarios and experiments
##### a. When lenses are in contact, their equivalent power is the sum of individual powers: $1/F_{eq} = 1/f_1 + 1/f_2$
##### b. If a lens is cut along the principal axis, the focal length of the pieces remains $f$; if cut perpendicular to the axis, the focal length of each half becomes $2f$
##### c. The Displacement Method is used to find the focal length of a convex lens using the formula $f = (D^2 - x^2) / 4D$, where $D$ is the distance between object and screen
## VI. Prism Theory and Optical Dispersion
### A. Prism Geometry and Deviation
#### Geometric relationships within a triangular prism
##### a. The angle of the prism ($A$) is equal to the sum of the internal refraction angles, $r_1 + r_2$
##### b. The net deviation ($\delta$) of a ray passing through a prism is $\delta = i + e - A$, where $e$ is the angle of emergence
##### c. For a ray to just emerge from the second face, the angle of incidence must satisfy specific critical conditions
#### Minimum deviation and refractive index determination
##### a. At minimum deviation ($\delta_m$), the ray passes symmetrically through the prism such that $i = e$ and $r_1 = r_2 = A/2$
##### b. The refractive index can be calculated at this point using the formula $\mu = \sin((A + \delta_m)/2) / \sin(A/2)$
##### c. For "thin prisms" with very small apex angles, the deviation is constant and simplified to $\delta = (\mu - 1)A$
### B. Dispersion of Light and Rainbow Effects
#### Chromatic splitting of white light
##### a. Dispersion occurs because the refractive index of a material is different for different wavelengths (Cauchy's relation)
##### b. In the visible spectrum, violet light has the highest refractive index and undergoes maximum deviation, while red light has the lowest and undergoes minimum deviation
##### c. Angular dispersion is the difference in deviation between violet and red rays: $\theta = (\mu_v - \mu_r)A$
#### Power and combinations of dispersive elements
##### a. Dispersive power ($\omega$) is a material property defined as the ratio of angular dispersion to mean deviation (usually yellow light)
##### b. "Dispersion without deviation" and "deviation without dispersion" are achieved by combining two prisms of different materials and orientations
##### c. Chromatic aberration in lenses is a direct result of dispersion, where different colours focus at different points along the axis
## VII. Optical Instruments and Vision
### A. Microscopy and Magnification
#### Simple Microscope principles
##### a. Uses a single convex lens to produce a virtual, erect, and magnified image
##### b. Magnification is highest when the image is formed at the least distance of distinct vision
##### c. Essential for viewing small objects that require high angular magnification
#### Compound Microscope construction
##### a. Employs two lenses: the objective lens (near the object) and the eyepiece (near the eye)
##### b. The objective forms a real, magnified image which then acts as the object for the eyepiece
##### c. Provides significantly higher magnification than a simple microscope through dual-stage enlargement
### B. Telescopic Systems
#### Astronomical Telescope functionality
##### a. Designed for viewing distant celestial objects by using a large objective lens to collect light
##### b. The final image produced is typically virtual and inverted
##### c. The length of the telescope in normal adjustment is the sum of the focal lengths of the objective and the eyepiece
#### Practical considerations in instrument design
##### a. Large objective lenses are required in telescopes to increase resolving power and light-gathering capacity
##### b. Aberrations (chromatic and spherical) must be minimized to ensure clear, sharp images
##### c. Modern systems may use mirrors (reflecting telescopes) instead of lenses to avoid chromatic issues