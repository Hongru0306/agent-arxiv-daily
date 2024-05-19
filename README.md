## Updated on 2024.05.19
> Usage instructions: [here](./docs/README.md#usage)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#agent>agent</a></li>
    <li><a href=#llm>llm</a></li>
  </ol>
</details>

## agent

|Publish Date|Title|Authors|PDF|Code|abstract|
|---|---|---|---|---|---|
|**2024-05-16**|**When LLMs step into the 3D World: A Survey and Meta-Analysis of 3D Tasks via Multi-modal Large Language Models**|Xianzheng Ma et.al.|[2405.10255](http://arxiv.org/abs/2405.10255)|null|随着大型语言模型（LLMs）的不断发展，它们与三维空间数据（3D-LLMs）的融合取得了显著进步，这极大地增强了理解和互动物理环境的能力。这篇综述详细探讨了使LLMs能够处理、理解并生成三维数据的方法论，强调了LLMs的独特优势，如上下文学习、逐步推理、开放词汇能力和丰富的世界知识，这些将极大地推动人工智能体在空间理解与交互方面的提升。研究覆盖了从点云到神经辐射场（NeRF）等各种三维数据表示，并考察了它们与LLMs在任务中的结合，如三维场景理解、描述、问答和对话，以及基于LLM的代理进行空间推理、规划和导航。文章还简要回顾了其他结合三维和语言的方法。本文的元分析揭示了显著的进步，但也强调了挖掘3D-LLMs全部潜力的新方法的必要性。因此，我们希望通过本论文为未来的研究指明方向，探索和扩展3D-LLMs在理解和互动复杂三维世界的能力。为了支持这次调查，我们已经在GitHub上建立了一个项目页面，整理并列出了相关论文：https://github.com/ActiveVisionLab/Awesome-LLM-3D。|
|**2024-05-16**|**DEBATE: Devil's Advocate-Based Assessment and Text Evaluation**|Alex Kim et.al.|[2405.09935](http://arxiv.org/abs/2405.09935)|null|随着自然语言生成（NLG）模型的普及，系统地评估机器生成文本的质量变得日益关键。近期的研究引入了基于大型语言模型（LLM）的无参考评价器，它们展现出处理新任务的能力。然而，这些模型通常采用单代理方法，我们认为这限制了它们的表现。因为LLM代理的回答存在偏见，比如对特定文本结构或内容的偏好。本文中，我们提出DEBATE，一个基于多代理评分系统的NLG评价框架，融入了“辩 devil's Advocate”的概念。在该框架中，一个代理被指令批评其他代理的观点，从而可能消解LLM代理答案中的偏见。DEBATE在NLG评价的两个元评估基准，SummEval和TopicalChat中显著优于先前的最优方法。我们还展示了代理之间的辩论广度以及代理的个性如何影响评价器的性能。|
|**2024-05-05**|**Self-Reflection in LLM Agents: Effects on Problem-Solving Performance**|Matthew Renze et.al.|[2405.06682](http://arxiv.org/abs/2405.06682)|**[link](https://github.com/matthewrenze/self-reflection)**|**在这项研究中，我们探讨了自我反思对大型语言模型（LLMs）解决问题能力的影响。我们让九种流行的LLMs回答一系列选择题，以建立性能基准。对于回答错误的问题，我们指导八种不同类型的自我反思LLM代理反思其错误，并为自己提供改进问题解决的指导。然后，根据这些指导，每个自我反思的代理尝试重新回答相同的问题。结果显示，LLM代理通过自我反思显著提高了问题解决能力（ $p<0.001$ ）。此外，我们还比较了各种自我反思方式对性能的单独贡献。所有代码和数据已在GitHub上公开，地址为：https://github.com/matthewrenze/self-reflection。**|
|**2024-05-08**|**Air Gap: Protecting Privacy-Conscious Conversational Agents**|Eugene Bagdasaryan et.al.|[2405.05175](http://arxiv.org/abs/2405.05175)|null|随着大型语言模型（LLMs）在对话式代理中的广泛应用，处理敏感用户数据时引发了严重的隐私问题。这些代理虽能理解并处理上下文，但也可能被恶意一方利用。为此，我们提出了一种新的威胁模型，即第三方应用通过操控交互上下文，误导LLM代理泄露与其任务无关的私人信息。在基于上下文完整性框架的基础上，我们开发了AirGapAgent，这是一种注重隐私的代理，旨在通过限制代理仅访问完成特定任务所需的数据，防止意外数据泄露。通过使用Gemini、GPT和Mistral模型进行大量实验，我们证实了AirGapAgent在抵御这类“上下文劫持”攻击方面的有效性，同时保持了核心代理功能。例如，我们发现对Gemini Ultra代理执行单次查询的上下文劫持攻击，会使其保护用户数据的能力从94%降至45%，而AirGapAgent则能达到97%的防护，使同样的攻击失效。|
|**2024-05-07**|**Deception in Reinforced Autonomous Agents: The Unconventional Rabbit Hat Trick in Legislation**|Atharvan Dogra et.al.|[2405.04325](http://arxiv.org/abs/2405.04325)|null|近期大型语言模型（LLMs）的进展虽为构建自然语言代理提供了强大基础，但同时也引发了关于它们及其基于它们构建的自主代理的安全性担忧。特别是欺骗能力是一个关键问题，我们关注的是AI代理通过混淆和模棱两可来误导、隐藏真相或推广部分不真实的信念的行为，这超越了以往AI安全研究中的撒谎、自私决策或提供错误信息的理解。我们聚焦于一类特定的欺骗，类似于魔术师利用障眼法让兔子从帽子里出现，要么通过隐藏的暗门，要么（我们的重点）通过误导观众注意力在眼前完成这一表演。我们设计了一个新颖的测试框架，展示了LLM代理在具有目标驱动环境的两代理对抗性对话系统中，当被指令在自然语言生成中进行欺骗时，其内在欺骗能力。在这个立法任务“游说”法案的环境中，我们采用强化学习设置来发展欺骗能力，结合语言哲学和认知心理学理论。结果显示，经过多次对抗性互动的强化试验，游说者代理的欺骗能力提高了约40%（相对），而我们的欺骗检测机制能达到高达92%的识别率。这些发现突显了人机交互中的潜在问题，即代理可能操纵人类以实现预设的目标。|
|**2024-05-07**|**Granite Code Models: A Family of Open Foundation Models for Code Intelligence**|Mayank Mishra et.al.|[2405.04324](http://arxiv.org/abs/2405.04324)|**[link](https://github.com/ibm-granite/granite-code-models)**|**大语言模型（LLMs）在代码领域的训练正在革新软件开发流程。如今，这些代码LLMs正逐步融入软件开发环境，以提升人类程序员的效率，并展现出自主处理复杂任务的潜力。要充分利用代码LLMs的全部效能，需要其具备诸如代码生成、修复bug、解释和文档编写、仓库维护等多种功能。本文介绍Granite系列解码器仅有的代码模型，专为代码生成任务而设计，训练数据覆盖116种编程语言。Granite Code模型家族包括从3亿到340亿参数的模型，适用于从复杂应用现代化到设备内存受限场景的广泛需求。在一系列全面任务上的评估显示，Granite Code模型在所有公开源代码LLMs中表现出了最先进的性能。该模型家族针对企业软件开发工作流进行了优化，无论是在代码生成、修复还是理解等任务上都能表现出色，成为一款全能的代码模型。我们以Apache 2.0许可协议发布所有Granite Code模型，供研究和商业使用。**|
|**2024-05-07**|**Iterative Experience Refinement of Software-Developing Agents**|Chen Qian et.al.|[2405.04219](http://arxiv.org/abs/2405.04219)|null|### 概述  大型语言模型驱动的自主代理在软件开发等场景中展现出强大的自主性潜力。然而，当前静态经验范式依赖于通过启发式方法获取的固定历史经验集，这限制了代理的适应性和优化。本文提出迭代经验精炼框架，允许语言模型在执行任务过程中动态更新和优化经验。我们定义了两种核心模式：顺序模式，根据任务批次内的最近经验进行优化；累计模式，跨所有先前批次积累经验。结合我们的经验淘汰策略，该方法优先选择高质量和常用的经验，有效管理经验空间，提高效率。实验结果显示，虽然顺序模式可能带来更好的性能，但累计模式提供了更稳定的性能。此外，经验淘汰机制使得仅使用高质量经验子集的11.54%，就能实现更好的性能。|
|**2024-05-06**|**Large Language Models as Instruments of Power: New Regimes of Autonomous Manipulation and Control**|Yaqub Chaudhary et.al.|[2405.03813](http://arxiv.org/abs/2405.03813)|null|## 翻译  大型语言模型（LLMs）能够模仿各种修辞风格，生成表达广泛情感的文本，这种能力在低成本下迅速普及，带来了潜在的社会危害。本文并未孤立看待这些模型，而是关注它们背后大规模计算基础设施在各领域的应用。我们首先探讨了LLMs如何通过污染和标准化信息环境来影响社会，并指出这些功能可能被用作控制手段。接下来，我们将焦点转向几个新兴研究领域，这些领域增强了LLMs作为权力工具的能力：  1. 通过实时设计对话界面中的选择架构（如“AI角色”），进行说服。 2. 将LLM模型化为人类行为的计算模型（如“硅质主体”）。 3. 利用LLMs模拟人类群体行为的模型（如“硅质社会”）。 4. 结合强化学习，开发可控制的战略对话模型。  这些方面结合在一起，展示了如何构建基于LLMs的系统，它们通过模拟和伪装的“预测”，成为操控个人、社会和政治的强大工具，对人类行为、意图和行动产生影响。|
|**2024-05-05**|**Language Evolution for Evading Social Media Regulation via LLM-based Multi-agent Simulation**|Jinyu Cai et.al.|[2405.02858](http://arxiv.org/abs/2405.02858)|**[link](https://github.com/BlueLinkX/GA-MAS)**|**社交媒体平台如Twitter、Reddit和新浪微博在全球交流中扮演重要角色，但它们在地缘政治敏感区域常常受到严格监管。这促使用户在受限的社交媒体环境中巧妙地调整沟通方式，经常采用编码语言。这种语言模式的转变不仅是对抗规则的策略，也是语言进化在社会和技术压力下的生动体现。研究受限制社交媒体环境下语言的演变对于保障言论自由、优化内容管理以及推动语言学研究具有重要意义。本文提出了一种基于大型语言模型（LLMs）的多代理模拟框架，用于探索在严格监管下用户语言的进化。该框架包含对话监督的主管代理和参与互动的语言策略进化者——模拟在规避社交媒体监管的严格条件下的沟通风格演变。研究通过从抽象场景到实际案例的多种情景评估了框架的有效性。研究结果表明，LLMs能够模拟受限环境中的复杂语言动态和交互，随着进化，它们在逃避监督和信息准确性方面表现出改善。此外，发现LLM代理针对不同的场景采用了不同的策略。**|
|**2024-05-02**|**OmniDrive: A Holistic LLM-Agent Framework for Autonomous Driving with 3D Perception, Reasoning and Planning**|Shihao Wang et.al.|[2405.01533](http://arxiv.org/abs/2405.01533)|**[link](https://github.com/nvlabs/omnidrive)**|**随着大规模多模态语言模型（MLLMs）的进步，人们对于基于这些模型的自动驾驶系统表现出日益增长的兴趣，期望利用它们强大的推理能力。然而，将MLLMs的强项应用于驾驶任务的规划部分是一个挑战，因为规划需要对三维环境有全面的理解，而不仅仅是二维推理。为此，我们的工作提出了一种框架，旨在实现模型与3D驾驶任务的紧密契合。我们首先设计了一个新颖的3D MLLM架构，它利用稀疏查询技术将视觉表示提升并压缩到三维空间，然后将其输入到语言模型中。这种基于查询的表示方式使得我们可以同时编码动态物体和静态地图元素（如道路），为感知和行动的对齐提供一个简化的三维世界模型。  此外，我们还创建了OmniDrive-nuScenes，这是一个新的视觉问答数据集，它通过全面的视觉问答任务（如场景描述、交通规则理解、三维定位、反事实推理、决策制定和规划）来考验模型在复杂三维场景中的真正情境意识。大量的实验结果表明，我们的提出的架构有效，并强调了在复杂三维环境中进行推理和规划时，视觉问答任务的重要性。**|
|**2024-05-02**|**CACTUS: Chemistry Agent Connecting Tool-Usage to Science**|Andrew D. McNaughton et.al.|[2405.00972](http://arxiv.org/abs/2405.00972)|**[link](https://github.com/pnnl/cactus)**|**这篇论文介绍了一种名为CACTUS的大型语言模型，它结合了化学信息学工具，旨在提升在化学和分子发现领域的高级推理与问题解决能力。研究者们使用包括Gemma-7b、Falcon-7b、MPT-7b、Llama2-7b和Mistral-7b在内的多款开源大语言模型，对CACTUS进行了广泛的性能评估，通过数千个化学问题的基准测试。结果显示，CACTUS明显优于基础模型，其中Gemma-7b和Mistral-7b无论采用何种提示策略，表现最为出色。论文还探讨了领域特定提示和硬件配置对模型性能的影响，强调了提示工程的重要性，并指出在消费级硬件上部署较小模型可能不会显著牺牲准确性。  CACTUS通过融合开源大语言模型的认知功能与专业工具，能够协助研究人员进行分子性质预测、相似性搜索和药物适用性评估等任务。作为化学信息学领域的重大突破，CACTUS为化学家和分子探索者提供了一个灵活的工具，有望加速科学研究，推动新型有效、安全药物、催化剂和材料的发现。此外，CACTUS与自动化实验平台的集成以及实时数据驱动决策的能力，为自主发现开辟了新的可能。**|
|**2024-04-29**|**Towards Generalizable Agents in Text-Based Educational Environments: A Study of Integrating RL with LLMs**|Bahar Radmehr et.al.|[2404.18978](http://arxiv.org/abs/2404.18978)|null|随着教育环境中对学习者模型日益增长的兴趣，研究重点逐渐转向如何通过强化学习（RL）与大型语言模型（LLMs）相结合，提升在开放性文本学习环境中的通用能力。本文探讨了三种类型的代理：（1）基于RL的代理，使用自然语言表示状态和行动策略以寻找最佳互动方式；（2）基于LLM的代理，利用模型的广泛知识和推理能力通过提示进行操作；（3）混合LLM辅助RL的代理，旨在提高性能和泛化能力。为了支持这些代理的发展和评估，我们提出了PharmaSimText，这是一个源自PharmaSim虚拟药店环境的新基准，专注于诊断对话实践。实验结果显示，RL基础的代理在任务完成方面表现优秀，但在提问质量上有所欠缺；而LLM基础的代理在提问能力上较强，但任务完成度不高。最后，混合LLM辅助RL的代理展示了克服这些局限性的潜力，证实了RL与LLMs结合用于开发开放性学习环境高表现代理的可能性。|
|**2024-04-27**|**CRISPR-GPT: An LLM Agent for Automated Design of Gene-Editing Experiments**|Kaixuan Huang et.al.|[2404.18021](http://arxiv.org/abs/2404.18021)|null|随着基因组工程技术的兴起，精确修改遗传信息已成为可能，但高效基因编辑系统的构建需要深入理解CRISPR技术及其复杂实验背景。大型语言模型（LLMs）在诸多任务中展现出潜力，但在生物设计问题上往往缺乏特定知识。本文介绍CRISPR-GPT，一个增强型LLM代理，它结合了领域知识和外部工具，以自动化并提升基于CRISPR的基因编辑实验设计过程。CRISPR-GPT利用LLMs的推理能力，协助选择CRISPR系统、设计引导RNA、推荐细胞递送方法、起草协议以及设计验证实验以确认编辑结果。我们展示了CRISPR-GPT如何帮助非专家研究人员从头开始进行基因编辑实验，并通过实际案例验证其有效性。同时，我们探讨了自动化基因编辑设计的伦理和监管问题，强调了负责任和透明使用此类工具的重要性。我们的工作目标是弥合初级生物研究者与CRISPR基因组工程技术之间的鸿沟，展示LLM代理在促进复杂生物发现任务中的潜力。|
|**2024-04-27**|**Testing and Understanding Erroneous Planning in LLM Agents through Synthesized User Inputs**|Zhenlan Ji et.al.|[2404.17833](http://arxiv.org/abs/2404.17833)|null|随着大型语言模型（LLMs）驱动的代理在各种商业应用中，特别是在心理健康支持、化学合成和软件开发等领域展现效用，人们发现这些代理在处理复杂任务和长期规划时容易产生错误。为此，本文提出了一种新颖的自动化方法——PDoctor，旨在检测和理解LLM代理的错误规划。PDoctor首先定义了一个领域特定的语言（DSL），用于用户查询，并借助Z3约束求解器生成各种输入，这些输入是描述一系列任务完成需求的自然语言段落。然后，PDoctor从这些需求中提取约束，形成一个测试基准。我们使用三个主流的代理框架和两个强大的LLMs（GPT-3.5和GPT-4）对PDoctor进行了评估，结果显示它能有效识别代理规划中的各种错误，并为开发者和用户提供了有价值的见解和错误特性。最后，我们讨论了可能的替代设计和扩展PDoctor的方向。|
|**2024-04-26**|**PLAYER*: Enhancing LLM-based Multi-Agent Communication and Interaction in Murder Mystery Games**|Qinglin Zhu et.al.|[2404.17662](http://arxiv.org/abs/2404.17662)|**[link](https://github.com/alickzhu/player)**|**随着大型语言模型（LLMs）的最新进展，增强了代理间的通信和社会交互能力。然而，在涉及竞争与合作的动态环境中，利用这些模型进行复杂推理的构建仍然面临挑战，尤其是因为基于信息图的搜索方法存在局限性。为此，我们提出PLAYER*，这是一个基于任意采样式规划器的新框架，它结合了传感器和剪枝技术，构建了一个完全依赖于问题驱动的搜索框架，适用于高难度的推理任务。我们还引入了一种可量化的评估方法，通过多项选择题来测试，并创建了WellPlay数据集，包含1,482个问答对。实验结果表明，PLAYER*在复杂动态环境中的效率和性能优于现有方法，并提供了可量化的对比结果。**|
|**2024-04-24**|**Autonomous LLM-driven research from data to human-verifiable research papers**|Tal Ifargan et.al.|[2404.17605](http://arxiv.org/abs/2404.17605)|**[link](https://github.com/technion-kishony-lab/data-to-paper)**|**随着人工智能推动科学发现的步伐加快，人们还不清楚完全由AI驱动的研究是否可行，以及它能否遵循关键的科学价值观，如透明度、可追溯性和可验证性。为了模拟人类的科学研究实践，我们构建了“数据到论文”（data-to-paper），这是一个自动化平台，引导相互协作的人工智能代理通过完整的分步骤研究流程，同时程序化追踪信息流，并允许人类监督和互动。在自动模式下，仅提供标注数据，该平台就能提出假设，设计研究计划，编写和调试分析代码，生成和解读结果，甚至创建完整且信息可追溯的科研论文。尽管研究新颖性有限，但这一过程展示了AI自主从数据中生成原创定量洞察的能力。对于简单的研究目标，全自动流程能创作出大约80-90%无需重大错误的稿件，然而随着目标复杂性的增加，人类的共同参与对于保证准确性至关重要。此外，生成的论文本身也具有内在的可验证性，因为信息追踪使得结果、方法和数据的链接可以程序化进行。因此，我们的工作表明，AI驱动的科研可以加速科学发现，同时增强而非威胁透明度、可追溯性和可验证性。**|
|**2024-04-11**|**The Future of Scientific Publishing: Automated Article Generation**|Jeremy R. Harper et.al.|[2404.17586](http://arxiv.org/abs/2404.17586)|null|这项研究介绍了一种创新的软件工具，它利用大型语言模型（LLM）提示，实现了从Python代码自动生成学术文章，这对于生物医学信息学和计算机科学领域具有重要意义。选择Python作为基础示例，因其广泛使用和强大的数据分析能力。该方法和框架的灵活性使得其适用于多种GitHub仓库，表明了工具的广泛应用潜力（Harper，2024年）。通过简化传统上耗时的学术写作过程，特别是在整合复杂数据集和代码输出方面，这一突破性进展推动了科研成果的快速传播。开发过程中并未依赖高级语言模型，确保了自动化生成内容的连贯性和完整性。此次探索不仅验证了软件的成功应用和效率，还预示了未来可能集成更先进的LLM，将进一步增强其功能，引领一个科研发现发布更加迅速和易获取的时代。|
|**2024-05-09**|**Large Language Model Agent as a Mechanical Designer**|Yayati Jadhav et.al.|[2404.17525](http://arxiv.org/abs/2404.17525)|null|传统的机械设计方法依赖于专家通过经验引导的修改和有限元分析（FEA）来满足特定需求，但这个过程耗时且高度依赖个人知识。尽管已经开发了许多机器学习模型来简化繁琐的专家驱动迭代过程，但它们通常需要大量训练数据和计算资源。深度学习方法往往局限于其训练领域和任务，限制了跨任务应用。这在自动化效率与资源需求之间形成了权衡。  本研究提出了一种新颖的方法，即将预训练的语言模型（LLMs）与有限元模块结合。有限元模块评估每个设计并提供关键反馈，引导LLMs不断学习、规划、生成和优化设计，无需针对特定领域进行专门训练。我们通过在桁架结构的迭代优化中展示这种框架的有效性，证明它能够根据结构化的反馈和标准调整设计。结果显示，基于LLM的代理成功生成符合自然语言描述的桁架结构设计，成功率高达90%，这取决于所施加的约束条件。通过提示式优化技术，我们展示了LLM代理在接收到解-得分对后，能够根据其内在推理能力迭代优化设计以满足规格要求。  LLM代理能够产生可行的设计并根据其固有的推理能力进行优化，这表明它们有潜力自主发展和实施有效的设计策略。|
|**2024-04-26**|**Ruffle&Riley: Insights from Designing and Evaluating a Large Language Model-Based Conversational Tutoring System**|Robin Schmucker et.al.|[2404.17460](http://arxiv.org/abs/2404.17460)|null|本文讨论并评估了一种新型的对话式辅导系统（Conversational Tutoring Systems，CTS），该系统利用大型语言模型（Large Language Models，LLMs）的最新进展。首先，系统通过自动从课程文本中生成易于编辑的教学脚本，实现AI辅助的内容创作。其次，系统通过两个基于LLM的代理（Ruffle和Riley）以学习教学模式运行，分别扮演学生和教授角色，进行自由形式的对话，遵循典型的人工智能辅导系统的内环和外环结构。我们在两个在线用户研究（N=200）中对比了该系统与简单的问答聊天机器人和阅读活动在支持生物学课程的效果。研究分析了系统使用模式、预后测试成绩以及用户体验调查，结果显示用户对Ruffle&Riley的参与度高，理解力强，并认为提供的支持有帮助。尽管Ruffle&Riley用户的完成时间较长，但在短期学习成效上并未发现显著差异，优于阅读活动。我们的系统架构和用户研究为未来CTS设计者提供了有价值的信息。此外，我们开源我们的系统，以促进基于LLM的学习技术有效教学设计的研究。|
|**2024-04-26**|**A Unified Debugging Approach via LLM-Based Multi-Agent Synergy**|Cheryl Lee et.al.|[2404.17153](http://arxiv.org/abs/2404.17153)|null|在软件调试这个耗时的过程中，人们一直在努力实现自动化，包括故障定位和修复生成。近年来，大型语言模型（LLMs）在自动化调试方面展现出巨大潜力。然而，我们发现了传统和基于LLM的调试工具面临三大挑战：1）上游的故障定位不准确会波及下游的修复；2）处理复杂逻辑错误的能力不足；3）忽视程序上下文。针对这些问题，我们提出了首个自动化的、统一的调试框架——FixAgent，通过LLM代理协同。FixAgent能执行端到端的故障定位、修复和分析。  我们的关键洞察是，LLMs能够从人类开发者认可的通用软件工程原则中获益，比如“橡皮鸭调试”，这有助于更好地理解程序功能和逻辑错误。为此，我们设计了三个灵感来源于“橡皮鸭”的解决方案：代理专业化与协同、关键变量跟踪和程序上下文理解，促使LLMs提供明确的解释，并聚焦于关键的程序逻辑信息。在广泛使用的QuixBugs数据集上，FixAgent成功修复了80个bug中的79个，其中9个是之前未解决的。它还在CodeFlaws上合理地修复了1.9倍于最佳修复工具的缺陷，而且无需位置信息，采样率低于0.6%。平均而言，与使用不同LLM的基线模型相比，FixAgent提高了约20%的合理修复和正确修复率，显示出我们设计的有效性。  此外，FixAgent的正确率高达97.26%，表明它有可能克服现有方法的过拟合问题。总结来说，FixAgent是一个有前景的自动化调试框架，旨在提升软件调试的效率和准确性。|
|**2024-04-25**|**Cooperate or Collapse: Emergence of Sustainability Behaviors in a Society of LLM Agents**|Giorgio Piatti et.al.|[2404.16698](http://arxiv.org/abs/2404.16698)|null|在快速发展的人工智能领域，确保大型语言模型（LLMs）的决策安全是一项重大挑战。本文提出了一种名为“Governance of the Commons Simulation”（GovSim）的模拟平台，旨在研究LLMs中的战略互动和合作决策。通过这个环境，我们探讨了AI代理之间资源分享的动态，强调了伦理考量、战略规划和谈判技巧的重要性。GovSim具有灵活性，支持文本型代理，包括LLMs。利用生成式代理框架，我们创建了一个通用代理，便于整合不同的LLMs。我们的研究发现，在GovSim中，只有15个测试模型中的2个能够实现可持续结果，这表明模型在管理共享资源的能力上存在显著差距。进一步的研究显示，如果移除代理之间的通信能力，它们会过度使用共享资源，突出了合作中沟通的关键性。有趣的是，大多数LLMs缺乏普遍化的假设能力，揭示了它们推理技能的一个重要弱点。我们开源了所有研究结果，包括模拟环境、代理提示以及全面的网络界面，以供进一步研究和讨论。|
|**2024-04-24**|**Online Personalizing White-box LLMs Generation with Neural Bandits**|Zekai Chen et.al.|[2404.16115](http://arxiv.org/abs/2404.16115)|null|随着大型语言模型（LLMs）开始生成个性化的文本内容，如何在不为每位用户创建独特模型的资源消耗下实现高效个性化成了新挑战。本文提出了一种创新的在线方法，利用神经_bandit算法动态优化软指令嵌入，根据用户反馈调整内容，从而提升白盒LLMs开放性文本生成的个性化水平。通过在多个任务上的严谨实验，我们证明了这种方法相对于基础策略有显著性能提升。特别是针对个性化新闻标题生成，NeuralTS带来了高达62.9%的最佳ROUGE分数提升以及2.76%的LLM代理评估分数增长，这表明其效果显著。|
|**2024-04-04**|**Elicitron: An LLM Agent-Based Simulation Framework for Design Requirements Elicitation**|Mohammadmehdi Ataei et.al.|[2404.16045](http://arxiv.org/abs/2404.16045)|null|## 翻译  在产品开发的关键阶段——需求获取，往往难以全面捕捉用户需求，导致最终产品可能无法满足期望。为此，本文提出了一种新颖的框架，它利用大型语言模型（LLMs）来自动化和增强这一过程。通过生成大量模拟用户（LLM代理），我们可以探索更广泛的用户需求和未预见的使用场景。这些代理通过描述他们的行为、观察和挑战，参与产品体验情景。随后的代理访谈和分析揭示了宝贵的用户需求，包括潜在需求。我们通过三个实验验证了我们的框架：首先，我们探讨了不同方法生成多样化的代理，分析其优缺点，并证明了具有上下文意识的代理生成能带来更大的需求多样性。其次，我们展示了该框架如何有效地模拟富有同情心的领先用户访谈，识别出比传统人类访谈更多的潜在需求。最后，我们展示了如何使用LLMs分析访谈，提取需求并将其分类为潜在或非潜在。我们的研究工作强调了利用LLM代理加速早期产品研发、降低成本和促进创新的潜力。|
|**2024-04-24**|**A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples**|Lihang Pan et.al.|[2404.15974](http://arxiv.org/abs/2404.15974)|null|## 翻译  单个大型语言模型（LLM）在解决复杂任务方面的能力有限。然而，通过连接多个LLM代理构建的网络可以显著提升整体性能。本文介绍了一种人机协作工具——EasyLAN，旨在帮助开发者轻松构建LLM代理网络（LAN）。EasyLAN首先根据任务描述自动生成仅包含一个代理的初始网络。接着，它利用少量训练示例来调整网络。对于每个示例，EasyLAN分析输出与真实结果之间的差距，并找出错误的原因。EasyLAN会采用精心设计的策略来修正这些问题。用户可以介入EasyLAN的工作流程或直接修改LAN。最终，LAN从单个代理发展成多代理的网络。实验结果显示，EasyLAN能够帮助开发者快速构建性能良好的LAN。|
|**2024-04-03**|**Concept-Guided LLM Agents for Human-AI Safety Codesign**|Florian Geissler et.al.|[2404.15317](http://arxiv.org/abs/2404.15317)|null|随着生成人工智能在软件工程，特别是安全工程中的重要性提升，对它的质量要求也随之提高。单纯依赖大型语言模型（LLMs）已不足以满足这些需求。因此，我们提出了一种高效且融合的策略，旨在利用LLMs进行安全分析和人机协同设计，以确保软件系统的安全性。我们开发了一个定制化的LLM代理，结合提示工程、启发式推理和检索增强生成，专注于解决与预定义安全概念相关的任务，并与系统模型图进行交互。决策流程通过一系列微决策进行引导，有助于保持结构化信息。此外，我们还提出了图的口头表述作为系统模型的中间表示，以促进LLM与图的交互。我们通过一个简化自动驾驶系统的示例，展示了选择的提示-响应对，以说明我们的方法如何应用于安全分析。|
|**2024-04-23**|**Aligning LLM Agents by Learning Latent Preference from User Edits**|Ge Gao et.al.|[2404.15269](http://arxiv.org/abs/2404.15269)|**[link](https://github.com/gao-g/prelude)**|**我们研究基于用户对语言模型编辑的互动学习语言代理。在诸如写作助手的常见场景中，用户与语言代理交互，根据上下文生成响应，并可能选择性地编辑代理的响应以反映他们的潜在偏好，同时提高准确性。这种编辑反馈是自然产生的，适合用于提升代理与用户偏好的契合度，降低后续用户的编辑成本。为此，我们提出PRELUDE框架，它根据历史编辑数据推断用户的潜在偏好，并据此设计一个提示策略，引导未来的响应生成，避免了昂贵且难以扩展的微调过程，还能保持在其他任务上的性能。  此外，学习描述性的偏好有助于增强可解释性，用户可以查看和调整学习到的偏好。然而，用户偏好可能复杂多变，受情境影响，因此学习起来具有挑战性。为解决这一问题，我们提出CIPHER算法，它利用大型语言模型（LLM）根据用户编辑推断给定情境下的用户偏好。未来，CIPHER会从历史中的k个最接近的上下文中检索推断出的偏好，综合生成响应。我们在总结和电子邮件写作两个互动环境中使用GPT-4模拟用户进行评估，与直接使用用户编辑但不学习描述性偏好的算法，以及学习全局无上下文偏好的算法进行了比较。  在两项任务中，CIPHER都实现了最低的编辑距离成本，并且学习到的偏好与真实偏好显示出显著的相似性。**|
|**2024-04-22**|**A Survey on Self-Evolution of Large Language Models**|Zhengwei Tao et.al.|[2404.14387](http://arxiv.org/abs/2404.14387)|**[link](https://github.com/alibabaresearch/damo-convai)**|**## 概述  大型语言模型（LLMs）在众多领域和智能代理应用中取得了显著进步。然而，依赖人类或外部模型监督的现有LLMs在处理复杂任务和多样性增加时可能会遇到成本高昂和性能瓶颈的问题。为此，自我进化方法应运而生，这种策略允许LLMs自主获取、精炼并从自身生成的经验中学习，借鉴人类经验学习过程，有望推动LLMs向超级智能发展。本文全面综述了LLMs中的自我进化方法。首先，我们提出一个概念框架，将进化过程划分为迭代循环的四个阶段：经验获取、经验细化、更新和评估。其次，我们分类探讨LLMs和基于LLM的代理的进化目标，并对相关文献进行总结，提供每个模块的分类和见解。最后，我们指出了当前的挑战，并提出了未来研究方向，为加速自演进LLMs的发展提供关键洞见。**|
|**2024-04-21**|**A Survey on the Memory Mechanism of Large Language Model based Agents**|Zeyu Zhang et.al.|[2404.13501](http://arxiv.org/abs/2404.13501)|**[link](https://github.com/nuster1128/llm_agent_memory_survey)**|**随着大型语言模型（LLMs）在科研和工业界的广泛关注，基于LLMs的智能代理因其自我进化能力而备受瞩目，这对于解决需要长期复杂交互的现实问题至关重要。支持agent-environment交互的关键要素是代理的记忆机制。尽管已有众多有前景的记忆设计被提出，但这些研究分散在多篇论文中，缺乏全面的综述来系统性地总结和比较，未能提炼出通用且有效的设计模式以启发后续研究。为此，本论文旨在填补这一空白，我们提出一份关于LLM基代理记忆机制的全面调查。首先，我们将探讨记忆在LLM代理中的“是什么”以及“为什么需要”。然后，我们系统回顾了关于记忆模块的设计和评估方法的研究。此外，我们还会展示记忆模块在各种应用中扮演的重要角色。最后，我们会分析现有工作的局限，并指出重要的未来研究方向。为了跟踪该领域最新进展，我们创建了一个GitHub仓库：\url{https://github.com/nuster1128/LLM_Agent_Memory_Survey}。**|
|**2024-04-18**|**From Language Models to Practical Self-Improving Computer Agents**|Alex Sheng et.al.|[2404.11964](http://arxiv.org/abs/2404.11964)|null|我们提出了一种简单直接的方法，用于创建能够执行各种计算机任务的人工智能代理，并通过自我改进来发展工具和增强功能，以解决日益复杂的任务。鉴于大型语言模型（LLMs）已显示出从非参数增强中获益，近期的研究大量集中在开发软件，以赋予LLMs各种能力。我们建议，通过适当的提示工程，一个LLM代理可以系统地生成软件来增强自身，而不是依赖人类工程的静态软件开发。  我们通过一些案例研究展示了这一点：仅通过终端访问，我们引导LLM代理添加了检索、互联网搜索、网页导航和文本编辑功能。该代理有效地利用这些工具解决了问题，例如自动化软件开发和基于网络的任务。这种方法表明，通过连续提问和巧妙的提示设计，LLM能够自主扩展其功能，执行实际的计算机任务。|
|**2024-04-25**|**Automated Social Science: Language Models as Scientist and Subjects**|Benjamin S. Manning et.al.|[2404.11794](http://arxiv.org/abs/2404.11794)|null|我们提出了一种方法，利用大型语言模型（LLM）的最新进展，自动构建和测试社会科学假设。这种方法的关键在于使用结构因果模型。结构因果模型提供了一个陈述假设的语言、构建LLM基础代理的蓝图、实验设计以及数据分析计划。拟合后的结构因果模型可供预测或规划后续实验。我们通过几个场景进行了演示：谈判、保释听证会、求职面试和拍卖。在这些情况下，系统既提出了因果关系，也进行了检验，发现了一些证据，而有些则没有。我们证明，从这些社会互动模拟中获取的洞察并非仅通过直接询问LLM就能获得。当给定每个场景的建议结构因果模型时，LLM在预测估计效应的符号方面表现良好，但无法可靠地预测效应的大小。在拍卖实验中，模拟结果与拍卖理论的预测紧密吻合，但LLM直接提取的清算价格预测不准确。然而，如果模型能基于拟合的结构因果模型进行条件化，LLM的预测会大幅改进。简而言之，LLM知道的比它能立即表达的要多。|
|**2024-04-17**|**AgentKit: Flow Engineering with Graphs, not Coding**|Yue Wu et.al.|[2404.11483](http://arxiv.org/abs/2404.11483)|**[link](https://github.com/holmeswww/agentkit)**|**我们提出了一种直观的大型语言模型提示框架（AgentKit），旨在为多功能代理提供统一的方法。AgentKit通过简单的自然语言提示构建复杂的“思维过程”。其基本单元是节点，包含特定子任务的自然语言指令。用户可以像拼接乐高积木一样连接这些节点，从而明确设计出自然结构化的“思考流程”。例如，在撰写论文时，可能的步骤包括：1）确定核心信息，2）识别研究空白等。AgentKit的模块化特性使得高级功能如即兴的层次化规划、反思和从互动中学习变得可能。由于其直观且模拟人类思考过程的设计，即使没有编程经验的人也能创建和调整基础代理。定量实验显示，使用AgentKit设计的代理在WebShop和Crafter任务上实现了最先进的性能。这些成果表明AgentKit有潜力使LLM代理在更广泛的场景下高效且易于使用。相关代码已开源在GitHub：https://github.com/holmeswww/AgentKit。**|
|**2024-04-15**|**Memory Sharing for Large Language Model based Agents**|Hang Gao et.al.|[2404.09982](http://arxiv.org/abs/2404.09982)|**[link](https://github.com/ghupppp/memorysharingllm)**|**在人工智能领域，大型语言模型（LLMs）通过自然语言提示执行任务的能力是一个重大突破，它减少了对固定答案任务（如常识问题和是非查询）的重新训练或微调需求。然而，在处理开放性挑战如诗歌创作时，基于上下文学习的方法显示出局限，主要源于提供的示例全面性以及模型理解问题内容的能力不足，导致输出往往与预期结果大相径庭。针对这一差距，我们的研究提出了Memory-Sharing（MS）框架，这是一种针对LLM多代理的实时记忆存储和检索系统，旨在增强基于上下文的学习过程。每个“记忆”单元记录了提出的查询及其来自LLM代理的即时响应，从多个类似代理中聚合这些记忆，形成所有代理共享的丰富记忆池。MS框架不仅帮助代理找到特定任务的相关示例，还评估其记忆的潜在利用价值，供其他代理未来应用。在三个不同领域的实证验证显示，MS框架显著提高了代理处理开放性问题的表现。此外，我们还讨论了哪种记忆池和检索策略能更好地支持代理，为MS的未来发展提供了方向。代码和数据可在：https://github.com/GHupppp/MemorySharingLLM 获取。**|
|**2024-05-10**|**Confidence Calibration and Rationalization for LLMs via Multi-Agent Deliberation**|Ruixin Yang et.al.|[2404.09127](http://arxiv.org/abs/2404.09127)|**[link](https://github.com/minnesotanlp/collaborative-calibration)**|**### 背景  当前的大规模语言模型（LLMs）在不确定性估计方面面临挑战，它们通常校准不良且过度自信，特别是在基于人类反馈的强化学习（RLHF）中。人类的决策和信心不仅源于内在信念，还能通过日常观察进行调整，而现有LLM的校准方法主要关注单个模型的信心估计，未能充分利用“集体智慧”：多个LLM之间的协作表达能力，这可以集体提高准确性和校准。本研究中，我们提出了一种无训练后处理的校准策略——协作校准（Collaborative Calibration），它利用多代理工具增强的LLMs在模拟的群体讨论过程中，共同提升校准能力和推理合理性。  ### 任务  我们在生成式问答任务上展示了协作校准的有效性，覆盖了多个领域，证明了它在整合集体校准后的信心评估和提升模型预测可靠性方面的潜力。**|
|**2024-04-13**|**CuriousLLM: Elevating Multi-Document QA with Reasoning-Infused Knowledge Graph Prompting**|Zukang Yang et.al.|[2404.09077](http://arxiv.org/abs/2404.09077)|**[link](https://github.com/zukangy/kgp-curiousllm)**|**在问答（QA）领域，大型语言模型（LLMs）与外部数据库的融合取得了显著成效。然而，这些方法在处理复杂推理任务时往往力有不逮。为此，我们对一种名为知识图谱提示（KGP）的创新方法进行了优化，该方法结合知识图谱和基于LLM的代理以提升推理和搜索精度。然而，原始的KGP框架需要昂贵的大规模数据微调，并且仍存在LLM的错误推断问题。因此，我们提出了一种融入推理能力的LLM代理，它模仿人类的好奇心，通过提问来更有效地导航搜索过程。这个简单的改进显著提高了LLM在QA任务中的性能，同时避免了初始KGP框架的高成本和延迟。我们的目标是进一步发展这种方法，最终实现更精确、更快捷且成本效益更高的QA解决方案。**|
|**2024-04-13**|**Do LLMs Play Dice? Exploring Probability Distribution Sampling in Large Language Models for Behavioral Simulation**|Jia Gu et.al.|[2404.09043](http://arxiv.org/abs/2404.09043)|null|随着大型语言模型（LLMs）的飞速发展及其在处理复杂语言任务中的出色表现，越来越多的研究尝试利用LLMs模拟人类的行为决策过程，通常这些过程被表示为马尔可夫决策过程（MDPs）。在这个框架中，动作遵循特定的概率分布，并需要迭代采样。这促使我们探究LLM代理理解概率分布的能力，以通过概率采样指导行为决策并生成行为序列。我们将问题分为两个主要方面：一是已知精确概率分布的模拟，二是模糊概率分布的序列生成。  在已知概率分布的情况下，代理需要根据问题描述提供概率分布的类型和参数，然后给出采样序列。然而，我们的研究显示，LLM代理在这方面的性能不佳，但通过编程工具可以一定程度上提高采样成功率。而在实际情境中，概率分布往往不明确。因此，我们在第二部分让代理调整在线社交网络中的活跃度，并分析行动频率。结果表明，即使借助编程工具，LLM代理依然无法有效地采样概率分布。这意味着在直接将LLM作为模拟人类行为的代理应用之前，还需要谨慎对待。|
|**2024-04-12**|**Strategic Interactions between Large Language Models-based Agents in Beauty Contests**|Siting Lu et.al.|[2404.08492](http://arxiv.org/abs/2404.08492)|null|随着大型语言模型（LLMs）的广泛应用，它们在博弈论框架下的游戏行为理解潜力日益显现。本研究聚焦于通过模拟分析不同类型LLM驱动的代理在经典 Beauty Contest 游戏中的策略互动。借鉴人类实验，我们对LLM代理的策略层次进行类似的评估，发现它们展现出从零级到一级的不同程度推理能力，并在重复游戏中表现出行动趋同。此外，我还探讨了不同类型的代理群体构成如何影响战略行为：高比例的固定策略对手能促进LLM代理的收敛，而混合环境中不同相对策略水平的代理共存会加速所有代理的收敛。更智能的代理可能获得更高的平均收益，但这是以较低智能代理的牺牲为代价的。这些结果不仅揭示了在特定情景下模拟代理的结局，还为理解算法之间的战略互动提供了重要启示。|
|**2024-04-17**|**LLM Agents can Autonomously Exploit One-day Vulnerabilities**|Richard Fang et.al.|[2404.08144](http://arxiv.org/abs/2404.08144)|null|随着大语言模型（LLMs）的威力日益增强，其在良性和恶意用途上的应用也日益广泛。研究人员开始关注它们利用网络安全漏洞的能力。近期的研究探讨了LLMs自主破解网站的可能性，但这些研究主要集中在简单的漏洞上。本工作揭示，LLMs能够自主利用现实世界系统中的单日漏洞。我们收集了一组包含15个被CVE描述为“关键严重性”的一天期漏洞数据。当提供CVE描述时，GPT-4模型能成功利用87%的漏洞，相比之下，其他测试模型（如GPT-3.5、开源LLMs和开源漏洞扫描器ZAP和Metasploit）的表现均为0%。然而，我们的GPT-4模型在没有描述的情况下效率大减，仅能利用7%的漏洞。这些发现对大规模部署高能力LLMs提出了质疑。|
|**2024-04-11**|**WESE: Weak Exploration to Strong Exploitation for LLM Agents**|Xu Huang et.al.|[2404.07456](http://arxiv.org/abs/2404.07456)|null|近期，大型语言模型（LLMs）显示出作为智能代理的强大潜力。然而，现有的研究主要集中在通过精心设计的提示工程或任务特定的微调来提升模型的推理或决策能力，忽视了探索与利用的过程。在处理开放世界交互环境中的复杂任务时，这些方法存在局限性。首先，由于缺乏对环境的全局信息，模型倾向于做出贪婪决策，导致解决方案不理想。另一方面，从环境中获取的无关信息不仅引入噪声，还增加了额外的成本。  为此，本文提出了一种新颖的方法——弱探索强化强利用（Weak Exploration to Strong Exploitation，WESE），旨在增强LLM在解决开放世界交互任务中的表现。具体来说，WESE将探索和利用过程解耦，使用成本效益高的“弱”代理执行探索任务，以获取全局知识。随后，我们引入基于知识图谱的策略来存储这些知识，并提取与任务相关的关键信息，从而提升“强”代理在成功率和效率上的性能。我们的方法适用于各种任务，并在四个互动基准测试中显著提高了成功率和效率。|
|**2024-04-10**|**GoEX: Perspectives and Designs Towards a Runtime for Autonomous LLM Applications**|Shishir G. Patil et.al.|[2404.06921](http://arxiv.org/abs/2404.06921)|**[link](https://github.com/ShishirPatil/gorilla)**|**随着大型语言模型（LLMs）的发展，它们不再仅仅是对话系统中的信息提供者，而是开始积极参与到与实际应用和服务的互动中。如今，人类在将LLM生成的输出（如代码、函数或操作）投入现实世界执行前，需要验证其正确性和适用性，这带来了挑战，因为代码理解被广泛认为非常困难。本文研究了人类如何能有效与LLMs协作、委派和监督，特别是在未来。我们主张，在许多情况下，对提出的行动进行“事后验证”（在看到输出后确认其正确性）比之前的“事前验证”更为容易。实现这一目标的核心理念是集成直观的撤销功能，并为LLM生成的动作设定损害约束，作为降低相关风险的有效策略。通过这种方式，人类可以撤销LLM输出的影响，或者确信潜在风险是有限的。我们认为这对于实现LLMs与应用和服务在有限的人类监督下交互至关重要。我们描述了开源运行时Gorilla Execution Engine（GoEX）的设计和实现，该运行时用于执行LLM动作，并提出了一些开放的研究问题，旨在推动LLMs与应用之间以最小的人工干预进行交互。GoEX的源代码已发布在https://github.com/ShishirPatil/gorilla/。**|
|**2024-04-09**|**AgentQuest: A Modular Benchmark Framework to Measure Progress and Improve LLM Agents**|Luca Gioacchini et.al.|[2404.06411](http://arxiv.org/abs/2404.06411)|**[link](https://github.com/nec-research/agentquest)**|**随着大型语言模型（LLMs）的进展，人们追求能够解决复杂、多步骤推理任务的LLM代理。然而，现有的基准往往局限且只关注整体任务成功率。为了解决这些问题，我们提出了AgentQuest框架，它具有以下特点：（i）benchmark和评估指标模块化且易于扩展，通过文档齐全、易用的API；（ii）我们提供了两种新的评估指标，能够在解决任务时可靠地追踪LLM代理的进步。我们通过两个示例展示了这些指标的实用性，通过识别常见失败点并优化代理架构，显著提高了性能。我们希望与研究界共同扩展AgentQuest，并已将其开源在https://github.com/nec-research/agentquest。**|
|**2024-04-15**|**AutoCodeRover: Autonomous Program Improvement**|Yuntong Zhang et.al.|[2404.05427](http://arxiv.org/abs/2404.05427)|**[link](https://github.com/nus-apr/auto-code-rover)**|**在过去几十年里，研究人员在自动化软件开发过程中取得了显著进展，尤其是大型语言模型（LLMs）的应用极大地推动了编程辅助的自动化。然而，软件工程并不仅仅是编码，还包括维护（如修复bug）和演化（如添加功能）等程序改进过程。本文提出了一种自动解决GitHub问题的方法，旨在实现程序自主改进。我们的方法称为AutoCodeRover，它结合了LLMs与高级代码搜索能力，最终生成程序修改或补丁。与AI研究者和从业者近期关注的仅文件级别的软件项目不同，我们的工作侧重于程序表示（抽象语法树），利用类/方法的程序结构来增强LLM对问题根本原因的理解，并通过迭代搜索提供上下文。当测试套件可用时，谱系基线故障定位技术进一步精确了上下文。  在SWE-bench-lite，一个包含300个真实GitHub问题的数据集上，AutoCodeRover的解决方案效果提升，解决了约22-23%的问题。对于全量的SWE-bench，包含2294个GitHub问题，AutoCodeRover解决了大约16%的问题，这比最近报道的来自Cognition Labs的AI软件工程师Devin的表现还要高，而且时间消耗与Devin相当。我们相信，我们的工作流程能够推动自主软件工程的发展，未来LLM自动生成的代码可以被自动地进行优化和改进。**|
|**2024-04-08**|**Long-horizon Locomotion and Manipulation on a Quadrupedal Robot with Large Language Models**|Yutao Ouyang et.al.|[2404.05291](http://arxiv.org/abs/2404.05291)|null|我们提出了一种基于大型语言模型（LLM）的系统，旨在提升四足机器人的问题解决能力，使其能够处理超越短期动作的长期任务。对于四足机器人来说，长期任务极具挑战性，因为它们需要对任务的语义有高层理解，并具备广泛的运动和操纵技能以与环境互动。我们的系统构建了一个高层推理层，利用大型语言模型，从任务描述中生成混合离散-连续的计划，作为机器人代码。它包括多个LLM代理：一个用于构思计划的语义规划器、一个参数计算器，用于预测计划中的参数，以及一个代码生成器，将计划转换为可执行的机器人代码。  在低层次，我们采用强化学习来训练一套运动规划和控制技能，以增强四足机器人的灵活性，使其能进行丰富环境交互。我们在难以用单一技能完成的长期任务上测试了我们的系统。模拟实验和真实世界实验表明，它成功地制定了多步骤策略，并展现出非平凡的行为，例如制作工具或向人类寻求帮助。|
|**2024-04-06**|**Autonomous Artificial Intelligence Agents for Clinical Decision Making in Oncology**|Dyke Ferber et.al.|[2404.04667](http://arxiv.org/abs/2404.04667)|null|多模态人工智能系统有望通过解析各类医学数据提升临床决策。然而，这些模型在各医学领域的效能尚不明朗，每个领域都有其独特挑战。本文提出了一种利用大型语言模型（LLMs）作为核心推理引擎的新型多模态医疗AI方法。此引擎自主协调并部署一系列专门的医疗AI工具，如文本解读、放射学和病理图像分析、基因数据处理、网络搜索以及医疗指南文档检索。我们在一系列临床肿瘤学场景中验证了该系统，这些场景模拟了典型的患者护理流程。结果显示，系统在选择恰当工具（97%）、得出正确结论（93.6%）、提供完整（94%）和有益（89.2%）治疗建议，以及根据指令引用相关文献（82.5%）方面表现出高能力。这表明LLMs能够有效地规划和执行领域特定模型，以获取或合成新信息，从而充当个性化临床助手。此外，这种架构简化了监管合规性，因为每个组件工具可以单独验证和审批。我们相信，这项工作为医疗领域的更先进LLM代理提供了概念验证。|
|**2024-04-05**|**Cleared for Takeoff? Compositional & Conditional Reasoning may be the Achilles Heel to (Flight-Booking) Language Agents**|Harsh Kohli et.al.|[2404.04237](http://arxiv.org/abs/2404.04237)|null|大型语言模型（LLMs）的快速进步使其在标准基准测试中频频超越人类表现，推动了众多下游应用的发展，如基于LLMs的代理。然而，这些模型在看似简单的任务中意外地表现不佳，这强调了对更全面和多样化的评估框架的需求，以衡量它们的实际能力。为此，我们聚焦于组合性和条件推理——人类认知的基石，并提出GroundCocoa，这是一个与航班预订这一现实问题相连接的词汇丰富的基准。我们的任务是将用户的详细偏好与以多选形式提供的可用航班选项进行匹配。结果显示，包括最先进的GPT-4 Turbo在内的当前最佳模型，在经过高级提示后，准确率仍不超过67%，显示出显著的性能差距。|
|**2024-04-02**|**Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization**|Yoichi Ishibashi et.al.|[2404.02183](http://arxiv.org/abs/2404.02183)|**[link](https://github.com/tsukushiai/self-organized-agent)**|**## 背景  随着大型语言模型（LLM）代理的最新进展，自动化软件开发的未来正逐渐显现。然而，现有的单代理方法在生成和优化大规模、复杂的代码库时面临上下文长度限制的问题。为解决这一挑战，我们提出了一种新颖的多代理框架——自组织多Agent体系（SoA）。SoA是一个可扩展且高效的多代理系统，它允许独立地生成和修改代码组件，并协同构建整个代码库。SoA的一个关键特性是根据问题复杂性自动增加代理，实现动态可扩展性。这样，整体代码量可以根据代理数量无限增长，而每个代理管理的代码量保持恒定。  我们在HumanEval基准上评估了SoA，并发现与单代理系统相比，SoA中的每个代理处理的代码量明显减少，但总体生成的代码量显著增加。此外，SoA在Pass@1准确率方面比强大的单代理基线提高了5%。**|
|**2024-04-02**|**Helmsman of the Masses? Evaluate the Opinion Leadership of Large Language Models in the Werewolf Game**|Silin Du et.al.|[2404.01602](http://arxiv.org/abs/2404.01602)|**[link](https://github.com/doslim/evaluate-the-opinion-leadership-of-llms)**|**大型语言模型在社交推理游戏中展现出显著的策略行为，但对它们作为意见领袖的重要性关注不足，这对于多Agent和人机交互场景的实际应用至关重要。意见领袖是指在一个社会群体中对他人信念和行为有显著影响的个体。本研究使用“狼人杀”游戏作为模拟平台，探讨语言模型在扮演Sheriff（治安官）角色时的意见领导能力。Sheriff负责总结论点并提出决策建议，因此它代表了意见领袖的一个可信代理。我们构建了一个整合Sheriff角色的框架，并基于意见领袖的关键特性提出了两个评估指标：第一个衡量意见领袖的可靠性，第二个考察其对其他玩家决策的影响。  我们进行了大量实验，评估不同规模的语言模型，并创建了“狼人杀”问题回答数据集（WWQA），以测试和提升模型对游戏规则的理解。此外，还包含了人类参与者进行进一步分析。研究结果表明，“狼人杀”游戏是一个有效评估语言模型意见领导力的试验场，但目前仅有少数语言模型具备这种能力。**|
|**2024-04-15**|**CHOPS: CHat with custOmer Profile Systems for Customer Service with LLMs**|Jingzhe Shi et.al.|[2404.01343](http://arxiv.org/abs/2404.01343)|**[link](https://github.com/jingzheshi/chops)**|**随着企业和软件平台越来越多地采用大型语言模型（如GPT-3.5、GPT-4、GLM-3和LLaMa-2）提供聊天辅助或客户服务推理，现有的基于LLM的客户服务模型在与客户资料集成和执行实际操作方面存在局限。它们倾向于强调多样性而非精确性和错误避免，这对于现实世界的客户服务场景并不理想。因此，我们提出了一种名为CHOPS（结合客户资料的聊天助手）的LLM代理，旨在：（1）高效利用现有数据库或系统查询用户信息，或遵循既定指南与系统交互；（2）提供准确合理的响应并执行系统内的必要操作，同时避免有害操作；（3）通过结合小型和大型LLM以实现性能满意且成本合理的推理。  我们开发了一个实用的数据集，称为CPHOS-dataset，它包括一个数据库、指导文件以及来自CPHOS平台的模拟物理奥林匹克组织服务的问答对。CPHOS是一个面向高中教师和学生的在线平台。我们通过使用CPHOS-dataset进行了广泛的实验，验证了CHOPS架构的性能，目标是展示LLM如何提升或替代人工客户服务。关于我们的提案架构和数据集的代码可在此处获取：<https://github.com/JingzheShi/CHOPS>。**|
|**2024-03-31**|**DiffAgent: Fast and Accurate Text-to-Image API Selection with Large Language Model**|Lirui Zhao et.al.|[2404.01342](http://arxiv.org/abs/2404.01342)|**[link](https://github.com/opengvlab/diffagent)**|**文本到图像（T2I）生成模型近年来备受瞩目，在学术研究和实际应用中大放异彩。例如，Civitai平台，一个T2I创新的聚集地，目前汇集了74,492种独特的模型，这带来了选择最合适的模型和参数的艰巨任务，通常需要多次试验。借鉴大型语言模型（LLMs）工具使用研究的思路，我们推出了DiffAgent，这是一个通过API调用来快速筛选准确选项的LLM代理。DiffAgent采用了一种新颖的两阶段训练框架，称为SFTA，使其能够根据人类偏好精确地将T2I API的响应与用户输入对齐。为了训练和评估DiffAgent的能力，我们构建了DABench，这是一个全面的数据库，涵盖了社区中的各种T2I API。实验结果显示，DiffAgent不仅在选择适当的T2I API方面表现出色，还验证了SFTA训练框架的有效性。相关代码已可在https://github.com/OpenGVLab/DiffAgent获取。**|
|**2024-03-31**|**Algorithmic Collusion by Large Language Models**|Sara Fish et.al.|[2404.00806](http://arxiv.org/abs/2404.00806)|null|随着算法定价的兴起，人们担忧算法间的合谋问题。我们通过实验使用基于大型语言模型（LLMs）的定价代理，特别是GPT-4，进行了探究。研究发现：(1) LLM驱动的定价机制在定价任务上表现出色；(2) 在寡头竞争环境中，LLM定价代理会自发地进行合谋，从而损害消费者利益；(3) 对LLM指令（“提示”）看似微小的变化可能加剧这种合作行为。这些结果同样适用于拍卖场景。我们的研究结果强调了对算法定价进行反垄断监管的必要性，并揭示了针对LLM定价代理特有的监管挑战。|
|**2024-03-31**|**"My agent understands me better": Integrating Dynamic Human-like Memory Recall and Consolidation in LLM-Based Agents**|Yuki Hou et.al.|[2404.00573](http://arxiv.org/abs/2404.00573)|null|在这个研究中，我们提出了一种创新的人类记忆架构，旨在提升基于大型语言模型的对话代理的认知能力。我们的设计使得这些代理能自主检索生成响应所需的必要记忆，从而解决LLMs在时间认知上的局限。我们借鉴了人类的记忆线索召回机制作为触发点，以实现精确且高效的回忆。此外，我们开发了一个数学模型，动态量化记忆巩固过程，考虑了诸如上下文相关性、时间流逝和回忆频率等因素。代理会从用户的交互历史中存储记忆，这些记忆被封装在数据库中，每个记忆都包含了内容和时间关联的语境。这样，通过类似人类识别和回忆过往经历的方式，系统能够战略性地存储记忆，并理解它们对用户在时间线上的重要性。|

<p align=right>(<a href=#updated-on-20240519>back to top</a>)</p>

## llm

|Publish Date|Title|Authors|PDF|Code|abstract|
|---|---|---|---|---|---|
|**2024-05-16**|**UniRAG: Universal Retrieval Augmentation for Multi-Modal Large Language Models**|Sahel Sharifymoghaddam et.al.|[2405.10311](http://arxiv.org/abs/2405.10311)|null|## 背景  近期，多模态（MM）大型语言模型（LLMs）已经解锁了许多需要多模态理解（如图像描述或视觉问答）和生成（如文本引导的图像生成或编辑）复杂任务。为了进一步提升MM-LLMs的输出质量，我们提出了一种模型通用的UniRAG技术，它在推理阶段将相关检索信息添加到提示中，作为少量样例。与普遍认为检索增强（RA）主要改进罕见实体的生成或理解不同，我们在MSCOCO数据集上对包括GPT4、Gemini-Pro在内的专有模型以及Llava、LaVIT和Emu2等开源小型模型进行了评估，结果显示，这些模型在输入提示通过MM检索器（如UniIR模型）增强后，显著提高了生成质量。|
|**2024-05-16**|**4D Panoptic Scene Graph Generation**|Jingkang Yang et.al.|[2405.10305](http://arxiv.org/abs/2405.10305)|**[link](https://github.com/jingkang50/psg4d)**|**我们生活在一个三维空间中，同时通过第四维时间向前推进。为了使人工智能能够全面理解这种4D环境，我们提出了一种新的表示形式——4D全景场景图（PSG-4D），它将动态4D世界中的原始视觉数据抽象为节点和边，节点代表具有精确位置和状态信息的实体，边捕捉时间关系。为了促进在这一新领域的研究，我们构建了一个丰富的注释PSG-4D数据集，包含3000个RGB-D视频，总计100万帧，每帧都带有4D全景分割掩码以及详细的动态场景图标签。我们为此任务提出了一种名为PSG4DFormer的Transformer模型，该模型能够预测全景分割掩码，沿时间轴跟踪掩码，并通过关系组件生成相应的场景图。在新数据集上的大量实验表明，我们的方法为未来的PSG-4D研究提供了一个强大的基准。最后，我们展示了如何通过将大型语言模型融入我们的PSG-4D系统来实现动态场景理解的一个实际应用示例。**|
|**2024-05-16**|**HW-GPT-Bench: Hardware-Aware Architecture Benchmark for Language Models**|Rhea Sanjay Sukthanker et.al.|[2405.10299](http://arxiv.org/abs/2405.10299)|**[link](https://github.com/automl/hw-aware-llm-bench)**|**随着语言模型的规模不断扩大，对硬件指标（如延迟、能耗、GPU内存使用和性能）之间的权衡需求日益增长。人们正在寻求为不同语言模型配置建立帕累托前沿，以在指定硬件限制下找到最优模型。然而，对多种架构在多台设备上的全面训练和评估在计算上是不可行的。为此，我们提出了HW-GPT-Bench，这是一个基于硬件感知的语言模型代理基准，利用神经架构搜索（NAS）中的权重共享技术，在一个模型中高效地训练包含不同规模语言模型的超网络。我们在13种设备上对这些模型进行了性能剖析，考虑了5种硬件指标和3种不同的模型规模。最后，我们通过8种不同的多目标NAS算法展示了HW-GPT-Bench的可用性，并评估了由此产生的帕累托前沿的质量。我们的目标是推动和加速大型语言模型的多目标方法，如NAS和结构化剪枝的研究。**|
|**2024-05-16**|**Timeline-based Sentence Decomposition with In-Context Learning for Temporal Fact Extraction**|Jianhao Chen et.al.|[2405.10288](http://arxiv.org/abs/2405.10288)|null|**摘要：**  事实抽取对于构建知识图谱至关重要。随着对时间相关事实在下游任务中的需求增长，出现了时间性事实抽取的任务。本文特别关注从自然语言文本中提取时间性事实。先前的研究未能妥善处理复杂句子中时间与事实对应关系的建立难题。为解决这一挑战，我们提出了一种基于时间线的句子分解策略，利用大语言模型（LLMs）进行上下文学习，以实现对事实相关时间线的精细理解。然而，直接使用LLMs进行时间性事实抽取的性能并不理想。因此，我们引入了TSDRE方法，将LLMs的分解能力融入到小型预训练语言模型（PLMs）的传统微调过程中。  为了支持评估，我们构建了一个复杂的时序事实抽取数据集ComplexTRED。实验结果显示，TSDRE在HyperRED-Temporal和ComplexTRED数据集上实现了最先进的性能。|
|**2024-05-16**|**Revisiting OPRO: The Limitations of Small-Scale LLMs as Optimizers**|Tuo Zhang et.al.|[2405.10276](http://arxiv.org/abs/2405.10276)|null|近年来，许多研究旨在通过策略性提示提升大型语言模型（LLMs）的效能。特别是优化通过prompting（OPRO）方法表现出顶尖性能，它利用LLMs作为优化器，目标是寻找能最大化任务准确性的指令。本论文重新审视了OPRO在小型LLMs（如LaMa-2系列和Mistral 7B）上的自动化提示效果。我们的研究表明，对于小型LLMs，OPRO的效果有限，因为其有限的推理能力限制了优化潜力。因此，我们建议未来的自动提示工程应同时考虑模型能力和计算成本。针对小型LLMs，我们推荐直接提供明确阐述目标和方法的指令，作为稳健的提示基线，以确保在当前研究中实现高效且有效的提示设计。|
|**2024-05-16**|**Keep It Private: Unsupervised Privatization of Online Text**|Calvin Bao et.al.|[2405.10260](http://arxiv.org/abs/2405.10260)|**[link](https://github.com/csbao/kip-privatization)**|**## 背景  作者身份混淆技术有望通过自动重写文本来保护网络通信中的个人隐私。然而，在自然语言处理（NLP）文献中，这些技术的评估大多局限在狭小场景下，主要依赖于表面的编辑操作，可能导致输出不自然。本研究提出了一种自动文本私密化框架，通过强化学习对大型语言模型进行微调，以生成兼顾准确、连贯和隐私的重写。我们在大规模的英语Reddit帖子测试集上进行了详尽的评估，该数据集由68,000名作者撰写，包含短到中等长度的文本。我们探讨了在不同评估条件下，如作者简介长度和作者识别策略，性能的变化。我们的方法在自动化指标和人工评估中保持高文本质量，并成功地规避了几种自动作者识别攻击。**|
|**2024-05-16**|**When LLMs step into the 3D World: A Survey and Meta-Analysis of 3D Tasks via Multi-modal Large Language Models**|Xianzheng Ma et.al.|[2405.10255](http://arxiv.org/abs/2405.10255)|null|随着大型语言模型（LLMs）的不断发展，它们与三维空间数据（3D-LLMs）的融合取得了显著进步，这极大地增强了理解和互动物理环境的能力。这篇综述详细探讨了使LLMs能够处理、理解并生成三维数据的方法论，强调了LLMs的独特优势，如上下文学习、逐步推理、开放词汇能力和丰富的世界知识，这些将极大地推动人工智能体在空间理解与交互方面的发展。研究覆盖了从点云到神经辐射场（NeRF）等各种三维数据表示，并考察了它们与LLMs在任务中的结合，如三维场景理解、描述、问答和对话，以及基于LLM的代理进行空间推理、规划和导航。此外，我们还简要回顾了其他结合三维和语言的方法。本文的元分析显示了显著的进步，但也指出了挖掘3D-LLMs全部潜力所需的创新方法的必要性。因此，本文旨在为未来的研究方向提供指导，探索和扩展3D-LLMs在理解和互动复杂三维世界的能力。为了支持本调查，我们已在GitHub上建立了一个项目页面，整理并列出了相关论文：https://github.com/ActiveVisionLab/Awesome-LLM-3D。|
|**2024-05-16**|**A Systematic Evaluation of Large Language Models for Natural Language Generation Tasks**|Xuanfan Ni et.al.|[2405.10251](http://arxiv.org/abs/2405.10251)|null|近期的研究已评估了大型语言模型（LLMs）在常识推理、数学推理和代码生成等方面的能力。然而，据我们所知，尚无专门针对自然语言生成（NLG）任务的深入研究，这是衡量模型优秀程度的关键标准。因此，本论文旨在全面评估知名且性能出色的LLMs，包括ChatGPT、ChatGLM、基于T5的模型、基于LLaMA的模型和Pythia模型，在对话生成和文本总结等NLG任务中的表现。我们选择了涵盖英语和中文的数据集，并设计了一种共同的评估框架，包括输入模板和后处理策略。研究结果报告了自动评分，同时进行了详细分析。|
|**2024-05-16**|**IntelliExplain: Enhancing Interactive Code Generation through Natural Language Explanations for Non-Professional Programmers**|Hao Yan et.al.|[2405.10250](http://arxiv.org/abs/2405.10250)|null|大型语言模型（LLMs）在根据自然语言描述自动生成可执行代码方面展现出巨大潜力，特别是通过互动功能，用户可以通过迭代反馈指导模型。然而，当前的互动方式往往假设用户具备调试源代码的专业知识，对非专业程序员不太友好。这使得使互动代码生成对不同编程水平的个体更易于使用成为一个挑战。为解决这个问题，我们提出了IntelliExplain，这是一种创新的人机交互范式，通过让用户通过自然语言解释与源代码互动，提升非专业人士的体验。用户通过提供他们发现错误的自然语言纠正反馈，来指导系统修订代码，直到用户对系统的代码解释感到满意。我们的用户研究显示，使用IntelliExplain的用户在Text-to-SQL和Python代码生成任务中的成功率分别比纯GPT-3.5提高了11.6%和25.3%，同时所需时间分别减少了39.0%和15.6%。|
|**2024-05-16**|**CPsyExam: A Chinese Benchmark for Evaluating Psychology using Examinations**|Jiahao Zhao et.al.|[2405.10212](http://arxiv.org/abs/2405.10212)|null|在这篇论文中，我们提出了一种创新的心理学基准测试——CPsyExam，它源于中国语言考试的问题。CPsyExam旨在分别强调心理学知识和案例分析的重要性，认识到将心理学知识应用于实际情境的价值。从22,000个问题库中，我们精选了4,000个来构建该基准，确保了主题的均衡覆盖，并包含了各种案例分析方法的多样性。此外，我们对一系列现有的大型语言模型（LLMs）进行了评估，包括开源和API基础的模型。实验和分析结果显示，CPsyExam是一个有效的确立语言模型对心理学理解能力的基准，同时支持在不同粒度上比较这些模型。|

<p align=right>(<a href=#updated-on-20240519>back to top</a>)</p>

