# HAH-III
Hubble Asteroid Hunter III data

This file corresponds to the asteroid population used in:
Hubble Asteroid Hunter - III. Physical properties of newly found asteroids
Pablo García-Martín, Sandor Kruk, Marcel Popescu, Bruno Merín, Karl R. Stapelfeldt, Robin W. Evans, Benoit Carry and Ross Thomson
A&A, 683 (2024) A122
DOI: https://doi.org/10.1051/0004-6361/202346771

This file is a list of objects divided in two asteroid sets: known and unknown objects. The unknown objects feature calculation uncertainties (columns marked as "U", "upper" or "lower") while the known objects have blank values in those columns. 

The values are calculated using the parallax method as explained in the published work referenced above.

Columns correspond to:

- asteroid ID: internal asteroid designation
- fname: HST image id
- distance_geo: calculated distance to Earth
- dist_geo_Ur_upper or dist_geo_U_upper: upper uncertainty
- dist_geo_Ur_lower or dist_geo_U_lower: lower uncertainty
- distance_SSB: distance to Solar System Barycenter
- distance_SSB_U_upper/lower: uncertainty
- HEx, HEy, HEz: heliocentric ecliptic coordinates for the object
- ELat: ecliptic latitude
- Phase_Ang: phase angle
- Escape_Vel: calculated escape velocity
- Object_Vel: calculated object velocity
- min_a: minimum semimajor axis
- min_e: minimum eccentricity
- min_i: minimum inclination
- max_i: maximum inclination
- MagCor_input: apparent magnitude in the filter used by HST for this image
- coor_to_V_apparent: apparent magnitude corrected to V band
- H: absolute magnitude
- H_lower/upper: uncertainty
- chisq: chi square for trail fitting
- size15: size in km calculated using a 0.15 albedo
- size15_lower/upper: uncertainty
- DorR: direct or reverse direction of motion for the asteroid (using HST image as a pixel array)
- Tisserands_imin/imax: Tisserand's parameter calculated using i_min and i_max values
