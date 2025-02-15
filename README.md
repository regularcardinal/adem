# adem

Takes a sum of monomials of Steenrod squares and applies the Adem relations (http://mathworld.wolfram.com/AdemRelations.html) to each summand. Thus, adem.py outputs a sum of monomials that are written with respect to the Serre-Cartan basis for the Steenrod algebra, also known as "admissible form".

The code is based on that in https://github.com/regularcardinal/steenrod/blob/master/src/main/Steenrod.java, but simplified and "Python-ized".

## Note!

You can try this code in a browser at https://regularcardinal.net/adem (previously a [Flask](https://palletsprojects.com/p/flask/) app, now served via Go -- see https://github.com/regularcardinal/regularcardinal).
