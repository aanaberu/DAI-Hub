# Backstage

## what is backstage ?
Backstage is an open source framework for building developer portals. Powered by a centralized software catalog, Backstage restores order to your microservices and infrastructure and enables your product teams to ship high-quality code quickly — without compromising autonomy.

Backstage unifies all your infrastructure tooling, services, and documentation to create a streamlined development environment from end to end.

### Backstage community comes with out-of-box features :
- Backstage Software Catalog for managing all your software (microservices, libraries, data pipelines, websites, ML models, etc.)

- Backstage Software Templates for quickly spinning up new projects and standardizing your tooling with your organization’s best practices

- Backstage TechDocs for making it easy to create, maintain, find, and use technical documentation, using a "docs like code" approach

## Benefits of backstage
- For **engineering managers**, it allows you to maintain standards and best practices across the organization, and can help you manage your whole tech ecosystem, from migrations to test certification.

- For **end users (developers)**, it makes it fast and simple to build software components in a standardized way, and it provides a central place to manage all projects and documentation.

- For **platform engineers**, it enables extensibility and scalability by letting you easily integrate new tools and services (via plugins), as well as extending the functionality of existing ones.

- For **everyone**, it’s a single, consistent experience that ties all your infrastructure tooling, resources, standards, owners, contributors, and administrators together in one place.


### Software Catalog

- The Backstage Software Catalog is a centralized system that keeps track of ownership and metadata for all the software in your ecosystem (services, websites, libraries, data pipelines, etc). The catalog is built around the concept of metadata YAML files stored together with the code, which are then harvested and visualized in Backstage.

Example as to how it works :
The Backstage Software Catalog is a centralized system that keeps track of ownership and metadata for all the software in your ecosystem (services, websites, libraries, data pipelines, etc). 
The catalog is built around the concept of metadata YAML files stored together with the code, which are then harvested and visualized in Backstage.

Core usecase that it handles:
1) Helping teams manage and maintain the software they own. Teams get a uniform view of all their software; services, libraries, websites, ML models — you name it, Backstage knows all about it.
2) Makes all the software in your company, and who owns it, discoverable. No more orphan software hiding in the dark corners of your software ecosystem.




# DAI-Hub
Provide details on what DAI Hub is about

Customer :
It doesn’t matter if the company relies 100% on public cloud services or its datacenter is fully on-prem, the requirement is still there: a frictionless onboarding of developers that must push into production code as a core business in the most qualitative, safe, and quick way possible.

Gartner ref:
"Cloud management platforms (CMPs) enable organizations to manage private, public and multicloud services and resources. Their functionality combines provisioning and orchestration; service request management; inventory and classification; monitoring and analytics; cost management and resource optimization; cloud migration; backup and disaster recovery; and identity, security and compliance. Functionality can be provided by a single product or a set of offerings with some degree of integration. — Gartner"

Why Customer wants their own Platfrom ?
Every enterprise company has a different use case: different tools, different processes, different code collaboration models, different organizations, and different skills.

Why Customer looks for backstage ?
Teams want most adopted industrial standard that enterprise companies are targeting. A standard that is vendor-neutral, open-source, and with a well-defined governance for contributors and maintainers. Does the word ‘Kubernetes’ ring you a bell?
Teams are also realizing that the need for HUB is to embrace not only application developers but also infrastructure and operations.

Gatner defination of internal developer platfrom ?
"Gartner defines internal developer portals as tools that enable self-service discovery, automation and access to reusable components, tools, platform services and knowledge assets in modern software development environments. The portals help improve developer experience and service reliability while enabling centralized governance and shared visibility across multiple teams. Capabilities include service and resource catalogs, scorecards to benchmark software quality and security, scaffolding templates for building new components and plug-ins for integrating with platform services. Platform engineering teams provide the portal to product development teams either as a stand-alone application or as integral components of DevOps platforms and broader internal developer platforms."


What DAI-Hub ?

- DAI Hub is a self-service, internal developer platform designed to empower organizations by providing the tools needed to scale DevOps, information security, operations management, and software engineering practices. It can be self-hosted and managed, allowing teams to enhance their productivity and innovation
- DAI Hub - natively integrated with Release, offers a wide range of capabilities, including visibility into running releases across the organization. This integration ensures that teams can manage and monitor their release processes more effectively.
- DAI Hub – with native integration into Deploy, DAI Hub provides visibility into application deployments across various providers, managing the entire lifecycle from start to finish. This feature ensures that deployments are consistent, secure, and well-documented.
- DAI Hub - Release templates feature will provide pre-built templates that streamline the release process, enabling teams to quickly set up and manage their release pipelines.
- DAI Hub - Release workflows with DAI Hub offers capabilities that enable platform teams to scale DevOps practices effectively. It empowers product teams to innovate faster by using templatized workflows, which reduce setup time and minimize errors.
- DAI Hub - Release Integrations Out-of-the-box support is provided for third-party integrations, essential for various areas of the DevOps lifecycle, including security (SAST, SCA, Image Scanning, DAST) and compliance. These integrations are available through the Digital.ai Integrations Marketplace, ensuring that teams have access to the tools they need.
- DAI Hub - Release embedded analytics with DAI Hub includes out-of-the-box support for various metrics, including DORA metrics and Flow metrics, providing teams with the insights needed to optimize their processes and improve performance
- DAI Hub - Release Application management, This feature facilitates comprehensive application management, ensuring that applications are properly maintained, monitored, and optimized throughout their lifecycle



