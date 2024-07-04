# Robin-Migration-Distance
This script is referenced in graduate student Susan Reed's M.S. thesis in Biology at Indiana University, summer 2024: "_________"

This script uses the "assignR" package in R Studio to designate the non-breeding location and migration distance of individuals from two populations of the American robin songbird, <em>Turdus migratorius</em> — one that breeds in Anchorage, AK, and another that breeds in Bloomington, IN.

This script is modified code from collaborator Dr. Tara M. Smiley (tara.smiley@stonybrook.edu).

The assignR requirements include:
(1) the species range spatial extent or shapefile, 
(2) a precipitation-weighted isoscape that is temporally and spatially relevant to the tissue being modeled (i.e., here, non-breeding period claw tissue),
(3) known-origin stable isotope values (likely referenced directly from the package), and
(4) unknown-origin stable isotope values in .csv format.


If you do not have a precipitation-weighted isoscape, follow the script labeled "#1. Precip-weighted isoscape" to create the appropriate objects to run the assignR script.
