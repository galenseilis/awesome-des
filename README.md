# Awesome Discrete Event Simulation [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme)

> A curated list of discrete event simulation (DES) resources: blog posts, books, papers, projects, forums, tools, and videos.

## Contents

- [Blog Posts](#blog-posts)
- [Books](#books)
- [Papers](#papers)
- [Projects](#projects)
- [Forums](#forums)
- [Tools](#tools)
- [Videos](#videos)
- [Related Lists](#related-lists)
- [Contributing](#contributing)

## Blog Posts

| Post | Summary |
| --- | --- |
| [A Ciw Implementation of SimPy's Car Example](https://galenseilis.github.io/blog/posts/python-ciw-simpy-car/) | Port of SimPy's classic "car arrives and leaves" example to Ciw's queueing-network API. |
| [A Ciw Implementation of SimPy's Clock Example](https://galenseilis.github.io/blog/posts/python-ciw-simpy-clock/) | Ciw version of SimPy's clock example, useful for comparing how the two frameworks schedule events. |
| [A Guide to Building Hybrid DES+SD Simulations in Ciw](http://www.geraintianpalmer.org.uk/2023/08/03/hybrid-simulation-ciw/) | Walkthrough of coupling discrete event simulation with system dynamics inside Ciw. |
| [A Rust Implementation of SimPy's Simple Car DES](https://galenseilis.github.io/blog/posts/rust-simpy-car/) | Reimplements SimPy's simple car example as a discrete event simulation in Rust. |
| [Deadlock in Queueing Networks](http://www.geraintianpalmer.org.uk/2017/12/20/deadlock/) | Explains how deadlock arises in open queueing networks and how Ciw detects it. |
| [Discrete Event Simulation in Python](https://medium.com/@vitostamatti1995/discrete-event-simulation-in-python-8baf9694948f) | Introductory walkthrough of DES concepts and a first model in Python. |
| [Discrete Event Simulation using Python SimPy — Building Basic Model](https://medium.com/@lazuardy.almuzaki/discrete-event-simulation-using-python-simpy-building-basic-model-1bb34b691797) | Step-by-step construction of a basic SimPy model. |
| [Implementing a D/M/1 Queue in Ciw](https://galenseilis.github.io/blog/posts/python-ciw-d-m-1-queue/) | Simulates a single-server queue with deterministic arrivals and exponential service in Ciw. |
| [Implementing a G/G/1 Queue in Ciw](https://galenseilis.github.io/blog/posts/python-ciw-g-g-1-queue/) | Simulates a general single-server queue in Ciw, with arrival and service processes to hand. |
| [Inspection Bias in Queueing Systems](http://www.geraintianpalmer.org.uk/2020/12/18/inspection-queueing/) | Looks at how inspection policy biases the queue statistics you end up measuring. |
| [Introduction to Discrete Event Simulation with Python](https://medium.com/@vitostamatti1995/introduction-to-discrete-event-simulation-with-python-3b0cce67f92e) | Beginner-friendly introduction to DES ideas before building a model. |
| [Object-Oriented Discrete Event Simulation — with SimPy](https://towardsdatascience.com/object-oriented-discrete-event-simulation-with-simpy-53ad82f5f6e2) | Shows how to structure an object-oriented DES model on top of SimPy. |
| [Queueing Simulations](https://www.programmingopiethehokie.com/2023/01/queueing-simulations.html) | Uses Ciw to put queueing-theory laws (Little's Law, the utilization law) into practice while sizing servers. |
| [Reproducibility in discrete event simulation](http://www.geraintianpalmer.org.uk/2017/10/30/ciw-paper/) / [Reproducibility in discrete event simulation](https://www.software.ac.uk/blog/reproducibility-discrete-event-simulation) | Pair of posts on seed control and reproducible workflows for DES experiments. |
| [SimPy: Simulating Real-World Processes With Python](https://realpython.com/simpy-simulating-with-python/) | Real Python tutorial introducing SimPy's core concepts through a worked example. |
| [Simulating and Visualizing Real-Life Events in Python with SimPy](https://towardsdatascience.com/simulating-real-life-events-in-python-with-simpy-619ffcdbf81f) | A SimPy model taken all the way through to visualizing the simulated events. |
| [Simulation Design: Trans-Paradigm Best-Practice from Software Engineering](https://www.jasss.org/18/3/9.html) | Argues for applying software engineering design discipline to simulation model construction (JASSS). |
| [The effect of variability on waiting times](http://www.geraintianpalmer.org.uk/2017/07/26/variability-waits-ciw/) | Demonstrates with Ciw how arrival and service variability drive waiting times. |

## Books

| Book | Author(s) | Description |
| --- | --- | --- |
| [Discrete-Event Modeling and Simulation: A Practitioner's Guide](https://www.amazon.ca/Discrete-Event-Modeling-Simulation-Practitioners-Computational-ebook/dp/B00OD4RVJ2) | Gabriel A. Wainer | DEVS-based treatment of modelling discrete-event systems, including the CD++ toolkit and application case studies. |
| [Discrete-Event Modeling and Simulation: Theory and Applications](https://www.amazon.ca/Discrete-Event-Modeling-Simulation-Theory-Applications/dp/1420072331) | Gabriel A. Wainer | CRC volume on discrete event simulation and modelling for model-based design. |
| [Discrete-Event Simulation: A First Course](https://www.amazon.ca/Discrete-Event-Simulation-Course-Larry-Leemis/dp/0131429175) | Lawrence M. Leemis & Stephen K. Park | Undergraduate-level introduction emphasising modelling, programming and output analysis. |
| [Discrete-Event Simulation: Modeling, Programming, and Analysis](https://link.springer.com/book/10.1007/978-1-4757-3552-9) | George S. Fishman | Graduate text built around the statistical foundations of DES, from model building through output analysis. |
| [Discrete-Event System Simulation](https://www.pearson.com/en-us/subject-catalog/p/Banks-Discrete-Event-System-Simulation-5th-Edition/P200000003161) | Jerry Banks, John S. Carson, Barry L. Nelson & David M. Nicol | The widely used textbook on the principles of building, verifying and analysing DES models. |
| [Foundations and Methods of Stochastic Simulation: A First Course](https://link.springer.com/book/10.1007/978-3-030-86194-0) | Barry L. Nelson & Linda Pei | Modern first course covering random number generation, input modelling, experimentation and output analysis. |
| [Introduction to Discrete Event Simulation and Agent-based Modeling: Voting Systems, Health Care, Military, and Manufacturing](https://link.springer.com/book/10.1007/978-0-85729-139-4) | Theodore T. Allen | Case-study-driven introduction using voting, healthcare, military and manufacturing examples. |
| [Introduction to Discrete Event Systems](https://link.springer.com/book/10.1007/978-3-030-72274-6) | Christos G. Cassandras & Stéphane Lafortune | Foundational treatment of DES modelling, formalisms and control theory. |
| [Modeling and Simulation of Complex Systems](https://link.springer.com/book/10.1007/978-3-658-07529-3) | Robert Siegfried | Develops a modelling and simulation framework for complex systems. |
| [Modeling and Simulation of Discrete-Event Systems](https://www.amazon.ca/Modeling-Simulation-Discrete-Event-Systems/dp/111838699X) | DongHun Kang & Byoung Kyu Choi | Introduction to DES modelling and simulation techniques for engineered systems. |
| [Simio and Simulation: Modeling, Analysis, Applications](https://textbook.simio.com/SASMAA/index.html) | Jeffrey S. Smith, David T. Sturrock & W. David Kelton | Practice-oriented text (7th edition) teaching simulation through worked Simio examples; free online. |
| [Simulation Modeling and Analysis](https://www.mheducation.com/highered/product/simulation-modeling-analysis-law-kelton/M9781264266791.html) | Averill M. Law & W. David Kelton | The reference text on simulation experiment design, input modelling and output analysis (6th edition, 2024). |
| [Simulation Modeling using the Kotlin Simulation Library (KSL)](https://rossetti.github.io/KSLBook/) | Manuel D. Rossetti | Open-access textbook introducing discrete event modelling and analysis through the Kotlin KSL. |
| [Simulation](https://www.amazon.com/Simulation-Sheldon-M-Ross/dp/0124158250) | Sheldon M. Ross | Concise, mathematically grounded introduction to simulation methodology. |
| [Simulation: The Practice of Model Development and Use](https://www.amazon.ca/Simulation-Practice-Model-Development-Use/dp/0470847727) | Stewart Robinson | Practice-focused guide to the whole simulation study lifecycle, from conceptual modelling to implementation. |
| [Simulation-Based Optimization: Parametric Optimization Techniques and Reinforcement Learning](https://link.springer.com/book/10.1007/978-1-4899-7491-4) | Abhijit Gosavi | Covers simulation optimization, from gradient-based and score-function methods to reinforcement learning. |
| [Simulation of Industrial Systems: Discrete Event Simulation Using Excel/VBA](https://www.amazon.ca/Simulation-Industrial-Systems-Discrete-Event/dp/1420067443) | David Elizandro & Hamdy Taha | Applies discrete event simulation to industrial systems using spreadsheet-based Excel/VBA models. |
| [System Simulation Techniques with MATLAB and Simulink](https://www.wiley.com/en-gb/System+Simulation+Techniques+with+MATLAB+and+Simulink-p-9781118647929) | Dingyü Xue & YangQuan Chen | Covers continuous, discrete event and hybrid system simulation in MATLAB and Simulink. |
| [The Little Book of DES](https://des.hsma.co.uk/) | Sammi Rosser & Dan Chalk | Free online introduction to discrete event simulation built around SimPy, from the HSMA programme. |
| [Theory of Modeling and Simulation (3rd ed.)](https://shop.elsevier.com/books/theory-of-modeling-and-simulation/zeigler/978-0-12-813370-5) | Bernard P. Zeigler, Alexandre Muzy & Ernesto Kofman | Foundational DEVS framework integrating discrete event and continuous system simulation. |
| [Use Cases of Discrete Event Simulation](https://link.springer.com/book/10.1007/978-3-642-28777-0) | Steffen Bangsow | Collection of applied, industrial case studies written with practitioner feedback. |

## Papers

| Paper | Summary |
| --- | --- |
| [A Practical and Sustainable Approach to Industrial Engineering Discrete-Event Simulation with Free Mathematical and Programming Software](https://www.mdpi.com/2071-1050/17/9/3973) (2025) | Builds DES case studies for manufacturing, maintenance and logistics with free tools such as Python and Octave. |
| [A Qualitative Comparison of Open Access Discrete Event Simulation Libraries](https://doi.org/10.1007/978-3-032-10929-3_26) (2026) | Qualitative comparison of open access DES libraries across several programming languages. |
| [A review of open source discrete event simulation software for operations research](https://www.researchgate.net/publication/281391626_A_review_of_open_source_discrete_event_simulation_software_for_operations_research#pfc) | Surveys the open source DES packages available to operations research practitioners. |
| [Ciw: An open-source discrete event simulation library](https://www.tandfonline.com/doi/full/10.1080/17477778.2018.1473909) (2019) | Journal article introducing Ciw and its design for simulating open queueing networks. |
| [Discrete Event Simulation: It's Easy with SimPy!](https://arxiv.org/abs/2405.01562) (2024) | Tutorial-style paper presenting DES concepts through SimPy. |
| [Discrete-Event Simulation for Smart Manufacturing: Assessing Software, Industry Adoption, and Future Research Challenges](https://doi.org/10.2478/bipcm-2025-0009) (2025) | Systematically evaluates leading DES software packages and their adoption in smart manufacturing. |
| [Experimental Comparison of Open Source Discrete-Event Simulation Frameworks](https://doi.org/10.1007/978-3-030-97124-3_24) (2022) | Benchmarks five open source frameworks — JaamSim, SimPy, SimJulia, SSJ and JavaSim — on performance and usability. |
| [Implementing hybrid simulations that integrate DES+SD in Python](https://www.tandfonline.com/doi/abs/10.1080/17477778.2021.1992312) (2021) | Shows how to couple discrete event simulation and system dynamics in Python. |

## Projects

| Project | Summary |
| --- | --- |
| [Discrete-event-simulation-for-solar-cell-production](https://github.com/slierp/Discrete-event-simulation-for-solar-cell-production) | SimPy-based discrete event simulation of a solar cell production line. |

## Forums

| Forum | Summary |
| --- | --- |
| [r/CiwPython](https://www.reddit.com/r/CiwPython/) | Community for the Ciw open queueing network simulation library. |
| [r/SimPy](https://www.reddit.com/r/SimPy/) | Community for the SimPy process-based discrete event simulation framework. |

### Notable Posts

| Question | Summary |
| --- | --- |
| [Simulation in Python](https://or.stackexchange.com/questions/1384/simulation-in-python) | Stack Overflow question collecting recommended simulation libraries for Python. |
| [What are process-based DES and event-based DES, exactly?](https://or.stackexchange.com/questions/11670/what-are-process-based-des-and-event-based-des-exactly) | Discussion clarifying the two main DES programming paradigms. |
| [Which books are used today to learn discrete-event simulation?](https://stackoverflow.com/questions/40428009/which-books-are-used-today-to-learn-discrete-event-simulation) | Survey of textbooks practitioners currently recommend for learning DES. |

## Tools

| Tool | Language | Description |
| --- | --- | --- |
| Sim\# ([GitHub](https://github.com/heal-research/SimSharp)) | C# | .NET port of SimPy's process-based discrete event simulation framework. |
| gem5 ([Website](https://www.gem5.org/)) | C++ | Modular platform for computer system architecture research, modelling processors, memory and interconnects. |
| ns-3 ([Website](https://www.nsnam.org/)) | C++ | Discrete-event network simulator for internet networking research and education. |
| OMNeT++ ([Website](https://omnetpp.org/)) | C++ | Discrete-event simulation framework aimed at large-scale computer and communication networks. |
| SimCpp20 ([GitHub](https://github.com/fschuetz04/simcpp20)) | C++ | Discrete-event simulation in C++20 using coroutines. |
| AnyLogic ([Website](https://www.anylogic.com/)) | Closed source | Multimethod simulation platform combining discrete event, agent-based and system dynamics modelling. |
| Arena ([Website](https://www.rockwellautomation.com/en-us/products/software/arena-simulation.html)) | Closed source | Discrete event simulation software from Rockwell Automation, common in manufacturing and healthcare. |
| DELMIA ([Website](https://www.3ds.com/products/delmia)) | Closed source | Dassault Systèmes' digital manufacturing and operations simulation suite. |
| Enterprise Dynamics ([Website](https://www.incontrolsim.com/)) | Closed source | Simulation platform for manufacturing, material handling and logistics, from INCONTROL. |
| ExtendSim ([Website](https://extendsim.com/)) | Closed source | Multi-method simulation tool that also offers discrete rate and reliability block modelling. |
| FlexSim ([Website](https://www.flexsim.com/)) | Closed source | 3D discrete event simulation with a drag-and-drop visual modelling interface. |
| GoldSim ([Website](https://www.goldsim.com/)) | Closed source | Dynamic systems simulation in a Monte Carlo framework, combining system dynamics with discrete event elements. |
| NetSim ([Website](https://www.tetcos.com/)) | Closed source | Packet-level network simulator from TETCOS used for networking R&D and teaching. |
| Simul8 ([Website](https://www.simul8.com/)) | Closed source | Commercial discrete event simulation tool for modelling and analysing business processes. |
| Sim-Diasca ([GitHub](https://github.com/Olivier-Boudeville-EDF/Sim-Diasca)) | Erlang | Multi-model, DEVS-based simulation engine with 2D/3D animation, developed at EDF. |
| DESMO-J ([Website](https://desmoj.sourceforge.net/)) | Java | Discrete event simulation framework from the University of Hamburg, supporting hybrid event/process models and 2D/3D animation. |
| JaamSim ([Website](https://jaamsim.com/)) | Java | Open source discrete event simulator with a drag-and-drop GUI and interactive 3D graphics. |
| jasima ([GitHub](https://github.com/jasima-simulator/jasima-simcore)) | Java | Java-based discrete event simulation core library and modelling framework. |
| SSJ ([GitHub](https://github.com/umontreal-simul/ssj)) | Java | Stochastic Simulation in Java: a library for Monte Carlo and discrete event simulation from Université de Montréal. |
| SIM.JS ([GitHub](https://github.com/mvarshney/simjs-source)) | JavaScript | General-purpose discrete event simulation library written entirely in JavaScript. |
| ConcurrentSim ([GitHub](https://github.com/JuliaDynamics/ConcurrentSim.jl)) | Julia | Process-oriented discrete event simulation framework for Julia, formerly SimJulia and inspired by SimPy. |
| DiscreteEvents ([GitHub](https://github.com/JuliaDynamics/DiscreteEvents.jl)) | Julia | Discrete event generation and simulation in Julia. |
| kalasim ([GitHub](https://github.com/holgerbrandl/kalasim)) | Kotlin | Discrete event simulator for Kotlin. |
| BPSimpy ([GitHub](https://github.com/claudiafracca/BPSimpyLibrary)) | Python | Generates executable simulation models compliant with the WfMC BPSim business process simulation standard. |
| Ciw ([GitHub](https://github.com/CiwPython/Ciw)) | Python | Discrete event simulation library for open queueing networks. |
| desim ([GitHub](https://github.com/sed-group/desim)) | Python | Simple discrete event simulation library built on top of SimPy. |
| desmod ([GitHub](https://github.com/westerndigitalcorporation/desmod)) | Python | Discrete event simulation modelling framework for SimPy. |
| DE-Sim ([GitHub](https://github.com/KarrLab/de_sim)) | Python | Object-oriented discrete event simulation tool for complex, data-driven modelling. |
| DESimpy ([GitHub](https://github.com/galenseilis/DESimpy)) | Python | Discrete event simulation in synchronous Python. |
| DESpy ([GitHub](https://github.com/ahbuss/DESpy)) | Python | Implements DES methodology based on Schruben's event graphs, with LEGO component support. |
| DESPy ([GitHub](https://github.com/irwinsnet-old/DesPy)) | Python | Discrete event simulation framework written in Python. |
| Hades ([GitHub](https://github.com/ki-oss/hades)) | Python | Small, user-friendly framework for asynchronous discrete event simulation in Python. |
| Hagane ([GitHub](https://github.com/carlosles/hagane/tree/main)) | Python | Functional discrete event simulation. |
| HCiw ([GitHub](https://github.com/galenseilis/HCiw)) | Python | Queueing network simulation for healthcare and other applications. |
| Khronos ([SourceForge](https://khronos-des.sourceforge.net/)) | Python | Discrete event simulation framework distributed via SourceForge. |
| pesim ([GitHub](https://github.com/Tefx/pesim)) | Python | Minimalist discrete event simulation library in Python. |
| plugboard ([GitHub](https://github.com/plugboard-dev/plugboard)) | Python | Event driven modelling and orchestration framework for simulating complex processes with interconnected stateful components. |
| PMSIM ([GitHub](https://github.com/mbafrani/AutomaticProcessSimulation)) | Python | Automatic process simulation built on SimPy and PM4Py. |
| Py-DES ([GitHub](https://github.com/vitostamatti/pydes/tree/main)) | Python | Discrete events simulation framework in Python. |
| Queueing-tool ([GitHub](https://github.com/djordon/queueing-tool)) | Python | Simulator for queueing networks. |
| QueueSim ([GitHub](https://github.com/A-Herzog/queuesim)) | Python | Discrete event stochastic simulation of queueing networks, with Erlang and Allen-Cunneen approximations for Kendall models. |
| Salabim ([GitHub](https://github.com/salabim/salabim)) | Python | Object-oriented discrete event simulation with queues, resources and 2D/3D animation. |
| SimCraft ([GitHub](https://github.com/bulentsoykan/simcraft)) | Python | DES framework for academic and industrial use, built for integration with optimization and reinforcement learning. |
| SimDist ([GitHub](https://github.com/galenseilis/SimDist)) | Python | Probability distributions for simulations in Python. |
| SimPy ([GitLab](https://gitlab.com/team-simpy/simpy)) | Python | Process-based discrete event simulation framework and the reference DES library for Python. |
| SimQ ([GitHub](https://github.com/galenseilis/SimQ)) | Python | Queueing network tool built on SimPy. |
| discrevpy ([GitHub](https://github.com/snkas/discrevpy)) | Python | Minimalist, single-threaded discrete event simulator using callback-based event execution. |
| UPSTAGE ([GitHub](https://github.com/JamesArruda/upstage)) | Python | Framework for creating robust, behavior-driven discrete event simulations. |
| queuecomputer ([GitHub](https://github.com/AnthonyEbert/queuecomputer)) | R | Computationally efficient R package for simulating queues with arbitrary arrival and service times. |
| simmer ([GitHub](https://github.com/r-simmer/simmer)) | R | Process-oriented, trajectory-based discrete event simulation package for R. |
| desim ([GitHub](https://github.com/garro95/desim)) | Rust | Discrete time event simulation framework using Rust's generator feature. |
| DESRu ([GitHub](https://github.com/galenseilis/DESRu)) | Rust | Library with the bare minimum components for writing discrete event simulations in Rust. |
| nexosim ([GitHub](https://github.com/asynchronics/nexosim)) | Rust | High-performance asynchronous framework for real-time system simulation. |
| QuokkaSim ([GitHub](https://github.com/jajetloh/quokkasim)) | Rust | DES framework built on the NeXosim engine, aimed at simplifying model building. |
| Sim ([GitHub](https://github.com/ndebuhr/sim)) | Rust | Discrete event simulation engine supporting Rust- and npm-based simulation products. |
| Simcore ([GitHub](https://github.com/systems-group/simcore/tree/main)) | Rust | Generic discrete event simulation framework for systems modeling. |
| Simul ([GitHub](https://github.com/jmqd/simul)) | Rust | Discrete event simulation library for high-level simulations of real-world problems. |

## Videos

| Video | Summary |
| --- | --- |
| [Ciw Tutorials](https://www.youtube.com/playlist?list=PLduYMAFW6YatFvymP_dCddjGCB7WBvzp_) | Video tutorial series on building simulations with Ciw. |

## Related Lists

| List | Summary |
| --- | --- |
| [Awesome Queueing Theory Software](https://github.com/A-Herzog/awesome-queueing-theory-software) | Curated list of queueing theory software, indexed by language, with recommendations. |
| [List of discrete event simulation software (Wikipedia)](https://en.wikipedia.org/wiki/List_of_discrete_event_simulation_software) | Wikipedia's overview of commercial and open source DES packages. |

## Contributing

Contributions welcome! Please open a pull request or an issue to suggest a resource.
