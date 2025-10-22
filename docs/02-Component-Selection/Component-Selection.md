---
title: Component Selection Example
---



*Table 1: Force sensor*

**Internal Weight limit module**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://www.robotshop.com/cdn/shop/files/capacitive-force-sensor-8-mm-100-n-22-lbs.webp?v=1720520354&width=500)<br>Option 1.<br> Capacitive Force Sensor 8 mm 100 N (22 lbs)<br>$37.50/each<br>[link to product](https://www.robotshop.com/products/capacitive-force-sensor-8-mm-100-n-22-lbs?srsltid=AfmBOor19xwTwwhdVJn0yiEShylPY2O0GjxZPYAcsRH4sPB03Ol_urBEaN4)                 | \*Inexpensive<br>\* Fall within the weight limits<br>\* Connections are easy access                                               | \* Requieres model specific addons<br>\* Brittle. |
| ![](https://www.mouser.com/images/honeywell/lrg/FSG.jpg)<br>\* Option 2. <br>\* FSG005WNPB <br>\* $129.62/each <br>\* [Link to product](https://www.tti.com/content/ttiinc/en/apps/part-detail.html?partsNumber=FSG005WNPB&mfgShortname=HON&srsltid=AfmBOoqxZRMXxUbu3haqkQcgSzEY6cKdgm8rqvCJfbez0ZP6yMrMC1ZgK2Q) | \* Small in size <br>\* Low error percantage <br> \* Easy pin acces | * More expensive <br>\* Small sensor base                                                       |
| ![](https://www.tekscan.com/sites/default/files/a201-main.jpg)<br>\* Option 2. <br>\* FlexiForce A201 Sensor <br>\* $153.16/8pack <br>\* [Link to product](https://www.tekscan.com/products-solutions/force-sensors/a201?utm_source=google&utm_medium=cpc&utm_campaign=shopping&utm_term=flexi&srsltid=AfmBOop3h7dcBe6WylGcv82oo1NJw9CDjoKWqct8cF7wpX0699rHpx7Y9GM&v=290) | \* Good weight tolerance <br>\* Great Temperature tolerance range <br> \* Lightweight | * Only available in 8packs <br>\* Hard pin access                                                       |

**Choice:** Option 1: Capacitive Force Sensor 8 mm 100 N (22 lbs)

**Rationale:** Our choice 1 (Capacitive Force Sensor) is the option chosen for three different reasons: price, style, and versatility. This option has the best price of the three, as one can only be purchased in packs of 8, and the other is quite expensive due to its precision and size. Second, the pin selection is exposed and easily accessible for soldering. In turn, its light weight and design are quite helpful for the model we want to produce, where the basket rests on the base of the sensor.

### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
