Edward Israel
######################

* **Cycles:** Recommended
* **EEVEE:** NOT COMPATABLE
  
Overlapping Panels with optional seams and triangulation.

.. image:: ./_static/images/thumb_edward_israel.png
  :alt: Edward Israel Material
  :width: 100%

.. image:: ./_static/images/nodes_edward_israel.png
  :alt: Edward Israel Material
  :width: 100%



Edward Israel Inputs
**************************************

* **Vector**: The UV Mapping Vector Input. A UV Map is recommended.
* **Seed**: Seed to set the random pattern.
* **Color 1**: First color variation for panels.
* **Color 2**: Second color variation for panels.
* **Border Color**: Border Color of seams.
* **Border Width**: Width of norder seams.
* **Triangulation**: The amount of triangulation in the pattern.
* **Triangulation Seed**: The randomness of the triangulation pattern.
* **Metallic**: The amount of roughness in the texture.
* **Roughness**: The amount of roughness in the texture.
* **Blur Amount**: Amount of noise introduced to blue the texture.  Best for Cycles. Set to zero for EEVEE.
* **Blur Detail**: The size of the noise used for the blur effect.
* **Max Height**: The Maximum height of the panels.
* **Medium Panels**: The amount of medium sized panels.
* **Small Panels**: The amount of small sized panels.

Edward Israel Outputs
**************************************

* **Shader**: The overall material shader output.
* **Albedo**: The diffuse color channel.
* **Metallic**: The metallic map.
* **Roughness**: The roughness map.
* **Height**: The height map, useful for displacement.
* **Normal**: The normal map used for the bump map.