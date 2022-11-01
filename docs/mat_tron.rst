Tron
######################

* **Cycles:** Recommended
* **EEVEE:** Compatible

Stylized Glowing Panels with variable border effect and bright seams.

.. image:: ./_static/images/thumb_tron.png
  :alt: Tron Material
  :width: 100%

.. image:: ./_static/images/nodes_tron.png
  :alt: Tron Material
  :width: 100%

.. tip:: Glow in Cycles

   Use the Glare Node in the compositor to introduce glow in Cycles:

   .. image:: ./_static/images/tip_tron_compositor.png




.. tip:: Glow in EEVEE

   Enable "Bloom" under the Render Settings tab to produce a glow effect:

   .. image:: ./_static/images/tip_tron_eevee.png



Tron Inputs
**************************************

Voronoi Node Group
====================================

* **Vector**: The UV Mapping Vector Input. A UV Map is recommended.
* **Seed**: Seed to set the random pattern.
* **Metallic**: The amount of roughness in the texture.
* **Roughness**: The amount of roughness in the texture.
* **Panel Color**: Color of the panels
* **Seam Color**: Color of the seams between the panels.
* **Color Variation:** Variation of panel color.
* **Medium Panels**: The amount of medium sized panels.
* **Small Panels**: The amount of small sized panels.
* **Max Height**: The Maximum height of the panels.


Control Border Thickness
====================================

Controlled by a Voronoi Noise node, this varies the thickness of the borders between the panels.  Use the *Minimum Border Width* and *Maximum Border Width* paramters to change the thickness of the border variations.

Emission Node
====================================

This controls the strength of the glow.

Tron Outputs
**************************************

* **Shader**: The overall material shader output.
* **Displacement**: The displacement normal map.
* **Albedo**: The diffuse color channel.
* **Metallic**: The metallic map.
* **Roughness**: The roughness map.
* **Height**: The height map used for control of mixing in the Emission shader.
* **Normal**: The normal map used for the bump map.

