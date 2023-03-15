# wbvreeuwijk
  <http://www.trilliumsoftware.com>
  <nospam+bas@reeuwijk.net>

## <a href='./components/bvrCountryConversion/readme.md'><img src='./components/bvrCountryConversion/logo.jpg' width='40' height='40'> bvrCountryConversion</a>
 :warning: Compatibility not known

<img src='./components/bvrCountryConversion/sample.jpg'>

## <a href='./components/bvrRunAnt/readme.md'><img src='./components/bvrRunAnt/logo.jpg' width='40' height='40'> bvrRunAnt</a>
 :warning: Compatibility not known

This component runs an ant build job from within a Talend job.



<img src='./components/bvrRunAnt/sample.jpg'>

## <a href='./components/bvrVATNumberCheck/readme.md'><img src='./components/bvrVATNumberCheck/logo.jpg' width='40' height='40'> bvrVATNumberCheck</a>
 :warning: Compatibility not known

This component checks and validates a VATNumber from the following european countries:

AT-Austria  
BE-Belgium 
BG-Bulgaria 
CY-Cyprus 
CZ-Czech Republic 
DE-Germany 
DK-Denmark 
EE-Estonia 
EL-Greece 
ES-Spain 
FI-Finland 
FR-France 
GB-United Kingdom 
HU-Hungary 
IE-Ireland 
IT-Italy 
LT-Lithuania 
LU-Luxembourg 
LV-Latvia 
MT-Malta 
NL-The Netherlands 
PL-Poland 
PT-Portugal 
RO-Romania 
SE-Sweden 
SI-Slovenia 
SK-Slovakia 

The component takes the VATNumber and the country code either in ISO2 or ISO3 code.


<img src='./components/bvrVATNumberCheck/sample.jpg'>

## <a href='./components/hiAbbreviationAndDivision/readme.md'><img src='./components/hiAbbreviationAndDivision/logo.jpg' width='40' height='40'> hiAbbreviationAndDivision</a>
 :warning: Compatibility not known

<img src='./components/hiAbbreviationAndDivision/sample.jpg'>

## <a href='./components/hiAddressBEFRGBStandardization/readme.md'><img src='./components/hiAddressBEFRGBStandardization/logo.jpg' width='40' height='40'> hiAddressBEFRGBStandardization</a>
 :warning: Compatibility not known

<img src='./components/hiAddressBEFRGBStandardization/sample.jpg'>

## <a href='./components/hiAddressNLDERapidAddressing/readme.md'><img src='./components/hiAddressNLDERapidAddressing/logo.jpg' width='40' height='40'> hiAddressNLDERapidAddressing</a>
 :warning: Compatibility not known

This component provides the interface to the Human Inference HIquality Address rapid addressing for The Netherlands and Germany

Rapid Addressing retrieves the address from the knowledge table based on the postcode and the house number. It is possible that the user has made a typing error and that nevertheless a valid address is retrieved with this erroneous postcode or house number. To prevent this seemingly correct address from being found, Rapid Addressing uses check components (see below). In Germany the postcode and house number do not always result in a unique address, therefore check components are mandatory in Germany

Prerequisites: Human Inference Address rapid addressing for NL/DE.




<img src='./components/hiAddressNLDERapidAddressing/sample.jpg'>

## <a href='./components/hiAddressNLDEStandardization/readme.md'><img src='./components/hiAddressNLDEStandardization/logo.jpg' width='40' height='40'> hiAddressNLDEStandardization</a>
 :warning: Compatibility not known

This component provides the interface to the Human Inference HIquality Address standardisation for The Netherlands and Germany

Standardization retrieves the correct address based on any parts of the address. This can be done in an on-line search, or in a batch run to correct and standardize the addresses in a database.
Standardization has an effort setting and the maximum number of results and the separation character can be set. If an address could not be found, Standardization will try to format the input. Standardization returns the address according to a flexible format that can be configured in the output template

Prerequisites: Human Inference Address standardisation for NL/DE.



<img src='./components/hiAddressNLDEStandardization/sample.jpg'>

## <a href='./components/hiAddressStandardization/readme.md'><img src='./components/hiAddressStandardization/logo.jpg' width='40' height='40'> hiAddressStandardization</a>
 :warning: Compatibility not known

<img src='./components/hiAddressStandardization/sample.jpg'>

## <a href='./components/hiAddressWW/readme.md'><img src='./components/hiAddressWW/logo.jpg' width='40' height='40'> hiAddressWW</a>
 :warning: Compatibility not known

This component provides the interface to the Human Inference HIquality Address standardisation for the rest of the world.

