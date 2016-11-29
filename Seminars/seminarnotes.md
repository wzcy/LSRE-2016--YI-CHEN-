Seminar1
Questions:
1 What is large scale requirements engineering?
2 What are the challenges in large scale requirements engineering?
3 What is the order of magnitude of the number of requirements we are
discussing?

Searching answer of the questions:
1.1Large companies often manage thousands of requirements continuously arriving from multiple sources.These requirements are often inter-related and originate from an increasing number ofcustomers, end users, developers, subcontractors, product features, external system interfaces, and so on. This context is deﬁned as very large-scale RE (VLSRE) and challenges RE and management capabilities.
Reference:[1]Wnuk K, Kabbedijk J, Brinkkemper S, et al. Exploring factors affecting decision outcome and lead time in large‐scale requirements engineering[J]. Journal of Software: Evolution and Process, 2015, 27(9): 647-673.
2.1The requirements selection process is a complex decision problem that introduces several challenges, for example, shifting goals, time stress, conﬂicting viewpoints on the value, anduncertain estimates to name just a few.To effectively improve RE decision making, more effortshould be dedicated towards decision-making aspect identiﬁcation 
2.2 Alen ljung andPersson listed ill-structured problems, uncertain environments, shifting goals, action andfeedback loops, time stress, high stakes, multiple-stakeholder situations, and organizational goalsand norms among the decision-making challenges
2.3 Ngo-The and Ruhe argued that requirements decisions are hard because of the incompleteness of the available information, and any notion of strict optimality is not appropriate in this context
2.4 Karlsson et al. [3] identiﬁed release planning based on uncertain estimates as one of the challenges in MDRE that is related to RE decisionmaking. 
2.5 Another challenging aspect of decision making, mentioned by Fogelstrom et al. andKarlsson et al. , is ﬁnding the right balance between selecting commercial requirements andinternal quality requirements. 
2.6 requirements prioritization was recognized as challenging because of conﬂicting priorities between stakeholders, complex dependenciesbetween requireme nts , or multi-objective decision problems . 
2.7 McAvoy and Butler discovered that the high empowerment level of a cohesive agile software development team maynegatively impact decision making.
Reference:
[2]Portraying the practice of decision-making in requirements engineering: a case of large scale bespoke development
Alenljung B, Persson A
[3] Engineering and Managing Software RequirementsNgo-The A, Ruhe G
[4]When product managers gamble with requirements: attitudes to value and riskFogelstrom N, Barney S, Aurum A, Hederstierna A
Find Article2009
3.
[5]"Requirements Prioritization" Patrik Berander and Anneliese Andrews
[6] Wnuk K. Visualizing, Analyzing and Managing the Scope of Software Releases in Large-Scale Requirements Engineering[D]. Lund University, 2012.


Answer for question 1:
Large scale requirement engineering means the thousands of requirement continously arriving form multiple resources. And theses requirements are usually inter-related and originate from an increasing number of stakeholders such as customers, end users, developers , subcontractors,product features, external system interfaces,and so on.

Answer for question 2
There are many challenges for large scale requirement engineering. There are ill-structured problems, uncertain environments, shifting goals, action andfeedback loops, time stress, high stakes, multiple-stakeholder situations, and organizational goalsand norms among the decision-making challenges. Besides, requirements decisions of large scale requirement are hard because of the incompleteness of the available information. What's more, release planning based on uncertain estimates as one of the challenges in MDRE. Addtional,  it is difficult in ﬁnding the right balance between selecting commercial requirements andinternal quality requirements. And requirements prioritization is another challenges because of conﬂicting priorities between stakeholders, complex dependenciesbetween requireme nts , or multi-objective decision problems. Last but not least, high empowerment level of a cohesive agile software development team may negatively impact decision making.

Answer for question 3:
Small-Scale Requirements Engineering(SSRE) 10 requirenets
Medium-Scale Requirements Engineering(MSRE) 100 requirements
Large-Scale Requirements Engineering(LSRE)  1000 requirements
Very Large-Scale Requirements Engineering(VLSRE) 10000 requirements

