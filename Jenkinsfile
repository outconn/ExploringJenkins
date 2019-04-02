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
   office365ConnectorSend status:'Master branch', message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/52cbc58a-c583-4bfe-930a-ac5c80e2ce77@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/74004ba3eac640f1b7d459968daebb54/11a97ad3-e780-471d-abd5-0abddae8e624'
   // Run the maven build
}
