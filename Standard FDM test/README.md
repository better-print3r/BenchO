Standard desktop FDM test
===============================

# Table of Contents
## STEP 1.Preparation & Info
- [Preparation](#step-1preparation)
- [General Info](#general-info)
## STEP 2.Test Model print & Settings
- [Basic Precision](#basic-precision)
- [Engineering](#engineering)
- [Art](#art)
- [Ruler](#ruler)
- [Tools](#tools)
## STEP 3.Measurement & Results
- [Precision & Accuracy](#precision--accuracy)
- [Base Quality & Edge](#base-quality--edge)
- [Base Bending](#base-bending)
- [Tolerance & Fit](#tolerance--fit)
- [Surface & Details](#surface--details)
- [Overhang & Bridge](#overhang--bridge)

## Test Example
- [Example](#example)
## FAQs
- [FAQs](#faqs)
## Score Distribution
- [Distribution table](#score-weight)
# STEP 1.Preparation

For Offline pdf version, Check [here](/Standard%20FDM%20test/BenchODocument.pdf).

## Software 
- **[BenchO]() ([Offline version](/Standard%20FDM%20test/BenchO_offline_ver20190823.xlsx))**
- [Test Models](/3Dmodel)
- [Tool Models(Ruler)](/3Dmodel/Ruler.STL)
## Hardware
- 3D printer for test
- **eSUN PLA+ filament(Grey)**
- A caliper with resolution up to 0.01mm and range larger than 100mm

# General Info

In the following section we will specify the parameters for standard test. You should print 5 test models in total to perform a complete test. In addition if you do not have a ruler(tool model) you should also print a ruler.
In our official test, all data are collected with **eSUN PLA+ (Grey)** .This type of filament should be widely available and easy to purchase. The Grey color makes it easier to identify surface details in the following test. If you use other types of filament. The result will be less comparable and will **not** be accept for official ranking.

This standard is created for desktop FDM 3D printers. Using this on other types of printer will generate inconclusive results.

# STEP 2.Test Model print & Settings
All models should strictly follow the designated parameters in a standard test.

**DO NOT RESCALE OR CHANGE THE TEST MODEL**.

You should start with a **default profile** in your slicing software and then change the parameters specified in the following section. For the parameters undeclared in the following section, keep it default.

Turn on all possible settings in your slicer. If you cannot find the settings required. Then it must be hidden in some advance menu in your slicing software.

**Do not** rotate the model along Z Axis in your slicing software
## Basic precision

There is only one model in this section: [Basic.stl](/3Dmodel/Basic.STL)

Using any default profile will be sufficient. You do not have to modify anything in specific but you could try different layer height.

## Engineering

There are two models: [Engineering1.stl](/3Dmodel/Engineering1.STL) and [Engineering2.stl](/3Dmodel/Engineering2.STL)

### Engineering1.stl
|     Setting     | Parameter |
|:---------------:|:---------:|
|   Layer height  |   0.2mm   |
| Wall line count |     2     |
|  Infill density |    100%   |
|  Infill pattern |    line   |
|     Support     |    None   |


### Engineering2.stl
|     Setting     | Parameter |
|:---------------:|:---------:|
|   Layer height  |   0.2mm   |
| Wall line count |     2     |
|  Infill density |    66%    |
|  Infill pattern | Triangles |
|    Top layers   |     0     |
|  Bottom layers  |     0     |
|     Support     |    None   |

## Art

There are two models: [Art1.stl](/3Dmodel/Art1.STL) and [Art2.stl](/3Dmodel/Art2.STL)

### Art1
|     Setting     | Parameter |
|:---------------:|:---------:|
|   Layer height  |   0.2mm   |
| Wall line count |     3     |
|  Infill density |     0%    |
|    Top layers   |     0     |
|     Support     |    None   |


### Art2
|     Setting     | Parameter |
|:---------------:|:---------:|
|   Layer height  |   0.2mm   |
| Wall line count |     2     |
|  Infill density |    20%    |
|     Support     |    None   |

### Ruler

There are one model:[Ruler.stl](/3Dmodel/Ruler.STL)

|     Setting     | Parameter |
|:---------------:|:---------:|
|   Layer height  |   0.2mm   |
| Wall line count |     2     |
|  Infill density |    20%    |
|     Support     |    None   |

![avatar](/Resource/Ruler1.png)

When printing this part you should put the ruler along one of the axis


## Tools

A caliper with resolution not less than 0.01mm and range larger than 100mm will be sufficient for the measurement. All data should be taken in .

The printed ruler in previous section will be your additional tool.

Check your ruler with known straight edge.

# STEP 3.Measurement & Results


## Precision & Accuracy
During measurement you should ignore the defects that are easy to remove. The test is designed to reflect the capability of your printer.
####

<center class="half">
<img src="/Resource/Basic1.png" width="400"/><img src="/Resource/Basic2.png" width="400"/>
</center>

This is the top view of the test model.You should take 8 measurements and fill the associative blank.
####
![avatar](/Resource/Basic2.png)

This is the top view of the test model.You should take 10 measurements and fill the associative blank.In this part you do not have to take data by order.
####
![avatar](/Resource/Basic3.png)

This is the front view of the test model.You should take 4 measurements and fill the associative blank.In this part you do not have to take data by order.


## Base Quality & Edge


####

![avatar](/Resource/ENG1.png)

You should take 8 measurements and fill the associative blank.

####
![avatar](/Resource/ENG2.png)

You should take 6 measurements and fill the associative blank.

## Base Bending

You should first bolt or fix your ruler in one of the four corner and then measure the gap between your ruler and the opposite side of the base. If there is no gap at all. Your result will be 0mm.
####

![avatar](/Resource/ENG3.png)

This will be an example for X axis measure.

####
![avatar](/Resource/ENG4.png)

This will be an example for Y axis measure.

## Tolerance & Fit

![avatar](/Resource/ENG5.png)

This is the Top view of the test model.You should take 6 measurements for each dimension and fill the associative blank

## Surface & Details

####
![avatar](/Resource/Art2.png)
Record the number of cameo level that is well printed.

Check the stringing

Check the ringing

## Overhang & Bridge

####
![avatar](/Resource/Art1.png)

This is the front view of the test model.You should measure the minimum distance between the bridge and base. Check if the space under bridges are clear.
####
![avatar](/Resource/Art3.png)

Check if there are major defects. Record the number of level that is perfectly printed.

# Example

# FAQs

# Score Weight

| Score Distribution     |                                 |        |          |
|------------------------|---------------------------------|--------|----------|
| section                | subsection                      | Weight | Subtotal |
| Part1: Basic Precision | XY relative precision           | 6      | 18       |
|                        | XY accuracy                     | 4      |          |
|                        | Small Scale accuracy            | 4      |          |
|                        | Z axis accuracy                 | 4      |          |
| Part2: Engineering     | Base Quality                    | 10     | 25       |
|                        | Edge and corner                 | 5      |          |
|                        | Large  Holes                    | 2\.5   |          |
|                        | Large Shafts                    | 2\.5   |          |
|                        | Small  Holes                    | 2\.5   |          |
|                        | Small Shafts                    | 2\.5   |          |
| Part3: Art             | Overhang Level                  | 4      | 25       |
|                        | cameo level                     | 4      |          |
|                        | Ringing size\(Included\)        | 5      |          |
|                        | Clear space between bridge      | 1      |          |
|                        | Bridge to bottom Distance\(mm\) | 3      |          |
|                        | Stringing                       | 3      |          |
|                        | Full height                     | 1      |          |
|                        | Disk\(Minimum layer height\)    | 4      |          |
| Part4:Time             | Engineering1                    | 10     | 32       |
|                        | Engineering2                    | 6      |          |
|                        | Art1                            | 10     |          |
|                        | Art2                            | 6      |          |
| Total                  | 100                             |        |          |

