+++
title = "Streamlining DevEx: The Power of CI/CD Standardization and Interoperability"
outputs = ["Reveal"]

[reveal_hugo]
width = "80%"

+++

## Streamlining DevEx

### The Power of CI/CD Standardization and Interoperability

---

![GreyNewell tweet](/images/grey-newell-tweet.jpg "Image: @GreyNewell on Twitter")
<!-- https://twitter.com/GreyNewell/status/1737295403052126213 -->

---
{{< slide background-image="/images/slides/1-d3fd3e68-8b83-4cd0-b705-6dad4e5d7691.webp" background-opacity="1" >}}

<!-- ## Impact of CI/CD on modern software development and DX -->

{{% note %}}
In the rapidly evolving landscape of modern software development, Continuous Integration and Continuous Delivery (CI/CD) stand as transformative pillars, reshaping how software is delivered and the very experience of those crafting it.  
{{% /note %}}

---

{{< slide background-image="/images/slides/2b-d316afa9-e89f-4bb6-9bca-11f73973a99f.webp" background-opacity="0.5" >}}

## Definition of DevEX

{{% note %}}
Developer Experience (DX) refers to developers' overall satisfaction and efficiency while working on software projects. It encompasses the tools, processes, and environments that shape developers' interactions with code, infrastructure, and each other. A positive DX is crucial for enhancing productivity as it directly influences how quickly and effectively developers can build, test, and deploy software.
{{% /note %}}

---

{{< slide name="CI/CD's influence" background-image="/images/slides/3-ci-cd-influence.png" background-opacity="1" >}}



{{% note %}}
**CI/CD's transformative influence on DX** CI/CD's impact on Developer Experience (DX) is profound, offering a dynamic shift in how developers collaborate, create, and deliver software. By automating integration, testing, and deployment processes, CI/CD accelerates development cycles, empowering developers with faster feedback loops, improved code quality, and the ability to iterate swiftly.
{{% /note %}}

---

{{< slide background-image="/images/slides/4-streamling-workflows.png" background-opacity="1" >}}

## 

{{% note %}}
By streamlining workflows, reducing friction, and providing intuitive tools, a good DX empowers developers to focus on creating high-quality code, fostering innovation, and ultimately contributing to faster and more reliable software delivery. In this talk, we will hone in on two critical pillars: standardization and interoperability. 
{{% /note %}}

---

{{< slide background-image="/images/slides/5-standardization-consistency.png" background-opacity="1" >}}

### CI/CD Standardization

{{% note %}}
CI/CD standardization brings consistency to development pipelines, reducing friction and enhancing collaboration. We'll also be looking at what a few prominent open-source tools (Argo and Flux) offer in their feature sets and practices that offer some real benefits toward CI/CD standardization.
{{% /note %}}

---

{{< slide background-image="/images/slides/6-interoperability.webp" background-opacity="1" >}}


{{% note %}}
**Interoperability** Concurrently, interoperability ensures seamless integration across diverse toolsets, fostering flexibility in development environments. So we'll look at how Spinnaker integrates harmoniously with tools like Backstage, bridging toolchain gaps and promoting adaptability.

Together, they both play pivotal roles in optimizing DX and improving overall productivity in the software development lifecycle.
{{% /note %}}

---

{{< slide background-image="/images/slides/7-implement-standardization.png" background-opacity="1" >}}

## Implementing CI/CD Standardization

{{% note %}}
CI/CD Standardization aims to minimize variability, reduce errors, and foster an environment where developers can efficiently collaborate. Standardization can be achieved by defining clear, repeatable code integration, testing, and deployment processes, ensuring a smooth development journey. Implementing CI/CD pipeline standardization is crucial for streamlining the development process and enhancing Developer Experience (DX). Here are the steps and best practices for achieving pipeline standardization:
{{% /note %}}

---

{{< slide background-image="/images/slides/8-assessment-analysis.png" background-opacity="0.5" >}}

### Assessment and Analysis

- Thoroughly assess your current CI/CD pipelines
- Identify pain points and bottlenecks
- Analyze specific requirements and constraints

