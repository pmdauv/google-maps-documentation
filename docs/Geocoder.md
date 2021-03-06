<h2 id="Geocoder"> Geocoder class </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">Geocoder</span></code>
class
</p><p>A service for converting between an address and a <code>LatLng</code>.</p><div class="devsite-table-wrapper"><table class="constructors responsive" summary="class Geocoder - Constructor">
<thead>
<tr><th colspan="2" id="Geocoder.constructor">Constructor</th>
</tr></thead>
<tbody>
<tr>
<td><code><span>Geocoder</span></code></td>
<td><div><code>Geocoder()</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; None</div>
<div class="desc">Creates a new instance of a <code>Geocoder</code> that sends geocode requests to Google servers.</div></td>
</tr>
</tbody>
</table></div><div class="devsite-table-wrapper"><table class="methods responsive" summary="class Geocoder - Methods">
<thead>
<tr><th colspan="2">Methods</th>
</tr></thead>
<tbody>
<tr id="Geocoder.geocode">
<td><code><span>geocode</span></code></td>
<td><div><code>geocode(request, callback)</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>request</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/GeocoderRequest.md">GeocoderRequest</a></code></li>
<li><code>callback</code>:&nbsp; <code>function(Array&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/GeocoderResult.md">GeocoderResult</a>&gt;, <a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/GeocoderStatus.md">GeocoderStatus</a>)</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; None</div>
<div class="desc">Geocode a request.</div></td>
</tr>
</tbody>
</table></div>