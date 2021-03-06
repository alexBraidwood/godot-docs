.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the ParallaxLayer.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_ParallaxLayer:

ParallaxLayer
=============

**Inherits:** :ref:`Node2D<class_node2d>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

A parallax scrolling layer to be used with :ref:`ParallaxBackground<class_parallaxbackground>`.

Member Variables
----------------

  .. _class_ParallaxLayer_motion_mirroring:

- :ref:`Vector2<class_vector2>` **motion_mirroring** - The ParallaxLayer's :ref:`Texture<class_texture>` mirroring. Useful for creating an infinite scrolling background. If an axis is set to ``0`` the :ref:`Texture<class_texture>` will not be mirrored. Default value: ``(0, 0)``.

  .. _class_ParallaxLayer_motion_offset:

- :ref:`Vector2<class_vector2>` **motion_offset** - The ParallaxLayer's offset relative to the parent ParallaxBackground's :ref:`ParallaxBackground.scroll_offset<class_ParallaxBackground_scroll_offset>`.

  .. _class_ParallaxLayer_motion_scale:

- :ref:`Vector2<class_vector2>` **motion_scale** - Multiplies the ParallaxLayer's motion. If an axis is set to ``0`` it will not scroll.


Description
-----------

A ParallaxLayer must be the child of a :ref:`ParallaxBackground<class_parallaxbackground>` node. Each ParallaxLayer can be set to move at different speeds relative to the camera movement or the :ref:`ParallaxBackground.scroll_offset<class_ParallaxBackground_scroll_offset>` value.

This node's children will be affected by its scroll offset.

