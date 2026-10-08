# dps-architecture - dvs-architektur
DPS (Digital Public Services Switzerland) architecture working group - Archimate Repository 

DVS (Digitale Verwaltung Schweiz) Arbeitsgruppe Architektur - Archimate Repository

## How to use this Archimate Repository

The models are built by the working group or derived from open documentations, binding standards are the publications not the models e.g. https://www.ech.ch/de/ech/ech-0279/1.0.0

:rotating_light: **Remember, all models are wrong but some are useful** (https://www.linkedin.com/posts/ghohpe_the-secret-to-software-architecture-is-knowing-activity-7401255011059625984-_fv0/ https://archive.learnwardleymapping.com/book.html)

## branch gh-pages
This branch is used to publish the manual generated HTML Report in a separate branch. So the archi collab plugin doesn't need to check the HTML Report changes

## how to generate the html report in branch gh-pages
dont't switch branches with archi it doesn't work on MacOS
1.) publish actual model in archi to the main branch
2.) in CLI switch branch to gh-pages with: git switch gh-pages
3.) in Archi publish HTML Report with Menu File -> Report -> HTML to directory docs/
4.) in CLI add docs to source control with git add docs/
5.) in CLI commit changes to local git with  git commit -m "HTML Report generiert"
6.) in CLI push changes to remote branch git push
7.) in CLI switch branch back to main with git switch 
8.) in Archi refresh model with collab plugin

