# corona
simulation of the volume of people in the west zone of São Paulo for Visagio's Hackaton (we won first place!).
To stop corona, it is important to avoid crowds. Hence, we created this website to give people suggestion about places to go shopping and avoid supermarkets with a high volume of people.

1. GoogleMaps.ipynb
This algorithm extract data from google maps API and generates a database that contains supermarkets and grocery stores info (name, id, district name, coordinates and volume of people in each hour and day of the week).
To use this algorithm it is necessary to create a google cloud platform and activate billing. Thus, you will be able to create a key, link it with google maps API (places) and use google maps info. Futhermore, it will be necessary to create a csv file with the stablishments info (district name, google maps id, name) and substitute supermercados.csv path by your own in the code.
In the end, it will generate super_horarios.csv that will be used in the next algorithm.

1. website.ipynb
This algorithm uses the data from the previous step, plot a circologram of the volume of people in a map and launches a website that gives people some suggestions about empty places to go shopping.
To use it, it is important to change the path of super_horario.csv and relacao_arquivos.csv (contains all paths for a folder with the maps) by your own files. 