Summary of The Art and Science of Software Release Planning:
The article introduces two approaches to Requirement Planning(RP). One is art of RP approach which relies on human intuition, communication, and capability to negotiate between conflicting objectives and constraints. The science of RP approach formalizes the problem and applies computational algorithms to generate best solutions. And then the authors present synergy between the two, integrating human and computational intelligence to define optimal RP feature assignments. There are some aspects should be emphasized on the science of RP approach. First, we should pay attention to two type of dependency constrains: a coupling relation called C and a precedence relation called P. Second, each release tasks should within the resource constraints. Third, set ordinal nine-point scale to allow sufficient differentiation in the degree of importance for the stakeholders. Forth, use value and urgency to prioritize the features. Finally, we can use the these number mentioned above to calculate the Objective function which indicate the prioritization of the specific feature in specific release. After we get result of science of RP approach, The decision maker can then evaluate them based on the “art” knowledge and experience before making a final decision.
Against the read paper:
The article mainly discuss the way of formulating how to assess the prioritization of the features in science RP approach. However, how to combine the art and science approach tightly and what should pay attention to when we use art approach? The author did not mention these questions. Besides, high expert knowledge is required in art approach and how to balance the art and science approach. I think these things should be taken into consideration in different projects and different situations.

Summary of Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model:
The article introduce a QUPER model which can find the right balance among competing quality requirements. It is a conceptual model that incorporates quality as a dimension in addition to the
cost and value dimensions used in prioritization approaches for functional requirements has been
developed. The QUPER model has three main steps: 1. Problem definition. 2. Model definition 3. Model validation. And then the paper present an industrial evaluation of the model.The overall result indicates that the QUPER model is relevant in high-level decision making for quality requirements in an activity such as release planning. The concepts of breakpoints, competitor analysis, and identification of own products quality level provides a greater understanding of the
current market segment and why a certain quality level is needed in a particular release. And the QUPER is proved that it is easy to understand and learn, it also improve the communication among staff when deal with requirement prioritization. However the QUPER also has two challenges: 1. It is difficult to identify and specify the values for the differentiation and saturation breakpoints. 2. Different staffs have different understanding of breakpoints value. 

Summary of A Market-Driven Requirements Engineering Process: Results from an Industrial Process Improvement Programme: 
This paper describes a specific industrial RE process for packaged software, called REPEAT (Requirements Engineering ProcEss At Telelogic). REPEAT is used in-house at Telelogic for eliciting,
selecting and managing requirements on a product family called Telelogic Tau - a software development environment for real-time systems. There are several actors involved in REPEAT: Requirements Management Group (RQMG), Issuer, Customers and users, Requirements team, Construction team, Test team, Expert, Requirements Database (RQDB). And there are six stages of REPEAT: new, assigned, classified, rejected, selected and applied. It is believed that REPEAT can cause the dramatic improvement in release precision and product quality are the prioritization of requirements, the effort estimation, the detailed requirements specification, and the continuous change management throughout design, implementation and verification. However, there are still some challenges such as: Overload control, Connecting fragments, Bridging the chasm between elicitation and selection, Long-term product strategy for a diversity of market segments, Hierarchical use case modelling, Cost-value use case prioritization.
Summary of A Case Study Evaluation of the Guideline-Supported Q UPER Model for Elicitation of Quality Requirements:
This paper presents the first complete version of the QUPER model, including the detailed guidelines of how to apply QUPER in practice.The development, evolvement, and refinement, parts of the model has been validated in a series of steps in prior industry validation.The main new contribution of this paper is the pritiacl guidelines. And the cost dependency is added into QUPER because dependencies may have a major impact on the estimated cost for other QR. Besides, the complete version of QUPER was evaluated in industry with 24 industry professionals using real QR. The paper result emphasizes that it is rather important to having concrete guidelines combined with instructive examples from real practice.

