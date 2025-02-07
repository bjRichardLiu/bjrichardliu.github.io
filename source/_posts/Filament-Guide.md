---
title: A Beginner's Guide to 3D Printing Filament
date: 2025-02-05 18:26:47
categories:
- guides
tags: 
- 3D Printing
- guides
---
# Introduction
This guide is intended to provide a beginner's guide about common 3D printing filaments. It will cover the most common types of filaments, their properties, and their use cases, as well as some tips for printing with them. A lot of the information and tips comes from my colleagues at [Bambu Lab](https://www.bambulab.com/), where I worked as a Graphics Algorithms Engineer Intern in the summer of 2024. I hope you find this guide helpful!

Since I used Bambu filament the most, I will use their filaments as examples in this guide. But the information should be applicable to filaments from other manufacturers as well.

This guide will mainly cover easy to print filaments, for more advanced and engineering filaments, please refer to other resources.

The guide will be updated as I learn more about 3D printing and filaments, and please let me know if you have any suggestions or corrections!

# PLA
PLA (Polylactic Acid) is one of the most common filaments used in 3D printing. It is very easy to print, it can print at low temperatures, it sticks well to the bed, and it doesn't warp. It is marketed as an bio-degradable filament, but it requires industrial composting to break down. But it is still a great filament, easy to work with, and not as toxic as filaments like ABS.
<div style="display: flex; justify-content: space-between;">
    <div class="image-container">
        <a href="https://store.bblcdn.com/494435955614642176.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/494435955614642176.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="PLA Matte from Bambu" class="image">
        </a>
    </div>
    <div class="image-container">
        <a href="https://store.bblcdn.com/494434261673332736.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/494434261673332736.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="PLA Silk Dual Color from Bambu" class="image">
        </a>
    </div>
    <div class="image-container">
        <a href="https://store.bblcdn.com/494434238034571264.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/494434238034571264.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="PLA Galaxy from Bambu" class="image">
        </a>
    </div>
</div>

## Pros
- Easy to print
    - Even without drying, modern printers can print PLA with minimal issues
- Cheap
- Easy to find
- Works well with all machines
- Tones of options for colors and finishes
    - You can get most of the colors you want (There are even multicolor filaments, the model will have different colors in different layers/directions)
    - Surface finished including generic, silk, matte, metallic, etc.
    - Can also add glitter, wood, or carbon fiber particles for different finishes/properties

## Cons
- Not as strong as other filaments
- Not heat resistant
- Not UV resistant
- Not food safe
- Not water resistant
- Will degrade over time(especially in sunlight)
    - After a few years, the print will become brittle and break

