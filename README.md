# MSc-Dissertation-Progress-Report

See main.pdf for the report.

Forward Ray Tracing Algorithm (https://www.educba.com/ray-tracing-algorithm/)
In this technique, the program triggers rays of light that follow from source to the object. Forward ray tracing is capable of determining the color of each object however this technique is inefficient. This is due to the fact that many rays from a light source never come through view plane and into the eye.

Also, tracking down each and every light ray from source to object is just a waste because not all the rays contribute to the visualization of the images. This is the reason why forward racing is also known as light ray tracing or photon tracing.

2. Backward Ray Tracing Algorithm
This method is used to get over the inefficiency of the forwarding ray-tracing method. In this method, an eye ray is created near the eye which passes through the view plane and into space. The first object that eye ray hits are the object which is seen from that point of view plane. Once the light ray is bouncing around, ray tracer figures the exact coloring and shading of this point in the view plane. This is now displayed at the exact corresponding pixel on the computer screen. Hence backward ray tracing is also called as eye-tracking.

The biggest negative of backward tracing corresponds to the fact that it only assumes light rays coming through the view plane and into the eye which gets to the final image. This might not be true in all cases. Say, for instance, an object is held on a table and if the light comes directly from the above and if the object, say a lens receives the light on the focal point where the concentration could be more. In this case, backward tracing would fail as it would not have an idea about the forward rays that could arise through the bending of light at the focal points. Hence backward tracing can strictly be used only when there is an even patch of light that goes through the object.