<img align="left" src="https://user-images.githubusercontent.com/62319355/104537209-7c71b380-5654-11eb-93db-047330b1ae3d.jpg"  height="80" alt="Cloudera">
<img align="right" src="https://user-images.githubusercontent.com/62319355/104537326-b9d64100-5654-11eb-89f3-c0ee9be8b1ec.png"  height="80" alt="Alteryx">
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
<img align="left" src="https://user-images.githubusercontent.com/62319355/104536931-f5bcd680-5653-11eb-8366-9c0e460624cd.png" alt="Cloudera Hue2">



## You can establish connection as shown below  :thumbsup:
<img align="center" src="https://user-images.githubusercontent.com/62319355/104537551-22252280-5655-11eb-9ea0-4de6e27e0114.png"   alt="ODBC impala">

## Please enable SSL Certifcate as shown below.
<img align="center" src="https://user-images.githubusercontent.com/62319355/104538259-7e3c7680-5656-11eb-84c0-0bb1ded086e1.png"   alt="SSL">


## Next let us connect to Alteryx
<img align="center" src="https://user-images.githubusercontent.com/62319355/104538740-674a5400-5657-11eb-9a0b-d6a6d5b8ec9d.png"   alt="altery impala">

## You will see all relevant schema once you have successfully connected
<img align="center" src="https://user-images.githubusercontent.com/62319355/104538835-9a8ce300-5657-11eb-8f55-bd8dad769302.png"   alt="table">

## (Additional) Tableau Connection with Impala
```
https://github.com/rainmankim/tableau_cloudera
```
<img align="center" src="https://github.com/rainmankim/cloudera_alteryx/blob/master/images/tableau_impala.PNG"   alt="table">





## Credits
```
- Daniel Toth         (https://www.linkedin.com/in/daniel-toth/)
```


