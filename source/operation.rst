Operation
============

Snapping to Vertex
-------------------
While drawing an edgeflow boundary, hold down Ctrl to snap to Vertex.

.. raw:: html

    <video width="70%" controls src="../static/snap_to_exsit_vertex.mp4">
      Your browser does not support the video tag.
    </video>

----



Snapping to Paths
-------------------
While drawing an edgeflow boundary, hold down Ctrl and Shift to snap to paths.

.. raw:: html

    <video width="70%" controls src="../static/snap_to_exsit_path.mp4">
      Your browser does not support the video tag.
    </video>

----


Snapping to Surfaces
--------------------------
Press the S key to toggle if snapping to object surfaces.

.. raw:: html

    <video width="50%" controls src="../static/boundary_snap_to_surface.mp4">
      Your browser does not support the video tag.
    </video>

.. raw:: html

    <video width="50%" controls src="../static/pattern_snap_to_surface.mp4">
      Your browser does not support the video tag.
    </video>

----

Enable Snapping to the Back Face
----------------------------------------------------
Press the V key to toggle if snapping to surfaces opposite the normal direction.

.. raw:: html

    <video width="70%" controls src="../static/snap_to_opposit_face.mp4">
      Your browser does not support the video tag.
    </video>

----

Drawing on Axis of Symmetry
----------------------------------------------------
Press the M key to toggle if drawing on the yz plane. After you draw a edgeflow boundary, this option will auto set to disable, you can press ctrl+M to keep this enable. 

.. raw:: html

    <video width="70%" controls src="../static/draw_on_axis_of_sym.mp4">
      Your browser does not support the video tag.
    </video>

----

Changing Segment number
---------------------------
When you hovering a edgeflow boundary, ctrl+mouse wheel can change the segment.

.. raw:: html

    <video width="70%" controls src="../static/chaning_segment.mp4">
      Your browser does not support the video tag.
    </video>

----

Switching Patterns
---------------------------
When you hovering a Loop, you can press T to changing the pattern constraint to get specific pattern.

Press the B key to toggle whether to skip shapes with no solution. When this option is enabled, shapes without solutions will be automatically skipped when switching.

.. raw:: html

    <video width="70%" controls src="../static/switch_pattern_shape.mp4">
      Your browser does not support the video tag.
    </video>

----

Changing Solver Constraints (Padding and Additional Edge Flow)
---------------------------------------------------------------------------------
When you hovering a Loop, you can press shift+mouse wheel to hange the padding of a boundary.

Use Ctrl + x,y,z to reduce the number of additional edge flows, Shift + x,y,z to increase the number of additional edge flows.

.. raw:: html

    <video width="70%" controls src="../static/changing_pattern_padding.mp4">
      Your browser does not support the video tag.
    </video>

----

Changing Pattern Rotation
-----------------------------
When you hovering a Loop, you can press R to add rotation constraint to solver.

.. raw:: html

    <video width="70%" controls src="../static/changing_pattern_rotation.mp4">
      Your browser does not support the video tag.
    </video>

----

Solver Suggestion
----------------------
When the resolution can not solve with your constraint, there will be a changing segment suggestion to guide you get a feasible solution, this suggestion is guess by solver, and is one fot the solution, not the only one.

.. raw:: html

    <video width="70%" controls src="../static/solver_suggestion.mp4">
      Your browser does not support the video tag.
    </video>

----

Smoothing Mesh
-----------------------------
When you hovering a Loop with a generated mesh, press Shift + 1 2 3 to smooth the mesh with three algorithm.

The last thrid one is smoothing by normal direction. It is useful for patches to a smooth surfaces.

.. raw:: html

    <video width="70%" controls src="../static/smooth_by_face_normal_direction.mp4">
      Your browser does not support the video tag.
    </video>

----

"Snap Selected Vertices to surface" Button
------------------------------------------------------
Click button, then the selected vertices will be snap to the target obj.

----

Available Patch Patterns
---------------------------

This is the patching of the pattern shape. Generally, pattern 0 is the cleanest. Other patterns are compromises because of the number of edges. For the cleanest topological shape, choose pattern 0.

.. raw:: html

    <a href="../static/patterns.png" target="_blank">
        <img src="../static/patterns.png" style="width: 100%;" />
    </a>

----
