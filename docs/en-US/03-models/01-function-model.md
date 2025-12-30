# Function Model

The Function Model is the base model when Logical Enterprise chooses to document its models in a structured way.

It exists to answer, clearly and in a reusable way:

- which functions exist in the company
- why each function exists
- what type of decision each function makes
- which constraints each function must respect

Without this model, the other models lose reference.

---

## The model's objective

The objective of the Function Model is not to create an org chart or describe people.

It serves to:

- separate function from job title
- make responsibilities explicit
- avoid overlap in decisions
- create a base for coherence over time
- provide clear context for people and AI

---

## When to use the Function Model

Use this model when:

- decisions start to get confused
- nobody knows who decides what
- one person has several responsibilities
- the company grows or changes in shape
- AI does not know which "role" to consider

If these situations appear, the Function Model helps.

---

## Simple structure of the model

A function can be described by answering a few questions.

### 1. Function name

A clear, direct name that represents the responsibility exercised.

Example:

- Product Definition
- Prioritization
- Rule Validation
- Risk Management

---

### 2. Function purpose

Why does this function exist?

What would stop working if it did not exist?

Example:
> Ensure the product solves the right problem and stays coherent over time.

---

### 3. Type of decisions made

What type of decision can this function make?

Example:

- define what enters or does not enter the product
- approve or reject changes
- establish priority criteria

---

### 4. Function constraints

What **can this function not** decide?

Example:

- it does not decide budget
- it does not decide technical execution
- it does not decide strategies outside the product

Constraints avoid conflict.

---

### 5. Relationship with other functions

Which functions does it depend on? Which functions depend on it?

This helps build the logical dependency hierarchy.

---

## A complete (generic) example

**Function:** Product Definition

- **Purpose:** ensure the product solves a real problem and stays coherent.
- **Decisions:** what the product is, what it is not, which problems it solves.
- **Constraints:** does not decide technical execution or short term priorities.
- **Relations:** depends on Business Purpose; guides Prioritization and Execution.

The example is simple, but already creates enough clarity.

---

## Level of detail is a choice

The model works:

- with short descriptions
- or with more detailed descriptions

What matters is:

- clarity
- real use
- updates when something changes

Excessive detail without practical use does not create value.

---

## Use with Artificial Intelligence

For AI, the Function Model helps to:

- understand "who decides what"
- respect the constraints of each function
- avoid out of scope answers
- maintain coherence between decisions

AI stops responding as a loose generalist and starts responding within a defined role.

---

## Common mistakes when using the model

Avoid:

- confusing function with job title
- creating too many functions unnecessarily
- using vague names
- not recording changes

The model should simplify, not complicate.

---

## In essence

The Function Model serves to:

- make responsibilities explicit
- separate decision from execution
- create a base for all other models
- support people and AI

Without clear functions, Logical Enterprise loses structure.

---

## Next recommended reading

Now that functions are clear, the next step is to structure **how decisions are recorded and reused**.

-> [02 - Decision Model](02-decision-model.md)
