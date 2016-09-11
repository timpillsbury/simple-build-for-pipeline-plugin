properties properties: [pipelineTriggers([]), [$class: 'GithubProjectProperty', displayName: 'Jenkins']]
node {

    env = [
        FOO : 42,
        BAR : "YASS"
    ]

    before_script = "echo before"
    script = 'echo after $FOO'
    
    notifications = [
        email : "mneale@cloudbees.com"    
    ]
    
   stage ('stage 1') {
      echo "hello from stage 1"
   }
}