[DAI HUB Journey](https://devopsai.sharepoint.com/:p:/r/sites/digital-ai-pm/Shared%20Documents/General/Products/Release%20and%20Deploy/Strategy/platform-engineering/Developer-Experince-With-Backstage/Digitalai-PlatformEngineering.pptx?d=w9fe784657e584df3889b4973cad725df&csf=1&web=1&e=3hRxhY)

# Gains in Areas 

1. Expediting manual and repetitive work
2. Jump starting the first draft of new workflow , template
3. Accelerating updates to existing workflow and template
4. incresing developers ablity to tackle new challenges

# Emmbedded Analytics in DAI HUB

1. Helps to diagonise and fix issues faster (DORA) and reduce technical debt and improve quality
2. Testing and documents, Test generation and higher code coverage means fewer defects and regression.with better doc reduce congnitive load and improve team efficiency
3. * Help analyse data and allocate resource more effectively ( Resource analytics)


# Details 
TBA


# References from Redhat 


# Myths ( Courtesy Redhat) 
[Link to Reference Redhat Blog](https://developers.redhat.com/articles/2024/07/22/5-myths-about-platform-engineering-debunked#myth__2__platform_engineering_sacrifices_security_and_governance_for_speed)

### #1 Platform engineering slows down development
Platform engineering, when implemented correctly, is designed to be a productivity booster, not a creativity crusher. One of the main goals of platform engineering is to enhance developer experience. This leads to developers being more effective and capable of delivering secure, stable, and supported code sooner, which in turn provides greater business agility, innovation, and reduced time to market.

Traditionally, development teams spend precious time wrestling with infrastructure complexities—setting up servers, configuring environments, managing dependencies, managing existing services and ensuring onboarding for new members is fast and quickly. The discipline of platform engineering steps in as the knight in shining armor, automating these tedious tasks, ensuring there is a central point of technology access, knowledge and services supported by a team with a single role of removing friction and increasing developer productivity. Imagine a team facing a mountain of infrastructure hurdles. Platform engineering blasts a tunnel right through that mountain, allowing development teams to focus on what they do best—deliver compelling software solutions. 

Furthermore, by providing pre-configured environments and self-service tools through a single pane of glass, platform engineering empowers development teams to spin up new environments on demand (either on-premises, cloud or even on the edge), accelerating development lifecycles and letting them focus on the solution.  

### #2 Platform engineering sacrifices security and governance for speed

Platform engineering, when implemented effectively, can actually be a champion for both speed and security.

Modern platforms naturally present complete security features that safeguard your applications and data. These features may include role-based access control (RBAC), which ensures only authorized users have access to specific resources. Additionally, features like network segmentation and containerization help isolate applications and prevent security breaches from spreading. 

Platform engineering also leverages automation to handle many of the tedious tasks traditionally associated with security. For example, automated vulnerability scanning and patching can identify and address security risks quickly, freeing up security teams to focus on more strategic initiatives. Think of it like a team of security robots—they tirelessly scan for vulnerabilities, allowing your human security experts to concentrate on complex threats.

Compliance is another area where platform engineering shines. Many platforms are designed to be compliant with various industry regulations. This means they offer built-in features and configurations that help organizations meet compliance requirements more efficiently. Imagine having pre-built security checklists and automated compliance reports—the platform simplifies the compliance process, allowing developers to focus on building secure applications.

Platform engineering can actually improve governance by providing a centralized platform for managing resources and enforcing policies. This ensures consistency and reduces the risk of shadow IT, where developers use unauthorized tools or infrastructure. Think of it like a well-organized city—the platform establishes clear rules and guidelines, promoting efficient development without stifling innovation.

By prioritizing built-in security features, leveraging automation, simplifying compliance, and streamlining governance, platform engineering can be a powerful ally in the quest for secure and efficient development

### #3 Platform engineering is a lone wolf's game
Successful platform engineering is all about teamwork and collaboration. It starts with product teams and designers, who understand what users need and where they face problems. Their insights help shape the platform so that it makes not only developers' jobs easier and more efficient but every project members. Security specialists are also crucial. They make sure the platform is safe from the start by building strong defenses against hackers and other threats. This helps protect the company's data and keeps everything secure.

Operations teams are the ones who integrate the new platform with the existing systems. They ensure that everything works together smoothly without causing interruptions. They also keep the platform running reliably, fixing any issues that come up so there’s no downtime. Another key part of this teamwork is open communication with stakeholders across the company. This means talking regularly with everyone involved to make sure everyone’s on the same page and working toward the same goals. When the platform engineering team knows the bigger picture, they can make decisions that support the company’s overall success.

By working together like this, platform engineering teams build platforms that are more than just tools. They become powerful assets that help the entire company grow and succeed. Collaboration ensures that these platforms are not only effective and user-friendly but also aligned with the strategic goals of the business, making them invaluable to the organization’s future.

### #4  Platform engineering makes infrastructure teams obsolete
Platform engineering adds a layer that makes things easier for developers, but the complex infrastructure behind the scenes still needs specialists. These infrastructure experts design and manage the foundation that everything runs on. They make sure the system can handle more users and data as it grows. When something goes wrong, they are the ones who fix it to keep everything running smoothly. They also find ways to make the system faster and more efficient.

Platform engineering’s main job is to make life easier for developers by providing tools and services that simplify their work. For example, they might create systems that automate repetitive tasks or make it easier to test new code. However, this doesn't mean infrastructure teams are no longer needed. In fact, platform engineering and infrastructure teams need to work closely together. The platform engineering team builds tools to help developers, while the infrastructure team ensures the underlying systems are strong and reliable.

This collaboration means that both teams can focus on what they do best. Developers get a user-friendly experience with tools that help them work faster and more efficiently. Meanwhile, infrastructure experts make sure everything is stable, secure, and can grow with the company’s needs. For instance, while platform engineers might create an easy-to-use interface for deploying applications, infrastructure specialists make sure the servers and networks can handle the new applications without crashing.

By working together, they create a powerful, efficient environment that supports the entire company. The goal is not to replace each other but to complement each other's skills. This teamwork leads to a stronger, more effective technology foundation for the organization. Everyone brings their expertise.


### #5 Platform engineering requires a completely new approach

Many organizations worry that platform engineering requires a disruptive, rip-and-replace approach to their existing infrastructure. But the reality is, platform engineering can be adopted incrementally. Think of it like a home renovation—you don't have to tear down the entire house. You can start by upgrading key areas like the kitchen or bathroom (e.g., integrating specific development tools or automating deployments) and gradually expand from there.

This means organizations can leverage their existing investments in cloud platforms or on-premises hardware while incorporating platform engineering principles.  Imagine building an extension onto your house—the platform can connect to your existing infrastructure, providing the benefits of platform engineering without requiring a complete rebuild.

Organizations can begin with a small-scale platform engineering implementation, focusing on a specific development team or project. This allows them to test the waters, identify the benefits, and then scale the platform to encompass more teams and applications over time. Think of it like planting a seed—you don't harvest a giant tree overnight. You start small and nurture it until it grows to its full potential.

By adopting platform engineering practices, even in a limited way, organizations lay the groundwork for a more efficient and scalable development environment in the future. 

# Reference 
## What Janus-Redhat Hub? 
[Link Red Hat Developer Hub](https://developers.redhat.com/rhdh/overview)

A unified platform that can consolidate these elements of the development process and foster internal collaboration will enable development teams to focus on rapidly enhancing code and functionality to efficiently build high-quality software.

# Details:

## Benfits

Red Hat Developer Hub allows platform engineering teams to offer software templates, pre-architected and supported approaches to maximize developer skills, ease onboarding, and increase development productivity, and focus on writing great code by reducing friction and frustration for development teams.Red Hat Developer Hub also offers Software Templates to simplify the development process, which can  reduce friction and frustration for development teams, boosting their productivity and increasing an organization's competitive advantage.

System Architects can benefit by implementing a tailored platform with a complementary suite of verified and curated tools and  components needed for operations teams to support developers—within a centralized, consistent location. Development teams can experience increased productivity, fewer development team obstacles, and simplified governance of technology choices with self-service and guardrails.

## Simplifying the inner loop for developers

Simplifying the inner and outer loop model is also an important part of improving the development process. 
- In the inner loop, the developer works on the code. 
- In the outer loop, developers push the code to version control for automation, testing, and deployment until it is ready for release. 
Developers need a simple inner loop so that they can focus on finding software solutions, not configuring tools.
Developers need a single place, like a hub, where they can find resources, utilize and generate shareable components, and follow Golden Path templates (templated paths to quick and easy software development).

# Overview of Backstage and Project Janus

Red Hat Developer Hub is an enterprise-grade, supported version of Backstage, an open source framework (provided by Spotify) for building developer portals. Engineering teams can use Red Hat Developer Hub to reduce friction and frustration and boost their productivity, giving their organization a competitive advantage.

Its preloaded all the necessary Red Hat plug-ins, including a variety of technology and tools that reduce developer cognitive load and support self service, while maintaining context and underlying technologies continuously maintained and improved by platform teams.

Project Janus, has developed and enhanced the Golden Path templates, Backstage platform, and plug-ins.

# 6 Red Hat Plug-ins for Backstage

Red Hat Plug-ins for Backstage work in tandem with Red Hat Developer Hub and pre-existing customer installations of Backstage, extending functionality and improving the overall experience. These 6 plug-ins are the supported version of the community plug-ins:

1. Authentication and Authorization with Keycloak: Load users and groups from Keycloak to Backstage, enabling use of multiple authentication providers applied to Backstage entities.
2. Multicluster View with Open Cluster Manager (OCM): This plug-in provides a multicluster view from Open Cluster Manager’s MultiClusterHub and MultiCluster Engine in Backstage.
3. Container Image Registry for Quay: The container image registry for Quay improves the integration and speed of interactions with Quay registries by providing a view into the container image details. This includes Common Vulnerabilities and Exposures (CVEs) associated with deployed images.
4. Application Topology for Kubernetes: Consistently visualize relationships and real-time status of applications and workloads deployed to any Kubernetes target, including Red Hat OpenShift.
5. Pipelines with Tekton: This plug-in provides details of all Tekton Pipelines and their status across all services.
6. GitOps with Argo CD: Track the health and status of Argo CD and monitor services inside Backstage.

+addon : Red Hat Developer Hub and its associated plug-ins extend the upstream Backstage product by providing additional features such as integration with OpenShift, enterprise role-based access control (RBAC), and dynamic plug-ins.

# Streamline onboarding with Golden Path templates

Red Hat Developer Hub provides Golden Path templates that are essential for fast-tracking development and ensuring organization and consistency. These templates are referred to as golden because they provide gold-standard best practices for developers to follow so your code will be coherent, scalable, and maintainable.

You can streamline application and developer onboarding with Golden Path templates. Golden Paths provide pre-architected and supported approaches to building and deploying a particular piece of software without having to learn all the details of the technology used.

Templates enable self-service for developers. They also provide the best pathway to fix bugs or implement features, enabling developers to speed up the process, thereby making your organization more competitive.

## The two sides of Red Hat Developer Hub

From a consumption perspective, Red Hat Developer Hub perfectly matches the functionality needed for the developer as part of the inner loop. For the first time, a developer has a single place to find everything, from links, integrated development environments (IDEs), and GitHub repos, to documentation and components catalogs added to applications

## How Red Hat Developer Hub benefits developers

Red Hat Developer Hub provides a single place for a developer to work. Finally, there’s a hub for all things a developer needs, such as resources, clusters, and templates. Red Hat Developer Hub provides complete coverage of the inner loop, IDE, direction interaction, and authentication to GitHub.

Developers must understand the complexity of the various tools they use. Learning numerous toolsets as well as the ins and outs of the frameworks, technologies, and components of their organization can be time consuming. The primary goal of Red Hat Developer Hub is to ease the development process and provide an aggregated toolset that reduces the mental overhead of context switching and searching for the core components they need.

Red Hat Developer Hub provides a wizard and template-driven experience for end developers. This makes it very easy to build complex systems from multiple components, including Git source-driven deployments to systems such as Kubernetes and OpenShift. In addition, the provisioning of these components simplifies the knowledge the developer needs. With a couple of clicks and text entry points, developers can convert a template to a running application component without knowing the convoluted technology beneath it.

This gives developers more time to spend on developing rather than configuring development environments and components. Not only is the developer presented with a rich set of components from which to choose, but system administrators can configure these components.

## How Red Hat Developer Hub benefits administrators

Red Hat Developer Hub is built on the Janus open source project, which extends the Backstage open source project, providing a highly configurable and secure development portal and catalog to control which components can be built together. Red Hat Developer Hub extends the functionality through a set of predefined supported plug-ins providing extensions and components to ease the developer's path as they design and build composite applications.

Using code-as-config, administrators can control exactly what developers can interact with and at what level, providing a simple to use and simple to configure mechanism for providing developers with a single point for all things development.

Red Hat Developer Hub also provides a highly configurable authentication model, allowing integration with providers such as GitHub and Keycloak. Administrators can configure authentication methods, templates (i.e., multi-component quick starts and API definitions), and the base definitions. This is a sophisticated tool for building organizational developer portals.

## Red Hat Developer Hub increases productivity and more
Red Hat Developer Hub is designed to significantly improve engineering productivity for IT organizations, enabling development teams to focus on what really matters—writing high-quality code and accelerating application delivery to give organizations a competitive advantage.