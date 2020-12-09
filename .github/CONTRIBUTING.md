<p align="center"><a href="https://lab.github.com/"><img alt="Learning Lab bot" src="https://user-images.githubusercontent.com/16547949/62085817-83232580-b22a-11e9-8693-7c54205b04e5.png"></a></p>

<h1 align="center">Course: Hello, GitHub Actions!</h1>

This repository powers the Learning Lab course [_Hello, GitHub Actions!_](https://lab.github.com/github/hello-github-actions!). 

This course is made up of:
- a [course repository](https://github.com/github/hello-github-actions), and
- a [template repository](https://github.com/github/hello-github-actions-template)

 The course repository is written in YAML and Markdown. The template repository could be written in any language that supports the learning objectives.

This course is currently in production. It was designed to meet the learning outcomes listed in [`README.md`](../README.md). 

### To contribute

1. Read the [contributing guidelines](#Contributing-to-Learning-Lab-courses).
1. Fork this repository. Optionally, create a branch in your fork. 
1. Make your edits, as follows:
    - to change course title, tags, tagline, short description, or logic, [edit `config.yml` in the course repository](https://lab.github.com/docs/content-for-the-catalog)
    - to change the bot's responses, edit the corresponding [response file in the `responses/` directory](https://lab.github.com/docs/writing-responses)
    - to change the course's longform description in the catalog, [edit `description.md`](https://lab.github.com/docs/course-ownership-and-repositories#set-up-the-course-repositories)
    - to change the starter code for the learner, edit the [template repository](https://lab.github.com/docs/course-ownership-and-repositories#the-repositories)
1. Commit your changes to your fork.
1. Open a pull request with:
    - base branch: the main branch of this repository
    - compare branch: the branch containing your commits in your fork
1. Wait for a review from the Learning Lab team, which will be automatically requested

## License

[CC-BY](../LICENSE) (c) 2019 GitHub, Inc.

When using the GitHub logos, be sure to follow the [GitHub logo guidelines](https://github.com/logos).

---

# Contributing to Learning Lab courses

Thanks for taking the time to contribute to a course on GitHub Learning Lab! :robot: :heart: :balloon:

### Code of Conduct

The course repository, template repository, and everyone participating in them is governed by the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to learninglab@github.com.

### What should I know before I get started?

You should be familiar with how Learning Lab courses are structured. To get up to speed on this, you can use the following resources:
- take the course: [_Write a Learning Lab course_](https://lab.github.com/github/write-a-learning-lab-course)
- read the [documentation on writing a course](https://lab.github.com/docs/writing-quickstart)
- watch the [video on how a Learning Lab course works](https://www.youtube.com/watch?v=xaLSVcwFkiI&list=PLg7s6cbtAD147DXcVp899Fk6SegoLY9gL&index=4)
- watch the [video on `config.yml`](https://www.youtube.com/watch?v=HL8MdBsFaF4&list=PLg7s6cbtAD147DXcVp899Fk6SegoLY9gL&index=2)

### Ways to contribute

There are many ways you can contribute! Here are just a few:
- report bugs: create an issue in this repository and follow the issue template for reporting bugs. Before you open the issue, ensure you read through the instructions to ensure you're not opening a duplicate
- answer questions: some of the issues in this repository may be questions asked by a learner. Answering these questions is a :sparkles: way of helping out. You can also provide this kind of contribution in the [GitHub community forum](https://github.community/t5/GitHub-Learning-Lab/bd-p/learn)
- suggest changes to the course: this could come in the form of a new learning outcome, updates to the content, updates to the bot responses, or the logic of the course
- implement bug fixes or suggestions

### Releasing

When your course branch has been merged into `main`, the [course version](https://lab.github.com/docs/course-versioning) on Learning Lab will automatically update and any new learners will receive the updated version of the course. There are no additional requirements on your part.