{{% note %}}
- Begin by thoroughly assessing your current CI/CD pipelines. Understand the existing workflows, tools, and processes in use.
- Identify pain points, bottlenecks, and areas where standardization is needed.
- Analyze the specific requirements and constraints of your projects and development teams.
{{% /note %}}

---

{{< slide background-image="/images/slides/9-define-goals.png" background-opacity="0.5" >}}

### Define Standardization Goals

- Define goals and objectives, aligned with strategy and objectives
- Determine success, like reduced deployment times / error rates

{{% note %}}
- Clearly define the goals and objectives of pipeline standardization. These goals should align with the overall development strategy and business objectives.
- Determine the key performance indicators (KPIs) that will measure the success of standardization efforts, such as reduced deployment times or decreased error rates.
{{% /note %}}

---

{{< slide background-image="/images/slides/10-picking-tools-practices.png" background-opacity="0.5" >}}

### Select Standardization Tools and Practices

- Choose tools & practices aligned with organization needs, goals
- Establish standard templates and configurations for pipelines
- Enforce coding standards for consistency and readability

{{% note %}}
- Choose CI/CD tools and practices that align with your organization's needs and goals. Consider tools like Jenkins, GitLab CI/CD, or cloud-native solutions like AWS CodePipeline.
- Establish standardized templates for pipelines, defining the essential stages (e.g., build, test, deploy) and standard configurations.
- Enforce coding standards for CI/CD configurations, ensuring consistency and readability.
{{% /note %}}

---

{{< slide background-image="/images/slides/11-docs-and-training.png" background-opacity="0.5" >}}

### Documentation and Training

- Create comprehensive docs for processes, configs, best practices
- Provide training to ensure understanding and effective use

{{% note %}}
- Create comprehensive documentation that outlines the standardized CI/CD processes, including workflows, configurations, and best practices.
- Provide training sessions for development teams to ensure they understand and can effectively use the standardized CI/CD pipeline templates.
{{% /note %}}

---

{{< slide background-image="/images/slides/12-version-control.png" background-opacity="0.5" >}}

### Version Control

- Store pipeline configs as code in version control systems (e.g., Git)
- Implement branching and pull request strategies to manage changes

{{% note %}}
- Store CI/CD pipeline configurations as code in version control systems (e.g., Git). This practice ensures that configurations are versioned, traceable, and easily revertible.
- Implement branching and pull request strategies to manage changes to CI/CD configurations.
{{% /note %}}

---

{{< slide background-image="/images/slides/13-auto-testing-validate.png" background-opacity="0.5" >}}

### Automated Testing and Validation

- Integrate automated testing and validation into templates
- Implement code reviews and peer validation early in dev process

{{% note %}}
- Integrate automated testing and validation into the pipeline templates to ensure that standardized configurations produce expected results.
- Implement code reviews and peer validation to catch configuration errors early in the development process.
{{% /note %}}

---

{{< slide background-image="/images/slides/14-monitoring-and-improvement.png" background-opacity="0.5" >}}

### Continuous Monitoring and Improvement

- Detect pipeline issues and bottlenecks in real-time 
- Establish culture of regular reviews and updating pipelines

{{% note %}}
- Set up monitoring and alerting for your CI/CD pipelines to detect issues and bottlenecks in real-time.
- Establish a culture of continuous improvement by regularly reviewing and updating standardized pipelines based on feedback and evolving project requirements.
{{% /note %}}

---

{{< slide background-image="/images/slides/15-governance-compliance.png" background-opacity="0.5" >}}

### Governance and Compliance

- Implement governance policies to enforce pipeline standards
- Validate compliance with industry regulations / internal standards
- Regularly audit and assess adherence to standardized practices

{{% note %}}
- Implement governance policies to enforce pipeline standardization and compliance with industry regulations or internal standards.
- Regularly audit and assess the adherence to standardized practices.
{{% /note %}}

---

{{< slide background-image="/images/slides/16-scaling-adaptation.png" background-opacity="0.5" >}}

### Scaling and Adaptation

- Ensure standardized templates can scale and adapt
- Maintain flexibility to accommodate unique project requirements

