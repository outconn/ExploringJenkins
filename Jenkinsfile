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
   office365ConnectorSend status:'Master branch', message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/109e6889-9862-4399-8610-d9bd3a707d37@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/7d3c36a78f3e40a189c41eddcb35b767/5ae8ccea-fc98-478b-9213-5e4ec50192cb'
   // Run the maven build
}
