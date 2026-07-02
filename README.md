Original Physical Context Website

Physical engineering is fragmented across softwares where we have CAD design in one platform, circuit sim in another, where we flash the code and get physical feedback all separate. More than that, physical development is fragmented across teams. A mechanical team touches one part of the project, an electrical another, software another.

The biggest time blocks and errors arrise from one engineer making a change, and not properly communicating that change with others who need to build on top of it.

If we ever want to be able to generate firmware in the same way we can software, and do hardware code review, the first step is to create a shared context layer across your physical development organizations workflow.

That's why I'm building Physical Context. The shared context layer for physical development teams.

Structured like a lightweight background service, Physical context knows the platforms your teams work with, and anytime one of these platforms is loaded in your screen (ex. Solidworks), Physical Context begins to record the session summary including changes you make, and prompts you to write justifications for when you decide to deviate from the spec.

Each session is written to a local markdown file, that also syncs to a folder in your organizations github repository. The team interface captures the past sessions, and anytime you're working in a platform in the side pannel or pull up the main interface, you can ask questions like catch me up on changes since the last time I opened this project, what were the justifications behind this component, etc.

Eventually, Physical Context will become the foundation for generating firmware using natural language.
