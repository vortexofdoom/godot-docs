.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PhysicsDirectBodyState.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PhysicsDirectBodyState:

PhysicsDirectBodyState
======================

**Inherits:** :ref:`Object<class_Object>`

**Inherited By:** :ref:`BulletPhysicsDirectBodyState<class_BulletPhysicsDirectBodyState>`

**Category:** Core

Brief Description
-----------------

Direct access object to a physics body in the :ref:`PhysicsServer<class_PhysicsServer>`.

Properties
----------

+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`angular_velocity<class_PhysicsDirectBodyState_property_angular_velocity>`             |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`center_of_mass<class_PhysicsDirectBodyState_property_center_of_mass>`                 |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`inverse_inertia<class_PhysicsDirectBodyState_property_inverse_inertia>`               |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`         | :ref:`inverse_mass<class_PhysicsDirectBodyState_property_inverse_mass>`                     |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`linear_velocity<class_PhysicsDirectBodyState_property_linear_velocity>`               |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Basis<class_Basis>`         | :ref:`principal_inertia_axes<class_PhysicsDirectBodyState_property_principal_inertia_axes>` |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`           | :ref:`sleeping<class_PhysicsDirectBodyState_property_sleeping>`                             |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`         | :ref:`step<class_PhysicsDirectBodyState_property_step>`                                     |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`         | :ref:`total_angular_damp<class_PhysicsDirectBodyState_property_total_angular_damp>`         |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`total_gravity<class_PhysicsDirectBodyState_property_total_gravity>`                   |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`         | :ref:`total_linear_damp<class_PhysicsDirectBodyState_property_total_linear_damp>`           |
+-----------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`transform<class_PhysicsDirectBodyState_property_transform>`                           |
+-----------------------------------+---------------------------------------------------------------------------------------------+

Methods
-------

+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`add_central_force<class_PhysicsDirectBodyState_method_add_central_force>` **(** :ref:`Vector3<class_Vector3>` force **)**                                                     |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`add_force<class_PhysicsDirectBodyState_method_add_force>` **(** :ref:`Vector3<class_Vector3>` force, :ref:`Vector3<class_Vector3>` position **)**                             |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`add_torque<class_PhysicsDirectBodyState_method_add_torque>` **(** :ref:`Vector3<class_Vector3>` torque **)**                                                                  |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`apply_central_impulse<class_PhysicsDirectBodyState_method_apply_central_impulse>` **(** :ref:`Vector3<class_Vector3>` j **)**                                                 |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`apply_impulse<class_PhysicsDirectBodyState_method_apply_impulse>` **(** :ref:`Vector3<class_Vector3>` position, :ref:`Vector3<class_Vector3>` j **)**                         |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`apply_torque_impulse<class_PhysicsDirectBodyState_method_apply_torque_impulse>` **(** :ref:`Vector3<class_Vector3>` j **)**                                                   |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`RID<class_RID>`                                         | :ref:`get_contact_collider<class_PhysicsDirectBodyState_method_get_contact_collider>` **(** :ref:`int<class_int>` contact_idx **)** const                                           |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                                         | :ref:`get_contact_collider_id<class_PhysicsDirectBodyState_method_get_contact_collider_id>` **(** :ref:`int<class_int>` contact_idx **)** const                                     |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`                                   | :ref:`get_contact_collider_object<class_PhysicsDirectBodyState_method_get_contact_collider_object>` **(** :ref:`int<class_int>` contact_idx **)** const                             |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                                 | :ref:`get_contact_collider_position<class_PhysicsDirectBodyState_method_get_contact_collider_position>` **(** :ref:`int<class_int>` contact_idx **)** const                         |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                                         | :ref:`get_contact_collider_shape<class_PhysicsDirectBodyState_method_get_contact_collider_shape>` **(** :ref:`int<class_int>` contact_idx **)** const                               |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                                 | :ref:`get_contact_collider_velocity_at_position<class_PhysicsDirectBodyState_method_get_contact_collider_velocity_at_position>` **(** :ref:`int<class_int>` contact_idx **)** const |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                                         | :ref:`get_contact_count<class_PhysicsDirectBodyState_method_get_contact_count>` **(** **)** const                                                                                   |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                                     | :ref:`get_contact_impulse<class_PhysicsDirectBodyState_method_get_contact_impulse>` **(** :ref:`int<class_int>` contact_idx **)** const                                             |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                                 | :ref:`get_contact_local_normal<class_PhysicsDirectBodyState_method_get_contact_local_normal>` **(** :ref:`int<class_int>` contact_idx **)** const                                   |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                                 | :ref:`get_contact_local_position<class_PhysicsDirectBodyState_method_get_contact_local_position>` **(** :ref:`int<class_int>` contact_idx **)** const                               |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                                         | :ref:`get_contact_local_shape<class_PhysicsDirectBodyState_method_get_contact_local_shape>` **(** :ref:`int<class_int>` contact_idx **)** const                                     |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PhysicsDirectSpaceState<class_PhysicsDirectSpaceState>` | :ref:`get_space_state<class_PhysicsDirectBodyState_method_get_space_state>` **(** **)**                                                                                             |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                          | :ref:`integrate_forces<class_PhysicsDirectBodyState_method_integrate_forces>` **(** **)**                                                                                           |
+---------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Description
-----------