Seminar2
1. Read up on GAP / CVA / IVA Analysis!
2. What tools are available for Continuous Integration?
3. Try one out (build something, have it run tests automatically, . . . ),
and write up your experiences.
4. What is technical product management?
5. What is roadmapping? How can you do it large scale?

Answer for question1:
(1) GPA analysis measures positive and negative “gaps” between what the product offers and what
the customer perceives.Features and characteristics of the product are identified and their fulfillment of customer needs is mapped. A positive gap represents when a product delivers more than is expected,a negative gap the opposite.

(2) Customer Value Analysis (CVA) is similar to GPA analysis but also includes the perspective of using competitor products in the analysis and the evaluated product is graded with regards to the value of a need in comparison to alternatives.

(3) Internal Value Analysis (IVA) is a technique to measure whether or not a product is in line with the product strategies (and the company strategies), taking limited resources and other products into account.Using IVA, factors like resources available (time, money, risk, and knowledge) can be taken into consideration, complementing data from both GAP/CVA analysis, prioritization of requirements, dependency mapping, and cost estimates. Combined, this can form decision support material for requirements selection taking product strategies into consideration.

Answer for question2: 
Jenkins: Jenkins is an open source CI tool written in Java. The Jenkins has two major jobs: one is building/testing software projects continuously and another one is monitoring externally run jobs. It can run tests automatically.

Answer for question3:
Technical product management focus on technology part of the project. It requires to use technical skills to improve prioritization and planning. It includes assess the risks of certain feature and communicate with develop team about the stories or tasks in detail. Besides, it requires method to close the communication gap between developer and the rest of employees.

Answer for question4: 
A roadmap is a relatively common way of representing targets based on development in the context of time and releases. As for large scale, the roadmapping should reflect not only current market knowledge and customer priorities but also the long-term goals set for a certain product. Ignore this product strategy to build roadmap for a product may success in a short term but expense at long term goal.

Summary of A Cost–Value Approach for Prioritizing Requirements: 
The paper presents a cost-value approach for prioritizing requirements and then apply it to two commercial projects. There are five steps for cost - value approach: 1. Requirements engineers review the requirement and make sure there is no ambiguous in requirement. 2. Customers and users use AHP pairwise comparison to assess relative value of the candidate requirements. 3. Software engineers use AHP pairwise comparison to access relative cost of the candidate requirements. 4. Software engineers use AHP to calculate the relative value and cost for each candidate requirement and implement a cost-value diagram 5. Stakeholders discuss on the cost-value diagram and decide which requirements should be put into which release. As for cost-value diagram the high ratio of value to cost means a value–cost ratio exceeding 2, medium ratio of value to cost means a value–cost ratio between 0.5 and 2, low ratio of value to cost means a value–cost ratio lower than 0.5. Through the two commercial project, we can draw a conclusion that provides a clear indication of the relative costs and values of all candidate requirements. However these method does not consider the interdependence between project. Besides, pairwise comparison is difficult for large scale requirement.

Summary of requirements engineering: In search of dependent variables :
The paper firstly creates a taxonomy of levels on which the impact of RE process changes can be assessed. And it exposes that the impact are multi- perspective in high level of taxonomy. Third, it reflect that the product strategies should reflect long term goal, but these goals also have to be aligned to both current market and technology trends. Finally, it approves that the the assessment of requirements engineering process change is a complex undertaking from wider perspective and the assessment of requirements engineering process change is a complex undertaking.

Summary of A Method for Early Requirements Triage and Selection Utilizing Product Strategies:
This paper presents a method that utilizes strategies for early requirements triage called Early Requirements Triage and Selection(MERTS). This method has two main purpose: First, it acts as a stepwise guide to creating product strategies taking both strategic and technical views into account. Second, the strategies resulting from MERTS can be used by managers to perform requirements triage, in essence selecting the “right” requirements for realization. The contribution of MERTS is to support explicit discussions, and the formulation and documentation of strategies, enabling requirements triage.

