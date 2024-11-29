# Why Everyone Hates Web Components

![Thumbnail](https://i.ytimg.com/vi/UrS61kn4gKI/maxresdefault.jpg)

In this video, Theo discusses the criticism around web components based on Ryan Carniato's article on the subject. He highlights the collective disillusionment among framework creators regarding web components, debating their practicality, usability, and implementation challenges, while contrasting them with established frameworks like React and Solid. The discussion dives into the inherent complexity and inefficiencies that arise from web components, which may limit their effectiveness in modern web development.

## Key Points

### Web components face significant criticism.

Theo explains how many prominent web developers and framework authors, including Ryan Carniato, have publicly stated their disenchantment with web components. He emphasizes that the issues identified with web components are not just personal opinions but a shared sentiment among the community.

### Web components introduce unnecessary complexity.

The discussion includes how web components complicate the development landscape, creating challenges for framework authors who need to adapt their tools to integrate with web components. This adaptation often results in additional overhead, making codebases larger and development slower.

### The appeal of interoperability is challenged.

While web components are meant to offer interoperability across frameworks, Theo and his guests argue that achieving this interoperability often requires a considerable amount of additional work. This undermines the primary benefit that web components purport to bring to developers.

### The standardization of web components may stifle innovation.

The argument is made that once web components are standardized, they could become stagnant and prevent the evolution and innovation seen in frameworks. Theo asserts that the community may need to rethink the strategy behind web components to avoid this issue.

### Web components can only serve niche use cases effectively,

The video concludes that while web components might have their place in very specific applications, such as simple widgets like chat interfaces, they are not inherently suitable for larger, more complex applications. Frameworks like React and Solid are often better suited for these scenarios.

---

---

## Summary

#### Web components face criticism for their limitations, inefficiencies, and misalignment with modern web practices, highlighting the need for collaboration with frameworks.

## Highlights

    - 🚫 Web components are criticized for their shortcomings and inefficiencies.
    - 🔍 The browser team’s disdain for frameworks led to the creation of web components without proper collaboration.
    - ⚖️ There’s a blurred line between elements and components, leading to development overhead.
    - 🌐 Complexities in interfacing with native elements present challenges in server-side rendering.
    - 🔄 Some argue for web components’ potential but recognize current limitations.
    - 🤝 The discussion emphasizes the need for balance and collaboration between frameworks and web components.
    - 🚀 Web components could enable more dynamic designs but require better understanding and support.

## Key Insights

    - 🚫 Critical Reception: Web components are often criticized for not meeting the needs of modern developers, resulting in inefficiencies in application development. Their performance and usability issues highlight the gap between theory and practice.
    - 🔍 Lack of Collaboration: The initial push for web components by the browser team, without input from framework authors, led to missed opportunities for improvement and integration, revealing a disconnect in the development community.
    - ⚖️ Element vs. Component: The confusion between standard web elements and complex components creates challenges in development, making it harder for developers to create efficient, reusable components.
    - 🌐 Server-Side Rendering Issues: The complexities that arise from using web components with native elements complicate server-side rendering, a critical aspect of modern web applications that impacts performance and SEO.
    - 🔄 Potential vs. Reality: While there is optimism about the benefits of web components, the current state shows they are not a one-size-fits-all solution, leading to skepticism among developers.
    - 🤝 Need for Balance: The future of web development may lie in a harmonious coexistence of frameworks and web components, allowing developers to leverage the strengths of both.
    - 🚀 Empowerment through Understanding: With better comprehension of how to author and utilize web components, developers can unlock their potential for creating dynamic and reusable components, but this requires ongoing support and education.

---

---

- Complexity and Usability: Web components introduce significant complexity in their implementation. They require developers to navigate a range of APIs and behaviors that do not align well with existing HTML and DOM standards, making them harder to use effectively.

- Interoperability Issues: While web components are designed to work across different frameworks, in practice, they often require extensive workarounds. Frameworks like React and Vue have to implement additional logic to accommodate web components, leading to increased complexity and potential performance overhead.

- Performance Overhead: The performance costs associated with web components can be significant. They often introduce additional code and dependencies, which can slow down applications, especially when compared to more optimized frameworks.

- Lack of State Management: Web components, by design, don’t handle state management as intuitively as frameworks like React. This limitation makes it difficult to build complex applications that require dynamic interactions without resorting to verbose and cumbersome workarounds.

- Shadow DOM Limitations: The Shadow DOM encapsulates styles and markup, which can hinder composability and reusability. Events that originate from elements within the Shadow DOM may not bubble correctly, complicating event handling and making it challenging to integrate with existing applications.

- Standardization Issues: The standardization of web components has led to rigid structures that can stifle innovation. If a fundamental flaw exists in the standard, it becomes difficult to rectify without breaking existing implementations, leading to a stagnation of progress.

- Limited Use Cases: Web components are often seen as useful for specific, isolated functionalities (like chat widgets), but their application in broader contexts is limited. They don’t easily fit into larger, more complex applications that benefit from the flexibility and features offered by traditional frameworks

---

---

Chapter: The Controversy Surrounding Web Components
Introduction

The topic of web components has generated significant debate among developers, particularly those who work with popular frameworks like React and Vue. Web components are designed to enable the creation of reusable components that can be used across various frameworks and platforms. However, many developers argue that they come with substantial drawbacks that make them less appealing than existing solutions. This chapter delves into the concerns raised by prominent figures in the web development community, the arguments for and against web components, and the implications of their adoption.
Key Vocabulary and Concepts

    Web Components: A set of web standards that allow developers to create reusable custom elements.
    Custom Elements: The fundamental building blocks of web components that extend HTML elements.
    Shadow DOM: A DOM subtree that is isolated from the main document DOM, providing encapsulation for web components.
    Interoperability: The ability of different systems and frameworks to work together.
    Frameworks: Libraries such as React, Vue, and Angular that provide a structured way to build web applications.

The Critique of Web Components
Consensus Among Framework Authors

    Prominent framework authors, including Rich Harris (creator of Svelte) and Ryan Carniato (creator of Solid), have voiced their criticisms of web components.
    They argue that web components present significant challenges, including performance overhead and complex integration issues with existing frameworks.

Historical Context

    The push for web components arose during a phase of browser development where there was a perceived need to standardize component creation, largely in response to the rise of frameworks like React.
    This context has led to a tension between the two camps, with web components seen as a potential threat to the framework model.

The Case Against Web Components
Complexity and Performance Issues

    Web components introduce a layer of complexity that can make development more cumbersome for framework authors.
    Issues such as different lifecycle events and event handling quirks complicate the integration of web components into frameworks, leading to performance hits.

Real-World Examples

    Framework authors have reported spending significant time working around the limitations of web components, with Ryan Carniato stating, “If I could build someone for the time I’ve spent working around web components in Svelte, I’d be a rich man.”

Interoperability Challenges

    While proponents argue that web components promote interoperability, the reality is that they require extensive workarounds to function correctly within frameworks.
    The effort involved in making web components compatible often outweighs the benefits, leading some developers to question their utility.

The Potential Benefits of Web Components
Use Cases for Specific Scenarios

    Web components can be advantageous for creating isolated widgets, such as chat interfaces, where their encapsulated nature is beneficial.
    However, their utility diminishes in larger applications where frameworks provide better solutions for component composition and state management.

The Role of Standards

    Web components were created as a response to the perceived shortcomings of existing framework solutions, but their implementation as a standard has led to unintended consequences.
    The idea that web components could serve as a universal solution for component development is challenged by the reality of development practices and the need for flexibility.

The Path Forward: Collaboration and Improvement
Acknowledging the Shortcomings

    Leah Culver, a notable advocate for web components, acknowledges the challenges but emphasizes the importance of collaboration between framework authors and web component developers.
    The establishment of community groups to improve web component specifications is a positive step toward addressing the concerns raised by framework authors.

Future Directions

    The dialogue surrounding web components emphasizes the need for ongoing development and refinement of standards to make them more usable.
    Framework authors are encouraged to engage with web component standards bodies to help shape their evolution.

Conclusion

The debate surrounding web components underscores a critical moment in web development, as developers navigate the balance between innovation and practicality. While web components offer a framework-agnostic approach to building UI elements, their current implementation has raised significant concerns regarding complexity, performance, and usability. The ongoing dialogue between proponents and critics of web components is essential to finding a path forward that benefits the entire web development community. Ultimately, the future of web components will depend on collaborative efforts to refine their capabilities and address the legitimate concerns raised by framework authors.
