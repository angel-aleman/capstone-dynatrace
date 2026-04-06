# Solutions Engineering Capstone

Thank you for your interest in being a part of the Solutions Engineering team at Dynatrace. As next steps we will ask you to setup and demo an environment of your choosing to the Solutions Engineering team, instrumented by the Dynatrace platform. The goal of this capstone is to showcase your technical skills, the core features of the Dynatrace platform, and your ability to present its value to various business units in one presentation.

See below for further instructions and expectations of this demo and reach out to your hiring manager with any questions.
    
---

1. Sign up for a free Dynatrace SaaS trial 
    - https://www.dynatrace.com/trial/

1. Ingest data to your environment from the source you want:
    - [Ingest data](https://docs.dynatrace.com/docs/shortlink/ingest-data-from)


1. Deploy a Web Application
    
    Setup a demo application into your environment. See below for a list of sample apps you can potentially leverage and will meet the requirements. 

    - [Astronomy Shop](https://opentelemetry.io/docs/demo/kubernetes-deployment/)
    - [Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo)
    - [EasyTrade](https://github.com/Dynatrace/easytrade)
    
    You can choose any custom application you have worked with in the past or built for this demo. 
    Requirements of the demo application, in case you want to use a different.
   
    - Front end web server (for browser RUM injection) 
    - Code level calls more advance than a "hello world" or health check 
      -  Check [Dynatrace's list of supported technologies](https://docs.dynatrace.com/docs/setup-and-configuration/technology-support) for technology compatibility
    - Application logs are generated and available (stdout by default)
    - A Database component 
    - The application must be capable of generating errors/ crashes/ outages

    
1. Configuration requirements:

    Below is a list of the requirements needed to be done to your Dynatrace environment as well as documentation links to get you started. These are intended to be challenging and highlight how your previous experience will translate to Dynatrace's Solutions Engineering team. While the Dynatrace documentation links are included, please note, these are only examples and are not specific to any demo application. There are many ways to ingest and configure data in Dynatrace.

    Required Configurations for your Demo


    Observability
    - [Logs Ingestion](https://docs.dynatrace.com/docs/analyze-explore-automate/logs/lma-log-ingestion)
    - [Metric Ingestion](https://docs.dynatrace.com/docs/analyze-explore-automate/metrics)
    - [Trace Ingestion](https://docs.dynatrace.com/docs/analyze-explore-automate/distributed-tracing/ingest-traces)

    Real User Monitoring
    - [Add a browser monitoring check to your web application](https://docs.dynatrace.com/docs/observe/digital-experience/synthetic-monitoring/browser-monitors/create-a-single-url-browser-monitor)
    - [Enable Session Replay Capture](https://docs.dynatrace.com/docs/platform-modules/digital-experience/session-replay/enable-session-replay-web)
    - [Configure conversion goals for your web application](https://docs.dynatrace.com/docs/platform-modules/digital-experience/web-applications/analyze-and-use/define-conversion-goals)

    Administration     
    - [Configure a outbound problem notification via Workflows](https://docs.dynatrace.com/docs/analyze-explore-automate/workflows/simple-workflow)
    - [Create a segment to organize your infrastructure or data](https://docs.dynatrace.com/docs/shortlink/segments)
    - [Enable Dynatrace Intelligence](https://docs.dynatrace.com/docs/discover-dynatrace/platform/davis-ai/copilot/copilot-getting-started)

    Root-cause and analysis 
   - [Create a notebook to analize a log and their content](https://docs.dynatrace.com/docs/shortlink/notebooks)
   - [Create a dashborad for analysis of services or infrastructure](https://docs.dynatrace.com/docs/shortlink/dashboards)
   - [Analyze a problem and their root cause](https://docs.dynatrace.com/docs/shortlink/dynatrace-intelligence-problems-app)
   - [Use the smartscape to analyze your services interactions](https://docs.dynatrace.com/docs/shortlink/smartscape-app)

 

1. Presentation Overview

    The primary focus of your presentation will be to demonstrate the value of the data provided by Dynatrace to multiple business units, teams and stakeholders for any given organization. For the purposes of this demo the Dynatrace Solutions Engineering team will be role playing as stake holders of a prospect in the roles of:  
    
    - C Suite Leadership 
    - Technology Operations
    - Software Development
    - DevOps
    - Site Reliability Engineer
    - Infrastructure Support
    - Business Analytics & Intelligence
    - etc

    Come prepared with these roles in mind and tailor your presentation to demonstrate how each of these teams day-to-day jobs could be different and drive better business outcomes with the Dynatrace platform. Additionally, be prepared to field live questions from these business units' stakeholders about the Dynatrace platform from their specific lens.
   `This session will take 1 hour, where 40 mins will be for your demo and 20 mins for the panel.`
    
    Demo Expectations

     The over arching theme of your presentation should hinge of the business value the above requirements will provide to your audience. Focus on business value  highlighting how the Dynatrace platform can drive revenue, reduce costs, or improve efficiency.

    - Get to know your audience. Understand the background of your audience to tailor the narrative and depth of your demo.
    - Highlight just the key features. Focus on the most important technical features and how they work, but avoid a "feature demo" 
    - Articulate the practical application of the platform. Explain how the technical features solve real-world problems for your audience.
    - Be prepared for questions & interruptions from you audience
    - Try to maintain engagement. Keep the audience engaged with interaction and encourage questions throughout the demo.
    - Highlight the value of the data provided by the Dynatrace platform to your audience
    - Incorporate how you would benefit from the Dynatrace platform & data you are presenting in your current or previous role(s) 

  
Additional configuration recommendations
    
These are not required, but it is strongly encouraged that you configure some of these. Make sure you call these out during your demo if you set them up!

- [BizEvents](https://docs.dynatrace.com/docs/shortlink/bo-business-events-capturing)
- [Log Events](https://docs.dynatrace.com/docs/dynatrace-intelligence/use-cases/create-alert-in-logs) 
- [Live Debugger](https://docs.dynatrace.com/docs/observe/applications-and-microservices/developer-observability/offering-capabilities)
- [RUM Session Properties](https://docs.dynatrace.com/docs/platform-modules/digital-experience/web-applications/additional-configuration/define-user-action-and-session-properties)
- [OpenTelemetry Ingestion](https://docs.dynatrace.com/docs/ingest-from/opentelemetry)
- [Run Time Vulnerabilites](https://docs.dynatrace.com/docs/secure/application-security/vulnerability-analytics)
- [Kubernetes Security Posture Management](https://docs.dynatrace.com/docs/ingest-from/setup-on-k8s/deployment/security-posture-management)
- [Integrate Dynatrace with a Cloud Account](https://docs.dynatrace.com/docs/platform-modules/infrastructure-monitoring/cloud-platform-monitoring)
- [AI Observability](https://docs.dynatrace.com/docs/shortlink/dynatrace-for-ai-observability)

Feel free to review the full Dynatrace product documentation on [Getting started with Dynatrace](https://docs.dynatrace.com/docs/get-started) and [Product News](https://www.dynatrace.com/news/blog/) pages and come up with your own integration ideas for you demo.

If you need additional ideas for demos, talking points or general knowledge take a look at:

- [Dynatrace YouTube Channel](https://www.youtube.com/@dynatrace)
- [Dynatrace LinkedIn](https://www.linkedin.com/company/dynatrace/posts/?feedView=all)
- [Dynatrace Playground SaaS Environment](https://wkf10640.apps.dynatrace.com/)
- [Dynatrace Blog](https://www.dynatrace.com/news/blog/)


- Have fun!   
