### Installing a project to the local repository **for RELEASE**
`mvn -DaltDeploymentRepository=snapshot-repo::default::file:/Users/$USER/dev/maven-repo/releases clean deploy`
### Installing a project to the local repository **as a snapshot**
`mvn -DaltDeploymentRepository=snapshot-repo::default::file:/Users/$USER/dev/maven-repo/snapshots clean deploy`