Based on the provided input the software tries to find the best fit for the address in the given country. If multiple addresses fit the input then they will be returned. The software also provides a reliability level of 1 to 3 where 1 is a sure match and 3 is a highly doubtful match.

The component supports two modes of operation:
1) Through a web-service
2) Stand-alone

In both case Human Inference software is needed.

Prerequisites: Human Inference Address WW standardisation.



<img src='./components/hiAddressWW/sample.jpg'>

## <a href='./components/hiBussinessDetailsV3/readme.md'><img src='./components/hiBussinessDetailsV3/logo.jpg' width='40' height='40'> hiBussinessDetailsV3</a>
 :warning: Compatibility not known

This component retrieves Chamber of Commerce details using the webservice from Webservices.nl. Based on the dossiernumber and subdossiernumber the following businessdetails are returned:

- RegisterLetter
- DossierNo
- SubDossierNo
- ChamberNo
- Legalformcode
- LegalformcodeText
- PreviousDossierNo
- PreviousSubDossierNo
- Tradename45
- TradenameFull
- EstablishmentPostcode
- EstablishmentCity
- EstablishmentStreetname
- EstablishmentHouseNo
- EstablishmentHouseNoAddition
- CorrespondencePostcode
- CorrespondenceCity
- CorrespondenceStreetname
- CorrespondenceHouseNo
- CorrespondenceHouseNoAddition
- TelephoneNo
- Domainname
- PrimarySBICode
- SecondarySBICode1
- SecondarySBICode2
- PrimarySBICodeText
- SecondarySBICode1Text
- SecondarySBICode2Text
- Personnel
- ClassPersonnel
- IndicationOrganisationcode
- IndicationEconomicallyActive
- IndicationNonMailing
- IndicationBankruptcy
- IndicationDIP

Requirements:
- Account on webservices.nl

<img src='./components/hiBussinessDetailsV3/sample.jpg'>

## <a href='./components/hiBussinessSearch/readme.md'><img src='./components/hiBussinessSearch/logo.jpg' width='40' height='40'> hiBussinessSearch</a>
 :warning: Compatibility not known

This component uses the Business information webservice published by webservices.nl to find information in the Dutch Chamber of Commerce. Information can be retrieved based on:

- Name
- Street/City
- Postcode/Housenr

Information returned:
- Dossiernumber
- Subdossiernumber
- Tradename
- Streetname
- City

Requirements:
- Account on webservices.nl
<img src='./components/hiBussinessSearch/sample.jpg'>

## <a href='./components/hiCapitalization/readme.md'><img src='./components/hiCapitalization/logo.jpg' width='40' height='40'> hiCapitalization</a>
 :warning: Compatibility not known

<img src='./components/hiCapitalization/sample.jpg'>

## <a href='./components/hiDedup/readme.md'><img src='./components/hiDedup/logo.jpg' width='40' height='40'> hiDedup</a>
 :warning: Compatibility not known

This component uses Human Inference precision matching to perform a deduplication on Persons, Companies, Persons/Companies and Contactpersons at companies.

The following countries are supported:
- Netherlands
- Belgium
- Germany
- Great Britain
- France
- Rest of the world

Prerequisites: Human Inference Identify software.

This component uses standard plan-files that can be found in the std_plan_files.zip archive. Place the contents of this file in the current config-directory.



<img src='./components/hiDedup/sample.jpg'>

## <a href='./components/hiEmail/readme.md'><img src='./components/hiEmail/logo.jpg' width='40' height='40'> hiEmail</a>
 :warning: Compatibility not known

<img src='./components/hiEmail/sample.jpg'>

## <a href='./components/hiFormatConversion/readme.md'><img src='./components/hiFormatConversion/logo.jpg' width='40' height='40'> hiFormatConversion</a>
 :warning: Compatibility not known

<img src='./components/hiFormatConversion/sample.jpg'>

## <a href='./components/hiIdentifyExec/readme.md'><img src='./components/hiIdentifyExec/logo.jpg' width='40' height='40'> hiIdentifyExec</a>
 :warning: Compatibility not known

The hiIdentifyExec component provides a means to start Human Inference HIquality Identify tasks. HIquality Identify is a high precision matching engine that uses linguistic knowledge to split client records into descriptions, slice them into chunks and evaluates each pair to find duplicated in relational data.

There are four steps that this component can be used for:
- Create: creates database structure according to the plan-file
- Build: build the descriptions according to the plan-file
- Dedup: deduplicate records based on evaluations in the plan-file
- Drop: drop the database components

