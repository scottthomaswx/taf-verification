# taf-verification
TAF Verification Plot

v2.0.2 - Scott Thomas
Last Updated: 09/27/2025

Description
This program creates a plot showing forecast ceilings and visibility for a TAF Site (including PROB30s and TEMPO Groups) and compares it to observed ASOS Data. The interface runs off of IEM's TAF and METAR archives and uses the TAF issuance time (rather than the valid time) for lookup. TAF issuance times can be looked up by WFO and Date here. https://mesonet.agron.iastate.edu/wx/afos/list.phtml

Data Availability
January 1, 1996 to Present - Iowa Environmental Mesonet (https://mesonet.agron.iastate.edu/wx/afos/list.phtml)

Version History
- v2.0.2 - September 27, 2025. Fix narritave text
- v2.0.1 - September 26, 2025. Fix issue with partial TAFs issued between 18z-00z
- v2.0.0 - September 26, 2025. Switch all data to IEM, allow for within TAF period plotting and plotting for any TAF regardless of issuance time

- v1.2.0 - September 24, 2025. Add ZIP file and file deletion capability
- v1.1.0 - August 17, 2025. Switch TAF plot to "step" graph
- v1.0.0 - August 2, 2025. Initial Release
