# open-plan living room project in blender
##### I used Blender to design an open-plan living room for the project required for the Design and Animation course (code BLM2-4731) in the Computer Engineering department.
---
How did you meet the project requirements?
- Main geometric structures: All structures in the project were created from scratch; I only prepared an archive of image files for reference purposes, and based on the structures in this archive, I made similar and identical ones.
- Shading: I made changes to the color parameter in the Diffuse BSDF section of the textures' shading; in the material output section, I used the BSDF with the Surface.
- Other structures used in the project: In order to be realistic, I used Bezier Circle and Bezier Curve, which are mathematically calculated smooth geometric curves and circles, with their measurements being automatically optimized. In addition to these structures, I used cube, cylinder, and plane, sphere; to add variety, I used surface to make the backrests of the chairs in front of the kitchen counter, and I used cube to make the backrests of the chairs in front of the door; I used Torus in the spot light sockets; for lighting, I preferred Spot light; I defined spot light with different powers in different places and used it with shadowing support; I made the curtains at the beginning of the room with texture on plane.
- Field depth: I tried to create a field depth that focuses on the Sphere.001 object on the table at the beginning of the room, following a perspective approach; I implemented the relevant camera properties under the field depth roof.

What did each member of the group do?
- All work was done by Ömer Furkan SAĞIR.


Which assets did you download from the internet?
- I did not download any assets from the internet, I used some images to make textures with the colors I found appropriate; I selected these images from various websites solely based on their aesthetics appealing to my personal taste;
---
> The image used as a texture on the marble countertop, kitchen wall, and kitchen table:

<img width="285" alt="Ekran Resmi 2022-12-26 20 18 51" src="https://user-images.githubusercontent.com/44947688/209571160-19ad3278-9f6a-437b-847a-2eaf30934856.png">

---

> Texture sample used for the chair:

<img width="406" alt="Ekran Resmi 2022-12-26 20 19 00" src="https://user-images.githubusercontent.com/44947688/209571212-a717fa59-1c2d-4d29-af11-faf56f0a6ebc.png">

---

> Texture sample used as a texture for the coffee table, board used to define the boundary of the kitchen, television stand, and pentagonal shelves mounted on the wall:

<img width="484" alt="Ekran Resmi 2022-12-26 20 19 08" src="https://user-images.githubusercontent.com/44947688/209571222-ca70783f-27a2-4e0b-8e73-049734ce2a1c.png">

---

> Texture sample used as a texture for the flower vase next to the television:

<img width="304" alt="Ekran Resmi 2022-12-26 20 19 14" src="https://user-images.githubusercontent.com/44947688/209571236-216c54b0-75ff-4bcf-86fa-7a59c0ea2b00.png">

---

> Texture sample used as a texture for the curtains at the beginning of the scene and the chairs in front of the door:

<img width="309" alt="Ekran Resmi 2022-12-26 20 19 20" src="https://user-images.githubusercontent.com/44947688/209571241-7ef7a404-de45-4b46-9e1e-048014050a81.png">

---

> Texture sample used as a texture for the parquet:


<img width="201" alt="Ekran Resmi 2022-12-26 20 19 26" src="https://user-images.githubusercontent.com/44947688/209571247-ccf529e9-1239-48e6-af83-af08bc452eb4.png">

---

Which assets did you make yourself?

- I used a design mainly based on cubes, and I tried to turn them into structures similar to those I found in images and photos on the internet that I took as a reference point in edit mode; I tried to transform them into structures similar to those I found in images and photos on the internet that I took as a reference point in edit mode; the L-shaped kitchen counter, kitchen shelves, kitchen walls, refrigerator and its arm, chair, chair and coffee table legs, cushions and pillows, TV unit and TV were created with the shaping of the cube in edit mode.
- I created structures that give the impression of spotlights with Torus and buried Circle inside.
- I created the legs of the table, chair and coffee table with cylinder.
- I created the structures in the shape of hanging leaves with Bezier Curve.
- I created the kitchen sink and the decorative vase on the coffee table with Sphere.
- I made the backrests of the chairs used in the kitchen with Surface.
- I defined the field depth at a distance of 10 meters and chose the Aperture values for F-Stop as 55.8; Blades as 16; Rotation as 32.8°; and Ratio as 1.

---

Which tutorials did you refer to?
- blender basics: I gained such basic blender knowledge with such a poor Udemy training that I would never recommend it. Be aware that it is the worst blender basics training on the market and work with a random blender training video and be sure to get a much better foundation.

- [leaf making](https://www.youtube.com/watch?v=y7PdiGXbrD0)
- [a training video on modern room design that I benefited from to gain vision 1](https://www.youtube.com/watch?v=Yf9YJ3d9GHo)
- [a training video on modern room design that I benefited from to gain vision 2](https://www.youtube.com/watch?v=wrzSrjAY69c)
- [a training video on modern room design that I benefited from to gain vision 3](https://www.youtube.com/watch?v=rRuwN8DXjm0)

---

## Final Scene

> <img width="1440" alt="Ekran Resmi 2022-12-17 19 16 08" src="https://user-images.githubusercontent.com/44947688/209573276-f774fbe8-1376-45e5-9a9d-fd4277bf846b.png">

>> _The rendered version of the same image_

![render 1](https://user-images.githubusercontent.com/44947688/209573296-077d5a9e-b833-4d0d-a232-2bc99d83cc7f.png)


---

> Variant A: Different Camera Angle

<img width="1440" alt="Ekran Resmi 2022-12-17 19 25 31" src="https://user-images.githubusercontent.com/44947688/209573426-a26a13e7-a1b6-4ac4-9c57-42b0253a918e.png">

>> _The rendered version of the same image_


![render 3](https://user-images.githubusercontent.com/44947688/209573459-e75c3946-4d22-4633-8d8d-606c1ff9cf73.png)

---

> Variant B: The same scene with the textures removed


![no texture](https://user-images.githubusercontent.com/44947688/209573570-30d7c853-21e3-4a86-b090-aa61d443ecf4.png)

---

> _I activated the Denoise parameter, set the Noise Threshold to 0.01, set the Max Samples to 4096, and took the render with CPU as the Device and Cycles as the Render Engine:_

![cycles render](https://user-images.githubusercontent.com/44947688/209573909-56d1f4c6-a38b-4630-83a8-7a77de78be4e.png)




