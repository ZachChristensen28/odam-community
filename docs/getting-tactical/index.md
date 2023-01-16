---
hide:
    - navigation
    - toc
---

# Getting Tactical

## Part IV

??? note "Getting Tactical - Recommendations"
    These are my tactical recommendations for you to consider when thinking about the essentials in security analytics and security operations:

    - Create a data-driven security strategy: By focusing on data-driven approaches to security, organizations can more effectively identify, prioritize, and address security threats and vulnerabilities. This may involve establishing key performance indicators (KPIs) to measure the effectiveness of security efforts, and using analytics to identify trends and patterns in security data.
    - Develop a strong security analytics team: Building a team of skilled security analysts is critical for successful security analytics. This team should have expertise in areas such as data analysis, visualization, and machine learning, and should be equipped with the right tools and technologies to support their work.
    - Leverage automation and machine learning: Automation and machine learning can help to streamline and improve the efficiency of security analytics and operations. For example, machine learning algorithms can be used to identify patterns and trends in security data, while automation can help to reduce the workload of security analysts by automating routine tasks.
    - Foster collaboration and communication: Effective security analytics and operations require strong collaboration and communication between different teams and stakeholders. This may involve establishing clear lines of communication between the security analytics team and other teams within the organization, as well as establishing effective channels for sharing security data and insights.
    - Invest in the right tools and technologies: In order to support effective security analytics and operations, organizations need to invest in the right tools and technologies. This may include security analytics platforms, visualization tools, and machine learning algorithms, as well as technologies to support data collection and management.
    - Implement a security information and event management (SIEM) system: A SIEM system can help to collect, analyze, and report on security-related events and data from a variety of sources, including network devices, servers, applications, and security devices. This can help to provide visibility into potential threats and help you to identify and respond to incidents more quickly.
    - Implement a security orchestration, automation, and response (SOAR) platform: A SOAR platform can help to automate and streamline your incident response process by providing tools for automating incident triage, escalating incidents to the appropriate teams, and coordinating response efforts.
    - Implement a vulnerability management program: A vulnerability management program can help you to identify and prioritize vulnerabilities in your systems and applications, and implement measures to mitigate or eliminate those vulnerabilities. This can help to reduce your risk of successful attacks.
    - Implement a threat intelligence program: A threat intelligence program can help you to stay informed about emerging threats and trends, and provide guidance on how to mitigate or eliminate those threats. This can help you to proactively protect your organization against potential attacks.
    - Implement a continuous monitoring program: A continuous monitoring program can help you to regularly assess and monitor your security posture, identify potential vulnerabilities or risks, and implement corrective actions to address those issues. This can help you to maintain a strong security posture over time.
    - Identify and prioritize the data sources that will be most valuable for your security analytics efforts. This may include network logs, security event logs, and other data sources that can provide insights into potential security threats.
    - Develop a plan for collecting, storing, and analyzing your security data. This may include implementing a data lake or other data management solution, as well as identifying the tools and technologies that will be needed to analyze and interpret the data.
    - Implement processes and procedures for responding to security events and incidents. This may include establishing a security operations center (SOC) or other incident response team, as well as defining protocols for responding to different types of security threats.
    - Train and enable your security analytics and operations teams. Ensure that they have the necessary skills and knowledge to effectively analyze and respond to security threats, and provide ongoing training and support to help them stay up to date on the latest threats and technologies.
    - Regularly review and optimize your security analytics and operations efforts. Use metrics and other performance indicators to identify areas for improvement, and make adjustments as needed to ensure that you are effectively addressing security threats and meeting your objectives.

    These are some examples of practical recommendations you can consider in order to approach the essentials in security analytics and security operations. It is important to tailor your approach to the specific needs of your organization, and to be proactive in identifying and addressing potential threats.