The summary of Requirements Abstraction Mode:(focus on the goal)
The goal was to offer Product Managers a model supporting the ability to handle and work with requirements on multiple levels of abstraction in a continuous product-centered requirements engineering effort.This meant going from, e.g., one repository where all requirements were kept ,
regardless of abstraction level, to a structure mirroring the reality of the requirements coming in.

The summary of Quality requirement in Industrial Practice -- An Extended Interview Study at Eleven Companies
The paper shows the result of an empirical study that examines QR in practice in 11 software companies. First, it introduce the different type of companies have different opinion about the important aspects of quality requirements. As for B2C companies, usability is deemed the most important QR. As for B2B companies, safety is considered the most important QR. Then the author have a deep research in the interdependencies of the QR. REQUIRES (B2B view) and CVALUE(B2C view) are considered as the most common and important interdependency types to identify. AND and OR were considered the least common and least important interdependency types. As for cost estimation, the paper provides three contribution: 1.There is no distinction between FR and QR during cost estimation. 2. Expert opinion is the predominant method for estimation 3. In the worst case, B2B has much more inaccurate estimates than B2C. As for dismissal of QR, performance requirements are more often dismissed due to the difficulties in proper estimation for B2C companies. while for B2B, QR that are not considered important. Overall speaking, Poor cost estimation and the fact that QR have lower priority than FR are the main reason for dismissal.

Seminar3:

1. Read up on the Boston Matrix:
The Boston Matrix describes the impact of market share and market growth on businesses by using four categories:dogs, cash cows, question marks (or problem children) and stars. 
Dogs are confronted with low market share and low market growth problems. They tend to absorb cash rather than generate it and are developing in a slow growing industry.
Cash cows enjoy a high market share in low growing market. These units usually generate cash in excess but opportunities or new investments are limited, due to the low growing market. The aim is to ‘’milk’’ them as long as possible.
Problem children have low market share in a high growing market. These are products or units that grow rapidly and consume a high amount of resources, but generate low cash because of the low market share. They have the potential to grow market share and generate income thus turning into stars or cash cows when market growth slows, but there is also the possibility of them degrading into dogs with little return and wasted investment. Problem children are also called ‘question marks’ because we must analyze them carefully to decide whether they are worth the investment required to increase market share.
Stars represent the ideal combination for a company: high market share in a fast growing industry, two elements which generate cash and further opportunities.
Reference:http://www.oxlearn.com/arg_Marketing-Resources-The-Boston-Matrix_11_35

2.How do you connect your requirements to your architecture?
Requirement management is the third stage of the architecture. The first and second stage are Portfolio management and product roadmapping. The forth stage is release planning. In the architecture, the requirements is gathered from market trends, contract, partner requests and board requests which are links to the first stage and some external stakeholders. Then the requirements need elicitation, specification, prioritization and selection in the architecture. The customer and sales$market have a big influence on the requirement organizing. In the end, we get the release definition. The release planning will determining what requirement will be done in which release and how will it be scheduled. All in all, requirements are essential elements for the architecture. 

Reference:De Weerd, I. Van, et al. "Towards a Reference Framework for Software Product Management." Requirements Engineering (2006): 319-322.

3.Can you connect all requirements directly? What do you do if you cannot?
I cannot connect all requirements directly. The reason are as follows: (1) There is limitation of resources and time. (2) Some requirements may need technical support or policy supports. (3) Some requirements may not target the most important customer population. 
First, I will analyze the resources and time to market. Then use cost-value to choose the most benefit requirements within the limitation of resources and time. Finally, organize the requirements which consider the dependencies as well.

Reference:De Weerd, I. Van, et al. "Towards a Reference Framework for Software Product Management." Requirements Engineering (2006): 319-322.

Summary of Are you biting off more than you can chew? A case study on causes and effects of overscoping in large-scale software engineering:

