## Access to treatment dumps
This might include zip of >1GB!
* This is the overview pages to the [Treatment dump](https://tb.plazi.org/dumps/) including access to various formats. 

## Machine readable access
* [Darwin Core Archive HTTP GET](http://plazi.org/treatmentbank/treatment-data-access/)
* To get access to results from the webservices in TaxPub, simply append `?dataFormat=TTP_XML` to the result download URL ... the format is available for all three services in question, and it should give you pretty much the input XML, plus whatever the tagger added
* Different flavors of treatments are available by changing the XXX in this URL: `https://treatment.plazi.org/GgServer/XXX/885887A2FFFE8A18F8B4FCA2F30BD6BB`
   * [TaxPub Level 1](https://github.com/plazi/ggxml2taxpub-treatments/blob/main/taxpub%20levels.md): `taxPubL1`
   * Html: `html`
   * XML: `xml`
* List of updates [timestamps of changes](https://tb.plazi.org/GgServer/lodData/listFull?updatedSince=1646697601000); repalce timestamp with the [desired date](https://www.epochconverter.com/) 
* List of new or changed or deleted treatments UUID with lodRDF available [Link](https://tb.plazi.org/GgServer/lodData/038B87D0FFCD2D479A0CA15D0C6F75A5)

## Customized downloads
A customizable download of specific corpora of treatments in a given format is forthcoming.

At the moment a list of treatment UUIDs can be built using [Plazi Stats](https://tb.plazi.org/GgServer/srsStats). Then build the URL for the treatment using https://treatment.plazi.org/GgServer/XXX/ and download the respective treatments. E.g. for a treatment in taxPubL1:  https://tb.plazi.org/GgServer/taxPubL1/038B87D0FFCD2D479A0CA15D0C6F75A5
