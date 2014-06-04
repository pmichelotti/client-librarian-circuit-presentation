<h2>Template Level Dependencies</h2>

<p>Since pages exist as pseudo-glorified components, library dependencies can be added to the .content.xml of the page components themselves.</p>

<aside class="notes">
    As it stands, the common library is not included unless the Product component is included.  Further the library defined for the Navigation is not included, because this component is &quot;baked in&quot; to the template. 

    Common dependencies can be added as dependencies of the template component itself
</aside>