{{% note %}}
- Ensure that the standardized pipeline templates can scale and adapt to different project types, sizes, and technologies.
- Maintain flexibility to accommodate unique project requirements while adhering to standardized core practices.
{{% /note %}}

---

{{< slide background-image="/images/slides/17-feedback-collaboration.png" background-opacity="0.5" >}}

### Feedback Loop and Collaboration

- Foster collaborative environments where providing feedback and contributions is encouraged
- Continuously communicate benefits of standardized pipelines and celebrate successes

{{% note %}}
- Foster a collaborative environment where developers can provide feedback and contribute to improving CI/CD standardization practices.
- Continuously communicate the benefits of standardized pipelines and celebrate successes.

By following these steps and best practices, organizations can successfully implement CI/CD pipeline standardization, resulting in more efficient and consistent development workflows, improved Developer Experience, and ultimately, faster and more reliable software delivery.

Let's look at how open source tooling Argo and Flux implement CI/CD pipeline standardization: 
{{% /note %}}

---

### Argo CD
#### `WorkflowTemplate`

```yaml
apiVersion: argoproj.io/v1alpha1
kind: WorkflowTemplate
metadata:
  name: workflow-template-submittable
spec:
  arguments:
    parameters:
      - name: message
        value: hello world
  templates:
    - name: whalesay-template
      inputs:
        parameters:
          - name: message
      container:
        image: docker/whalesay
        command: [cowsay]
        args: ["{{inputs.parameters.message}}"]
```
REF: https://argo-workflows.readthedocs.io/en/latest/workflow-templates/

{{% note %}}
**workflow templates (3 minutes):**
- Organizations can define reusable workflow templates in Argo. 
- These templates encapsulate standardized sequences of CI/CD steps, including building, testing, and deploying applications.
- Developers can easily reuse these templates across projects, ensuring a consistent and standardized CI/CD process.
{{% /note %}}

---

### Argo CD
#### GitOps Principles

![Argo CD architecture](/images/slides/argocd_architecture.webp)
{.r-stretch}
REF: https://argo-cd.readthedocs.io/en/stable/operator-manual/architecture/

{{% note %}}
 - Argo follows GitOps principles, where CI/CD configurations and workflows are managed as code in Git repositories.
 - This approach ensures that standardized CI/CD practices are versioned, traceable, and easy to collaborate among development teams.
{{% /note %}}

---

### Argo CD
#### Artifact Management Support

![Argo CD Artifact Repo support](/images/slides/argocd-artifact-repo-support.png)
{.r-stretch}
REF: https://argo-workflows.readthedocs.io/en/latest/configure-artifact-repository/

{{% note %}}
**Artifact Management (2 minutes):**
- Argo provides support for managing and storing artifacts, such as Docker images, as part of the CI/CD process.
- Standardized artifact management practices ensure that the right artifacts are consistently deployed across environments, and able to be used as inputs to subsequent steps.
{{% /note %}}

---

### Flux CD
#### Declarative model, i.e. "GitOps"

![Flux declarative model](/images/slides/flux-declarative-config.png)
{.r-stretch}
REF: https://fluxcd.io/flux/concepts/

{{% note %}}
**Declarative Configuration (3 minutes):** Core Concepts | Flux
- Flux operates based on a declarative configuration model, where the system's desired state is defined as code.
- This declarative approach enables organizations to define and enforce standardized CI/CD practices as code, ensuring project consistency.
{{% /note %}}

---

### Flux CD
#### Continuous Synchronization

![Flux CD Continuous Sync](/images/slides/awstutorials-flux-cd-diagram.png)
{.r-stretch}
REF: https://www.awstutorials.cloud/post/tutorials/flux-multi-stage/

{{% note %}}
**Continuous Synchronization (2 minutes):** continuously synchronizes
- As a core principle of GitOps, Flux continuously synchronizes the desired state in Git repositories with the actual state of the Kubernetes cluster.
- This automation ensures that standardized configurations and deployments are consistently applied, regardless of changes in the cluster.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### Flux CD
#### Customized Deployments (via Flagger)