??? note "Essentials in Analytics Operations"
    ## Essentials in Analytics Operations

    <figure markdown>
        ![Essentials in Analytics Operations](/assets/getting-tactical/analytics-operations.png){ width="800" }
    </figure>

    ??? tip "Data"
        ### Data

        ??? info "Data Storage Options for Business Analytics"
            #### Data Storage Options for Business Analytics

            Data storage is a critical component of any business analytics strategy. A data warehouse is a repository of data that is organized and structured to support business analysis. However, there are other options available, such as data lakes and reservoirs, which offer different capabilities and features. It is important for businesses to choose the data storage option that best fits their needs and goals. Some considerations to keep in mind include the ability to access data from various locations, the ability to integrate with different analytics platforms, and the overall cost and scalability of the solution. In order to ensure that your business can effectively leverage data analytics, it is essential to carefully evaluate and choose the right data storage option.

        ??? info "The Importance of Data Management in a Data Strategy"
            #### The Importance of Data Management in a Data Strategy

            Effective data management is crucial for any organization looking to leverage data to drive business success. It involves the planning and execution of processes and systems that ensure the accurate, accessible, and usable storage of data. This includes activities such as data collection and storage, data integration, data cleansing and quality management, data security, and data governance. A well-designed data management system is necessary for supporting the use of data to inform decision-making and drive business actions, and is an essential component of a successful data strategy. Therefore, it is important to consider data management as a key part of any data strategy planning process

        ??? info "The Importance of Data Architecture in a Data Strategy"
            #### The Importance of Data Architecture in a Data Strategy

            Data architecture is a crucial aspect of a data strategy, as it determines the structure and organization of the data system or ecosystem that supports the data strategy. It includes the design of data models, the relationships between data elements, and the physical implementation of data storage and processing systems. A well-designed data architecture is essential for ensuring that data is accurate, accessible, and usable within an organization, and is a key factor in the successful implementation of a data strategy.

            There are two main categories of data architecture: logical data architecture, which defines the logical structure and relationships of data, and physical data architecture, which defines the physical structure and implementation of data storage and processing systems. Both are important considerations when designing and implementing a data strategy.

            Effective data architecture plays a critical role in supporting the effective management and use of data within an organization. It helps to ensure that data is integrated, stored, and secured in a way that supports the organization's business goals, and enables the effective use of data to inform decision-making and drive business actions. As such, data architecture should be an integral part of any data strategy planning process.

            <figure markdown>
                ![Overview of Data Architecture with ODAM](/assets/getting-tactical/data-architecture-overview.png){ width="800" }
            </figure>
        
        ??? info "Maintaining Data Quality"
            #### Maintaining Data Quality

            Maintaining data quality is the process of ensuring that data is accurate, complete, and up-to-date. This includes verifying the accuracy of data, correcting errors or inconsistencies, and removing or de-duplicating duplicate or outdated data. Data quality is an important aspect of data management, as it helps to ensure that data is reliable and can be used effectively for business purposes.

            Poor data quality can lead to a variety of problems, such as incorrect or incomplete insights, wasted time and resources, and damage to an organization's reputation. To maintain data quality, it is important to establish and implement processes for regularly reviewing and cleaning data, as well as for verifying the accuracy of data as it is collected and entered into systems.

            In terms of data architecture, data quality should be considered when designing and implementing data storage and processing systems. This may include implementing data validation and error correction mechanisms, as well as regularly reviewing and cleaning data to ensure that it is accurate and up-to-date. Maintaining data quality is an ongoing process that requires ongoing attention and resources, and should be an integral part of an organization's data management strategy.

        ??? info "Data Architecture Frameworks"
            #### Data Architecture Frameworks

            Data architecture frameworks are models or frameworks that provide a structure and approach for designing and organizing a data architecture. These frameworks typically include guidelines and best practices for areas such as data modeling, data storage, data integration, data governance, and data security.

            There are multiple data architecture frameworks that organizations can choose from, including:

            `The Zachman Framework`
            : This framework provides a structured approach to data architecture design by considering six dimensions of data: who, what, where, when, why, and how.
            
            `The Data Vault Model`
            : This framework is based on a hub-and-spoke model and is designed to support large, complex data architectures that need to be flexible and scalable.
            
            `The Data Warehouse Bus Architecture`
            : This framework is designed to support data warehousing and business intelligence systems and is based on a bus-based data model.
            
            `The Data Governance Framework`
            : This framework is focused on the governance and management of data and includes guidelines and best practices for areas such as data ownership, data quality, and data security.

            ---
            Data architecture frameworks provide a structured approach to designing and organizing a data architecture and can be helpful for organizations that are looking to improve the management and use of their data.

            - The Data Management Body of Knowledge (DAMA-DMBOK2) is a data management framework and reference guide created by DAMA International, a professional association for data managers.
            - TOGAF was created in 1995. It is an enterprise architecture framework and methodology that includes a section on data architecture design and roadmap development.
            - Meant to serve as the basis for an architecture, the Zachman Framework is an ontology framework that uses a 6-x-6 matrix of rows and columns to describe an enterprise architecture and data elements but does not include an implementation methodology.

            Using ODAM, organizations can ensure that data is flexible, adaptable, and elastic. ODAM provides the foundational components of a data strategy that your organization can customize and tailor to your business and specific needs. Components built-in to ODAM include:

            - A guide to implementing a modern data architecture.
            - Assistance in setting up agile data governance practices.
            - Assistance in adopting and utilizing data integration and transformation tools.
            - Guidance on implementing data virtualization.
            - A framework to set up regular monitoring and optimization of data performance. 

            These strategies, when implemented in combination, can help organizations to improve the flow and use of data, making it more scalable and responsive to changing business needs.

    ??? tip "IT Assets, Networks, Applications, and Users"
        ### IT Assets, Networks, Applications, and Users

        Monitoring IT assets is a crucial part of managing and maintaining a strong and secure technology infrastructure. By monitoring IT assets, organizations can identify and address issues as they arise, and ensure that their systems are functioning optimally.

        Continuously monitoring the IT network for threats can provide a range of benefits to organizations. By continuously monitoring the IT network for threats, organizations can identify and address potential vulnerabilities or threats, enhance their threat visibility, improve their incident response capabilities, and reduce risk.

        Continuously monitoring applications can provide a range of benefits to organizations. By continuously monitoring applications, organizations can identify and address issues that may be impacting system performance, enhance security, improve incident response capabilities, and reduce risk.

        Organizations can anticipate increased user productivity and security, maintain regulatory compliance, protect sensitive data and prevent data breaches, and speed up incident response time by continuously monitoring users, identities, and access.

        <figure markdown>
            ![IT, Networks, Applications, and Users](/assets/getting-tactical/it-networks-apps-users.png){ width="800" }
        </figure>

