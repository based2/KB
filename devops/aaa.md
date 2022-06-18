https://github.com/Kristories/awesome-guidelines

https://www.gitops.tech/

https://zwischenzugs.com/2020/11/30/gitops-decisions/

https://opengitops.dev/

https://cookiecutter.readthedocs.io/en/1.7.2/

https://blog.spinnaker.io/managed-delivery-evolving-continuous-delivery-at-netflix-eb74877fb33c

https://worklifenotes.com/2020/06/04/7-best-practices-modern-cicd/

https://github.com/MichaelCade/90DaysOfDevOps

https://blog.container-solutions.com/fluxcd-argocd-or-jenkins-x-which-is-the-right-gitops-tool-for-you

https://news.ycombinator.com/item?id=25843210

https://devops.stackexchange.com/questions/1254/does-the-cattle-not-pets-distinction-apply-as-equally-to-machine-instances-as
https://devops.stackexchange.com/questions/2731/downloading-docker-images-from-docker-hub-without-using-docker

http://devopsku.be/

https://github.com/mozilla/sops

https://docs.google.com/document/d/e/2PACX-1vRBi4WWgHBN_w59HbKhleBLL_cI_gJhIAWEKBdw9SR7EB2ApmTCrXof6zkx_Ljfx3TaZCdsjqy3p4dw/pub

https://blog.goldfiglabs.com/2021/04/07/cloud-infrastructure-linting.html

http://muratbuffalo.blogspot.com/2016/02/holistic-configuration-management-at.html

ianceicys 3 hours ago [–]

DevOps isn't about doing the jobs of two persons (software engineer + infra engineer) it's about automating away 1 and being WAY more efficient.

Take a look at how GitHub does DevOps: Make your team’s deploys as boring as hell and stop stressing about it: https://zachholman.com/posts/deploying-software

Take a look at this funny video from Launch Darkly about different approach to DevOps: https://fast.wistia.net/embed/channel/mli3h9o3nh?wchannelid=mli3h9o3nh&wmediaid=g3ifgwu7q0

Take a look at how AWS does DevOps: https://www.youtube.com/watch?v=ngnMj1zbMPY

Take a look at how Microsoft does DevOps: https://www.youtube.com/watch?v=X4uziBlC728

Engineering has to build that REPEATABLE DevOps automation @ scale.

The informed definition of DevOps is = "DevOps is the union of people, process, and products to enable continuous delivery of value to your end users." From Microsoft's Donovan Brown - https://www.youtube.com/watch?v=WW6x0jIPpr0

https://github.com/jghoman/awesome-apache-airflow
https://eatcodeplay.com/upgrading-to-airflow-2-0-massive-performance-wins-and-lessons-learned-8c6a15cec8e7

https://airbyte.io/blog/airflow-etl-pipelines
> https://news.ycombinator.com/item?id=28799745

https://shopify.engineering/lessons-learned-apache-airflow-scale
> https://news.ycombinator.com/item?id=31480320

https://drewdevault.com/2019/10/12/how-to-fuck-up-releases.html
> https://news.ycombinator.com/item?id=26902422

https://timothyandrew.dev/blog/git-stack/
> https://news.ycombinator.com/item?id=26913959

https://jg.gg/2018/09/29/stacked-diffs-versus-pull-requests/
> https://news.ycombinator.com/item?id=18119570

https://www.usenix.org/publications/loginonline/low-context-devops

# Versioning
https://semver.org/lang/

https://csemver.org/

https://calver.org/

https://lumosql.org/src/not-forking/doc/trunk/README.md

https://0ver.org/
> https://news.ycombinator.com/item?id=28154187

https://alexgaynor.net/2021/oct/07/whats-in-a-version-number/
> https://news.ycombinator.com/item?id=28785147

https://github.com/ptaoussanis/encore/blob/master/BREAK-VERSIONING.md
> https://lobste.rs/s/kg6rov/break_versioning

# CI

https://www.jenkins.io/
https://slack.engineering/how-a-jenkins-job-broke-our-jenkins-ui/
https://itnext.io/git-notes-your-ci-process-46b2fd5ac52
https://axelfontaine.com/blog/final-nail.html

https://tekton.dev/

https://gregoryszorc.com/blog/2021/04/07/modern-ci-is-too-complex-and-misdirected/
> https://news.ycombinator.com/item?id=26727790

https://guix.gnu.org/en/cuirass/

https://neverworkintheory.org/2021/10/18/bad-practices-in-continuous-integration.html

