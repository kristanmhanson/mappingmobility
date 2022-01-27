<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring" 
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a visual essay.  Complete [Documentation](https://juncture-digital.org/docs) and helpful [examples](https://juncture-digital.org/examples) are available on the [Juncture site](https://juncture-digital.org).
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

## Pelargonium annotations

The Grasse-based [Chiris perfumerie,](https://monumentum.fr/anciennes-parfumeries-chiris-pa00080934.html) founded by Antoine Chiris in 1768, provides a case study on the production of pelargonium oils.[^ref32] The artisanal factory specialized in manufacturing soaps, ointments, scented waters, and perfumes from aromatic plants. In the nineteenth century, Chiris expanded into a global, industrial company with many farms in colonized territories. For example, it used colonial labor to grow “Rose geranium” or _Pelargonium graveolens_ in Boufarik, Algeria. In 1865, the company built a cutting-edge 3,000 square meter factory in Boufarik’s Saint-Marguerite domain, growing pelargoniums along with orange and eucalyptus trees.[^ref33] The group of photographs, shows the Chiris complex and its workers engaging in cultivating, harvesting, and preparing pelargoniums for making rose-scented oils and other products.
<param ve-entity eid="Q2344308" title="Boufarik">
<param ve-entity eid="Q45669" title="Eucalyptus" aliases="eucalyptus">
<param ve-entity eid="Q81513" title="Citrus" aliases="orange">
<param ve-image fit="contain" title="Pelargonium fields and floricultural industry, Algeria. Anonymous, no publication date [1900s-1910s?], black and white photograph from glass plate" attribution="Source gallica.bnf.fr / BnF" url="Chiris_Factory.jpg">
<param ve-plant-specimen region="3500,3116,3515,3068" jpid="10.5555/al.ap.specimen.k000417315">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