Prerequisites: Human Inference HIquality software.



<img src='./components/hiIdentifyExec/sample.jpg'>

## <a href='./components/hiMergeExec/readme.md'><img src='./components/hiMergeExec/logo.jpg' width='40' height='40'> hiMergeExec</a>
 :warning: Compatibility not known

The hiMerge component is used to start a batch merging process it works by starting the Human Inference HIquality Merge process.

HIquality Merge is used form merging multiple client records into a single golden record. The configuration of this component is simply the name pointing to the HIquality Merge configuration file.

Prerequisites: Human Inference HIquality Merge software.
<img src='./components/hiMergeExec/sample.jpg'>

## <a href='./components/hiNameProcessing/readme.md'><img src='./components/hiNameProcessing/logo.jpg' width='40' height='40'> hiNameProcessing</a>
 :warning: Compatibility not known

The Human Inference Name Processing component gives you the ability to split names into their name elements. So the name "ing. Bas W.B. van Reeuwijk" will be split into

QualificationPreceding: ing.
GivenNames: Bas
GivenNamesInitial: W.B.
SurnamePrefixFirst: van
SurnameFirst: Reeuwijk

The component supports the following countries: Netherlands, Belgium, France, Germany and United Kingdom. It allows you to check the gender of a person and whether it is a person or an organisation. 

Requirements: Access to a Human Inference server, Human Inference java connector.

Notes on usage:

1) The reliability code gives a reliability status of (1 = correct, 2 = doubtfull, 3 = probably incorrect)
2) The resultcodes of the standardisation are put into a string in the form of
[code1]|[remark1]|[message1];[code2]|[remark2]|[message2];...;[codeN]|[remarkN]|[messageN]; It is therefore recommended to use the tNormalize and tExtractDelimited to get all the details out of the standardisation (see screenshot)
3) Out of one name multiply rows can be generated when the name passed to the component contains more than one name.




<img src='./components/hiNameProcessing/sample.jpg'>

## <a href='./components/hiSearch/readme.md'><img src='./components/hiSearch/logo.jpg' width='40' height='40'> hiSearch</a>
 :warning: Compatibility not known

<img src='./components/hiSearch/sample.jpg'>

## <a href='./components/hiSynchronize/readme.md'><img src='./components/hiSynchronize/logo.jpg' width='40' height='40'> hiSynchronize</a>
 :warning: Compatibility not known

This component provides the interface to the Human Inference Identify Synchronize functionality. To be able to use hiSearch descriptions need to be created. This is done through the this component.

Synchronize
Call Synchronize after every change (insertion, deletion or modification) in the customer database providing the changed record. To ensure that the synchronize record function is called after every change, a trigger can be put on the customer database.

Requirements: Human Inference Identify software
<img src='./components/hiSynchronize/sample.jpg'>

## <a href='./components/hiTransform/readme.md'><img src='./components/hiTransform/logo.jpg' width='40' height='40'> hiTransform</a>
 :warning: Compatibility not known

<img src='./components/hiTransform/sample.jpg'>

## <a href='./components/hiTransliterate/readme.md'><img src='./components/hiTransliterate/logo.jpg' width='40' height='40'> hiTransliterate</a>
 :warning: Compatibility not known

This component provides the interface to the Human Inference transliteration functionality.

Transliterate can be used to transform non-latin characters into a latin characterset.

Examples:
??? -> mao ze dong
????????? ?????? -> vladimir putin
?? -> shang hai
??? -> tokyo
????? -> mumba'i

Requirements: Human Inference Transliterate software

<img src='./components/hiTransliterate/sample.jpg'>

## <a href='./components/hiValidateName/readme.md'><img src='./components/hiValidateName/logo.jpg' width='40' height='40'> hiValidateName</a>
 :warning: Compatibility not known

This component provides an interface to the Human Inference validate name functionality.

Validation Name checks if a person name exists. Company names cannot be validated, because an infinite number of word combinations and acronyms can be a valid company name.
Validation Name uses extensive knowledge of first names and surnames to determine if a name is valid, but it can still happen that a name is not (yet) added to the knowledge. It is possible to add the name to the user table or notify Human Inference to include the name in the next knowledge update. Human Inference offers regular updates of the knowledge.

Requirements: Human Inference software
<img src='./components/hiValidateName/sample.jpg'>

## <a href='./components/tOracleExecute/readme.md'><img src='./components/tOracleExecute/logo.jpg' width='40' height='40'> tOracleExecute</a>
 :warning: Compatibility not known

Execute command on Oracle database connection
<img src='./components/tOracleExecute/sample.jpg'>
