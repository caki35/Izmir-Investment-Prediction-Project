# Izmir-Investment-Prediction-Project

## 1. Introduction: Business Problem
Turkish metropolitan city Izmir has population of 4.36 million. It makes Izmir the third most populous city in Turkey and the fourth in Mediterranean Sea. Izmir consist of 11 urban districts – namely Balcova, Bayrakli, Bornova, Buca, Cigli, Gaziemir, Guzelbahce, Karabaglar, Karsiyaka, Konak, and Narlidere – and additionally 19 rural districts – namely Aliaga, Bayindir, Bergama, Beydag, Cesme, Dikili, Foca, Karaburun, Kemalpasa, Kinik, Kiraz, Menderes, Menemen, Odemis, Seferihisar, Selcuk, Tire, Torbalı, Urla –. [1]
Located on the west coast of Turkey, Izmir includes two ports – namely Aliaga Port and Izmir Alsancak Port – that are the primary ports of Turkey for exports. Particularly Izmir Alsancak Port is the biggest container port of Turkey with a capacity of 10 million tons. Thanks to capacity of exports and imports, there are vast industrial zones from various branches of industry, especially high-tech industry. Apart from industry, Izmir is one of the centers of modern agriculture and animal husbandry because of its fertile lands, favorable climatic conditions, rich water resources, and biodiversity. Today, Izmir is the second largest commercial hub in Turkey. [2] According to Brookings Institution Global Metro Monitor, Izmir is the world’s second fastest growing metropolitan economy. [3] Moreover, hundreds of thousands of tourists come to Izmir every year to vacation in coastal towns such as Cesme, Seferihisar, Urla, and Foca, and to visit ancient heritages and religious areas in Selcuk and Bergama. [4] 
All those factors mentioned above make Izmir attractive for investment. As a result of this, the number of Turkish citizens and foreign people who immigrate to Izmir rises day by day. [2] This situation induces sharply increase property prices in Izmir. Izmir has become the most profitable city of Turkey in which house rents increase most recently. [5] Prediction of new areas that may have the potential to appreciate in value is vital for investors or for those who think to buy a new house. I aimed to meet this requirement in this project. Boroughs of Izmir were clustered based on the venues that they have. Then, the clusters were compared with sold house prices to reveal patterns behind house prices.

## 2. Data:
In project four data sources will be used:
•	An open-source API, which is publicly available in GitHub, is used to retrieve longitude and latitude coordinates of the center of boroughs. [6] The API includes coordinates of all cities and boroughs in Turkey. The information of Izmir is parsed through URL query.  
•	I mentioned above that similar boroughs were clustered by exploiting venues that they have. By using the center coordinates, the most common venues with their features in neighborhoods are retrieved from Foursquare API through URL query. [7]
•	The average sales price of houses sold in Izmir are taken from Endeksa that is one of the most popular property price index companies in Turkey. [8]
•	The geolocation data of polygons that draw the boundary of boroughs of Izmir are retrieved from Second-level Administrative Divisions of the Turkey from Spatial Data Repository of NYU. [9] The data contains the geolocation of whole cities and boroughs in Turkey. The data of Izmir was parsed from all geojson files. It will be used to create choropleth map.

References
[1] “İzmir.” Wikipedia. Wikimedia Foundation, February 28, 2020. https://en.wikipedia.org/wiki/İzmir. 
[2] “Economy Of İzmir.” Izto. Accessed March 1, 2020. http://www.izto.org.tr/en/izmir-ekonomisi.
[3] “Tourism of İzmir.” Izto. Accessed March 1, 2020. http://www.izto.org.tr/en/izmir-turizmi.
[4] Trujillo, Jesus Leal, and Joseph Parilla. “The World's 10 Fastest Growing Metropolitan Areas.” Brookings. Brookings, August 8, 2019. https://www.brookings.edu/blog/the-avenue/2015/02/10/the-worlds-10-fastest-growing-metropolitan-areas/.
[5] “REIDIN Emlak Endeks 2018 Temmuz Ayı Sonuçları.” REIDIN, September 17, 2018. https://blog.reidin.com/reidin-emlak-endeks-2018-temmuz-ayi-sonuclari/.
[6] https://github.com/melihkorkmaz/il-ilce-mahalle-geolocation-rest-api
[7] https://developer.foursquare.com/
[8] https://www.endeksa.com/en/analiz/izmir/endeks/for-sale/house
[9] Second-level Administrative Divisions, 2. (2020). Second-level Administrative Divisions, Turkey, 2015 - NYU Spatial Data Repository. [online] Geo.nyu.edu. https://geo.nyu.edu/catalog/stanford-nj696zj1674
[10] Özdalgıç, Aytaç. “Türkiye'nin En Pahalı 50 Ilçesi.” Tapusor.com, October 19, 2018. https://tapusor.com/blog/turkiyenin-en-pahali-50-ilcesi/.
