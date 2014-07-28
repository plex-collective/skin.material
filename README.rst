.. -*- coding: utf-8 -*-

skin.material
=============

Material Skin for Plex Home Theater

This is the development branch of the Material Skin for Plex Home Theater.

Not for everyday use since things may break!

Coding Style Used
-----------------

- Includes
    Include names should be CamelCase

    ``IncludeName``


- Property
    Property variables should begin with an underscore and be all lowercase

    ``_property_name``

- Skin Setting
    Skin setting names should be all uppercase

    ``SKIN_SETTING``

- Variables
    Variable names should be lowercase

    ``variable_name``

- Controls Style
    List tags in order of, description, visibility, positioning, design elements, labels, actions, and then animation

    .. code-block:: xml

        <!-- description -->
        <description>Skin</description>

        <!-- visibility -->
        <visible>false</visible>

        <!-- positioning -->
        <posx>59</posx>
        <posy>165</posy>
        <width>111</width>
        <height>27</height>
        <align>center</align>
        <aligny>center</aligny>

        <!-- design elements -->
        <font>homelabel</font>
        <shadowcolor>Black</shadowcolor>

        <!-- info labels -->
        <label>$VAR[listitem_poster_title_2]</label>

        <!-- actions -->
        <onup>noop</onup>
        <scroll>true</scroll>

        <!-- animation -->
        <animation effect="fade" delay="300" time="200">Visible</animation>

