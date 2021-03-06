<h2 id="spherical"> spherical namespace </h2><p>
<code><span itemprop="path">google.maps.geometry</span>.<span itemprop="name">spherical</span></code>
namespace
</p><p>Utility functions for computing geodesic angles, distances and areas. The default radius is Earth's radius of 6378137 meters.</p><h4>Library</h4><p>geometry</p><div class="devsite-table-wrapper"><table class="methods responsive" summary="namespace spherical - Static Methods">
<thead>
<tr><th colspan="2">Static Methods</th>
</tr></thead>
<tbody>
<tr id="spherical.computeArea">
<td><code><span>computeArea</span></code></td>
<td><div><code>computeArea(path[, radius])</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>path</code>:&nbsp; <code>Array&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/MVCArray.md">MVCArray</a>&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;</code></li>
<li><code>radius</code> (optional):&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the area of a closed path. The computed area uses the same units as the radius. The radius defaults to the Earth's radius in meters, in which case the area is in square meters.</div></td>
</tr>
<tr id="spherical.computeDistanceBetween">
<td><code><span>computeDistanceBetween</span></code></td>
<td><div><code>computeDistanceBetween(from, to[, radius])</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>from</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>to</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>radius</code> (optional):&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the distance, in meters, between two LatLngs. You can optionally specify a custom radius. The radius defaults to the radius of the Earth.</div></td>
</tr>
<tr id="spherical.computeHeading">
<td><code><span>computeHeading</span></code></td>
<td><div><code>computeHeading(from, to)</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>from</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>to</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the heading from one LatLng to another LatLng. Headings are expressed in degrees clockwise from North within the range [-180,180).</div></td>
</tr>
<tr id="spherical.computeLength">
<td><code><span>computeLength</span></code></td>
<td><div><code>computeLength(path[, radius])</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>path</code>:&nbsp; <code>Array&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/MVCArray.md">MVCArray</a>&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;</code></li>
<li><code>radius</code> (optional):&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the length of the given path.</div></td>
</tr>
<tr id="spherical.computeOffset">
<td><code><span>computeOffset</span></code></td>
<td><div><code>computeOffset(from, distance, heading[, radius])</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>from</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>distance</code>:&nbsp; <code>number</code></li>
<li><code>heading</code>:&nbsp; <code>number</code></li>
<li><code>radius</code> (optional):&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></div>
<div class="desc">Returns the LatLng resulting from moving a distance from an origin in the specified heading (expressed in degrees clockwise from north).</div></td>
</tr>
<tr id="spherical.computeOffsetOrigin">
<td><code><span>computeOffsetOrigin</span></code></td>
<td><div><code>computeOffsetOrigin(to, distance, heading[, radius])</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>to</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>distance</code>:&nbsp; <code>number</code></li>
<li><code>heading</code>:&nbsp; <code>number</code></li>
<li><code>radius</code> (optional):&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></div>
<div class="desc">Returns the location of origin when provided with a LatLng destination, meters travelled and original heading. Headings are expressed in degrees clockwise from North. This function returns null when no solution is available.</div></td>
</tr>
<tr id="spherical.computeSignedArea">
<td><code><span>computeSignedArea</span></code></td>
<td><div><code>computeSignedArea(loop[, radius])</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>loop</code>:&nbsp; <code>Array&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/MVCArray.md">MVCArray</a>&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;</code></li>
<li><code>radius</code> (optional):&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the signed area of a closed path. The signed area may be used to determine the orientation of the path. The computed area uses the same units as the radius. The radius defaults to the Earth's radius in meters, in which case the area is in square meters.</div></td>
</tr>
<tr id="spherical.interpolate">
<td><code><span>interpolate</span></code></td>
<td><div><code>interpolate(from, to, fraction)</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>from</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>to</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></li>
<li><code>fraction</code>:&nbsp; <code>number</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></div>
<div class="desc">Returns the LatLng which lies the given fraction of the way between the origin LatLng and the destination LatLng.</div></td>
</tr>
</tbody>
</table></div>