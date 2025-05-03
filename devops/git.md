https://git-scm.com/

https://people.irisa.fr/Anthony.Baire/git/git-for-beginners-handout.pdf

https://pre-commit.com/

https://github.com/summitech/gitexplorer

https://www.ndpsoftware.com/git-cheatsheet.html#loc=workspace;
> https://news.ycombinator.com/item?id=28578896
> https://github.com/ndp/git-cheatsheet

https://cuddly-octo-palm-tree.com/posts/2021-09-19-git-elements/
> https://news.ycombinator.com/item?id=28584422

https://www.weave.works/blog/the-gitops-maturity-model

https://www.netguru.com/codestories/5-git-commands-i-wish-i-knew-about-when-i-started-coding

https://levelup.gitconnected.com/git-worktrees-the-best-git-feature-youve-never-heard-of-9cd21df67baf

https://www.reddit.com/r/git/comments/bs3g0h/master_repositories_and_immutability_from_the/

https://ericsink.com/entries/git_immutability.html
> https://news.ycombinator.com/item?id=491923

https://community.atlassian.com/t5/Bitbucket-questions/How-do-I-disable-history-rewriting-rebase-forced-commit/qaq-p/1099076

https://softwareengineering.stackexchange.com/questions/145315/does-git-have-a-safe-mode-to-prevent-rewriting-history
> https://stackoverflow.com/questions/2085871/strategy-for-preventing-or-catching-git-history-rewrite

     git config --system receive.denyNonFastforwards true
     git config --system receive.denyDeletes true

https://wiki.phantomnet.org/wiki/everything-you-need-to-unlearn-about-git

https://github.com/lyndseypadget/semflow A Git Workflow for Version Management: RESTful APIs and beyond

https://levelup.gitconnected.com/git-worktrees-the-best-git-feature-youve-never-heard-of-9cd21df67baf

https://muhammadraza.me/2019/Exploring-Git/

https://upte.ch/blog/how-we-should-be-using-git/

https://bakkenbaeck.github.io/a-random-walk-through-git/

https://stackoverflow.com/questions/11401155/git-how-to-protect-the-branch-from-being-removed-by-other-developers

https://stackoverflow.com/questions/2471340/is-there-a-way-to-lock-a-branch-in-git?noredirect=1&lq=1

https://blog.waleedkhan.name/git-undo/
> https://news.ycombinator.com/item?id=27579701

https://www.moxio.com/blog/43/ignoring-bulk-change-commits-with-git-blame
> https://news.ycombinator.com/item?id=27683059

https://github.com/jayphelps/git-blame-someone-else
> https://news.ycombinator.com/item?id=27963868

https://www.banterly.net/2021/07/31/new-in-git-switch-and-restore/
> https://news.ycombinator.com/item?id=28024972

https://blog.sulami.xyz/posts/cleaning-up-git-history/
> https://news.ycombinator.com/item?id=28106981

https://www.presslabs.com/docs/code/gitfs/
> https://news.ycombinator.com/item?id=28263356

|-+=  git gc --auto --quiet
 | \-+- git repack -d -l -q --cruft --cruft-expiration=2.weeks.ago
 |   \--- git pack-objects --local --quiet --delta-base-offset .git/objects/pack/.tmp-XXXXX-pack --keep-true-parents --honor-pack-keep

# Changelog
https://github.com/orhun/git-cliff Summary
> https://news.ycombinator.com/item?id=28423843
> https://news.ycombinator.com/item?id=39428922

https://keepachangelog.com/en/1.0.0/
> https://news.ycombinator.com/item?id=29438221

# Books
https://git-scm.com/book/en/v2

https://jwiegley.github.io/git-from-the-bottom-up/
> https://news.ycombinator.com/item?id=26884318

https://wildlyinaccurate.com/a-hackers-guide-to-git/

# Branch Flows
https://thinkfoo.wordpress.com/2016/04/17/how-branching-affects-team-culture-talk-at-pipeline-conf-2016/

https://lethain.com/trunk-and-branches/
> https://news.ycombinator.com/item?id=30620843

## Ship / Show / Ask
https://martinfowler.com/articles/ship-show-ask.html
> https://news.ycombinator.com/item?id=28457071

## Git Flow
https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow

https://github.com/gitflow-incremental-builder/gitflow-incremental-builder

https://nvie.com/posts/a-successful-git-branching-model/

