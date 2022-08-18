# `Angle Cutoff` variable for Hydrogen Bonds in VMD

Consider the following water dimer (`pdb` and `vmd` files in repository),

Below I've written as well the angles that are printed in the terminal window when measuring them with vmd.

![10_water_molecules_only_2_dimer_only](https://user-images.githubusercontent.com/18029016/185359915-79b2baa2-dd67-4174-ace1-09b468714a71.png)

The hydrogen bond is not detected for `Angle Cutoff = 29` but it is detected for `Angle Cutoff = 30` (see below figures)

I'm wondering which is this `Angle Cutoff` that VMD is referring to, since 30 does not seem to match any of the `a`, `b` or `c` angles marked in the image.

![29](https://user-images.githubusercontent.com/18029016/185360561-91b8be55-3a52-4b0a-b8b9-d5089a63baec.png)
![30](https://user-images.githubusercontent.com/18029016/185360595-82909016-2df4-4dc9-9c5d-4af54c048886.png)
