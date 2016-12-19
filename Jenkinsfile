node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.

   // Mark the code build 'stage'....
   stage 'Build'
   office365ConnectorSend message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office365.com/webhook/ca32e350-d0aa-461a-8e84-c01d2af86bda@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/dc20127d72394d41a24aa7cb8c262d49/a17a5cc4-4a98-4fd2-b7d6-9260e1e24fa0'
   // Run the maven build
}
