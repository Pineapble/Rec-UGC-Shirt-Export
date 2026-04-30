# How to recreate your custom shirt using the export model

Make sure you apply this to the blank orange shirt that downloads with your avatar if you try to export a UGC shirt.
![Step 0 Image](/images/1.png)

---

## 1 - Extracting your shirt files from Rec Room library

(Ensure you have loaded all your shirt files in-game recently. This is necessary for them to appear)

### 1.1 - Download the latest .exe release of the following tool, or build your own from source.

EXE Release:
[https://github.com/longwalter/LibraryCacheDownloader/releases/tag/v1.0.0](https://github.com/longwalter/LibraryCacheDownloader/releases/tag/v1.0.0)

---

### 1.2 - Run the file, and grab your shirt texture from the new ‘DownloadedImages’ folder that appears in the same file path you ran the program in.

It should look something like this

![Step 1.2 Image](/images/2.png)
![Step 1.2 Image](/images/2.5.png)

---

## 2 - Setting up your shirt texture

Download the provided .psd file and open it in [https://www.photopea.com/](https://www.photopea.com/) (free) or photoshop.

This guide will be based on photopea

### 2.1 - Open the PSD

You should see this

![Step 2.1 Image](/images/3.png)

---

### 2.2 - Import your shirt texture

next, import your shirt texture using file → open and place

![Step 2.2 Image](/images/4.png)

---

### 2.3 - Move the shirt layer

Drag the shirt layer behind the template layer

![Step 2.3 Image](/images/5.png)

---

### 2.4 - Rasterize the shirt layer

Right click the shirt layer, and click ‘rasterize’ to ensure you’ll be able to edit it to fit the sides of the template

![Step 2.4 Image](/images/6.png)

---

### 2.5 - Position the shirt texture

Using ctrl + T (not sure about mobile controls), position the shirt texture so it lines up with how you want the front and back of the shirt to look.

You can use the select tool to move part of the image to center it on the other side of the template.

It should look like this

![Step 2.5 Image](/images/7.png)

---

### 2.6 - Hide the template layer

Now click the eye to hide the template layer

![Step 2.6 Image](/images/8.png)

---

### 2.7 - Edit colors and details

You can select the background layer and use the paint bucket tool to fill in the orange part of the shirt with another colour of your choice, and make further adjustments to the shirt collar or jeans sections.

For further editing knowledge, watch a photopea tutorial.
---

### 2.8 - Export your shirt

Now export your shirt as png

![Step 2.8 Image](/images/9.png)

---

## 3a - Adding your texture in blender

### 3a.1 - Open shading tab

Select the shirt, go to the ‘shading’ tab

![Step 3a.1 Image](/images/10.png)

---

### 3a.2 - Remove unnecessary maps

delete the custom roughness and normal maps, we don’t really need those where we're going

![Step 3a.2 Image](/images/11.png)

---

### 3a.3 - Remove base color image

click the ‘x’ on the remaining base color image module

![Step 3a.3 Image](/images/12.png)

Then open your shirt texture

![Step 3a.3a Image](/images/13.png)

---

Easy Peasy done!
![Step 3a done Image](/images/14.png)

---

## 3b - adding your texture in Unity

### 3b.1 - Create a material

Create a material

![Step 3b.1 Image](/images/15.png)

---

### 3b.2 - Assign texture

Select the new material, drag your shirt texture to ‘albedo’ in the inspect tab

![Step 3b.2 Image](/images/16.png)

---

### 3b.3 - Apply material

Drag your material onto the shirt!

![Step 3b.3 Image](/images/17.png)

---

Easy!
