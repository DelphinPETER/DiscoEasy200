## Vous possédez un imprimante 3D de chez DAGOMA et vous désirez passer de CuraByDagoma à Cura 2.4.

##ATTENTION CERTAINS PARAMÈTRES NE SONT PAS ENCORE TRANSFÉRÉS, CES FICHIERS SONT PARTAGÉS POUR ÊTRE TESTÉS.

Voici les fichiers qui vous permettront de retrouver les paramètres par défaut de CuraByDagoma dans Cura version 2.4

Les fichiers sont à copier dans le dossier d'installation de Cura.

Par défaut, sous Windows 64bits :
`C:\Program Files\Cura 2.4`

- Les paramètres des imprimantes :
  - `.\resources\definitions\*.def.json`
- Le modèle 3D des imprimantes :
  - `.\resources\meshes\*_plateform.stl`
- Les paramètres de qualité d'impression :
  - `.\resources\quality\dagoma_*\*.inst.cfg`
- Les paramètres des différents filaments :
  - `.\resources\materials\*.xml.fdm_material`

**Attention ces fichiers vous sont fournis sans garantie**. Je ne pourrais être tenu responsable d'un quelconque dommage causé à votre imprimante 3D. A vous de bien vérifier les paramètres avant de lancer l'impression.

##ASTUCES :

Si vous souhaitez accélérer le chargement de Cura, vous pouvez supprimer les fichiers ne correspondant pas aux imprimantes Dagoma.
ATTENTION : vous ne pourrez pas installer d'autres imprimantes autres que celles de Dagoma par la suite (sauf en réinstallation Cura).
- `.\resources\definitions\*.def.json` **SAUF fdmprinter.def.json  et  fdmextruder.def.json**
- `.\resources\materials\*.xml.fdm_material`
- `.\resources\quality\*.inst.cfg`

Si vous souhaitez que Cura enresgitre le fichier sur votre carte SD directement avec le bon nom `dagoma0.g`, il suffit de copier le fichier `hack\RemovableDriveOutputDevice.py` dans le dossier `plugins\RemovableDriveOutputDevice`

Si vous souhaitez donner les couleurs de Dagoma à Cura, vous pouvez copier les dossiers `images` et `themes`présents dans le dossier `theme_dagoma` vers le dossier `ressources` de Cura.

![GitHub Logo](/theme_dagoma/preview.png)