https://render.com/blog/git-organized-a-better-git-flow
> https://news.ycombinator.com/item?id=29998227
> https://lobste.rs/s/yzcjy7/git_organized_better_git_flow

### Cons.
https://thinkinglabs.io/articles/2021/07/14/on-the-evilness-of-feature-branching-a-tale-of-two-teams.html
> https://news.ycombinator.com/item?id=27850385

## Trunk based
https://trunkbaseddevelopment.com/

https://commonflow.org/spec/1.0.0-rc.5.html
> https://news.ycombinator.com/item?id=13925213

https://blog.brixit.nl/git-email-flow-versus-github-flow/
> https://news.ycombinator.com/item?id=26629765

https://devblogs.microsoft.com/devops/release-flow-how-we-do-branching-on-the-vsts-team/

http://www.utm.mx/~caff/doc/OpenUPWeb/openup/guidances/concepts/phase_milestones_5678231E.html

https://www.nomachetejuggling.com/2017/04/09/a-different-branching-strategy/
> https://lobste.rs/s/moamfx/branching_strategy_simpler_than_gitflow

https://brennan.io/2021/06/15/git-less-is-more/
> https://news.ycombinator.com/item?id=27643057

https://sethrobertson.github.io/GitBestPractices/
> https://news.ycombinator.com/item?id=27727501

http://blog.danieljanus.pl/2021/07/01/commit-groups/
> https://news.ycombinator.com/item?id=27722221

https://reviewpad.com/blog/modern-trunk-based-development/

# Commit
https://www.conventionalcommits.org/en/v1.0.0/

https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716 Semantic Commit Messages
> https://news.ycombinator.com/item?id=28669891

# Cleanup
https://blog.frankel.ch/git-cleanup/

# Logs
https://zwischenzugs.com/2018/03/26/git-log-the-good-parts/
> https://news.ycombinator.com/item?id=16677308

# Security
## Secret
https://github.com/bitnami-labs/sealed-secrets

https://github.blog/2021-03-09-git-clone-vulnerability-announced/
https://www.reddit.com/r/programming/comments/m7mdab/security_implications_of_stolen_gitobjects_files/

https://github.com/git/git/blob/master/banned.h Git's list of banned C functions
 > https://news.ycombinator.com/item?id=26347867

https://twitter.com/ryancdotorg/status/1375484757916672000
> https://news.ycombinator.com/item?id=26615938

https://blog.acolyer.org/2016/10/24/whats-wrong-with-git-a-conceptual-design-analysis/
> https://gitless.com/

https://release-monitoring.org/

https://blog.frankel.ch/inserting-new-commit-git-history/

https://medium.com/@sauvik_dolui/a-few-git-tricks-tips-b680c3968a9b

https://ohshitgit.com/

https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/

https://goiabada.blog/git-tricks-avoid-solving-the-same-rebase-conflict-multiple-times-9a3afbcf1d22

https://hal.inria.fr/hal-01112795/document HAL Id: hal-01112795https://hal.inria.fr/hal-01112795Submitted on 3 Feb 2015HALis a multi-disciplinary open accessarchive for the deposit and dissemination of sci-entific research documents, whether they are pub-lished or not. The documents may come fromteaching and research institutions in France orabroad, or from public or private research centers.L’archive ouverte pluridisciplinaireHAL, estdestinée au dépôt et à la diffusion de documentsscientifiques de niveau recherche, publiés ou non,émanant des établissements d’enseignement et derecherche français ou étrangers, des laboratoirespublics ou privés.An Effective Git And Org-Mode Based Workflow ForReproducible Research

https://github.blog/2017-10-13-stretching-spokes/

https://jonas.github.io/tig/
> https://github.com/jonas/tig c
> https://www.pofilo.fr/post/20210627-outil-tig/

https://jpalmer.dev/2021/05/interactive-git-history/
> https://news.ycombinator.com/item?id=27689664

https://medium.com/typeforms-engineering-blog/prevent-secrets-leaks-at-scale-in-repositories-e785b96e8244

https://docs.ansible.com/ansible/latest/user_guide/vault.html

https://github.com/cyberark/summon

https://github.com/gopasspw/gopass

# Hash ID
https://blog.plover.com/prog/git-rev-parse.html
> https://www.reddit.com/r/git/comments/7gzk3b/git_psa_gitrevparse/

