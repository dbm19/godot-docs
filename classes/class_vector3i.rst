:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Vector3i.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Vector3i:

Vector3i
========

Vector used for 3D math using integer coordinates.

Description
-----------

3-element structure that can be used to represent positions in 3D space or any other pair of numeric values.

It uses integer coordinates and is therefore preferable to :ref:`Vector3<class_Vector3>` when exact precision is required.

\ **Note:** In a boolean context, a Vector3i will evaluate to ``false`` if it's equal to ``Vector3i(0, 0, 0)``. Otherwise, a Vector3i will always evaluate to ``true``.

Tutorials
---------

- :doc:`Math documentation index <../tutorials/math/index>`

- :doc:`Vector math <../tutorials/math/vector_math>`

- `3Blue1Brown Essence of Linear Algebra <https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab>`__

Properties
----------

+-----------------------+-------------------------------------+-------+
| :ref:`int<class_int>` | :ref:`x<class_Vector3i_property_x>` | ``0`` |
+-----------------------+-------------------------------------+-------+
| :ref:`int<class_int>` | :ref:`y<class_Vector3i_property_y>` | ``0`` |
+-----------------------+-------------------------------------+-------+
| :ref:`int<class_int>` | :ref:`z<class_Vector3i_property_z>` | ``0`` |
+-----------------------+-------------------------------------+-------+

Constructors
------------

+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`Vector3i<class_Vector3i_constructor_Vector3i>` **(** **)**                                                                           |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`Vector3i<class_Vector3i_constructor_Vector3i>` **(** :ref:`Vector3i<class_Vector3i>` from **)**                                      |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`Vector3i<class_Vector3i_constructor_Vector3i>` **(** :ref:`Vector3<class_Vector3>` from **)**                                        |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`Vector3i<class_Vector3i_constructor_Vector3i>` **(** :ref:`int<class_int>` x, :ref:`int<class_int>` y, :ref:`int<class_int>` z **)** |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+

Methods
-------

+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`abs<class_Vector3i_method_abs>` **(** **)** |const|                                                                              |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`clamp<class_Vector3i_method_clamp>` **(** :ref:`Vector3i<class_Vector3i>` min, :ref:`Vector3i<class_Vector3i>` max **)** |const| |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`       | :ref:`length<class_Vector3i_method_length>` **(** **)** |const|                                                                        |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`length_squared<class_Vector3i_method_length_squared>` **(** **)** |const|                                                        |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`max_axis_index<class_Vector3i_method_max_axis_index>` **(** **)** |const|                                                        |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`min_axis_index<class_Vector3i_method_min_axis_index>` **(** **)** |const|                                                        |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`sign<class_Vector3i_method_sign>` **(** **)** |const|                                                                            |
+---------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+

Operators
---------

+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator !=<class_Vector3i_operator_neq_bool>` **(** **)**                                          |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator !=<class_Vector3i_operator_neq_bool>` **(** :ref:`Vector3i<class_Vector3i>` right **)**    |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator %<class_Vector3i_operator_mod_Vector3i>` **(** :ref:`Vector3i<class_Vector3i>` right **)** |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator %<class_Vector3i_operator_mod_Vector3i>` **(** :ref:`int<class_int>` right **)**           |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator *<class_Vector3i_operator_mul_Vector3i>` **(** :ref:`Vector3i<class_Vector3i>` right **)** |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`   | :ref:`operator *<class_Vector3i_operator_mul_Vector3>` **(** :ref:`float<class_float>` right **)**        |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator *<class_Vector3i_operator_mul_Vector3i>` **(** :ref:`int<class_int>` right **)**           |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator +<class_Vector3i_operator_sum_Vector3i>` **(** :ref:`Vector3i<class_Vector3i>` right **)** |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator -<class_Vector3i_operator_dif_Vector3i>` **(** :ref:`Vector3i<class_Vector3i>` right **)** |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator /<class_Vector3i_operator_div_Vector3i>` **(** :ref:`Vector3i<class_Vector3i>` right **)** |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`   | :ref:`operator /<class_Vector3i_operator_div_Vector3>` **(** :ref:`float<class_float>` right **)**        |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator /<class_Vector3i_operator_div_Vector3i>` **(** :ref:`int<class_int>` right **)**           |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator <<class_Vector3i_operator_lt_bool>` **(** :ref:`Vector3i<class_Vector3i>` right **)**      |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator <=<class_Vector3i_operator_lte_bool>` **(** :ref:`Vector3i<class_Vector3i>` right **)**    |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator ==<class_Vector3i_operator_eq_bool>` **(** **)**                                           |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator ==<class_Vector3i_operator_eq_bool>` **(** :ref:`Vector3i<class_Vector3i>` right **)**     |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator ><class_Vector3i_operator_gt_bool>` **(** :ref:`Vector3i<class_Vector3i>` right **)**      |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`operator >=<class_Vector3i_operator_gte_bool>` **(** :ref:`Vector3i<class_Vector3i>` right **)**    |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`operator []<class_Vector3i_operator_idx_int>` **(** :ref:`int<class_int>` index **)**               |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator unary+<class_Vector3i_operator_unplus_Vector3i>` **(** **)**                               |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Vector3i<class_Vector3i>` | :ref:`operator unary-<class_Vector3i_operator_unminus_Vector3i>` **(** **)**                              |
+---------------------------------+-----------------------------------------------------------------------------------------------------------+

