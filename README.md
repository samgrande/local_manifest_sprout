# local_manifest_sprout4
How to sync with the rom repo ? 
Copy and paste these commands :-
go to the repo initalised source folder then
cd .repo
mkdir local_manifests 
cd local_manifests 
wget https://raw.githubusercontent.com/samgrande/local_manifest_sprout/master/local_manifest.xml
cd ../../
repo sync -j16 -f
