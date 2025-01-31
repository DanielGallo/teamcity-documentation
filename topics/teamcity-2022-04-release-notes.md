[//]: # (title: TeamCity 2022.04 Release Notes)
[//]: # (auxiliary-id: TeamCity 2022.04 Release Notes)  

__Build: 108502__  

__28 April 2022__    



### Feature

* **[TW-5610](https://youtrack.jetbrains.com/issue/TW-5610/Custom-build:-allow-to-provide-revisions-for-the-VCS-roots)** — Custom build: allow to provide revisions for the VCS roots
* **[TW-10498](https://youtrack.jetbrains.com/issue/TW-10498/Multiple-equivalent-builds-can-be-present-in-the-queue-on-snapsh)** — Multiple equivalent builds can be present in the queue on snapshot builds triggering (no snapshot chains optimizing int he queue)
* **[TW-22960](https://youtrack.jetbrains.com/issue/TW-22960/Number-of-simultaneously-running-builds-should-have-option-for-b)** — Number of simultaneously running builds should have option for branches
* **[TW-29273](https://youtrack.jetbrains.com/issue/TW-29273/Display-templates-in-breadcrumbs-in-administration-pages-for-fas)** — Display templates in breadcrumbs in administration pages for fast navigation
* **[TW-48863](https://youtrack.jetbrains.com/issue/TW-48863/Publish-commit-status-on-adding-to-queue)** — Publish commit status on adding to queue
* **[TW-52778](https://youtrack.jetbrains.com/issue/TW-52778/Ability-to-migrate-existing-build-artifacts-from-local-storage-t)** — Ability to migrate existing build artifacts from local storage to S3
* **[TW-53412](https://youtrack.jetbrains.com/issue/TW-53412/Batch-operations-with-builds)** — Batch operations with builds
* **[TW-64423](https://youtrack.jetbrains.com/issue/TW-64423/Split-tests-into-groups-and-run-on-multiple-agents-in-parallel)** — Split tests into groups and run on multiple agents in parallel
* **[TW-65906](https://youtrack.jetbrains.com/issue/TW-65906/Implement-Downloaded-and-delivered-artifacts-view-in-the-new-UI)** — Implement Downloaded and delivered artifacts view in the new UI
* **[TW-69740](https://youtrack.jetbrains.com/issue/TW-69740/Changes-page-in-new-UI)** — Changes page in new UI
* **[TW-73204](https://youtrack.jetbrains.com/issue/TW-73204/Support-parallel-tests-in-the-.NET-runner)** — Support parallel tests in the .NET runner
* **[TW-74613](https://youtrack.jetbrains.com/issue/TW-74613/UI:-Add-the-ability-to-get-the-reasons-and-time-to-wait-for-the-)** — UI: Add the ability to get the reasons and time to wait for the queued build.
* **[TW-75042](https://youtrack.jetbrains.com/issue/TW-75042/Add-GitLab-issues-support)** — Add GitLab issues support
* **[TW-75688](https://youtrack.jetbrains.com/issue/TW-75688/Bundle-Qodana-plugin)** — Bundle Qodana plugin
* **[TW-75736](https://youtrack.jetbrains.com/issue/TW-75736/Allow-providing-a-fallback-build-configuration-with-tests-statis)** — Allow providing a fallback build configuration with tests statistics
* **[TW-26623](https://youtrack.jetbrains.com/issue/TW-26623/Approval-for-Run-button-(requiring-sign-off-by-several-users))** — Approval for Run button (requiring sign off by several users)
* **[TW-40404](https://youtrack.jetbrains.com/issue/TW-40404/Use-native-git-for-repository-fetching)** — Use native git for repository fetching
* **[TW-48449](https://youtrack.jetbrains.com/issue/TW-48449/Support-Cloud-profiles-in-Kotlin-DSL-project)** — Support Cloud profiles in Kotlin DSL project
* **[TW-52941](https://youtrack.jetbrains.com/issue/TW-52941/To-add-ability-to-view-public-part-of-the-uploaded-SSH-key)** — To add ability to view public part of the uploaded SSH key
* **[TW-66588](https://youtrack.jetbrains.com/issue/TW-66588/Provide-a-way-to-automatically-choose-some-parent-project-as-sco)** — Provide a way to automatically choose some parent project as scope when assigning an investigation or muting tests
* **[TW-68011](https://youtrack.jetbrains.com/issue/TW-68011/Run-custom-build-dialog:-allow-specifying-an-arbitrary-branch-na)** — Run custom build dialog: allow specifying an arbitrary branch name
* **[TW-70296](https://youtrack.jetbrains.com/issue/TW-70296/Add-support-for-Space-merge-requests-to-Pull-requests-build-feat)** — Add support for Space merge requests to Pull requests build feature
* **[TW-73101](https://youtrack.jetbrains.com/issue/TW-73101/Publish-a-build-status-to-the-Merge-request-in-JetBrains-Space)** — Publish a build status to the Merge request in JetBrains Space
* **[TW-73147](https://youtrack.jetbrains.com/issue/TW-73147/Import-avatars-from-GitHub,-BitBucket-and-other-external-auth-mo)** — Import avatars from GitHub, BitBucket and other external auth modules on user creation
* **[TW-73161](https://youtrack.jetbrains.com/issue/TW-73161/UI-to-manage-agent-pool-projects)** — UI to manage agent pool projects
* **[TW-73266](https://youtrack.jetbrains.com/issue/TW-73266/Support-reporting-of-the-build-status-to-the-review-directly-via)** — Support reporting of the build status to the review directly via build status API of Helix Swarm
* **[TW-73411](https://youtrack.jetbrains.com/issue/TW-73411/Sakura:-allow-to-collapse-expand-all-projects-on-the-project-ove)** — Sakura: allow to collapse/expand all projects on the project overview page
* **[TW-73691](https://youtrack.jetbrains.com/issue/TW-73691/Disallow-adding-more-builds-in-the-build-queue-using-REST-reques)** — Disallow adding more builds in the build queue using REST requests if the build queue is too large
* **[TW-73796](https://youtrack.jetbrains.com/issue/TW-73796/Allow-to-create-a-build-problem-for-every-match-found-with-%22Fail)** — Allow to create a build problem for every match found with "Fail Build on Specific Text" failure condition
* **[TW-73967](https://youtrack.jetbrains.com/issue/TW-73967/Report-the-build-status-in-the-head-commit-of-the-Space-Merge-re)** — Report the build status in the head commit of the Space Merge request
* **[TW-74421](https://youtrack.jetbrains.com/issue/TW-74421/Add-support-(connection-type)-for-public-ECR)** — Add support (connection type) for public ECR
* **[TW-74651](https://youtrack.jetbrains.com/issue/TW-74651/Support-the-Gradle-runner-parallel-tests)** — Support the Gradle runner parallel tests
* **[TW-74653](https://youtrack.jetbrains.com/issue/TW-74653/Support-the-Maven-runner-parallel-tests)** — Support the Maven runner parallel tests


### Usability Problem
* **[TW-75224](https://youtrack.jetbrains.com/issue/TW-75224/The-change-status-preview-on-the-bar-graph-looks-ridiculous-when)** — The change status preview on the bar graph looks ridiculous when the status is the same
* **[TW-29414](https://youtrack.jetbrains.com/issue/TW-29414/Include-name-of-the-deleted-object-into-%22Are-you-sure-you-want-t)** — Include name of the deleted object into "Are you sure you want to delete this project" confirmation
* **[TW-30985](https://youtrack.jetbrains.com/issue/TW-30985/Improve-browser-page-title-to-differentiate-between-build-config)** — Improve browser page title to differentiate between build configurations better
* **[TW-61639](https://youtrack.jetbrains.com/issue/TW-61639/Improve-Build-overview-tabs-placement-on-expanded-build-area)** — Improve Build overview tabs placement on expanded build area
* **[TW-64933](https://youtrack.jetbrains.com/issue/TW-64933/Remember-filter-value-in-sidebar)** — Remember filter value in sidebar
* **[TW-68007](https://youtrack.jetbrains.com/issue/TW-68007/Build-Configuration-Home-Project-Home-links-in-build-configurati)** — Build Configuration Home/ Project Home links in build configuration/project settings are unobvious
* **[TW-68324](https://youtrack.jetbrains.com/issue/TW-68324/Automatically-remove-%22Fixed%22-mark-from-investigation-on-new-fail)** — Automatically remove "Fixed" mark from investigation on new failure
* **[TW-74149](https://youtrack.jetbrains.com/issue/TW-74149/Artifacts-publishing-times-are-wrong-in-the-build-log)** — Artifacts publishing times are wrong in the build log
* **[TW-59414](https://youtrack.jetbrains.com/issue/TW-59414/A-health-report-on-branch-specs-in-VCS-root-overlapping-with-the)** — A health report on branch specs in VCS root overlapping with the ones provided by the Pull Requests build feature is required
* **[TW-59968](https://youtrack.jetbrains.com/issue/TW-59968/No-need-to-change-projects-list-in-sidebar-if-the-search-field-i)** — No need to change projects list in sidebar if the search field is selected and empty. Only after typing the letters
* **[TW-62550](https://youtrack.jetbrains.com/issue/TW-62550/Small-circle-on-the-build-log-timeline-is-not-self-descriptive)** — Small circle on the build log timeline is not self-descriptive
* **[TW-67258](https://youtrack.jetbrains.com/issue/TW-67258/%22No-differences-between-builds-were-found%22-phrase-is-formally-in)** — "No differences between builds were found" phrase is formally incorrect
* **[TW-68156](https://youtrack.jetbrains.com/issue/TW-68156/'Test-connection'-is-not-available-if-project-settings-are-read-)** — 'Test connection' is not available if project settings are read-only
* **[TW-68191](https://youtrack.jetbrains.com/issue/TW-68191/Kotlin-DSL:-several-versions-of-the-same-class-are-available-for)** — Kotlin DSL: several versions of the same class are available for import, one for each version of DSL API
* **[TW-68366](https://youtrack.jetbrains.com/issue/TW-68366/Build-log-search:-Next-result-button-is-disabled-when-the-last-r)** — Build log search: Next result button is disabled when the last result is reached
* **[TW-68390](https://youtrack.jetbrains.com/issue/TW-68390/Build-log-search:-make-Next-button-search-for-new-results-starti)** — Build log search: make Next button search for new results starting from the place user has clicked
* **[TW-69011](https://youtrack.jetbrains.com/issue/TW-69011/UI-to-edit-agent-pools)** — UI to edit agent pools
* **[TW-69949](https://youtrack.jetbrains.com/issue/TW-69949/Show-duration-for-currently-running-stages-on-Build-log)** — Show duration for currently running stages on Build log
* **[TW-72734](https://youtrack.jetbrains.com/issue/TW-72734/Build-log-search:-Don't-enable-Previous-result-button-if-only-on)** — Build log search: Don't enable Previous result button if only one result was found
* **[TW-72783](https://youtrack.jetbrains.com/issue/TW-72783/Not-clear-meaning-of-the-Muted-word-on-the-Tests-tab)** — Not clear meaning of the Muted word on the Tests tab
* **[TW-73548](https://youtrack.jetbrains.com/issue/TW-73548/Information-about-pending-changes-is-shown-in-a-blind-spot)** — Information about pending changes is shown in a blind spot
* **[TW-73849](https://youtrack.jetbrains.com/issue/TW-73849/Not-related-build-log-is-shown-for-expanded-problem-Build-failur)** — Not related build log is shown for expanded problem Build failure on specific text in build log
* **[TW-73875](https://youtrack.jetbrains.com/issue/TW-73875/Assign-agents-projects-dialog-is-reloaded-every-time-when-any-po)** — Assign agents/projects dialog is reloaded every time when any pool is changed.
* **[TW-74056](https://youtrack.jetbrains.com/issue/TW-74056/Impossible-to-navigate-back-from-Server-Health-page)** — Impossible to navigate back from Server Health page
* **[TW-74090](https://youtrack.jetbrains.com/issue/TW-74090/Need-to-make-more-visible-that-there-are-several-builds-behind-t)** — Need to make more visible that there are several builds behind this configuration
* **[TW-74321](https://youtrack.jetbrains.com/issue/TW-74321/Reboot-Agent-action-should-not-reload-the-page)** — Reboot Agent action should not reload the page
* **[TW-74576](https://youtrack.jetbrains.com/issue/TW-74576/Make-the-colors-of-the-modified-files-the-same-as-in-IDEA)** — Make the colors of the modified files the same as in IDEA
* **[TW-74646](https://youtrack.jetbrains.com/issue/TW-74646/Get-rid-of-meaningless-debug-logs-for-shutting-down-S3-clients)** — Get rid of meaningless debug logs for shutting down S3 clients
* **[TW-74688](https://youtrack.jetbrains.com/issue/TW-74688/Rework-%60There-are-no-fully-running-cloud-agents%60-wait-reason-wor)** — Rework `There are no fully-running cloud agents` wait reason wording
* **[TW-74806](https://youtrack.jetbrains.com/issue/TW-74806/Multiline-in-parameters-description-doesn't-work)** — Multiline in parameters description doesn't work
* **[TW-74929](https://youtrack.jetbrains.com/issue/TW-74929/s3-migration-tool.-Rename-%22-cleanup-source%22-option-in-non-Intera)** — s3 migration tool. Rename "--cleanup-source" option in non-Interactive mode.
* **[TW-75795](https://youtrack.jetbrains.com/issue/TW-75795/Show-username-instead-of-VCS-name-in-Slack-notifier)** — Show username instead of VCS name in Slack notifier
* **[TW-75831](https://youtrack.jetbrains.com/issue/TW-75831/Consider-making-%22maximum-running-builds-per-branch%22-field-a-bit-)** — Consider making "maximum running builds per branch" field a bit wider
* **[TW-75863](https://youtrack.jetbrains.com/issue/TW-75863/S3-migration-tool.-Uncomment-required-properties-in-application.)** — S3 migration tool. Uncomment required properties in application.properties.
* **[TW-75878](https://youtrack.jetbrains.com/issue/TW-75878/%22maximum-running-builds-per-branch%22-field-should-not-be-empty-af)** — "maximum running builds per branch" field should not be empty after its data is cleared.
* **[TW-75883](https://youtrack.jetbrains.com/issue/TW-75883/There-is-no-link-to-the-build-in-the-test-tree)** — There is no link to the build in the test tree
* **[TW-75927](https://youtrack.jetbrains.com/issue/TW-75927/Gitlab-issues:-add-a-more-precise-hint-for-distinguishing-GitLab)** — Gitlab issues: add a more precise hint for distinguishing GitLab connections in Project URL


### Bug

* **[TW-42841](https://youtrack.jetbrains.com/issue/TW-42841/Server-can-hang-on-start-(corrupted-HSQLDB-of-builds-metadata-st))** — Server can hang on start (corrupted HSQLDB of builds metadata storage)
* **[TW-73911](https://youtrack.jetbrains.com/issue/TW-73911/Deadlock-on-attempt-to-store-a-new-metadata-storage-key-id)** — Deadlock on attempt to store a new metadata storage key id
* **[TW-75864](https://youtrack.jetbrains.com/issue/TW-75864/jetbrains.exodus.ExodusException-on-trying-to-run-the-same-migra)** — jetbrains.exodus.ExodusException on trying to run the same migration tool using another command line.
* **[TW-31663](https://youtrack.jetbrains.com/issue/TW-31663/Confusing-project-without-parent-on-Overview-and-Configure-visib)** — Confusing project without parent on Overview and Configure visible projects dialog
* **[TW-57117](https://youtrack.jetbrains.com/issue/TW-57117/Git-downgrades-to-protocol-version-1-when-%22git-config-global-pro)** — Git downgrades to protocol version 1 when "git config --global protocol.version 2" is set
* **[TW-58551](https://youtrack.jetbrains.com/issue/TW-58551/Can't-preview-DSL-for-general-build-configuration-settings-witho)** — Can't preview DSL for general build configuration settings without saving configuration
* **[TW-62530](https://youtrack.jetbrains.com/issue/TW-62530/Hide-sidebar-automatically-after-search-was-complete-with-the-se)** — Hide sidebar automatically after search was complete with the selection of the item
* **[TW-63772](https://youtrack.jetbrains.com/issue/TW-63772/FlowID-is-ignored-in-the-new-build-log)** — FlowID is ignored in the new build log
* **[TW-65583](https://youtrack.jetbrains.com/issue/TW-65583/Expanded-artifact-dependency-changes-shows-wrong-data)** — Expanded artifact dependency changes shows wrong data
* **[TW-68545](https://youtrack.jetbrains.com/issue/TW-68545/git-ls-remote-process-hanging-on-Windows-agent)** — git ls-remote process hanging on Windows agent
* **[TW-69922](https://youtrack.jetbrains.com/issue/TW-69922/View-DSL-in-Add-Artifact-Dependency-doesn't-reflect-unsaved-user)** — View DSL in Add Artifact Dependency doesn't reflect unsaved user's changes
* **[TW-71644](https://youtrack.jetbrains.com/issue/TW-71644/GraphQL-API:-support-agent-permissions-within-the-agent-pool)** — GraphQL API: support agent permissions within the agent pool
* **[TW-72760](https://youtrack.jetbrains.com/issue/TW-72760/Password-access-token-is-not-extracted-in-case-when-separate-VCS)** — Password/access token is not extracted in case when separate VCS root is created using the Azure DevOps OAuth connection
* **[TW-72763](https://youtrack.jetbrains.com/issue/TW-72763/Azure-DevOps-OAuth-Connection:-Handle-errors-that-happened-durin)** — Azure DevOps OAuth Connection: Handle errors that happened during project creation
* **[TW-73006](https://youtrack.jetbrains.com/issue/TW-73006/Scrollbars-always-show-on-agents-page-in-new-UI)** — Scrollbars always show on agents page in new UI
* **[TW-73160](https://youtrack.jetbrains.com/issue/TW-73160/Build-can-be-interrupted-by-an-agent-in-multi-node-setup-if-seco)** — Build can be interrupted by an agent in multi node setup if secondary node becomes unavailable for some time
* **[TW-73167](https://youtrack.jetbrains.com/issue/TW-73167/Single-change-page.-No-%22Show-projects-hierarchy%22-option-on-Build)** — Single change page. No "Show projects hierarchy" option on Builds tab
* **[TW-73288](https://youtrack.jetbrains.com/issue/TW-73288/UnPin-clears-existing-tags-on-first-attempt-(Classic-UI))** — UnPin clears existing tags on first attempt (Classic UI)
* **[TW-73363](https://youtrack.jetbrains.com/issue/TW-73363/Add-the-ability-to-get-all-the-VCS-roots-related-to-the-commit)** — Add the ability to get all the VCS roots related to the commit
* **[TW-73473](https://youtrack.jetbrains.com/issue/TW-73473/The-pager-on-the-Build-Changes-tab-disappears-after-switching-be)** — The pager on the Build Changes tab disappears after switching between pages in reverse order
* **[TW-73874](https://youtrack.jetbrains.com/issue/TW-73874/GraphQL-API:-make-ids-globally-unique)** — GraphQL API: make ids globally unique
* **[TW-73912](https://youtrack.jetbrains.com/issue/TW-73912/Absence-of-an-index-on-test_metadata(key_id)-slows-down-startup-)** — Absence of an index on test_metadata(key_id) slows down startup and can cause failure to start if connection timeout is configured
* **[TW-73917](https://youtrack.jetbrains.com/issue/TW-73917/IDEA's-remote-run-fails-to-determine-related-run-configurations)** — IDEA's remote run fails to determine related run configurations
* **[TW-74062](https://youtrack.jetbrains.com/issue/TW-74062/Remote-debug-is-listening-wrong-host-and-doesn't-start-build-on-)** — Remote debug is listening wrong host and doesn't start build on TeamCity server
* **[TW-74111](https://youtrack.jetbrains.com/issue/TW-74111/Fix-nesting-of-publishing-artifacts-messages-(verbose-logging-le))** — Fix nesting of publishing artifacts messages (verbose logging level)
* **[TW-74161](https://youtrack.jetbrains.com/issue/TW-74161/Allow-to-disable-enable-integration-with-Space-merge-requests-wi)** — Allow to disable/enable integration with Space merge requests without restart of server
* **[TW-74181](https://youtrack.jetbrains.com/issue/TW-74181/Concurrent-publishing-of-artifacts-via-service-messages-sometime)** — Concurrent publishing of artifacts via service messages sometimes causes build to fail with FileNotFoundException when there is a large number of artifacts
* **[TW-74284](https://youtrack.jetbrains.com/issue/TW-74284/Endless-agent-upgrades-loop)** — Endless agent upgrades loop
* **[TW-74422](https://youtrack.jetbrains.com/issue/TW-74422/Re-run-ignores-last-chain-structure.)** — Re-run ignores last chain structure.
* **[TW-74430](https://youtrack.jetbrains.com/issue/TW-74430/Build-duration-(secs)-appears-is-wrong-while-build-is-checking-o)** — Build duration (secs) appears is wrong while build is checking out sources
* **[TW-74458](https://youtrack.jetbrains.com/issue/TW-74458/%22preferredInvestigationProject%22-parameter-isn't-taken-into-accou)** — "preferredInvestigationProject" parameter isn't taken into account by "Assign investigation to ..." button
* **[TW-74549](https://youtrack.jetbrains.com/issue/TW-74549/Add-build-number-build-configuration-to-build-status-popup)** — Add build number/build configuration to build status popup
* **[TW-74595](https://youtrack.jetbrains.com/issue/TW-74595/Apply-Ring-UI-like-styles-to-Classic-UI-controls)** — Apply Ring UI-like styles to Classic UI controls
* **[TW-74734](https://youtrack.jetbrains.com/issue/TW-74734/Builds-list-is-not-updated-when-a-build-is-taken-from-the-queue)** — Builds list is not updated when a build is taken from the queue
* **[TW-74745](https://youtrack.jetbrains.com/issue/TW-74745/Build-artifact-directory-can-be-removed-by-clean-up-process-if-t)** — Build artifact directory can be removed by clean-up process if the build configuration name or the project external id was upper(lower)cased
* **[TW-74951](https://youtrack.jetbrains.com/issue/TW-74951/Misplaced-agent-name-in-a-build-line-of-the-deployment-section-())** — Misplaced agent name in a build line of the deployment section (Safari)
* **[TW-75102](https://youtrack.jetbrains.com/issue/TW-75102/SSH-Auth-fail-to-Devops-Server-(Azure-DevOps-or-local-TFS-server))** — SSH Auth fail to Devops Server (Azure DevOps or local TFS server)
* **[TW-75114](https://youtrack.jetbrains.com/issue/TW-75114/Build-does-not-start-because-of-a-missing-condition-type-for-a-f)** — Build does not start because of a missing condition type for a failure condition
* **[TW-75138](https://youtrack.jetbrains.com/issue/TW-75138/Remove-windows-new-lines-from-the-SSH-keys-before-passing-them-t)** — Remove windows new lines from the SSH keys before passing them to Git executable
* **[TW-75285](https://youtrack.jetbrains.com/issue/TW-75285/Empty-auto-generated-virtual-configurations-remain-forever-after)** — Empty auto-generated virtual configurations remain forever after deleting "Run tests in parallel" feature
* **[TW-75322](https://youtrack.jetbrains.com/issue/TW-75322/Parallel-tests:-Add-option-to-preferably-run-tests-from-one-test)** — Parallel tests: Add option to preferably run tests from one test suite on different agents
* **[TW-75572](https://youtrack.jetbrains.com/issue/TW-75572/cleanupPoliciesRest.html:-don't-return-virtual-projects)** — cleanupPoliciesRest.html: don't return virtual projects
* **[TW-75582](https://youtrack.jetbrains.com/issue/TW-75582/Jira-Cloud-OAuth-401)** — Jira Cloud OAuth 401
* **[TW-75612](https://youtrack.jetbrains.com/issue/TW-75612/Main-node-can-fail-to-take-an-exclusive-lock-which-is-required-t)** — Main node can fail to take an exclusive lock which is required to perform upgrade
* **[TW-75634](https://youtrack.jetbrains.com/issue/TW-75634/Exception-occurred-during-finishing-of-the-build-...-java.lang.I)** — Exception occurred during finishing of the build #... java.lang.IllegalArgumentException
* **[TW-75713](https://youtrack.jetbrains.com/issue/TW-75713/Tests-in-new-branches-are-not-parallel,-if-the-configuration-doe)** — Tests in new branches are not parallel, if the configuration does not build default branch
* **[TW-75818](https://youtrack.jetbrains.com/issue/TW-75818/IntelliJ-2022.1-used-as-tool-(for-Inspections-run)-cannot-start)** — IntelliJ 2022.1 used as tool (for Inspections run) cannot start
* **[TW-75832](https://youtrack.jetbrains.com/issue/TW-75832/.NET-test:-only-small-part-of-tests-is-launched-with-specified-%22)** — .NET test: only small part of tests is launched with specified "Test case filter"
* **[TW-75881](https://youtrack.jetbrains.com/issue/TW-75881/TeamCity-server-can't-start-with-%22Failed-to-copy-jdbc-drivers%22-e)** — TeamCity server can't start with "Failed to copy jdbc drivers" error message if JDBC driver file is read only
* **[TW-76046](https://youtrack.jetbrains.com/issue/TW-76046/Gradle-breaks-with-gradleBuildProblem-service-message)** — Gradle breaks with gradleBuildProblem service message
* **[TW-52638](https://youtrack.jetbrains.com/issue/TW-52638/Manual-build-Promote-action-promotes-the-build-to-all-artifact-d)** — Manual build Promote action promotes the build to all artifact dependencies in dependent build
* **[TW-57482](https://youtrack.jetbrains.com/issue/TW-57482/TeamCity-Service-Message-Build-Problem-&-Block-Messages-Issue)** — TeamCity Service Message - Build Problem & Block Messages Issue
* **[TW-58149](https://youtrack.jetbrains.com/issue/TW-58149/Java-API:-Composite-queued-build-returns-agents-for-getCanRunOnA)** — Java API: Composite queued build returns agents for getCanRunOnAgents call
* **[TW-62096](https://youtrack.jetbrains.com/issue/TW-62096/Incorrect-number-of-files-in-new-changes-popup-for-artifact-depe)** — Incorrect number of files in new changes popup for artifact dependency.
* **[TW-62349](https://youtrack.jetbrains.com/issue/TW-62349/Some-TeamCity-service-messages-are-interrupted-in-stdOut-by-newl)** — Some TeamCity service messages are interrupted in stdOut by newline symbol in the case of .net core tests
* **[TW-63121](https://youtrack.jetbrains.com/issue/TW-63121/Max-Agents-parameter-is-not-displayed-in-the-agents-pool-page)** — Max Agents parameter is not displayed in the agents pool page
* **[TW-65686](https://youtrack.jetbrains.com/issue/TW-65686/javax.el.ELException:-Cannot-read-property:-versionedSettingsRoo)** — javax.el.ELException: Cannot read property: versionedSettingsRootUsages when trying to edit a VCS Root
* **[TW-66332](https://youtrack.jetbrains.com/issue/TW-66332/Rendering-SGR-parameters-in-ANSI-sequences-in-build-log-in-new-U)** — Rendering SGR parameters in ANSI sequences in build log in new UI
* **[TW-67865](https://youtrack.jetbrains.com/issue/TW-67865/StaticUIExtensions:-content-configured-to-be-shown-in-ALL_PAGES_)** — StaticUIExtensions: content configured to be shown in ALL_PAGES_HEADER also appears on the AGENT_SUMMARY tabs in Sakura UI
* **[TW-68851](https://youtrack.jetbrains.com/issue/TW-68851/%22Failed-to-process-'buckets'-request:-Connection-to-%22s3.amazonaw)** — "Failed to process 'buckets' request: Connection to "s3.amazonaws.com" is prohibited by TeamCity node restrictions" on the secondary node
* **[TW-69555](https://youtrack.jetbrains.com/issue/TW-69555/Links-to-correct-Team-Foundation-Work-Items-return-404-error)** — Links to correct Team Foundation Work Items return 404 error
* **[TW-70151](https://youtrack.jetbrains.com/issue/TW-70151/The-option-%22Show-all-personal-builds%22-does-not-affect-the-result)** — The option "Show all personal builds" does not affect the result of the test runs list request
* **[TW-70200](https://youtrack.jetbrains.com/issue/TW-70200/Per-usage-license:-secondary-node-reports-%22Failed-to-send-server)** — Per-usage license: secondary node reports "Failed to send server usage data"
* **[TW-71108](https://youtrack.jetbrains.com/issue/TW-71108/IDEA-runner-failes-to-build-project-with-languageLevel-more-than)** — IDEA runner failes to build project with languageLevel more than JDK 11
* **[TW-71862](https://youtrack.jetbrains.com/issue/TW-71862/Display-the-number-of-projects-that-cannot-be-seen-by-user-due-t)** — Display the number of projects that cannot be seen by user due to lack of permissions on GraphQL agent pool projects tab.
* **[TW-71874](https://youtrack.jetbrains.com/issue/TW-71874/Renaming-moving-archiving-of-projects-should-be-reflected-in-Gra)** — Renaming/moving/archiving of projects should be reflected in GraphQL agent pool projects tab
* **[TW-71927](https://youtrack.jetbrains.com/issue/TW-71927/fix-%22-Please-do-not-use-ActionPlaces.UNKNOWN-or-the-empty-place%22)** — fix " Please do not use ActionPlaces.UNKNOWN or the empty place"
* **[TW-72411](https://youtrack.jetbrains.com/issue/TW-72411/Changes-tab:-only-users-from-the-first-page-are-shown-in-the-fil)** — Changes tab: only users from the first page are shown in the filter by users
* **[TW-72526](https://youtrack.jetbrains.com/issue/TW-72526/Agents-pools.-Provide-correct-tooltip-on-assigned-projects-tab.)** — Agents pools. Provide correct tooltip on assigned projects tab.
* **[TW-72565](https://youtrack.jetbrains.com/issue/TW-72565/Add-a-note-about-the-usage-of-permissions-in-information-about-c)** — Add a note about the usage of permissions in information about connections
* **[TW-72569](https://youtrack.jetbrains.com/issue/TW-72569/Docker-Free-Disk-Space-integration-should-auto-detect-the-locati)** — Docker Free Disk Space integration should auto-detect the location of images/containers for the docker when cleaning docker images
* **[TW-72581](https://youtrack.jetbrains.com/issue/TW-72581/Docker-Wrapper-doesn't-escape-ampersand-when-passing-environment)** — Docker Wrapper doesn't escape ampersand when passing environment variables into containers
* **[TW-72705](https://youtrack.jetbrains.com/issue/TW-72705/Default-branch-build-with-checkout-rules-specified-isn't-reused-)** — Default branch build with checkout rules specified isn't reused in non-default branch build chain
* **[TW-72775](https://youtrack.jetbrains.com/issue/TW-72775/Remove-unnecessary-scroll-in-Test-Mute-popup.)** — Remove unnecessary scroll in Test Mute popup.
* **[TW-72876](https://youtrack.jetbrains.com/issue/TW-72876/Do-not-display-Perforce-personal-build-section-in-Custom-Run-dia)** — Do not display Perforce personal build section in Custom Run dialog for user without "Change build source code with a custom patch" permission.
* **[TW-72927](https://youtrack.jetbrains.com/issue/TW-72927/Files-with-special-Perforce-characters-in-names-are-displayed-an)** — Files with special Perforce characters in names are displayed and applied incorrectly in perforce patch
* **[TW-72942](https://youtrack.jetbrains.com/issue/TW-72942/Add-%22Build-log%22-Icon-to-%22Show-full-log%22-button)** — Add "Build log" Icon to "Show full log" button
* **[TW-72962](https://youtrack.jetbrains.com/issue/TW-72962/Deadlock-found-when-trying-to-get-lock-(FailedTestsStorageImpl.m))** — Deadlock found when trying to get lock (FailedTestsStorageImpl.markTestFailed)
* **[TW-72990](https://youtrack.jetbrains.com/issue/TW-72990/Build-Page:-Titles-Should-be-Bigger)** — Build Page: Titles Should be Bigger
* **[TW-73012](https://youtrack.jetbrains.com/issue/TW-73012/TeamCity-retries-the-deletion-requests-5-times-regardless-of-the)** — TeamCity retries the deletion requests 5 times regardless of the numberOfRetries value from internal.properties file
* **[TW-73103](https://youtrack.jetbrains.com/issue/TW-73103/A-few-JetBrains-Space-merge-requests-from-one-branch-are-display)** — A few JetBrains Space merge requests from one branch are displayed in the information about Pull Request
* **[TW-73138](https://youtrack.jetbrains.com/issue/TW-73138/Agents-parameters-subtabs-links-leads-to-old-UI)** — Agents parameters subtabs links leads to old UI
* **[TW-73140](https://youtrack.jetbrains.com/issue/TW-73140/Sakura-Change-page:-links-to-issues-are-not-shown-as-links)** — Sakura Change page: links to issues are not shown as links
* **[TW-73211](https://youtrack.jetbrains.com/issue/TW-73211/Missing-DSL-for-some-parameters-in-.Net-runner)** — Missing DSL for some parameters in .Net runner
* **[TW-73213](https://youtrack.jetbrains.com/issue/TW-73213/Missing-DSL-for-some-parameters-in-Docker-runner)** — Missing DSL for some parameters in Docker runner
* **[TW-73215](https://youtrack.jetbrains.com/issue/TW-73215/Missing-DSL-for-Distinguish-fields-parameter-in-Duplicates-finde)** — Missing DSL for Distinguish fields parameter in Duplicates finder (Java) runner
* **[TW-73217](https://youtrack.jetbrains.com/issue/TW-73217/Missing-DSL-for-coverage-parameters-in-IntelliJ-IDEA-Project-run)** — Missing DSL for coverage parameters in IntelliJ IDEA Project runner
* **[TW-73218](https://youtrack.jetbrains.com/issue/TW-73218/Missing-DSL-for-Script-Argument-parameter-in-PowerShell-runner)** — Missing DSL for Script Argument parameter in PowerShell runner
* **[TW-73244](https://youtrack.jetbrains.com/issue/TW-73244/No-way-to-view-Common-Failure-Conditions-as-code-without-saving-)** — No way to view Common Failure Conditions as code without saving it
* **[TW-73390](https://youtrack.jetbrains.com/issue/TW-73390/Align-and-rename-%22Remote-run%22-label-for-a-single-personal-change)** — Align and rename "Remote run" label for a single personal change
* **[TW-73455](https://youtrack.jetbrains.com/issue/TW-73455/Repository-names-with-Unicode-symbols-are-displayed-incorrectly-)** — Repository names with Unicode symbols are displayed incorrectly in the project creation dialog
* **[TW-73534](https://youtrack.jetbrains.com/issue/TW-73534/Hide-%22New-configuration...-New-subprojects...%22-under-%22Edit-proje)** — Hide "New configuration... / New subprojects..." under "Edit project..." dropdown
* **[TW-73610](https://youtrack.jetbrains.com/issue/TW-73610/Consider-placing-%22Copy-to-clipboard%22-link-at-the-bottom-of-the-s)** — Consider placing "Copy to clipboard" link at the bottom of the stacktrace
* **[TW-73619](https://youtrack.jetbrains.com/issue/TW-73619/The-%22Highlight-my-changes-and-investigations%22-setting-does-not-w)** — The "Highlight my changes and investigations" setting does not work in terms of highlighting my investigations
* **[TW-73621](https://youtrack.jetbrains.com/issue/TW-73621/reverse.dep.-parameters-are-not-applied-to-dependencies-if-setti)** — reverse.dep. parameters are not applied to dependencies if settings are loaded from a branch
* **[TW-73667](https://youtrack.jetbrains.com/issue/TW-73667/Incorrect-rendering-of-a-combination-of-emoji-and-space-in-autog)** — Incorrect rendering of a combination of emoji and space in autogenerated avatars
* **[TW-73738](https://youtrack.jetbrains.com/issue/TW-73738/Single-change-page:-%22No-failed-tests%22-message-is-not-displayed-i)** — Single change page: "No failed tests" message is not displayed if build reported problems
* **[TW-73766](https://youtrack.jetbrains.com/issue/TW-73766/Provide-the-limit-for-number-of-symbols-in-Agent-Pool-name-in-Ex)** — Provide the limit for number of symbols in Agent Pool name in Experimental UI.
* **[TW-73772](https://youtrack.jetbrains.com/issue/TW-73772/Favorite-builds-are-sometimes-not-returned-even-though-they-are-)** — Favorite builds are sometimes not returned even though they are inside lookupLimit
* **[TW-73773](https://youtrack.jetbrains.com/issue/TW-73773/Linux-TeamCity-agent-running-under-WSL-on-windows-detects-.NET-S)** — Linux TeamCity agent running under WSL on windows detects .NET SDKs and runtimes installed on the windows host
* **[TW-73805](https://youtrack.jetbrains.com/issue/TW-73805/Warning-%22Upload-artifact-failed-with-error%22-in-build-log-even-if)** — Warning "Upload artifact failed with error" in build log even if artifacts were uploaded (the case when CloudFront distribution is in deploying state)
* **[TW-73871](https://youtrack.jetbrains.com/issue/TW-73871/Pull-Requests-in-Overview-aren't-ordered)** — Pull Requests in Overview aren't ordered
* **[TW-73939](https://youtrack.jetbrains.com/issue/TW-73939/Agent-pools.-Images-wihout-running-instances-should-be-displayed)** — Agent pools. Images wihout running instances should be displayed on Agent Pool page in Experimental UI.
* **[TW-73965](https://youtrack.jetbrains.com/issue/TW-73965/TeamCity-unexpectedly-closes-the-test-with-suite,-so-test-names-)** — TeamCity unexpectedly closes the test with suite, so test names loose suite names
* **[TW-73973](https://youtrack.jetbrains.com/issue/TW-73973/GraphQL-API:-add-the-%60excludedCount%60-prop-to-the-%60AgentPoolProje)** — GraphQL API: add the `excludedCount` prop to the `AgentPoolProjectsConnection` type
* **[TW-73984](https://youtrack.jetbrains.com/issue/TW-73984/Agent-pool-projects-page:-it-should-not-be-possible-to-remove-a-)** — Agent pool projects page: it should not be possible to remove a project, assigned only with the default pool, and the project pool, from the default pool
* **[TW-73989](https://youtrack.jetbrains.com/issue/TW-73989/Update-sbt-launcher-to-1.5.5)** — Update sbt launcher to 1.5.5
* **[TW-74040](https://youtrack.jetbrains.com/issue/TW-74040/Investigations-auto-assigner-should-not-automatically-assign-inv)** — Investigations auto assigner should not automatically assign investigations on setUp/tearDown methods
* **[TW-74088](https://youtrack.jetbrains.com/issue/TW-74088/Build-may-be-cancelled-when-the-server-is-temporary-unavailable)** — Build may be cancelled when the server is temporary unavailable
* **[TW-74089](https://youtrack.jetbrains.com/issue/TW-74089/Build-may-not-start-for-a-long-period-of-time-with-reason-%22Waiti)** — Build may not start for a long period of time with reason "Waiting for the build settings finalization in other queued builds"
* **[TW-74120](https://youtrack.jetbrains.com/issue/TW-74120/Java-code-duplicates-runner-fails-on-some-versions-of-JDK)** — Java code duplicates runner fails on some versions of JDK
* **[TW-74138](https://youtrack.jetbrains.com/issue/TW-74138/Warning-about-unset-parameter-%22teamcity.agent.hostname%22)** — Warning about unset parameter "teamcity.agent.hostname"
* **[TW-74251](https://youtrack.jetbrains.com/issue/TW-74251/More-visible-icon-for-assigned-investigation-(build-page))** — More visible icon for assigned investigation (build page)
* **[TW-74253](https://youtrack.jetbrains.com/issue/TW-74253/Agent-pool-agents-tab:-remove-redundant-headers)** — Agent pool agents tab: remove redundant headers
* **[TW-74289](https://youtrack.jetbrains.com/issue/TW-74289/Canceled-build-status-is-not-published-to-Space-Merge-Request)** — Canceled build status is not published to Space Merge Request
* **[TW-74359](https://youtrack.jetbrains.com/issue/TW-74359/[S3-Storage]-Artifact-publishing-becomes-interrupted-when-build-)** — [S3 Storage] Artifact publishing becomes interrupted when build has stopped regardless of the option to always publish artifact
* **[TW-74366](https://youtrack.jetbrains.com/issue/TW-74366/Class-is-not-shown-for-xunit-tests-with-DisplayName)** — Class is not shown for xunit tests with DisplayName
* **[TW-74372](https://youtrack.jetbrains.com/issue/TW-74372/Links-to-the-Tabs-for-the-Expanded-Build-UI)** — Links to the Tabs for the Expanded Build UI
* **[TW-74391](https://youtrack.jetbrains.com/issue/TW-74391/Increase-Block-Headers-on-the-Build-Page)** — Increase Block Headers on the Build Page
* **[TW-74423](https://youtrack.jetbrains.com/issue/TW-74423/SecurityException-on-a-secondary-(read-only)-node-(update-failed))** — SecurityException on a secondary (read-only) node (update failed_tests table)
* **[TW-74427](https://youtrack.jetbrains.com/issue/TW-74427/Secure-FTP-uploads-fail-when-using-the-FTP-Upload-build-runner)** — Secure FTP uploads fail when using the FTP Upload build runner
* **[TW-74454](https://youtrack.jetbrains.com/issue/TW-74454/Artifacts-upload:-retry-OPTIONS-requests)** — Artifacts upload: retry OPTIONS requests
* **[TW-74467](https://youtrack.jetbrains.com/issue/TW-74467/Health-items-are-not-updated-when-a-user-navigates-through-Sakur)** — Health items are not updated when a user navigates through Sakura UI
* **[TW-74468](https://youtrack.jetbrains.com/issue/TW-74468/Unable-to-upload-a-new-Tool-version-on-a-secondary-node)** — Unable to upload a new Tool version on a secondary node
* **[TW-74488](https://youtrack.jetbrains.com/issue/TW-74488/Misaligned-quick-links-on-build-expanded-view)** — Misaligned quick links on build expanded view
* **[TW-74501](https://youtrack.jetbrains.com/issue/TW-74501/Background-is-not-uniform-for-expanded-build-in-queue)** — Background is not uniform for expanded build in queue
* **[TW-74503](https://youtrack.jetbrains.com/issue/TW-74503/failed-to-get-project-vcs-roots-via-API-when-another-project-wit)** — failed to get project vcs-roots via API when another project with no access has vcs root with same name
* **[TW-74509](https://youtrack.jetbrains.com/issue/TW-74509/Don't-collapse-build-problem-section-on-cmd-+-click)** — Don't collapse build problem section on cmd + click
* **[TW-74512](https://youtrack.jetbrains.com/issue/TW-74512/%22preferredInvestigationProject%22-parameter-isn't-taken-into-accou)** — "preferredInvestigationProject" parameter isn't taken into account by the investigation auto-assignee build feature
* **[TW-74513](https://youtrack.jetbrains.com/issue/TW-74513/An-avatar-doesn't-fit-in-expanded-build-line)** — An avatar doesn't fit in expanded build line
* **[TW-74522](https://youtrack.jetbrains.com/issue/TW-74522/Pull-request-build-feature-may-fail-to-provide-relevant-branches)** — Pull request build feature may fail to provide relevant branches in a build configuration if it is misconfigured in another build configuration that uses the same VCS root
* **[TW-74542](https://youtrack.jetbrains.com/issue/TW-74542/Bad-browser-tab-title-on-Single-Change-page,-if-change-does-not-)** — Bad browser tab title on Single Change page, if change does not exist
* **[TW-74575](https://youtrack.jetbrains.com/issue/TW-74575/K8s-plugin:-PVC-created-together-with-Pod-(Custom-Pod-Template)-)** — K8s plugin: PVC created together with Pod (Custom Pod Template) might be orphaned if Pod failed to create
* **[TW-74580](https://youtrack.jetbrains.com/issue/TW-74580/Make-sure-SSH-DSA-keys-are-supported-if-native-Git-support-is-en)** — Make sure SSH DSA keys are supported if native Git support is enabled on the server
* **[TW-74601](https://youtrack.jetbrains.com/issue/TW-74601/Parameter-vcsRoot.id.p4client-has-a-different-case-compared-with)** — Parameter vcsRoot.id.p4client has a different case compared with other parameters
* **[TW-74614](https://youtrack.jetbrains.com/issue/TW-74614/AssertionError-in-HierarchyMessagesProcessor.process(HierarchyMe))** — AssertionError in HierarchyMessagesProcessor.process(HierarchyMessagesProcessor.java:70)
* **[TW-74629](https://youtrack.jetbrains.com/issue/TW-74629/Not-all-of-the-parameters-of-a-composite-build-are-shown-on-the-)** — Not all of the parameters of a composite build are shown on the build parameters tab
* **[TW-74645](https://youtrack.jetbrains.com/issue/TW-74645/Build-details-dropdown-always-has-horizontal-scrollbar)** — Build details dropdown always has horizontal scrollbar
* **[TW-74666](https://youtrack.jetbrains.com/issue/TW-74666/Build-cannot-stop-probably-because-it-is-routed-to-incorrect-nod)** — Build cannot stop probably because it is routed to incorrect node with id MAIN_SERVER instead of actual id of the main node
* **[TW-74692](https://youtrack.jetbrains.com/issue/TW-74692/Agent-hostnames-are-incorrect)** — Agent hostnames are incorrect
* **[TW-74694](https://youtrack.jetbrains.com/issue/TW-74694/ConcurrentModificationException-in-UserInvestigationsCounterProv)** — ConcurrentModificationException in UserInvestigationsCounterProvider on server start
* **[TW-74695](https://youtrack.jetbrains.com/issue/TW-74695/Artifacts-published-in-folders-or-archives-are-not-displayed-in-)** — Artifacts published in folders or archives are not displayed in statistics in the verbose build log
* **[TW-74748](https://youtrack.jetbrains.com/issue/TW-74748/No-build-status-popup-on-re-run-action)** — No build status popup on re-run action
* **[TW-74750](https://youtrack.jetbrains.com/issue/TW-74750/PerfMon-data-for-running-builds-is-not-available-on-nodes-which-)** — PerfMon data for running builds is not available on nodes which are not responsible for the current build
* **[TW-74794](https://youtrack.jetbrains.com/issue/TW-74794/Schedule-trigger-may-trigger-a-build-twice)** — Schedule trigger may trigger a build twice
* **[TW-74797](https://youtrack.jetbrains.com/issue/TW-74797/Build-may-fail-to-upload-artifacts-in-multi-node-setup)** — Build may fail to upload artifacts in multi-node setup
* **[TW-74814](https://youtrack.jetbrains.com/issue/TW-74814/Build-steps-names-collision-causes-incomplete-list-of-build-step)** — Build steps names collision causes incomplete list of build steps to be displayed
* **[TW-74875](https://youtrack.jetbrains.com/issue/TW-74875/Compare-Builds-has-a-Mammoth-icon-which-leads-to-the-overview.ht)** — Compare Builds has a Mammoth icon which leads to the /overview.html
* **[TW-74985](https://youtrack.jetbrains.com/issue/TW-74985/it's-not-possible-to-configure-using-path-style-URL-access-to-s3)** — it's not possible to configure using path-style URL access to s3 bucket
* **[TW-74997](https://youtrack.jetbrains.com/issue/TW-74997/Artifacts-publishing-has-been-interrupted)** — Artifacts publishing has been interrupted
* **[TW-75028](https://youtrack.jetbrains.com/issue/TW-75028/Build-restored-in-the-queue-by-a-secondary-node-may-not-have-all)** — Build restored in the queue by a secondary node may not have all of the dependencies
* **[TW-75073](https://youtrack.jetbrains.com/issue/TW-75073/Not-all-of-the-dependencies-settings-are-copied-from-the-origina)** — Not all of the dependencies settings are copied from the original build to a new one in case of re-run action
* **[TW-75133](https://youtrack.jetbrains.com/issue/TW-75133/Auto-update-Fails-with-%22Failed-to-prepare-for-update:-failed-to-)** — Auto update Fails with "Failed to prepare for update: failed to download TeamCity distribution"
* **[TW-75141](https://youtrack.jetbrains.com/issue/TW-75141/Magic-keywords-do-not-work-for-ElasticSearch)** — Magic keywords do not work for ElasticSearch
* **[TW-75163](https://youtrack.jetbrains.com/issue/TW-75163/Cloud-Profiles-DSL-patches-might-not-apply-after-updating-to-typ)** — Cloud Profiles DSL patches might not apply after updating to typed DSL
* **[TW-75184](https://youtrack.jetbrains.com/issue/TW-75184/Do-not-show-batch-operations-checkboxes-actions-without-sufficie)** — Do not show batch operations checkboxes/actions without sufficient permissions on read-only secondary nodes
* **[TW-75198](https://youtrack.jetbrains.com/issue/TW-75198/TeamCity-does-not-remove-cleaned-up-builds-from-the-build_projec)** — TeamCity does not remove cleaned up builds from the build_project table
* **[TW-75256](https://youtrack.jetbrains.com/issue/TW-75256/Continuous-increasing-duration-for-the-some-nested-blocks-in-bui)** — Continuous increasing duration for the some nested blocks in build log
* **[TW-75280](https://youtrack.jetbrains.com/issue/TW-75280/Parallel-tests-may-be-useless-for-new-pull-requests-to-non-defau)** — Parallel tests may be useless for new pull requests to non-default branch
* **[TW-75286](https://youtrack.jetbrains.com/issue/TW-75286/Max-running-builds-limitation-for-a-composite-build-should-not-p)** — Max running builds limitation for a composite build should not prevent start of dependencies if they are reachable from other composite builds without this limitation
* **[TW-75298](https://youtrack.jetbrains.com/issue/TW-75298/Helix-Swarm-queued-status-published-to-the-latest-commit,-if-som)** — Helix Swarm queued status published to the latest commit, if some earlier commit was selected for the build
* **[TW-75307](https://youtrack.jetbrains.com/issue/TW-75307/Rerun-of-a-build-by-unexpected-finish-does-not-handle-intersecti)** — Rerun of a build by unexpected finish does not handle intersecting build chains
* **[TW-75318](https://youtrack.jetbrains.com/issue/TW-75318/NullPointerException-when-running-the-restore-process-via-UI)** — NullPointerException when running the restore process via UI
* **[TW-75335](https://youtrack.jetbrains.com/issue/TW-75335/Project-configuration-is-not-selected-in-the-sidebar,-if-project)** — Project/configuration is not selected in the sidebar, if projects are filtered by search/jump to
* **[TW-75341](https://youtrack.jetbrains.com/issue/TW-75341/When-agent-is-upgrading,-error-response-on-%60-update-teamcity-age)** — When agent is upgrading, error response on `/update/teamcity-agent.xml` makes it start without plugins
* **[TW-75342](https://youtrack.jetbrains.com/issue/TW-75342/DiskUsageController-should-not-allow-using-GET-method-to-trigger)** — DiskUsageController should not allow using GET method to trigger refreshing disk usage statistics
* **[TW-75343](https://youtrack.jetbrains.com/issue/TW-75343/PullRequestRefreshController-should-check-the-HTTP-POST-method-f)** — PullRequestRefreshController should check the HTTP POST method for invocation
* **[TW-75347](https://youtrack.jetbrains.com/issue/TW-75347/Attempt-to-re-run-a-build-which-was-executed-on-a-change-not-ass)** — Attempt to re-run a build which was executed on a change not associated with a build configuration picks up fresh revisions
* **[TW-75381](https://youtrack.jetbrains.com/issue/TW-75381/Build-duration-for-expanded-block-can-increase-endlessly-in-Saku)** — Build duration for expanded block can increase endlessly in Sakura
* **[TW-75422](https://youtrack.jetbrains.com/issue/TW-75422/Different-%22Test-connection%22-behaviour-on-different-pages-for-the)** — Different "Test connection" behaviour on different pages for the same VCS root
* **[TW-75435](https://youtrack.jetbrains.com/issue/TW-75435/Dependencies-timeline-text-distorted-in-Firefox)** — Dependencies timeline text distorted in Firefox
* **[TW-75467](https://youtrack.jetbrains.com/issue/TW-75467/EC2-cloud-profile:-cannot-use-multiple-images-from-the-same-Laun)** — EC2 cloud profile: cannot use multiple images from the same LaunchTemplate
* **[TW-75484](https://youtrack.jetbrains.com/issue/TW-75484/Parallel-tests:-splitted-builds-with-compilation-errors-are-not-)** — Parallel tests: splitted builds with compilation errors are not skipped when looking for a split base
* **[TW-75498](https://youtrack.jetbrains.com/issue/TW-75498/NPE-in-BuildProblemInvestigationsAndMutesListener)** — NPE in BuildProblemInvestigationsAndMutesListener
* **[TW-75544](https://youtrack.jetbrains.com/issue/TW-75544/Commit-status-publisher-sends-Pending-status-to-Azure-DevOps-whe)** — Commit status publisher sends Pending status to Azure DevOps when build is cancelled
* **[TW-75550](https://youtrack.jetbrains.com/issue/TW-75550/Wrong-delayedByBuild-is-returned-in-some-cases)** — Wrong delayedByBuild is returned in some cases
* **[TW-75562](https://youtrack.jetbrains.com/issue/TW-75562/An-error-message-appears-on-creating-a-new-user-account)** — An error message appears on creating a new user account
* **[TW-75574](https://youtrack.jetbrains.com/issue/TW-75574/RejectedExecutionException-in-NotificationProcessor.executeEvent)** — RejectedExecutionException in NotificationProcessor.executeEventNotification
* **[TW-75583](https://youtrack.jetbrains.com/issue/TW-75583/Investigations-auto-assigner-should-not-assign-an-investigation-)** — Investigations auto assigner should not assign an investigation in an auto generated project
* **[TW-75602](https://youtrack.jetbrains.com/issue/TW-75602/java.lang.UnsupportedOperationException:-Build-has-not-been-popu)** — java.lang.UnsupportedOperationException: Build has not been populated: LightweightTestRunImpl
* **[TW-75623](https://youtrack.jetbrains.com/issue/TW-75623/Rename-%22PublicAMI%22-to-%22AMI%22-in-CloudProfile's-DSL)** — Rename "PublicAMI" to "AMI" in CloudProfile's DSL
* **[TW-75652](https://youtrack.jetbrains.com/issue/TW-75652/Can't-view-DSL-for-Version-control-settings-page-without-saving)** — Can't view DSL for Version control settings page without saving
* **[TW-75655](https://youtrack.jetbrains.com/issue/TW-75655/JsonSyntaxException-when-cleaning-up-.artifacts_cache)** — JsonSyntaxException when cleaning up .artifacts_cache
* **[TW-75656](https://youtrack.jetbrains.com/issue/TW-75656/TimeoutException-in-Slack-notifier-jbSlackNotifier-autocompleteU)** — TimeoutException in Slack notifier /jbSlackNotifier/autocompleteUserId.html
* **[TW-75812](https://youtrack.jetbrains.com/issue/TW-75812/Parallel-tests:-dependency-block-doesn't-refresh-when-build-fini)** — Parallel tests: dependency block doesn't refresh when build finishes
* **[TW-75819](https://youtrack.jetbrains.com/issue/TW-75819/Builds-limit-per-branch-does-not-support-round-brackets-in-branc)** — Builds limit per branch does not support round brackets in branch names and escaping
* **[TW-75866](https://youtrack.jetbrains.com/issue/TW-75866/s3-migration-tool.-Correct-displayed-name-for-revert-migration-b)** — s3 migration tool. Correct displayed name for revert migration build step.
* **[TW-75908](https://youtrack.jetbrains.com/issue/TW-75908/Builds-are-not-triggered-due-to-%22Some-repository-state-updated-d)** — Builds are not triggered due to "Some repository state updated during the trigger execution, skip triggering till next time" message
* **[TW-75925](https://youtrack.jetbrains.com/issue/TW-75925/NullPointerException-on-attempt-to-open-a-custom-build-dialog)** — NullPointerException on attempt to open a custom build dialog
* **[TW-75935](https://youtrack.jetbrains.com/issue/TW-75935/java.lang.ClassCastException:-class-jetbrains.buildServer.server)** — java.lang.ClassCastException: class jetbrains.buildServer.serverSide.impl.QueuedBuildImpl$1 cannot be cast to class jetbrains.buildServer.serverSide.BuildTypeEx
* **[TW-75963](https://youtrack.jetbrains.com/issue/TW-75963/java.lang.NoClassDefFoundError-in-github-webhooks-plugin-after-i)** — java.lang.NoClassDefFoundError in github webhooks plugin after installing the latest version
* **[TW-75992](https://youtrack.jetbrains.com/issue/TW-75992/Do-not-show-enable-disable-git-native-button-on-a-read-only-node)** — Do not show enable/disable git native button on a read-only node
* **[TW-76000](https://youtrack.jetbrains.com/issue/TW-76000/Native-Git-support-can-be-enabled-for-a-Git-version-which-is-sho)** — Native Git support can be enabled for a Git version which is shown later as not supported
* **[TW-64269](https://youtrack.jetbrains.com/issue/TW-64269/Improve-buttons-presentations-on-hover)** — Improve buttons presentations on hover
* **[TW-71876](https://youtrack.jetbrains.com/issue/TW-71876/Display-zero-counter-if-Agents-pool-contains-no-agents-in-Experi)** — Display zero counter if Agents pool contains no agents in Experimental UI.


### Performance Problem

* **[TW-75951](https://youtrack.jetbrains.com/issue/TW-75951/LuceneSearchService.serverStartup-spent-more-than-20-minutes-ini)** — LuceneSearchService.serverStartup spent more than 20 minutes initializing on server startup
* **[TW-72284](https://youtrack.jetbrains.com/issue/TW-72284/Finish-composite-builds-immediately-when-the-last-dependency-is-)** — Finish composite builds immediately when the last dependency is finished
* **[TW-73704](https://youtrack.jetbrains.com/issue/TW-73704/Test-details-expanding-can-take-a-lot-of-time)** — Test details expanding can take a lot of time
* **[TW-74652](https://youtrack.jetbrains.com/issue/TW-74652/Lots-of-HTTP-requests-loading-build.finish.properties.gz-files)** — Lots of HTTP requests loading build.finish.properties.gz files
* **[TW-74803](https://youtrack.jetbrains.com/issue/TW-74803/Should-not-cleanup-all-caches-in-AgentTypeStorage-when-agent-poo)** — Should not cleanup all caches in AgentTypeStorage when agent pool is deleted or projects are removed from it.
* **[TW-75019](https://youtrack.jetbrains.com/issue/TW-75019/Create-an-index-for-build_type_id,-remove_from_queue_time-column)** — Create an index for build_type_id, remove_from_queue_time columns to speedup showing builds of a build configuration
* **[TW-75054](https://youtrack.jetbrains.com/issue/TW-75054/Create-an-index-to-final_artifact_dependency.source_build_type_i)** — Create an index to final_artifact_dependency.source_build_type_id
* **[TW-75348](https://youtrack.jetbrains.com/issue/TW-75348/The-Change-page-is-very-slow-if-a-commit-is-%22unreachable%22)** — The Change page is very slow if a commit is "unreachable"
* **[TW-75401](https://youtrack.jetbrains.com/issue/TW-75401/A-lot-of-threads-consume-CPU-on-generating-presign-urls-(cloudfr))** — A lot of threads consume CPU on generating presign urls (cloudfront sign URLs)
* **[TW-75543](https://youtrack.jetbrains.com/issue/TW-75543/Lots-of-exclusive-DB-locks-are-taken-by-CloudInstancesDBPersisto)** — Lots of exclusive DB locks are taken by CloudInstancesDBPersistor::persistToDB
* **[TW-75920](https://youtrack.jetbrains.com/issue/TW-75920/New-Changes-UI;-switching-to-Builds-shows-truncated-tree-for-not)** — New Changes UI; switching to Builds shows truncated tree for noticeable time
* **[TW-53298](https://youtrack.jetbrains.com/issue/TW-53298/Long-cleanup-BackgroundBuildDataCleanerImpl-stage:-removing-data)** — Long cleanup BackgroundBuildDataCleanerImpl stage: removing data from test_info table takes more than 6 hours
* **[TW-56119](https://youtrack.jetbrains.com/issue/TW-56119/Improve-Git-getCurrentState-operation-in-case-when-several-threa)** — Improve Git getCurrentState operation in case when several threads attempt to perform ls-remote against the same repository
* **[TW-62988](https://youtrack.jetbrains.com/issue/TW-62988/Build-queue-processing-thread-can-delay-builds-starting-if-there)** — Build queue processing thread can delay builds starting if there were many events produced by a secondary node
* **[TW-64793](https://youtrack.jetbrains.com/issue/TW-64793/A-build-which-constantly-reports-lots-of-build-problems-can-slow)** — A build which constantly reports lots of build problems can slow down queue processing in case of multi-node setup
* **[TW-66424](https://youtrack.jetbrains.com/issue/TW-66424/Overflow-of-%22Low-prio-executor%22)** — Overflow of "Low prio executor"
* **[TW-70501](https://youtrack.jetbrains.com/issue/TW-70501/Slow-REST-API-call-app-rest-ui-projects-id:%3Cproject%3E-branchesloc)** — Slow REST API call /app/rest/ui/projects/id:&lt;project>/branches?locator=
* **[TW-73504](https://youtrack.jetbrains.com/issue/TW-73504/ExactRevisionMatchStrategy.findBuildContainingChange-slows-down-)** — ExactRevisionMatchStrategy.findBuildContainingChange slows down build triggers processing
* **[TW-73572](https://youtrack.jetbrains.com/issue/TW-73572/Build-agents-cannot-send-messages-to-server-because-server-does-)** — Build agents cannot send messages to server because server does not accept the messages, XmlRpcPoolQueueOverflownException (caused by PerfMon plugin)
* **[TW-73732](https://youtrack.jetbrains.com/issue/TW-73732/Build-agents-messages-processing-delay-because-of-global-synchro)** — Build agents messages processing delay because of global synchronization in TestMetadataStorage
* **[TW-73923](https://youtrack.jetbrains.com/issue/TW-73923/Avoid-re-calculating-tests-statistics-for-composite-builds-witho)** — Avoid re-calculating tests statistics for composite builds without currently running dependencies
* **[TW-74143](https://youtrack.jetbrains.com/issue/TW-74143/Extremely-high-CPU-usage-on-a-server-without-any-running-builds-)** — Extremely high CPU usage on a server without any running builds and with a large number of queued builds or build triggers
* **[TW-74229](https://youtrack.jetbrains.com/issue/TW-74229/Drop-Edge-18-support)** — Drop Edge 18 support
* **[TW-74349](https://youtrack.jetbrains.com/issue/TW-74349/Builds-List-in-Safari-has-low-FPS-when-a-user-scrolls-moves-poin)** — Builds List in Safari has low FPS when a user scrolls/moves pointer over it.
* **[TW-74355](https://youtrack.jetbrains.com/issue/TW-74355/JDK-chooser-control-can-slow-down-loading-of-the-build-step-edit)** — JDK chooser control can slow down loading of the build step editing page
* **[TW-74457](https://youtrack.jetbrains.com/issue/TW-74457/A-single-agent-buildFinished-message-processing-can-lead-to-a-bl)** — A single agent buildFinished message processing can lead to a blocked threads and inability to process messages from any other agents for a long period of time
* **[TW-74722](https://youtrack.jetbrains.com/issue/TW-74722/REST-API-calls-fetching-all-branches-of-a-particular-project-are)** — REST API calls fetching all branches of a particular project are slow and CPU consuming
* **[TW-75006](https://youtrack.jetbrains.com/issue/TW-75006/SequenceLoader-recalculates-readiness-of-all-items-in-it)** — SequenceLoader recalculates readiness of all items in it
* **[TW-75067](https://youtrack.jetbrains.com/issue/TW-75067/Postpone-check-for-default-branch-existence-used-for-build-confi)** — Postpone check for default branch existence used for build configuration Run button
* **[TW-75085](https://youtrack.jetbrains.com/issue/TW-75085/Slow-order-and-visibility-computation-for-overview-page)** — Slow order and visibility computation for overview page
* **[TW-75111](https://youtrack.jetbrains.com/issue/TW-75111/GuardedS3PresignedUrlProvider-performs-a-file-operation-on-each-)** — GuardedS3PresignedUrlProvider performs a file operation on each /artefacts/s3/upload/presign-urls.html request
* **[TW-75164](https://youtrack.jetbrains.com/issue/TW-75164/Server-unresponsive-due-to-loading-of-AgentType-caches)** — Server unresponsive due to loading of AgentType caches
* **[TW-75178](https://youtrack.jetbrains.com/issue/TW-75178/Speedup-check-for-empty-directory-in-.GeneratedSettingsCache.get)** — Speedup check for empty directory in .GeneratedSettingsCache.getAndLock
* **[TW-75265](https://youtrack.jetbrains.com/issue/TW-75265/Unnecessary-listing-of-all-of-the-files-under-the-directory-fetc)** — Unnecessary listing of all of the files under the directory fetched from the versioned settings (versioned settings are enabled on the root project level)
* **[TW-75654](https://youtrack.jetbrains.com/issue/TW-75654/High-CPU-load-on-Perforce-server-to-collect-the-latest-changes)** — High CPU load on Perforce server to collect the latest changes

### Security

11 security problems have been fixed.
