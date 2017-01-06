# Description
This is a repository of Swagger documents representing the HL7 FHIR REST API Implementation.  Provided is a swagger document that represents the HL7 FHIR REST API Implementation that gives you access to all the FHIR resources.  Also provided is a Swagger Document for key individual resources to make the experiences of the non-techie FHIR API consumers better.

## API Management Version Compatibilty
This artefact was successfully tested for the following versions:
- v7.5.2


## Install


## Usage

### Import
Import Swagger documents into Axway API Management

### Test FHIR Servers
We are currently leveraging the HL7 Health Intersections FHIR server for testing.
* http://fhir3.healthintersections.com.au/open

You may use any FHIR server endpoint you wish. List of publicly available test FHIR server:

* http://wiki.hl7.org/index.php?title=Publicly_Available_FHIR_Servers_for_testing

### Change FHIR Server Endpoint
To change the FHIR server endpoint.  Open the Swagger file and change the "host" field as shown below.
```
{
    "swagger": "2.0",
    "host": "fhir3.healthintersections.com.au/open",
    "basePath": "/",
    "schemes": [
        "http"
    ],
    ....
```


## Bug and Caveats

```
The Swagger documents in this repository do not fully document the FHIR REST API specification.  
The Swagger documents only cover the more common scenarios.  You may need to elaborate on the 
swagger documents if functionality or descriptive text is missing.   
See Contributing below for how to contribute back. 
```

## Contributing

Please read [Contributing.md] (https://github.com/Axway-API-Management/Common/blob/master/Contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.


## Team

![alt text][Axwaylogo] Axway Team

[Axwaylogo]: https://github.com/Axway-API-Management/Common/blob/master/img/AxwayLogoSmall.png  "Axway logo"


## License
Apache License 2.0 (refer to document [license] (/LICENSE))
