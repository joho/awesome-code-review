<img src="Awesome Code Review.png" alt="Awesome Code Review" />

# Awesome Code Review [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of tools, articles, books, and any other resource related to [code review](https://en.wikipedia.org/wiki/Code_review)

Code review is the systematic examination (sometimes referred to as peer review) of computer source code.

## Contents

- [Awesome Code Review ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-code-review-)
- [Contents](#contents)
- [Academic Papers](#academic-papers)
- [Articles](#articles)
- [Books](#books)
- [Talks and Podcasts](#talks-and-podcasts)
- [Tools](#tools)
- [Contribute](#contribute)
- [License](#license)

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
- [A Better Code Review](https://www.giladpeleg.com/blog/better-code-review/) Decent set of patterns and anti-patterns for code reviews.
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
- [Modern Code Reviews](https://rethought.se/research/modern-code-reviews/) Arguably belongs in academic paper, but it's a website giving an overview of evidence on code review by facet/context. Links off to a bunch of papers.
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

- [Axolo](https://www.axolo.co) Github/GitLab Slack integration. Create one ephemeral channel per pull request/ merge request.
- [Crucible](https://www.atlassian.com/software/crucible) Atlassian's on-premise code review tool.
- [Gerrit](https://www.gerritcodereview.com/) Open source git code review tool originating out of Google.
- [GitHub](https://github.com) Git hosting and pioneer of the "Pull Request".
- [Gitpod](https://gitpod.io) Code review pull requests in a full IDE within your browser.
- [LGTM](https://lgtm.com) Automated Git code review for GitHub and Bitbucket pull requests for finding security vulnerabilities and code quality issues.
- [Phabricator](https://www.phacility.com/phabricator/) Open source git/mercurial/svn code review tool originating out of Facebook.
- [PullNotifier](https://www.pullnotifier.com/) Improve pull request visibility and overall productivity for dev teams using Github and Slack.
- [PullRequest](https://www.pullrequest.com/) Code review as a service for GitHub pull requests.
- [Reviewable](https://reviewable.io/) Code review tool built on top of GitHub pull requests.
- [Review Board](https://www.reviewboard.org/) Open source review tool that is SCM/platform neutral.
- [Sider](https://sider.review/) Automated code review service for GitHub.
- [Softagram](https://softagram.com/) Automated code change visualization (and dependency analytics) for pull requests, merge requests (GitLab) and patch sets (Gerrit).
- [SonarCloud](https://sonarcloud.io) Detect code smells, bugs and vulnerabilities in Azure DevOps, Bitbucket and GitHub repositories.
- [Upsource](https://www.jetbrains.com/upsource/) JetBrain's on-premise git/mercurial/perforce/svn code review tool.
- [Viezly](https://viezly.com) Code review service with pull request visualization and enhanced navigation between changes.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [John Barton](https://johnbarton.co) has waived all copyright and
related or neighboring rights to this work.


## 🌐 Web Resources & Interactive Index
- [BUBBLE SHOOTER CANDY WHEEL LEVEL PACK](https://themindplay.pages.dev/bubble-shooter-candy-wheel-level-pack.html)
- [STRONGBLADE](https://themindplays.pages.dev/strongblade.html)
- [WORD JAM ASSOCIATION PUZZLE](https://quizverses.github.io/word-jam-association-puzzle.html)
- [CUBE DROP PUZZLE](https://quizverses-9d2f2.web.app/cube-drop-puzzle.html)
- [TANGRAM PUZZLE](https://thequizzone.pages.dev/tangram-puzzle.html)
- [SPIN SPIN](https://themindskillplayplay.pages.dev/spin-spin.html)
- [CATEGORY 2048](https://iskillquest.pages.dev/category-2048.html)
- [CHIBI DOLL AVATAR CREATOR](https://studyquests.github.io/chibi-doll-avatar-creator.html)
- [GOMU GOMAN](https://theskillquest.pages.dev/gomu-goman.html)
- [3D ACRYLIC NAIL NAIL ART GAME](https://studyquesthub.web.app/3d-acrylic-nail-nail-art-game.html)
- [BOXTERIA](https://studyplayings.web.app/boxteria.html)
- [TOYTOPIA](https://learnquesters.pages.dev/toytopia.html)
- [MIRACLE MAHJONG](https://theskillquest.pages.dev/miracle-mahjong.html)
- [GT CHAMPIONSHIP ARCADE](https://thequizzone.pages.dev/gt-championship-arcade.html)
- [CARNAGE BATTLE ARENA](https://studyplayings.pages.dev/carnage-battle-arena.html)
- [BLOCK MANIA](https://thequizzone.pages.dev/block-mania.html)
- [THE STONE MINER](https://learnquester.github.io/the-stone-miner.html)
- [CATEGORY COOKING46](https://studyquesthub.web.app/category-cooking46.html)
- [FUN IQ PUZZLE](https://studyplayings.pages.dev/fun-iq-puzzle.html)
- [HORSEBACK SURVIVAL](https://themindplay.pages.dev/horseback-survival.html)
- [MAGIC AND WIZARDS MAHJONG](https://themindzone.pages.dev/magic-and-wizards-mahjong.html)
- [CATEGORY PARTY23](https://themindplays.pages.dev/category-party23.html)
- [MARBLE BLAST](https://themindplay.pages.dev/marble-blast.html)
- [SAMURAI LEGACY](https://iskillquest.pages.dev/samurai-legacy.html)
- [CATEGORY MATCH 3](https://thelearnquester.web.app/category-match-3.html)
- [SNAKES](https://learnquester.github.io/snakes.html)
- [CELEBRITIES GET READY FOR CHRISTMAS](https://themindplaying.web.app/celebrities-get-ready-for-christmas.html)
- [SPIDER EVOLUTION](https://themindzone.pages.dev/spider-evolution.html)
- [FUN TOWN PARKING](https://theskillquest.pages.dev/fun-town-parking.html)
- [GARAGE MASTER NUTS AND BOLTS](https://theskillquest.pages.dev/garage-master-nuts-and-bolts.html)
- [RUN FROM BABA YAGA](https://learnquester.github.io/run-from-baba-yaga.html)
- [STICKMAN ARMY THE DEFENDERS](https://studyquests.github.io/stickman-army-the-defenders.html)
- [CATEGORY GROW99](https://learnquester.github.io/category-grow99.html)
- [GUN RUSH](https://learnquester.github.io/gun-rush.html)
- [BABY PIANO CHILDREN SONG](https://studyquesthub.web.app/baby-piano-children-song.html)
- [XMAS PRESENTS MAHJONG](https://theskillquest.pages.dev/xmas-presents-mahjong.html)
- [MERGE COMBO](https://studyquests.github.io/merge-combo.html)
- [CONSTRUCTION SET 3D BUILDER](https://thequizzone.pages.dev/construction-set-3d-builder.html)
- [CAP](https://thequizzone.pages.dev/cap.html)
- [CATEGORY DESTROY256](https://studyquests.pages.dev/category-destroy256.html)
- [DARTS JAM](https://theskillquest.pages.dev/darts-jam.html)
- [STACK N SORT](https://studyquests.github.io/stack-n-sort.html)
- [CATEGORY PLATFORM260](https://learnquester.pages.dev/category-platform260.html)
- [NINE CARDS OF WINTER](https://theskillquest.pages.dev/nine-cards-of-winter.html)
- [SPRUNKI 3D SHOOTER](https://iskillquest.pages.dev/sprunki-3d-shooter.html)
- [CLEAN HOUSE CLEARING TRASH AND DIRT](https://iskillquest.pages.dev/clean-house-clearing-trash-and-dirt.html)
- [PARKING FURY 3D NIGHT CITY](https://thelearnquester.web.app/parking-fury-3d-night-city.html)
- [SNAP FIX](https://studyquests.github.io/snap-fix.html)
- [PRIVACY](https://themindplaying.web.app/privacy.html)
- [BUTTERFLY KYODAI RAINBOW](https://themindplay.pages.dev/butterfly-kyodai-rainbow.html)
- [CELEBRITY SPRING FASHION TRENDS](https://iskillquest.pages.dev/celebrity-spring-fashion-trends.html)
- [DOOMSDAY TOWER DEFENSE](https://iskillquest.pages.dev/doomsday-tower-defense.html)
- [CYBERPUNK AGENT](https://studyplayings.pages.dev/cyberpunk-agent.html)
- [LINKLINK](https://learnquester.github.io/linklink.html)
- [NOOB JAILBREAK 2](https://studyquesthub.web.app/noob-jailbreak-2.html)
- [AGE OF ZOMBIES](https://theskillquest.pages.dev/age-of-zombies.html)
- [SQUARE WORLD 3D](https://themindplaying.web.app/square-world-3d.html)
- [MINI GAMES RELAX COLLECTION 2](https://themindzone.pages.dev/mini-games-relax-collection-2.html)
- [GLOVES OF BLOCK](https://iskillquest.pages.dev/gloves-of-block.html)
- [TILE HEX WORLD RED VS BLUE](https://studyquests.github.io/tile-hex-world-red-vs-blue.html)
- [CATEGORY UNBLOCKED GAMES](https://learnquester.github.io/category-unblocked-games.html)
- [WAVE DASH GEOMETRY ARROW](https://thelearnquester.web.app/wave-dash-geometry-arrow.html)
- [NG FLOW LINES](https://themindplaying.web.app/ng-flow-lines.html)
- [CATEGORY CAN T STOP PLAYING212](https://themindplay.pages.dev/category-can-t-stop-playing212.html)
- [SCREW SPIN](https://thelearnquester.web.app/screw-spin.html)
- [INDEX13](https://themindplaying.web.app/index13.html)
- [YOUR DREAM ROOM](https://thequizzone.pages.dev/your-dream-room.html)
- [LAMPHEAD](https://theskillquest.pages.dev/lamphead.html)
- [TANK ATTACK 5](https://themindplaying.web.app/tank-attack-5.html)
- [GOOSE CUP](https://themindzone.pages.dev/goose-cup.html)
- [SQUAD ASSEMBLER](https://studyplayings.pages.dev/squad-assembler.html)
- [WORD CROSS](https://studyquesthub.web.app/word-cross.html)
- [CATEGORY WATER39](https://learnquester.github.io/category-water39.html)
- [SLINGSHOT CHICKEN](https://themindplaying.web.app/slingshot-chicken.html)
- [ARCADE ROPE](https://studyplayings.pages.dev/arcade-rope.html)
- [CATEGORY TOP DOWN251](https://thelearnquester.web.app/category-top-down251.html)
- [BUBBLE MATCH MERGE](https://learnquester.github.io/bubble-match-merge.html)
- [REAL MOTORBIKE SUPER HERO STUNT 3D](https://studyquesthub.web.app/real-motorbike-super-hero-stunt-3d.html)
- [BATTLE ARENA](https://themindplaying.web.app/battle-arena.html)
- [FOOTBALL PENALTY](https://studyquesthub.web.app/football-penalty.html)
- [MOTO TRAFFIC RIDER](https://studyplayings.pages.dev/moto-traffic-rider.html)
- [HEX PLANET IDLE](https://studyquesthub.web.app/hex-planet-idle.html)
- [UNLOCK THE BOLTS](https://themindzone.pages.dev/unlock-the-bolts.html)
- [SCOOTER TOUCHGRIND TRICKS 3D](https://studyquests.github.io/scooter-touchgrind-tricks-3d.html)
- [JEWEL LEGEND QUEST](https://themindzone.pages.dev/jewel-legend-quest.html)
- [TRALALA LA LA LA ITALIANO](https://thelearnquester.web.app/tralala-la-la-la-italiano.html)
- [CATEGORY MAHJONG CONNECT](https://thelearnquester.web.app/category-mahjong-connect.html)
- [ANGRY CITY SMASHER](https://studyplayings.pages.dev/angry-city-smasher.html)
- [CATEGORY IDLE448](https://themindzone.pages.dev/category-idle448.html)
- [NUMBER COLLECTOR BRAINTEASER](https://thelearnquester.web.app/number-collector-brainteaser.html)
- [JUICY MATCH](https://studyquests.github.io/juicy-match.html)
- [CATEGORY SHOOTER](https://thelearnquester.web.app/category-shooter.html)
- [STUNT CAR EXTREME 2](https://studyquests.github.io/stunt-car-extreme-2.html)
- [DARK MYTH MONKEY MERGE](https://thequizzone.pages.dev/dark-myth-monkey-merge.html)
- [VALENTINES HIDDEN ALPHAWORDS](https://theskillquest.pages.dev/valentines-hidden-alphawords.html)
- [LITTLE LILY HALLOWEEN PREP](https://learnquester.github.io/little-lily-halloween-prep.html)
- [MERGE PIXEL](https://thequizzone.pages.dev/merge-pixel.html)
- [COLOR BRAIN TEST GAMES](https://learnquester.github.io/color-brain-test-games.html)
- [ANTS EMPIRE EVOLVE SIM](https://studyquests.github.io/ants-empire-evolve-sim.html)
- [100 ROOMS ESCAPE](https://thequizzone.pages.dev/100-rooms-escape.html)
- [CATEGORY CASUAL 4](https://learnquester.github.io/category-casual-4.html)
- [SPIN THRU](https://studyquesthub.web.app/spin-thru.html)
- [GUN MATCH SCREW](https://thelearnquester.web.app/gun-match-screw.html)
- [STEAM SORTER](https://studyquesthub.web.app/steam-sorter.html)
- [WITCHY SISTERS RELAX PUZZLE](https://iskillquest.pages.dev/witchy-sisters-relax-puzzle.html)
- [MATCH MASTER](https://studyquesthub.web.app/match-master.html)
- [BREAKTHROUGH TEAM](https://thelearnquester.web.app/breakthrough-team.html)
- [CATEGORY FLASH](https://themindzone.pages.dev/category-flash.html)
- [RIOT VILLAGE](https://studyplayings.pages.dev/riot-village.html)
- [MINE FPS SHOOTER NOOB ARENA](https://thequizzone.pages.dev/mine-fps-shooter-noob-arena.html)
- [CATEGORY FASHION105](https://themindplay.pages.dev/category-fashion105.html)
- [ZOMBIE SPACE EPISODE II](https://thelearnquester.web.app/zombie-space-episode-ii.html)
- [OBBY VS ZOMBIES](https://theskillquest.pages.dev/obby-vs-zombies.html)
- [CATEGORY 3D1 371](https://learnquester.github.io/category-3d1-371.html)
- [CONSTRUCTION SIMULATOR](https://studyquests.github.io/construction-simulator.html)
- [ULTIMATE YATZY](https://themindplaying.web.app/ultimate-yatzy.html)
- [ARROW SLIDE PUZZLE](https://studyquesthub.web.app/arrow-slide-puzzle.html)
- [OBBY GYM SIMULATOR ESCAPE](https://studyquesthub.web.app/obby-gym-simulator-escape.html)
- [INDEX6](https://learnquester.github.io/index6.html)
- [DINO IDLE PARK](https://thequizzone.pages.dev/dino-idle-park.html)
- [BUBBLE SHOOTER AURA](https://studyquests.github.io/bubble-shooter-aura.html)
- [CATEGORY FPS GAMES](https://learnquester.github.io/category-fps-games.html)
- [CONNECT CLUES THE MISSING PROFESSOR](https://themindplay.pages.dev/connect-clues-the-missing-professor.html)
- [PIRATE PARADISE](https://themindplays.pages.dev/pirate-paradise.html)
- [MEGA ESCAPE CAR PARKING PUZZLE](https://theskillquest.pages.dev/mega-escape-car-parking-puzzle.html)
- [SOCCER EURO CUP 2025](https://studyquesthub.web.app/soccer-euro-cup-2025.html)
- [REACH 2048](https://studyplayings.pages.dev/reach-2048.html)
- [BLOCK MERGE CITY](https://themindplay.pages.dev/block-merge-city.html)
- [INDEX7](https://learnquester.github.io/index7.html)
- [SNIPER FREEZE](https://iskillquest.pages.dev/sniper-freeze.html)