Provides direct access to a physics body in the :ref:`PhysicsServer<class_PhysicsServer>`, allowing safe changes to physics properties. This object is passed via the direct state callback of rigid/character bodies, and is intended for changing the direct state of that body. See :ref:`RigidBody._integrate_forces<class_RigidBody_method__integrate_forces>`.

Property Descriptions
---------------------

.. _class_PhysicsDirectBodyState_property_angular_velocity:

- :ref:`Vector3<class_Vector3>` **angular_velocity**

+----------+-----------------------------+
| *Setter* | set_angular_velocity(value) |
+----------+-----------------------------+
| *Getter* | get_angular_velocity()      |
+----------+-----------------------------+

The body's rotational velocity.

.. _class_PhysicsDirectBodyState_property_center_of_mass:

- :ref:`Vector3<class_Vector3>` **center_of_mass**

+----------+----------------------+
| *Getter* | get_center_of_mass() |
+----------+----------------------+

.. _class_PhysicsDirectBodyState_property_inverse_inertia:

- :ref:`Vector3<class_Vector3>` **inverse_inertia**

+----------+-----------------------+
| *Getter* | get_inverse_inertia() |
+----------+-----------------------+

The inverse of the inertia of the body.

.. _class_PhysicsDirectBodyState_property_inverse_mass:

- :ref:`float<class_float>` **inverse_mass**

+----------+--------------------+
| *Getter* | get_inverse_mass() |
+----------+--------------------+

The inverse of the mass of the body.

.. _class_PhysicsDirectBodyState_property_linear_velocity:

- :ref:`Vector3<class_Vector3>` **linear_velocity**

+----------+----------------------------+
| *Setter* | set_linear_velocity(value) |
+----------+----------------------------+
| *Getter* | get_linear_velocity()      |
+----------+----------------------------+

The body's linear velocity.

.. _class_PhysicsDirectBodyState_property_principal_inertia_axes:

- :ref:`Basis<class_Basis>` **principal_inertia_axes**

+----------+------------------------------+
| *Getter* | get_principal_inertia_axes() |
+----------+------------------------------+

.. _class_PhysicsDirectBodyState_property_sleeping:

- :ref:`bool<class_bool>` **sleeping**

+----------+------------------------+
| *Setter* | set_sleep_state(value) |
+----------+------------------------+
| *Getter* | is_sleeping()          |
+----------+------------------------+

If ``true``, this body is currently sleeping (not active).

.. _class_PhysicsDirectBodyState_property_step:

- :ref:`float<class_float>` **step**

+----------+------------+
| *Getter* | get_step() |
+----------+------------+

The timestep (delta) used for the simulation.

.. _class_PhysicsDirectBodyState_property_total_angular_damp:

- :ref:`float<class_float>` **total_angular_damp**

+----------+--------------------------+
| *Getter* | get_total_angular_damp() |
+----------+--------------------------+

The rate at which the body stops rotating, if there are not any other forces moving it.

.. _class_PhysicsDirectBodyState_property_total_gravity:

- :ref:`Vector3<class_Vector3>` **total_gravity**

+----------+---------------------+
| *Getter* | get_total_gravity() |
+----------+---------------------+

The total gravity vector being currently applied to this body.

.. _class_PhysicsDirectBodyState_property_total_linear_damp:

- :ref:`float<class_float>` **total_linear_damp**

+----------+-------------------------+
| *Getter* | get_total_linear_damp() |
+----------+-------------------------+

The rate at which the body stops moving, if there are not any other forces moving it.

.. _class_PhysicsDirectBodyState_property_transform:

- :ref:`Transform<class_Transform>` **transform**

+----------+----------------------+
| *Setter* | set_transform(value) |
+----------+----------------------+
| *Getter* | get_transform()      |
+----------+----------------------+

