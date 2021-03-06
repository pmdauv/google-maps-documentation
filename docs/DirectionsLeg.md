<h2 id="DirectionsLeg"> DirectionsLeg interface </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">DirectionsLeg</span></code>
interface
</p><p>A single leg consisting of a set of steps in a <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/DirectionsResult.md">DirectionsResult</a></code>. Some fields in the leg may not be returned for all requests. Note that though this result is "JSON-like," it is not strictly JSON, as it directly and indirectly includes <code>LatLng</code> objects.</p><div class="devsite-table-wrapper"><table class="properties responsive" summary="interface DirectionsLeg - Properties">
<thead>
<tr><th colspan="2">Properties</th>
</tr></thead>
<tbody>
<tr id="DirectionsLeg.arrival_time">
<td><code><span>arrival_time</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Time.md">Time</a></code></div>
<div class="desc">An estimated arrival time for this leg. Only applicable for TRANSIT requests.</div></td>
</tr>
<tr id="DirectionsLeg.departure_time">
<td><code><span>departure_time</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Time.md">Time</a></code></div>
<div class="desc">An estimated departure time for this leg. Only applicable for TRANSIT requests.</div></td>
</tr>
<tr id="DirectionsLeg.distance">
<td><code><span>distance</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Distance.md">Distance</a></code></div>
<div class="desc">The total distance covered by this leg. This property may be undefined as the distance may be unknown.</div></td>
</tr>
<tr id="DirectionsLeg.duration">
<td><code><span>duration</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Duration.md">Duration</a></code></div>
<div class="desc">The total duration of this leg. This property may be undefined as the duration may be unknown.</div></td>
</tr>
<tr id="DirectionsLeg.duration_in_traffic">
<td><code><span>duration_in_traffic</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/Duration.md">Duration</a></code></div>
<div class="desc">The total duration of this leg, taking into account the traffic conditions indicated by the <code>trafficModel</code> property. This property may be undefined as the duration may be unknown. Only available to Premium Plan customers when <code>drivingOptions</code> is defined when making the request.</div></td>
</tr>
<tr id="DirectionsLeg.end_address">
<td><code><span>end_address</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">The address of the destination of this leg.</div></td>
</tr>
<tr id="DirectionsLeg.end_location">
<td><code><span>end_location</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></div>
<div class="desc">The <code>DirectionsService</code> calculates directions between locations by using the nearest transportation option (usually a road) at the start and end locations. <code>end_location</code> indicates the actual geocoded destination, which may be different than the <code>end_location</code> of the last step if, for example, the road is not near the destination of this leg.</div></td>
</tr>
<tr id="DirectionsLeg.start_address">
<td><code><span>start_address</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">The address of the origin of this leg.</div></td>
</tr>
<tr id="DirectionsLeg.start_location">
<td><code><span>start_location</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></div>
<div class="desc">The <code>DirectionsService</code> calculates directions between locations by using the nearest transportation option (usually a road) at the start and end locations. <code>start_location</code> indicates the actual geocoded origin, which may be different than the <code>start_location</code> of the first step if, for example, the road is not near the origin of this leg.</div></td>
</tr>
<tr id="DirectionsLeg.steps">
<td><code><span>steps</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>Array&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/DirectionsStep.md">DirectionsStep</a>&gt;</code></div>
<div class="desc">An array of <code>DirectionsStep</code>s, each of which contains information about the individual steps in this leg.</div></td>
</tr>
<tr id="DirectionsLeg.via_waypoints">
<td><code><span>via_waypoints</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>Array&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>&gt;</code></div>
<div class="desc">An array of non-stopover waypoints along this leg, which were specified in the original request. <p> <strong>Deprecated in alternative routes</strong>. Version 3.27 will be the last version of the API that adds extra <code>via_waypoints</code> in alternative routes. </p><p> When using the Directions Service to implement draggable directions, it is recommended to disable dragging of alternative routes. Only the main route should be draggable. Users can drag the main route until it matches an alternative route.</p></div></td>
</tr>
</tbody>
</table></div>