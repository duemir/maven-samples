echo "Hello Actions Pipeline!"
currentBuild.rawBuild.getActions(jenkins.scm.api.SCMRevisionAction).eachWithIndex { a, i ->
    echo "SCM Action ${i}, revision is: ${a.revision}"
}
