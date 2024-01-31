+++
title = "Streamlining DevEx: The Power of CI/CD Standardization and Interoperability"
outputs = ["Reveal"]

[reveal_hugo]
width = "80%"

+++

## Streamlining DevEx

### The Power of CI/CD Standardization and Interoperability

{{% note %}}
As a quick note, I used ChatGPT + DALL-E to generate the images in this presentation, which took entirely too much time because the effort to train the model for what I was trying to get was tedious and time consuming. 
{{% /note %}}

---

{{< slide id="bio" transition="zoom" transition-speed="fast" >}}
<section>
    <div class="multiCol">
        <div class="col">
            <h4 style="color: rgb(111, 168, 220);">Jeremy Meiss</h4>
            <p style="font-size: .75em;">Co-Founder</p>
            <p style="font-size: .75em; font-style: italic;">DevEx Startup</p>
        </div>
        <div class="col"><img src="/images/profile-pic.jpg" width="60%"></div>
    </div>
</section>

{{% note %}}
Early reviews are in....
{{% /note %}}

---

![GreyNewell tweet](/images/grey-newell-tweet.jpg "Image: @GreyNewell on Twitter")
<!-- https://twitter.com/GreyNewell/status/1737295403052126213 -->

{{% note %}}
Not so sure about heresy, seems kinda harsh, but here goes! In the rapidly evolving landscape of modern software development....  
{{% /note %}}

---

![CNCF Landscape, 29-Jan-2024](/images/slides/cncf-landscape.jpeg)
{.r-stretch}
REF: CNCF Landscape, 29-Jan-2024

{{% note %}}
...illustrated here by the CNCF landscape (as of January 29, 2024) Continuous Integration and Continuous Deployment (CI/CD) stand as transformative pillars, reshaping how software is delivered and the very experience of those crafting it.  
{{% /note %}}

---

## Developer Experience

![DevEx poll from Twitter and LinkedIn](/images/slides/devex-poll.jpg)

52% of respondents said "DevEx" (34% "DX")

---

{{< slide background-image="/images/slides/2b-d316afa9-e89f-4bb6-9bca-11f73973a99f.jpeg" background-opacity="0.3" >}}

## Developer Experience (DevEx)...
>#### ...encompasses the journey of developers as they learn and deploy technology. When successful, it focuses on eliminating obstacles that hinder a developer or practitioner from achieving success in their endeavors.

{{% note %}}
Developer Experience (DevEx) encompasses the journey of developers as they learn and deploy technology. When successful, it focuses on eliminating obstacles that hinder a developer or practitioner from achieving success in their endeavors. 

Developer Experience (DevEX) refers to developers' overall satisfaction and efficiency while working on software projects. It encompasses the tools, processes, and environments that shape developers' interactions with code, infrastructure, and each other. A positive DevEx is crucial for enhancing productivity as it directly influences how quickly and effectively developers can build, test, and deploy software.
{{% /note %}}

---

{{< slide name="CI/CD's influence" background-image="/images/slides/3-ci-cd-influence.jpeg" background-opacity="1" >}}


{{% note %}}
**CI/CD's transformative influence on DevEx** CI/CD's impact on Developer Experience (DevEx) is profound, offering a dynamic shift in how developers collaborate, create, and deliver software. By automating integration, testing, and deployment processes, CI/CD accelerates development cycles, empowering developers with faster feedback loops, improved code quality, and the ability to iterate swiftly.
{{% /note %}}

---

{{< slide background-image="/images/slides/4-streamling-workflows.jpeg" background-opacity="1" >}}

## 

{{% note %}}
By streamlining workflows, reducing friction, and providing intuitive tools, a good DevEx empowers developers to focus on creating high-quality code, fostering innovation, and ultimately contributing to faster and more reliable software delivery. In this talk, we will hone in on two critical pillars: standardization and interoperability. 
{{% /note %}}

---

