## Declaring Component Dependencies on Libraries

Dependencies are declared by specifying a `dependencies` attribute on a Component's defining node (aka, .content.xml file)

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<jcr:root 
	xmlns:cq="http://www.day.com/jcr/cq/1.0"
	xmlns:jcr="http://www.jcp.org/jcr/1.0"
	xmlns:sling="http://sling.apache.org/jcr/sling/1.0"
	jcr:primaryType="cq:Component"
	jcr:title="Carousel" 
	allowedParents="[*/parsys]" 
	sling:resourceSuperType="foundation/components/parbase"
	componentGroup="My App" 
	cq:isContainer="{Boolean}false" 
	dependencies="myapp.components.carousel" />

```