# CD

ArgoCD

https://news.ycombinator.com/item?id=26872904

https://github.com/lesfurets/git-octopus

https://github.com/ovotech/gitoops/blob/main/docs/blog.md

# History
https://gitlab.com/-/snippets/1846041 Blue-Green deployment

# Security

https://github.com/reposaur/reposaur Allows users and organizations to execute policies against GitHub data to generate reports, perform auditing and more

# Incidents
https://news.ycombinator.com/item?id=31769520

https://news.ycombinator.com/item?id=31579862

https://gitlab.com/gitlab-org/cves/-/blob/master/2022/CVE-2022-0477.json

https://www.githubstatus.com/incidents/b40k7ckrs7sp
> https://news.ycombinator.com/item?id=31152403

https://www.bleepingcomputer.com/news/security/github-restores-popular-python-repo-hit-by-bogus-dmca-takedown/

https://www.theregister.com/2022/04/21/github-stolen-oauth-tokens-used-in-breaches/
> https://github.blog/2022-05-26-npm-security-update-oauth-tokens/
> > https://news.ycombinator.com/item?id=31526044
> https://www.theregister.com/2022/05/27/github_publishes_a_post_mortem/

https://www.githubstatus.com/incidents/vxvyrmy9w1vp
> https://news.ycombinator.com/item?id=31023695

https://newsletter.pragmaticengineer.com/p/scoop-atlassian?s=r
> https://news.ycombinator.com/item?id=31015813
> https://www.reddit.com/r/programming/comments/u3ejph/the_scoop_inside_the_longest_atlassian_outage_of/

https://twitter.com/kjartanmuller/status/1513462616030683138 Atlassian: We estimate the rebuilding effort to last for up to 2 more weeks
> https://news.ycombinator.com/item?id=30990697

https://jira-software.status.atlassian.com/
> https://news.ycombinator.com/item?id=30990577
https://news.ycombinator.com/item?id=30986732

https://news.ycombinator.com/item?id=30973808 Atlassian products have been down for 4 days

https://news.ycombinator.com/item?id=30960499 Multiple Atlassian services suffering outages

https://news.ycombinator.com/item?id=30931475 CircleCI Down

https://news.ycombinator.com/item?id=30920046 Confluence, Jira, and other Atlassian products are down

https://about.gitlab.com/blog/2022/03/11/gitlab-actions-to-date-regarding-russian-invasion-of-ukraine/

https://www.githubstatus.com/incidents/sksd097hm0y5 Incident with GitHub Actions, API Requests, Codespaces, Git Operations, Issues, GitHub Packages, GitHub Pages, Pull Requests, and Webhooks
> https://news.ycombinator.com/item?id=30711269

https://www.bleepingcomputer.com/news/technology/github-outage-impacts-actions-codespaces-issues-pull-requests/

https://security.humanativaspa.it/gitlab-ce-cve-2021-22205-in-the-wild/

https://marc.info/?l=git&m=152761328506724&w=2 CVE-2018-11233 Git RCE

https://travis-ci.community/t/security-bulletin/12081
> https://news.ycombinator.com/item?id=28523350

SourceForge nobody Apache HTTPD configuration

# New versions

https://about.gitlab.com/releases/2022/05/22/gitlab-15-0-released/

https://about.gitlab.com/releases/2022/04/22/gitlab-14-10-released/

https://about.gitlab.com/releases/2022/02/22/gitlab-14-8-released/
> https://news.ycombinator.com/item?id=30430227

https://about.gitlab.com/releases/2021/12/22/gitlab-14-6-released/

https://about.gitlab.com/releases/2021/08/22/gitlab-14-2-released/

https://about.gitlab.com/releases/2021/06/22/gitlab-14-0-released/

# News
https://www.amazon.science/blog/calculating-the-differential-cost-of-code-changes

https://www.phoronix.com/scan.php?page=news_item&px=Wine-GitLab-Main-Workflow
> https://news.ycombinator.com/item?id=31737807

https://news.ycombinator.com/item?id=31705099 Ask HN: Would you be interested in POM generator for Selenium?

https://github.com/gabrielsoltz/ess-gitlab Scanner for Gitlab Security Mis-Configurations

https://github.com/google/cadvisor Container Advisor provides container users an understanding of the resource usage and performance characteristics of their running containers

https://taylorbrazelton.com/2022/06/06/2022-06-06-bye-bye-semantic-versioning-say-hello-to-gitdate/
> https://news.ycombinator.com/item?id=31703803