![Customized Deployments (via Flagger)](/images/slides/flux-deployment-strategies.png)
{.r-stretch}
REF: https://fluxcd.io/flagger/usage/deployment-strategies/

{{% note %}}
**Policy-Based Deployments (2 minutes):**
- Flux supports custom deployment policies, allowing organizations to define rules for when and how deployments should occur.
- Standardized policies ensure deployments follow best practices and adhere to organizational standards.
{{% /note %}}

---

{{< slide background-image="/images/slides/24-achieving-standards.png" background-opacity="0.5" >}}

### Achieving Standardized Workflows
#### Argo and Flux in Action

- Encourage use of standardized pipeline templates / definitions
- Templates standardize CI/CD stages and reusable for consistency

{{% note %}}
By leveraging tools like Argo and Flux, organizations can establish and maintain standardized workflows, ensuring that CI/CD practices are consistent, repeatable, and adaptable to a variety of projects. This promotes a streamlined and efficient development process, enhancing Developer Experience and software delivery.

**Templates and Definitions (3 minutes):**
   - Organizations using both Argo and Flux can establish standardized pipeline templates and definitions.
   - These templates can specify standard CI/CD stages, such as building, testing, and deploying, and can be reused across projects, ensuring consistency.
{{% /note %}}

---

{{< slide background-image="/images/slides/25-achieving-standard-integration.png" background-opacity="0.5" >}}

### Achieving Standardized Workflows
#### Argo and Flux Integration

- Integration with VCS & CI/CD tools ensures configs maintained and accessible to all

{{% note %}}
**Integration (2 minutes):**
- Integrating Argo and Flux with version control systems and other CI/CD tools ensures that standardized configurations are maintained as code and are accessible to development teams.
{{% /note %}}

---

{{< slide background-image="/images/slides/26-achieving-standard-docs.png" background-opacity="0.5" >}}

### Achieving Standardized Workflows
#### Documentation and Training

- Comprehensive docs and training essential to standardizing workflows
- Should be applicable to the processes in use by the organization

{{% note %}}
**Documentation and Training (3 minutes):**
   - Organizations should provide comprehensive documentation and training on how to use standardized workflows with Argo and Flux.
   - Training sessions can help developers understand how to apply standardized practices effectively.
{{% /note %}}

---

{{< slide background-image="/images/slides/27-achieving-continuous-improvement.png" background-opacity="0.5" >}}

### Achieving Standardized Workflows
#### Continuous Improvement

- Foster culture by regularly reviewing and updating workflows
- Encourage developers to provide feedback and suggest improvements

{{% note %}}
**Continuous Improvement (2 minutes):**
   - Foster a culture of continuous improvement by regularly reviewing and updating standardized workflows.
   - Encourage developers to provide feedback and suggest improvements to ensure standardized practices remain relevant and practical.
{{% /note %}}

---

{{< slide background-image="/images/slides/28-interoperability.png" background-opacity="0.5" >}}

## The Role of Interoperability

{{% note %}}
Interoperability in CI/CD (Continuous Integration and Continuous Delivery) systems refers to the ability of different tools, technologies, and components within a CI/CD ecosystem to work seamlessly together. It ensures that various CI/CD pipeline parts, including source code repositories, build systems, testing frameworks, deployment platforms, and monitoring tools, can communicate, integrate, and exchange data effectively without compatibility issues or disruptions.

The importance of interoperability in CI/CD systems for collaboration is multifaceted:
{{% /note %}}

---

{{< slide background-image="/images/slides/29-interoperability-collab.png" background-opacity="0.5" >}}

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
**Flexibility & Choice:** Interop enables development teams sse best tool for job, preventing vendor lock-in  
**Enhanced Collaboration:** Various tool prefs within org / company is not a blocker. Ensures smoothly interaction, facilitating collab & comms  
**Ecosystem Integration:** Interoperable CI/CD systems integrate w/ broader ecosystems  
**Resource Utilization:** Allows orgs to make the most efficient use of existing infra & tools. Reuse components / scripts, etc.  
**Scalability & Growth:** As orgs scale / adopt new tech, interop ensures  CI/CD systems can adapt & expand, supporting incorporating new tools / practices => existing workflows.  
**Cross-Platform Deployment:** In multi-cloud / hybrid environments, promtes unified approach to deployment & infra mgmt.  
**Troubleshooting & Debugging:** When issues arise, interop enables seamless data sharing between various tools & components, for quicker issue ID, troubleshooting, and resolution.
{{% /note %}}

