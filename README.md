# etwmanifests
This repository contains a dump of the XML manifests of all registered Windows ETW providers in the following format/structure:

* manifests
  * (OS build number)
    * (provider name) {provider GUID}.xml

These manifests were produced with etwlib, a .NET ETW library (to be released soon).

# References
* [@repnz's etw-providers-docs](https://github.com/repnz/etw-providers-docs)
* [Microsoft's perfview parser](https://github.com/microsoft/perfview/blob/main/src/TraceEvent/RegisteredTraceEventParser.cs)