{{< slide background-image="/images/slides/5-standardization-consistency.jpeg" background-opacity=".3" >}}

### CI/CD Standardization

{{% note %}}
CI/CD standardization brings consistency to development pipelines, reducing friction and enhancing collaboration. We'll also be looking at what a few prominent open-source tools (Argo and Flux) offer in their feature sets and practices that offer some real benefits toward CI/CD standardization.
{{% /note %}}

---

{{< slide background-image="/images/slides/6-interoperability.jpeg" background-opacity=".3" >}}

### CI/CD Interoperability

{{% note %}}
Concurrently, interoperability ensures seamless integration across diverse toolsets, fostering flexibility in development environments. So we'll look at how Spinnaker integrates harmoniously with tools like Backstage, bridging toolchain gaps and promoting adaptability.

Together, they both play pivotal roles in optimizing DevEx and improving overall productivity in the software development lifecycle.
{{% /note %}}

---

{{< slide background-image="/images/slides/7-implement-standardization.jpeg" background-opacity="0.4" >}}

## Implementing CI/CD Standardization

{{% note %}}
CI/CD Standardization aims to minimize variability, reduce errors, and foster an environment where developers can efficiently collaborate. Standardizing CI/CD can be achieved by defining clear, repeatable code integration, testing, and deployment processes, ensuring a smooth development journey. Implementing CI/CD pipeline standardization is crucial for streamlining the development process and enhancing Developer Experience (DevEx). Here are the steps and best practices for achieving pipeline standardization:
{{% /note %}}

---

{{< slide background-image="/images/slides/8-assessment-analysis.jpeg" background-opacity="0.3" >}}

### Implementing CI/CD Standardization
#### Assessment and Analysis

- Thoroughly assess your current CI/CD pipelines
- Identify pain points and bottlenecks
- Analyze specific requirements and constraints

{{% note %}}
- Begin by thoroughly assessing your current CI/CD pipelines. Understand the existing workflows, tools, and processes in use.
- Identify pain points, bottlenecks, and areas where standardization is needed.
- Analyze the specific requirements and constraints of your projects and development teams.
{{% /note %}}

---

{{< slide background-image="/images/slides/9-define-goals.jpeg" background-opacity="0.3" >}}

### Implementing CI/CD Standardization
#### Define Standardization Goals

- Define goals and objectives, align with strategy and objectives
- Determine success, like reduced deployment times / error rates

{{% note %}}
- Clearly define the goals and objectives of pipeline standardization. These goals should align with the overall development strategy and business objectives.
- Determine the key performance indicators (KPIs) that will measure the success of standardization efforts, such as reduced deployment times or decreased error rates.
{{% /note %}}

---

{{< slide background-image="/images/slides/10-picking-tools-practices.jpeg" background-opacity="0.4" >}}

### Implementing CI/CD Standardization
#### Select Standardization Tools and Practices

- Choose tools & practices aligned with organization needs, goals
- Establish standard templates and configurations for pipelines
- Enforce coding standards for consistency and readability

{{% note %}}
- Choose CI/CD tools and practices that align with your organization's needs and goals. Consider tools like Jenkins, GitLab CI/CD, or cloud-native solutions like AWS CodePipeline.
- Establish standardized templates for pipelines, defining the essential stages (e.g., build, test, deploy) and standard configurations.
- Enforce coding standards for CI/CD configurations, ensuring consistency and readability.
{{% /note %}}

---

{{< slide background-image="/images/slides/11-docs-and-training.jpeg" background-opacity="0.4" >}}

### Implementing CI/CD Standardization
#### Documentation and Training

- Create comprehensive docs for processes, configs, best practices
- Provide training to ensure understanding and effective use

{{% note %}}
- Create comprehensive documentation that outlines the standardized CI/CD processes, including workflows, configurations, and best practices.
- Provide training sessions for development teams to ensure they understand and can effectively use the standardized CI/CD pipeline templates.
{{% /note %}}

