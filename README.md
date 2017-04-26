# local_manifest_sprout4
How to sync with the rom repo ? <br>
Copy and paste these commands :-<br>
go to the repo initalised source folder then<br>
cd .repo<br>
mkdir local_manifests <br>
cd local_manifests <br>
wget https://raw.githubusercontent.com/samgrande/local_manifest_sprout/master/local_manifest.xml<br>
cd ../../<br>
repo sync -j16 -f<br>
