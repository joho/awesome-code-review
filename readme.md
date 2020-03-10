<img src="Awesome Code Review.png" alt="Awesome Code Review" />

# Awesome Code Review [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of tools, articles, books, and any other resource related to [code review](https://en.wikipedia.org/wiki/Code_review)

Code review is the systematic examination (sometimes referred to as peer review) of computer source code.

## Contents

- [Academic Papers](#academic-papers)
- [Articles](#articles)
- [Books](#books)
- [Talks and Podcasts](#talks-and-podcasts)
- [Tools](#tools)

## Academic Papers

- [An experiment to assess the cost-benefits of code inspections in large scale software development (Porter, Siy, Toman & Votta, 1997)](http://laser.cs.umass.edu/courses/cs521-621.Fall10/documents/PorterSiyetal.pdf) Early paper that tested a range of then-current review techniques including multi-stage review and code-review-via-meeting that found you can get most of the benefit in an offline, single pass, with two reviewers.
- [Anywhere, anytime code inspections: using the Web to remove inspection bottlenecks in large-scale software development (Perpich, Perry, Porter, Votta & Wade, 1997)](https://dl.acm.org/citation.cfm?id=253234) One day in the far future the best way to review code will be on the world wide web.
- [Characteristics of Useful Code Reviews: An Empirical Study at Microsoft (Bosu, Greiler, Bird, 2015)](https://www.michaelagreiler.com/wp-content/uploads/2019/02/Characteristics-Of-Useful-Comments.pdf) This paper reports the findings of a large scale qualitative and quantitative study focusing on understanding which code review comments are considered useful by developers.  
- [Code Reviewing in the Trenches: Understanding Challenges, Best Practices, and Tool Needs (MacLeod, Greiler, Storey, Bird, Czerwonka, 2018)](https://www.michaelagreiler.com/wp-content/uploads/2019/03/Code-Reviewing-in-the-Trenches-Understanding-Challenges-Best-Practices-and-Tool-Needs.pdf) A large scale study of over 900 Microsoft developers to understand their code review processes, their motivations to do code reviews, and which pitfalls and best practices they encounter.
- [Design and Code Inspections to Reduce Errors in Program Development (Fagan, 2002)](https://link.springer.com/chapter/10.1007/978-3-642-59412-0_35) Using a more formal process, particularly with defined roles for each participant and drive a big increase in error detection during review.
- [Helping Developers Help Themselves: Automatic Decomposition of Code Review Changes (Barnett et al. 2015)](http://research.microsoft.com/pubs/238937/barnett2015hdh.pdf) ([summary on the morning paper](https://blog.acolyer.org/2015/06/26/helping-developers-help-themselves-automatic-decomposition-of-code-review-changes/)) Research into automatically splitting big diffs into smaller diffs leading to better reviews.
- [Modern Code Review: A Case Study at Google](https://sback.it/publications/icse2018seip.pdf) A study that shows how code reviews work at Google.
- [Work Practices and Challenges in Pull-Based Development (Gousios et al. 2015)](https://sback.it/publications/icse2016b.pdf) ([summary on the morning paper](https://blog.acolyer.org/2015/06/23/work-practices-and-challenges-in-pull-based-development/)) Field study of how GitHub pull requests are used in the wild.

## Articles

- [8 Tips for Great Code Reviews](https://kellysutton.com/2018/10/08/8-tips-for-great-code-reviews.html) A few basic rules for a better code review process.
- [A Zen Manifesto for Effective Code Reviews](https://medium.freecodecamp.org/a-zen-manifesto-for-effective-code-reviews-e30b5c95204a) Practical tips for the submitter and the reviewer to make effective code reviews.
- [Brian Guthrie's Feature Branching Rant](https://twitter.com/bguthrie/status/937750796334174209) Twitter thread on the pros and cons of GitHub's open source first model with regards to "in-company" code review practice.
- [Building an Inclusive Code Review Culture](https://blog.plaid.com/building-an-inclusive-code-review-culture/) Guidelines to help ensure a collaborative and learning culture
- [Code Review: Create The Culture, Learn The Best Practices](https://codingsans.com/blog/code-review) Code review tips and best practices from tech leaders.
- [Code Review Etiquette](https://css-tricks.com/code-review-etiquette/) A few tips helping with positive engagement on code review.
- [Code Review Guidelines for Humans](https://phauer.com/2018/code-review-guidelines/) Some guidelines for giving and getting code reviews.
- [Code Reviews: Just Do It](https://blog.codinghorror.com/code-reviews-just-do-it/) Seminal post advocating for peer review of software back in 2006.
- [Code Reviews at Google are lightweight and fast](https://www.michaelagreiler.com/code-reviews-at-google/) Details on how code review best practices and processes work at Google.
- [Code Review Review is the Manager's Job](https://hecate.co/blog/code-review-review-is-the-managers-job) Why management should ensure code review is done and done well.
- [Comments During Code Reviews](https://medium.com/@otarutunde/comments-during-code-reviews-2cb7791e1ac7) Writing good comments during code reviews.
- [Designing Awesome Code Reviews](https://medium.com/unpacking-trunk-club/designing-awesome-code-reviews-5a0d9cd867e3) Principles for actively designing a code review process.
- [Effective Code Reviews Without the Pain](https://www.developer.com/tech/article.php/3579756/Effective-Code-Reviews-Without-the-Pain.htm) Another 2006 classic on how to effectively perform a code review.
- [Feedback Ladders: How We Encode Code Reviews at Netlify](https://www.netlify.com/blog/2020/03/05/feedback-ladders-how-we-encode-code-reviews-at-netlify/) Helpful framwork for reviewers to classify how actionable specific pieces of review feedback are.
- [How Code Reviews work at Microsoft](https://www.michaelagreiler.com/code-reviews-at-microsoft-how-to-code-review-at-a-large-software-company/) A in-depth analysis on how the code review process looks like at Microsoft.
- [How I review code](https://engineering.tumblr.com/post/170040992289/how-i-review-code) More personal advice on how to best review a pull request from an engineer at Tumblr.
- [How to do a code review](https://google.github.io/eng-practices/review/reviewer/) A thorough description of how Google engineers do code reviews, from the Google's Engineering Practices documentation.
- [How to Do Code Reviews Like a Human](https://mtlynch.io/human-code-reviews-1/) Techniques that treat the code review as not only a technical process but a social one as well.
- [On Code Review](https://medium.com/@schrockn/on-code-reviews-b1c7c94d868c) Short article about tooling and personal elements of code review, from an ex-Facebook engineer.
- [Pull Requests: How to Get and Give Good Feedback](https://kickstarter.engineering/pull-requests-how-to-get-and-give-good-feedback-f573469f0c44) Advice for both sides of the code review process, the reviewer and the reviewee.
- [Ship Small Diffs](https://blog.skyliner.io/ship-small-diffs-741308bec0d1) Why it's better to review small changes rather than large ones.
- [Stacked Pull Requests: Keeping GitHub Diffs Small](https://graysonkoonce.com/stacked-pull-requests-keeping-github-diffs-small/) A step-by-step process to split big PRs and increase review engagement.
- [The Art of Humanizing Pull Requests](https://blog.usejournal.com/the-art-of-humanizing-pull-requests-prs-b520588eb345) Emoji rich guide to the human side of code review via pull requests.
- [Towards Productive Technical Discussions](https://cate.blog/2018/07/03/towards-productive-technical-discussions/) Tactical questions and actions to push code review discussions into a more productive territory.
- [Unlearning Toxic Behaviors in a Code Review Culture](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c) A how-to guide for pull requests via how-not-too.
- [Why I changed the way I think about Code Quality](https://medium.freecodecamp.org/why-i-changed-the-way-i-think-about-code-quality-88c5d8d57e68) Why code quality is about more than just the code.

## Books

- [Best Kept Secrets of Peer Code Review](https://www.goodreads.com/book/show/1563457.Best_Kept_Secrets_of_Peer_Code_Review) Older compilation of 10 essays on the practice of code reviews. Some repetition due to different authors covering the same territory.
- [Handbook of Walkthroughs, Inspections, and Technical Reviews](https://www.amazon.com/Handbook-Walkthroughs-Inspections-Technical-Reviews/dp/0932633196) Older book covering more formal walkthroughs but covers politics and group dynamics in review well.
- [Peer Reviews in Software: A Practical Guide](https://www.amazon.com/Peer-Reviews-Software-Practical-Guide/dp/0201734850) A practical guide to formal code inspections as a code review practice.
- [Software Inspection: An Industry Best Practice](https://www.amazon.com/Software-Inspection-Industry-Best-Practice/dp/0818673400) Compendium of papers on code review practice.
- [Ultimate Guide to Code Reviews](https://www.codacy.com/ebooks/guide-to-code-reviews) Codacy sponsored ebook of code review practices based on developer survey.
- [What to Look for in a Code Review](https://leanpub.com/whattolookforinacodereview) JetBrains sponsored ebook of how to spot coding anti-patterns during review.

## Talks and Podcasts

- [Code Reviews: Honesty, Kindness, Inspiration: Pick Three - Jacob Stoebel RubyConf 2017](http://confreaks.tv/videos/rubyconf2017-code-reviews-honesty-kindness-inspiration-pick-three) How to do effective code review while remaining kind to the original author.
- [Goldilocks and the Three Code Reviews - Vaidehi Joshi RedDot Ruby Conf 2017](https://confreaks.tv/videos/reddotrubyconf2017-goldilocks-and-the-three-code-reviews) Finding just the right amount of code review by focussing on what is affecting.
- [Implementing a Strong Code-Review Culture - Derek Prior Railsconf 2015](https://www.youtube.com/watch?v=PJjmw9TRB7s) How to instill a healthy code review culture in a team.
- [Michaela Greiler on Code Reviews - SE Radio 2020](https://www.se-radio.net/2020/02/episode-400-michaela-greiler-on-code-reviews/) Michaela Greiler discusses the importance of code reviews and how to conduct them on the Software Engineering Radio podcast.

## Tools

- [Crucible](https://www.atlassian.com/software/crucible) Atlassian's on-premise code review tool.
- [Gerrit](https://www.gerritcodereview.com/) Open source git code review tool originating out of Google.
- [GitHub](https://github.com) Git hosting and pioneer of the "Pull Request".
- [Gitpod](https://gitpod.io) Code review pull requests in a full IDE within your browser.
- [GitRise](https://www.gitrise.com/) Slack Reminders for GitHub pull requests
- [LGTM](https://lgtm.com) Automated Git code review for GitHub and Bitbucket pull requests for finding security vulnerabilities and code quality issues.
- [Phabricator](https://www.phacility.com/phabricator/) Open source git/mercurial/svn code review tool originating out of Facebook.
- [PullRequest](https://www.pullrequest.com/) Code review as a service for GitHub pull requests.
- [Pull Reminders](https://pullreminders.com) Automated Slack reminders and metrics for GitHub pull requests.
- [Reviewable](https://reviewable.io/) Code review tool built on top of GitHub pull requests.
- [Review Board](https://www.reviewboard.org/) Open source review tool that is SCM/platform neutral.
- [Rubberduck](https://www.rubberduck.io) Browser extension to adds code-aware navigation to GitHub pull requests.
- [Sider](https://sider.review/) Automated code review service for GitHub.
- [Softagram](https://softagram.com/) Automated code change visualization (and dependency analytics) for pull requests, merge requests (GitLab) and patch sets (Gerrit).
- [SonarCloud](https://sonarcloud.io) Detect code smells, bugs and vulnerabilities in Azure DevOps, Bitbucket and GitHub repositories.
- [Upsource](https://www.jetbrains.com/upsource/) JetBrain's on-premise git/mercurial/perforce/svn code review tool.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [John Barton](https://johnbarton.co) has waived all copyright and
related or neighboring rights to this work.