---

{{< slide background-image="/images/slides/12-version-control.jpeg" background-opacity="0.3" >}}

### Implementing CI/CD Standardization
#### Version Control

- Store pipeline configs as code in version control systems
- Implement branching and pull request strategies

{{% note %}}
- Store CI/CD pipeline configurations as code in version control systems (e.g., Git). This practice ensures that configurations are versioned, traceable, and easily revertible.
- Implement branching and pull request strategies to manage changes to CI/CD configurations.
{{% /note %}}

---

{{< slide background-image="/images/slides/13-auto-testing-validate.jpeg" background-opacity="0.4" >}}

### Implementing CI/CD Standardization
#### Automated Testing and Validation

- Integrate automated testing and validation into templates
- Implement code reviews and peer validation early in dev process

{{% note %}}
- Integrate automated testing and validation into the pipeline templates to ensure that standardized configurations produce expected results.
- Implement code reviews and peer validation to catch configuration errors early in the development process.
{{% /note %}}

---

{{< slide background-image="/images/slides/14-monitoring-and-improvement.jpeg" background-opacity="0.4" >}}

### Implementing CI/CD Standardization
#### Continuous Monitoring and Improvement

- Detect pipeline issues and bottlenecks in real-time 
- Establish culture of regular reviews and updating pipelines

{{% note %}}
- Set up monitoring and alerting for your CI/CD pipelines to detect issues and bottlenecks in real-time.
- Establish a culture of continuous improvement by regularly reviewing and updating standardized pipelines based on feedback and evolving project requirements.
{{% /note %}}

---

{{< slide background-image="/images/slides/15-governance-compliance.jpeg" background-opacity="0.3" >}}

### Implementing CI/CD Standardization
#### Governance and Compliance

- Implement governance policies to enforce pipeline standards
- Validate compliance with industry regulations / internal standards
- Regularly audit and assess adherence to standardized practices

{{% note %}}
- Implement governance policies to enforce pipeline standardization and compliance with industry regulations or internal standards.
- Regularly audit and assess the adherence to standardized practices.
{{% /note %}}

---

{{< slide background-image="/images/slides/16-scaling-adaptation.jpeg" background-opacity="0.3" >}}

### Implementing CI/CD Standardization
#### Scaling and Adaptation

- Ensure standardized templates can scale and adapt
- Maintain flexibility to accommodate unique project requirements

{{% note %}}
- Ensure that the standardized pipeline templates can scale and adapt to different project types, sizes, and technologies.
- Maintain flexibility to accommodate unique project requirements while adhering to standardized core practices.
{{% /note %}}

---

{{< slide background-image="/images/slides/17-feedback-collaboration.jpeg" background-opacity="0.3" >}}

### Implementing CI/CD Standardization
#### Feedback Loop and Collaboration

- Foster collaborative environments where feedback & contributions encouraged
- Continuously communicate benefits of standardized pipelines & celebrate successes

{{% note %}}
- Foster a collaborative environment where developers can provide feedback and contribute to improving CI/CD standardization practices.
- Continuously communicate the benefits of standardized pipelines and celebrate successes.

By following these steps and best practices, organizations can successfully implement CI/CD pipeline standardization, resulting in more efficient and consistent development workflows, improved Developer Experience, and ultimately, faster and more reliable software delivery.

Let's look at how open source tooling Argo and Flux implement CI/CD pipeline standardization: 
{{% /note %}}

---

{{< slide background-image="/images/slides/18-argo-pipeline-standardization.jpeg" background-opacity="0.3" >}}

### CI/CD Pipeline Standardization
#### Argo

<p class="fragment"><strong>Reusable workflows:</strong> orgs define reusable workflow templates</p>
<p class="fragment"><strong>GitOps principles:</strong> CI/CD configs & workflows managed as code</p>
<p class="fragment"><strong>Artifact Management Support:</strong> artifacts managed & stored for consistency</p>

