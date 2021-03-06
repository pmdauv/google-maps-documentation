<h2 id="StreetViewPanoramaOptions"> StreetViewPanoramaOptions interface </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">StreetViewPanoramaOptions</span></code>
interface
</p><p>Options defining the properties of a <code>StreetViewPanorama</code> object.</p><div class="devsite-table-wrapper"><table class="properties responsive" summary="interface StreetViewPanoramaOptions - Properties">
<thead>
<tr><th colspan="2">Properties</th>
</tr></thead>
<tbody>
<tr id="StreetViewPanoramaOptions.addressControl">
<td><code><span>addressControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the address control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.addressControlOptions">
<td><code><span>addressControlOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/StreetViewAddressControlOptions.md">StreetViewAddressControlOptions</a></code></div>
<div class="desc">The display options for the address control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.clickToGo">
<td><code><span>clickToGo</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of click-to-go.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.disableDefaultUI">
<td><code><span>disableDefaultUI</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">Enables/disables all default UI. May be overridden individually.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.disableDoubleClickZoom">
<td><code><span>disableDoubleClickZoom</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">Enables/disables zoom on double click. Disabled by default.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.enableCloseButton">
<td><code><span>enableCloseButton</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">If <code>true</code>, the close button is displayed. Disabled by default.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.fullscreenControl">
<td><code><span>fullscreenControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the fullscreen control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.fullscreenControlOptions">
<td><code><span>fullscreenControlOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/FullscreenControlOptions.md">FullscreenControlOptions</a></code></div>
<div class="desc">The display options for the fullscreen control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.imageDateControl">
<td><code><span>imageDateControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the imagery acquisition date control. Disabled by default.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.linksControl">
<td><code><span>linksControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the links control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.motionTracking">
<td><code><span>motionTracking</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">Whether motion tracking is on or off. Enabled by default when the motion tracking control is present, so that the POV (point of view) follows the orientation of the device. This is primarily applicable to mobile devices. If <code>motionTracking</code> is set to false while <code>motionTrackingControl</code> is enabled, the motion tracking control appears but tracking is off. The user can tap the motion tracking control to toggle this option.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.motionTrackingControl">
<td><code><span>motionTrackingControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the motion tracking control. Enabled by default when the device has motion data, so that the control appears on the map. This is primarily applicable to mobile devices.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.motionTrackingControlOptions">
<td><code><span>motionTrackingControlOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/MotionTrackingControlOptions.md">MotionTrackingControlOptions</a></code></div>
<div class="desc">The display options for the motion tracking control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.panControl">
<td><code><span>panControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the pan control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.panControlOptions">
<td><code><span>panControlOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/PanControlOptions.md">PanControlOptions</a></code></div>
<div class="desc">The display options for the pan control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.pano">
<td><code><span>pano</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">The panorama ID, which should be set when specifying a custom panorama.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.position">
<td><code><span>position</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a>|<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLngLiteral.md">LatLngLiteral</a></code></div>
<div class="desc">The <code>LatLng</code> position of the Street View panorama.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.pov">
<td><code><span>pov</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/StreetViewPov.md">StreetViewPov</a></code></div>
<div class="desc">The camera orientation, specified as heading and pitch, for the panorama.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.scrollwheel">
<td><code><span>scrollwheel</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">If false, disables scrollwheel zooming in Street View. The scrollwheel is enabled by default.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.showRoadLabels">
<td><code><span>showRoadLabels</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The display of street names on the panorama. If this value is not specified, or is set to <code>true</code>, street names are displayed on the panorama. If set to <code>false</code>, street names are not displayed.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.visible">
<td><code><span>visible</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">If <code>true</code>, the Street View panorama is visible on load.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.zoom">
<td><code><span>zoom</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>number</code></div>
<div class="desc">The zoom of the panorama, specified as a number. A zoom of 0 gives a 180 degrees Field of View.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.zoomControl">
<td><code><span>zoomControl</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">The enabled/disabled state of the zoom control.</div></td>
</tr>
<tr id="StreetViewPanoramaOptions.zoomControlOptions">
<td><code><span>zoomControlOptions</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/ZoomControlOptions.md">ZoomControlOptions</a></code></div>
<div class="desc">The display options for the zoom control.</div></td>
</tr>
</tbody>
</table></div>