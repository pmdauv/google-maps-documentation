<h2 id="DirectionsService"> DirectionsService class </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">DirectionsService</span></code>
class
</p><p>A service for computing directions between two or more places.</p><div class="devsite-table-wrapper"><table class="constructors responsive" summary="class DirectionsService - Constructor">
<thead>
<tr><th colspan="2" id="DirectionsService.constructor">Constructor</th>
</tr></thead>
<tbody>
<tr>
<td><code><span>DirectionsService</span></code></td>
<td><div><code>DirectionsService()</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; None</div>
<div class="desc">Creates a new instance of a <code>DirectionsService</code> that sends directions queries to Google servers.</div></td>
</tr>
</tbody>
</table></div><div class="devsite-table-wrapper"><table class="methods responsive" summary="class DirectionsService - Methods">
<thead>
<tr><th colspan="2">Methods</th>
</tr></thead>
<tbody>
<tr id="DirectionsService.route">
<td><code><span>route</span></code></td>
<td><div><code>route(request, callback)</code></div>
<div class="desc"><strong>Parameters:</strong>&nbsp; <ul>
<li><code>request</code>:&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/DirectionsRequest.md">DirectionsRequest</a></code></li>
<li><code>callback</code>:&nbsp; <code>function(<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/DirectionsResult.md">DirectionsResult</a>, <a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/DirectionsStatus.md">DirectionsStatus</a>)</code></li>
</ul></div>
<div class="desc"><strong>Return Value:</strong>&nbsp; None</div>
<div class="desc">Issue a directions search request.</div></td>
</tr>
</tbody>
</table></div>