The body's transformation matrix.

Method Descriptions
-------------------

.. _class_PhysicsDirectBodyState_method_add_central_force:

- void **add_central_force** **(** :ref:`Vector3<class_Vector3>` force **)**

Adds a constant directional force without affecting rotation.

This is equivalent to ``add_force(force, Vector3(0,0,0))``.

.. _class_PhysicsDirectBodyState_method_add_force:

- void **add_force** **(** :ref:`Vector3<class_Vector3>` force, :ref:`Vector3<class_Vector3>` position **)**

Adds a positioned force to the body. Both the force and the offset from the body origin are in global coordinates.

.. _class_PhysicsDirectBodyState_method_add_torque:

- void **add_torque** **(** :ref:`Vector3<class_Vector3>` torque **)**

Adds a constant rotational force without affecting position.

.. _class_PhysicsDirectBodyState_method_apply_central_impulse:

- void **apply_central_impulse** **(** :ref:`Vector3<class_Vector3>` j **)**

Applies a single directional impulse without affecting rotation.

This is equivalent to ``apply_impulse(Vector3(0, 0, 0), impulse)``.

.. _class_PhysicsDirectBodyState_method_apply_impulse:

- void **apply_impulse** **(** :ref:`Vector3<class_Vector3>` position, :ref:`Vector3<class_Vector3>` j **)**

Applies a positioned impulse to the body. An impulse is time-independent! Applying an impulse every frame would result in a framerate-dependent force. For this reason it should only be used when simulating one-time impacts. The position uses the rotation of the global coordinate system, but is centered at the object's origin.

.. _class_PhysicsDirectBodyState_method_apply_torque_impulse:

- void **apply_torque_impulse** **(** :ref:`Vector3<class_Vector3>` j **)**

Apply a torque impulse (which will be affected by the body mass and shape). This will rotate the body around the vector ``j`` passed as parameter.

.. _class_PhysicsDirectBodyState_method_get_contact_collider:

- :ref:`RID<class_RID>` **get_contact_collider** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the collider's :ref:`RID<class_RID>`.

.. _class_PhysicsDirectBodyState_method_get_contact_collider_id:

- :ref:`int<class_int>` **get_contact_collider_id** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the collider's object id.

.. _class_PhysicsDirectBodyState_method_get_contact_collider_object:

- :ref:`Object<class_Object>` **get_contact_collider_object** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the collider object.

.. _class_PhysicsDirectBodyState_method_get_contact_collider_position:

- :ref:`Vector3<class_Vector3>` **get_contact_collider_position** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the contact position in the collider.

.. _class_PhysicsDirectBodyState_method_get_contact_collider_shape:

- :ref:`int<class_int>` **get_contact_collider_shape** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the collider's shape index.

.. _class_PhysicsDirectBodyState_method_get_contact_collider_velocity_at_position:

- :ref:`Vector3<class_Vector3>` **get_contact_collider_velocity_at_position** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the linear velocity vector at the collider's contact point.

.. _class_PhysicsDirectBodyState_method_get_contact_count:

- :ref:`int<class_int>` **get_contact_count** **(** **)** const

Returns the number of contacts this body has with other bodies.

**Note:** By default, this returns 0 unless bodies are configured to monitor contacts. See :ref:`RigidBody.contact_monitor<class_RigidBody_property_contact_monitor>`.

.. _class_PhysicsDirectBodyState_method_get_contact_impulse:

- :ref:`float<class_float>` **get_contact_impulse** **(** :ref:`int<class_int>` contact_idx **)** const

Impulse created by the contact. Only implemented for Bullet physics.

.. _class_PhysicsDirectBodyState_method_get_contact_local_normal:

- :ref:`Vector3<class_Vector3>` **get_contact_local_normal** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the local normal at the contact point.

.. _class_PhysicsDirectBodyState_method_get_contact_local_position:

- :ref:`Vector3<class_Vector3>` **get_contact_local_position** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the local position of the contact point.

.. _class_PhysicsDirectBodyState_method_get_contact_local_shape:

- :ref:`int<class_int>` **get_contact_local_shape** **(** :ref:`int<class_int>` contact_idx **)** const

Returns the local shape index of the collision.

.. _class_PhysicsDirectBodyState_method_get_space_state:

- :ref:`PhysicsDirectSpaceState<class_PhysicsDirectSpaceState>` **get_space_state** **(** **)**

Returns the current state of the space, useful for queries.

.. _class_PhysicsDirectBodyState_method_integrate_forces:

- void **integrate_forces** **(** **)**

Calls the built-in force integration code.

