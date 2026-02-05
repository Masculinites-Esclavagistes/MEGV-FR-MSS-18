
# MEGV-FR-MSS-18

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

## Content

This repo contains training data [`data_ref`](https://github.com/Masculinites-Esclavagistes/MEGV-FR-MSS-18/tree/a7d231515a9a87c8d3ae1367127a7b175f8f9129/data_ref), as well as HTR and segmentation models fine-tuned with this training data (FoNDUE-GD-MEGV_v2 and seg_megv), for the project entitled 'Masculinités Esclavagistes : Genre et Violence dans la Caraïbe Française (XVIIIème siècle)' or MEGV. The training data was also OCR'd using the MEGV models [`data_ocr`] (https://github.com/Masculinites-Esclavagistes/MEGV-FR-MSS-18/tree/main/data_ocr). 
The training data originates from manual transcriptions of 18th c. French manuscripts from a composite corpus: the correspondence of plantation owners in the French Caribbean, the files of individual soldiers and colonial officers, and court cases from the holdings of the Secrétariat de la Marine.

The data comes from the MEGV project, led by Marie Houllemare at the University of Geneva (Switzerland) and financed by the SNSF. 
The transcriptions were carried out by Elodie Bascoul, Marion Philip and Méloé Maillard, with the support of Simon Gabay and Thomas Gauffroy-Naudin using eScriptorium VRE. 

### ANOM (Aix-en-Provence) - Secrétariat d'Etat à la Marine - Personnel colonial ancien - COL E : 

#### Dossier "anom_col_e_vrac"

| Description                                                             | File Number         | Source                                                                      | Transcription |
|-------------------------------------------------------------------------|---------------------|-----------------------------------------------------------------------------|---------------|
| Tach, Etienne - Tan, René, Robert Guillaume - meurtre - Saint-Domingue  |  COL E 375          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424bv2uwvp/daogrp/0/1) | M. Philip     |
| Taffart, Jean - cadet - Saint-Domingue                                  |  COL E 375          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424xryqsxu/daogrp/0/1) | M. Philip     |
| Taillevis de Perrigny, Charles Léon - lieutenant du roi - Saint-Domingue|  COL E 334BIS       | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424g07z26j/daogrp/0/1) | M. Philip     |
| Thomy, Jean - Janson, Mathieu - tentative meurtre - Saint-Domingue      |  COL E 379          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424au1wvtl/daogrp/0/1) | M. Philip     |
| Despousses - adultère - Saint-Domingue                                  |  COL E 128          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424ayyy0h/daogrp/0/2)  | M. Philip     |
| Julienne, négresse - Gourgeu, Sébastien - affranchissement - Cayenne    |  COL E 233          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424icbeegc/daogrp/0/2) | M. Philip     |

#### Dossier "anom_col_e_vrac_2"

| Description                                                             | File Number         | Source                                                                       | Transcription |
|-------------------------------------------------------------------------|---------------------|------------------------------------------------------------------------------|---------------|
| Michel, Françoise - de La Mure - mariage - Martinique                   |  COL E 311          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424wqsyrtp/daogrp/0/18) | M. Maillard   |
| Michel - Lefèvre, Jean Jacques - assassinat - Saint-Domingue            |  COL E 311          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qkmsmng/daogrp/0/1)  | M. Maillard   |
| Garet - assassinat - Guyane                                             |  COL E 198          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424tuoonm/daogrp/0/1)   | M. Maillard   |
| Julien, Jean Pierre - assassinat - Grenade                              |  COL E 233          | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424fzy103s/daogrp/0/18) | M. Maillard   |



#### Dossier "anom_col_e_soldats_1a ; anom_col_e_soldats_1b ; anom_col_e_soldats_1c"

| Description                                                             | File Number         | Source                                                                      | Transcription |
|-------------------------------------------------------------------------|---------------------|-----------------------------------------------------------------------------|---------------|
| Adam, Jean - Soldat mort - Marie Galante   							  |  COL E 1  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424g25r/daogrp/0/2)    | E. Bascoul    |
| Adert, Pierre - Soldat déserteur - Saint Domingue  					  |  COL E 1  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424wttg/daogrp/0/2)    | E. Bascoul    |
| Agré, dit Montpellier - Tambour major - Guadeloupe 					  |  COL E 1  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424mlkf/daogrp/0/2)    | E. Bascoul    |
| Ailleboust, Charles Philippe - Lieutenant - Cayenne			 		  |  COL E 2  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424wwyo/daogrp/0/2)    | E. Bascoul    |
| Augerant, Jacques - soldat déserteur - Ile de France			 		  |  COL E 11  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424usptl/daogrp/0/2)   | E. Bascoul    |
| Béguinot, Antoine - soldat déserteur - Ile de Ré					 	  |  COL E 24  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424oiinno/daogrp/0/2)  | E. Bascoul    |
| Bigorry, Jean - soldat - Martinique								 	  |  COL E 314BIS 		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qkpmqb/daogrp/0/2)  | E. Bascoul    |
| Carbonnel, Siméon dit Saint Marcel - soldat - Saint-Domingue		 	  |  COL E 62	 		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424e0xz1r/daogrp/0/2)  | E. Bascoul    |
| Chabaroche, Pierre Charles - soldat - Saint-Domingue				 	  |  COL E 67	 		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424xtsxyn/daogrp/1) 	  | E. Bascoul    |
| Duparc, Jean Pierre - lieutenant - Martinique						 	  |  COL E 157	 		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424mllkjl/daogrp/0/2)  | E. Bascoul    |
| Monpas, Jean François - soldat - Saint Domingue					 	  |  COL E 314BIS	 	| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qknkmpb/daogrp/0/2) | E. Bascoul    |

