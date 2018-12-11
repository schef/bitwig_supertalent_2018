# bitwig_supertalent_2018

To get started with Git LFS, the following commands can be used.

 1. Setup Git LFS on your system. You only have to do this once per
    repository per machine:

        git lfs install

 2. Choose the type of files you want to track, for examples all ISO
    images, with git lfs track:

        git lfs track "*.bwproject"
        git lfs track "*.wav"
        git lfs track "*.mp3"
        git lfs track "*.pdf"
        git lfs track "*.sample"
        git lfs track "*.multisample"

 3. The above stores this information in gitattributes(5) files, so
    that file need to be added to the repository:

        git add .gitattributes

 3. Commit, push and work with the files normally:

        git add file.iso
        git commit -m "Add disk image"
        git push

