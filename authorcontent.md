#  (PART) Author Guide {-}

# Content Guidelines {#content}

<div class="summaryblock">
<p>This chapter coaches you in thinking through what you might say in a post for the rOpenSci website.</p>
</div>

## Blog post or tech note? {#postornote}

The rOpenSci blog features two types of posts: long form blog posts for a broad readership, and shorter tech notes aimed at a more technical audience. The word "post" refers generically to either type.
We provide details and [selected examples of blog posts and tech notes](#postthemes) below.
[Tech notes](https://ropensci.org/technotes/) are written for a narrower audience that wants details.
They may include information on a software release with major new features, breaking changes, or significant new documentation.
They should provide something a reader could not glean from the documentation itself.

Blog posts are usually published weekly on Tuesdays.
Tech notes can be published on any weekday.
Both are given the same [promotional treatment](#promote) by rOpenSci.


## Themes of posts {#postthemes}

Read a few [posts](https://ropensci.org/archive/) and consider what you like (or not) about them.
Most posts written by community members are about packages that have passed rOpenSci software peer review, however, we have posts on a range of topics and we encourage you to consider these or to propose others.

Expand a topic below to see examples.

<ul><li><details closed>
<summary> <span title='Click to Expand'> About a peer-reviewed package developed by the authors </span> </summary>
<ul><li> [rmangal: Making Ecological Networks Easily Accessible](https://ropensci.org/blog/2019/10/21/rmangal/) talks through the scientific problem and context, shows some code examples, and talks about peer review but doesn't make that the dominant part of the post.</li>
<li> [Forcing Yourself to Make Your Life Easier](https://ropensci.org/blog/2018/04/12/ijtiff/) is an honest post with some reflection and an important message.</li>
<li> [The av Package: Production Quality Video in R](https://ropensci.org/technotes/2018/10/06/av-release/) (tech note) is to the point. av is not a peer-reviewed package but this is a good example of a tech note.</li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Major updates to key packages </span> </summary>
<ul><li> [(Re)introducing skimr v2 - A year in the life of an open source R project](https://ropensci.org/blog/2019/10/29/skimrv2/)) </li>
<li> [drake transformed](https://ropensci.org/technotes/2019/03/18/drake-700/) (technote)</li>
<li> [drake's improved high-performance computing power](https://ropensci.org/technotes/2018/05/18/drake-hpc/) (technote)</li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Reviewer perspectives </span> </summary>
<ul><li> [posts tagged reviewer](https://ropensci.org/tags/reviewer/) </li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Contributing to or taking over maintenance of a package </span> </summary>
<ul><li> [Relaunching the qualtRics package](https://ropensci.org/blog/2019/04/30/qualtrics-relaunch/) has an engaging tone while being informative and providing technical details.</li>
<li> [Monkeying around with Code and Paying it Forward](https://ropensci.org/blog/2018/04/20/monkeydo/) gives insight into how the author is thinking about workflows and contributing to rOpenSci.</li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Summarizing a Community Call </span> </summary>
<ul><li> [Code Review in the Lab](https://ropensci.org/blog/2018/11/29/codereview/) </li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Describing a creative use case for multiple rOpenSci packages </span> </summary>
<ul><li> [Where to go observe birds in Radolfzell? An answer with R and open data](https://ropensci.org/blog/2018/08/14/where-to-bird/) </li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Using an rOpenSci resource, such as the Package Development Guide or a task view </span> </summary>
<ul><li> [When Standards Go Wild - Software Review for a Manuscript](https://ropensci.org/blog/2019/04/18/wild-standards/) </li>
<li> [Using rOpenSci Software Peer Review Guidelines for Teaching](https://ropensci.org/blog/2019/08/27/software-peer-review-guidelines-for-teaching/) </li>
<li> [Getting your toes wet in R: Hydrology, meteorology, and more](https://ropensci.org/blog/2019/04/02/hydrology-task-view/) </li></ul>
</details></li>
<li><details closed>
<summary> <span title='Click to Expand'> Describe an unsolved problem and a call to action </span> </summary>
<ul><li> [rOpenSci Educators Collaborative: What Are The Challenges When Teaching Science With R?](https://ropensci.org/blog/2018/07/24/educollab-challenges/) (3 posts from unconf18)</li></ul>
</details></li></ul>

## What goes in your post? {#whatgoesin}

Since most posts contributed by community members are about packages that have passed software peer review, we use this type of post as an example to outline components you should consider including in your post.
Some components would not be included if the post is not about a peer reviewed package.

### What message would you like a reader to take away? {#takeaway}

What do you feel like you can’t resist sharing with (a very small corner of) the world?

Why did you create the package?
Discuss the tools it builds upon or how it works under the hood.
You might share your opinions, 5 tips on doing X, what was challenging and how did you meet the challenge, what got you excited or inspired you, something you learned or implemented from the software peer review process, or a compelling real-world example.

Share something a reader could not glean from the package documentation itself.

Use your own voice when you’re writing this. 
Our website has a professional tone but is less formal than, for example, an academic journal.

### Who is your audience? {#audience}

You can’t write for everyone; you should have an audience in mind.
Consider that readers of the rOpenSci blog have a broad range of interests, skills, and experiences.
Some will have deep technical knowledge in software development.
Some will be domain scientists interested in how to use the package you have developed.
Some might be reading as a way to consider how they can contribute to an open source project.
Write in a way that any reader can understand what your post is about, but target the majority of its content to a specific audience.

### Start with a short summary {#summary}

Assume no one knows what your package does or why they should care about it.
Provide an outline so your reader knows where you’re taking them, especially if your post is long or complex.
A good introduction helps potential readers know whether they want to read the rest.
Use short headings to guide the reader.

### Give a compelling example {#example}

*   Explain what you’re going to do in plain language
*   Include some code and a figure or other image
*   Before code snippets, explain what they do
*   After a figure generated by your code, explain what conclusion can be drawn from it. Don’t leave the reader to guess your intent.

### Be generous with your appreciation {#acknowledge}

Did others who are not authors of the post make significant contributions to the package or its inspiration?

Thank reviewers using their first and last names linked to their [rOpenSci author page](https://ropensci.org/authors/) if they have one, or to their relevant online presence (e.g. website, Twitter, GitHub) and link to the software review thread.
There is no obligation to do this, but you could note something specific that you improved in your package or in your coding or documentation practice as a direct result of reviewers’ comments.

### Consider including a call to action {#action}

Do you talk about future plans for package development?
Consider opening issues to illustrate your thinking.
If you’re willing to consider code or documentation contributions from others, label those issues “[help wanted](https://github.com/search?q=org%3Aropensci+label%3A%22help+wanted%22+state%3Aopen&type=Issues)” (no hyphen, no emojis) and “[good first issue](https://github.com/search?q=org%3Aropensci+label%3A%22good+first+issue%22+state%3Aopen&type=Issues)” or “[beginner](https://github.com/search?q=org%3Aropensci+label%3A%22beginner%22+state%3Aopen&type=Issues)” if those apply. People who want to contribute to rOpenSci can find these by searching GitHub (example: [org:ropensci label:"help wanted" state:open](https://github.com/search?q=org%3Aropensci+label%3A%22help+wanted%22+state%3Aopen&type=Issues)), and we occasionally feature these in our [newsletter](https://news.ropensci.org/).

If you want people to tell you how they have used your package, tell them how you want them to do that. Encourage them to submit their use case to our [public forum](https://discuss.ropensci.org/c/usecases).
There’s a template to help. We tweet these to help others see applications and we tag both the package author and use case submitter to give credit.
For longer form use cases, they could submit a vignette to include as an article in your package documentation ([example](https://docs.ropensci.org/cyphr/articles/data.html)).

If you want people to give you general feedback, tell them how you’d like to receive that.

### Conclusion or summary {#conclusion}

Will readers understand your take-home message clearly enough to tweet about your post?
You might need to remind them of your main points.

Now **[review the Technical Guidelines](#technical)** for submitting your draft post, and you’re ready to go.