https://news.ycombinator.com/item?id=31696447 Ask HN: How are you dealing with the M1/ARM migration?

https://github.blog/2022-06-09-dependabot-updates-hit-ga-in-ghes/

https://gitlab.com/gitlab-org/gitlab/-/issues/352316 Move required pipeline configuration to Ultimate
> https://news.ycombinator.com/item?id=31657483

https://woodpecker-ci.org/
> https://news.ycombinator.com/item?id=31633339

https://github.com/go-gitea/lgtm
> https://news.ycombinator.com/item?id=31577888

https://news.ycombinator.com/item?id=31580763 Ask HN: If Kubernetes is the solution, why are there so many DevOps jobs?

https://github.com/jmgilman/nixago

https://einride.engineering/blog/its-tech-radar-review-season/

https://dnastacio.medium.com/gitops-repo-content-a31884d4104f
> https://dnastacio.medium.com/why-you-should-avoid-sealed-secrets-in-your-gitops-deployment-e50131d360dd
> > https://external-secrets.io/v0.5.3/
> > https://ismailyenigul.medium.com/take-backup-of-all-sealed-secrets-keys-or-re-encrypt-regularly-297367b3443
> https://ismailyenigul.medium.com/take-backup-of-all-sealed-secrets-keys-or-re-encrypt-regularly-297367b3443 How to Configure GitHub Environments with Terraform?
> https://dnastacio.medium.com/the-gitops-files-ci-cd-bricks-and-blueprints-fcfdb5b3e34d

https://star-history.com/ GitHub Star History Graph
> https://news.ycombinator.com/item?id=31542234

https://netfoundry.io/this-is-the-way-invisible-jenkins/
> https://news.ycombinator.com/item?id=31503429

https://blog.replit.com/nix_dynamic_version

https://anchore.com/sbom/how-to-generate-an-sbom-with-free-open-source-tools/

https://consulting.drmaciver.com/code-review-quick-fixes/
> https://news.ycombinator.com/item?id=31447080

https://security.googleblog.com/2021/06/introducing-slsa-end-to-end-framework.html

https://www.bleepingcomputer.com/news/security/github-can-now-alert-of-supply-chain-bugs-in-new-dependencies/

https://www.theinsaneapp.com/2022/05/gitee.html
> https://www.zhihu.com/question/533388365/answer/2491172345

https://sandervanderburg.blogspot.com/2020/07/on-using-nix-and-docker-as-deployment.html

https://www.heise.de/news/GitLab-macht-Pull-basierte-Kubernetes-Deployments-kostenlos-7098276.html

https://about.gitlab.com/handbook/
> https://news.ycombinator.com/item?id=31270407

https://openfeature.dev/ open standard for feature flags
> https://news.ycombinator.com/item?id=31223429

https://stripe.com/blog/fast-secure-builds-choose-two bazel

https://www.theregister.com/2022/05/05/github_2fa_mandatory_2023/?td=rt-9c

https://blog.yossarian.net/2022/05/09/A-most-vexing-parse-but-for-Python-packaging
> https://news.ycombinator.com/item?id=31314379

https://www.haskellforall.com/2022/05/the-golden-rule-of-software.html
> https://news.ycombinator.com/item?id=31315516

https://christine.website/talks/nixos-pain-2021-11-10
> https://news.ycombinator.com/item?id=31141377

https://v5.chriskrycho.com/journal/semver-for-ts-in-practice/
> https://news.ycombinator.com/item?id=31123315

https://www.uyuni-project.org/ release of SUSE Manager, salt stack

https://news.ycombinator.com/item?id=31108828 Ask HN: How are pull requests integrated in a repo with high commit frequency?

https://github.com/caldito/soup gitOps

https://about.gitlab.com/blog/2022/02/10/how-to-code-build-and-deploy-from-an-ipad-using-gitlab-and-gitpod/

https://www.taiga.io/ Open Source project management tool for multi-functional teams
> https://news.ycombinator.com/item?id=31064126
> https://github.com/kaleidos-ventures MPL-2.0

https://www.bleepingcomputer.com/news/security/github-suspends-accounts-of-russian-devs-at-sanctioned-companies/

https://status.heroku.com/incidents/2413 Heroku Security Notification, GitHub integration mitigation steps
> https://news.ycombinator.com/item?id=31048646

