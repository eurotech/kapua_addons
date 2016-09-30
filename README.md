# kapua_addons

Eclipse Kapua add-ons that don't belong in the Eclipse Kapua repository


How to install an artifact
--------------------------

For a specific jar:

  - Checkout the mvn-repo branch `git checkout mvn-repo` and pull the latest changes

  - From the kapua_addons root directory, run the following (substituting the appropriate values):
```mvn deploy:deploy-file -DgroupId={group.id} -DartifactId={artifact.id} -Dversion={artifact.version} -Dpackaging=jar -Dfile={file.path} -Durl=file://. ```

  - Commit the files that were added, then push to github