## Signature
https://people.kernel.org/monsieuricon/what-does-a-pgp-signature-on-a-git-commit-prove
> https://news.ycombinator.com/item?id=26640915

https://stackoverflow.com/questions/15790120/what-is-the-first-line-of-git-format-patch-output/27005870#27005870

https://calebhearth.com/sign-git-with-ssh
> https://news.ycombinator.com/item?id=32831731

https://iter.ca/post/gh-sig-pwn/
> https://news.ycombinator.com/item?id=39086334

https://news.ycombinator.com/item?id=39124995

## Check
https://github.com/Orange-Cyberdefense/versionshaker

# Tools
https://github.com/svandragt/repoman

https://github.com/foriequal0/git-trim

https://githistory.xyz/

# Monorepo
https://monorepo.tools/
> https://news.ycombinator.com/item?id=30438579

https://news.ycombinator.com/item?id=26479127

https://news.ycombinator.com/item?id=26164790

https://github.blog/2021-04-29-scaling-monorepo-maintenance/

https://github.com/esrlabs/josh
> https://news.ycombinator.com/item?id=27844363

https://www.snellman.net/blog/archive/2021-07-21-monorepo-atomic/
> https://news.ycombinator.com/item?id=27903282

https://css-tricks.com/from-a-single-repo-to-multi-repos-to-monorepo-to-multi-monorepo/
> https://news.ycombinator.com/item?id=28220113

https://buttondown.email/j2kun/archive/monorepos-and-forced-migrations/
> https://news.ycombinator.com/item?id=28845570

https://yosefk.com/blog/dont-ask-if-a-monorepo-is-good-for-you-ask-if-youre-good-enough-for-a-monorepo.html

https://medium.com/@amir_h/which-version-control-system-should-i-choose-for-a-monorepo-in-2021-13a6ed532108

https://github.blog/2021-11-10-make-your-monorepo-feel-small-with-gits-sparse-index/
> https://news.ycombinator.com/item?id=29188863

https://render.com/docs/monorepo-support
> https://news.ycombinator.com/item?id=32876866

https://github.com/typeofweb/ignore-monorepo-buildstep

https://earthly.dev/blog/monorepo-tools/
> https://www.reddit.com/r/programming/comments/zmlp7h/monorepo_build_tools/

https://news.ycombinator.com/item?id=39426753

https://news.ycombinator.com/item?id=41258932

https://news.ycombinator.com/item?id=41959428

https://github.com/changesets/changesets/blob/main/docs/intro-to-using-changesets.md

# Interap
https://www.kenneth-truyers.net/2016/10/13/git-nosql-database/

https://github.blog/2020-12-17-commits-are-snapshots-not-diffs/
> https://news.ycombinator.com/item?id=26741829

# LFS
https://gregoryszorc.com/blog/2021/05/12/why-you-shouldn%27t-use-git-lfs/
> https://news.ycombinator.com/item?id=27134972

# Live
https://www.producthunt.com/posts/gitlive
> https://www.reddit.com/r/programming/comments/nqmnyl/extend_git_with_realtime_collaborative_superpowers/
https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
  
# News
https://news.ycombinator.com/item?id=43870999

https://news.ycombinator.com/item?id=43869236

https://git-scm.com/book/en/v2/Git-Tools-Rerere

https://news.ycombinator.com/item?id=43613305

https://news.ycombinator.com/item?id=43404548 blame

https://news.ycombinator.com/item?id=43272275

https://news.ycombinator.com/item?id=43234544

https://news.ycombinator.com/item?id=43230734

https://news.ycombinator.com/item?id=43142135

https://news.ycombinator.com/item?id=43080535

https://lobste.rs/s/oafv9d/on_jujutsu_magit_experience_report

https://justinpombrio.net/2025/02/11/jj-cheat-sheet.html
> https://news.ycombinator.com/item?id=43020180

https://news.ycombinator.com/item?id=42941283

https://news.ycombinator.com/item?id=42835054

https://news.ycombinator.com/item?id=42262047

https://news.ycombinator.com/item?id=42093756

https://gitlip.com/blog/infinite-git-repos-on-cloudflare-workers
> https://news.ycombinator.com/item?id=41947513

https://github.com/awslabs/git-remote-s3
> https://news.ycombinator.com/item?id=41887004

https://news.ycombinator.com/item?id=41890480

https://news.ycombinator.com/item?id=41653191

https://news.ycombinator.com/item?id=41546769

