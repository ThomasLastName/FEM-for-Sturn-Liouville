# FEM-for-Sturm-Liouville
Use FEM to approximate a solution to the Sturm-Liouville problem with homogeneous boundary conditions in the span of some pointy bois (https://en.wikipedia.org/wiki/Triangular_function).
Slightly more information, though admittedly not a complete discussion, can be found in the corresponding writeup for the original problem (https://www.overleaf.com/read/wpbppmwyjnkw).
The algorithm fails ocasionally, but when it does so it will not lead to false results, as it will fail spectacularly. If that happens, literally just restart it.
I don't understand why, but running the same code multiple times it only fail a fraction of the time (and once it has been successfully run, it typically will no longer fail).
This behavior is somehow related to Numba (which I still do not completely understand), and if anyone has any insight on the matter, an email on the subject is welcome (my address found at https://sites.google.com/view/my-undergrad-site/main).