??? note "Phased Approach to Security Maturity"
    ## Phased Approach to Security Maturity

    !!! quote "Data is like garbage. You’d better know what you are going to do with it before you collect it."
        <strong>Mark Twain</strong>
    
    Splunk's phased approach to security maturity is a systematic framework that helps organizations to progressively improve their security posture over time. The approach is designed to help organizations to quickly detect, investigate, and respond to threats.
    
    1. Ad-hoc search and investigation capabilities (Level 1).
    1. Proactive Monitoring and Alerting (Level 2).
    1. Security Situational Awareness (Level 3).
    1. Real-time Risk Insight and Automation (Level 4).

    One of the key benefits of ODAM is its ability to increase visibility into security logs and enable organizations to monitor their security posture in real-time. This can help organizations identify potential security threats more quickly and respond to them more effectively. Additionally, ODAM can provide advanced security analytics and a risk-based alerting framework, which can help organizations proactively identify and respond to security incidents.

    ODAM can also help organizations integrate threat intelligence into their security operations. By incorporating threat intelligence into their data analytics initiatives, organizations can enhance their overall security posture and stay ahead of potential threats.

    One of the most exciting ways that ODAM can help organizations is by preparing for new capabilities like Splunk Mission Control. Splunk Mission Control is an innovative platform that unifies security operations and enables organizations to improve their incident response times, automate their workflows, and gain real-time visibility into their security posture.

    By using ODAM to mature and operationalize your data analytics capabilities, organizations can be better prepared to take advantage of new technologies like Splunk Mission Control. This can help improve threat detection, investigation, and response capabilities, and ultimately become more resilient against security threats.

??? note "The Role of Threat Intelligence in Cybersecurity Maturity"
    ## The Role of Threat Intelligence in Cybersecurity Maturity

    Threat intelligence is essential in a phased approach to achieving cybersecurity maturity. It enables organizations to understand the various types of threats they may encounter and the tactics, techniques, and procedures (TTPs) that attackers use. This information helps organizations to develop a comprehensive cybersecurity strategy that addresses their specific threats and vulnerabilities.

    During the planning phase, threat intelligence is used to identify potential threats and vulnerabilities and prioritize the most pressing risks. This information is then used to inform the development of a risk assessment and risk management plan.

    In the implementation phase, threat intelligence helps organizations to select and deploy appropriate cybersecurity controls or technologies.

    During the ongoing maintenance phase, threat intelligence is used to continuously monitor for and assess new threats and vulnerabilities, and to update the organization's cybersecurity strategy and controls as needed.

    In summary, threat intelligence is a crucial factor in a phased approach to achieving cybersecurity maturity, as it provides organizations with the information they need to identify and prioritize threats, and to implement and maintain a robust and effective cybersecurity strategy.

