# Volume of an arepa

The arepa is our gastronomical signature. Here is a way to calculate the volumen based on diameter and thickness.

```python
from math import pi

height = float(input('Altura de la arepa cm: '))
diameter = float(input('Diametro de la arepa en cm: '))
volume = pi * ((diameter-height)/2) * ((diameter-height)/2) * height
print("El Volumen del cilindro ", volume, "cm3")


Rinput = diameter/2 #radio de la arepa
Rcil = Rinput - (height/2)
R_semi_torus = Rcil+4*(height/2)/(3*pi)
Volume = (float)(2 * pi * pi * R_semi_torus * (height/2) * (height/2));
print("Volumen de medio toroide: ", Volume/2);

Volumen_de_la_arepa = volume+Volume/2
print("El Volumen de la arepa es: ",Volumen_de_la_arepa, "cm3")
```

Prototipos para máquina de arepa

<a href="https://spanish.alibaba.com/product-detail/new-design-automatic-arepa-making-machine-encrusting-machine-hot-product-2019-fully-automatic-304-stainless-steel-for-sale-price-62357808633.html?spm=a2700.galleryofferlist.normal_offer.d_title.4dab23480cDvhC"> Prototipo_1<a\>
