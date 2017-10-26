echo "Hello Causes Pipeline!"
echo "Actions Dump: ${currentBuild.rawBuild.actions.dump()}"
currentBuild.rawBuild.getActions(jenkins.scm.api.SCMRevisionAction).eachWithIndex { a, i ->
    echo "SCM Action ${i}: ${a.dump()}"
}
