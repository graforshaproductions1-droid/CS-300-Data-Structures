# CS 300 – Data Structures and Algorithms Portfolio Reflection

## What was the problem you were solving in the projects for this course?

Efficient organization of academic course data defined the central challenge of this course. Academic advisors depend on immediate access to accurate course information, including prerequisite relationships and properly ordered listings, without unnecessary computational delay. Project One required a comparative evaluation of multiple data structures to determine which could best support those operational needs. Project Two required implementation of a working advising assistance program capable of loading course data from a file, storing it in an appropriate structure, and presenting results in clear alphanumeric order. At its core, the work involved designing a system that balanced correctness, efficiency, and long-term scalability.

## How did you approach the problem? Consider why data structures are important to understand.

Deliberate analysis of runtime complexity guided each decision. Data structures function as architectural foundations rather than passive storage containers. Their design directly influences how efficiently information can be accessed, modified, validated, and displayed. Comparative evaluation of vectors, hash tables, and binary search trees revealed meaningful trade-offs in lookup speed, ordering capability, and memory behavior. Selection of a Binary Search Tree reflected the dual requirement of efficient search operations and naturally sorted output through in-order traversal. Structural organization therefore minimized reliance on external sorting logic and embedded efficiency directly into the system’s design.

## How did you overcome any roadblocks you encountered while going through the activities or project?

Primary complexity emerged in recursive tree operations and prerequisite validation during file processing. Preserving the Binary Search Tree property required disciplined reasoning about conditional branching and pointer relationships. Edge cases, including duplicate course entries and invalid prerequisite references, demanded careful defensive validation. Progress depended on modular decomposition, incremental testing, and systematic debugging rather than reactive patching. Dividing responsibilities into clearly defined components clarified logical errors and strengthened overall program stability.

## How has your work on this project expanded your approach to designing software and developing programs?

Expanded perspective on software design developed through sustained attention to performance analysis. Algorithmic correctness alone does not guarantee scalability. Structural decisions determine system behavior long before optimization techniques are introduced. Engagement with Big O analysis sharpened awareness of both average-case and worst-case performance, particularly in situations where input patterns influence structural balance. Future development efforts will begin with architectural consideration of data organization rather than relying on post-implementation refinement.

## How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

Greater intentionality now shapes code structure and documentation practices. Modular separation of concerns, descriptive naming conventions, and proactive input validation improve maintainability and reliability. Clear internal documentation supports readability for both technical reviewers and broader audiences exploring the portfolio. Adaptability remains central; organized structure enables future feature expansion or alternative data structure integration without complete redesign. Commitment to clarity, sustainability, and structural discipline represents one of the most enduring outcomes of this course.