The paper presents a result from nine interviews and it is validate by six practitioners via questionnaire. The results provide an increased understanding of scoping as a complex and continuous activity, including an analysis of the (1)causes such as continuous requirements inflow from multiple channels , requirements not agreed with development team, no overview of software resource availability, low development team involvement in early phases, detailed requirements specification produced upfront, unclear vision of overall goal , weak process adherence and scope and deadline dictated by management, (2)effects such as many changes after the project scope is set, quality issues, delays, customer expectations are not always met, communication gaps, challenge to keep SRS updated, overtime, changed/cancelled product plans, low priority for administrative tasks, (3)and a discussion on possible impact of agile requirements engineering practices to the issue of overscoping: one continuous scope and release planning flow, Cross-functional development teams, Cross-functional development teams. 

For: This paper presents a deep discussion of causes and effects of overscoping in large-scale software engineering. As far as I am concerned, continuous requirements inflow from multiple channels is truly a serious cause. Because we will have problem with meeting customer expectation if we do not manage and balanced against the amount of available capacity. So, we should consider the increasing requirements from large number of customers in LSSE.

Against: This paper just investigated one company towards the topic. If the paper can include other companies and other aspects such as marketing and sales, it will make the paper more reliable.

Summary of An Industrial Survey of Requirements Interdependencies in Software Product Release Planning:
The paper find that only 20% of requirements are singular. So it is rather important to put emphasis on the interdependencies of requirements.There tend to be more functionality-related interdependencies in a bespoke development situation, whereas there are more value-related interdependencies in a product development situation. And then the author introduce a visualization technique which proved to be very powerful to support reasoning about possible and good ways of partitioning a set of requirements. Finally, the concepts of requirements coupling and release coupling is introduced.

For: The paper has a precise discussion on the interdependencies of requirements. From the paper’s presentation, I can draw a conclusion that there are much more interdependencies among the requirements that we can forecast. It is rather important to use the right technique to analyze the interdependencies and pay attention to it when dealing with release planning.

Against: The author did not relate the issue of requirements interdependencies to that of dependencies between requirements and the code base. Some implemented requirements are also important to consider the dependencies.

Summary of Exploring factors affecting decision outcome and lead time in large-scale requirements engineering:
The paper reports on an investigation of decision making in RE. The author points out several results: (1)The lead time to make a decision increases when more products, considered as a proxy for the decision complexity, are affected by this decision. (2) The statistical analysis of the decision log suggests no significant relationship between the release of the product line that a change impacts and the decision lead time (3) The lead time for decisions is shorter when the change requests are issued by important customers (4) The chance of accepting a change request is higher if it affects a greater number of products (5) Change requests affecting late releases have a significantly higher probability of acceptance (6) Change requests issued by important customers are more likely to be accepted (7)The lead time to reject a decision is significantly longer than that to accept a decision.

For: The paper have a deep consideration on the decision making in RE. I agree on the change requests issues by important customers are more likely to be accepted. It is because that if we can ask for additional details from more important customers, the lead time may be highly reduced.

Against: The paper did not consider the dependencies between software components and number of stakeholder involved in the change discussion. These two factors can also influence the lead time of decision making.

Summary of Market-Driven Requirements Engineering for Software Products:
When the requirements engineering process is enacted in a market-driven context the developing organization faces special challenges. First, it introduces the different kinds of challenges that may be faced in the market-driven requirements engineering such as Balancing market pull and technology push, Chasm between marketing and development. Second, the author introduces the MDRE process. In this part, the author mentions the alfa requirement and beta requirements. alfa requirement is a requirement that has such a high inherent quality that it ideally should be selected.. Correspondingly, beta requirements are those that ideally should be rejected, as they are of inherently low quality. Third, a requirements state model is elicited. It contains seven steps for a requirement from candidate to released. Finally, a typical MDRE repository is introduced which contains attribute, value, assigned in state.

For: It is a introduction of MDRE. It contains several parts of MDRE: (1) A process quality model for assessing the goodness of requirements selection (2)A typical requirements state model to be used in progress tracking (3)A typical requirements repository to be used in data management. These three part provide me a detail structure of MDRE.

