# Week 1: Introduction to HCI & User Experience Workflow

## Introduction
**Human-Computer Interaction (HCI)** is the study of how people interact with computers and digital products. Its goal is to design systems that are **easy to use, efficient, and enjoyable**. This week focuses on understanding the HCI design life cycle, setting up a prototyping tool, and evaluating the usability of an everyday app.

## Objective
To understand the **HCI design life cycle** and set up the **prototyping environment**.

## HCI Design Life Cycle
The HCI design life cycle is a repeating process that helps designers build products around real user needs.

1. **Understand users:** learn who the users are, what they need, and in what situation they use the product.
2. **Define requirements:** decide what the product must do to meet those needs.
3. **Design:** create sketches and wireframes of the screens and layout.
4. **Prototype:** build a clickable version of the design to test the idea early.
5. **Evaluate:** check the design for usability problems using heuristic evaluation or user testing.
6. **Iterate:** fix the problems found and repeat the cycle until the design works well.

## Practical Tasks

### 1. Prototyping Environment (Figma)
I registered on **Figma** and explored the design canvas. Figma is a browser-based design tool used to create wireframes and interactive prototypes. I learned the main parts of the workspace: **frames** for screens, the **layers panel** for organizing elements, the **design panel** for size, color, and text, and the **export option** for saving screens as images.

**Figma design used:** [Foodpanda design on Figma](https://www.figma.com/design/ubBxMUhuy3XYtEHMaYrgUx/Foodpanda--Community-?node-id=3-5&t=HHplywHKT50kAKA2-0)

### 2. Usability Evaluation of an Everyday App (Foodpanda)
I evaluated the **Foodpanda** food delivery app using **Nielsen's 10 Usability Heuristics**, a well-known set of rules for judging how usable an interface is. I followed the main user flow: browsing the home screen, opening a restaurant, choosing an item, and checking the cart. Each problem was rated from **1 (cosmetic)** to **4 (critical)**.

**Problems found:**

- **Price does not add up (Severity 4):** The cart total shows Rs.482.60, but the listed amounts (560 − 227 + 60 + 89) add up to Rs.482. The item price also differs from the price on the item screen. *Heuristic: Visibility of system status.*
- **Selection mismatch (Severity 3):** The drink chosen on the item screen is 7up, but the cart shows Mirinda. *Heuristic: Consistency and standards.*
- **No clear edit or remove option (Severity 3):** The cart does not clearly let the user change quantity or remove an item. *Heuristic: User control and freedom.*
- **Cluttered Home screen (Severity 3):** Many colored tiles, cut-off text, and icons without labels make the screen harder to understand. *Heuristic: Aesthetic and minimalist design, and Recognition rather than recall.*
- **Repeated and unclear information (Severity 2):** "Rs.0.00" is repeated beside every option, and the Add to cart button does not show the price. *Heuristic: Aesthetic and minimalist design.*
- **Inconsistent text (Severity 2):** The same offer is called "Food Fast Deals" on one screen and "Food Fest Deals" on another. *Heuristic: Consistency and standards.*

**Proposed solutions:** Show one correct price on every screen, display the exact selections in the cart, add clear plus, minus, and remove buttons, reduce clutter on the Home screen, and show the total price on the Add to cart button. I also made low-fidelity wireframes of an improved cart and item details screen to show these fixes.

### 3. GitHub Repository
I created a GitHub repository to store my **wireframes, screenshots, and evaluation reports**. A repository keeps all design work organized, tracks changes over time, and makes it easy to share the work.

## Key Learnings
- Good design is a **loop** of understanding users, designing, testing, and improving.
- **Figma** makes it easy to create and share screens and prototypes.
- **Heuristic evaluation** helps find real usability problems quickly, even in popular apps.
- Consistent information and clear controls build **user trust**.
- Documenting design work on **GitHub** keeps the project organized.

## Next Step
Use these findings to design a better food delivery app, **TastyBite**, in Figma.
