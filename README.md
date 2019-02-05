# CurveTransformation
Small Python module that replicates Lefty's Astrophotography crazy curve transformation from PixInsight

Replicates Curves Transformation from PixInsight on RGB space images, using akima subspline interpolation and a set of points to define the curve.


The particular curve defined in this program replicates the curve created by Lefty. 


## How it works
Takes a url of a jpg or png image. Downloads it, applies the transformation, writes the edited image to disk and then returns the filename. Deletes original downloaded file. 
