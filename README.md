# Automating the Calculation of Stellar Temperature

Stellar temperature is super important to cosmology and astronomy, but it's difficult to calculate. Astronomers need to measure the star's luminosity, distance, and size each time! I wanted to remedy that so that scientists could first find the star's temperature independent of those factors and then use the temperature to find them. To do that, we need stellar spectra. Yes, spectra are difficult to source. But so long as we have access to these spectra, a star's temperature can be accurately calculated without ever needing to know its distance, an arguably more difficult metric to find. 

## Methodology

Using the stellar spectra, the general idea is to find the maximum of the regressed data and apply Wein's Law to find the temperature of the star. For the purposes of research, I tested some other methods but they weren't really interesting in terms of outcomes. 

## Materials

See my research paper here for details about the methods, data, results, and discussion. And take a look at all the code for the project [here](\ACST_Condensed.ipynb)
