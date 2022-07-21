
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/jxjo/Airfoils/JX-GS">
    <img src="images/JX-GS_family.png" alt="Logo"  >
  </a>
</p>

# JX-GS
Airfoil family for fast F3F style slope gliders

| Airfoil      | Thickness      | Camber         | Re*Sqrt(cl) |
| :---:        |     :---       |   :---         |  ---:       |
| JX-GS-15     | 7.6% at 27,7%  | 1.46% at 40.0% |  150k       |
| JX-GS-10     | 7.4% at 26.8%  | 1.47% at 36.1% |  100k       |
| JX-GS-06     | 7.1% at 25.0%  | 1.47% at 32.3% |   60k       |
| JX-GS-04     | 6.9% at 23.9%  | 1.48% at 30.7% |   40k       |

### Calculation of Re*Sqrt(cl)
The value of Re*Sqrt(cl), which equals to the fixed lift T2 polar, can be easly calculated with the approximation formula

`Re*Sqrt(cl) = 900 * l * sqrt(Ws)` with `l  chord length [cm]` and `Ws wing load    [g/dm²]`

Example: 
A wing with a wing load of 70 g/dm² will have at chord length 20cm a value of:
Re*sqrt(cl) = 900 * 20 * sqrt(70) = 150000.
So airfoil JX-GS-15 would be a good choice at this section.  

### License
Unless otherwise noted, these files are licensed under the Creative Commons [Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0) license.



