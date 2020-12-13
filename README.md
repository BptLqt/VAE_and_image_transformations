# VAE_and_image_transformations


Dataset utilisé : CelebA

CelebA provient plusieurs centaines de millers de photos de visages, toute, labelisées selon 40 attributs, comme : "Smiling", "Young" ou "Male".

En utilisant une architecture d'un auto-encodeur variationel, on peut estimer la distribution latente de ces images, et générée des images semblant provenir de cette distribution. Et en estimant le vecteur "sourire", par exemple, en trouvant la moyenne des représentations latentes des images labelisée, on peut faire plus ou moins sourire une personne. Et en estimant les vecteurs des 40 attributs, on peut modifier la photo comme l'on veut selon les 40 attributs
