# Greenwood-library-website

Certainly! Here's the documentation of your capstone project in Markdown format:

```markdown
# Capstone Project on Enhancing a Community Library Website

## Name: Ugwu Emeka Ben-kingsley

### Background Study

I applied git version control concepts and collaboration skills learned so far with darey.io. This has helped to enhance my understanding of branching, merging, conflict resolution, and collaborative development using Git, mirroring real-world scenarios where version control is essential for team-based projects.

### Markdown (MD)

Markdown is a lightweight markup language with plain-text formatting syntax. It is designed to be easy to read and write, and its syntax is converted into HTML for rendering on web pages. Markdown is widely used for formatting README files, documentation, notes, messages in online forums, and other types of text that benefit from simple formatting. In this project, Markdown (MD) was used.

### Objectives

- Practice cloning a repository and working with branches in Git.
- Gain experience in staging, committing, and pushing changes from both developers.
- Create pull requests and merge them after resolving any potential conflicts.

### Setup

I already had Git, MobaXterm, and Visual Studio Code installed on my local machine. Here are the steps I followed to set up the project:

1. Created a folder named `git-capstone-project` inside `darey_io` folder.
2. Created a repository on GitHub named `Greenwood-library-website` and initialized it with a `README.md` file.
3. Cloned the repository to my local machine using the command:
   ```
   git clone https://github.com/benking-web/Greenwood-library-website
   ```
4. Changed directory into the cloned folder (`greenwood-library-website`).
5. On the main branch, created four HTML files inside Visual Studio Code:
   - `About_us.html`
   - `Contact_us.html`
   - `Event.html`
   - `Home.html`
6. Added random contents to each of the files.
7. Staged the changes using:
   ```
   git add .
   ```
8. Checked the status of the repository:
   ```
   git status
   ```
9. Committed these changes to the project history:
   ```
   git commit -m "This is my first commit"
   ```
10. Pushed the main branch to GitHub:
    ```
    git push origin main
    ```

### Collaboration

#### Simulating Morgan's Work

1. Navigated to the cloned project directory (`greenwood-library-website`) and changed into it.
2. Created a new branch for Morgan's work:
   ```
   git checkout -b add-book-reviews
   ```
3. Created a new file named `book_reviews.html` using MobaXterm to represent the book reviews section.
4. Edited the file (`book_reviews.html`) using vi editor in MobaXterm, adding random text content.
5. Staged, committed, and pushed changes with a message:
   ```
   git add .
   git commit -m "Add book reviews section"
   git push origin add-book-reviews
   ```
6. Raised a pull request for Morgan's work and merged it into the main branch.

#### Simulating Jamie's Work

1. Updated the events page and created a branch named `update-events` from the main branch.
2. Staged, committed, and pushed changes with a message:
   ```
   git add .
   git commit -m "Update events"
   git push origin update-events
   ```
3. Raised a pull request for Jamie's changes and merged them into the main branch.

### Final Steps

Before raising a pull request for Jamie's update-events branch, I ensured to pull the latest changes into `update-events`.

```

This Markdown document captures the key steps, processes, and outcomes of your project using Git for version control and collaboration on enhancing a community library website. Adjust as needed based on additional details or formatting preferences!





![description of the image](images/Screenshot2.png)