https://github.blog/2022-04-15-security-alert-stolen-oauth-user-tokens/
> https://news.ycombinator.com/item?id=31046791
> https://www.securitynewspaper.com/2022/04/18/github-was-hacked-source-code-is-filtered-from-different-repositories/

https://httpie.io/blog/stardust
> https://news.ycombinator.com/item?id=31033758

https://github.blog/changelog/2022-04-12-organization-discussions/
> https://news.ycombinator.com/item?id=31007694

https://github.com/facebookexperimental/eden scm
> https://news.ycombinator.com/item?id=31006003

https://sourcehut.org/blog/2022-04-08-2021-financial-report/
> https://news.ycombinator.com/item?id=30956872

https://shopify.github.io/shadowenv/
> https://news.ycombinator.com/item?id=30957613

https://turborepo.org/blog/turbo-1-2-0 monorepo
> https://news.ycombinator.com/item?id=30958653

https://jinyuz.dev/posts/tips-and-tricks/Switching-from-pyenv,-rbenv,-goenv-and-nvm-to-asdf
> https://news.ycombinator.com/item?id=30917354

https://bhupesh.me//finding-pull-requests-that-change-a-file-terminal/

https://github.blog/2022-04-05-4-ways-we-use-github-actions-to-build-github/
> https://news.ycombinator.com/item?id=30920543

https://github.com/asdf-vm/asdf Manage multiple runtime versions with a single CLI tool, extendable via plugins

https://www.mikeperham.com/2022/01/17/happy-10th-birthday-sidekiq/
> https://news.ycombinator.com/item?id=30917740

https://docs.dagger.io/1215/what-is-cue/ alpha
> https://github.com/dagger/dagger
> https://github.com/dagger/dagger/discussions/1677
> > https://blog.nestybox.com/2020/10/21/gitlab-dind.html Securing GitLab CI pipelines with Sysbox

https://squeaky.ai/blog/development/why-we-dont-use-a-staging-environment
> https://news.ycombinator.com/item?id=30899362

https://github.com/dlvhdr/gh-dash
> https://news.ycombinator.com/item?id=30881441

https://underjord.io/fundamentals-and-deployment.html

https://go.dev/blog/supply-chain
> https://news.ycombinator.com/item?id=30869261

https://r2devops.io/
> https://news.ycombinator.com/item?id=30853914

https://dagger.io/blog/public-launch-announcement
> https://news.ycombinator.com/item?id=30857012

https://coolify.io/
> https://news.ycombinator.com/item?id=30854912

https://daniel.haxx.se/blog/2022/03/28/what-curl-expects-from-dependencies/

https://github.blog/2022-03-28-how-to-secure-your-end-to-end-supply-chain-on-github/

https://about.gitlab.com/blog/2022/03/24/efficient-free-tier/ Upcoming changes to user limits on Free tier of Gitlab SaaS
> https://news.ycombinator.com/item?id=30791162

https://chaordic.io/blog/reliable_continuous_deployment_in_7_steps/

https://www.githubstatus.com/incidents/tyc8wpsgr2r8
> https://news.ycombinator.com/item?id=30779046
> https://github.blog/2022-03-23-an-update-on-recent-service-disruptions/

https://github.com/eBay/goose Service to simplify adding GitOps functionality to systems

https://github.com/github/feedback/discussions/12341 Pull Request File Tree Feedback
> https://news.ycombinator.com/item?id=30647047

https://fossa.com/blog/three-pillars-reproducible-builds/
> https://news.ycombinator.com/item?id=30604954

https://github.com/jsnjack/wakeci

https://fbinfer.com/
> https://news.ycombinator.com/item?id=30565270

https://core.telegram.org/bots/webhooks

https://www.mihaileric.com/posts/mlops-is-a-mess/
> https://news.ycombinator.com/item?id=30529305

https://github.com/sigoden/argc handy way to handle sh/bash cli parameters
> https://news.ycombinator.com/item?id=30540201

https://endoflife.date/
> https://news.ycombinator.com/item?id=30499023

https://crooked-hideout.blogspot.com/2012/01/ableton-live-set-is-gzipped-xml-ruby.html
> https://rubydoc.info/github/guard/guard/master/frames
> https://news.ycombinator.com/item?id=30485195

https://gitlab.com/gitlab-org/gitlab/-/issues/23166 Can repository mirroring (pulling) be incorporated into Gitlab CE?

https://scaledagiledevops.com/

