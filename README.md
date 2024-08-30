


# BRK410: Copilot Implmentation Essentials

![Session cover image with a bright "AI" text in 3D over a blue and purple abstract background.](img/session-cover.png)

## Session Desciption

Deliver AI value quickly with our guide for Microsoft 365 Copilot implementations. Ensure secure, efficient rollouts with data governance and user support. This session is enriched by customer success stories.

## Learning Outcomes
Our implementation framework is easy to follow and complete​

There are tools & resources to help you at each step​

The community is here to provide ongoing assistance as you expand your ​AI capabilities

## Technology Used

## Training Resources and Continued Learning
For Training Resources :  [Training](session-delivery-resources/README.md)

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Join Driving Adoption Tech Community  | [Link 1](https://aka.ms/DriveAdoption) | Collaborate, share, and learn from experts |
| Microsoft Adoption Hub  | [Link 2](https://adoption.microsoft.com/) | Resources to help you drive adoption of Microsoft Services|

## Content Owners


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/brwoff.png" width="100px;" alt="Chris Testa-O'Neill
"/><br />
        <sub><b>Bryan Wofford
</b></sub></a><br />
            <a href="https://github.com/brwoff" title="talk">📢</a> 
    </td>
</tr></table>
<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in).

You can evaluate your AI application in your development environment using the [prompt flow SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).