https://news.ycombinator.com/item?id=41401005

https://news.ycombinator.com/item?id=41148450

https://github.blog/open-source/git/highlights-from-git-2-46/

https://news.ycombinator.com/item?id=40998060

https://andrewlock.net/working-with-stacked-branches-in-git-is-easier-with-update-refs/

https://pr.pico.sh/ Patch requests over SSH
> https://news.ycombinator.com/item?id=40959526

https://news.ycombinator.com/item?id=40742628

https://github.com/piku/piku
> https://news.ycombinator.com/item?id=40622704

https://news.ycombinator.com/item?id=40486197

https://lwn.net/SubscriberLink/972467/595a68b99f57a87d/
> https://news.ycombinator.com/item?id=40303338

https://glasskube.dev/guides/git/
> https://news.ycombinator.com/item?id=40262056

https://github.blog/2024-04-29-highlights-from-git-2-45/

https://news.ycombinator.com/item?id=40012374

https://antonz.org/git-by-example/

https://neodyme.io/en/blog/github_secrets/
> https://news.ycombinator.com/item?id=39481933

https://jvns.ca/blog/2024/02/16/popular-git-config-options/
> https://frenchie14.itch.io/driftmania

https://news.ycombinator.com/item?id=39327192

https://news.ycombinator.com/item?id=39217149

https://news.ycombinator.com/item?id=39237668

https://jvns.ca/blog/2024/01/26/inside-git/

https://news.ycombinator.com/item?id=39088551

https://jyn.dev/2022/09/02/git-cheats.html

https://blog.scottlowe.org/2023/12/15/conditional-git-configuration/
> https://news.ycombinator.com/item?id=38942892

https://github.com/extrawurst/gitui
> https://news.ycombinator.com/item?id=38905019

https://jvns.ca/blog/2024/01/05/do-we-think-of-git-commits-as-diffs--snapshots--or-histories/
> https://news.ycombinator.com/item?id=38888527

https://wizardzines.com/comics/branches-have-no-rules/
> https://lobste.rs/s/fqnqga/branches_have_no_rules

https://github.com/aaronjensen/software-development/blob/master/commit-messages.md
> https://news.ycombinator.com/item?id=38831991

https://matklad.github.io/2023/12/31/git-things.html#Git-Things
> https://news.ycombinator.com/item?id=38830194

https://matheustavares.gitlab.io/posts/committing-without-git
> https://news.ycombinator.com/item?id=38814492

https://graphite.dev/blog/why-ban-merge-commits
> https://news.ycombinator.com/item?id=38800454

https://baecher.dev/stdout/reproducible-git-bundles/
> https://news.ycombinator.com/item?id=38764452

https://news.ycombinator.com/item?id=38590080

https://jvns.ca/blog/2023/12/04/mounting-git-commits-as-folders-with-nfs/
> https://news.ycombinator.com/item?id=38527866

https://github.com/google/git-appraise code review

https://github.com/AmrDeveloper/GQL
> https://news.ycombinator.com/item?id=38498688

https://github.blog/2023-11-20-highlights-from-git-2-43/

https://jvns.ca/blog/2023/11/10/how-cherry-pick-and-revert-work/
> https://news.ycombinator.com/item?id=38222596

https://jvns.ca/blog/2023/11/06/rebasing-what-can-go-wrong-/
> https://news.ycombinator.com/item?id=38164046

https://calebhearth.com/git-method-history
> https://news.ycombinator.com/item?id=38153309

https://news.ycombinator.com/item?id=38124845

https://github.com/iterative/dvc
> https://news.ycombinator.com/item?id=38120493

https://jvns.ca/blog/2023/11/01/confusing-git-terminology/
> https://news.ycombinator.com/item?id=38112951

https://www.qword.net/2023/10/22/the-use-and-abuse-of-the-dev-branch

https://gist.github.com/chapmanjacobd/cb8695e6b106c8c5d7285149266fab11

https://jvns.ca/blog/2023/10/20/some-miscellaneous-git-facts/
> https://lobste.rs/s/yiotbv/some_miscellaneous_git_facts

https://news.ycombinator.com/item?id=37854995

https://developers.redhat.com/articles/2023/08/02/beginners-guide-git-version-control
> https://news.ycombinator.com/item?id=37038457

https://jesseduffield.com/Lazygit-5-Years-On/
> https://news.ycombinator.com/item?id=37009879

