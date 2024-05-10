# Integrating electronics and 3D printing
Ideas for integrating electronics and 3D printing. By Katrien van Riet.

## Table of contents

1. [Filament light guides](#light_guides)
2. [Flexure buttons](#flexure_buttons)

## Filament light guides <a name="light_guides"></a>

![Light guide titled](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/light%20guide%20filament%20tilted%20small.png)

(3D printing files in 'print files' folder)

Light guides are pieces of very transparent plastic that uniformly guide light (often from an LED) to a specific spot in the surface of a product. You have probably seen these in commercially produced products, like the on/off status light on displays, tv's, coffee machines, etc. This project adds cheap light guide functionality to your 3D-printed prototypes by inserting a small piece of 1.75mm (or 2.85mm if you want) transparent filament into a small hole that drops down right to a small (0805 or 0604) surface-mounted LED. These are LED's you often find on microcontrollers. 

### Materials
1. Transparent PLA (or PETG, etc.) filament (1.75mm)
2. 3D-print with holes in it
3. Side cutter pliers (those blue cutters you get with a 3D printer)

### Steps
1. Print the light guide tester. This model has holes ranging from 2.2mm - 2.9mm diameter. (or create your own tester)
(important! print the tester in the same orientation that your prototype hole will be in, so you can test the fit properly)
2. Insert 1.75mm transparent filament into the tester and see which hole produces the best fit. Use this diameter for the light guides you will use in your prototype.
3. Print your prototype with the holes in it. If your wall thickness is a bit thin (like 1.5mm) and far removed from the LED light source, extrude a 6mm diameter cylinder around the hole down to the LED, and put a 3mm chamfer on that cylinder (see example in 'images --> light guide model bottom'). This gives your filament some stability and reduces bleed from different LED sources, and maintains light intensity.
4. Insert 1.75mm filament, and cut flat to the surface of your 3D print. Add a bit of superglue on the INSIDE of your print on the light guide filament to secure it. Don't do this on the outside. You will see the superglue dry and this will ruin the look.
5. Optional: after cutting the filament to size, but before securing with glue, you could sand the ends of the filament flat for a more polished end look.

### Difference between light guides and regular holes
![filament](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/light%20guide%20filament%20tilted%20small.png)
![holes](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/light%20guide%20no%20filament%20small.png)

## Flexure buttons <a name="flexure_buttons"></a>

![Flexure buttons round](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/round%20flexure%20button%20print%20small.png)

One way to quickly update the look and feel of a prototype using buttons is to cover those buttons with flexures. These flexures are part of the print, and offer a satisfying, springy experience. And because they are integrated into the print, you get this complexity for free.

### Guide
There are two main orientations that you can print these flexures in: flat and upright. Both orientations need their own approach. 

#### 1. Flat printing
Flat printing is the easiest and produces flexure buttons that are resistant to breaking along the printed layer lines (because they flex perpendicular to the layer lines instead of along them).
You can vary the thickness and shape of the beam connecting the round button to the rest of the printed part. Narrower beams produce more flexible buttons, and wider beams produce stiffer buttons. You can even change the colour of the top of the button by changing to a different colour of filament. 

Here is a simple round button design. You can print this one to test out the stiffness of the buttons:

![flexure button cross section](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/round%20flexure%20button%20model%20cross%20section%20-%20small.png)

And here's the side view:

![flexure button side view](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/round%20flexure%20button%20model%20side%20view.png)

Of course your buttons don't need to be round. You can create any shape you want, provided it can be printed flat.

#### 2. Upright printing
What if you need a flexure button on the side of your print that is printed upright (vertically)? Your printer might not like the buttons described in option 1.

In that case, you can use diamond-shaped buttons. These slant upwards with 45 degree angles, which is within the capabilities of almost all printers, even cheap ones. Make sure that you have enough material connecting the button to the rest of the print, otherwise your button will snap. For the same reason, make sure that your flexure button is less than 1mm away from the push button. As this model is printed vertically, it is more difficult to give the buttons a change in colour because you cannot change the filament at a certain layer height.

Here's a simple diamond button design. You can print this one to test out the stiffness of the buttons. Note: this model should be printed with a very big brim:

![diamond model](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/diamond%20flexure%20button%20model%20upright.png)

Here are two different connector types. The one on the left has more chance of breaking at the connector:

![straight connector](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/diamond%20connectors.png)

And some dimensions:

![diamond dimensions](https://github.com/kvriet/integrated-electronics-and-3d-printing/blob/main/images/diamond%20flexure%20button%20dimensions.png)




