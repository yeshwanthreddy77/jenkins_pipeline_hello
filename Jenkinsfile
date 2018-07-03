node {
   stage 'Build'
   		echo 'Build step'
   stage 'deploy'
   		echo 'Deploy step'
   stage 'release'
   sh 'mvn release:prepare release:perform -B'
}
