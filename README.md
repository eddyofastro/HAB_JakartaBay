# Welcome

&nbsp;

## Introduction

*Harmful algal bloom* (HAB) adalah peristiwa pertumbuhan alga (fitoplankton) secara masif dan cepat di kawasan perairan, termasuk di kolam, danau ataupun pesisir. Walaupun fitoplankton merupakan organisme penting di perairan, namun pertumbuhan yang berlebihan menimbulkan bahaya bagi ekosistem perairan. Dampak yang bisa muncul antara lain terjadinya kekurangan oksigen yang menyebabkan kematian massal ikan dan organisme lainnya, hingga penyebaran racun dari jenis fitoplankton tertentu.

Kajian-kajian mengenai HAB telah banyak dilakukan, terutama mengenai penyebab dan dampaknya. Namun, monitoring terjadinya HAB merupakan hal yang cukup sulit dilakukan di lapangan. Meluasnya penggunaan citra satelit dapat membantu proses monitoring, namun diperlukan algoritma yang dpaat menerjemahkan data citra optik satelit (berupa reflektansi cahaya di permukaan air) menjadi parameter yang relevan dengan HAB. 

Kajian dari ... telah menunjukkan bahwa citra satelit dari Sentinel-3 dapat digunakan untuk mendeteksi terjadinya HAB. Red Tide Index dikalkulasi dengan rumusan

$$
RDI = \left( \frac{1}{Rrs_{08}} - \frac{1}{Rrs_{06}} \right) \times Rrs_{12}
$$

Untuk riset ini, kami menggunakan RDI untuk mendeteksi kejadian HAB di Teluk Jakarta. Kami menggunakan platform `Planetary Computer` yang [disediakan oleh Microsoft](https://planetarycomputer.microsoft.com/) untuk memproses data Sentinel-3 pada *cloud*. Platform ini menyediakan akses data yang luas sekaligus *analysis tools* yang menggunakan program-program opensource seperti Jupyter (Python), R dan QGIS. Hal ini memudahkan pemrosesan data karena bisa langsung dilakukan secara *online* dan kolaboratif, dan dapat menghemat *resources* di level pengguna.

## Content
