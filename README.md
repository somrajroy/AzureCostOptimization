#### Microsoft Azure Cost Optimization aligned with Azure Well-Architected Framework <br/><br/>
* Cloud cost optimization is a combination of strategies, techniques, best practices, and tools that not only help reduce cloud costs but also maximize the business value of using the cloud. Optimizing cloud costs isn't just about reducing costs; it's also about aligning costs with business goals to create business value because costs cannot be separated from application/workload performance. If an organization was optimizing for cost alone, moving all applications by lift & shift to the smallest VM size would be the way to go, but no business would be willing to take the performance hit. Hence in the Cloud, more than ever, cost and performance are tied together.<br/>
* Eventhough the benefits of Cloud are numerous, the costs quickly add up, especially for customers who are not actively managing their cloud spending. Microsoft recommends customers should take a proactive & continuous approach to "Cloud Cost Optimization" to significantly reduce their Cloud spending without sacrificing the performance and reliability of their services. This article elaborates & describes in great detail about the various options and techniques that can be applied. [Microsoft too has a detailed article on cost optimization and some points will overlap with this document.](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-cost-optimisation/ba-p/3624817)<br/>
* An increase in costs is not necessarily a problem if it's accompanied by an increase in revenue. One of the most important goals is to ensure that costs correlate with productive and profitable activities. Cloud cost optimization is not about cost cutting & reducing cloud costs is not an absolute goal. Rather focus is on [reducing costs in relation to business outcomes](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/business-outcomes/). If a certain cloud spend brings a lot of business value then there is no point reducing costs there. This means there is more then just managing costs. By optimization of cloud costs customers gets the opportunity to optimize all aspects of their cloud computing to maximize business benefits. Some of aspects are; performance of applications, speed of innovation, time-to-market, continuity, compliance and costs.<br/>
* There are three fundamental drivers of cost in Cloud which should be kept in mind while architecting solutions : compute, storage, and outbound data transfer. <br/>
* [According to Microsoft Azure WAF(well architected framework)](https://learn.microsoft.com/en-us/azure/architecture/framework/#cost-optimization) - focus should be on [generating incremental business value early](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/innovate/business-value?source=recommendations). This detailed artcle and covers every aspect of cost optimization on MS Azure as on date. The techniques mentioned below will help customers in making smart investments in the right Azure services and tools and aligning cloud strategy with customers business goals. If done correctly, these cloud cost optimization techniques can help businesses leverage the full power of the cloud to drive innovation, growth, and success.<br/><br/>
  * Increase Linux Compute   : There’s no such thing as the perfect operating system, but nearly everyone in the tech world would probably say that Linux comes close. With the ability to run on almost any machine, configured how client want it, and with a super-low TCO (to name a few of Linux's awesome attributes), a Linux based operating system should be go-to for. Linux will only continue to gain ground as cloud-native apps become more prevalent and companies look for new ways to build the future & create success.<br/>
  * Leverage Automation in Cloud : Apply Automation to increase productivity & optimize performance to deliver business value at lowest price point. With automation customers can stay immune from effects of human error, downtime and outages. Automation enhances system productivity, improves performance, and reduces costs. Cloud is meant for automation. <br/>
  * Review Pricing and Billing Information to leverage the right pricing model for the workloads : Azure provides billing details explaining the cost of cloud services. This information can be analysed & leveraged to identify high-cost areas and generate savings. Understanding cloud costs helps in informed decisions <br/>
  * Start early with cost optimization : Start with the basics and improve over time. [This video about Managing, reporting, and reducing costs in Azure is an excellent guide](https://www.youtube.com/watch?v=XQTQz-MgEBA). Leverage Azure services, tools, and resources to organize and track cost and usage data, enhance control through consolidated billing and access permission, enable better planning through budgeting and forecasts, and further lower cost with resources and pricing optimizations. [Microsoft recommended 7 ways to optimize costs in Azure is a another good place to begin with.](https://azure.microsoft.com/en-us/solutions/cost-optimization/#ways-to-optimize) <br/>
  * Choose right pricing model (payment options) for the use case : Azure provides several payment options for its services. Customers should opt for the most optimized one after forecasting usage patterns which should be improved over time by observing usage patterns. For example - [Customers can optimize cloud investments with Azure Reservations.](https://azure.microsoft.com/en-us/blog/optimize-your-cloud-investment-with-azure-reservations/) and [leveraging Azure Savings plans](https://techcommunity.microsoft.com/t5/azure-compute-blog/optimize-and-maximize-cloud-investment-with-azure-savings-plan/ba-p/3636447) <br/>
  * [Setting budgets](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-acm-create-budgets) : Cloud costs can be controlled by ensuring everyone knows the goals and budgets of each project. Setting a monthly budget to plan is a good step. It helps to measure cost vs output and track cost anomalies. While it is common to have some variations in cloud usage due to seasonality, customers/architects should  keep an eye on any sudden unexpected spikes and out of band spend. Tracking cost anomalies enables customers/architects to respond to cost challenges before they wreck havoc on budget limits. <br/>
  * [Embrace consumption model](https://learn.microsoft.com/en-us/azure/well-architected/cost/design-price)  & align with work cycles: Schedule suspension/deletion of Azure resources to ensure that when people aren’t using them, they also aren’t paying for them. Customers needs to be aware that they pay for what they provision. The gap between consumption and allocation is what causes the large and unexpected bills. The goal of building a performant & complex cloud system isn’t merely to cut costs. It can never be so.It's about identifying waste and ensuring customers are maximizing the value of every dollar spent. Constantly cleaning up of the cloud estate from unnecessary/unwanted resources to maximize benefits should be an regular  process. <br/>
  * Apply governance policies & Implement automated processes to identify resource waste (or idle resources) & prevent cloud sprawl : Cloud sprawl tends to happen when customers lacks visibility into the spread of their cloud instances, services, or providers across the organization. Without governance policies, the self-service nature of the cloud leads to cloud sprawl. Defining and implementing governance policies will help maintain and gain control of unchecked cloud growth. [One under rated feature in Azure is Azure Policy and automation](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-policy-recommended-practices/ba-p/3798024) - this helps customers automate operation tasks, monitor for deviations, remediate and enforce standards and configuration automatically. Customers should improve their Azure Policy posture with the recommended practices from Microsoft. Secondly, Identify unused and unattached resources and remove them to eliminate unnecessary expenses. Resources should be de-provisioned immediately when job finishes. For example [Delete unattached disks](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/find-unattached-disks), idle load balancers etc. Automation should be applied to do all these & that is what cloud is meant for <br/>
  * Tag Azure resources : Resource tagging is a cloud cost optimization strategy that involves assigning tags to Azure resources to organize them better and monitor them to subsequently optimize workloads once lay of the land is understood/stable. A good resource tagging policy can save costs. For example, resources with non-production tags can be de-provisioned or shut down in holidays or when not used. Tags helps to analyze and attribute expenditure. Tags makes it easier to accurately identify the usage and cost of systems, which then allows transparent attribution of IT costs to individual workload owners. This helps measure return on investment (ROI) and gives workload owners an opportunity to optimize their resources and reduce costs. Tagging resources increases the amount of data monitoring tools can obtain.<br/>
  * [Refer Azure Advisor](https://learn.microsoft.com/en-us/training/modules/get-started-azure-advisor/) recommendations regularly and take actions if needed. [Azure Advisor helps in reducing cost & increasing operational excellence.](https://learn.microsoft.com/en-us/azure/advisor/advisor-overview)  <br/>
  * [Right size services/resources](https://learn.microsoft.com/en-us/azure/advisor/advisor-reference-cost-recommendations) : Every application’s and workload’s needs are unique — which changes/evolve over time. Hence it is very important to measure efficiency and then optimize over time. When key factors such as demand patterns and seasonality are well understood, it becomes easier to leverage techniques and tools to predict cloud spend. [For example to right size VM's start with four main metrics](https://learn.microsoft.com/en-us/azure/advisor/advisor-cost-recommendations) - CPU, memory, I/O and networking. <br/>
  * Automate capacity planning : Cloud addresses the old & critical pain point –  infrastructure supply is static while application demand is dynamic – and allows matching demand with supply in real-time across multiple metrics and dimensions. Leverage just-in-time features to the fullest to avoid overspend with autoscaling & elasticity to start with. Auto-scaling encourages automation and drives more efficiency. <br/>
  * Limit data transfer fees : [These charges are labelled as Bandwith pricing](https://azure.microsoft.com/en-in/pricing/details/bandwidth/). Private endpoints can be very useful. Limiting egress through Private IPs can be a good strategy to reduce egress charges. It is recommended to reduce the number of Public IPs in an architecture which is beneficial both from a cost as well as security perspective. Ensure that systems that swap a lot of data are together in same cloud/region. Start with an assessment of cloud provider's transfer fees. Then, adjust the cloud architecture to minimize the necessary data transfers. For example, move on-premises applications that frequently access cloud-hosted data into the cloud to eliminate hops. Data transfers from Azure services to Azure CDN are free of charge. Customers can consider Azure CDN for applications with higher outbound data transfer requirements, such as streaming services, for example. There can be some rule/metric in place, for example, no more than 15% of cloud expenditure should be spent on data transfer.<br/>
  * Azure Hybrid Benefit (AHB)/Bring-your-own-license (BYOL) : [Azure Hybrid Benefit is a licensing benefit that helps to significantly reduce the costs of running workloads in Azure Cloud](https://azure.microsoft.com/en-us/blog/save-big-by-using-your-onpremises-licenses-on-azure/). Its an azure based program that providing BYOL to Azure and it available for Enterprise customers with Software Assurance that provides license mobility. It works by reuse on-premises Software Assurance-enabled Windows Server, RedHat, SUSE and SQL Server licenses on Azure. Azure Hybrid Benefit can lead to the highest level of savings on VMs i.e. up to 82% off pay-as-you-go pricing. <br/>
  * Leverage Microsoft Azure cost monitoring & management tools regularly : Managing cloud costs is too complex for humans to do alone. To address this issue Microsoft Azure provides a suite of tools to track spending across individual Azure services, provides future bill forecasts and alerts users when they go over budget. Cost Management is a free tool built into the Azure portal. It collects data and enables analysis that can help save costs on Azure services. Azure provides additional tools for cost planning and optimization, including the Azure Advisor, Azure Cost Management + Billing, Cost Calculator, Cost Analysis, Azure Budgets, and Cloudyn, which lets track resource usage and expenditure for Azure alongside other clouds. <br/>
  * [Azure cost analysis](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/quick-acm-cost-analysis) : Once workloads run in Azure, use the cost analysis feature in the Azure portal to understand how much each workload will cost. This tool also forecasts future spending based on current configurations.<br/>
  * [Leverage Azure Dev/Test Pricing](https://azure.microsoft.com/en-us/pricing/dev-test/) :  Azure provides deep discounts on services if they are used for development and testing: For example Run Windows and SQL Server VMs with no charge for Microsoft software (same price as Linux instances), Up to 55% discount on Azure SQL Database,Up to 50% discount on Logic Apps etc. <br/>
  * [Leverage B-series VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/sizes-b-series-burstable) : B-Series VMs grant discounts of between 15-55% compared to equivalent VMs. Identify if there are workloads that need to be available but only occasionally require high performance or throughput, and can be moved  to B-Series VMs. Azure offers B-Series virtual machines, designed for applications that are typically idle and then have sudden bursts of usage. A B-Series VM usually runs with a low, baseline level of CPU power, and as long as this low level is suitable for the workload, customers accumulate credits which can be utlized in "bursts".  <br/>
  * Optimize storage & make use of Azure storage tiering : Storage can become very costly if not optimized properly. [This video from Azure explains in details of storage optimization](https://www.youtube.com/watch?v=9_N-mPxywwo) along with strategy customers should follow for storage tiering. Secondly, customers should understand the true costs of traditional storage and leverage Azure storage to reduce cost. For example - Azure file storage can reduce TCO by up to 70% compared to traditional storage. [This article helps understand the true cost of traditional storage and how Azure File storage can save upto 70%](https://techcommunity.microsoft.com/t5/azure-storage-blog/the-true-cost-of-traditional-file-storage/ba-p/3797945)<br/>
  * Base VM's stop/start schedule on usage : it’s highly recommended to perform an analysis of usage patterns and availability so as to create a VM stop/start schedule that is optimal. This custom scheduling can be combined with autoscaling for better cost-effectiveness in the long run.  <br/>
  * (Choosing the right technology) Rearchitect workloads to containers/microservices : Customers should check workload affinity and consider switching to containers/microservices. Hosting costs will immediately reduce. Containerazation of cloud estate can lead to a leaner Cloud environment with much lower cost.  <br/>
  * (Choosing the right technology) Serverless : Cloud native design of workloads is one of the most important aspect of cost optimization best practices. Serverless functions runs on demand, based on user-defined triggers. Serverless computing is best suited for compute-intensive workloads that run intermittently. <br/>
  * Avoid undifferentiated heavy lifting and leverage managed services : Minimizing overhead is a fundamental business process. For example moving away from traditional databases to PaaS options reduces cost. Customers can shift focus towards their core value and leave the burden of performing IT services to Azure. Managed services also helps upgrade the infrastructure and guide future applications to keep pace with new upcoming technologies. MS Azure continiously improves & releases changes on a near-constant basis so customers can leverage up-to-date innovations and increase productivity. However customers should keep in mind that - Ensuring that the extra PaaS/SaaS charges are offset by savings in developer/operational overhead is key for justifying PaaS/SaaS service.<br/>
  * Reduce licensing burden :  Software licensing is a major component of cloud operating costs. Manual license management is challenging, increasing the risk of paying for unused software licenses. Migrating to an open source equivalent can save millions. <br/>
  * Choose the right region : Azure pricing often varies by regions -- with the North American regions typically being the cheapest -- so selecting a certain region could save money. If possible, move workloads to a less expensive region.(consider network latency and packet loss)<br/>
  * [Optimize networking cost with routing preference](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/routing-preference-overview) : Routing Preference is a process in which you can traffic your route between Azure and the Internet. [This also applies to storage cost optimization](https://azure.microsoft.com/en-us/updates/azure-routing-preference-is-now-generally-available/). The terms "cold potato routing" and "hot potato routing" are also used to describe these alternatives. <br/>
  * Establish a review cadence : Cloud Cost Optimization should be a continuous process to measure and monitor overall efficiency of workloads. Keeping the cloud environment constantly optimized ensures that customers capitalize on the promise of the cloud — only pay for what they use — by constantly ensuring that applications are receiving exactly the resources they need to deliver on their SLAs, as cost-effectively as possible. One good approach would be to periodically perform Azure Well-Architected reviews & implement FinOps using Azure Well-Architected framework. The overall process can consist of - Review spend, Action findings, Monitor actions, Automate & Document. Establishing a review cadence will reduce costs monthly and will provide larger savings over a customers lifetime on Azure. [Progress comes through iteration](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices#iteration) <br/>
  * Support and upskill your teams : As with everything in technology, the greatest standards are only as good as how well they are followed. The limiting factor, more often than not, isn’t the capability of the technology, but the people and processes involved. Microsoft provides full details of cost of it's various services & also elaborate billing information about what is being paid for. These details, breakdown or itemization of costs is the map to savings. Customers should prioritize the highest-spend services for a detailed analysis. Getting resources upskilled & trained to get full understanding of costs is very productive & essential, because this allows better judgments to be made about what should be purchased or avoided. Below are some key official trainings from Microsoft.<br/>
      * [Microsoft Learning Paths](https://learn.microsoft.com/en-us/training/browse/) is a very good repository. If we search on by "Well-Architected Framework" in search bar then all Microsoft tranings related to WAF can be found. <br/>
      *  [Build great solutions with the Microsoft Azure Well-Architected Framework](https://learn.microsoft.com/en-us/training/paths/azure-well-architected-framework/?wt.mc_id=3reg_17567_webpage_reactor)<br/>
      *  [Introduction to analyzing costs and creating budgets with Microsoft Cost Management](https://learn.microsoft.com/en-us/training/modules/analyze-costs-create-budgets-azure-cost-management/)<br/>
      *  [Control Azure spending and manage bills with Microsoft Cost Management + Billing](https://learn.microsoft.com/en-us/training/paths/control-spending-manage-bills/)<br/>
      *  [Configure and manage costs as a Microsoft partner by using Microsoft Cost Management](https://learn.microsoft.com/en-us/training/modules/manage-costs-partner-cost-management/)<br/>
      *  [Microsoft Azure Well-Architected Framework](https://www.youtube.com/watch?v=dT233xJ3xPs)<br/>
  
 #### Further References <br/>
* [The comprehensive WAF Cost Optimization documentation](https://learn.microsoft.com/en-us/azure/architecture/framework/cost/).<br/>
* [4 cloud cost optimization strategies with Microsoft Azure with E-Book](https://azure.microsoft.com/en-gb/blog/4-cloud-cost-optimization-strategies-with-microsoft-azure/)<br/>
* [Managing, reporting, and reducing your costs in Azure | Azure Friday](https://www.youtube.com/watch?v=XQTQz-MgEBA)<br/>
* [Overview of Azure Cost optimization pillar & Principles](https://learn.microsoft.com/en-us/azure/architecture/framework/cost/overview)<br/>
* [Cloud cost-optimization simulator](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/cloud-cost-optimization-simulator#)<br/>
* [Mastering Cloud Cost Optimization: The Principles](https://www.ibm.com/cloud/blog/mastering-cloud-cost-optimization-the-principles)<br/>
* [Optimize Azure costs](https://azure.microsoft.com/en-us/solutions/cost-optimization/#tools)<br/>
* [How to optimize your cloud investment with Cost Management](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)<br/>
* [Azure Cost Optimization Techniques](https://www.linkedin.com/pulse/azure-cost-optimization-techniques-dr-rabi-prasad-padhy?trk=pulse-article_more-articles_related-content-card)<br/>
* [Azure Cost Optimisation - Azure Architecture Blog](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-cost-optimisation/ba-p/3624817)<br/>
* [Diving deeper into Azure cost optimization (Part 1) | Well-Architected Framework](https://www.youtube.com/watch?v=6ynOHAainug&t=15s) & [Diving deeper into Azure cost optimization (Part 2) | Well-Architected Framework](https://www.youtube.com/watch?v=nQ1V19FlSxA)<br/>
* [Azure Cost Optimisation - A practical approach to cost optimize your Microsoft Azure Solutions.](https://www.youtube.com/watch?v=uBIbXdfpHBQ&t=1469s)<br/>