Against: The author wants to use value-cost method to determining the requirement is alfa or beta. However, value contains many aspects such as value for a certain market segment, value for the internal architecture to enable future feature development, value for strengthening company image, value for entering new markets. And these value should also consider the dependencies between the requirements. So I am concerned that it is difficult to trade-off among these aspects and it is also have problem in calculating value-cost when considering the dependencies.

Summary of Towards a Reference Framework for Software Product Management:
In this paper, authors present a reference framework for software product management, in which the key process areas, namely portfolio management, product roadmapping, release planning and requirements management, are identified, as well as the stakeholders and their relations. portfolio management contains four main processes: partnering & contracting, market trend identification, product lifecycle management and product line identification. Roadmapping is r for planning and portraying the use of scientific and technological resources, elements and their structural relationships over a period of time. Requirements management contains the activities of gathering, identifying, revising and organizing incoming requirements from the various stakeholders. Software release management starts with prioritization, then selected, then a release definition is written that is validated by different stakeholders.

For: This paper provides a detail framework for software product management. Through the article, I have a deep understand on the divided four parts -- portfolio management, product roadmapping, release planning and requirements management. Figure 1 describe the relation among these four part vividly.

Against: I have not find any against so far.

Summary of Scaled Agile Framework:
The Scaled Agile Framework is a freely revealed knowledge base of proven, integrated patterns for enterprise-scale Lean-Agile development. It is scalable and modular, allowing each organization to apply it in a way that provides better business outcomes and happier, more engaged employees. Ir has two level of views: three level view is well suited for solutions that require a modest number of Agile teams, as well as smaller systems, products and services that are largely independent of each other. The “4-level view” supports those building large, integrated solutions that typically require hundreds or more practitioners to build and maintain The SAFe increase the 20-50% productivity, increase more than 50% quality, 30-75%faster time to market and increase in employee engagement and job satisfaction.

For: It is free and have lot of benefits mentioned above. It is suitable for companies to build agile team and gain benefits from it.

Against: I have not find any against so far.



Seminar4:

Summary of What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting:
The paper introduces a technique called feature survival charts which is for visualization of scoping change dynamics. This technique increase the understanding of performance of scoping process.It is because it provides feedback not only about ongoing scoping activities but also a a visualization of previous project scoping activities. And then the author applied this technique into case companies, the result indicate that FSC outperform the past used table-based textual method to track the scope changes in the case company. 

For: A visualization of scoping change dynamics is really a good technique to track the scope change. It can help companies to get a lesson from the previous project by visualization the scope change. For example, if the company find that there are many late removal of previously accepted features in last project of visualization. The company should consider the reason why this phenomenon happened. The reason can be lack of resources. So the company may pay more attention to the resources analysis and it may avoid this phenomenon. 

Against: Not a against but a suggestion. A visualization is a excellent method. However, we should not neglect the effect of table-based textual method or documentation. It is because the analysis of the reason why scope change is hard to present in the visualization technique. I suggest that the combine of these two method can benefit the company most.

Summary of Obsolete software requirements:

The paper takes a survey among 219 respondents from 45 countries about the phenomenon of obsolete software requirement. The result indicate that OSRs are the significant challenges for software development companies. And the authors suggest that it is needed to develop automated tools or methods to support identification and management of OSRs. Manually managing OSRs may be sufficient in small project. However, in large scale requirement, it is suggested to develop scalable methods that scale to a reality which is often characterized by large numbers of requirements and a substantial and continuous influx of new requirements.

For: In large scale requirement, there are more than hundred requirements which tend to have large issue related to the presence of OSRs. So the OSRs will have big impact on the large project compared with small project. To short the time for detect and handle the OSRs in large scale requirement, the automated tools or methods is needed. 

Against: As far as I am concerned, It may be a little difficult to build a standard tool for OSRs management. Because different project have different scope, different environment, different stakeholders and so on. These all need to be put into consideration when building this kind of tool. On the other hand, develop a automated tool for identification and management of OSRs in a specific project can be possible. But what is the cost for the tool and how much the company can benefit from it is another question.