Constants
---------

.. _class_Vector3i_constant_AXIS_X:

.. _class_Vector3i_constant_AXIS_Y:

.. _class_Vector3i_constant_AXIS_Z:

.. _class_Vector3i_constant_ZERO:

.. _class_Vector3i_constant_ONE:

.. _class_Vector3i_constant_LEFT:

.. _class_Vector3i_constant_RIGHT:

.. _class_Vector3i_constant_UP:

.. _class_Vector3i_constant_DOWN:

.. _class_Vector3i_constant_FORWARD:

.. _class_Vector3i_constant_BACK:

- **AXIS_X** = **0** --- Enumerated value for the X axis. Returned by :ref:`max_axis_index<class_Vector3i_method_max_axis_index>` and :ref:`min_axis_index<class_Vector3i_method_min_axis_index>`.

- **AXIS_Y** = **1** --- Enumerated value for the Y axis. Returned by :ref:`max_axis_index<class_Vector3i_method_max_axis_index>` and :ref:`min_axis_index<class_Vector3i_method_min_axis_index>`.

- **AXIS_Z** = **2** --- Enumerated value for the Z axis. Returned by :ref:`max_axis_index<class_Vector3i_method_max_axis_index>` and :ref:`min_axis_index<class_Vector3i_method_min_axis_index>`.

- **ZERO** = **Vector3i(0, 0, 0)** --- Zero vector, a vector with all components set to ``0``.

- **ONE** = **Vector3i(1, 1, 1)** --- One vector, a vector with all components set to ``1``.

- **LEFT** = **Vector3i(-1, 0, 0)** --- Left unit vector. Represents the local direction of left, and the global direction of west.

- **RIGHT** = **Vector3i(1, 0, 0)** --- Right unit vector. Represents the local direction of right, and the global direction of east.

- **UP** = **Vector3i(0, 1, 0)** --- Up unit vector.

- **DOWN** = **Vector3i(0, -1, 0)** --- Down unit vector.

- **FORWARD** = **Vector3i(0, 0, -1)** --- Forward unit vector. Represents the local direction of forward, and the global direction of north.

- **BACK** = **Vector3i(0, 0, 1)** --- Back unit vector. Represents the local direction of back, and the global direction of south.

Property Descriptions
---------------------

.. _class_Vector3i_property_x:

- :ref:`int<class_int>` **x**

+-----------+-------+
| *Default* | ``0`` |
+-----------+-------+

The vector's X component. Also accessible by using the index position ``[0]``.

----

.. _class_Vector3i_property_y:

- :ref:`int<class_int>` **y**

+-----------+-------+
| *Default* | ``0`` |
+-----------+-------+

The vector's Y component. Also accessible by using the index position ``[1]``.

----

.. _class_Vector3i_property_z:

- :ref:`int<class_int>` **z**

+-----------+-------+
| *Default* | ``0`` |
+-----------+-------+

The vector's Z component. Also accessible by using the index position ``[2]``.

Constructor Descriptions
------------------------

.. _class_Vector3i_constructor_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **Vector3i** **(** **)**

Constructs a default-initialized ``Vector3i`` with all components set to ``0``.

----

- :ref:`Vector3i<class_Vector3i>` **Vector3i** **(** :ref:`Vector3i<class_Vector3i>` from **)**

