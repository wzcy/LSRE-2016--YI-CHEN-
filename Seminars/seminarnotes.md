Seminar0
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
