**In this repositary we have implemented the Various view of data visualization with various library using LiDAR Data.**


**--------------------------Views-------------------------**

**Front View**

![front view](https://user-images.githubusercontent.com/84854222/119775614-7a144580-bee1-11eb-8e88-0b41a04e7a98.png)


**Top View(Matplotlib)**

![top view](https://user-images.githubusercontent.com/84854222/119775676-90ba9c80-bee1-11eb-96ba-2a6d82f4bf8a.png)


**3D view(Mayavi)**

![Mayavi](https://user-images.githubusercontent.com/84854222/119784876-44288e80-beec-11eb-9437-5b746277e4d3.png)

PyQT 
![image](https://user-images.githubusercontent.com/84854222/119793584-59092000-bef4-11eb-843b-7ecbc761d3dd.png)

Vispy

![image](https://user-images.githubusercontent.com/84854222/119793757-7f2ec000-bef4-11eb-9598-ffda941a3330.png)




**We have ranked the  various visualization Libraries using LiDAR data**

**Name of the Plotting Environment       and Timing (fps)**
  
    Vispy                                 0.9 sec (per frame)

    Mayavi                                1.2 sec (per frame)

    Matplotlib                            0.2 sec (per frame) 


    +------------+------------------------------+--------------------------------------+
    | library    | Advantage                    | Disadvantage                         |
    |  name      |                              |                                      |
    +------------+------------------------------+--------------------------------------+
    | matplotlib | Faster than all              | Don't have interactive view          |
    |            |                              | (like 360 degree rotation)           |
    +------------+------------------------------+--------------------------------------+
    | mayavi     | Interactive view             | installation is difficult            |
    +------------+------------------------------+--------------------------------------+
    | vispy      | quite faster                 | Creating bounding boxes is difficult |
    +------------+------------------------------+--------------------------------------+
    | pyqt       | the object visulaization     | Don't have in-build save function    |
    |            | is too clear when compare to | like matplotlib has plt.savefig.     |
    |            | other lib.                   | there is no such save function       |
    +------------+------------------------------+--------------------------------------+

