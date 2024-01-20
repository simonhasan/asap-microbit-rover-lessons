# Notes for Teacher

```{contents}
:local:
```

## Overview

In this lesson, examples will be given for an M3 button head bolt with a hex socket as displayed below:

![m3-example](assets/m3-example.png)

```{attention}
All measurements in the examples have been redacted. Students are meant to find values for the bolts independently. Teachers can request dimensions at [simon@hasanprep.org](mailto:simon@hasanprep.org). 
```

## General Notes

1. **Preparation**: Ensure all materials, especially the datasheets for M3 bolts, 3D printer, filament, and Tinkercad software, are available and ready for use. Check the 3D printer for any maintenance needs. 
2. **Introduction**: Explain the importance of precision in engineering and how this assignment will help students understand this concept. Discuss the specifications of M3 bolts and how to read the datasheets. The height of the test piece should be 3mm.
3. **Guidance**: During the design process, guide the students in considering the bolt specifications in their designs. Encourage them to consider why specific hole diameters might work better than others. 
4. **Safety**: Ensure all students follow safety guidelines while using the 3D printer. It might be beneficial to do a safety refresher before starting the assignment. 
5. **Assessment**: Use the provided rubric to assess each student's work. Remember to give constructive feedback to help them improve. 
6. **Differentiation**: Be prepared to support students struggling with the assignment. This could include providing templates, one-on-one assistance, or additional resources. 
7. **Reflection**: After the assignment, have a class discussion about the results. Which hole diameters worked best? Why? What would they do differently next time? 

---

## Understanding Metric Labeling



![m3](assets/m3.png)



:::{note} 
M3 bolts have been chosen for this design project because they fit most of the mounting holes found on electronic components. Occasionally, an M2.5 bolt may be needed. Check any datasheets or diagrams of the components to see if an M2.5 bolt is required.
:::

## Types of M3 Nuts

There are a variety of heads for M3 nuts available. The shape of the head varies according to the intended use of the bolt. Some bolts have a head. that requires tools that are uncommon to discourage the removal of the bolt. Some have a head optimized so they can be removed by hand. Other bolts have a head that reduces the profile of the bolt.

![m3-nut-heads](assets/m3-nut-heads.png)



## Sourcing Materials

### M3 Bolts

M3 bolt sets are available on Amazon. These bolts are more expensive and may contain sizes that are not necessary for the project. Furthermore, the bolts on Amazon do not have a diagram or datasheet. Sourcing bolts from Aliexpress is more affordable. You can buy the right amount of specific sizes needed at a lower cost. The vendors often include the specifications of the bolts in the images that can be screen-captured for distribution. The only drawback to Aliexpress is that it takes longer to deliver the items.

### 3D Printers

This project works best with a newer generation high-speed 3D printer. The test pieces can print in 4 to 8 minutes, depending on the object's size. These printers are becoming less expensive and more prevalent on the market today.

Here are some high-speed 3D printers:

[AnkerMake M5C](https://www.ankermake.com/collections/all-3d-printers?ref=homepage_AccessoriesBanner1&pf_t_printer_model=M5C+3D+Printers)

[AnkerMake M5](https://www.ankermake.com/collections/all-3d-printers?ref=homepage_AccessoriesBanner1&pf_t_printer_model=M5+3D+Printers)

[Anycubic Kobra 2 Pro](https://www.anycubic.com/products/kobra-2-pro)

[Bambu Lab A1 Series](https://us.store.bambulab.com/collections/a1-series)

[Bambu Lab P1 Series](https://us.store.bambulab.com/collections/p1-series)

[Bambu Lab X1 Series](https://us.store.bambulab.com/collections/x1-series)

### Filament

Filament can be expensive. Luckily, Voxel offers inexpensive filament that works well with high-speed 3D printing. They offer discounts when purchasing 3 or more spools:

[Voxel](https://voxelpla.com/)

---

## Follow-Up Lessons or Extensions

The two examples below can be used as follow-up lessons or extensions to the lesson. It may be the case that the students' designs may require one of these modifications.

### Creating Holes for Recessed Bolts

Using the same materials from this lesson, students can create holes to recess the bolts to create a flat surface for other components.

![m3-bolt-recessed](assets/m3-bolt-recessed.png)

### Created Holes for Recessed Nuts

Another possible lesson that can be directly modeled after this is one where students create recessed holes for the M3 nuts. This can help to tighten the bolt without a tool and create a surface without protrusions.

![m3-nut-recessed](assets/m3-nut-recessed.png)

Students can use a datasheet to create the recess holes in their engineering design notebook.

![datasheet-m3-nut](assets/datasheet-m3-nut.jpg)

:::{note}
Tinkercad does not scale objects uniformly. Students will have to calculate the ratio. This is an excellent opportunity to integrate mathematics in the lesson.
::: 

The image below demonstrates the height-to-width and width-to-height ratio of a regular hexagon:

![hexagon-ratios](assets/hexagon-ratios.png)

The hexagon on the left has a $\frac{2}{\sqrt{3}}:1$ or $1.1547:1$ ratio. The hexagon on the right has a $1:\frac{\sqrt{3}}{2}$ or $1:0.8660$ ratio. Below is a hexagon in Tinkercad with the default values.

![tinkercad-hexagon-01](assets/tinkercad-hexagon-01.jpg)

If the width was changed from $17.32$ to $20$ it is no longer a regular hexagon.

![tinkercad-hexagon-02](assets/tinkercad-hexagon-02.jpg)

To make the irregular hexagon above to a regular hexagon, the height would be the width $20\frac{2}{\sqrt{3}}\approx20\cdot1.1547\approx23.094$. Tinkercad only has decimals to the hundredth. Changing the height to 23.09 makes the hexagon closer to a regular hexagon.

![tinkercad-hexagon-03](assets/tinkercad-hexagon-03.jpg)

Similarly, the height of the hexagon below was changed to $30$.

![tinkercad-hexagon-04](assets/tinkercad-hexagon-04.jpg)

The width would be $30\frac{\sqrt{3}}{2}\approx30\cdot0.866\approx25.98$.

![tinkercad-hexagon-05](assets/tinkercad-hexagon-05.jpg)

