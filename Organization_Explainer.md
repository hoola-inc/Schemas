# Organization Example
Classes and Properties

| Class	       	| CredentialOrganizatio		| Status  	| Place  	|
| ------------- |--------------------- 		| -----		| -----		|
|Properties	|ceterms:name		       	|Required	|streetAddress	|
|    		|ceterms:subjectWebpage	       	|Required	|addressLocality|	
|    		|ceterms:address       	       	|Required	|addressRegion	|	
|    		|ceterms:offers	       	       	|Required	|addressCountry	|	
|		|ceterms:agentSectorType       	|Required	|postalCode	|
|		|ceterms:agentType	       	|Required	|		|
|		|ceterms:DID		       	|Required	|		|
|		|ceterms:email		       	|Required	|		|
|		|ceterms:telephone	       	|Required	|		|
|		|ceterms:foundingDate	       	|Recommended	|		|
|		|ceterms:image		       	|Recommended	|		|
|		|ceterms:foundingDate		|Recommended	|		|	
|		|ceterms:image			|Recommended	|		|	
|		|ceterms:jurisdiction		|Recommended	|		|	
|		|ceterms:keyword		|Recommended	|		|	
|		|ceterms:maintenanceProcess	|Recommended	|		|	
|		|ceterms:parentOrganization	|Recommended	|		|	
|		|ceterms:serviceType		|Recommended	|		|	
|		|ceterms:socialMedia		|Recommended	|		|	
|		|ceterms:accreditedBy		|Recommended	|		|	
|		|ceterms:approvedBy		|Recommended	|		|	
|		|ceterms:regulatedBy		|Recommended	|		|	
|		|ceterms:agentPurpose		|Recommended	|		|	
|		|ceterms:agentPurposeDescription|Recommended	|		|	



```
{
  "@context": {
    "ceterms": "http://purl.org/ctdl/terms/",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "res": "http://example.org/resources/",
    "xsd": "http://www.w3.org/2001/XMLSchema#"
  },
  "@graph": [
    {
      "@id": "res:79d498f4-224e-4778-9ba7-febd5c038374",
      "@type": "ceterms:CredentialOrganization",
      "ceterms:name": {
        "@language": "en-US",
        "@value": "Santa Rosa Junior College"
      },
      "ceterms:address": {
        "@id": "_:2a1fadd8-0f6b-4b3f-9758-622cb55d489f"
      },      
      "ceterms:subjectWebpage": {
        "@id": "http://www.santarosa.edu/"
      },
      "ceterms:offers": {
        "@id": "res:2df7b15e-f975-433c-b1ba-5357ff9a5957"
      }      
    },
    {
      "@id": "_:2a1fadd8-0f6b-4b3f-9758-622cb55d489f",
      "@type": "ceterms:PostalAddress",
      "ceterms:addressCountry": "US",
      "ceterms:addressRegion": "CA",
      "ceterms:addresssLocality": "Santa Rosa",
      "ceterms:postalCode": "95401-4395",
      "ceterms:streetAdddess": "1501 Mendocino Ave."
    }
  ]
}
```