{{% note %}}
**Reusable workflows:** Orgs can define reusable workflow templates, setting up standard sequences for CI/CD (build, test, deploy), so devs can reuse across projects for consistent & standardized CI/CD processes.  
**GitOps principles:** Argo follows GitOps principles, where CI/CD configs and workflows are managed as code in Git repos, ensuring versioned, traceable, and easy processes to collab amongst dev teams.  
**Artifact Management:** Argo supports managing & storing artifacts, such as Docker images, as part of the CI/CD process, ensuring the right artifacts are consistently deployed across environments & able to be used as inputs to subsequent steps.
{{% /note %}}

---

{{< slide background-image="/images/slides/19-flux-pipeline-standardization.jpeg" background-opacity="0.3" >}}

### CI/CD Pipeline Standardization
#### Flux

<p class="fragment"><strong>Declarative config model, i.e. "GitOps":</strong> desired system state defined in code</p>
<p class="fragment"><strong>Continuous Synchronization:</strong> desired state with actual state in K8s clusters</p>
<p class="fragment"><strong>Customized Deployments (via Flagger)</strong> feature-flagged deployments</p>

{{% note %}}
**Declarative Configuration:** operates on a declarative config model, where system's desired state is defined as code, enabling orgs to define & enforce standardized CI/CD practices in a VCS, ensuring trackable project consistency.  
**Continuous Synchronization:** continuously synchronize desired state in Git repos w/ the actual state of the K8s cluster, ensuring standardied configs & deployments are consistent across environments, regardless of changes.  
**Policy-Based Deployments:** supports custom deployment policies, allowing orgs to define rules for when & how deployments should occur, ensuring better practices & adhering to org standards.
{{% /note %}}

---

{{< slide background-image="/images/slides/24-achieving-standards.jpeg" background-opacity="0.3" >}}

### Achieving Standardized Workflows

<p class="fragment"><strong>Argo & Flux:</strong> encourage standardized templates/definitions</p>
<p class="fragment"><strong>VCS & CI/CD Integrations:</strong> ensures configs maintained and accessible to all</p>
<p class="fragment"><strong>Documentation & Training:</strong> responsibility of org for devs understanding process</p>
<p class="fragment"><strong>Continuous Improvement:</strong> foster continual improvement & gathering feedback</p>


{{% note %}}
So in summary, achieving standardized workflows comes down to the following:
**Templates & Definitions:** With the standardized pipeline templates and definitions that Flux and Argo employ, orgs establish the baseline for consistency, which promotes a streamlined and efficient dev process.  
**Integrations:** Fully integrating with VCS & CI/CD tooling ensures configs maintained and accessible to all  
**Documentation and Training:** docs and training so essential to standardization. Orgs are responsible for making sure devs understand how to use the workflows effectively.  
**Continuous Improvement:** Foster culture by regularly reviewing and updating workflows, encouraging feedback and suggesting improvements. This helps ensure that standardized practices remain relevant and practical.
{{% /note %}}

---

{{< slide background-image="/images/slides/28-interoperability.jpeg" background-opacity="0.4" >}}

## The Role of Interoperability

{{% note %}}
Interoperability in CI/CD (Continuous Integration and Continuous Delivery) systems refers to the ability of different tools, technologies, and components within a CI/CD ecosystem to work seamlessly together. It ensures that various CI/CD pipeline parts, including source code repositories, build systems, testing frameworks, deployment platforms, and monitoring tools, can communicate, integrate, and exchange data effectively without compatibility issues or disruptions.

The importance of interoperability in CI/CD systems for collaboration is multifaceted:
{{% /note %}}

---

{{< slide background-image="/images/slides/29-interoperability-collab.jpeg" background-opacity="0.3" >}}

### Interoperability advantages
#### Collaboration