#### Dossier "anom_col_e_soldats_2"

| Description                                                             | File Number         | Source                                                                      | Transcription |
|-------------------------------------------------------------------------|---------------------|-----------------------------------------------------------------------------|---------------|
| Brussel, Pierre Louis - soldat - Saint Domingue - Saty, Anne sa femme	  |	COL E 55   			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424pkplmv/daogrp/0) 	  | E. Bascoul	  |
| Cabaret - soldat - régiment de l'Amérique								  | COL E 58 			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424xsytzp/daogrp/0/)	  | E. Bascoul    |
| Florac, Pierre - soldat au régiment suisse - Rochefort				  | COL E 185  	        | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qqpkmb/daogrp/0)    | E. Bascoul    |
| Gouy, Jean - soldat - Guyane 											  | COL E 209           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424c4vwzj/daogrp/0)    | E. Bascoul    |
| Hiot, François dit Duchâteau - soldat - Saint Saint-Domingue			  | COL E 223           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424sussqw/daogrp/0/1)  | E. Bascoul    |
| Honoré, Charles dit La Verdure - soldat - Cayenne 					  | COL E 224           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424z10ttc/daogrp/0     | E. Bascoul    |
| Joly, Jean Baptiste - soldat - Martinique								  | COL E 231           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424lfegemt/daogrp/0)   | E. Bascoul    |
| Moisset, Jean - soldat -  Sainte-Lucie								  | COL E 314           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424rlokpsk/daogrp/0/2) | E. Bascoul    |
| Racolet, Jean - soldat - Guadeloupe									  | COL E 344BIS        | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424oimqpmc/daogrp/0)   | E. Bascoul    |
| Roule, Jean - soldat déserteur - Guadeloupe							  | COL E 358           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424ey36zyr/daogrp/0/2) | E. Bascoul    |
| Salvigny, Frédérich de - soldat - Guadeloupe							  | COL E 364           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qkqmpoi/daogrp/0/)  | E. Bascoul    |
| Suzanne, Noël - soldat - Saint-Domingue								  | COL E 374           | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424lfmeekx/daogrp/0/2) | E. Bascoul    |
| Voidant, Pierre Michel - soldat déserteur - Versailles				  | COL E 389BIS        | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424g081z1e/daogrp/0/4) | E. Bascoul    |
| Volant, François Henri - soldat - Saint-Domingue    					  | COL E 389BIS        | (https://recherche-anom.culture.gouv.fr/ark:/61561/up424zt1utzl/daogrp/0/2) | E. Bascoul    |

#### Dossier "anom_col_e_soldats_3"

| Description                                                             | File Number         | Source                                                                      | Transcription |
|-------------------------------------------------------------------------|---------------------|-----------------------------------------------------------------------------|---------------|
| Adam, Pierre - fusilier - Guyane				  					      |	COL E 1  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424okpl/daogrp/0/2) 	  | M. Maillard   |
| Fievé - soldat - Lorient												  |	COL E 183  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424lljfhb/daogrp/0/2)  | M. Maillard   |
| Frenet - tambour - Saint Vincent										  |	COL E 194  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424uuwsvh/daogrp/0/2)  | M. Maillard   |
| Jujardy, Joseph Daniel - garde-magasin -  Saint-Domingue				  |	COL E 233  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424hbadbet/daogrp/0/1) | M. Maillard   |
| Julien, Pierre - chasseur déserteur - Martinique              	      |	COL E 233  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qkjmlpy/daogrp/0/2) | M. Maillard   |
| La Roch, Jacques - chasseur déserteur - Guadeloupe                      |	COL E 256   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424fzy63ys/daogrp/0/2) | M. Maillard   |
| Lemius, Arnold - soldat, ancien capitaine de milices - Saint-Domingue	  |	COL E 276  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424lfgilew/daogrp/0/5) | M. Maillard	  |
| Négrier, Joseph - soldat - Saint-Domingue								  |	COL E 320   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424smpqoqq/daogrp/0/2) | M. Maillard   |
| Palvoisin, Jean Baptiste - soldat - Saint-Domingue					  |	COL E 327   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424kehlfes/daogrp/0/2) | M. Maillard   |
| Pasquier, Adrien - soldat - Îles du Vent   							  |	COL E 331   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424qknslrk/daogrp/0/2) | M. Maillard   |
| Peregard, Nicolas - fusilier - Grenade								  |	COL E 333   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424auyuwte/daogrp/0/2) | M. Maillard   |
| Robillard, Germain Marie - soldat - Cap 								  |	COL E 354  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424jdihkhv/daogrp/0/3) | M. Maillard   |
| Dimerlin - soldat de Marine - Martinique								  |	COL E 134  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424jhjfiw/daogrp/0/2)  | M. Maillard   |
| Gommelet, Pierre - soldat - Martinique Fort-Royal 					  |	COL E 208   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424opppkb/daogrp/0/2)  | M. Maillard   |
| Landry - soldat - Guadeloupe											  |	COL E 253  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424tnnpout/daogrp/0/2) | M. Maillard   |
| Le Chevauseur, Jean Jacques - soldat - Guadeloupe						  |	COL E 269   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424pjjpqkz/daogrp/0/2) | M. Maillard   |
| Mérique, François - soldat - Martinique Fort-Royal	  				  |	COL E 310   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424tnpupub/daogrp/0/2) | M. Maillard   |
| Midy, Antoine François - soldat - Martinique Fort-Royal				  |	COL E 312  			| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424hbdjfac/daogrp/0/2) | M. Maillard   |
| Ormancey, Jean - soldat - Guadeloupe 									  |	COL E 326   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424cwz2zvz/daogrp/0/3) | M. Maillard   |
| Ozot, Antoine Joseph - soldat - Guadeloupe							  |	COL E 326   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424aux00ww/daogrp/0/3) | M. Maillard   |
| Peinteur, Julien - soldat - Guadeloupe								  |	COL E 332   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424icgbege/daogrp/0/2) | M. Maillard   |
| Vautrain, Antoine - soldat - Guadeloupe								  |	COL E 384BIS   		| (https://recherche-anom.culture.gouv.fr/ark:/61561/up424zt00usn/daogrp/0/2) | M. Maillard   |

### Archives Nationales (AN, Paris) - Papiers privés tombés dans le domaine public - T :

#### Dossier "an_corresp_fougeu_conflans"

| Description                                                                                | File Number                                         | Source                       | Transcription |
|--------------------------------------------------------------------------------------------|-----------------------------------------------------|------------------------------|---------------|
| Correspondance Marie-Rose Fougeu – Hubert de Brienne comte de Conflans - Marie du Bouchet  |  T//586 - liasse 14 - côte O - 1 à 11 et 140 à 146  | Photographies personnelles   | M. Philip  |

#### Dossier "an_corresp_fougeu_conflans_2"

| Description                                                                                | File Number                                                           | Source                       | Transcription |
|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|------------------------------|---------------|
| Correspondance Marie-Rose Fougeu – Hubert de Brienne comte de Conflans - Marie du Bouchet  |  T//586 - liasse 14 - côte O - 69 à 81;  liasse 12 - côte M - 7 à 16  | Photographies personnelles   | M. Maillard     |

#### Dossier "an_corresp_provenchere_rochefoucauld"

| Description                                                                                | File Number                                                                                                                                                                      | Source                       | Transcription |
|--------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|---------------|
| Correspondance Provenchère – François Jean Charles de La Rochefoucauld Bayers - et al.     |  T//1113/8                                                                                                                                                                       | Photographies personnelles   | M. Philip     |
| Correspondance Provenchère – François Jean Charles de La Rochefoucauld Bayers - et al.     |  T//1113/11 - liasse 1 - sous-liasse 2 (387, 390, 392, 397, 412-416, 423, 426, 475-477, 483); sous-liasse 3 (548-553, 557); liasse 2 - sous-liasse 1 (156, 158, 160, 161, 163) | Photographies personnelles   | M. Philip     |

#### Dossier "an_corresp_provenchere_rochefoucauld_2"

 | Description                                                                                | File Number                                                             | Source                       | Transcription |
 |--------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|------------------------------|---------------|
 | Correspondance Provenchère – François Jean Charles de La Rochefoucauld Bayers - et al.     |T//1113/11 - liasse 1 - sous-liasse 2 (488-489, 493-494, 486, 500, 504)  | Photographies personnelles   | M. Maillard     |



## How to cite

Cf. [`htr-united.yml`](https://github.com/Masculinites-Esclavagistes/MEGV-FR-MSS-18/blob/main/htr-united.yml) file.


## Licences

Images of COL-E belongs to ANOM (Archives Nationales d'Outre Mer). 
Images of Correspondances (T) are personnal photographies of sources from AN (Archives Nationales).
Transcription is CC-BY-NC. 

<a rel="license" href="https://creativecommons.org/licenses/by/2.0"><img alt="Creative Commons License" style="border-width:0" src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Cc_by-nc_icon.svg" /></a><br /> 