## Special Notes
- PLA is the best filament for beginners, and it is the best for decorative prints
    - Galaxy/Sparkle are really great at hiding layer lines
    - Definitely checkout PLA wood! It looks and feels like wood
    ![PLA Wood from Bambu](https://cdn.shopify.com/s/files/1/0584/7236/6216/files/PLA_Wood_Feature_1-1_PC_42eae015-3608-4799-ac85-cb791c39186e.png?v=1731466856)
    - Metal finishes are good for car models
    ![A model showcasing different types of PLA](https://store.bblcdn.com/3427076cd10d4e979e80eba42e7899d6.jpg)
    - There are also glow-in-the-dark filaments, filaments that change color with temperature, PLA definitely is the most fun filament
- For any filament with particles(Galaxy, Sparkle, Wood, CF), use at least 0.4mm nozzle, 0.6mm is recommended
    - Even though the particles are small, multiple particles can clog the nozzle
    - It is also recommended to use a hardened nozzle
- The new flexible and bouncy PLA are also really interesting! They are more bouncy than TPU, so great for airless basketball, check [this video](https://www.youtube.com/watch?v=o7PgO1OzgqM) for more details
- When changing filaments, darker colors will require more purging to get a pure new color
- White PLA is a bit transparent
    - Good for light diffusion or lamp prints
    - Don't flush other color inside a white print, it will show up(same for other light colors)
- PLA does NOT stick to PETG, so for multi-material prints, you can't use PLA with PETG
    - But, you can use PETG for the support surface of a PLA print, making support easier to remove, please refer to [this guide from Bambu Wiki](https://wiki.bambulab.com/en/filament-acc/filament/pla-basic-and-petg-hf)
    - There are dedicated support filaments, they will have better surface finish, but they are more expensive
    - There are also water dissolvable support filaments, it will just dissolve in water, suitable for complex prints, but they are very expensive, and needs to be stored in a dry place, or it will just broken down itself
![Change Support Interface in Bambu Studio (source: Bambu Wiki)](https://wiki.bambulab.com/software/bambu-studio/support/%E6%94%AF%E6%92%91%E9%9D%A2en.png)


# PETG
PETG (Polyethylene Terephthalate Glycol) is another common filament used in 3D printing. It is stronger and more heat resistant than PLA, but it is also a bit harder to print. It requires higher temperatures, it is more prone to warping, and it can be stringy. But it is still a great filament, it is strong, and it is more resistant to UV and water.
<div style="display: flex; justify-content: space-between;">
    <div class="image-container">
        <a href="https://store.bblcdn.com/494435453950717952.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/494435453950717952.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="PETG from Bambu" class="image">
        </a>
    </div>
    <div class="image-container">
        <a href="https://store.bblcdn.com/494434758727716864.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/494434758727716864.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="PETG Translucent from Bambu" class="image">
        </a>
    </div>
    <div class="image-container">
        <a href="https://store.bblcdn.com/s1/default/74901ade628b4d8da7ea810eb6baa620.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/s1/default/74901ade628b4d8da7ea810eb6baa620.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="PETG CF from Bambu" class="image">
        </a>
    </div>
</div>

## Pros
- Doesn't require enclosure to print
- Stronger than PLA
- More heat resistant than PLA
- More UV resistant than PLA
- More water resistant than PLA
- More durable than PLA
- Similar price to PLA
- Available in many colors and finishes, but not as many as PLA
- PETG transparent is the clearest filament you can get

## Cons
- Harder to print than PLA (but not a big issue for modern printers)
- Drying is important, or it will be stringy
- More prone to warping than PLA
- Doesn't stick to the bed as well as PLA

## Special Notes
- For printing PETG transparent, if you want to achieve full transparency, you need to dry the filament, use bigger nozzle, print slower, higher temperature, and 100% infill to get a clear print, check [this guide](https://www.printables.com/model/15310-how-to-print-glass) for more details
    - Drying is very important, even a little moisture will make the filament stringy
    ![Drying is important! (source: Bambu Lab)](https://store.bblcdn.com/aeecca4c06e04e578e58b10c82342865.jpg)
    - Depending on the flow, adjust the infill between 99% and 100%
    - Refer to the manufacturer's recommendations is also a good idea
    ![Printed transparent model from Bambu Wiki](https://wiki.bambulab.com/knowledge-sharing/transparent-petg/%E6%89%93%E5%8D%B0%E9%80%8F%E6%98%8E%E6%95%88%E6%9E%9C%E5%B1%95%E7%A4%BA.png)
- PETG does NOT stick to PLA, so for multi-material prints, you can't use PLA with PETG
    - But, you can use PLA for the support surface, making support easier to remove

# TPU
TPU (Thermoplastic Polyurethane) is a flexible filament used in 3D printing. It is very flexible, best for printing things like phone cases, shoes, and tires. It is also very stretchy, so it is hard to print on some machines.

p.s. I haven't use TPU much, so please take this section with a grain of salt
<div style="display: flex; justify-content: space-between;">
    <div class="image-container">
        <a href="https://store.bblcdn.com/494433984912519168.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
            <img src="https://store.bblcdn.com/494433984912519168.jpg__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="TPU 95A HF from Bambu" class="image">
        </a>
    </div>
    <div class="image-container">
        <a href="https://store.bblcdn.com/494434035307081728.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80">
        <img src="https://store.bblcdn.com/494434035307081728.png__op__resize,m_lfit,w_1920__op__format,f_auto__op__quality,q_80" alt="TPU 95A HF from Bambu" class="image">
        </a>
    </div>
</div>

## Pros
- Doesn't require enclosure
- The most common flexible filament

## Cons
- Very stretchy, hard to print on some machines
- Most filaments are not compatible with multi-material systems, very easy to slip on the gears
- Less color options

# Other Filaments
There are many other filaments available, including ABS, ASA, Nylon, PC, PVA, HIPS, etc. But they are less common and harder to print, so I won't cover them in this guide. Most of them requires enclosure, and needs higher temperature to print, and they are more prone to warping. But they are also stronger and more heat resistant than PLA and PETG. So for functional parts, they are better choices.

A note for ABS is that it is toxic, so you need to print in a well-ventilated area.


