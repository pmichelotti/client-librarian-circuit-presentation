## Determining Dependencies

To determine the dependencies for a particular Page Resource, the Librarian polls all known `ResourceDependencyProvider` OSGI Service implementations.

The default implementation provided with the Librarian looks to the resources which are descendents of the current page and, given the `sling:resourceType` where defined, looks up the dependencies in the component definition associated with the resource type.

Some use cases for custom Dependency Providers might be: 

* Determining additional dependencies based on Page property values
* Determining additional dependencies based on Design properties established for the current template