Constructs a ``Vector3i`` as a copy of the given ``Vector3i``.

----

- :ref:`Vector3i<class_Vector3i>` **Vector3i** **(** :ref:`Vector3<class_Vector3>` from **)**

Constructs a new ``Vector3i`` from :ref:`Vector3<class_Vector3>`. The floating point coordinates will be truncated.

----

- :ref:`Vector3i<class_Vector3i>` **Vector3i** **(** :ref:`int<class_int>` x, :ref:`int<class_int>` y, :ref:`int<class_int>` z **)**

Returns a ``Vector3i`` with the given components.

Method Descriptions
-------------------

.. _class_Vector3i_method_abs:

- :ref:`Vector3i<class_Vector3i>` **abs** **(** **)** |const|

Returns a new vector with all components in absolute values (i.e. positive).

----

.. _class_Vector3i_method_clamp:

- :ref:`Vector3i<class_Vector3i>` **clamp** **(** :ref:`Vector3i<class_Vector3i>` min, :ref:`Vector3i<class_Vector3i>` max **)** |const|

Returns a new vector with all components clamped between the components of ``min`` and ``max``, by running :ref:`@GlobalScope.clamp<class_@GlobalScope_method_clamp>` on each component.

----

.. _class_Vector3i_method_length:

- :ref:`float<class_float>` **length** **(** **)** |const|

Returns the length (magnitude) of this vector.

----

.. _class_Vector3i_method_length_squared:

- :ref:`int<class_int>` **length_squared** **(** **)** |const|

Returns the squared length (squared magnitude) of this vector.

This method runs faster than :ref:`length<class_Vector3i_method_length>`, so prefer it if you need to compare vectors or need the squared distance for some formula.

----

.. _class_Vector3i_method_max_axis_index:

- :ref:`int<class_int>` **max_axis_index** **(** **)** |const|

Returns the axis of the vector's highest value. See ``AXIS_*`` constants. If all components are equal, this method returns :ref:`AXIS_X<class_Vector3i_constant_AXIS_X>`.

----

.. _class_Vector3i_method_min_axis_index:

- :ref:`int<class_int>` **min_axis_index** **(** **)** |const|

Returns the axis of the vector's lowest value. See ``AXIS_*`` constants. If all components are equal, this method returns :ref:`AXIS_Z<class_Vector3i_constant_AXIS_Z>`.

----

.. _class_Vector3i_method_sign:

- :ref:`Vector3i<class_Vector3i>` **sign** **(** **)** |const|

Returns the vector with each component set to one or negative one, depending on the signs of the components.

Operator Descriptions
---------------------

.. _class_Vector3i_operator_neq_bool:

- :ref:`bool<class_bool>` **operator !=** **(** **)**

----

- :ref:`bool<class_bool>` **operator !=** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Returns ``true`` if the vectors are not equal.

----

.. _class_Vector3i_operator_mod_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator %** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Gets the remainder of each component of the ``Vector3i`` with the components of the given ``Vector3i``. This operation uses truncated division, which is often not desired as it does not work well with negative numbers. Consider using :ref:`@GlobalScope.posmod<class_@GlobalScope_method_posmod>` instead if you want to handle negative numbers.

::

    print(Vector3i(10, -20, 30) % Vector3i(7, 8, 9)) # Prints "(3, -4, 3)"

----

- :ref:`Vector3i<class_Vector3i>` **operator %** **(** :ref:`int<class_int>` right **)**

Gets the remainder of each component of the ``Vector3i`` with the the given :ref:`int<class_int>`. This operation uses truncated division, which is often not desired as it does not work well with negative numbers. Consider using :ref:`@GlobalScope.posmod<class_@GlobalScope_method_posmod>` instead if you want to handle negative numbers.

::

    print(Vector2i(10, -20, 30) % 7) # Prints "(3, -6, 2)"

----

.. _class_Vector3i_operator_mul_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator *** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Multiplies each component of the ``Vector3i`` by the components of the given ``Vector3i``.

::

    print(Vector3i(10, 20, 30) * Vector3i(3, 4, 5)) # Prints "(30, 80, 150)"

----

- :ref:`Vector3<class_Vector3>` **operator *** **(** :ref:`float<class_float>` right **)**

Multiplies each component of the ``Vector3i`` by the given :ref:`float<class_float>`. Returns a :ref:`Vector3<class_Vector3>`.

