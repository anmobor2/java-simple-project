// java-simple-project
@Library("jenkins-shared-library@main")

def PROJECT_NAME = "java-simple-project"
def EMAIL_TO_NOTIFY = "tonibandal@gmail.com"
def STOP_ON_FAILED_QG = false
def JAVA_VERSION = 17
def TEST_CONTAINERS = false
// Set the Java version dynamically (11 or 17)

simpleJavaPipeline(projectName: PROJECT_NAME,
             emailToNotify: EMAIL_TO_NOTIFY,
             stopOnFailedQG: STOP_ON_FAILED_QG,
             javaVersion: JAVA_VERSION,
             testContainers: TEST_CONTAINERS)