??? note "Risk: Assessments, Modifiers, and Variables"
    ## Risk: Assessments, Modifiers, and Variables

    ??? tip "Risk Assessments"
        ### Risk Assessments

        Risk assessments are an important tool for determining company priorities. Organizations may better understand the risks they face and determine the most important priorities for resolving those risks by examining the effect, exposure, threats, and likelihood of risk occurrences. Finally, risk assessments assist companies in making educated decisions about how to deploy resources and reduce possible risks in order to safeguard assets and meet business objectives.
    
    ??? tip "Risk Factor Editor"
        ### Risk Factor Editor

        In today's digital world, managing cyber risk is an essential part of any organization's operations. One important tool for doing so is the Risk Factor Editor, which allows organizations to take a range of considerations into account when evaluating and prioritizing their cyber risk. Some of the key considerations that the risk factor editor can factor in include: asset criticality, alert criticality, SLA classification, data classification, application criticality, network criticality, user criticality, and MITRE TTP details. In this section, we will delve into each of these risk factors in more detail, exploring what they are, why they are important, and how they can be used to help organizations manage their cyber risk more effectively. By understanding the full range of factors that can impact an organization's cyber risk, IT professionals can make more informed and strategic decisions about how to protect their systems, data, and users from potential threats.

        `Asset Criticality`
        : This refers to the importance or value of a particular asset to the organization, such as a server, database, or application. An asset's criticality may be determined by factors such as the impact it has on the organization's operations, the cost of replacing it, or the sensitivity of the data it stores.
        
        `Alert Criticality`
        : This refers to the level of urgency or importance of an alert or notification, such as a security breach or system failure. An alert's criticality may be determined by the potential impact on the organization's operations, the likelihood of damage or loss, or the time required to address the issue.
        
        `SLA Classification`
        : This refers to the classification or categorization of a service level agreement (SLA), which is a contract that outlines the terms and conditions for delivering a specific service. An SLA classification might include categories such as standard, premium, or critical, depending on the level of service required.
        
        `Data Classification`
        : This refers to the process of categorizing data based on its sensitivity, value, or importance to the organization. Data classification may be used to determine the level of protection required, the access controls needed, or the legal or regulatory obligations associated with the data.
        
        `App Criticality`
        : This refers to the importance or value of a particular application to the organization, such as a customer relationship management system or an enterprise resource planning system. An app's criticality may be determined by factors such as the impact it has on the organization's operations, the cost of replacing it, or the sensitivity of the data it stores.
        
        `Network Criticality`
        : This refers to the importance or value of a particular network or network component to the organization, such as a server, switch, or router. A network's criticality may be determined by factors such as the impact it has on the organization's operations, the cost of replacing it, or the sensitivity of the data it transmits.
        
        `User Criticality`
        : This refers to the importance or value of a particular user or user group to the organization, such as employees, customers, or partners. A user's criticality may be determined by factors such as their role within the organization, their level of access to sensitive data or systems, or their impact on the organization's operations.
        
        `TTP Details`
        : Tactic, technique, and procedure (TTP) details are important risk variables to consider when analyzing and mitigating cyber threats. These details refer to the specific methods or approaches used to carry out an action, such as a cyber attack or security breach. By understanding TTP details, organizations can identify patterns or trends in attack methods and understand the potential risks and impacts associated with these methods. This can inform risk management and security strategies, and help to develop more effective countermeasures to protect against potential threats.

        ODAM helps organizations pinpoint risk factors and make adjustments to their risk evaluation and policy enforcement processes. By using ODAM, organizations can take a targeted approach to risk management and streamline their processes for identifying, assessing, and addressing risks in real-time. ODAM can be a valuable tool for organizations responsible for managing and mitigating cyber risk. 