---

{{< slide background-image="/images/slides/30-interop-bridge.png" background-opacity="1" >}}



{{% note %}}
In essence, CI/CD systems interoperability acts as a bridge, connecting different parts of the development and delivery process, fostering collaboration, and ensuring that teams can work cohesively and efficiently, even when using diverse toolsets and technologies. This flexibility and adaptability are essential for modern software development, where agility and collaboration are paramount.
{{% /note %}}

---

{{< slide background-image="/images/slides/31-interop-diverse-toolsets.png" background-opacity="0.5" >}}

### Interoperability
#### Spinnaker & Backstage

{{% note %}}
Interoperability in action with Spinnaker and Backstage demonstrates how these tools effectively integrate and collaborate within a CI/CD ecosystem, while also bridging the gap between the diverse toolsets organizations, and the developers and operators tasked with implementing them, are using. This interoperability offers enhanced flexibility in CI/CD and software development.
{{% /note %}}

---

{{< slide background-image="/images/slides/32-interop-spinnaker.png" background-opacity="0.5" >}}

### Interoperability: Spinnaker

<p class="fragment"><strong>Integration with Cloud Providers:</strong> broad integration options</p>
<p class="fragment"><strong>VCS Integrations:</strong> enable trigger deployment pipelines automation</p>
<p class="fragment"><strong>Extensibility:</strong> useful integrations, like monitoring, incident mgmt, etc.</p>
<p class="fragment"><strong>Artifact Management:</strong> deploy the right artifacts, enhancing reliability</p>
<p class="fragment"><strong>Pipeline Abstraction:</strong> flexible / adaptable process as reqs evolve</p>


{{% note %}}
**Integration w/ Cloud Providers:** Spinnaker is known for its integrations with various cloud providers, providing a consistent interface for deploying/managing across platforms, ensuring seamlessly targeting of environments for devs. Choose what works best.  
**Integration w/ VCS:** Integrations with VCS enables trigger deployment pipelines directly from repos, automating release process and reducing manual intervention.  
**Extensible Integrations:** Extensible arch supports many integrations, allowing teams to connect w/ various ext tools, like monitoring, incident mgmt, scripts, etc. Flexibility ensures Spinnaker can seamlessly fit into org's existing toolset, requirements, and workflows.  
**Artifact Management:** Artifact repo integration, Docker Hub / Artifactory, assist in managing various artifacts, ensuring the right artifacts are consistently deployed across environments, enhancing CI/CD reliability.  
**Pipeline Abstraction:** Abstracting deployments make the process flexible and adaptable. Devs can reuse templates, making adaptation easier as project requirements evolve. This bridge between abstraction and flexibility ensures that Spinnaker can cater to various deployment scenarios.
{{% /note %}}

---

{{< slide background-image="/images/slides/33-interop-backstage.png" background-opacity="0.5" >}}

### Interoperability: Backstage

<p class="fragment"><strong>Integration with CI/CD Tools:</strong> </p>
<p class="fragment"><strong>Service Catalog Integration:</strong> </p>
<p class="fragment"><strong>Plugin Ecosystem:</strong> </p>
<p class="fragment"><strong>Customization and Theming:</strong> </p>

{{% note %}}
**Integration with CI/CD Tools:** Backstage offers integration with various CI/CD tools, including Jenkins, CircleCI, GitHub Actions, Flux, and Argo. This interoperability allows developers to visualize and manage their CI/CD pipelines directly from the Backstage platform, providing a unified view of the entire development workflow.
**Service Catalog Integration:** Backstage serves as a service catalog, helping teams manage and discover their services and applications. Its interoperability with CI/CD systems ensures that CI/CD information is integrated into the service catalog, making it easier for teams to understand the status and history of services.
**Plugin Ecosystem:** Backstage's extensible architecture allows the creation of custom plugins and integrations. This interoperability capability enables organizations to connect Backstage with a wide range of internal and external tools, adapting it to their specific needs and enhancing the overall Developer Experience.
**Customization and Theming:** Backstage allows organizations to customize the user interface and theme, making it adaptable to specific branding and design preferences. This flexibility ensures that Backstage can align with an organization's unique requirements and workflows, enhancing its overall appeal and usability.
{{% /note %}}

