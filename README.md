# micro-rti-build

## SECTION 1: PURPOSE and AIMS

## SECTION 2: HARDWARE, SOFTWARE, TOOLS and MATERIALS

## SECTION 3: ASSEMBLY

## SECTION 4: TEST EXAMPLE

==========================

**SECTION 1: PURPOSE and AIMS**

Instructions for building an inexpensive micro-rti tool for high resolution surface detail imaging based on experiments undertaken during the proof of concept stage outlined in a blog post titled *[MicroRTI: experiments in seeing really (really) close](http://digitalhumanities.soton.ac.uk/blog/southampton-dh/3272)* published 02-09-2022. 

The purpose of microRTI is to enhance the visualisation of object surfaces through the capture of multiple digital micrographs from a stationary microscope positioned squarely above the subject. In each micrograph, light is cast from multiple known, or knowable, distances and angles of inclination on the subject and a reflective sphere placed within the frame. The result is a series of still images of the same subject with varying highlights and shadows and of the sphere with the light information reflected upon it. Lighting information from the images is mathematically synthesised to generate a mathematical model of the surface, enabling a user to re-light the RTI images interactively and examine its surface on screen. 

The second iteration build (see fig.1) aims to:
- be replicable without the need for technical knowledge;
- use affordable and readily available tools and materials;
- be easily repaired;
- considerably reduce interruptions of the light cast on subjects by replacing the tripod (that holds the microscope) with a single support arm;
- ensure lighting from at least three angles of inclination between 15-65 degrees is available;
- be reasonably mobile and modular;
- physically accommodate the vast majority of objects for which Micro-RTI might be applied.

![FIGURE 1](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig1-concept.JPG)

**SECTION 2: HARDWARE, SOFTWARE, TOOLS and MATERIALS**

*HARDWARE* 

Plugable brand 250X digital USB microscope ~£40.00

  -2.0 Megapixels, up to 250x magnification (Note: Final magnification corresponds to monitor size) 

  -1600x1200 resolution 

  -8bit colour depth 

Reflective spheres £15.00 

  -3mm and 0.25mm 

Morpilot LED torch (White and UV light) £10.00

  -250 lumen output  

Laptop/Desktop (~£100+)*

*SOFTWARE* 

Plugable Digital Viewer (v 3.3.30) ** 

RTI Builder (v 2.02) *** 

RTI Viewer (v 1.1) **** 

*MATERIALS* 

PLA filament (for 3D printed parts) £10.00 

4 x M2 10mm bolts £2.00 

1 x M2 nut £0.50 

1 x M6 20mm bolt £1.00 

1 x M6 nut £0.50 

1 x 38mm x 5.5mm compression spring £0.40 

2 x l: 25mm, w: 2mm Phillips head screws £0.25 

Plywood (cut in to disc, radius 200mm) £5.00 per 500mm x 500mm cut 

Velcro strips (affix light source tripod to risers and subject plate to plywood platform) £8.00/pack 

Permanent black marker (mark lighting angles around platform) £1.00 

Velcro strap (to hold light source to light source tripod) £1.00 

*TOOLS* 

3D printer (Ultimaker 3) or similar. ***** 

Jig saw (or small handsaw) for cutting plywood base £5.00-50.00 

Electronics screwdriver set (specifically 1.3mm Allen head) £10.00/set 

Small knife (for cleaning the holes in 3d printed parts) £3.00 

Fine file (nail file for cleaning 3d printed parts) £1.00 

* Most modern PC’s and Apple machines will run this software, though some instruction for installation located in site forum is required due to recent Apple security setting changes.

** Free with digital microscope. Most digital microscopes come with some variation of a viewer software.

*** Free RTI Builder software available here: Cultural Heritage Imaging | Downloads

**** Free RTI Viewer software available here: Cultural Heritage Imaging | Downloads

***** Available to use free of charge for related projects at the Digital Humanities Hub 

**SECTION 3: ASSEMBLY 

![FIGURE 2](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig2-MicroRTI-iteration2.jpg)**

*Plywood Base* 

  1. Cut 400mm x 400mm plywood square. 

  2. Locate and mark centre point of plywood square. 

  3. Fix one end of 200mm string to centre and another to a pencil to trace a circle with 200mm radius on to plywood square. 

  4. Cut out plywood circle. 

  5. Mark equal increments around perimeter of plywood circle (minimum 16) using permanent marker pen. 

  6. Drill five 3mm holes through plywood circle. One in centre and four equally spaced around the base c. 60mm from edge to produce a stable support.  

*Microscope Support Arm*

  1. 3D print cable route, lock plunger guide, lock plunger, horizontal support arm, vertical support column, and microscope 'C' clamp found in 'Parts Files' folder.

 ![FIGURE 3](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig3-microscope_arm_pts.JPG)
  
  2. Screw cable route to top of vertical support column using 1 x 10mm M2 bolt. 

  3. Screw lock plunger guide to vertical support arm using 2 x 10mm M2 bolts. Plastic may require filing to improve fit. 

![FIGURE 4](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig4-scope_arm_detail.jpg)

  4. Slide lock plunger into the slot in the back of the vertical support arm and engage teeth of lock plunger and vertical support column. 

  5. Slide compression spring over 20mm M6 bolt. 

  6. Fit M6 nut in to recess at back of lock plunger guide. Plastic may require filing to improve fit. 

  7. Fit head of 20mm M6 bolt into recess into recess in lock plunger, compress spring, align bolt with nut and rotate for min of 3 threads. The teeth of the lock          plunger and vertical support column should freely engage under the tension of the compression spring. Plastic may require filing to improve fit. 

  8. Attach microscope ‘C’ clamp to horizontal support arm using 1 x 10mm M2 nut and bolt. Fit microscope to clamp. 

  9. Route microscope cable through the cable route fixture.  

![FIGURE 5](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig5-lock_plunger_detail.jpg)

*Fix microscope support to plywood base.* 

  1. 3D print subject plate and five support feet found in 'Parts Files' folder.
 
  2. Place the assembly on top of the plywood base, disengage teeth of lock plunger from vertical support column and lower microscope until it meets surface of base.  

  3. Adjust the assembly so that the centre of the microscope lens aligns with the centre of the plywood base. 

  4. Fasten microscope support to the plywood base using 2 x Phillips head screws. 

  5. Affix both hook and loop sides of 2 x c.150mm strips of Velcro to base of subject plate. Remove paper backing to expose adhesive. 

  6. Raise microscope to place subject plate. Align centres of subject plate and plywood base and press firmly to join the two. 

  7. Cut 5 pairs of hook and loop Velcro circles of c.20mm in diameter. Punch a hole through their centres using a paper hole punch. Remove paper to expose adhesive. 

  8. Place Velcro pairings onto tops of support feet by feeding 3mm pegs through the punched holes. 

  9. Guide each peg into the holes drilled into plywood board and press firmly to engage Velcro adhesive. 

![FIGURE 6](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig6-final_assembly.jpg)

*Assemble light source and tripod arrangement.* 

  1. 3D print light tripod cradle, light tripod base and light tripod bolt found in 'Parts Files' folder. 
  
  2. Press fit the ball head of the tripod base into the cup of the tripod cradle. 

  3. Thread bolt through cradle until finger tight. 

  4. Place torch in cradle. 

  5. Thread Velcro strap through slits in cradle and secure torch in place. 

  6. Affix Velcro strips to underside of tripod base and top of two riser blocks.  

  7. Support barrier fits slots in to front of riser block(s) to prevent riser from sliding underneath platform and introducing variation in distance of lighting. 

![FIGURE 7](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/FIGURES/Fig7-tripod_assembly.jpg) 

**SECTION 4: TEST EXAMPLE**

A .rti model of an  area of a  mezzotint-left eye of figure-was produced using the build described above. This includes the use of a 0.25mm sphere at 250x magnification at 200mm distance from the subject.  

![IMAGE 8](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/Imaging%20Example/IMAGE8-Test_subject.jpg)

![IMAGE 9](https://github.com/Southampton-Digital-Humanities/micro-rti-build/blob/main/Imaging%20Example/IMAGE9-screenshot_RTI_model_eye.jpg)

 Image 9 demonstrates the potential for visualising the microscopic surface texture of objects using this equipment. 

 

 

 

 

 

 