??? note "How Splunk Enhances All Functional Groups in the SOC"
    ## How Splunk Enhances All Functional Groups in the SOC

    A mature Security Operations Center (SOC) typically includes the following functional groups:

    SOC Functional Group | Enhancement with Splunk
    -------------------- | -----------------------
    `Security Operations`: This group is responsible for monitoring and analyzing security events and incidents, identifying threats, and taking action to mitigate them. | Splunk can provide real-time visibility into security events and incidents, allowing security operations teams to quickly identify and respond to threats. Splunk can also provide analytics capabilities to help security operations teams understand the nature and scope of threats, and to identify patterns and trends that may indicate the presence of a larger attack.
    `Threat Intelligence`: This group is responsible for gathering, analyzing, and disseminating intelligence about threats, vulnerabilities, and trends in the cyber landscape. | Splunk can help threat intelligence teams to gather, analyze, and disseminate intelligence about threats, vulnerabilities, and trends in the cyber landscape. Splunk can provide a centralized platform for storing and analyzing intelligence data, and can help teams to identify patterns and trends that may indicate the presence of a new or evolving threat.
    `Vulnerability Management`: This group is responsible for identifying and prioritizing vulnerabilities, coordinating remediation efforts, and monitoring progress. | Splunk can help vulnerability management teams to identify and prioritize vulnerabilities, and to monitor progress in addressing them. Splunk can provide real-time visibility into the state of an organization's security posture, and can help teams to identify and prioritize vulnerabilities based on their potential impact and likelihood of exploitation.
    `Security Architecture`: This group is responsible for designing, implementing, and maintaining the security infrastructure of the organization. | Splunk can help security architecture teams to design, implement, and maintain the security infrastructure of the organization. Splunk can provide real-time visibility into the state of an organization's security infrastructure, and can help teams to identify and address weaknesses and vulnerabilities.
    `Security Engineering`: This group is responsible for implementing, maintaining, and updating security controls and technologies. | Splunk can help security engineering teams to implement, maintain, and update security controls and technologies. Splunk can provide real-time visibility into the state of an organization's security controls, and can help teams to identify and address weaknesses and vulnerabilities.
    `Compliance`: This group is responsible for ensuring that the organization is compliant with relevant regulations and standards, such as PCI DSS, HIPAA, and NIST. | Splunk can help compliance teams to ensure that the organization is compliant with relevant regulations and standards. Splunk can provide real-time visibility into the state of an organization's security posture, and can help teams to identify and address areas of non-compliance.
    `Risk Management`: This group is responsible for identifying, assessing, and mitigating risks to the organization's assets, including data, systems, and networks. | Splunk can help risk management teams to identify, assess, and mitigate risks to the organization's assets, including data, systems, and networks. Splunk can provide real-time visibility into the state of an organization's security posture, and can help teams to identify and prioritize risks based on their potential impact and likelihood of occurrence.

    ??? tip "Continuous Monitoring for Cybersecurity: Threat Intelligence, Incident Handling, Forensics, and Self-Assessment"
        ### Continuous Monitoring for Cybersecurity: Threat Intelligence, Incident Handling, Forensics, and Self-Assessment

        !!! quote "Not everything that can be counted counts and not everything that counts can be counted."
            <strong>Albert Einstein, Physicist</strong>
        
        The focus should not be on a specific data source or technology but rather on the broader concept of observability.

        IT operations refer to the activities and processes involved in maintaining and managing the technology infrastructure, systems, and applications of an organization. This can include tasks such as installing and configuring hardware and software, monitoring systems and networks for issues or outages, and troubleshooting and resolving problems as they arise.

        IT observability, on the other hand, refers to the ability to monitor, measure, and understand the performance and behavior of IT systems, networks, and applications. This can include collecting and analyzing data from various sources, such as log files, performance metrics, and traffic patterns, to identify trends, issues, and potential problems.

        The main difference between IT operations and IT observability is that IT operations focus on the day-to-day management and maintenance of IT systems, while IT observability focuses on understanding and optimizing the performance and behavior of these systems. Both are important for ensuring the smooth and reliable operation of an organization's technology infrastructure, but they serve different purposes and use different approaches and tools.

        Threat intelligence, incident handling, forensics, and self-assessment can all be important factors in a continuous monitoring approach to cybersecurity.

        `Threat intelligence`
        : Threat intelligence refers to information about potential threats or vulnerabilities that an organization may face, such as new malware strains or zero-day exploits. This information can be used to inform continuous monitoring efforts by helping to identify potential risks and vulnerabilities, and to prioritize the most important areas to focus on.
        
        `Incident handling`
        : Incident handling refers to the process of responding to and managing security incidents or breaches, such as malware infections or unauthorized access to sensitive data. This can be an important part of continuous monitoring because it helps to identify and address potential issues as they arise, and to prevent further damage or loss.
        
        `Forensics`
        : Forensics refers to the process of collecting, analyzing, and preserving digital evidence for the purpose of investigating security incidents or crimes. This can be an important part of continuous monitoring because it helps to identify the root causes of incidents or breaches, and to understand the extent of the damage or loss.
        
        `Self-assessment`
        : Self-assessment refers to the process of evaluating an organization's security posture and identifying areas for improvement. This can be an important part of continuous monitoring because it helps to identify weaknesses or vulnerabilities that may not be immediately apparent, and to take steps to address them.

        ---
        Continuous monitoring with respect to cybersecurity involves continuously collecting and analyzing data from various sources, such as threat intelligence feeds, security logs, and network traffic, to identify potential risks and vulnerabilities, and to respond to and manage incidents or breaches as they arise. By using tools and processes such as threat intelligence, incident handling, forensics, and self-assessment, organizations can improve their ability to identify and mitigate potential threats, and to maintain a strong security posture.

        <figure markdown>
            ![Security Monitoring](/assets/getting-tactical/security-monitoring.png){ width="800" }
        </figure>

        Cybersecurity Operations and Monitoring teams running a Security Operations Center (SOC) require data analytics at operational speed.

    ??? tip "Benefits of Constant Introspection for IT Organizations"
        ### Benefits of Constant Introspection for IT Organizations

        Constant introspection refers to the process of continuously monitoring and analyzing the performance and behavior of an organization's technology infrastructure, systems, and applications. This practice can provide numerous benefits for IT organizations, including:

        `Performance monitoring`
        : Identifying potential bottlenecks or issues that may be impacting system performance.
        
        `Capacity planning`
        : Understanding resource requirements and planning for future capacity needs.
        
        `Security monitoring`
        : Identifying potential vulnerabilities or threats.
        
        `Compliance monitoring`
        : Ensuring compliance with relevant regulations and standards.
        
        `Root cause analysis`
        : Identifying the root causes of problems and addressing them.

        By implementing constant introspection, IT organizations can optimize the performance and efficiency of their systems, improve security, and ensure compliance.

    ??? tip "Tracking Key Performance Indicators for IT Systems and Applications"
        ### Tracking Key Performance Indicators for IT Systems and Applications

        Performance monitoring and capacity planning are important activities for ensuring the smooth and reliable operation of an organization's technology infrastructure, systems, and applications. Some specific key performance indicators (KPIs) that an organization can track when it comes to these activities include:

        `System availability`
        : This KPI measures the percentage of time that a system is available and functioning as expected. This can be important for ensuring that systems are meeting the needs of users and customers.
        
        `Response time`
        : This KPI measures the time it takes for a system or application to respond to a request. This can be important for ensuring that systems are responsive and perform well.
        
        `Throughput`
        : This KPI measures the amount of data or transactions that a system or application can process in a given time period. This can be important for understanding the capacity and performance of a system.
        
        `Error rate`
        : This KPI measures the percentage of requests or transactions that result in errors. This can be important for identifying potential issues or problems with a system.
        
        `Resource utilization`
        : This KPI measures the percentage of available resources (such as CPU, memory, or storage) that are being used by a system or application. This can be important for understanding capacity and performance, and for identifying potential bottlenecks or issues.
        
        `Capacity utilization`
        : This KPI measures the percentage of available capacity (such as bandwidth or storage) that is being used by a system or application. This can be important for understanding capacity and performance, and for identifying potential bottlenecks or issues.

        Tracking these and other KPIs can help organizations to understand the performance and capacity of their IT systems and applications, and to identify potential issues or problems that may need to be addressed.

        ---
        Compliance monitoring and root cause analysis are important activities for ensuring that an organization's technology infrastructure, systems, and applications are operating in a compliant and effective manner. Some specific key performance indicators (KPIs) that an organization can track when it comes to these activities include:

        
        `Compliance rate` 
        : This KPI measures the percentage of transactions or processes that are compliant with relevant regulations and standards. This can be important for ensuring that an organization is meeting its compliance obligations.
        
        `Number of compliance violations` 
        : This KPI measures the number of instances in which an organization's systems or processes are found to be non-compliant. This can be important for understanding the extent to which an organization is meeting its compliance obligations.
        
        `Time to compliance` 
        : This KPI measures the time it takes for an organization to bring its systems or processes into compliance after a violation has been identified. This can be important for ensuring that issues are addressed promptly and effectively.
        
        `Compliance cost` 
        : This KPI measures the financial cost of maintaining compliance with relevant regulations and standards. This can be important for understanding the resources that are required to meet compliance obligations.
        
        `Root cause resolution rate` 
        : This KPI measures the percentage of problems or issues that are successfully addressed at the root cause level. This can be important for ensuring that issues are not just being patched over, but are being fully resolved.
        
        `Mean time to resolution (MTTR)` 
        : This KPI measures the average time it takes to resolve a problem or issue. This can be important for understanding the efficiency and effectiveness of an organization's problem-solving processes.
        
        `Mean time between failures (MTBF)` 
        : This KPI measures the average time between failures or issues with a system or application. This can be important for understanding the reliability and stability of a system.
        
        `Mean time to detect (MTTD)` 
        : This KPI measures the average time it takes to detect a problem or issue. This can be important for identifying and addressing problems as soon as possible.

        Tracking these and other KPIs can help organizations to understand the compliance and reliability of their IT systems and applications, and to identify and address potential issues or problems that may need to be addressed.

    ??? tip "Incident Response"
        ### Incident Response

        <figure markdown>
            ![Incident Response](/assets/getting-tactical/incident-response.png){ width="800" }
        </figure>

        Incident response is the process of managing and responding to security incidents or other disruptions that may impact an organization's technology infrastructure, systems, or applications. Some specific key performance indicators (KPIs) that an organization can track when it comes to incident response include:

        `Mean time to identify (MTTI)`
        : This KPI measures the average time it takes to identify a security incident or other disruption. This can be important for identifying and addressing issues as soon as possible.
        
        `Mean time to respond (MTTR)`
        : This KPI measures the average time it takes to respond to a security incident or other disruption. This can be important for ensuring that issues are addressed promptly and effectively.
        
        `Mean time to recovery (MTTR)`
        : This KPI measures the average time it takes to recover from a security incident or other disruption. This can be important for ensuring that systems are restored and operational as quickly as possible.
        
        `Number of incidents`
        : This KPI measures the total number of security incidents or disruptions that an organization experiences over a given time period. This can be important for understanding the frequency and impact of such incidents.
        
        `Incident severity`
        : This KPI measures the severity or impact of security incidents or disruptions on an organization. This can be important for understanding the potential impact of such incidents and for prioritizing response efforts.

        Tracking these and other KPIs can help organizations to understand the effectiveness of their incident response processes, and to identify areas where improvements may be needed.