https://revelry.co/insights/development/nix-time/
> https://news.ycombinator.com/item?id=30384121
> https://www.reddit.com/r/programming/comments/sw2cjd/nix_an_idea_whose_time_has_come/

https://www.aspect.dev/blog/what-is-a-build-system-and-what-is-ci

https://blog.appsignal.com/2022/02/15/delayed-job-vs-sidekiq-which-is-better.html
> https://news.ycombinator.com/item?id=30345806

https://oshea.io/all-posts/work-backwards-from-a-feature-announcement

https://full-stack.blend.com/how-we-write-github-actions-in-go.html
> https://news.ycombinator.com/item?id=30247675

https://www.decadent.org.uk/ben/blog/ci-for-the-debian-kernel-team.html
> https://news.ycombinator.com/item?id=30229192

https://www.enterpriseready.io/podcast/40-alexis-richardson-weaveworks/

https://greenops.io/atlas/
> https://news.ycombinator.com/item?id=30164420

https://www.perfecto.io/blog/devops-testing-strategy

https://news.ycombinator.com/item?id=30163324

https://brooker.co.za/blog/2022/01/31/deployments.html

https://simonwillison.net/2022/Jan/31/release-notes/

https://itnext.io/spice-up-your-infrastructure-as-code-with-tacos-1a9c179e0783
> https://github.com/spacelift-io/spacectl
> https://www.reddit.com/r/Terraform/comments/sgf59w/tacos_providers/

https://thenewstack.io/automated-sbom-generation-with-paketo-buildpacks/

https://github.blog/2022-01-31-dependency-graph-now-supports-github-actions/

https://news.ycombinator.com/item?id=30109187

https://blog.forcesunseen.com/stop-storing-secrets-in-environment-variables
> https://www.reddit.com/r/netsec/comments/sevepr/stop_storing_secrets_in_environment_variables/
> > https://blog.sebastian-daschner.com/entries/changing_env_java

https://news.ycombinator.com/item?id=30114856 Ask HN: Does your team use feature flags?
> https://news.ycombinator.com/item?id=30114856

https://www.actionsbyexample.com/
> https://news.ycombinator.com/item?id=30060765

https://github.com/yuriizinets/gitlab-secrets

https://news.ycombinator.com/item?id=29891656 GitHub no longer supporting unauthenticated `git://`

https://github.com/ankitpokhrel/jira-cli

https://github.com/mattst88/gmail-gitlab-filtering
> https://news.ycombinator.com/item?id=29733120

https://iopscience.iop.org/article/10.3847/1538-3881/ac341b Visibility Predictions for Near-future Satellite Megaconstellations: Latitudes near 50° Will Experience the Worst Light Pollution

https://microtica.com/blog/how-to-use-gitops-on-aws-in-your-organization-a-complete-guide/

https://pre-commit.com/
> https://news.ycombinator.com/item?id=29634897

https://www.pullrequest.com/
> https://news.ycombinator.com/item?id=29623505

https://wolfoliver.medium.com/the-big-devops-misunderstanding-8435a910a5fd
> https://news.ycombinator.com/item?id=29617794

https://github.com/thlorenz/doctoc

https://github.com/dhanvi/direnvp

https://news.ycombinator.com/item?id=29600228 Ask HN: I'm tired of intense code review cycles

https://releasechurch.dev/
> https://news.ycombinator.com/item?id=29604374

https://www.theserverside.com/tip/5-Jenkins-alternatives-for-Java-developers

https://github.com/merico-dev/lake

https://www.devops-research.com/research.html

https://about.gitlab.com/releases/2021/11/22/gitlab-14-5-released/

https://github.blog/2018-10-17-behind-the-scenes-of-github-token-scanning/

https://mattsegal.dev/devops-academic-research.html
> https://news.ycombinator.com/item?id=29294644

https://www.courier.com/blog/routing-and-preferences

https://github.blog/2021-11-18-7-advanced-workflow-automation-features-with-github-actions/
> https://news.ycombinator.com/item?id=29267759

https://www.theregister.com/2021/11/18/firefox_cookies_github/

https://brandur.org/fragments/flags-v-gates
> https://news.ycombinator.com/item?id=29278149

https://github.com/elfshaker/elfshaker low-footprint, high-performance version control system fine-tuned for binaries
> https://news.ycombinator.com/item?id=29276557

https://news.ycombinator.com/item?id=29251343

https://graphite.dev/blog/post/DThX8ffP1gmxWJChEv0y
> https://news.ycombinator.com/item?id=29255195

