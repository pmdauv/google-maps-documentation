<h2 id="DistanceMatrixRequest"> DistanceMatrixRequest interface </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">DistanceMatrixRequest</span></code>
interface
</p><p>A distance matrix query sent by the <code>DistanceMatrixService</code> containing arrays of origin and destination locations, and various options for computing metrics.</p><div class="devsite-table-wrapper"><table class="properties responsive" summary="interface DistanceMatrixRequest - Properties">
<thead>
<tr><th colspan="2">Properties</th>
</tr></thead>
<tbody>
<tr id="DistanceMatrixRequest.avoidFerries">
<td><code><span>avoidFerries</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">If true, instructs the Distance Matrix service to avoid ferries where possible. Optional.</div></td>
</tr>
<tr id="DistanceMatrixRequest.avoidHighways">
<td><code><span>avoidHighways</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">If true, instructs the Distance Matrix service to avoid highways where possible. Optional.</div></td>
</tr>
<tr id="DistanceMatrixRequest.avoidTolls">
<td><code><span>avoidTolls</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">If true, instructs the Distance Matrix service to avoid toll roads where possible. Optional.</div></td>
</tr>
<tr id="DistanceMatrixRequest.destinations">
<td><code><span>destinations</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>Array&lt;string|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Place.md">Place</a>&gt;</code></div>
<div class="desc">An array containing destination address strings, or <code>LatLng</code>, or <code>Place</code> objects, to which to calculate distance and time. Required.</div></td>
</tr>
<tr id="DistanceMatrixRequest.drivingOptions">
<td><code><span>drivingOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/DrivingOptions.md">DrivingOptions</a></code></div>
<div class="desc">Settings that apply only to requests where <code>travelMode</code> is <code>DRIVING</code>. This object will have no effect for other travel modes.</div></td>
</tr>
<tr id="DistanceMatrixRequest.origins">
<td><code><span>origins</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>Array&lt;string|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Place.md">Place</a>&gt;</code></div>
<div class="desc">An array containing origin address strings, or <code>LatLng</code>, or <code>Place</code> objects, from which to calculate distance and time. Required.</div></td>
</tr>
<tr id="DistanceMatrixRequest.region">
<td><code><span>region</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">Region code used as a bias for geocoding requests. Optional.</div></td>
</tr>
<tr id="DistanceMatrixRequest.transitOptions">
<td><code><span>transitOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/TransitOptions.md">TransitOptions</a></code></div>
<div class="desc">Settings that apply only to requests where <code>travelMode</code> is TRANSIT. This object will have no effect for other travel modes.</div></td>
</tr>
<tr id="DistanceMatrixRequest.travelMode">
<td><code><span>travelMode</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/TravelMode.md">TravelMode</a></code></div>
<div class="desc">Type of routing requested. Required.</div></td>
</tr>
<tr id="DistanceMatrixRequest.unitSystem">
<td><code><span>unitSystem</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/UnitSystem.md">UnitSystem</a></code></div>
<div class="desc">Preferred unit system to use when displaying distance. Optional; defaults to metric.</div></td>
</tr>
</tbody>
</table></div>