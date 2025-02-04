# Tailwind CSS Gradient Issue
This repository demonstrates an uncommon bug encountered while using Tailwind CSS gradients. The gradient background does not apply correctly in specific scenarios, which are explained in the `bug.js` file. The solution is provided in `bugSolution.js`.

## Bug Description
The gradient background using `bg-gradient-to-r from-blue-500 to-purple-500` does not render correctly. The expected output is a smooth transition between blue and purple, but instead a solid color is shown. This can occur inconsistently across different components or due to unexpected CSS interference.

## Solution
To resolve this, add specific styling or ensure the correct structure of the element. The corrected code is in `bugSolution.js`

## Setup
To reproduce the bug, create the necessary files and HTML to render the code in bug.js. Then run the code and observe the issue.