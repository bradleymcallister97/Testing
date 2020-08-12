pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Starting"
                // Get some code from a GitHub repository
                git 'https://github.com/bradleymcallister97/Testing.git'

                sh "printenv"

                // sh 'git diff "$GIT_PREVIOUS_COMMIT" "$GIT_COMMIT"'
                // if [ "$GITHUB_BASE_REF" ]; then
                //     git fetch origin "$GITHUB_BASE_REF" --depth=1;
                //     echo "PR: fetching diff between origin/$GITHUB_BASE_REF and $GITHUB_SHA";
                //     git diff origin/"$GITHUB_BASE_REF" "$GITHUB_SHA" > $diff_filename;
                // else
                //     if [ "$EVENT_BEFORE" = "0000000000000000000000000000000000000000" ]; then
                //         echo "PUSH: fetching diff of initial commit";
                //         git show --format="" "$GITHUB_SHA" > $diff_filename;
                //     else
                //         git fetch origin "$EVENT_BEFORE" --depth=1;
                //         echo "PUSH: fetching diff between $EVENT_BEFORE and $GITHUB_SHA";
                //         git diff "$EVENT_BEFORE" "$GITHUB_SHA" > $diff_filename;
                //     fi;
                // fi;

                
                echo "Done"
            }
        }
    }
}
