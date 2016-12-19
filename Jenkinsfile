node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'
   office365ConnectorSend message: 'Message from pipeline script.', webhookUrl:'https://outlook.office365.com/webhook/629ef99b-ddb2-4733-adbe-f6be76767ae1@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/58804729b2344bb6b2ca9a51020879c7/a17a5cc4-4a98-4fd2-b7d6-9260e1e24fa0'

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
