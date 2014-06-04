## Brand Based Filtering

A "Branded" library is a Client Library with an associated `brands` attribute.  Branded Libraries are only included during library composition if one of their brands matches the brand requested.  Unbranded libraries are always included.  In the case where no brand is requested, Branded Libraries will not be included unless one of their brands is the special "default" brand.  

A particular brand is requested by specifying the `brand` attribute of the `cl:pageLibrary` jsp tag.  