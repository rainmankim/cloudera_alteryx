<img align="left" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/cloudera_logo.jpg"  height="80" alt="Cloudera">
<img align="right" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/alteryx_logo.png"  height="80" alt="Alteryx">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:

## Cloudera HIVE/Impala-Alteryx connection 
```
Hi,  my name is Ray Kim. 
THis documentation will show how you can establish connection between Cloudera Datalake and Alteryx.

Connecting Alteryx to Clouder has many advantages:
- Can extract more than 100,000 rows
- Can easily cleanse and prep data

Please go to Cloudera Websites to download ODBC connectors.
In this documenteation, I will install Impala ODBC connector.
(HIVE is more robust for larger query but HIVE is slower than Impala.

```
https://www.cloudera.com/downloads/connectors/impala/odbc/2-6-0.html
https://www.cloudera.com/downloads/connectors/hive/odbc/2-6-1.html
<img align="left" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/cloudera_hue.png" alt="Cloudera Hue">
<img align="left" src="https://user-images.githubusercontent.com/62319355/104536931-f5bcd680-5653-11eb-8366-9c0e460624cd.png" alt="Cloudera Hue2">



## You can establish connection as shown below  :thumbsup:
<img align="center" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/ODBC_impala.PNG"   alt="ODBC impala">

## Please enable SSL Certifcate as shown below.
<img align="center" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/ODBC_impala_SSL.PNG"   alt="SSL">


## Next let us connect to Alteryx
<img align="center" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/alteryx_impala.PNG"   alt="altery impala">

## You will see all relevant schema once you have successfully connected
<img align="center" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/alteryx_impala_schema.PNG"   alt="table">

## (Additional) Tableau Connection with Impala
```
As on my side, I can establish connection but it seems Tableau cannot read Tables.
```
<img align="center" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/tableau_impala.PNG"   alt="table">





## Credits
```
- Daniel Toth         (https://www.linkedin.com/in/daniel-toth/)
```