---

{{< slide background-image="/images/slides/34-interop-flexibility.png" background-opacity="1" >}}


{{% note %}}
Spinnaker and Backstage both prioritize flexibility and adaptability, allowing organizations to integrate with diverse toolsets and accommodate varying development needs. By bridging gaps between different technologies and systems, they act as central hubs that connect other parts and enhance the flexibility of CI/CD pipelines and developer workflows, ultimately promoting a more efficient and collaborative development environment.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

## Challenges implementing interoperability

{{% note %}}
- **Diverse Toolsets:** Organizations often use a mix of CI/CD tools, each with its own ecosystem and APIs, making it challenging to ensure seamless integration.

- **Data Format and Schema Differences:** Tools may use different data formats or schemas for configuration and communication, leading to compatibility issues.

- **Authentication and Authorization:** Integrating tools may require handling various authentication methods and managing permissions, which can be complex.

- **Versioning and Compatibility:** Changes in tool versions can break existing integrations, necessitating ongoing maintenance.

- **Lack of Documentation:** Insufficient or outdated documentation for APIs and integrations can hinder the development of interoperable solutions.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### Overcoming these hurdles

{{% note %}}
- **Unified Data Formats (Spinnaker Case Study):**
     - In Spinnaker, consider using a unified configuration format for defining deployment pipelines. This format should be documented and enforced for all teams and projects.
     - Provide tools or libraries to automatically convert between different data formats used by other CI/CD tools and Spinnaker. This ensures data consistency and compatibility.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### 

{{% note %}}
   - **API Gateways (Backstage Case Study):**
     - Implement API gateways and adaptors for Backstage to communicate with other CI/CD tools. These gateways can translate data between Backstage's format and the format expected by other tools.
     - Use authentication and authorization mechanisms in the API gateways to seamlessly manage access control and permissions across different toolsets.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### 

{{% note %}}
   - **Version Compatibility (Spinnaker and Backstage):**
     - Maintain version compatibility matrices for Spinnaker and Backstage, listing supported versions of other CI/CD tools and libraries.
     - Prioritize updates and ensure that integrations remain compatible with the latest versions of the tools.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### 

{{% note %}}
   - **Documentation and Developer Resources (Backstage Case Study):**
     - Invest in thorough and up-to-date documentation for both Spinnaker and Backstage integration points.
     - Establish developer resources, such as forums or dedicated support channels, where teams can seek assistance and share best practices.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### 

{{% note %}}
   - **Continuous Testing (Spinnaker and Backstage):**
     - Implement automated testing for integrations between Spinnaker, Backstage, and other CI/CD tools.
     - Include integration tests in your CI/CD pipeline to catch compatibility issues early and ensure ongoing reliability.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### 

{{% note %}}
   - **Community Collaboration (Spinnaker and Backstage):**
     - Encourage collaboration and information sharing within the Spinnaker and Backstage communities to address interoperability challenges collectively.
     - Share success stories and case studies of how teams have successfully integrated Spinnaker and Backstage with other tools to inspire others.

By applying these strategies and tips, organizations can overcome the common interoperability challenges and establish robust connections between Spinnaker, Backstage, and other CI/CD tools, fostering a more seamless and integrated development ecosystem.
{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### In conclusion

{{% note %}}
The efficiencies gained by making sure you're using tools that provide CI/CD standardization as well as being interoperable between all of the systems your developers are using is at the core of what Developer Experience really is about… ruthlessly eliminating barriers (and blockers) that keep your developers from being successful.{{% /note %}}

---

{{< slide background-image="" background-opacity="0.5" >}}

### Thank you.

{{% note %}}

{{% /note %}}