<p class="fragment"><strong>Flexibility and Choice:</strong> prevents vendor lock-in</p>
<p class="fragment"><strong>Enhanced Collaboration:</strong> enables effective inter-team collaboration</p>
<p class="fragment"><strong>Ecosystem Integration:</strong> streamlines comms, sharing, coordination</p>
<p class="fragment"><strong>Resource Utilization:</strong> make efficient use of existing infra / tools</p>
<p class="fragment"><strong>Scalability and Growth:</strong> allows for new tech and practices into workflows</p>
<p class="fragment"><strong>Cross-Platform Deploys:</strong> promotes unified deployment / infra mgmt approach</p>
<p class="fragment"><strong>Troubleshooting and Debugging:</strong> enables better incident response</p>


{{% note %}}
**Flexibility & Choice:** Interop enables development teams use best tool for job, preventing vendor lock-in  
**Enhanced Collaboration:** Various tool prefs within org / company is not a blocker. Ensures smoothly interaction, facilitating collab & comms  
**Ecosystem Integration:** Interoperable CI/CD systems integrate w/ broader ecosystems  
**Resource Utilization:** Allows orgs to make the most efficient use of existing infra & tools. Reuse components / scripts, etc.  
**Scalability & Growth:** As orgs scale / adopt new tech, interop ensures  CI/CD systems can adapt & expand, supporting incorporating new tools / practices => existing workflows.  
**Cross-Platform Deployment:** In multi-cloud / hybrid environments, promtes unified approach to deployment & infra mgmt.  
**Troubleshooting & Debugging:** When issues arise, interop enables seamless data sharing between various tools & components, for quicker issue ID, troubleshooting, and resolution.
{{% /note %}}

---

{{< slide background-image="/images/slides/30-interop-bridge.jpeg" background-opacity="1" >}}



{{% note %}}
In essence, CI/CD systems interoperability acts as a bridge, connecting different parts of the development and delivery process, fostering collaboration, and ensuring that teams can work cohesively and efficiently, even when using diverse toolsets and technologies. This flexibility and adaptability are essential for modern software development, where agility and collaboration are paramount.
{{% /note %}}

---

{{< slide background-image="/images/slides/31-interop-diverse-toolsets.jpeg" background-opacity="0.4" >}}

### Interoperability
#### Spinnaker & Backstage

{{% note %}}
Interoperability in action with Spinnaker and Backstage demonstrates how these tools effectively integrate and collaborate within a CI/CD ecosystem, while also bridging the gap between the diverse toolsets organizations, and the developers and operators tasked with implementing them, are using. This interoperability offers enhanced flexibility in CI/CD and software development.
{{% /note %}}

---

{{< slide background-image="/images/slides/32-interop-spinnaker.jpeg" background-opacity="0.3" >}}

### Interoperability: Spinnaker

<p class="fragment"><strong>Integration with Cloud Providers:</strong> broad integration options</p>
<p class="fragment"><strong>VCS Integrations:</strong> enable trigger deployment pipelines automation</p>
<p class="fragment"><strong>Extensibility:</strong> useful integrations, like monitoring, incident mgmt, etc.</p>
<p class="fragment"><strong>Artifact Management:</strong> deploy the right artifacts, enhancing reliability</p>
<p class="fragment"><strong>Pipeline Abstraction:</strong> flexible / adaptable process as reqs evolve</p>


