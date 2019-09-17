# Credentials Explainer
Classes and Properties


## Course (Meta)
| Class	       	| Course		|
| ------------- |---------------	|
|Properties	|ceterms:name		|
|		|creditUnitType 	|		
|		|creditUniteValue	|		
|		|ctid		 	|		
|		|subjectWebpage 	|		
|		|prerequisite      	|
|		|uri/https		|
|		|hasChild		|

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
      "@type": "ceterms:Course",
      "creditUnitType": "http://purl.org/ctdl/vocabs/creditUnit/DegreeCredit",
      "ceterms:creditUnitValue": "43.5",
      "ceterms:ctid": "urn:ctid:61183b59-0669-457b-881a-a2b3bedcafdc",
      "ceterms:prerequisite": "res:642806c0-e0e2-4805-a95e-47627d5b4b9d"
      "ceasn:hasChild": "uniqueIdentifier:1231239342423",
      "ceterms:name": {
        "@language": "en-US",
        "@value": "Dental Assisting 101"
      },

      "ceterms:subjectWebpage": {
        "@id": "https://portal.santarosa.edu/SRWeb/SR_ProgramOfStudy.aspx?ProgramType=1&Program=003176&Version=4"
      }
    }
  ]
}
```

## Course (Instance)

| Class	       	| Course		|
| ------------- |---------------	|
|Properties	|ceterms:name		|
|		|creditUnitType 	|		
|		|creditUniteValue	|		
|		|courseCode	 	|		
|		|programTerm	 	|		
|		|startDate	 	|		
|		|endDate	 	|		
|		|isChildOf	 	|		
|		|prerequisite      	|

```
    {
       "@type": "schema:CourseInstance",
       "@id": "uniqueIdentifier:1231239342423",
       "name": "Programming Concepts and Methodology II",
       "creditUnitType": "http://purl.org/ctdl/vocabs/creditUnit/DegreeCredit",
       "creditUnitValue": 3.0,
       "courseCode": "COMP B12",
       "programTerm": "2nd Term",
       "ceterms:startDate": "2019-9-16",
       "ceterms:endDate": "2019-12-16",
       "ceasn:isChildOf": "res:61183b59-0669-457b-881a-a2b3bedcafdc",
       "ceterms:prerequisite": "res:642806c0-e0e2-4805-a95e-47627d5b4b9d"
    }
```

