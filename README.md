# ch-core
CH Core Implementation Guide (FHIR)
Core FHIR profiles for Switzerland

## building the implementation guide

```
wget http://build.fhir.org/org.hl7.fhir.igpublisher.jar -O org.hl7.fhir.igpublisher.jar
java -Xms3550m -Xmx3550m -jar org.hl7.fhir.igpublisher.jar -ig ig.json
```



search in VS Code for differentials in profiles (e.g. Patient):

profiles-resources.xml
<differential>[\n|\s]*<element id="Patient
