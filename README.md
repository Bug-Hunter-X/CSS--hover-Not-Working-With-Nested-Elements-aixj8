# CSS :hover Issue with Nested Elements

This repository demonstrates a common issue encountered when using the `:hover` pseudo-class in CSS with nested elements.  The problem arises when a child element (e.g., an `<a>` tag) has its own `:hover` style, potentially interfering with the parent element's `:hover` style.  The parent's `:hover` might not trigger correctly due to event capture. 

The `bug.css` file showcases the problem, and `bugSolution.css` provides a possible solution.