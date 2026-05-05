# PatientExample - v0.1.0

## Example Patient: PatientExample

Profile: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (no stated gender), DoB Unknown

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "PatientExample",
  "meta" : {
    "profile" : ["http://BR&R/EligibilityIG.org/StructureDefinition/MyPatient"]
  },
  "name" : [{
    "family" : "Pond",
    "given" : ["James"]
  }]
}

```
