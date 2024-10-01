// java-simple-project
@Library("jenkins-shared-libraries@main")

def PROJECT_NAME = "java-simple-project"
def EMAIL_TO_NOTIFY = "tonibandal@gmail.com"
def STOP_ON_FAILED_QG = false
def JAVA_VERSION = 17 // Set the Java version dynamically (11 or 17)
def GIT_REPO = "https://github.com/tonibandal/java-simple-project.git"

javaPipeline(projectName: PROJECT_NAME,
             emailToNotify: EMAIL_TO_NOTIFY,
             stopOnFailedQG: STOP_ON_FAILED_QG,
             javaVersion: JAVA_VERSION,
             gitRepo: GIT_REPO)