{{% note %}}
**Integration w/ Cloud Providers:** Spinnaker is known for its integrations w/ various cloud providers, providing a consistent interface for deploying/managing across platforms, ensuring seamlessly targeting of environments for devs. Choose what works best.  
**Integration w/ VCS:** Integrations w/ VCS enables trigger deployment pipelines directly from repos, automating release process & reducing manual intervention.  
**Extensible Integrations:** Extensible arch supports many integrations, allowing teams to connect w/ various ext tools, like monitoring, incident mgmt, scripts, etc. Flexibility ensures Spinnaker can seamlessly fit into org's existing toolset, requirements, & workflows.  
**Artifact Management:** Artifact repo integration, Docker Hub / Artifactory, assist in managing various artifacts, ensuring the right artifacts are consistently deployed across environments, enhancing CI/CD reliability.  
**Pipeline Abstraction:** Abstracting deployments make the process flexible & adaptable. Devs can reuse templates, making adaptation easier as project reqs evolve. This bridge between abstraction & flexibility ensures Spinnaker can cater to various deployment scenarios.
{{% /note %}}

---

{{< slide background-image="/images/slides/33-interop-backstage.jpeg" background-opacity="0.4" >}}

### Interoperability: Backstage

<p class="fragment"><strong>Integration with CI/CD Tools:</strong> allows single-pane-of-glass view of pipelines</p>
<p class="fragment"><strong>Service Catalog Integration:</strong> teams have full view into available services & apps</p>
<p class="fragment"><strong>Plugin Ecosystem:</strong> extensible architecture to connect tools and adapt to needs</p>
<p class="fragment"><strong>Customization and Theming:</strong> organize everything to exact needs, easier to adopt</p>

{{% note %}}
**Integration with CI/CD Tools:** Backstage integrates w/ various CI/CD tools, including Jenkins, CircleCI, GitHub Actions, Flux, and Argo. This interoperability allows devs to visualize & manage their CI/CD pipelines directly from the Backstage platform, providing a unified view of the entire development workflow.  
**Service Catalog Integration:** Acting as a service catalog, helps teams manage & discover their services & apps. Its interoperability w/ CI/CD systems ensures CI/CD information is integrated into the service catalog, making it easier for teams to understand service status & history.  
**Plugin Ecosystem:** An extensible architecture allows custom plugin & integration creation, enabling orgs to connect w/ a wide range of internal & external tools, adapting to their specific needs & enhancing the overall Developer Experience.  
**Customization and Theming:** Allowing orgs to customize the UI & theme makes it adaptable to specific branding & design preferences. This flexibility ensures alignment with an org's unique requirements & workflows, enhancing its overall appeal & usability.  
{{% /note %}}

---

{{< slide background-image="/images/slides/34-interop-flexibility.jpeg" background-opacity="1" >}}


{{% note %}}
Spinnaker and Backstage both prioritize flexibility and adaptability, allowing organizations to integrate with diverse toolsets and accommodate varying development needs. By bridging gaps between different technologies and systems, they act as central hubs that connect other parts and enhance the flexibility of CI/CD pipelines and developer workflows, ultimately promoting a more efficient and collaborative development environment.
{{% /note %}}

---

{{< slide background-image="/images/slides/35-interop-roadblocks.jpeg" background-opacity="0.4" >}}

### Challenges implementing interoperability

<p class="fragment"><strong>Diverse Toolsets & Ecosystems:</strong> seamless integration challenging</p>
<p class="fragment"><strong>Data Format & Schema Differences:</strong> disrupt compatibility and communication</p>
<p class="fragment"><strong>Authentication and Authorization:</strong> complexity with methods and permissions</p>
<p class="fragment"><strong>Versioning and Compatibility:</strong> breaking changes require ongoing maintenance</p>
<p class="fragment"><strong>Lack of Documentation:</strong> insufficient or outdated docs = common roadblock</p>


{{% note %}}
**Diverse Toolsets:** Organizations often use a mix of CI/CD tools, each with its own ecosystem and APIs, making it challenging to ensure seamless integration.  
**Data Format and Schema Differences:** Tools may use different data formats or schemas for configuration and communication, leading to compatibility issues.  
**Authentication and Authorization:** Integrating tools may require handling various authentication methods and managing permissions, which can be complex.  
**Versioning and Compatibility:** Changes in tool versions can break existing integrations, necessitating ongoing maintenance.  
**Lack of Documentation:** Insufficient or outdated documentation for APIs and integrations can hinder the development of interoperable solutions.  
{{% /note %}}

