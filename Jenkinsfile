// java-simple-project
@Library("jenkins-shared-libraries@main")

def PROJECT_NAME = "chatbot-companion"
def EMAIL_TO_NOTIFY = "reviewpro.pd@shijigroup.com"
def STOP_ON_FAILED_QG = false
def TEST_CONTAINERS = true
def JAVA_VERSION = 17  // Set the Java version dynamically (11 or 17)

javaPipeline(projectName: PROJECT_NAME,
             emailToNotify: EMAIL_TO_NOTIFY,
             stopOnFailedQG: STOP_ON_FAILED_QG,
             testContainers: TEST_CONTAINERS,
             javaVersion: JAVA_VERSION)