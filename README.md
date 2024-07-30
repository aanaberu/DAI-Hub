# DAI-Hub
Provide details on what DAI Hub is about

What DAI-Hub ?

Reference 
What Janus-Redhat Hub?

A unified platform that can consolidate these elements of the development process and foster internal collaboration will enable development teams to focus on rapidly enhancing code and functionality to efficiently build high-quality software.

# Details:

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