::

    print(Vector3i(10, 15, 20) * 0.9) # Prints "(9, 13.5, 18)"

----

- :ref:`Vector3i<class_Vector3i>` **operator *** **(** :ref:`int<class_int>` right **)**

Multiplies each component of the ``Vector3i`` by the given :ref:`int<class_int>`.

----

.. _class_Vector3i_operator_sum_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator +** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Adds each component of the ``Vector3i`` by the components of the given ``Vector3i``.

::

    print(Vector3i(10, 20, 30) + Vector3i(3, 4, 5)) # Prints "(13, 24, 35)"

----

.. _class_Vector3i_operator_dif_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator -** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Subtracts each component of the ``Vector3i`` by the components of the given ``Vector3i``.

::

    print(Vector3i(10, 20, 30) - Vector3i(3, 4, 5)) # Prints "(7, 16, 25)"

----

.. _class_Vector3i_operator_div_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator /** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Divides each component of the ``Vector3i`` by the components of the given ``Vector3i``.

::

    print(Vector3i(10, 20, 30) / Vector3i(2, 5, 3)) # Prints "(5, 4, 10)"

----

- :ref:`Vector3<class_Vector3>` **operator /** **(** :ref:`float<class_float>` right **)**

Divides each component of the ``Vector3i`` by the given :ref:`float<class_float>`. Returns a :ref:`Vector3<class_Vector3>`.

::

    print(Vector3i(10, 20, 30) / 2.9) # Prints "(5, 10, 15)"

----

- :ref:`Vector3i<class_Vector3i>` **operator /** **(** :ref:`int<class_int>` right **)**

Divides each component of the ``Vector3i`` by the given :ref:`int<class_int>`.

----

.. _class_Vector3i_operator_lt_bool:

- :ref:`bool<class_bool>` **operator <** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Compares two ``Vector3i`` vectors by first checking if the X value of the left vector is less than the X value of the ``right`` vector. If the X values are exactly equal, then it repeats this check with the Y values of the two vectors, and then with the Z values. This operator is useful for sorting vectors.

----

.. _class_Vector3i_operator_lte_bool:

- :ref:`bool<class_bool>` **operator <=** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Compares two ``Vector3i`` vectors by first checking if the X value of the left vector is less than or equal to the X value of the ``right`` vector. If the X values are exactly equal, then it repeats this check with the Y values of the two vectors, and then with the Z values. This operator is useful for sorting vectors.

----

.. _class_Vector3i_operator_eq_bool:

- :ref:`bool<class_bool>` **operator ==** **(** **)**

----

- :ref:`bool<class_bool>` **operator ==** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Returns ``true`` if the vectors are equal.

----

.. _class_Vector3i_operator_gt_bool:

- :ref:`bool<class_bool>` **operator >** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Compares two ``Vector3i`` vectors by first checking if the X value of the left vector is greater than the X value of the ``right`` vector. If the X values are exactly equal, then it repeats this check with the Y values of the two vectors, and then with the Z values. This operator is useful for sorting vectors.

----

.. _class_Vector3i_operator_gte_bool:

- :ref:`bool<class_bool>` **operator >=** **(** :ref:`Vector3i<class_Vector3i>` right **)**

Compares two ``Vector3i`` vectors by first checking if the X value of the left vector is greater than or equal to the X value of the ``right`` vector. If the X values are exactly equal, then it repeats this check with the Y values of the two vectors, and then with the Z values. This operator is useful for sorting vectors.

----

.. _class_Vector3i_operator_idx_int:

- :ref:`int<class_int>` **operator []** **(** :ref:`int<class_int>` index **)**

Access vector components using their index. ``v[0]`` is equivalent to ``v.x``, ``v[1]`` is equivalent to ``v.y``, and ``v[2]`` is equivalent to ``v.z``.

----

.. _class_Vector3i_operator_unplus_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator unary+** **(** **)**

Returns the same value as if the ``+`` was not there. Unary ``+`` does nothing, but sometimes it can make your code more readable.

----

.. _class_Vector3i_operator_unminus_Vector3i:

- :ref:`Vector3i<class_Vector3i>` **operator unary-** **(** **)**

Returns the negative value of the ``Vector3i``. This is the same as writing ``Vector3i(-v.x, -v.y, -v.z)``. This operation flips the direction of the vector while keeping the same magnitude.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