??? note "Increase Access, Throughput, and Value From Data via Splunk"
    ## Increase Access, Throughput, and Value From Data via Splunk

    To achieve this, organizations need to understand the metrics that make them tick, leverage the data to understand changes in their environment early, and be quick to take action.

    Here are four recommendations for organizations to help them understand their own key performance indicators (KPIs) or metrics:

    `1. Identify the key business objectives`
    : The first step in understanding your own KPIs is to identify the key business objectives that the organization is trying to achieve. This will help to ensure that the KPIs chosen are aligned with the goals of the organization and are focused on delivering value.
    
    `2. Determine the most relevant metrics`
    : Once the key business objectives have been identified, the next step is to determine the most relevant metrics that can be used to track progress towards those objectives. This may involve considering a range of different metrics, such as financial metrics, operational metrics, customer metrics, or employee metrics.
    
    `3. Establish baseline metrics`
    : In order to track progress over time, it is important to establish baseline metrics that can be used as a reference point. This may involve collecting data on the current state of the organization, so that changes can be measured and tracked over time.
    
    `4. Monitor and analyze metrics regularly`
    : Once the relevant metrics have been identified and baseline data has been collected, it is important to monitor and analyze the metrics on a regular basis. This may involve using tools such as Splunk to visualize and analyze the data, and to identify trends, patterns, or issues that may need to be addressed.

    Understanding your own KPIs and metrics is an important step in leveraging data to understand changes in your environment and take quick action. By identifying the key business objectives, determining the most relevant metrics, establishing baseline metrics, and monitoring and analyzing metrics regularly, organizations can increase access, throughput, and value from their data.
