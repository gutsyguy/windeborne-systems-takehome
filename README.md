Gauge Dial Project
This project is a simple implementation of a gauge dial using HTML and CSS. The gauge features a circular design with a gradient, a white background, and a marker indicating a current reading. The design is responsive and uses modern CSS techniques for styling.

Features
Circular Gauge: The gauge spans approximately 250 degrees with a gradient that follows the circle.

White Background: The inner part of the gauge has a white background.

Current Reading Marker: A marker is hardcoded to indicate a specific reading (e.g., 80% of the way along the gauge).

Responsive Design: The gauge is designed to be responsive, using viewport units (vmin) for sizing.

Code Structure
HTML
The HTML structure consists of a container for the gauge, which includes:

A div for the gauge background.

A div for the gauge dial, which contains the gradient and the marker.

A div for displaying the current reading.

Two div elements for displaying additional numbers below the gauge.

CSS
The CSS styles define the appearance and layout of the gauge:

Gradient: A conic-gradient is used to create the circular gradient effect.

Marker: A pseudo-element (::after) is used to create the marker.

Responsive Units: Viewport units (vmin, vw) are used to ensure the gauge scales with the viewport size.

