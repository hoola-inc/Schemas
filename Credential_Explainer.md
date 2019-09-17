# Organization Example
Classes and Properties

| Class	       	| Certificate	|LearningOpportunityProfile  	| CredentialAlignmentObject	|
| ------------- |---------------|----- 				| -----				|
|Properties	|ceterms:name	|name           		| frameworkName               	|
|		|subjectWebpage |creditUnitValue		| targetNodeName		|		
|		|requires       |description    		| targetNode			|
|		|creditUnitValue|deliveryType   		| targetNodeDescription		| 
|		|occupationType |subjectWebpage 		|				|
|		|ctid		|				|				|



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
      "@id": "res:61183b59-0669-457b-881a-a2b3bedcafdc",
      "@type": "ceterms:Certificate",
      "ceterms:creditUnitValue": "43.5",
      "ceterms:ctid": "urn:ctid:61183b59-0669-457b-881a-a2b3bedcafdc",
      "ceterms:name": {
        "@language": "en-US",
        "@value": "Dental Assisting Certificate"
      },
      "ceterms:occupationType": {
        "@id": "_:ub22bL13C28"
      },
      "ceterms:requires": {
        "@id": "res:642806c0-e0e2-4805-a95e-47627d5b4b9d"
      },
      "ceterms:subjectWebpage": {
        "@id": "https://portal.santarosa.edu/SRWeb/SR_ProgramOfStudy.aspx?ProgramType=1&Program=003176&Version=4"
      }
    },
    {
      "@id": "_:ub22bL13C28",
      "@type": "ceterms:CredentialAlignmentObject",
      "ceterms:frameworkName": {
        "@language": "en-US",
        "@value": "O*Net - Occupations"
      },
      "ceterms:targetNode": {
        "@id": "http://exampleONet.org/occupation/31-9091.00"
      },
      "ceterms:targetNodeDescription": {
        "@language": "en-US",
        "@value": "Assist dentist, set up equipment, prepare patient for treatment, and keep records."
      },
      "ceterms:targetNodeName": {
        "@language": "en-US",
        "@value": "Dental Assistants"
      }
    },
    {
      "@id": "res:642806c0-e0e2-4805-a95e-47627d5b4b9d",
      "@type": "ceterms:LearningOpportunityProfile",
      "ceterms:creditUnitValue": "3.0",
      "ceterms:deliveryType": {
        "@id": "http://purl.org/ctdl/vocabs/deliveryType/InPerson"
      },
      "ceterms:description": {
        "@language": "en-US",
        "@value": "Dental terminology, basic anatomy of the oral cavity, dental anatomy …"
      },
      "ceterms:name": {
        "@language": "en-US",
        "@value": "Applied Dental Science"
      },
      "ceterms:subjectWebpage": {
        "@id": "https://portal.santarosa.edu/SRWeb/SR_CourseOutlines.aspx?ck=DA60"
      }
    }
  ]
}
```
