# Ongoing developments
D discussion, I implementations

## 20220621
### Implementation
* added a new field <code>Accession HTTP URI</code> in srsStats
* GateKeeper rules are available in [Data Access and Dashboards](https://github.com/plazi/Plazi-Communications/wiki/Data-Access-and-Dashboards#gatekeeper-rules)
* Data Tape Library (DTL) installed to long term preserver IMF files. 

### Discussion
* tables: how to get semantics out of tables: Tables should not be converted directly into semantic units, like in [this case](https://tb.plazi.org/GgServer/summary/5412FF8EFFDFFFCB76743F08FFBDFFE8), but a copy of the table should be maintained and then an extracted version should be produced downstream
* Is a row in a table a treatment: Currently yes. Should we insert a new data type for this? 
* The merge treatments in an article gizmo exists, but is not used. Need to create a training session
