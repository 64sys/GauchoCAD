# GauchoCAD
GauchoCAD is a free CAD program written in the Gambas language.

![Screenshoot](./screen.png)

## Graphics
Actually we use the OpenGL library for the graphics (before we try cairo and paint) because is really fast but some work still there with the diferent line styles like dashed

## History
At the beginning this program was created as a practice in the use of classes and over time it was mutating, increasing the number of graphic tools, improving the interface etc.
CAD programs belong to the group of large and complex programs since for this to work it must handle various things from geometric calculations and graphical representation to configurations, user profiles, interpreter of orders, scripting printing, export and import in differents files formats, etc.
GauchoCAD is currently under development and the status is as follows:

![Status](./status.png)

## Using

# Entities
| Icon | Alias | Name | Description |
|------|:-----:|:----:|------------:|
| <img src="./svg/entities/arc.svg" width="48" height="48"> | a | Arc | Create an arc |
| <img src="./svg/entities/circle.svg" width="48" height="48"> | cv | Circle | Create a circle |
| <img src="./svg/entities/dim.svg" width="48" height="48"> | dw | Dim | Create a dimension |
| <img src="./svg/entities/ellipse.svg" width="48" height="48"> | ew | Ellipse | Create an ellipse |
| <img src="./svg/entities/hatch.svg" width="48" height="48"> | ht | Hatch | Create an hatch |
| <img src="./svg/entities/insert.svg" width="48" height="48"> | b | Insert | Create a block insert |
| <img src="./svg/entities/leader.svg" width="48" height="48"> | li | Leader | Create a leader |
| <img src="./svg/entities/line.svg" width="48" height="48"> | l | Line | Create a line |
| <img src="./svg/entities/mtext.svg" width="48" height="48"> | tt | Mtext | Create a mtext |
| <img src="./svg/entities/pline.svg" width="48" height="48"> | po | Pline | Create a polyline |
| <img src="./svg/entities/rectangle.svg" width="48" height="48"> | re | Rectangle | Create an rectangle |
| <img src="./svg/entities/solid.svg" width="48" height="48"> | sa | Solid | Create an solid |
| <img src="./svg/entities/spline.svg" width="48" height="48"> | sq | Spline | Create an spline |
| <img src="./svg/entities/text.svg" width="48" height="48"> | t | Text | Create a text |


# Tools
| Icon | Alias | Name | Description |
|------|:-----:|:----:|------------:|
| <img src="./svg/tools/break.svg" width="48" height="48"> | bg | Break | Brak a entity in two parts |
| <img src="./svg/tools/chamfer.svg" width="48" height="48"> | cd | Chamfer | Create a chamfer from two lines |
| <img src="./svg/tools/copy.svg" width="48" height="48"> | c | Copy | Copy an entity |
| <img src="./svg/tools/divide.svg" width="48" height="48"> | dx | Divide | Divide an entity |
| <img src="./svg/tools/erase.svg" width="48" height="48"> | de | Erase | Delete an entity |
| <img src="./svg/tools/extend.svg" width="48" height="48"> | e | Extend | Stretch an entity from one end |
| <img src="./svg/tools/fillet.svg" width="48" height="48"> | f | Fillet | Create a tangential arc to two lines |
| <img src="./svg/tools/mirror.svg" width="48" height="48"> | mn | Mirror | Create a new entity mirroring another |
| <img src="./svg/tools/move.svg" width="48" height="48"> | m | Move | Move a site entity |
| <img src="./svg/tools/offset.svg" width="48" height="48"> | fg | Offset | Create a parallel entity |
| <img src="./svg/tools/pan.svg" width="48" height="48"> | zc | Pan | Displacement of sight |
| <img src="./svg/tools/rotate.svg" width="48" height="48"> | rt | Rotate | Rotate an entity |
| <img src="./svg/tools/scale.svg" width="48" height="48"> | sc | Scale | Scale an entity |
| <img src="./svg/tools/stretch.svg" width="48" height="48"> | s | Stretch | Stretch an entity |
| <img src="./svg/tools/trim.svg" width="48" height="48"> | tr | Trim | Cut an entity |
| <img src="./svg/tools/zoome.svg" width="48" height="48"> | zx | Zoome | View fit to all entities |
| <img src="./svg/tools/zoomw.svg" width="48" height="48"> | z | Zoomw | View window |


# Layers
| Icon | Alias | Name | Description |
|------|:-----:|:----:|------------:|
| <img src="./svg/layers/layers.svg" width="48" height="48"> | lk | Layers |  |

# Smart - concret structures
| Icon | Alias | Name | Description |
|------|:-----:|:----:|------------:|
| <img src="./svg/smart/beam.svg" width="48" height="48"> | w1 | Beam |  |
| <img src="./svg/smart/column.svg" width="48" height="48"> | w2 | Column |  |
| <img src="./svg/smart/slab3p.svg" width="48" height="48"> | w3 | Slab3P |  |
| <img src="./svg/smart/slab4p.svg" width="48" height="48"> | w4 | Slab4P |  |
| <img src="./svg/smart/wallcolumn.svg" width="48" height="48"> | w5 | Wallcolumn |  |

# Locks
| Icon | Key | Name | Description |
|------|:-----:|:----:|------------:|
| <img src="./svg/locks/help.svg" width="48" height="48"> | F1 | Help |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F2 | Spare |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F3 | Spare |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F4 | Spare |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F5 | Spare |  |
| <img src="./svg/locks/bounds.svg" width="48" height="48"> | F6 | Bounds | Enable or disable the bounds in drawing |
| <img src="./svg/locks/grid.svg" width="48" height="48"> | F7 | Grid | Enable or disable the grid in screen |
| <img src="./svg/locks/ortho.svg" width="48" height="48"> | F8 | Ortho | Enable or disable the orthogonal mode |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F9 | Spare |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F10 | Spare |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F11 | Spare |  |
| <img src="./svg/locks/spare.svg" width="48" height="48"> | F12 | Spare |  |

## Contact
gauchocad@gmail.com

## Gambas project
Gambas is a free development environment and a full powerful development platform based on a Basic interpreter with object extensions.
http://gambas.sourceforge.net/en/main.html



