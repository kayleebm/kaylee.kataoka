---
layout: essay
type: essay
title: "Experiencing Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2025-08-11
published: true
labels:
  - Engineering
  - Reflection
  - Code
---
<img width="380px" class="rounded float-start pe-3" src="../img/CodingStandards/1_J5VZnEaZrednUe6KQ-6IvQ.jpg">
  
## Configuration Management <img src="../img/CodingStandards/coding_standards_arent_for_you.jpg" width="50px" style="vertical-align: middle; margin-left: 10px;">

During this course, we gained hands-on experience with configuration management, which is the practice of systematically handling changes to software in a way that maintains integrity and traceability. One key aspect we encountered was working with .env (environment) files, which are used to store sensitive configuration data—such as database connection strings, API keys, and authentication secrets—outside of the source code. This helps keep our codebase secure and flexible across different environments. For example, we used a local .env file to store environment variables for development on our own machines, and we also configured environment variables through Vercel's dashboard to support deployment to production. This separation allowed our apps to run correctly in both environments without changing the source code.

We also learned how to manage database changes using tools like Prisma, specifically with commands such as npx prisma migrate dev, and by editing files like schema.prisma. These tools helped us safely update our database schema whenever new components or fields were added to the application. Additionally, we faced and resolved various deployment errors on Vercel, often caused by missing or misconfigured environment variables or mismatches between our local and production databases. Understanding how to debug and fix these configuration-related issues was a critical part of successfully deploying our projects.

## Challenges of Coding Standards <img src="../img/CodingStandards/shutterstock_293450465-2560x2137.jpg" width="45px" style="vertical-align: middle; margin-left: 10px;">

While coding standards can be helpful for maintaining consistency across a project, they also come with several challenges. Experienced developers may find it difficult to adjust to strict new guidelines, especially if they have developed their own coding habits and organizational methods that don't fully align with a company’s standards.

Another common challenge is the time required to learn and adapt to new standards. Software engineers often need time to relearn practices and fully adjust, which can slow down the onboarding process. This delay can reduce overall productivity, making it more difficult to complete large or complex projects efficiently.

## Agile Project Management <img src="../img/CodingStandards/images.jpg" width="40px" style="vertical-align: middle; margin-left: 10px;">

Agile Project Management is a flexible development methodology that emphasizes short development cycles, frequent customer feedback, and iterative delivery. A variation of this approach that we used during this course is called Issue-Driven Project Management (IDPM), which organizes all tasks as GitHub issues with labels, assignments, and milestones. While building our group project, Find My Friends, we relied on IDPM to collaborate effectively. Each team member took ownership of specific tasks, and we tracked progress directly within the GitHub repository. With multiple contributors, it could sometimes be challenging to manage who was working on what at any given time. To address this, we used separate Git branches for each feature or fix, allowing us to work independently without interfering with each other’s changes before merging into the main branch.

We also created checklists and milestones for each phase of the project. This helped us stay organized, prioritize tasks, and better manage our time. By seeing who was assigned to what and tracking progress, it was easier to offer support to team members or move on to the next part of the project.

Through this experience, I learned valuable skills like breaking down large tasks, managing timelines, and collaborating effectively—skills I can now apply to personal projects and even my small business. Time management is crucial when fulfilling customer orders, and while it can sometimes be overwhelming, these project management strategies give me a structured way to stay on track and meet deadlines.

## Ethics in Software Engineering <img src="../img/CodingStandards/1_OvaSRk5EFxb_mN_M_QpUNg.png" width="40px" style="vertical-align: middle; margin-left: 10px;">

Ethics in software engineering is about more than just writing functional code—it’s about making responsible decisions that protect users and promote fairness, transparency, and trust. Throughout this course, we encountered ethical considerations firsthand, especially when handling sensitive user data in projects like Find My Friends. For example, we had to be careful not to expose personal information like names, photos, or account credentials, whether in our codebase or during deployment. This highlighted the importance of using secure authentication, protecting access to databases, and respecting user privacy. Ethics also played a role in our team collaboration—making sure work was divided fairly, credit was given where due, and issues were communicated honestly. As future developers, these experiences reminded us that software can have real-world consequences, and it’s our responsibility to ensure that what we build is not only effective, but also safe, respectful, and accountable.

## AI Usage Reflection <img src="../img/typescript/AI.png" width="40px" style="vertical-align: middle; margin-left: 10px;">

AI tools were used only for grammar, punctuation, and readability suggestions. All ideas, reflections, and writing are entirely my own.