https://sites.google.com/a/chromium.org/dev/developers/fast-intro-to-git-internals

https://benhoyt.com/writings/gogit/
> https://news.ycombinator.com/item?id=36924267

https://news.ycombinator.com/item?id=36782018

https://news.ycombinator.com/item?id=36334957

https://gitless.com/ no updates
> https://news.ycombinator.com/item?id=36370225

https://changelog.complete.org/archives/10516-using-git-annex-for-data-archiving

https://github.com/jayphelps/git-blame-someone-else
> https://news.ycombinator.com/item?id=36180249

https://www.worthe-it.co.za/blog/2023-06-02-leveling-up-your-git-server-sharing-repos.html
> https://news.ycombinator.com/item?id=36162789

https://adamj.eu/tech/2023/05/29/git-detect-in-progress-operation/

https://github.com/charmbracelet/soft-serve

https://www.freecodecamp.org/news/the-definitive-guide-to-git-merge/

https://git.zx2c4.com/cgit/
> https://news.ycombinator.com/item?id=35945497

https://git.codemadness.org/stagit/

https://www.leshenko.net/p/ugit/#
> https://news.ycombinator.com/item?id=35932074

https://bytes.zone/posts/modeling-git-internals-in-alloy-part-3-operations-on-blobs-and-trees/

https://alanastorm.com/review-of-james-coglands-building-git/
> https://news.ycombinator.com/item?id=35626698

https://gitlab.com/leipert-projects/git-recon#git-recon

https://git-scm.com/docs/git-worktree/2.39.0
> https://www.dylanpaulus.com/posts/git-worktree

https://gut-cli.dev/
> https://news.ycombinator.com/item?id=35371469

https://lore.kernel.org/git/20171225035215.GC1257@thunk.org/ Theodore Ts'o on how he uses Git when working on Linux - 2017
> https://news.ycombinator.com/item?id=35030729

https://github.com/gov4git/gov4git
> https://news.ycombinator.com/item?id=35005511

https://diziet.dreamwidth.org/14666.html Never use git submodules
> https://news.ycombinator.com/item?id=35006213

https://gavinhoward.com/2023/02/a-git-sin-re-signing-an-entire-git-repo/

https://blog.jcoglan.com/2017/05/08/merging-with-diff3/
> https://news.ycombinator.com/item?id=34557827

https://github.com/jmforsythe/Git-Heat-Map
> https://news.ycombinator.com/item?id=34563851

https://initialcommit.com/blog/git-sim
> https://news.ycombinator.com/item?id=34477976

https://medium.com/@vs28031996/remove-git-history-with-bfg-repo-cleaner-866808826eea

https://blog.waleedkhan.name/git-ui-features/
> https://news.ycombinator.com/item?id=34301543

https://www.highflux.io/blog/what-makes-git-hard-to-use

https://lwn.net/Articles/898522/
> https://news.ycombinator.com/item?id=34193244

https://github.com/h2obrain/about/blob/main/odyssey.md
> https://github.com/h2obrain/about/blob/main/snippets/snippets.md

https://opensource.com/article/22/11/git-tools

https://tylercipriani.com/blog/2022/11/19/git-notes-gits-coolest-most-unloved-feature/
> https://news.ycombinator.com/item?id=33766396

https://github.com/MichaelMure/git-bug/releases/tag/v0.8.0
> https://news.ycombinator.com/item?id=33730417

https://blog.waleedkhan.name/bringing-revsets-to-git/

https://engineering.fb.com/2022/11/15/open-source/sapling-source-control-scalable/
> https://news.ycombinator.com/item?id=33612410

https://github.com/o2sh/onefetch Cli Git information tool to display project information and code statistics

https://lwn.net/SubscriberLink/914041/4a512be97032a2f6/ Git evolve: tracking changes to changes

https://softwaredoug.com/blog/2022/11/09/idiot-proof-git-aliases.html
> https://news.ycombinator.com/item?id=33532062

https://donatstudios.com/yagni-git-gc

https://news.ycombinator.com/item?id=33261862 Ask HN: Apps that are built with Git as the back end?

https://github.blog/2022-10-13-the-story-of-scalar/

https://devblogs.microsoft.com/oldnewthing/20220929-00/?p=107229
> https://lobste.rs/s/dcqonj/i_did_merge_as_cherry_pick_thing_my_change

