-- Command lines to Clone and Change remote --

\git clone https://github.com/RedStudio418/Marguerite.git TestClone

\cd TestClone

\git remote add CloneFork https://github.com/MrEsport/Versioning_CloneTest
	fatal: not a git repository (or any of the parent directories): .git

\git remote add CloneFork https://github.com/MrEsport/Versioning_CloneTest.git

\git remote -v
	CloneFork       https://github.com/MrEsport/Versioning_CloneTest.git (fetch)
	CloneFork       https://github.com/MrEsport/Versioning_CloneTest.git (push)
	origin  https://github.com/RedStudio418/Marguerite.git (fetch)
	origin  https://github.com/RedStudio418/Marguerite.git (push)

\git help remote

\git remote rm origin

\git remote -v
	CloneFork       https://github.com/MrEsport/Versioning_CloneTest.git (fetch)
	CloneFork       https://github.com/MrEsport/Versioning_CloneTest.git (push)

\git push CloneFork master

\git add README.md

\git commit -m "added Command Lines path"

\ git push

--------------------------------------------------------------
{
# Marguerite

## FR

Marguerite est un jeu narratif racontant l'histoire de Mia une jeune écolière. 5 fins différentes sont disponibles :)

Crée par Anna Bressan et Kévin Roussel, Fondateurs de RedStudio.
L'application est disponible sur le GooglePlay.
Réalisé avec Unity 2018.3.0f2

## EN

Marguerite is a narrative game telling the story of Mia a young schoolgirl. 5 different purposes are available :)

Created by Anna Bressan and Kévin Roussel, Founders of RedStudio.
The application is available on GooglePlay.
Made with Unity 2018.3.0f2

## Links
License GNU 2.0
🔥 Trailer : https://www.youtube.com/watch?v=i88wN1wRbV8

🔥 Application : https://play.google.com/store/apps/details?id=xyz.redstudio.marguerite&hl=fr

🔥 Website : https://redstudio.xyz

🔥 Youtube : https://www.youtube.com/channel/UCpcqBwz3l_m82UxLgI1qpOQ

🔥 Twitter : https://twitter.com/AventuresDeRed

🔥 Facebook : https://www.facebook.com/AventuresDeRed

🔥 Instagram : https://www.instagram.com/aventuresdered
}

