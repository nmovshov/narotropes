# narotropes
Naor's barotropes - template interface classes for pressure-density laws

This MATLAB package provides simple interfaces that help working with pressure-
density relations, called barotropes. The abstract base class, Barotrope,
defines the interface: a pressure(density) method and a density(pressure)
method. A few simple barotropes derived from the base are included. This package
is not typically used on its own. The recommended usage is to copy the
+barotropes folder to your own project and then add or modify as needed.
