AUTHOR - Raman Sailopal

BACKGROUND - Simple command lije script to display a summary of Jenkins jobs and their last statuses

PREREQUISITES - A working version of Jenkins

PARAMETERS -

          First parameter - The address of the Jenkins installation
          Second parameter - A username to authenticate with
          Third parameter - A password to authenticate with
          Fourth parameter (Optional) - The job to get the status for.
          If left blank, will search all jobs


USAGE EXAMPLE - jenkins-cli "jenkinserver" "testuser" "testpass"

INSTALLATION -

           git clone https://github.com/RamSailopal/jenkins-cli.git
           mv jenkins-cli/jenkins-cli /usr/local/bin
