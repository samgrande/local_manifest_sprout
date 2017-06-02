# local_manifest_sprout4
How to sync with the rom repo ? <br>
Copy and paste these commands :-<br>
go to the repo initalised source folder then<br>
<ul style="list-style-type:circle">
 <li> cd .repo</li>
 <li> mkdir local_manifests </li>
 <li> cd local_manifests </li>
 <li> wget https://raw.githubusercontent.com/samgrande/local_manifest_sprout/N/sprout4.xml </li>
 <li> cd ../../</li>
 <li> repo sync -j16 -f</li>
