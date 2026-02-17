![IMG_0641](https://github.com/user-attachments/assets/c4826b07-39bf-4799-82e4-3fa54321dc6b)


# InfinityCubeLED
3D Printed Cube frame with acrylic panels + LED strips creating an infinite light illusion  
my Thingiverse make of this project:
https://www.thingiverse.com/make:1041607

Printed this at normal scale. If soldering outside the frame like I did, I highly suggest measuring the exact length you want for the wires before you start soldering as I made a lot of my connections WAY too long & ended up having very sloppy corners (as seen in the pictures). Make sure to keep good track of the order of the soldering (the diagram picture in original by highping is a very good way to follow), also I suggest starting at the last side (12) and working backwards as I've seen many others suggest. One of the hardest parts for me though was trying to get the acrylic panels to fit perfectly and not fall off. I suggest waiting a good amount (at least 10-15 min) before moving onto next panel if using hot glue, as it takes quite a while to actually activate. I had a few panels constantly falling off as I tried gluing a different one (VERY frustrating & produced very messy sides). But ultimately this was a very satisfying project to finish & even in its messy state, the results are stunning! It's so hard to not just sit and stare at it.

P.S. I suggest looking into LedFX if you are interested in getting the lights to sync with desktop audio w/o a mic, very cool & easy to use app! https://github.com/LedFx/LedFx

## Materials
[x2] LED strips (60 LED/m): https://www.amazon.com/dp/B01CDTED80

D1 Mini (3-pack): https://www.amazon.com/dp/B07V84VWSM

[x6] Custom size 2-way mirror acrylic: https://www.ttplasticland.com/collections/mirror-acrylic-sheets-1/products/custom_see-thru-2-way-mirror-acrylic-sheet?variant=16497623105602

& ofc soldering iron, stranded copper wires, hot glue :)

## Print Settings
- Material: PLA
- Layer height: 0.2mm
- Infill: 15%
- Supports: No
- Printer: Ender 3
- Filament: Overture Black PLA

## Assembly


## 1. Prep
![IMG_0601](https://github.com/user-attachments/assets/f2f8d4db-cbf6-4511-9499-9a36d4df8aa5)

- Print frame
- Test-fit LED strip in bottom channel before printing the top.
  - Designed for ~11mm strips.
- Attach top and bottom with 2mm screws (recommended) or glue.
- Measure LED length once bottom is printed (~21 LEDs per segment).
- Cut into 12 equal segments (center cuts on pads).
- Tin all pads on both ends before install.

---

## 2. Layout (Critical)
- Label cube legs 1–12 with tape.
- Mark direction arrows.
- LED arrows must follow your marked path.

**Note:** A continuous path requires 3 loopbacks (legs 10–12).
- Route wires under one strip at loopbacks.
- Start at leg 12 and work backward:
  - 12→11→10→9→...→1

---

## 3. Wiring & Soldering
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0add1354-f356-420e-b43e-f20e814ec17c" />
- Bend wire to match connection.
- Hold on tinned pad.
- Touch iron.
- Let cool.
- Trim excess.

**Tip:**  
- Use inner full pads for power.  
- Use end pads only for data.
![IMG_0617](https://github.com/user-attachments/assets/2593c2cb-8d43-4d6d-a427-bbd5fc34b3a4)
![IMG_0619](https://github.com/user-attachments/assets/530dbabe-3b1b-4ac6-9911-13019127f0e6)
![IMG_0631](https://github.com/user-attachments/assets/37fffddd-fa41-4e23-b3f3-ca76db19e231)

---

## 4. Controller Install
- Wire per diagram.
- Keep wires tidy and tuck under controller.
- Secure with glue or melted PLA tabs.

![IMG_0635](https://github.com/user-attachments/assets/6b5a74f5-d0f7-44f6-a2e4-080b5b7d299e)

**Software:** WLED  
https://kno.wled.ge/basics/getting-started/

---

## 5. Mirror Panels (Final Step)
⚠️ Double-check connections before sealing.

**Test:**
- Run solid pattern.
- Tap connections with wooden toothpick.
- Fix any flicker.

**Panels:**
- 3mm pre-mirrored acrylic recommended.

**Install:**
- Glue first 5 panels (small corner dabs).
- Install final panel with suction cup or gravity.
- Secure with small drops of CA glue.

![IMG_0636](https://github.com/user-attachments/assets/0095ecb7-6421-441a-9342-d9a52df6340e)

