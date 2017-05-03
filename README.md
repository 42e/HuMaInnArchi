# HuMaInnArchi....

[Repository](https://github.com/42e/HumaInnArchi) for collaboratibe development of HuMaInn's holistic architecture description.

## Primary tools
- [Archi Tool](https://www.archimatetool.com/dev/beta) with support Archimate 3.0
- [Grafico](https://github.com/archi-contribs/archi-grafico-plugin) plugin
- [SourceTree](https://confluence.atlassian.com/get-started-with-sourcetree) by Atlassian
- [Git](https://en.wikipedia.org/wiki/Git) should be installed by SourceTree. If not, get it [here](https://git-scm.com/downloads)

## Basic Principles
- [Archimate 3.0](http://pubs.opengroup.org/architecture/archimate3-doc/)
- [GRAFICO](http://blog.archimatetool.com/2016/11/03/archops-a-new-paradigm-for-ea-toolsets/)
- [GIT](http://nvie.com/posts/a-successful-git-branching-model/)

## How to

### Initialize environment
1. Adopt and Follow Basic Principles
2. Istall Archi, Grafico plugin, SourceTree with GIT
3. Create local GIT repository by cloning [this remote repository on GitHub](https://github.com/42e/HumaInnArchi) for keeping "splitted & versioned" ARCHI repository XML file
4. Create local ARCHI repository (simple directory for keeping the "merged" ARCHI repository XML file)

### Round trip
1. Keep GIT local repository actual (apply all remote recorded changes) - by SourceTree
2. In Archi, choose "Import/Model from Grafico ..." and point to the GIT local repository
3. Save complete (merged) ARCHI XML repository file into
4. Maintain properly branches by SourceTree
5. Make changes (i.e. model architecture :-))
6. After work is finished, choose in ARCHI "Export/Model as Grafico ..." and point to GIT local repository. It will save changes into GIT repository.
7. Maintain properly branches by SourceTree
8. PUSH selected changes from selected branches into remote GitHub repositorz by SourceTree and solve conflicts.
9. Enjoy it!