https://git-scm.com/docs/hash-function-transition/
> https://news.ycombinator.com/item?id=33020513

https://github.com/community/community/discussions/10539 IPv6 support for cloning Git repositories
> https://news.ycombinator.com/item?id=33024581

https://harmonyland.vercel.app/ Show HN: Git in-memory in browser with Web Assembly
> https://news.ycombinator.com/item?id=33025358

https://github.com/extrawurst/gitui
> https://news.ycombinator.com/item?id=32864036

https://novalis.org/blog/2016-11-13-analogies-for-git.html

https://sluongng.hashnode.dev/bazel-in-ci-part-1-commit-under-test

https://github.blog/2022-09-13-scaling-gits-garbage-collection/
> https://news.ycombinator.com/item?id=32826072

https://github.com/petar/maymounkov.org/blob/main/articles/governance_for_git/gov4git_whitepaper.md

https://github.blog/2022-08-30-gits-database-internals-ii-commit-history-queries/
> https://news.ycombinator.com/item?id=32651934

https://github.blog/2022-08-29-gits-database-internals-i-packed-object-store/
> https://news.ycombinator.com/item?id=32637643

https://andrealmeid.com/post/2022-07-31-keep-bisect/
> https://www.reddit.com/r/programming/comments/wg1ql3/keeping_a_project_bisectable/

https://www.garyrobinson.net/2014/10/git-in-two-minutes-for-a-solo-developer.html
> https://news.ycombinator.com/item?id=32370234

https://fully-faltoo.com/p/reviewing-each-line-of-code/

https://matt-rickard.com/how-kubernetes-broke-git/
> https://news.ycombinator.com/item?id=32294373

https://paedubucher.ch/articles/2022-07-26-git-with-multiple-e-mail-addresses.html

https://git.inept.dev/~doyle/rgit.git/about

https://agateau.com/2022/your-git-log-is-not-a-changelog/
> https://news.ycombinator.com/item?id=32122028

https://blog.plover.com/prog/git/tips-2.html
> https://news.ycombinator.com/item?id=32161247

https://github.blog/2022-06-30-write-better-commits-build-better-projects/

https://github.blog/2022-06-27-highlights-from-git-2-37/

https://codewords.recurse.com/issues/two/git-from-the-inside-out
> https://news.ycombinator.com/item?id=31964814

https://github.blog/2022-06-29-improve-git-monorepo-performance-with-a-file-system-monitor/
> https://news.ycombinator.com/item?id=31924554

https://blog.plover.com/2022/06/29/#tips
> https://news.ycombinator.com/item?id=31923429

https://dangitgit.com/en

https://www.phoronix.com/scan.php?page=news_item&px=Git-2.37-rc1-Released

https://canvatechblog.com/we-put-half-a-million-files-in-one-git-repository-heres-what-we-learned-ec734a764181
> https://news.ycombinator.com/item?id=31762245

https://www.reddit.com/r/AZURE/comments/v9bsw7/azure_devops_has_one_of_the_simplest_and_easiest/

https://think-like-a-git.net/

https://github.com/aaossa/git-activity
> https://news.ycombinator.com/item?id=31532156

https://blog.aloni.org/posts/proper-use-of-git-tags/

https://github.com/naggie/dstask
> https://news.ycombinator.com/item?id=31409707

https://github.com/wfxr/forgit
> https://news.ycombinator.com/item?id=31414179

https://rubenerd.com/git-ignores-gitignore-with-gitignore-in-gitignore/
> https://news.ycombinator.com/item?id=31420268

https://blog.palantir.com/optimizing-gits-merge-machinery-1-127ceb0ef2a1

https://github.blog/2022-04-18-highlights-from-git-2-36/
> https://news.ycombinator.com/item?id=31073154

https://stackoverflow.blog/2022/04/06/use-git-tactically/
> https://news.ycombinator.com/item?id=30943478

https://telemachus.me/git-can-break-your-tests

https://github.com/gitext-rs/git-stack
> https://jg.gg/2018/09/29/stacked-diffs-versus-pull-requests/

https://render.com/blog/git-organized-a-better-git-flow

https://news.ycombinator.com/item?id=30712175 Ask HN: What is your Git commit/push flow?

https://paul-samuels.com/blog/2022/03/12/updating-git-edit/

https://github.com/o2sh/onefetch

https://github.com/martinvonz/jj
> https://news.ycombinator.com/item?id=30398662
> https://news.ycombinator.com/item?id=36952796