https://reflect.run/articles/typescript-the-perfect-file-format/
> https://news.ycombinator.com/item?id=29254679

https://utteranc.es/
> https://news.ycombinator.com/item?id=29189923

https://techcrunch.com/2021/11/09/cascade-labs-raises-5-3m-for-its-no-code-data-automation-platform/?guccounter=1&guce_referrer=aHR0cHM6Ly9uZXdzLnljb21iaW5hdG9yLmNvbS8&guce_referrer_sig=AQAAAAHvJx1NbiapkEHEly8lV2GK0W-ZeAlxpnAw7lsn8tbNjvutlEq6EtCvTIQ_yQN0JkDEiBCsKABgS8BIJKVKZl1Jm2fE2qMz__iGqbag1909XoUPaNBhwcw3QxVM5Efo0-utuVH59MBhhZV-MuG1KYCyk6JhTkelAHEIHV8iGI5s

https://trufflesecurity.com/blog/driftwood Driftwood: Know if Private Keys are Sensitive
> https://news.ycombinator.com/item?id=29153995

https://blog.kronis.dev/articles/never-update-anything
> https://news.ycombinator.com/item?id=29106159

https://github.com/GitGuardian/ggshield scan

https://www.sourceware.org/dwz/

https://blog.sonarsource.com/gocd-pre-auth-pipeline-takeover

https://megalinter.github.io/

https://opensource.googleblog.com/2021/10/protect-your-open-source-project-from-supply-chain-attacks.html
> https://news.ycombinator.com/item?id=28931248

https://netflixtechblog.com/safe-updates-of-client-applications-at-netflix-1d01c71a930c

https://blog.argoproj.io/argo-rollouts-v1-1-fef8611a9034

https://www.cobaltrobotics.com/premortems-and-postmortems/
> https://news.ycombinator.com/item?id=28854598

https://github.com/Flagsmith/flagsmith
> https://news.ycombinator.com/item?id=28785788

https://thenewstack.io/sigstore-code-signing-for-software-supply-chain-security/

https://tech.ovoenergy.com/gitoops-attacking-and-defending-ci-cd-pipelines/

https://fr.sonatype.com/resources/state-of-the-software-supply-chain-2021

https://tomhummel.com/posts/ci/cd-quick-reference/

https://csrc.nist.gov/publications/detail/sp/800-204c/draft

https://github.com/run-x/opta/

https://github.com/theonedev/onedev Jetty Shiro Wicket

https://news.ycombinator.com/item?id=28615329 How do you handle CI pipeline in front end-back end monorepo

https://github.com/mattbillenstein/salty

https://cloudogu.com/en/blog/gitops-tools

https://theforeman.org/2021/09/foreman-30-is-here.html
> https://news.ycombinator.com/item?id=28569690

https://gitlab.com/gitlab-org/gitlab/-/issues/335278
> https://news.ycombinator.com/item?id=28535298

https://decisionops.substack.com/p/decisionops
> https://news.ycombinator.com/item?id=28234629

https://blog.cedriccharly.com/post/20210523-how-cue-wins/

https://iximiuz.com/en/posts/devops-sre-and-platform-engineering/
> https://news.ycombinator.com/item?id=28137852

https://five9sclub.substack.com/p/how-to-explain-devops-to-non-tech
> https://news.ycombinator.com/item?id=28059162

https://github.com/MicrosoftEdge/MSEdgeExplainers/blob/main/VersionHistory/explainer.md
> https://news.ycombinator.com/item?id=27971502

https://www.sleuth.io/
> https://news.ycombinator.com/item?id=27974573

https://www.jetbrains.com/lp/devecosystem-2021/
> https://news.ycombinator.com/item?id=27856283

https://bitbucket.org/blog/encountering-some-turbulence-on-bitbuckets-journey-to-a-new-platform
> https://news.ycombinator.com/item?id=27774987

https://about.gitlab.com/blog/2021/06/22/gitlab-14-modern-devops/
> https://news.ycombinator.com/item?id=27714296

https://news.ycombinator.com/item?id=27711403

https://pijul.org/posts/2021-06-28-two-changes/

https://tomtalks.blog/2021/06/microsoft-teams-2-0-will-use-half-the-memory-dropping-electron-for-edge-webview2/

https://about.gitlab.com/blog/2021/05/04/gitlabs-2021-survey-uncovers-a-new-devops-maturity-model/

https://about.gitlab.com/developer-survey/
> https://news.ycombinator.com/item?id=27039376


