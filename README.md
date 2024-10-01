# The Office of Digitisation & Innovation (TODI)
## Developer Workshops

### Environment (1 Corinthians 5:6-8)
The environment we work in is crucial to the overall health and productivity of our team. Just as a little yeast affects the whole dough, our tools, systems, and practices can influence the quality of our work. In this workshop, we will focus on the **Command Line Interface (CLI)** because it keeps us close to the machine. Modern cloud tools can make us feel distant from the fundamentals of development, but the CLI allows us to control and command the system directly, providing a deeper understanding of the underlying processes.

### Collaboration (Matthew 22:37-39)
Collaboration is at the heart of all development projects. Just as we are called to love our neighbors, we must collaborate effectively with our team. This means clear communication, sharing knowledge, and working towards common goals. Effective collaboration also requires a strong focus on **writing readable and maintainable code**. While AI and Large Language Models (LLMs) can generate code that works, it's often hard to maintain or understand by human developers, leading to technical debt. Writing clean, consistent, and easy-to-read code ensures that all team members can contribute to and maintain the project over time.

Here are a few examples of good and bad code:

**Bad Code Example:**
```python
def s(x):
    return x**2 + x * 3 + 4 * x**0.5
```
The function name `s` and the variable `x` are not descriptive, making it hard to understand what the code does.

**Good Code Example:**
```python
def calculate_polynomial(value):
    return value**2 + value * 3 + 4 * value**0.5
```
Here, the function name `calculate_polynomial` and the variable `value` provide much more context, making it easier to understand and maintain.

**Bad Code Example:**
```javascript
for(i=0;i<l;i++){if(a[i]==b){return true}}
```
The variable names `i`, `l`, `a`, and `b` are too cryptic, and the entire code is crammed into one line, making it difficult to read.

**Good Code Example:**
```javascript
for (let index = 0; index < listLength; index++) {
    if (array[index] === searchElement) {
        return true;
    }
}
```
This version is much more readable because it uses meaningful variable names and breaks the code into readable chunks.

Maintaining clear and understandable code ensures collaboration is efficient, even as projects scale. 

### Conduct (Galatians 6:4)
Each developer is responsible for their own work and should focus on improving their individual contributions. While collaboration is key, we must also ensure that we are regularly committing our work, communicating progress, and setting clear goals. Here's the conduct expected during the development cycle:

- **Start of Week Build Schedule**: At the start of each week, outline the tasks and goals for the week ahead.
- **Daily Commits**: Make daily commits to ensure consistent progress and to make tracking changes easier for the team.
- **End of Week Brief**: At the end of each week, summarize the accomplishments, challenges, and plans for the next week in a brief report.

### End of Week Demos
At the end of each week, each developer will showcase what they have built. These demos serve as an opportunity to highlight the benefits of the work done, whether it directly serves users or builds towards larger goals. This process, in the spirit of Galatians 6:4, encourages reflection on individual contributions and how they benefit the wider team and the project.

### Refactor Fridays
In the age of **Large Language Models (LLMs)** and **AI-generated code**, we often encounter code that runs efficiently but is hard to read and maintain. While AI can help generate good code snippets quickly, those snippets can lead to unmaintainable codebases over time. That's why we dedicate **Refactor Fridays** to code housekeeping.

**Why Refactor Fridays?**
- **Readability**: Well-structured code is easier for your team to understand and for future developers to modify.
- **Maintainability**: Refactored code helps reduce technical debt, making future updates and scaling more manageable.
- **Consistency**: Ensuring consistent coding practices across the team helps in avoiding bugs and inefficiencies.

On Fridays, developers will revisit their week's work to clean up the code, refactor inefficient structures, and ensure that their contributions align with best practices for readability and maintainability.

### DevOps
DevOps represents a modern approach to development and operations where the two practices are integrated for continuous improvement, faster delivery, and greater reliability. By automating processes and enhancing communication between development and operations teams, DevOps enables more efficient workflows and shorter development cycles.

#### Local Development
During local development, each developer works on their own feature or task. The branch naming convention for local development is:

```
<name_of_dev/feature>
```

For example, if a developer named Alex is working on a new login feature, the branch name would be:

```
alex/login-feature
```

#### Development
Once the local feature is ready, it is merged into the development branch. This is the main integration point before staging. The branch naming convention for the development environment is:

```
<development>
```

#### Staging
Once the feature has been integrated and tested, it moves to the staging environment for further testing. This is where Internal Acceptance Testing (IAT) and User Acceptance Testing (UAT) occur, with a focus group evaluating the new feature. The branch used for staging is:

```
<main>
```

#### Production
Once all tests have passed, the code is deployed to production, where it is ready to serve users. Production represents the final stage in the development lifecycle where the code is live and serving its intended purpose.

### What Isn’t Covered

In this workshop, we are focusing on the **Application Layer** of the OSI model. Here’s what is **not** covered:

- Physical Layer
- Data Link Layer
- Network Layer
- Transport Layer
- Session Layer
- Presentation Layer

For more information on the OSI model and its different layers, you can visit [this resource](https://www.techtarget.com/searchnetworking/definition/OSI).

Our focus remains on **software development** and practices relevant to building and maintaining applications.

