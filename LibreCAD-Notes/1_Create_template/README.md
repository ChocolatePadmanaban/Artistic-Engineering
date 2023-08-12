# 1 Create A Template 

## 1.1 Preparations

1. -  Edit present Layer 

![Edit Present Layer](./images/1_edit_layer)

- Set Layer Settings value 

![increase Layer Width](./images/2_increase_layer_width)

2.  Check Current Drawing preferences

- Go to current drawing preference

![go to cdp](./images/3_Current_Drawing_Preference.png)

- Edit Current Drawing preference 

```
- Paper: Select A4 Format, Orientation Landscape, and pay attention to the dimensions: Width 297 mm, Height 210 mm
- Units: Main drawing unit Millimeter, Format Decimal, precision 0.0000 (precision machinery today go to a thousandth of a millimeter or less – in construction engineering an inch is a precise measure)
- Grid: Default selections are OK (Grid on, Orthogonal, etc.)
- Dimensions: Change Text Height to 2 mm, leave the rest as they are
- Splines: No actions
```

![2mm text change](./images/4_2mm_text.png)

## 1.2 Draw the Border

1. Draw the outer rectangle, we are going to draw a 277x190 mm rectangle, as an A4 page is 297x210 mm 

go to cammand box , type the followign commands lines after each line type enter 

```
rec
0, 0 
277, 190
```
for auto-zoom , and rectangle to be visible, Enter in the same command-box
```
za
```
Press [**Esc**] to end the task

![Rectangle Output](./images/5_draw_rec.png)


2. Draw Boarder parallel lines

- 