---

{{< slide background-image="/images/slides/36-interop-overcoming.jpeg" background-opacity="0.4" >}}

### Overcoming these hurdles

<p class="fragment"><strong>Unified Data Formats:</strong> document & enforce deployment pipeline requirements</p>
<p class="fragment"><strong>API Gateways:</strong> translate data, simplify authn / authz </p>
<p class="fragment"><strong>Version Compatibility:</strong> version matrices of supported versions & tool updates</p>
<p class="fragment"><strong>Docs and Dev Resources:</strong> thorough updated docs + forums & dedicated support</p>
<p class="fragment"><strong>Continuous Testing:</strong> automate testing of integrations between all tools + pipelines</p>
<p class="fragment"><strong>Community Collab:</strong> share successes & challenges within tooling communities </p>

{{% note %}}
**Unified Data Formats:** unified config format for defining deployment pipelines that are documented and enforced for all. Tools and libraries can automatically convert between formats, ensuring data consistency & compatibility.  
**API Gateways:** API gateways translate data between systems for consistency, and can simplify authentication / authorization across different toolsets.  
**Version Compatibility:** Maintain version compatibility matrices, list supported versions of all tools & libraries. Prioritize updates & ensure integrations remain compatible with tools.  
**Documentation & Developer Resources:** Invest in thorough & up-to-date docs for all integration points. Establish dev resources, such as forums or dedicated support channels, where teams can seek assistance & share best practices.  
**Continuous Testing:** Automate testing of integrations between all tools (where possible) & CI/CD tools. Also include in pipeline to catch compatibility issues early.  
**Community Collab:** Encourage collaboration & information sharing within your tooling communities to address interoperability challenges together. Share successes & case studies of your integrations to inspire others.
{{% /note %}}

---

{{< slide background-image="/images/slides/37-efficiences.jpeg" background-opacity="1" >}}

{{% note %}}
By applying these strategies and tips, organizations can overcome the common interoperability challenges and establish robust connections between Spinnaker, Backstage, and other CI/CD tools, fostering a more seamless and integrated development ecosystem.The efficiencies gained by making sure you're using tools that provide CI/CD standardization as well as being interoperable between all of the systems your developers are using is at the core of what Developer Experience really is about… 
{{% /note %}}

---

{{< slide background-image="/images/slides/37-efficiences.jpeg" background-opacity="0.3" >}}

>### "ruthlessly eliminating barriers (and blockers) that keep your developers from being successful"

{{% note %}}
ruthlessly eliminating barriers (and blockers) that keep your developers from being successful.
{{% /note %}}

---

{{< slide id="end" >}}
<section>
    <div class="multiCol">
        <div class="col">
            <h2 style="color: #04aa51; text-shadow: none;">Thank You.</h2>
            <img src="/images/slides/generic-DevEx-talk-qrcode.png" alt="DevEx Talk QR Code" style="width: 100%; max-width: 200px; margin: 0 auto;">
            <a href="https://bit.ly/DevExTalk/">https://bit.ly/DevExTalk</a>
        </div>
        <div class="col" align="center"></div>
        <div class="col" align="left" style="font-size: .5em;">
            <img src="/images/linkedin.png" height="50px" style="vertical-align: middle; margin: 10px;">/in/jeremymeiss<br />
            <img src="/images/twitter.png" height="50px" style="vertical-align: middle; margin: 10px;">@IAmJerdog<br />
            <img src="/images/devto.png" height="50px" style="vertical-align: middle; margin: 10px;">@jerdog<br />
            <img src="/images/mastodon.png" height="50px" style="vertical-align: middle; margin: 10px;">@jerdog@hachyderm.io
        </div>
    </div>
</section>

{{% note %}}

{{% /note %}}
 