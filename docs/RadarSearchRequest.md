<h2 id="RadarSearchRequest"> RadarSearchRequest interface </h2><p>
<code><span itemprop="path">google.maps.places</span>.<span itemprop="name">RadarSearchRequest</span></code>
interface
</p><aside class="warning"><p><b>Notice:</b> Radar Search is <strong>deprecated</strong> as of June 30, 2017. This feature will be turned down on June 30, 2018, and will no longer be available after that date.</p></aside><p>A Radar Search request to be sent to the <code>PlacesService</code>.</p><h4>Library</h4><p>places</p><div class="devsite-table-wrapper"><table class="properties responsive" summary="interface RadarSearchRequest - Properties">
<thead>
<tr><th colspan="2">Properties</th>
</tr></thead>
<tbody>
<tr id="RadarSearchRequest.bounds">
<td><code><span>bounds</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLngBounds.md">LatLngBounds</a>|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLngBoundsLiteral.md">LatLngBoundsLiteral</a></code></div>
<div class="desc">Bounds used to bias results when searching for Places (optional). Both <code>location</code> and <code>radius</code> will be ignored if <code>bounds</code> is set. Results will not be restricted to those inside these bounds; but, results inside it will rank higher.</div></td>
</tr>
<tr id="RadarSearchRequest.keyword">
<td><code><span>keyword</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">A term to be matched against all available fields, including but not limited to name, type, and address, as well as customer reviews and other third-party content.</div></td>
</tr>
<tr id="RadarSearchRequest.location">
<td><code><span>location</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLngLiteral.md">LatLngLiteral</a></code></div>
<div class="desc">The center of the area used to bias results when searching for Places.</div></td>
</tr>
<tr id="RadarSearchRequest.name">
<td><code><span>name</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">Restricts results to Places that include this text in the name.</div></td>
</tr>
<tr id="RadarSearchRequest.radius">
<td><code><span>radius</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>number</code></div>
<div class="desc">The radius of the area used to bias results when searching for Places, in meters.</div></td>
</tr>
<tr id="RadarSearchRequest.type">
<td><code><span>type</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">Searches for places of the given type. The type will be translated to the local language of the request's target location and used as query. If a query is also provided, it will be concatenated to the localized type string. Results of a different type will be dropped from the response. Use this to search for language and region independent categorical search. <a href="https://developers.google.com/maps/documentation/places/supported_types">here</a>.</div></td>
</tr>
</tbody>
</table></div>