https://gitbom.dev/
> https://news.ycombinator.com/item?id=30374558

https://gitless.com/

https://lobste.rs/s/rl9pxx/idea_move_hunk

https://www.schoenitzer.de/blog/2021/Shorter%20Hacks%201%20Git%20dash.html cd -

https://github.blog/2022-01-24-highlights-from-git-2-35/
> https://news.ycombinator.com/item?id=30068776

https://meldmerge.org/ diff ui
> https://news.ycombinator.com/item?id=30741123

https://gist.github.com/phoe/7d24bdb1f2be76a02fecba8cfecbef38 Forever Stable Branch

https://soap.coffee/~lthms/opinions/StackedGit.html

https://gist.github.com/lisawolderiksen/a7b99d94c92c6671181611be1641c733 Using Git Commit Message Templates to Write Better Commit Messages
> https://news.ycombinator.com/item?id=29911308

https://github.com/tkellogg/dura background process that watches your Git repositories and commits your uncommitted changes
> https://news.ycombinator.com/item?id=29784238

https://www.jenweber.dev/how-to-squash-and-rebase/
> https://news.ycombinator.com/item?id=29839884

https://lwn.net/Articles/877964/ Stochastic bisection in Git

https://news.ycombinator.com/item?id=29756272 Ask HN: Do we need an easier Git?

https://threkk.medium.com/how-to-back-up-your-git-repositories-1298a4487a31

https://github.com/gotvc/got
> https://github.com/brendoncarroll/webfs

https://nouslesdevs.com/cli/securiser-un-git/

https://github.com/jesseduffield/lazygit
> https://news.ycombinator.com/item?id=29394162

https://cj.rs//blog/git-ls-files-is-faster-than-fd-and-find/

https://github.blog/2021-11-15-highlights-from-git-2-34/
> https://news.ycombinator.com/item?id=29230100

https://riskledger.com/blog/git-basics-at-risk-ledger/
> https://news.ycombinator.com/item?id=29162234

https://visualgit.io/news.html#20211031
> https://news.ycombinator.com/item?id=29062679

[SSH signing: Add commit & tag signing/verification via SSH keys using ssh-keygen
](https://github.com/git/git/pull/1041)


https://github.com/Artawower/blamer.el
> https://news.ycombinator.com/item?id=28988346

https://emacsair.me/2017/09/01/the-magical-git-interface/
> https://news.ycombinator.com/item?id=28954058

https://blog.ploeh.dk/2015/01/15/10-tips-for-better-pull-requests/
> https://lobste.rs/s/bavio3/10_tips_for_better_pull_requests_2015

https://gitexplorer.com/
> https://news.ycombinator.com/item?id=28888763

https://blog.stephane-robert.info/post/gitlab-pipeline-dynamique/

https://graphite.dev/blog/post/y6ysWaplagKc8YEFzYfr
> https://news.ycombinator.com/item?id=28787335

https://github.com/djanderson/aho
> https://news.ycombinator.com/item?id=28771841

https://bronevichok.ru/posts/git-as-a-storage.html
> https://news.ycombinator.com/item?id=28800229

https://www.leshenko.net/p/ugit/#
> https://news.ycombinator.com/item?id=28735425

https://arxiv.org/abs/2101.06542 ConE: A Concurrent Edit Detection Tool for Large Scale Software Development
> https://news.ycombinator.com/item?id=28681873

https://about.gitlab.com/releases/2021/09/22/gitlab-14-3-released/

https://www.jelmer.uk/janitor-webhooks.html

https://itoshkov.github.io/git-tutorial
> https://news.ycombinator.com/item?id=28549652

https://www.biteinteractive.com/picturing-git-conceptions-and-misconceptions/
> https://news.ycombinator.com/item?id=28392566

https://github.blog/2021-09-01-improving-git-protocol-security-github/
> https://news.ycombinator.com/item?id=28382496

https://blog.andrewray.me/a-better-git-blame/

[Versioned DB Database in OCaml](https://github.com/mirage/irmin) 

https://github.blog/2021-08-16-highlights-from-git-2-33/ merge-ort: a new merge strategy
> https://news.ycombinator.com/item?id=28207168

https://felipec.wordpress.com/2021/07/05/git-update/
> https://news.ycombinator.com/item?id=27741204
> > https://github.com/felipec/git
