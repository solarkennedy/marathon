# Change Log

## [Unreleased](https://github.com/mesosphere/marathon/tree/HEAD)

[Full Changelog](https://github.com/mesosphere/marathon/compare/v1.1.0-RC2...HEAD)

**Merged pull requests:**

- document the dependency on the feature-flag in the ext vol docs [\#3764](https://github.com/mesosphere/marathon/pull/3764) ([jdef](https://github.com/jdef))

## [v1.1.0-RC2](https://github.com/mesosphere/marathon/tree/v1.1.0-RC2) (2016-04-13)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v1.1.0-RC1...v1.1.0-RC2)

**Implemented enhancements:**

- Don't provide a kill button for "suspended" resident tasks [\#3658](https://github.com/mesosphere/marathon/issues/3658)
- "Suspended" resident tasks should have a different status [\#3657](https://github.com/mesosphere/marathon/issues/3657)
- Docker volume ":z" option [\#3593](https://github.com/mesosphere/marathon/issues/3593)
- Support per-container ip addresses [\#2432](https://github.com/mesosphere/marathon/issues/2432)

**Fixed bugs:**

- external volumes: UI shows volume attached even though app is suspended and no tasks are active [\#3724](https://github.com/mesosphere/marathon/issues/3724)
- external volumes: allows user to create multiple zero-instance apps that ref the same volume, and then scale them both to 1 [\#3723](https://github.com/mesosphere/marathon/issues/3723)
- Don't provide a kill button for "suspended" resident tasks [\#3658](https://github.com/mesosphere/marathon/issues/3658)
- "Suspended" resident tasks should have a different status [\#3657](https://github.com/mesosphere/marathon/issues/3657)
- JSON editor help button obscured by line highlight [\#3656](https://github.com/mesosphere/marathon/issues/3656)
- Improve documentation for persistent volumes [\#3627](https://github.com/mesosphere/marathon/issues/3627)
- Scheduler Migrations: Fix host port detection for readiness checks [\#3616](https://github.com/mesosphere/marathon/issues/3616)
- ZK CandidateImpl instances leaked after leader elections [\#2419](https://github.com/mesosphere/marathon/issues/2419)
- Fix offersWantedSubjects [\#3758](https://github.com/mesosphere/marathon/pull/3758) ([kolloch](https://github.com/kolloch))
- ext vol docs: s/external.drivers/external.options/ [\#3749](https://github.com/mesosphere/marathon/pull/3749) ([jdef](https://github.com/jdef))
- Fixes \#3648 - LaunchQueue: Do not defer TaskChanged [\#3721](https://github.com/mesosphere/marathon/pull/3721) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Persistent volumes: probably a bug when restart the marathon app \(click the restart button\) [\#3754](https://github.com/mesosphere/marathon/issues/3754)
- No way to delete persistent volumes for an application instance [\#3748](https://github.com/mesosphere/marathon/issues/3748)
- is there any way to specify the container's name? [\#3743](https://github.com/mesosphere/marathon/issues/3743)
- Update release notes to explain external volume support [\#3740](https://github.com/mesosphere/marathon/issues/3740)
- Getting more done in GitHub with ZenHub [\#3727](https://github.com/mesosphere/marathon/issues/3727)
- Confusion about mesos role and default accepted roles [\#3722](https://github.com/mesosphere/marathon/issues/3722)
- External Volumes has the wrong tooltip message [\#3719](https://github.com/mesosphere/marathon/issues/3719)
- Flaky Test: GroupDeployIntegrationTest [\#3648](https://github.com/mesosphere/marathon/issues/3648)
- Scheduler Migrations: AppDefinition documentation [\#3505](https://github.com/mesosphere/marathon/issues/3505)
- Scheduler Migrations: Integration Test [\#3503](https://github.com/mesosphere/marathon/issues/3503)

**Merged pull requests:**

- Add missing documentation for the wipe flag [\#3756](https://github.com/mesosphere/marathon/pull/3756) ([meichstedt](https://github.com/meichstedt))
- Introduce feature\_flag external\_volumes. [\#3755](https://github.com/mesosphere/marathon/pull/3755) ([aquamatthias](https://github.com/aquamatthias))
- Remove unused dependency. [\#3750](https://github.com/mesosphere/marathon/pull/3750) ([aquamatthias](https://github.com/aquamatthias))
- TOC reorganization [\#3746](https://github.com/mesosphere/marathon/pull/3746) ([meichstedt](https://github.com/meichstedt))
- Log unknown task. [\#3739](https://github.com/mesosphere/marathon/pull/3739) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3503 by implementing integration tests for starting and updati… [\#3738](https://github.com/mesosphere/marathon/pull/3738) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3723 - Fix validation of duplicate volume names [\#3737](https://github.com/mesosphere/marathon/pull/3737) ([kolloch](https://github.com/kolloch))
- Resolves \#3627 by improving docs on stateful applications … [\#3736](https://github.com/mesosphere/marathon/pull/3736) ([meichstedt](https://github.com/meichstedt))
- Fix Zookeeper group member listener leak in leader election [\#3732](https://github.com/mesosphere/marathon/pull/3732) ([sttts](https://github.com/sttts))
- Task documentation reformatting \(automatic\) [\#3731](https://github.com/mesosphere/marathon/pull/3731) ([kolloch](https://github.com/kolloch))
- Changelog for 1.1 [\#3720](https://github.com/mesosphere/marathon/pull/3720) ([aquamatthias](https://github.com/aquamatthias))
- Task State Diagram [\#3718](https://github.com/mesosphere/marathon/pull/3718) ([kolloch](https://github.com/kolloch))
- Documentation for external volumes [\#3715](https://github.com/mesosphere/marathon/pull/3715) ([jdef](https://github.com/jdef))
- Resolves \#3505 by adding documentation for ReadinessChecks [\#3711](https://github.com/mesosphere/marathon/pull/3711) ([meichstedt](https://github.com/meichstedt))

## [v1.1.0-RC1](https://github.com/mesosphere/marathon/tree/v1.1.0-RC1) (2016-04-08)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v1.0.0-RC1...v1.1.0-RC1)

**Implemented enhancements:**

- Improve genral error reporting [\#3661](https://github.com/mesosphere/marathon/issues/3661)
- Don't allow persistent container paths containing slashes [\#3614](https://github.com/mesosphere/marathon/issues/3614)
- Add link to Docker section for Ports [\#3564](https://github.com/mesosphere/marathon/issues/3564)
- Create Modal: always show Port Index for host ports [\#3559](https://github.com/mesosphere/marathon/issues/3559)
- Cleanup JSON editor portDefinitions [\#3539](https://github.com/mesosphere/marathon/issues/3539)
- Improve ports validation [\#3426](https://github.com/mesosphere/marathon/issues/3426)
- Maintain "assign random port" settings after JSON mode switch [\#3424](https://github.com/mesosphere/marathon/issues/3424)
- Support HTTPS health checks. [\#3405](https://github.com/mesosphere/marathon/issues/3405)
- Add port name and labels to Docker portMappings [\#3262](https://github.com/mesosphere/marathon/issues/3262)
- \[Authorization Interface\] Create AppDefinition specific Actions, so the decision can be based on the app [\#2905](https://github.com/mesosphere/marathon/issues/2905)

**Fixed bugs:**

- Marathon uses incorrect URI for continue operation on a interrupted plan [\#3691](https://github.com/mesosphere/marathon/issues/3691)
- Readiness Checks Should be Independent of Service Health [\#3689](https://github.com/mesosphere/marathon/issues/3689)
- Resident tasks: Disallow "acceptedResourceRoles" != \["\*"\] [\#3673](https://github.com/mesosphere/marathon/issues/3673)
- PUT /v2/apps/\<app id\> fails for resident task without upgradeStrategy [\#3664](https://github.com/mesosphere/marathon/issues/3664)
- Apps created from inside a group have a double forward-slash in their ID [\#3663](https://github.com/mesosphere/marathon/issues/3663)
- JSON editor help button does not work in IE11 [\#3659](https://github.com/mesosphere/marathon/issues/3659)
- Apps with no volumes reported as stateful [\#3655](https://github.com/mesosphere/marathon/issues/3655)
- portMapping labels are not being set [\#3654](https://github.com/mesosphere/marathon/issues/3654)
- Error paths are mapped incorrectly [\#3652](https://github.com/mesosphere/marathon/issues/3652)
- Liquid Exception in docs [\#3646](https://github.com/mesosphere/marathon/issues/3646)
- Marathon should validate that port names contain only letters and numbers [\#3612](https://github.com/mesosphere/marathon/issues/3612)
- Marathon editor sometimes corrupts container port assignments after edits \(video\) [\#3595](https://github.com/mesosphere/marathon/issues/3595)
- Not specifying "network" config causes mesos to thrash [\#3587](https://github.com/mesosphere/marathon/issues/3587)
- Resident Tasks: Flaky test: restart [\#3579](https://github.com/mesosphere/marathon/issues/3579)
- Duplicable row client-side validation hangs the UI \(Safari Browser\) [\#3577](https://github.com/mesosphere/marathon/issues/3577)
- Container IP not correctly display in 0.15.0 and above [\#3575](https://github.com/mesosphere/marathon/issues/3575)
- Editing an App: Switching between JSON and normal Editor produces a broken UX [\#3552](https://github.com/mesosphere/marathon/issues/3552)
- The default Docker network should be `host`. [\#3519](https://github.com/mesosphere/marathon/issues/3519)
- residency added even if no volumes are requested [\#3518](https://github.com/mesosphere/marathon/issues/3518)
- Ports: strip deprecated ports when editing via JSON [\#3470](https://github.com/mesosphere/marathon/issues/3470)
- Ports: name should be optional [\#3468](https://github.com/mesosphere/marathon/issues/3468)
- Constraints validation message [\#3369](https://github.com/mesosphere/marathon/issues/3369)
- Delayed applications can appear to be running [\#3092](https://github.com/mesosphere/marathon/issues/3092)
- Fixes \#3575 - Get NetworkInfo from Mesos task updates [\#3604](https://github.com/mesosphere/marathon/pull/3604) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3579/\#3477/\#3597 - adjustments to restart logic [\#3603](https://github.com/mesosphere/marathon/pull/3603) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- External Volumes: Clean up validation [\#3700](https://github.com/mesosphere/marathon/issues/3700)
- External Volumes: Choose a matching upgrade strategy by default [\#3699](https://github.com/mesosphere/marathon/issues/3699)
- Remove the Deployment Stop Button in the UI [\#3692](https://github.com/mesosphere/marathon/issues/3692)
- Add VIPs + IP-per-Task support [\#3684](https://github.com/mesosphere/marathon/issues/3684)
- Scrolling issue with create modal [\#3671](https://github.com/mesosphere/marathon/issues/3671)
- Add support for scheduler upgrades and readinessChecks [\#3670](https://github.com/mesosphere/marathon/issues/3670)
- Question: is Mesos unified containerizer supported through the API? [\#3638](https://github.com/mesosphere/marathon/issues/3638)
- Constraints are not working for updating [\#3624](https://github.com/mesosphere/marathon/issues/3624)
- Discovery Ports should be stored and exposed for docker tasks [\#3619](https://github.com/mesosphere/marathon/issues/3619)
- Variable Commands [\#3618](https://github.com/mesosphere/marathon/issues/3618)
- Upgrading applications with persistent storage [\#3597](https://github.com/mesosphere/marathon/issues/3597)
- Accessing Marathon Plugin Conf in Java Implementation [\#3592](https://github.com/mesosphere/marathon/issues/3592)
- Container path containing slashes makes application hang on wait \[Version 1.0.0-RC1\] [\#3589](https://github.com/mesosphere/marathon/issues/3589)
- memory size can not set less than 32m [\#3588](https://github.com/mesosphere/marathon/issues/3588)
- Object is not valid on app scaling [\#3585](https://github.com/mesosphere/marathon/issues/3585)
- ResidentTasks: ResourceMatching and Constraints [\#3574](https://github.com/mesosphere/marathon/issues/3574)
- Scheduler Migrations: Expose Readiness Check Results [\#3562](https://github.com/mesosphere/marathon/issues/3562)
- Unnecessary active class on create button [\#3554](https://github.com/mesosphere/marathon/issues/3554)
- Marathon callback lost message [\#3532](https://github.com/mesosphere/marathon/issues/3532)
- Scheduler Migrations: Integrate Readiness Checks into Restart Deployment Action [\#3502](https://github.com/mesosphere/marathon/issues/3502)
- Scheduler Migrations: AppDefinition validation [\#3501](https://github.com/mesosphere/marathon/issues/3501)
- Scheduler Migrations: Add "readinessCheck" configuration to AppDefinition [\#3500](https://github.com/mesosphere/marathon/issues/3500)
- Scheduler Migrations: Fake scheduler for integration tests [\#3498](https://github.com/mesosphere/marathon/issues/3498)
- Resident Tasks: Flaky test: config change [\#3477](https://github.com/mesosphere/marathon/issues/3477)
- marathon create docker ps -a display name does not work [\#3354](https://github.com/mesosphere/marathon/issues/3354)
- Leadership Metric [\#3010](https://github.com/mesosphere/marathon/issues/3010)

**Merged pull requests:**

- use config.taskReservationTimeout for TaskStateOp.Reserve [\#3717](https://github.com/mesosphere/marathon/pull/3717) ([meichstedt](https://github.com/meichstedt))
- Use MarathonUI 1.1.0-SNAPSHOT [\#3714](https://github.com/mesosphere/marathon/pull/3714) ([orlandohohmeier](https://github.com/orlandohohmeier))
- Fixes \#3699 - external volumes with update strategy [\#3713](https://github.com/mesosphere/marathon/pull/3713) ([lexwbr](https://github.com/lexwbr))
- Fixes \#3682 - Use portAssignments for readiness checks [\#3712](https://github.com/mesosphere/marathon/pull/3712) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3700 - cleanup external volume validation [\#3710](https://github.com/mesosphere/marathon/pull/3710) ([kolloch](https://github.com/kolloch))
- Fixes \#3684 - Add VIPs + IP-per-Task support [\#3709](https://github.com/mesosphere/marathon/pull/3709) ([gkleiman](https://github.com/gkleiman))
- Bump MarathonUI number to 1.0.1 [\#3708](https://github.com/mesosphere/marathon/pull/3708) ([philipnrmn](https://github.com/philipnrmn))
- Fixes \#3689 by starting readiness checks, once the task is started. [\#3705](https://github.com/mesosphere/marathon/pull/3705) ([aquamatthias](https://github.com/aquamatthias))
- External volumes - hide internal implementations [\#3703](https://github.com/mesosphere/marathon/pull/3703) ([kolloch](https://github.com/kolloch))
- Towards \#3616 - Introduce AppDefinition.portAssignments [\#3702](https://github.com/mesosphere/marathon/pull/3702) ([gkleiman](https://github.com/gkleiman))
- docs: fix sentence with typo than -\> then [\#3701](https://github.com/mesosphere/marathon/pull/3701) ([thefourtheye](https://github.com/thefourtheye))
- Feature scheduler upgrades [\#3697](https://github.com/mesosphere/marathon/pull/3697) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3689 by starting readiness checks, once the task is started. [\#3695](https://github.com/mesosphere/marathon/pull/3695) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3664 - default upgradeStrategy and residency for persistent volumes [\#3686](https://github.com/mesosphere/marathon/pull/3686) ([lexwbr](https://github.com/lexwbr))
- Resolves \#3673 by only considering unreserved resources [\#3685](https://github.com/mesosphere/marathon/pull/3685) ([meichstedt](https://github.com/meichstedt))
- Finish providerName =\> provider renaming [\#3683](https://github.com/mesosphere/marathon/pull/3683) ([sttts](https://github.com/sttts))
- External Volumes refactorings [\#3680](https://github.com/mesosphere/marathon/pull/3680) ([kolloch](https://github.com/kolloch))
- Refactoring External Volumes [\#3678](https://github.com/mesosphere/marathon/pull/3678) ([kolloch](https://github.com/kolloch))
- Fixes \#3654 - Extract port labels from port mappings [\#3677](https://github.com/mesosphere/marathon/pull/3677) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3698 - External Volumes: DVDI [\#3675](https://github.com/mesosphere/marathon/pull/3675) ([sttts](https://github.com/sttts))
- Make mesos principal optional. [\#3674](https://github.com/mesosphere/marathon/pull/3674) ([aquamatthias](https://github.com/aquamatthias))
- add a log statement when a ReservationTimeout is scheduled for a task [\#3669](https://github.com/mesosphere/marathon/pull/3669) ([meichstedt](https://github.com/meichstedt))
- Start a deployment also if only residency or upgradeStrategy is changed. [\#3667](https://github.com/mesosphere/marathon/pull/3667) ([aquamatthias](https://github.com/aquamatthias))
- Use MarathonUI 1.0.0-SNAPSHOT [\#3666](https://github.com/mesosphere/marathon/pull/3666) ([gkleiman](https://github.com/gkleiman))
- Accept --no-logger and --no\_logger to fix ENV export [\#3651](https://github.com/mesosphere/marathon/pull/3651) ([lloesche](https://github.com/lloesche))
- WIP: Simplifications [\#3650](https://github.com/mesosphere/marathon/pull/3650) ([sttts](https://github.com/sttts))
- Resolves \#3574 by not considering the volumeMatch's Reserved task … [\#3649](https://github.com/mesosphere/marathon/pull/3649) ([meichstedt](https://github.com/meichstedt))
- Fixes \#3646 by removing a line break [\#3647](https://github.com/mesosphere/marathon/pull/3647) ([meichstedt](https://github.com/meichstedt))
- Fixes \#3614 - Don't allow persistent container paths containing slashes [\#3645](https://github.com/mesosphere/marathon/pull/3645) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3612 - Validate port names [\#3644](https://github.com/mesosphere/marathon/pull/3644) ([gkleiman](https://github.com/gkleiman))
- Fix TaskBuilderTest: Test would fail when [\#3642](https://github.com/mesosphere/marathon/pull/3642) ([kolloch](https://github.com/kolloch))
- Towards \#3627 tiny improvements of the Resident Tasks doc [\#3641](https://github.com/mesosphere/marathon/pull/3641) ([meichstedt](https://github.com/meichstedt))
- Cancel subscriptions if the task terminates. [\#3640](https://github.com/mesosphere/marathon/pull/3640) ([aquamatthias](https://github.com/aquamatthias))
- Make group validation O\(n\*log\(n\)\) [\#3639](https://github.com/mesosphere/marathon/pull/3639) ([sttts](https://github.com/sttts))
- Render deployment check results into the app listing. [\#3634](https://github.com/mesosphere/marathon/pull/3634) ([aquamatthias](https://github.com/aquamatthias))
- Remove an illegal comma from JSON example [\#3633](https://github.com/mesosphere/marathon/pull/3633) ([plombardi89](https://github.com/plombardi89))
- Fixed Typo in Stateful Docu. [\#3631](https://github.com/mesosphere/marathon/pull/3631) ([joerg84](https://github.com/joerg84))
- Fixes \#3502 - Implement ReadinessCheckExecutor with Spray [\#3630](https://github.com/mesosphere/marathon/pull/3630) ([kolloch](https://github.com/kolloch))
- Cleanup [\#3628](https://github.com/mesosphere/marathon/pull/3628) ([sttts](https://github.com/sttts))
- Resolves \#3501 by adding validation for Scheduler app definitions and… [\#3626](https://github.com/mesosphere/marathon/pull/3626) ([meichstedt](https://github.com/meichstedt))
- Implement a ServiceMock that adheres to the Service Upgrade specification. [\#3625](https://github.com/mesosphere/marathon/pull/3625) ([aquamatthias](https://github.com/aquamatthias))
- Updated Copyright to 2016. [\#3623](https://github.com/mesosphere/marathon/pull/3623) ([joerg84](https://github.com/joerg84))
- Apply readiness checks as part of a Deployment [\#3617](https://github.com/mesosphere/marathon/pull/3617) ([aquamatthias](https://github.com/aquamatthias))
- Edit recipes [\#3608](https://github.com/mesosphere/marathon/pull/3608) ([sascala](https://github.com/sascala))
- remove Defaults.defaultSettings mix in [\#3605](https://github.com/mesosphere/marathon/pull/3605) ([timcharper](https://github.com/timcharper))
- Towards \#3502 - Define ReadinessCheckExecutor [\#3600](https://github.com/mesosphere/marathon/pull/3600) ([kolloch](https://github.com/kolloch))
- Correct sample deployments response [\#3598](https://github.com/mesosphere/marathon/pull/3598) ([kolloch](https://github.com/kolloch))
- Add HTTPS healthCheck in doc [\#3594](https://github.com/mesosphere/marathon/pull/3594) ([janisz](https://github.com/janisz))
- Towards \#3562 - Readiness Checks formats [\#3584](https://github.com/mesosphere/marathon/pull/3584) ([gkleiman](https://github.com/gkleiman))
- Add ReadinessCheckResults classes [\#3581](https://github.com/mesosphere/marathon/pull/3581) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3500 - Add ReadinessChecks to AppDefinition [\#3580](https://github.com/mesosphere/marathon/pull/3580) ([kolloch](https://github.com/kolloch))
- Add v0.15.3 changelog [\#3578](https://github.com/mesosphere/marathon/pull/3578) ([gkleiman](https://github.com/gkleiman))
- rewrote the docs landing page [\#3576](https://github.com/mesosphere/marathon/pull/3576) ([air](https://github.com/air))
- Add changelog entry for Persistent Storage [\#3573](https://github.com/mesosphere/marathon/pull/3573) ([meichstedt](https://github.com/meichstedt))

## [v1.0.0-RC1](https://github.com/mesosphere/marathon/tree/v1.0.0-RC1) (2016-03-23)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.16.0-RC3...v1.0.0-RC1)

**Fixed bugs:**

- Ports validation errors [\#3557](https://github.com/mesosphere/marathon/issues/3557)
- Ports validation errror text should be red [\#3542](https://github.com/mesosphere/marathon/issues/3542)
- The application is locked by deployment error is missing in the app edit modal [\#3537](https://github.com/mesosphere/marathon/issues/3537)
- apps shown last identifier to id, rather than entire path [\#3530](https://github.com/mesosphere/marathon/issues/3530)
- UI docker volumes validation issue [\#3495](https://github.com/mesosphere/marathon/issues/3495)
- Create application button stays disabled [\#3494](https://github.com/mesosphere/marathon/issues/3494)
- Path needs to be absolute in Marathon 0.16.0-RC1 [\#3487](https://github.com/mesosphere/marathon/issues/3487)
- Empty groups produce duplicate key in App List [\#3482](https://github.com/mesosphere/marathon/issues/3482)
- Leader not aware of its leadership [\#2751](https://github.com/mesosphere/marathon/issues/2751)
- Make integration tests pass with official Mesos releases [\#3538](https://github.com/mesosphere/marathon/pull/3538) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2751 - Commit suicide on ZK exceptions [\#3528](https://github.com/mesosphere/marathon/pull/3528) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3520 - Revert "Opt in for task killing state \(pure signalling … [\#3521](https://github.com/mesosphere/marathon/pull/3521) ([gkleiman](https://github.com/gkleiman))

**Closed issues:**

- External Volumes: DVDI/rexray [\#3698](https://github.com/mesosphere/marathon/issues/3698)
- Update link in JSON editor tooltip [\#3558](https://github.com/mesosphere/marathon/issues/3558)
- Tooltip links within create modal should be white [\#3548](https://github.com/mesosphere/marathon/issues/3548)
- Feature Flags [\#3544](https://github.com/mesosphere/marathon/issues/3544)
- app id within group requires / [\#3529](https://github.com/mesosphere/marathon/issues/3529)
- Odd Mesos UI behavior [\#3524](https://github.com/mesosphere/marathon/issues/3524)
- cannot register to mesos [\#3520](https://github.com/mesosphere/marathon/issues/3520)
- marathon health check problem with tcp protocol [\#3517](https://github.com/mesosphere/marathon/issues/3517)
- Unable to start applications [\#3514](https://github.com/mesosphere/marathon/issues/3514)
- Questions about port names [\#3506](https://github.com/mesosphere/marathon/issues/3506)
- Scheduler Migrations: "Proxy" commands to schedulers [\#3499](https://github.com/mesosphere/marathon/issues/3499)
- Scheduler Migrations: Query and execute commands on scheduler /v1/plan endpoint [\#3497](https://github.com/mesosphere/marathon/issues/3497)
- Resident Tasks: Manually kill/wipe task including reservation [\#3456](https://github.com/mesosphere/marathon/issues/3456)
- Resident Tasks: Acknowledgement/Timeout for Reservations/Local Volume Creates [\#3221](https://github.com/mesosphere/marathon/issues/3221)
- Provide a UI plugin mechanism [\#2827](https://github.com/mesosphere/marathon/issues/2827)
- Marathon, docker, consul. containerPort = hostPort = 0 for udp and tcp [\#929](https://github.com/mesosphere/marathon/issues/929)

**Merged pull requests:**

- Add missing fixes. [\#3572](https://github.com/mesosphere/marathon/pull/3572) ([aquamatthias](https://github.com/aquamatthias))
- doc updates for 1.0.0-RC1 [\#3571](https://github.com/mesosphere/marathon/pull/3571) ([air](https://github.com/air))
- Resolves \#3456 added endpoint for manual deletion of residents [\#3570](https://github.com/mesosphere/marathon/pull/3570) ([meichstedt](https://github.com/meichstedt))
- Update Marathon UI to 1.0.0 [\#3569](https://github.com/mesosphere/marathon/pull/3569) ([aquamatthias](https://github.com/aquamatthias))
- WIP Update changelog for v1.0.0 [\#3567](https://github.com/mesosphere/marathon/pull/3567) ([gkleiman](https://github.com/gkleiman))
- Use mesos 0.28.0 [\#3561](https://github.com/mesosphere/marathon/pull/3561) ([aquamatthias](https://github.com/aquamatthias))
- Handle special case, if users have no access to the root group. [\#3560](https://github.com/mesosphere/marathon/pull/3560) ([aquamatthias](https://github.com/aquamatthias))
- Make the defaults consistent with the code. [\#3556](https://github.com/mesosphere/marathon/pull/3556) ([aquamatthias](https://github.com/aquamatthias))
- Enable TASK\_KILLING state that is available in mesos 0.28. This featu… [\#3550](https://github.com/mesosphere/marathon/pull/3550) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3530 by using the canonical path of a nested group or app. [\#3547](https://github.com/mesosphere/marathon/pull/3547) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3544 - Introduce feature flags [\#3545](https://github.com/mesosphere/marathon/pull/3545) ([kolloch](https://github.com/kolloch))
- Bump version to mesos 0.28 [\#3536](https://github.com/mesosphere/marathon/pull/3536) ([aquamatthias](https://github.com/aquamatthias))
- Allow  for tcp,udp ports in portMappings [\#3534](https://github.com/mesosphere/marathon/pull/3534) ([sttts](https://github.com/sttts))
- Towards \#3221 - serialized task updates [\#3533](https://github.com/mesosphere/marathon/pull/3533) ([meichstedt](https://github.com/meichstedt))
- Fixes 3091 - App updates hanging on downscales [\#3531](https://github.com/mesosphere/marathon/pull/3531) ([pgkelley4](https://github.com/pgkelley4))
- Updates Tomcat to 7.0.68 [\#3522](https://github.com/mesosphere/marathon/pull/3522) ([brianantonelli](https://github.com/brianantonelli))
- Improve Task Kill behavior in deployments by introducing kills in batches [\#3513](https://github.com/mesosphere/marathon/pull/3513) ([aquamatthias](https://github.com/aquamatthias))
- Opt in for task killing state \(pure signalling in the moment\) [\#3507](https://github.com/mesosphere/marathon/pull/3507) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3471 - prevent multiple marathon instances to fight over reser… [\#3492](https://github.com/mesosphere/marathon/pull/3492) ([kolloch](https://github.com/kolloch))
- Towards \#3221 - \(Kill\)OverdueTasksActor also handles reservation time… [\#3486](https://github.com/mesosphere/marathon/pull/3486) ([kolloch](https://github.com/kolloch))
- Documentation for persistent volumes [\#3479](https://github.com/mesosphere/marathon/pull/3479) ([sascala](https://github.com/sascala))
- Adding test for negative resources app creation [\#3453](https://github.com/mesosphere/marathon/pull/3453) ([jimenez](https://github.com/jimenez))

## [v0.16.0-RC3](https://github.com/mesosphere/marathon/tree/v0.16.0-RC3) (2016-03-16)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.16.0-RC2...v0.16.0-RC3)

**Implemented enhancements:**

- Report kills due to failed health check in "Last Task Failure" [\#3423](https://github.com/mesosphere/marathon/issues/3423)

**Closed issues:**

- why does the app or group id not support i18n, such as chinese? [\#3509](https://github.com/mesosphere/marathon/issues/3509)
- app group deploy error [\#3508](https://github.com/mesosphere/marathon/issues/3508)

**Merged pull requests:**

- Fill DiscoveryInfo with host port instead of service port [\#3511](https://github.com/mesosphere/marathon/pull/3511) ([gkleiman](https://github.com/gkleiman))

## [v0.16.0-RC2](https://github.com/mesosphere/marathon/tree/v0.16.0-RC2) (2016-03-15)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.16.0-RC1...v0.16.0-RC2)

**Fixed bugs:**

- Marathon fails to properly escape command health checks [\#3333](https://github.com/mesosphere/marathon/issues/3333)

**Closed issues:**

- Resident Tasks: Prevent multiple marathon instances to fight over reservations [\#3471](https://github.com/mesosphere/marathon/issues/3471)
- Nicer container validation [\#3412](https://github.com/mesosphere/marathon/issues/3412)
- Cleanup threads in HttpEventModule [\#3109](https://github.com/mesosphere/marathon/issues/3109)
- Support  dynamic persistent volumes [\#2493](https://github.com/mesosphere/marathon/issues/2493)

**Merged pull requests:**

- Do not exhaust service provider iterator. [\#3493](https://github.com/mesosphere/marathon/pull/3493) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3412 - nicer container validation. [\#3484](https://github.com/mesosphere/marathon/pull/3484) ([lexwbr](https://github.com/lexwbr))

## [v0.16.0-RC1](https://github.com/mesosphere/marathon/tree/v0.16.0-RC1) (2016-03-14)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC8...v0.16.0-RC1)

**Implemented enhancements:**

- Validation errors should only be shown if the user had the chance to enter the valid values. [\#3462](https://github.com/mesosphere/marathon/issues/3462)
- Create modal: pre-fill group with trailing / when creating a new app [\#3440](https://github.com/mesosphere/marathon/issues/3440)
- Create application button should be disabled until data was provided [\#3431](https://github.com/mesosphere/marathon/issues/3431)
- Add tooltips to the new app modal [\#3425](https://github.com/mesosphere/marathon/issues/3425)
- Show empty groups [\#2769](https://github.com/mesosphere/marathon/issues/2769)

**Fixed bugs:**

- Deployment progress bar looks weird [\#3469](https://github.com/mesosphere/marathon/issues/3469)
- Creating an app in a group removes default values [\#3467](https://github.com/mesosphere/marathon/issues/3467)
- Adjust API error parsing to match new format [\#3460](https://github.com/mesosphere/marathon/issues/3460)
- Fix dialog styles [\#3458](https://github.com/mesosphere/marathon/issues/3458)
- Uncaught TypeError when creating an empty application [\#3430](https://github.com/mesosphere/marathon/issues/3430)
- Race condition\(s\) in HttpEventActor [\#3403](https://github.com/mesosphere/marathon/issues/3403)
- Residents Task: Use count from LaunchQueue to determine how many tasks are still needed [\#3392](https://github.com/mesosphere/marathon/issues/3392)
- Adjust resource matching to include disk resources for local volumes [\#3391](https://github.com/mesosphere/marathon/issues/3391)
- Relative paths for dependencies not working anymore [\#3367](https://github.com/mesosphere/marathon/issues/3367)

**Closed issues:**

- Resident tasks: Various cleanup tasks [\#3474](https://github.com/mesosphere/marathon/issues/3474)
- Catch all responses with a statuscode  \> 300 [\#3457](https://github.com/mesosphere/marathon/issues/3457)
- Dialog ribbon colors not matching state [\#3446](https://github.com/mesosphere/marathon/issues/3446)
- Resident Tasks: Use a sensible upgradeStrategy by default [\#3442](https://github.com/mesosphere/marathon/issues/3442)
- Relative paths in dependencies [\#3439](https://github.com/mesosphere/marathon/issues/3439)
- App modal error highlighting issue [\#3436](https://github.com/mesosphere/marathon/issues/3436)
- Orphaned containers with docker 1.10.2 [\#3418](https://github.com/mesosphere/marathon/issues/3418)
- args in marathon file does not resolve env variables [\#3416](https://github.com/mesosphere/marathon/issues/3416)
- Validation of predicates [\#3413](https://github.com/mesosphere/marathon/issues/3413)
- v0.11.0 Version Update [\#3409](https://github.com/mesosphere/marathon/issues/3409)
- Improvements to Empty Groups [\#3383](https://github.com/mesosphere/marathon/issues/3383)
- Expose server-side validation errors in JSON editor [\#3360](https://github.com/mesosphere/marathon/issues/3360)
- Flaky HttpEventActorTest:  "A message is broadcast to all subscribers" [\#3183](https://github.com/mesosphere/marathon/issues/3183)
- Resident Tasks: Extend MarathonTask state [\#3041](https://github.com/mesosphere/marathon/issues/3041)

**Merged pull requests:**

- Raise UI version to 0.16.0 [\#3483](https://github.com/mesosphere/marathon/pull/3483) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fixes \#3392 and \#3477 - Residents Task: Use count from LaunchQueue to determine how many tasks are still needed [\#3475](https://github.com/mesosphere/marathon/pull/3475) ([kolloch](https://github.com/kolloch))
- Based on application definition a default residency is added if not a… [\#3454](https://github.com/mesosphere/marathon/pull/3454) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3439 - relative paths in dependencies validation. [\#3450](https://github.com/mesosphere/marathon/pull/3450) ([lexwbr](https://github.com/lexwbr))
- Add portDefinitions documentation [\#3444](https://github.com/mesosphere/marathon/pull/3444) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3442 by applying a different default upgrade strategy based on… [\#3443](https://github.com/mesosphere/marathon/pull/3443) ([aquamatthias](https://github.com/aquamatthias))
- If residency is defined, there must be also persistent volumes and vi… [\#3441](https://github.com/mesosphere/marathon/pull/3441) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3438 - Remove spurious reservations/volumes [\#3437](https://github.com/mesosphere/marathon/pull/3437) ([kolloch](https://github.com/kolloch))
- Remove unused code [\#3433](https://github.com/mesosphere/marathon/pull/3433) ([gkleiman](https://github.com/gkleiman))
- Towards \#3221 additional review changes [\#3428](https://github.com/mesosphere/marathon/pull/3428) ([meichstedt](https://github.com/meichstedt))
- Fixes \#3413 - replaces predicate validation with simpler representation. [\#3415](https://github.com/mesosphere/marathon/pull/3415) ([lexwbr](https://github.com/lexwbr))
- Final edits based on MatthiasV's comments [\#3348](https://github.com/mesosphere/marathon/pull/3348) ([sascala](https://github.com/sascala))
- Fixes \#3169 by validating the resource values of the AppDefinition. [\#3193](https://github.com/mesosphere/marathon/pull/3193) ([aquamatthias](https://github.com/aquamatthias))

## [v0.10.2-RC8](https://github.com/mesosphere/marathon/tree/v0.10.2-RC8) (2016-03-09)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.3...v0.10.2-RC8)

**Implemented enhancements:**

- Inaccurate Statistics [\#3275](https://github.com/mesosphere/marathon/issues/3275)
- Add volumes tab to application page [\#3240](https://github.com/mesosphere/marathon/issues/3240)
- Allow embed fields in /v2/groups endpoint [\#2404](https://github.com/mesosphere/marathon/issues/2404)
- Set DiscoveryInfo for created TaskInfo messages [\#1866](https://github.com/mesosphere/marathon/issues/1866)
- Allow users to create new groups [\#966](https://github.com/mesosphere/marathon/issues/966)

**Fixed bugs:**

- Resource leakage in the Webui? [\#3408](https://github.com/mesosphere/marathon/issues/3408)
- The app `cmd` error response is not properly parsed and displayed [\#3393](https://github.com/mesosphere/marathon/issues/3393)
- Regression: remove error state upon typing [\#3389](https://github.com/mesosphere/marathon/issues/3389)
- Creating an empty group using an existing app ID should return 409 [\#3385](https://github.com/mesosphere/marathon/issues/3385)
- Marathon should remove the FrameworkId for special mesos errors [\#3377](https://github.com/mesosphere/marathon/issues/3377)
- Port indices notation in validation errors is not consistent [\#3339](https://github.com/mesosphere/marathon/issues/3339)
- Path in health checks validation failure results is broken [\#3338](https://github.com/mesosphere/marathon/issues/3338)
- Marathon UI hangs after being open for a while [\#3304](https://github.com/mesosphere/marathon/issues/3304)
- Cannot remove a constraint [\#3233](https://github.com/mesosphere/marathon/issues/3233)
- Aggregate scalar resources across roles [\#1606](https://github.com/mesosphere/marathon/issues/1606)
- Fixes \#3402 - Fix race conditions in HttpEventActor [\#3402](https://github.com/mesosphere/marathon/pull/3402) ([kolloch](https://github.com/kolloch))
- Wait for taskOp acknowledgements during shutdown in AppTaskLaunchActor [\#3396](https://github.com/mesosphere/marathon/pull/3396) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Resident Tasks: Aggresively remove spurious volumes/reservations [\#3438](https://github.com/mesosphere/marathon/issues/3438)
- NPE in `AppStartActorTest` [\#3427](https://github.com/mesosphere/marathon/issues/3427)
- Docker example in Marathon Application Basics page fails to run [\#3399](https://github.com/mesosphere/marathon/issues/3399)
- Cleanup the docker container section in the add/edit application modal [\#3395](https://github.com/mesosphere/marathon/issues/3395)
- Empty JSON being added to JSON editor [\#3394](https://github.com/mesosphere/marathon/issues/3394)
- Don't rely on the presence of fields in task definitions [\#3376](https://github.com/mesosphere/marathon/issues/3376)
- Document new error definition introduced in \#3241 [\#3371](https://github.com/mesosphere/marathon/issues/3371)
- Don't render hidden panes [\#3363](https://github.com/mesosphere/marathon/issues/3363)
- Allow sending notifications of crashed tasks [\#3351](https://github.com/mesosphere/marathon/issues/3351)
- Don't inspect app configuration to determine modal type [\#3350](https://github.com/mesosphere/marathon/issues/3350)
- what does the disk parameter use for? [\#3349](https://github.com/mesosphere/marathon/issues/3349)
- Resident Tasks: leverage Reservation Labels [\#3344](https://github.com/mesosphere/marathon/issues/3344)
- Passing SRV records \(Service DiscoveryInfo\) for non-docker tasks [\#3342](https://github.com/mesosphere/marathon/issues/3342)
- Refactor service error parsing to new structure [\#3337](https://github.com/mesosphere/marathon/issues/3337)
- Environmental variables for Marathon Authentication [\#3329](https://github.com/mesosphere/marathon/issues/3329)
- Nicer PortDefinition validation is needed [\#3328](https://github.com/mesosphere/marathon/issues/3328)
- Resident Tasks: enable framework auth for integration tests [\#3313](https://github.com/mesosphere/marathon/issues/3313)
- Resident Tasks: adjust task counts and take reservations into account [\#3306](https://github.com/mesosphere/marathon/issues/3306)
- Redesign Create/Edit modal and add JSON editor toggle [\#3305](https://github.com/mesosphere/marathon/issues/3305)
- Resident Tasks: render local volumes in the task endpoint [\#3273](https://github.com/mesosphere/marathon/issues/3273)
- Resident Tasks: Take Task.launched for all Task.Id.mesosTaskId into consideration [\#3253](https://github.com/mesosphere/marathon/issues/3253)
- Simplify port management in Marathon UI [\#3243](https://github.com/mesosphere/marathon/issues/3243)
- Serverside validation messages are inconsistent [\#3241](https://github.com/mesosphere/marathon/issues/3241)
- Resident Tasks: Restrictive AppDefinition validation [\#3231](https://github.com/mesosphere/marathon/issues/3231)
- Filter apps by attached volumes [\#3157](https://github.com/mesosphere/marathon/issues/3157)
- Show groups as part of search results [\#3127](https://github.com/mesosphere/marathon/issues/3127)
- Resident Tasks: Adjust App handling workflow [\#3043](https://github.com/mesosphere/marathon/issues/3043)
- Resident Tasks: Offer matching [\#3042](https://github.com/mesosphere/marathon/issues/3042)
- Frontend build includes many unnecessary files [\#1120](https://github.com/mesosphere/marathon/issues/1120)

**Merged pull requests:**

- Edit metrics [\#3609](https://github.com/mesosphere/marathon/pull/3609) ([sascala](https://github.com/sascala))
- Backport Leadership fixes [\#3429](https://github.com/mesosphere/marathon/pull/3429) ([aquamatthias](https://github.com/aquamatthias))
- Add DueDil to list of companies using Marathon [\#3422](https://github.com/mesosphere/marathon/pull/3422) ([ltrabuco](https://github.com/ltrabuco))
- Fixes \#3344 - label reservations and match against the labels [\#3414](https://github.com/mesosphere/marathon/pull/3414) ([kolloch](https://github.com/kolloch))
- Towards \#3221 reservation timeouts [\#3411](https://github.com/mesosphere/marathon/pull/3411) ([meichstedt](https://github.com/meichstedt))
- Remove unused MarathonTasks code [\#3410](https://github.com/mesosphere/marathon/pull/3410) ([kolloch](https://github.com/kolloch))
- Fixes \#1606 and \#3391 - Fixed resource matching for resident tasks [\#3404](https://github.com/mesosphere/marathon/pull/3404) ([kolloch](https://github.com/kolloch))
- Upgrade to Mesos 0.28.0-rc1 [\#3401](https://github.com/mesosphere/marathon/pull/3401) ([kolloch](https://github.com/kolloch))
- Fixes \#3385 - groups with same IDs as apps should not be created. [\#3398](https://github.com/mesosphere/marathon/pull/3398) ([lexwbr](https://github.com/lexwbr))
- Fixes \#3338 - provide better HealthCheck validation [\#3397](https://github.com/mesosphere/marathon/pull/3397) ([lexwbr](https://github.com/lexwbr))
- Fixes \#3339 - path output format of object validation is identical to JSON structure [\#3387](https://github.com/mesosphere/marathon/pull/3387) ([lexwbr](https://github.com/lexwbr))
- Fixes \#3377 Remove the FrameworkId in case of a specific error message from Mesos [\#3384](https://github.com/mesosphere/marathon/pull/3384) ([aquamatthias](https://github.com/aquamatthias))
- Remove TaskOpProcessor.Action.Unlaunched [\#3375](https://github.com/mesosphere/marathon/pull/3375) ([kolloch](https://github.com/kolloch))
- TaskOpFactory, scaladoc fixes [\#3374](https://github.com/mesosphere/marathon/pull/3374) ([kolloch](https://github.com/kolloch))
- Fixes \#2404 by introducing GroupInfo for rendering groups and using A… [\#3370](https://github.com/mesosphere/marathon/pull/3370) ([aquamatthias](https://github.com/aquamatthias))
- DELETE /v2/apps/\<unknown-app\> returns a 404 if authorized [\#3362](https://github.com/mesosphere/marathon/pull/3362) ([gkleiman](https://github.com/gkleiman))
- Fixes \#3231 by introducing a validator for DeploymentPlan [\#3359](https://github.com/mesosphere/marathon/pull/3359) ([aquamatthias](https://github.com/aquamatthias))
- Partly resolves \#3043 Resident tasks deployment integration tests [\#3358](https://github.com/mesosphere/marathon/pull/3358) ([meichstedt](https://github.com/meichstedt))
- Edit index [\#3347](https://github.com/mesosphere/marathon/pull/3347) ([sascala](https://github.com/sascala))
- \(small\) edits to ssl-basic-access-authentication.md [\#3346](https://github.com/mesosphere/marathon/pull/3346) ([sascala](https://github.com/sascala))
- \(tiny\) edits to service-discovery-load-balancing.md [\#3345](https://github.com/mesosphere/marathon/pull/3345) ([sascala](https://github.com/sascala))
- Fixes \#3328 - nicer way of PortDefinition validation. [\#3330](https://github.com/mesosphere/marathon/pull/3330) ([lexwbr](https://github.com/lexwbr))
- Rename design doc [\#3327](https://github.com/mesosphere/marathon/pull/3327) ([sascala](https://github.com/sascala))
- Update docs.html [\#3326](https://github.com/mesosphere/marathon/pull/3326) ([sascala](https://github.com/sascala))
- DataMan is powered by marathon [\#3323](https://github.com/mesosphere/marathon/pull/3323) ([vitan](https://github.com/vitan))
- Resolves \#3313 by introducing framework authentication for resident tasks [\#3314](https://github.com/mesosphere/marathon/pull/3314) ([meichstedt](https://github.com/meichstedt))
- Add Criteo to companies using Mesosphere Marathon [\#3312](https://github.com/mesosphere/marathon/pull/3312) ([pierrecdn](https://github.com/pierrecdn))
- Fixes \#3308 by introducing the provided CLI parameter from AllConf [\#3309](https://github.com/mesosphere/marathon/pull/3309) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3306 by introducing special purpose methods in TaskTracker [\#3307](https://github.com/mesosphere/marathon/pull/3307) ([aquamatthias](https://github.com/aquamatthias))
- Added leaderDuration metric [\#3303](https://github.com/mesosphere/marathon/pull/3303) ([prsekar](https://github.com/prsekar))
- Add support for port names and labels [\#3302](https://github.com/mesosphere/marathon/pull/3302) ([gkleiman](https://github.com/gkleiman))
- WIP on resident task offer matching and reserve/launch operations [\#3292](https://github.com/mesosphere/marathon/pull/3292) ([meichstedt](https://github.com/meichstedt))
- Fixes \#3241 - consistent JSON error output. [\#3255](https://github.com/mesosphere/marathon/pull/3255) ([lexwbr](https://github.com/lexwbr))
- Auth plugin interface refactoring [\#3230](https://github.com/mesosphere/marathon/pull/3230) ([gkleiman](https://github.com/gkleiman))

## [v0.15.3](https://github.com/mesosphere/marathon/tree/v0.15.3) (2016-02-23)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.2...v0.15.3)

**Implemented enhancements:**

- marathon UI: alphabetical environment variables [\#3269](https://github.com/mesosphere/marathon/issues/3269)
- Support port names and labels [\#3263](https://github.com/mesosphere/marathon/issues/3263)
- Move docker volumes to volumes section [\#3239](https://github.com/mesosphere/marathon/issues/3239)

**Fixed bugs:**

- tried to kill an existing app, said it doesn't exist even though it does [\#3251](https://github.com/mesosphere/marathon/issues/3251)
- Regression: group name no longer pre-filled in app modal [\#3218](https://github.com/mesosphere/marathon/issues/3218)
- Regression: changes in JSON editor are not reflected [\#3215](https://github.com/mesosphere/marathon/issues/3215)
- App creation modal ports field default value does not reflect service default value [\#3214](https://github.com/mesosphere/marathon/issues/3214)
- "Apply" button is broken \(sending both uris and fetch\) [\#3172](https://github.com/mesosphere/marathon/issues/3172)

**Closed issues:**

- Resident Tasks: make sure correct CLI parameter are provided as part of validation. [\#3308](https://github.com/mesosphere/marathon/issues/3308)
- Specific role required by app is not matched by default resource role: "\*" [\#3290](https://github.com/mesosphere/marathon/issues/3290)
- java.lang.UnsatisfiedLinkError: /usr/lib/libmesos-0.26.0.so: libgcrypt.so.20 [\#3288](https://github.com/mesosphere/marathon/issues/3288)
- Resident Tasks: offer matching priority should keep reserved resources into account [\#3266](https://github.com/mesosphere/marathon/issues/3266)
- Resident Tasks: Treat status updates correctly [\#3232](https://github.com/mesosphere/marathon/issues/3232)
- Add support for Local Volumes in Create/Edit modal [\#3155](https://github.com/mesosphere/marathon/issues/3155)
- Develop a process to load and register plugins [\#3108](https://github.com/mesosphere/marathon/issues/3108)
- Implement a PluginDispatcher, PluginStore and PluginComponent [\#3107](https://github.com/mesosphere/marathon/issues/3107)
- Create a UI Plugin Example [\#2926](https://github.com/mesosphere/marathon/issues/2926)
- Give us links to binary tarballs on releases page [\#2716](https://github.com/mesosphere/marathon/issues/2716)

**Merged pull requests:**

- Raise UI version to 0.15.6 [\#3310](https://github.com/mesosphere/marathon/pull/3310) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fix markdown emphasis mistakes for notes in task env var doc. [\#3279](https://github.com/mesosphere/marathon/pull/3279) ([timoreimann](https://github.com/timoreimann))
- More consistent error messages \#2277 [\#3278](https://github.com/mesosphere/marathon/pull/3278) ([alenkacz](https://github.com/alenkacz))
- Fixes \#3251 by making sure the app exists, even in the case there are… [\#3277](https://github.com/mesosphere/marathon/pull/3277) ([aquamatthias](https://github.com/aquamatthias))
- Replace MarathonTask by Task in the /v2/ endpoints [\#3274](https://github.com/mesosphere/marathon/pull/3274) ([aquamatthias](https://github.com/aquamatthias))
- Update artifact-store.md [\#3270](https://github.com/mesosphere/marathon/pull/3270) ([sascala](https://github.com/sascala))
- Remove deprecated task tracker methods. [\#3268](https://github.com/mesosphere/marathon/pull/3268) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3266 by introducing an optional precedence \(PathId\) for OfferMatchers. [\#3267](https://github.com/mesosphere/marathon/pull/3267) ([aquamatthias](https://github.com/aquamatthias))
- Updated mesos-utils dependency version to 0.27.0 [\#3265](https://github.com/mesosphere/marathon/pull/3265) ([gkleiman](https://github.com/gkleiman))
- Added Mesos Library example for linux. [\#3260](https://github.com/mesosphere/marathon/pull/3260) ([joerg84](https://github.com/joerg84))
- Bump to mesos 0.27.0 [\#3259](https://github.com/mesosphere/marathon/pull/3259) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3232 by handling terminating status updates for resident tasks: [\#3258](https://github.com/mesosphere/marathon/pull/3258) ([aquamatthias](https://github.com/aquamatthias))
- Fix unrendered examples in docs [\#3256](https://github.com/mesosphere/marathon/pull/3256) ([janisz](https://github.com/janisz))
- Update ssl-basic-access-authentication.md [\#3254](https://github.com/mesosphere/marathon/pull/3254) ([knesenko](https://github.com/knesenko))
- Update service-discovery-load-balancing.md [\#3250](https://github.com/mesosphere/marathon/pull/3250) ([sascala](https://github.com/sascala))
- Update docs version to 0.15.2 [\#3249](https://github.com/mesosphere/marathon/pull/3249) ([philipnrmn](https://github.com/philipnrmn))
- Clarify behavior of portIndex and port health check options. [\#3238](https://github.com/mesosphere/marathon/pull/3238) ([timoreimann](https://github.com/timoreimann))
- Set new \(sensible\) default values [\#3229](https://github.com/mesosphere/marathon/pull/3229) ([aquamatthias](https://github.com/aquamatthias))
- Resolves \#3200 by adding an integration test for persistent volumes [\#3227](https://github.com/mesosphere/marathon/pull/3227) ([meichstedt](https://github.com/meichstedt))
- Enable http based plugin extensions [\#3106](https://github.com/mesosphere/marathon/pull/3106) ([aquamatthias](https://github.com/aquamatthias))

## [v0.15.2](https://github.com/mesosphere/marathon/tree/v0.15.2) (2016-02-16)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.2...v0.15.2)

**Fixed bugs:**

- Contextual bar is a different size in search result view [\#3134](https://github.com/mesosphere/marathon/issues/3134)

**Closed issues:**

- Treat "value" attribute in server-side validation errors as general error [\#3242](https://github.com/mesosphere/marathon/issues/3242)
- hostPort to containerPort mapping [\#3234](https://github.com/mesosphere/marathon/issues/3234)
- Adapt default Mem/CPU settings [\#3192](https://github.com/mesosphere/marathon/issues/3192)

**Merged pull requests:**

- Update changelog with 0.15.2 fixes [\#3247](https://github.com/mesosphere/marathon/pull/3247) ([philipnrmn](https://github.com/philipnrmn))
- Prepare for 0.15.2 release [\#3246](https://github.com/mesosphere/marathon/pull/3246) ([philipnrmn](https://github.com/philipnrmn))
- Fix the json key in documentation [\#3236](https://github.com/mesosphere/marathon/pull/3236) ([alenkacz](https://github.com/alenkacz))

## [v0.14.2](https://github.com/mesosphere/marathon/tree/v0.14.2) (2016-02-12)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.2-RC1...v0.14.2)

**Merged pull requests:**

- Fix naming irregularities in TaskCreationHandlerAndUpdaterDelegateTest [\#3226](https://github.com/mesosphere/marathon/pull/3226) ([meichstedt](https://github.com/meichstedt))
- Fixes \#3209 - fixes misplacement of dot in validation messages. [\#3211](https://github.com/mesosphere/marathon/pull/3211) ([lexwbr](https://github.com/lexwbr))
- Migrate upgrade package to new Task and get rid of TaskIDUtil [\#3210](https://github.com/mesosphere/marathon/pull/3210) ([kolloch](https://github.com/kolloch))

## [v0.15.2-RC1](https://github.com/mesosphere/marathon/tree/v0.15.2-RC1) (2016-02-11)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.1...v0.15.2-RC1)

**Implemented enhancements:**

- Fixes \#3161 - Improve error message for invalid constraints [\#3162](https://github.com/mesosphere/marathon/pull/3162) ([gkleiman](https://github.com/gkleiman))

**Fixed bugs:**

- When accepting an Offer, no offer timeout should be applied. [\#3216](https://github.com/mesosphere/marathon/issues/3216)
- Validation point position for containers is placed wrong according to \#3175 [\#3209](https://github.com/mesosphere/marathon/issues/3209)
- Header and suspend icon have size problem [\#3174](https://github.com/mesosphere/marathon/issues/3174)
- Possible to start app with negative resources [\#3169](https://github.com/mesosphere/marathon/issues/3169)
- Interrupted scaling operations can leave the health bar in an incorrect state [\#3133](https://github.com/mesosphere/marathon/issues/3133)
- Updating Environment Variables Sometimes Deletes Entries [\#3102](https://github.com/mesosphere/marathon/issues/3102)
- Marathon cannot schedule task when log writing is blocked [\#2985](https://github.com/mesosphere/marathon/issues/2985)

**Closed issues:**

- Resident Tasks: Write Integration Tests [\#3200](https://github.com/mesosphere/marathon/issues/3200)
- How to reliably discover Marathon URL [\#3191](https://github.com/mesosphere/marathon/issues/3191)
- \[UI\] Cannot view/modify docker task 'args' [\#3159](https://github.com/mesosphere/marathon/issues/3159)
- Allow configuration of Resident Tasks [\#3039](https://github.com/mesosphere/marathon/issues/3039)
- Ports documentation [\#2236](https://github.com/mesosphere/marathon/issues/2236)

**Merged pull requests:**

- Towards \#3041 remove Task.launchCounter and add list of LocalVolumeIds [\#3219](https://github.com/mesosphere/marathon/pull/3219) ([meichstedt](https://github.com/meichstedt))
- Fixes \#3216 by setting the default offer timeout to 0 while accepting an offer. [\#3217](https://github.com/mesosphere/marathon/pull/3217) ([aquamatthias](https://github.com/aquamatthias))
- Towards \#3041 - better Tasks in health [\#3201](https://github.com/mesosphere/marathon/pull/3201) ([kolloch](https://github.com/kolloch))
- Fixes \#2985 by logging a specific message in case of timeout and using an async logger. [\#3199](https://github.com/mesosphere/marathon/pull/3199) ([aquamatthias](https://github.com/aquamatthias))
- Towards \#3041 - Introduced Task for TaskStatusUpdateStep [\#3198](https://github.com/mesosphere/marathon/pull/3198) ([kolloch](https://github.com/kolloch))
- Towards \#3041 - Use new Task for counts and some other things [\#3196](https://github.com/mesosphere/marathon/pull/3196) ([kolloch](https://github.com/kolloch))
- update mesosphere.io to mesosphere.com [\#3195](https://github.com/mesosphere/marathon/pull/3195) ([lloesche](https://github.com/lloesche))
- Towards \#3041 - Use new "Task" in more places instead of "MarathonTask" [\#3188](https://github.com/mesosphere/marathon/pull/3188) ([kolloch](https://github.com/kolloch))
- Resolves \#3039 API changes for Resident Tasks [\#3175](https://github.com/mesosphere/marathon/pull/3175) ([meichstedt](https://github.com/meichstedt))
- Ports documentation, fixes \#2236. [\#3166](https://github.com/mesosphere/marathon/pull/3166) ([ssk2](https://github.com/ssk2))

## [v0.15.1](https://github.com/mesosphere/marathon/tree/v0.15.1) (2016-02-08)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.1-RC1...v0.15.1)

**Implemented enhancements:**

- Refactor all stores that expose setters [\#3011](https://github.com/mesosphere/marathon/issues/3011)
- Advanced JSON editing mode in app modal [\#2049](https://github.com/mesosphere/marathon/issues/2049)

**Fixed bugs:**

- Marathon 0.15 error on bad application id is really bad [\#3164](https://github.com/mesosphere/marathon/issues/3164)
- Improve error message for invalid constraints [\#3161](https://github.com/mesosphere/marathon/issues/3161)
- Show 400 error for Constraints field [\#3160](https://github.com/mesosphere/marathon/issues/3160)
- ErrorIndicies use array out of bounds [\#3158](https://github.com/mesosphere/marathon/issues/3158)
- breaking API change on portIndex? [\#3140](https://github.com/mesosphere/marathon/issues/3140)
- Empty - non set-  application attributes are accidentaly submited by the UI [\#3054](https://github.com/mesosphere/marathon/issues/3054)

**Closed issues:**

- MarathonSchedulerActorTest FAILED. [\#3152](https://github.com/mesosphere/marathon/issues/3152)
- SBT fails to download api-console.jar when launching container from Dockerfile.development [\#3151](https://github.com/mesosphere/marathon/issues/3151)
- Refactor AppFormStore to have the app definition private [\#3148](https://github.com/mesosphere/marathon/issues/3148)

**Merged pull requests:**

- Raise UI version to 0.15.4 [\#3186](https://github.com/mesosphere/marathon/pull/3186) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Corrected example of max\_tasks\_per\_offer\(\_cycle\). [\#3181](https://github.com/mesosphere/marathon/pull/3181) ([joerg84](https://github.com/joerg84))
- Fixing path on developing doc [\#3180](https://github.com/mesosphere/marathon/pull/3180) ([jimenez](https://github.com/jimenez))
- Haproxy marathon bridge deprecated [\#3177](https://github.com/mesosphere/marathon/pull/3177) ([sascala](https://github.com/sascala))
- Fixes \#3140 - Also default to HealthCheck\#portIndex=0 when an app is updated [\#3173](https://github.com/mesosphere/marathon/pull/3173) ([gkleiman](https://github.com/gkleiman))
- Towards \#3041 - Representing all state relating to a task in TaskState [\#3171](https://github.com/mesosphere/marathon/pull/3171) ([kolloch](https://github.com/kolloch))
- Read environment variables from /etc/default/marathon file. [\#3168](https://github.com/mesosphere/marathon/pull/3168) ([aquamatthias](https://github.com/aquamatthias))

## [v0.15.1-RC1](https://github.com/mesosphere/marathon/tree/v0.15.1-RC1) (2016-02-03)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.0...v0.15.1-RC1)

**Implemented enhancements:**

- Fixes \#3141 - Upgrade Chaos to v0.8.4 [\#3146](https://github.com/mesosphere/marathon/pull/3146) ([gkleiman](https://github.com/gkleiman))

**Fixed bugs:**

- The application definition should be always post processed [\#3149](https://github.com/mesosphere/marathon/issues/3149)
- Jetty throws exception during load [\#3141](https://github.com/mesosphere/marathon/issues/3141)
- Marathon cannot deal with SCALAR values in mesos slave attributes. [\#1906](https://github.com/mesosphere/marathon/issues/1906)
- Fixes \#3139 - Do not restart unchanged apps [\#3145](https://github.com/mesosphere/marathon/pull/3145) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Introduce application getter in AppFormStore [\#3147](https://github.com/mesosphere/marathon/issues/3147)
- Marathon 0.15.0-1.0.457.ubuntu1404 forces redeploy of app all the time [\#3139](https://github.com/mesosphere/marathon/issues/3139)
- Problems with MARATHON\_APP\_LABELS and Docker-Containers [\#3137](https://github.com/mesosphere/marathon/issues/3137)
- Auto-link URLs in validation error messages [\#3082](https://github.com/mesosphere/marathon/issues/3082)
- Highlight sorted columns in the UI [\#3076](https://github.com/mesosphere/marathon/issues/3076)

**Merged pull requests:**

- Raise UI version to 0.15.3 [\#3150](https://github.com/mesosphere/marathon/pull/3150) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Update docs to latest version v0.15.0 [\#3144](https://github.com/mesosphere/marathon/pull/3144) ([meichstedt](https://github.com/meichstedt))
- Removed reference to deprecated state.json endpoint. [\#3135](https://github.com/mesosphere/marathon/pull/3135) ([joerg84](https://github.com/joerg84))

## [v0.15.0](https://github.com/mesosphere/marathon/tree/v0.15.0) (2016-02-01)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.1...v0.15.0)

**Fixed bugs:**

- DCOS tests for Marathon are failing [\#2970](https://github.com/mesosphere/marathon/issues/2970)
- './haproxy-marathon-bridge install\_haproxy\_system' fails if 'redhat-lsb-core' package is not installed on RHEL, CentOS [\#2446](https://github.com/mesosphere/marathon/issues/2446)
- Typo in documentation [\#3104](https://github.com/mesosphere/marathon/pull/3104) ([tgermain](https://github.com/tgermain))

**Closed issues:**

- No redirect to current master [\#3126](https://github.com/mesosphere/marathon/issues/3126)
- Shaky HttpEventActorTest "If a message is send to a slow subscriber" [\#3120](https://github.com/mesosphere/marathon/issues/3120)
- Use acceptOffers to launch tasks [\#3040](https://github.com/mesosphere/marathon/issues/3040)
- Add help icons linking to docs for status and health [\#2907](https://github.com/mesosphere/marathon/issues/2907)

**Merged pull requests:**

- Add link to UX Research capture form [\#3123](https://github.com/mesosphere/marathon/pull/3123) ([leemunroe](https://github.com/leemunroe))
- Fixes \#3120 by taking the time before making the request. [\#3121](https://github.com/mesosphere/marathon/pull/3121) ([aquamatthias](https://github.com/aquamatthias))
- Hack to make it possible to run integration tests [\#3119](https://github.com/mesosphere/marathon/pull/3119) ([kolloch](https://github.com/kolloch))
- Fix non-sensical assert [\#3118](https://github.com/mesosphere/marathon/pull/3118) ([kolloch](https://github.com/kolloch))
- Type annotations to make compilation in Intellij work [\#3117](https://github.com/mesosphere/marathon/pull/3117) ([kolloch](https://github.com/kolloch))
- Raise UI version to 0.15.2 for the next Marathon 0.15 release [\#3116](https://github.com/mesosphere/marathon/pull/3116) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fixes \#3040 - use acceptOffer to launch tasks [\#3115](https://github.com/mesosphere/marathon/pull/3115) ([kolloch](https://github.com/kolloch))
- Add link to UX Research capture form [\#3112](https://github.com/mesosphere/marathon/pull/3112) ([leemunroe](https://github.com/leemunroe))

## [v0.13.1](https://github.com/mesosphere/marathon/tree/v0.13.1) (2016-01-27)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.1...v0.13.1)

**Closed issues:**

- Move application Search Bar to the Header [\#3017](https://github.com/mesosphere/marathon/issues/3017)

## [v0.14.1](https://github.com/mesosphere/marathon/tree/v0.14.1) (2016-01-27)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.0-RC3...v0.14.1)

**Closed issues:**

- Always show download button for logs [\#3078](https://github.com/mesosphere/marathon/issues/3078)

## [v0.15.0-RC3](https://github.com/mesosphere/marathon/tree/v0.15.0-RC3) (2016-01-27)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC7...v0.15.0-RC3)

**Fixed bugs:**

- Event callbacks hold on to unresponsive hosts [\#3047](https://github.com/mesosphere/marathon/issues/3047)

**Merged pull requests:**

- Update Marathon UI version to 0.14.3 [\#3110](https://github.com/mesosphere/marathon/pull/3110) ([philipnrmn](https://github.com/philipnrmn))
- \[Master\] Fixes \#3047 by introducing a exponential backoff for unresponsive hosts. [\#3101](https://github.com/mesosphere/marathon/pull/3101) ([aquamatthias](https://github.com/aquamatthias))

## [v0.10.2-RC7](https://github.com/mesosphere/marathon/tree/v0.10.2-RC7) (2016-01-27)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.0-RC2...v0.10.2-RC7)

**Implemented enhancements:**

- Add coverage target to UI scripts [\#2217](https://github.com/mesosphere/marathon/issues/2217)

**Fixed bugs:**

- Don't display "Create an Application" together with "Loading error" [\#3093](https://github.com/mesosphere/marathon/issues/3093)
- Task info is broken in 0.14.0-RC2 [\#2973](https://github.com/mesosphere/marathon/issues/2973)

**Closed issues:**

- MarathonSchedulerActorTest is shaky [\#3103](https://github.com/mesosphere/marathon/issues/3103)
- Document framework authentication mechanism [\#3095](https://github.com/mesosphere/marathon/issues/3095)
- TooltipComponent is too tightly coupled with its usage [\#3094](https://github.com/mesosphere/marathon/issues/3094)
- Document new fetch field in AppDefinition [\#3074](https://github.com/mesosphere/marathon/issues/3074)
- Why marathon assign a random port when network is HOST mode [\#3049](https://github.com/mesosphere/marathon/issues/3049)
- Improve Tests: Document current tests [\#2929](https://github.com/mesosphere/marathon/issues/2929)
- Improve Tests: Split out Unit Tests into their own files [\#2928](https://github.com/mesosphere/marathon/issues/2928)
- Add App Health definitions to Docs [\#2920](https://github.com/mesosphere/marathon/issues/2920)
- UI webjar SNAPSHOT is cached too long [\#2145](https://github.com/mesosphere/marathon/issues/2145)
- Use portals for alert-type modals [\#2090](https://github.com/mesosphere/marathon/issues/2090)

**Merged pull requests:**

- Add link from README.md to Marathon UI page [\#3105](https://github.com/mesosphere/marathon/pull/3105) ([kolloch](https://github.com/kolloch))
- Resolves \#3095 by documenting framework authentication [\#3100](https://github.com/mesosphere/marathon/pull/3100) ([meichstedt](https://github.com/meichstedt))
- Prefer Scala Numeric classes over Java classes [\#3098](https://github.com/mesosphere/marathon/pull/3098) ([gkleiman](https://github.com/gkleiman))
- Add deprecation warnings for fetch [\#3097](https://github.com/mesosphere/marathon/pull/3097) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Add Application Health State reference to UI docs [\#3090](https://github.com/mesosphere/marathon/pull/3090) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Added 0.15 UI changes [\#3089](https://github.com/mesosphere/marathon/pull/3089) ([meichstedt](https://github.com/meichstedt))
- Bump docs version to 0.14 [\#3088](https://github.com/mesosphere/marathon/pull/3088) ([philipnrmn](https://github.com/philipnrmn))
- Fixes \#2692 - Document important metrics [\#3084](https://github.com/mesosphere/marathon/pull/3084) ([kolloch](https://github.com/kolloch))
- Fixes \#3074 by describing the model in AppsResource\_create, change th… [\#3083](https://github.com/mesosphere/marathon/pull/3083) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#3047 by introducing a exponential backoff for unresponsive hosts. [\#3072](https://github.com/mesosphere/marathon/pull/3072) ([aquamatthias](https://github.com/aquamatthias))
- Update build.scala for 0.16.0-snapshot [\#3037](https://github.com/mesosphere/marathon/pull/3037) ([Poltergeist](https://github.com/Poltergeist))

## [v0.15.0-RC2](https://github.com/mesosphere/marathon/tree/v0.15.0-RC2) (2016-01-25)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.15.0-RC1...v0.15.0-RC2)

**Closed issues:**

- Unknown server error, could not create or apply app. [\#3033](https://github.com/mesosphere/marathon/issues/3033)
- haproxy-marathon-bridge script should not call sudo when executing as root [\#3008](https://github.com/mesosphere/marathon/issues/3008)
- haproxy-marathon-bridge script should not be run from install path when in install mode [\#3007](https://github.com/mesosphere/marathon/issues/3007)

**Merged pull requests:**

- raise marathon ui version to 0.15.1 [\#3075](https://github.com/mesosphere/marathon/pull/3075) ([Poltergeist](https://github.com/Poltergeist))
- Add checks to see if the current user is root before using sudo. Also… [\#3009](https://github.com/mesosphere/marathon/pull/3009) ([jlamillan](https://github.com/jlamillan))

## [v0.15.0-RC1](https://github.com/mesosphere/marathon/tree/v0.15.0-RC1) (2016-01-22)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.0...v0.15.0-RC1)

**Implemented enhancements:**

- Add support for the new fetcher cache in Mesos 0.23 [\#1953](https://github.com/mesosphere/marathon/issues/1953)

**Fixed bugs:**

- can't ⌘+C or Ctrl+C on the Marathon page as it launches "create" dialog [\#3065](https://github.com/mesosphere/marathon/issues/3065)
- Labels dropdown menu not showing up [\#3064](https://github.com/mesosphere/marathon/issues/3064)
- After scaling a healthy app to 0, it appears to be Infinity% overcapacity [\#3063](https://github.com/mesosphere/marathon/issues/3063)
- AppDefinition config edit dialog broken [\#3055](https://github.com/mesosphere/marathon/issues/3055)
- Can't add dynamic ports using PUT [\#3051](https://github.com/mesosphere/marathon/issues/3051)
- \* [\#3048](https://github.com/mesosphere/marathon/issues/3048)
- \[master\] Deadlock or something similar while waiting for TaskTracker.list [\#2997](https://github.com/mesosphere/marathon/issues/2997)
- Don't log giant port lists [\#2938](https://github.com/mesosphere/marathon/issues/2938)
- Marathon sometimes tries \(and fails\) to assign duplicated service ports. [\#2868](https://github.com/mesosphere/marathon/issues/2868)
- Create app failed when there're multiple same word in the app id [\#2855](https://github.com/mesosphere/marathon/issues/2855)
- Fixes \#3051 - Improve service ports allocation [\#3052](https://github.com/mesosphere/marathon/pull/3052) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2868 - Don't assign duplicated service ports [\#3038](https://github.com/mesosphere/marathon/pull/3038) ([gkleiman](https://github.com/gkleiman))
- Mark lock aquisitions as blocking [\#3026](https://github.com/mesosphere/marathon/pull/3026) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- No point in collecting nameservers [\#3053](https://github.com/mesosphere/marathon/issues/3053)
- Better search result ranking and fuzzy matching [\#3018](https://github.com/mesosphere/marathon/issues/3018)
- Document all UI coding guidelines [\#2910](https://github.com/mesosphere/marathon/issues/2910)
- Document the most important metrics [\#2692](https://github.com/mesosphere/marathon/issues/2692)
- Rewrite Scheduler \(TaskQueue, TaskTracker\) to not have mutable shared state and race conditions [\#1640](https://github.com/mesosphere/marathon/issues/1640)
- Create integration tests starting apps via docker [\#1604](https://github.com/mesosphere/marathon/issues/1604)

**Merged pull requests:**

- Updated changelog for 0.15 [\#3069](https://github.com/mesosphere/marathon/pull/3069) ([meichstedt](https://github.com/meichstedt))
- tiny markdown change [\#3066](https://github.com/mesosphere/marathon/pull/3066) ([sascala](https://github.com/sascala))
- Fixes \#2938 - do not log giant port lists [\#3046](https://github.com/mesosphere/marathon/pull/3046) ([lexwbr](https://github.com/lexwbr))
- Convert some sync TaskTracker calls to async [\#3028](https://github.com/mesosphere/marathon/pull/3028) ([kolloch](https://github.com/kolloch))
- Fix constraints definition schema [\#3027](https://github.com/mesosphere/marathon/pull/3027) ([janisz](https://github.com/janisz))
- Move the haproxy-marathon-bridge into examples directory and add a deprecation warning [\#3023](https://github.com/mesosphere/marathon/pull/3023) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2855 - app creation failing, if path contains same name multiple times [\#3015](https://github.com/mesosphere/marathon/pull/3015) ([lexwbr](https://github.com/lexwbr))
- Fixes \#1604 - Add simple Docker integration tests [\#2887](https://github.com/mesosphere/marathon/pull/2887) ([gkleiman](https://github.com/gkleiman))

## [v0.14.0](https://github.com/mesosphere/marathon/tree/v0.14.0) (2016-01-19)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.0-RC4...v0.14.0)

**Closed issues:**

- Consistent naming for TaskTracker and data methods [\#3003](https://github.com/mesosphere/marathon/issues/3003)
- How to change default backOff for all apps? [\#2999](https://github.com/mesosphere/marathon/issues/2999)
- docker pull a remote image conflict [\#2998](https://github.com/mesosphere/marathon/issues/2998)
- Optimize AppInfoBase to query TaskTracker once [\#2990](https://github.com/mesosphere/marathon/issues/2990)
- Add loading animation to loading states [\#2969](https://github.com/mesosphere/marathon/issues/2969)
- Group Deployments look strange [\#2947](https://github.com/mesosphere/marathon/issues/2947)
- Revisit variables.less to minimize variable creep [\#2946](https://github.com/mesosphere/marathon/issues/2946)
- Change validation routines to non-BeanValidation ones [\#2735](https://github.com/mesosphere/marathon/issues/2735)
- Get rid of V2 model objects [\#2426](https://github.com/mesosphere/marathon/issues/2426)

**Merged pull requests:**

- Update v0.14.0 changelog [\#3024](https://github.com/mesosphere/marathon/pull/3024) ([gkleiman](https://github.com/gkleiman))
- Fixed \#3003 - Consistent names for the TaskTracker interface [\#3013](https://github.com/mesosphere/marathon/pull/3013) ([kolloch](https://github.com/kolloch))
- Make sure to not match on every zk option. [\#3006](https://github.com/mesosphere/marathon/pull/3006) ([cmluciano](https://github.com/cmluciano))
- Mark blocking calls in MarathonSchedulerService [\#3002](https://github.com/mesosphere/marathon/pull/3002) ([kolloch](https://github.com/kolloch))
- Allow obtaining client IP in authe plugin [\#2996](https://github.com/mesosphere/marathon/pull/2996) ([janisz](https://github.com/janisz))
- Fixes \#2990 - Optimize some calls to the TaskTracker  [\#2995](https://github.com/mesosphere/marathon/pull/2995) ([kolloch](https://github.com/kolloch))
- Fixes \#2989 - report total task count metrics [\#2994](https://github.com/mesosphere/marathon/pull/2994) ([kolloch](https://github.com/kolloch))
- Fixes \#2426 - get rid of v2 model objects [\#2978](https://github.com/mesosphere/marathon/pull/2978) ([lexwbr](https://github.com/lexwbr))
- Fixes \#2927 - cap maximum number of parallel status updates [\#2959](https://github.com/mesosphere/marathon/pull/2959) ([kolloch](https://github.com/kolloch))

## [v0.14.0-RC4](https://github.com/mesosphere/marathon/tree/v0.14.0-RC4) (2016-01-14)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.0-RC3...v0.14.0-RC4)

**Implemented enhancements:**

- Change storage backend to use replicated log [\#364](https://github.com/mesosphere/marathon/issues/364)

**Fixed bugs:**

- Failed migration 0.11.1 -\> 0.14.0-RC3 [\#2984](https://github.com/mesosphere/marathon/issues/2984)
- Double offerLeadership invocation after driver failure [\#2982](https://github.com/mesosphere/marathon/issues/2982)
- Fixes \#2982 - synchronize service state methods of MarathonSchedulerS… [\#2983](https://github.com/mesosphere/marathon/pull/2983) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Report task count metrics [\#2989](https://github.com/mesosphere/marathon/issues/2989)
- Marathon shows wrong ports in task view [\#2987](https://github.com/mesosphere/marathon/issues/2987)
- how can I see the marathon deploy log [\#2986](https://github.com/mesosphere/marathon/issues/2986)
- Add more inline task information [\#2972](https://github.com/mesosphere/marathon/issues/2972)
- PopoverComponent should only be rendered if visible [\#2967](https://github.com/mesosphere/marathon/issues/2967)

**Merged pull requests:**

- Raise Marathon UI to version 0.14.2 [\#2992](https://github.com/mesosphere/marathon/pull/2992) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fixes \#2984 by considering already existing framework:id node before … [\#2991](https://github.com/mesosphere/marathon/pull/2991) ([meichstedt](https://github.com/meichstedt))
- Improve TaskReplaceActorTest "Wait until the tasks are killed" [\#2979](https://github.com/mesosphere/marathon/pull/2979) ([kolloch](https://github.com/kolloch))
- Optimize TaskResource [\#2964](https://github.com/mesosphere/marathon/pull/2964) ([kolloch](https://github.com/kolloch))

## [v0.14.0-RC3](https://github.com/mesosphere/marathon/tree/v0.14.0-RC3) (2016-01-13)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.0-RC2...v0.14.0-RC3)

**Implemented enhancements:**

- Allow users to scale a group [\#2944](https://github.com/mesosphere/marathon/issues/2944)
- Improve action context menu button [\#2936](https://github.com/mesosphere/marathon/issues/2936)
- Update and improve dialog messages [\#2909](https://github.com/mesosphere/marathon/issues/2909)
- Show error icon for failing Mesos logs [\#2844](https://github.com/mesosphere/marathon/issues/2844)
- Trying to restart app in UI gives me confusing error dialog [\#2841](https://github.com/mesosphere/marathon/issues/2841)
- Convert alert, confirm and prompt dialogs to new design [\#2831](https://github.com/mesosphere/marathon/issues/2831)
- Add contextual dropdown menu to Application List items [\#2814](https://github.com/mesosphere/marathon/issues/2814)
- Allow users to delete groups [\#2770](https://github.com/mesosphere/marathon/issues/2770)
- Never preselect dangerous actions in modal dialogs [\#2655](https://github.com/mesosphere/marathon/issues/2655)
- Improve ui kill and scale error messages [\#2652](https://github.com/mesosphere/marathon/issues/2652)

**Fixed bugs:**

- Unbounded ThreadPool is used for too many operations [\#2957](https://github.com/mesosphere/marathon/issues/2957)
- Incorrect Constraint lead to an application exception, but should give an error response [\#2951](https://github.com/mesosphere/marathon/issues/2951)
- AjaxWrapper does't handle TypeError correctly [\#2949](https://github.com/mesosphere/marathon/issues/2949)
- Clicking "Restart" from the action context menu unexpectedly changes the view [\#2933](https://github.com/mesosphere/marathon/issues/2933)
- StateMetrics.timed\(Read/Write\) incorrectly used for methods returning Futures [\#2919](https://github.com/mesosphere/marathon/issues/2919)
- Incorrect Step-wise timers in TaskStatusUpdateProcessorImpl [\#2918](https://github.com/mesosphere/marathon/issues/2918)
- App page component should display the right number of instances [\#2893](https://github.com/mesosphere/marathon/issues/2893)
- \[Shaky Test\] SchedulerServiceTest: Abdicate leadership when driver ends with error [\#2858](https://github.com/mesosphere/marathon/issues/2858)
- Migration of ZK State to 0.13/0.14 does not work [\#2405](https://github.com/mesosphere/marathon/issues/2405)
- Remove misleading logging on GET /v2/info [\#2966](https://github.com/mesosphere/marathon/pull/2966) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2405 by excluding already migrated tasks in subsequent migrati… [\#2962](https://github.com/mesosphere/marathon/pull/2962) ([meichstedt](https://github.com/meichstedt))
- Report state metrics to the same classes as before [\#2937](https://github.com/mesosphere/marathon/pull/2937) ([kolloch](https://github.com/kolloch))
- Do not use user-supplied version timestamp for new applications [\#2931](https://github.com/mesosphere/marathon/pull/2931) ([kolloch](https://github.com/kolloch))
- Fixes \#2918 - capture step-wise metrics correctly [\#2922](https://github.com/mesosphere/marathon/pull/2922) ([kolloch](https://github.com/kolloch))
- Fixes \#2919 - correct metrics for state reads/writes [\#2921](https://github.com/mesosphere/marathon/pull/2921) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- When in HA mode, sync file based artifact\_store between nodes [\#2971](https://github.com/mesosphere/marathon/issues/2971)
- Unable  to run marathon without zookeeper [\#2950](https://github.com/mesosphere/marathon/issues/2950)
- Problem when marathon server restart [\#2948](https://github.com/mesosphere/marathon/issues/2948)
- different definitions of 'cpu' parameter for mesos and docker [\#2940](https://github.com/mesosphere/marathon/issues/2940)
- Clicking the "Scale" and "Restart" from the action context menu scrolls to the top [\#2934](https://github.com/mesosphere/marathon/issues/2934)
- Add groups-endpoint flux actions and events [\#2930](https://github.com/mesosphere/marathon/issues/2930)
- Cap parallel task status update processing [\#2927](https://github.com/mesosphere/marathon/issues/2927)
- Docker container hanging when scale app [\#2924](https://github.com/mesosphere/marathon/issues/2924)
- Refactor app list contextual actions menu to make use of the PopoverComponent [\#2915](https://github.com/mesosphere/marathon/issues/2915)
- Label popover alignment isn't working anymore   [\#2912](https://github.com/mesosphere/marathon/issues/2912)
- Show health status bar breakdown on application detail view [\#2906](https://github.com/mesosphere/marathon/issues/2906)
- Enhance metrics to include incoming resources? [\#2898](https://github.com/mesosphere/marathon/issues/2898)
- Unable to create new Apps [\#2886](https://github.com/mesosphere/marathon/issues/2886)
- Refactor AppListItemLabelsComponent to make use of new PopoverComponent [\#2856](https://github.com/mesosphere/marathon/issues/2856)
- Provision to start service group in a priority node [\#2791](https://github.com/mesosphere/marathon/issues/2791)
- Allow configuration of "port" instead of "portIndex" for HTTP/TCP health checks [\#2733](https://github.com/mesosphere/marathon/issues/2733)
- Prototype per-container IP support [\#2709](https://github.com/mesosphere/marathon/issues/2709)
- Improve UI error messages [\#2511](https://github.com/mesosphere/marathon/issues/2511)
- Improve flexibility of tests [\#2099](https://github.com/mesosphere/marathon/issues/2099)
- Redesign TaskTracker [\#462](https://github.com/mesosphere/marathon/issues/462)

**Merged pull requests:**

- Fix error when installing sbt [\#2977](https://github.com/mesosphere/marathon/pull/2977) ([kolloch](https://github.com/kolloch))
- Update changelog.md [\#2976](https://github.com/mesosphere/marathon/pull/2976) ([gkleiman](https://github.com/gkleiman))
- Adding 'message' property and changing 'errors' to 'details' [\#2975](https://github.com/mesosphere/marathon/pull/2975) ([lexwbr](https://github.com/lexwbr))
- Speed up MarathonSchedulerServiceTest [\#2968](https://github.com/mesosphere/marathon/pull/2968) ([kolloch](https://github.com/kolloch))
- Update Tomcat examples [\#2965](https://github.com/mesosphere/marathon/pull/2965) ([guenter](https://github.com/guenter))
- Fixes \#2957 - improve usage of io threadpool [\#2963](https://github.com/mesosphere/marathon/pull/2963) ([kolloch](https://github.com/kolloch))
- Fixes \#2951 by handling wrong formats in the constraints reader. [\#2955](https://github.com/mesosphere/marathon/pull/2955) ([aquamatthias](https://github.com/aquamatthias))
- Corrects JSON message spelling for leader abdication [\#2942](https://github.com/mesosphere/marathon/pull/2942) ([bayendor](https://github.com/bayendor))
- Remove unused method from ProcessKeeper [\#2914](https://github.com/mesosphere/marathon/pull/2914) ([gkleiman](https://github.com/gkleiman))
- Update Marathon UI version to 0.15-SNAPSHOT [\#2913](https://github.com/mesosphere/marathon/pull/2913) ([philipnrmn](https://github.com/philipnrmn))
- Use Mesos 0.26.0 in Dockerfile.development [\#2904](https://github.com/mesosphere/marathon/pull/2904) ([gkleiman](https://github.com/gkleiman))
- Add missing Default to the Description of boolean arguments. [\#2902](https://github.com/mesosphere/marathon/pull/2902) ([aquamatthias](https://github.com/aquamatthias))
- Test support for ActorSystem.shutdown and ShutdownHooks [\#2894](https://github.com/mesosphere/marathon/pull/2894) ([kolloch](https://github.com/kolloch))
- Fixes \#2916 - Actor Implementation of TaskTracker, TaskCreator, TaskUpdater [\#2863](https://github.com/mesosphere/marathon/pull/2863) ([kolloch](https://github.com/kolloch))
- \#2735 - replacement of ModelValidation [\#2804](https://github.com/mesosphere/marathon/pull/2804) ([lexwbr](https://github.com/lexwbr))

## [v0.14.0-RC2](https://github.com/mesosphere/marathon/tree/v0.14.0-RC2) (2016-01-05)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.14.0-RC1...v0.14.0-RC2)

**Implemented enhancements:**

- Convert all alert, confirm and prompt dialogs to have meaningful action button labels [\#2832](https://github.com/mesosphere/marathon/issues/2832)
- Improve ui scale error messages [\#2651](https://github.com/mesosphere/marathon/issues/2651)

**Fixed bugs:**

- Update IPAddress of a running app is not possible [\#2872](https://github.com/mesosphere/marathon/issues/2872)
- Marathon healthchecks on wrong address [\#2870](https://github.com/mesosphere/marathon/issues/2870)
- Multiple explicit ports are mixed up in task json [\#2865](https://github.com/mesosphere/marathon/issues/2865)
- Preserve unknown config options when editing app [\#2693](https://github.com/mesosphere/marathon/issues/2693)
- Fixes \#2870 - Use the container IP for HCs only if an IP address was requested [\#2882](https://github.com/mesosphere/marathon/pull/2882) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2872 - Make it possible to update the ipAddress [\#2877](https://github.com/mesosphere/marathon/pull/2877) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2865 - Preserve app definition ports order [\#2867](https://github.com/mesosphere/marathon/pull/2867) ([gkleiman](https://github.com/gkleiman))

**Closed issues:**

- Actor-based implementation of the TaskTracker [\#2916](https://github.com/mesosphere/marathon/issues/2916)
- Version in task detail component shouldn't be localised [\#2892](https://github.com/mesosphere/marathon/issues/2892)
- Unable to change marathon port [\#2885](https://github.com/mesosphere/marathon/issues/2885)
- Possible licensing / redistribution issue with marathon [\#2883](https://github.com/mesosphere/marathon/issues/2883)
- what does the "cpus" mean ? [\#2881](https://github.com/mesosphere/marathon/issues/2881)
- Old tasks content left on Mesos slave [\#2880](https://github.com/mesosphere/marathon/issues/2880)
- Graceful restart of a docker task [\#2876](https://github.com/mesosphere/marathon/issues/2876)
- marathon can't resolve hostnames locally after adding long line in /etc/hosts [\#2862](https://github.com/mesosphere/marathon/issues/2862)
- Make filters work like label / status selectors [\#2861](https://github.com/mesosphere/marathon/issues/2861)
- Improve --ha description \(was: typo in marathon document\) [\#2820](https://github.com/mesosphere/marathon/issues/2820)
- Document UI application states [\#2816](https://github.com/mesosphere/marathon/issues/2816)
- marathon documentation does not give dependecies for setting up a build environment [\#2813](https://github.com/mesosphere/marathon/issues/2813)

**Merged pull requests:**

- Update v0.14.0 changelog [\#2899](https://github.com/mesosphere/marathon/pull/2899) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2820 - Improve --\[disable\_\]ha documentation [\#2896](https://github.com/mesosphere/marathon/pull/2896) ([gkleiman](https://github.com/gkleiman))
- Add Notonthehighstreet as a user of Marathon [\#2895](https://github.com/mesosphere/marathon/pull/2895) ([justingood](https://github.com/justingood))
- Introduce trait for LeadershipModule [\#2891](https://github.com/mesosphere/marathon/pull/2891) ([kolloch](https://github.com/kolloch))
- Fixed duplicate assertion in ConstraintsTest. [\#2890](https://github.com/mesosphere/marathon/pull/2890) ([medzin](https://github.com/medzin))
- Update README.md - Add Teradata to company list [\#2888](https://github.com/mesosphere/marathon/pull/2888) ([jdubs](https://github.com/jdubs))
- PR for \#2813 [\#2879](https://github.com/mesosphere/marathon/pull/2879) ([asridharan](https://github.com/asridharan))
- Add Marathon UI to the official Docs [\#2873](https://github.com/mesosphere/marathon/pull/2873) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Minor correction to blue-green deployment doc [\#2866](https://github.com/mesosphere/marathon/pull/2866) ([brndnmtthws](https://github.com/brndnmtthws))
- Reorganize core.task package [\#2835](https://github.com/mesosphere/marathon/pull/2835) ([kolloch](https://github.com/kolloch))
- Remove unused functionality from WhenLeaderActor [\#2833](https://github.com/mesosphere/marathon/pull/2833) ([kolloch](https://github.com/kolloch))
- Toward \#462 - create interface traits for TaskTracker [\#2830](https://github.com/mesosphere/marathon/pull/2830) ([kolloch](https://github.com/kolloch))

## [v0.14.0-RC1](https://github.com/mesosphere/marathon/tree/v0.14.0-RC1) (2015-12-18)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0...v0.14.0-RC1)

**Implemented enhancements:**

- Health filter in sidebar [\#2809](https://github.com/mesosphere/marathon/issues/2809)
- Write more tests for our AJAX wrapper [\#2795](https://github.com/mesosphere/marathon/issues/2795)
- Prompt support for number input type [\#2785](https://github.com/mesosphere/marathon/issues/2785)
- Show Host field in Task details page also for apps with IP per container settings [\#2779](https://github.com/mesosphere/marathon/issues/2779)
- Show error alert for failing Mesos logs downloads [\#2777](https://github.com/mesosphere/marathon/issues/2777)
- Syntax highlighting for JSON fragments in configuration [\#2775](https://github.com/mesosphere/marathon/issues/2775)
- URI fields should be links [\#2772](https://github.com/mesosphere/marathon/issues/2772)
- Open task links in a new tab [\#2771](https://github.com/mesosphere/marathon/issues/2771)
- Current group should be prefilled in the app creation modal [\#2768](https://github.com/mesosphere/marathon/issues/2768)
- Restore eslint issues on npm run serve cycle [\#2668](https://github.com/mesosphere/marathon/issues/2668)
- Provide memory and cpu as environment variables in docker containers [\#2505](https://github.com/mesosphere/marathon/issues/2505)
- Use icons to communicate nature of alerts [\#2088](https://github.com/mesosphere/marathon/issues/2088)
- Expose additional app definition variables [\#2787](https://github.com/mesosphere/marathon/pull/2787) ([wendigo](https://github.com/wendigo))

**Fixed bugs:**

- Misleading error feedback in app creation modal on port conflict [\#2845](https://github.com/mesosphere/marathon/issues/2845)
- pass credentials with ajax requests [\#2826](https://github.com/mesosphere/marathon/issues/2826)
- Tooltip isn't removed on content change [\#2821](https://github.com/mesosphere/marathon/issues/2821)
- Cannot change configuration of Marathon app after deployment [\#2812](https://github.com/mesosphere/marathon/issues/2812)
- Health breakdown tooltip is one step behind [\#2808](https://github.com/mesosphere/marathon/issues/2808)
- Fix broken Task details fields for empty service discovery ports [\#2778](https://github.com/mesosphere/marathon/issues/2778)
- Show no links when no ports are specified for service discovery [\#2776](https://github.com/mesosphere/marathon/issues/2776)
- Invalid endpoint with ip-per-task + empty app.ipAddress.discover.ports [\#2767](https://github.com/mesosphere/marathon/issues/2767)
- Regression: breadcrumbs no longer collapse [\#2757](https://github.com/mesosphere/marathon/issues/2757)
- Firefox Memory Leak in Marathon UI [\#2755](https://github.com/mesosphere/marathon/issues/2755)
- Override cmd field with null, not " " [\#2749](https://github.com/mesosphere/marathon/issues/2749)
- Invalid validation for multiple ports [\#2734](https://github.com/mesosphere/marathon/issues/2734)
- Disabled button has wrong colour [\#2720](https://github.com/mesosphere/marathon/issues/2720)
- Leadership not abdicated on ZK connection loss [\#2509](https://github.com/mesosphere/marathon/issues/2509)
- Can't remove cmd from application without ugly hack [\#2147](https://github.com/mesosphere/marathon/issues/2147)
- java.lang.NoClassDefFoundError: java/util/concurrent/ThreadLocalRandom [\#2017](https://github.com/mesosphere/marathon/issues/2017)
- Marathon 0.80 upgrade deployment stuck with no tasks in the queue [\#1610](https://github.com/mesosphere/marathon/issues/1610)
- Task stuck in killing after launch timeout state [\#1594](https://github.com/mesosphere/marathon/issues/1594)
- App restart creates an invisible deployment [\#1478](https://github.com/mesosphere/marathon/issues/1478)
- Marathon violates hostname unique constraints during deploys [\#1349](https://github.com/mesosphere/marathon/issues/1349)
- Marathon crashes after getting restarted [\#1196](https://github.com/mesosphere/marathon/issues/1196)
- Killing too many instances at once causes master failure [\#1173](https://github.com/mesosphere/marathon/issues/1173)
- Out of Memory Exception - Memory usage does not seem bounded [\#974](https://github.com/mesosphere/marathon/issues/974)
- Some marathon jobs cannot be "destroyed" if they still have any running instances. [\#725](https://github.com/mesosphere/marathon/issues/725)

**Closed issues:**

- Marathon 0.13 compatible with Mesos 0.26.0? [\#2848](https://github.com/mesosphere/marathon/issues/2848)
- Provision to start group of applications on same Mesos slave [\#2846](https://github.com/mesosphere/marathon/issues/2846)
- Bug in 0.13 when PUT with ?force=true [\#2834](https://github.com/mesosphere/marathon/issues/2834)
- Add UI option for forcePullImage [\#2824](https://github.com/mesosphere/marathon/issues/2824)
- Remove `Set\[MarathonTask\]` from TaskTracker [\#2818](https://github.com/mesosphere/marathon/issues/2818)
- Investigate alternative to ref hack for AboutModalComponent [\#2815](https://github.com/mesosphere/marathon/issues/2815)
- Use shutdown call to kill tasks [\#2811](https://github.com/mesosphere/marathon/issues/2811)
- Show loading state for requested Mesos logs download [\#2806](https://github.com/mesosphere/marathon/issues/2806)
- Get rid of Oboe.js [\#2797](https://github.com/mesosphere/marathon/issues/2797)
- haproxy-marathon-bridge   error [\#2793](https://github.com/mesosphere/marathon/issues/2793)
- Open Marathon Bugs [\#2786](https://github.com/mesosphere/marathon/issues/2786)
- subprocess call should close file descriptors in child [\#2781](https://github.com/mesosphere/marathon/issues/2781)
- Can't seem to get Marathon COMMAND health checks to suceed [\#2760](https://github.com/mesosphere/marathon/issues/2760)
- Sidebar status filter slightly displaced  [\#2748](https://github.com/mesosphere/marathon/issues/2748)
- Refactor CSS: extract label styles to generic .badge class [\#2740](https://github.com/mesosphere/marathon/issues/2740)
- Run Unit Tests on Jenkins [\#2739](https://github.com/mesosphere/marathon/issues/2739)
- Don't have AppDefinition.json twice [\#2730](https://github.com/mesosphere/marathon/issues/2730)
- Show Logs \(Error Logs and and Output Logs\) in Task Detail View [\#2721](https://github.com/mesosphere/marathon/issues/2721)
- Rename the "basic" app type [\#2717](https://github.com/mesosphere/marathon/issues/2717)
- Deployment loading bar should have new style [\#2715](https://github.com/mesosphere/marathon/issues/2715)
- Global ellipsis on breadcrumbs [\#2714](https://github.com/mesosphere/marathon/issues/2714)
- Document scale test findings / Marathon limits [\#2697](https://github.com/mesosphere/marathon/issues/2697)
- forcePullImage resets after editing app in UI [\#2674](https://github.com/mesosphere/marathon/issues/2674)
- Tooltip for health bar in App Collection View [\#2657](https://github.com/mesosphere/marathon/issues/2657)
- Remove dubious functionality to remove orphaned tasks from TaskTracker storage [\#2620](https://github.com/mesosphere/marathon/issues/2620)
- Introduce jsDom or similar in our tests [\#1796](https://github.com/mesosphere/marathon/issues/1796)

**Merged pull requests:**

- Integration Tests & ProcessKeeper: Do not use duplicate process names [\#2859](https://github.com/mesosphere/marathon/pull/2859) ([kolloch](https://github.com/kolloch))
- Added UI updates between 14.0 and 14.1 [\#2857](https://github.com/mesosphere/marathon/pull/2857) ([philipnrmn](https://github.com/philipnrmn))
- Raise Marathon UI version to latest release [\#2851](https://github.com/mesosphere/marathon/pull/2851) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Update changelog [\#2850](https://github.com/mesosphere/marathon/pull/2850) ([gkleiman](https://github.com/gkleiman))
- Show the ZK event that will cause the abdication [\#2849](https://github.com/mesosphere/marathon/pull/2849) ([aquamatthias](https://github.com/aquamatthias))
- Use Mesos 0.26.0 [\#2847](https://github.com/mesosphere/marathon/pull/2847) ([aquamatthias](https://github.com/aquamatthias))
- Show the ZK event that will cause the abdication [\#2843](https://github.com/mesosphere/marathon/pull/2843) ([aquamatthias](https://github.com/aquamatthias))
- We currently kill processes randomly. But we should kill them in reve… [\#2842](https://github.com/mesosphere/marathon/pull/2842) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2818 - Remove TaskTracker.get returning Set\[MarathonTask\] [\#2819](https://github.com/mesosphere/marathon/pull/2819) ([kolloch](https://github.com/kolloch))
- Fixes \#2620 - Remove TaskTracker.expungeOrphanedTasks [\#2817](https://github.com/mesosphere/marathon/pull/2817) ([kolloch](https://github.com/kolloch))
- Add SVT to Companies using Marathon [\#2805](https://github.com/mesosphere/marathon/pull/2805) ([carlanton](https://github.com/carlanton))
- IP per Container [\#2801](https://github.com/mesosphere/marathon/pull/2801) ([aquamatthias](https://github.com/aquamatthias))
- Towards \#2709 - Add service discovery info to ipAddress [\#2800](https://github.com/mesosphere/marathon/pull/2800) ([aquamatthias](https://github.com/aquamatthias))
- Remove airbnb from companies list [\#2798](https://github.com/mesosphere/marathon/pull/2798) ([ljharb](https://github.com/ljharb))
- Update changelog with 0.14 changes [\#2789](https://github.com/mesosphere/marathon/pull/2789) ([philipnrmn](https://github.com/philipnrmn))
- Update 0.14.0 changelog - backend [\#2788](https://github.com/mesosphere/marathon/pull/2788) ([gkleiman](https://github.com/gkleiman))
- Added LaunchKey to Marathon using companies in Readme [\#2783](https://github.com/mesosphere/marathon/pull/2783) ([jchysk](https://github.com/jchysk))
- modified call to subprocess.check\_call for haproxy reload to close all file descriptors in the child [\#2782](https://github.com/mesosphere/marathon/pull/2782) ([cgbaker](https://github.com/cgbaker))
- Do not remove frameworkId automatically. [\#2765](https://github.com/mesosphere/marathon/pull/2765) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2734 by only using the available assigned ports instead of all… [\#2761](https://github.com/mesosphere/marathon/pull/2761) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2730 by removing the unused schema. [\#2756](https://github.com/mesosphere/marathon/pull/2756) ([aquamatthias](https://github.com/aquamatthias))
- Added VANAD Enovation to company list [\#2753](https://github.com/mesosphere/marathon/pull/2753) ([avthart](https://github.com/avthart))
- Add trivago as a user of Marathon [\#2752](https://github.com/mesosphere/marathon/pull/2752) ([andygrunwald](https://github.com/andygrunwald))
- Update docs for release 0.13 [\#2747](https://github.com/mesosphere/marathon/pull/2747) ([aquamatthias](https://github.com/aquamatthias))
- Towards \#2709 - IP per Task v3 [\#2744](https://github.com/mesosphere/marathon/pull/2744) ([gkleiman](https://github.com/gkleiman))
- Towards \#2709 - Allow port instead of portIndex for health checks [\#2731](https://github.com/mesosphere/marathon/pull/2731) ([kolloch](https://github.com/kolloch))
- Fixes \#2509 by listening for connection drops and abdicating directly [\#2712](https://github.com/mesosphere/marathon/pull/2712) ([aquamatthias](https://github.com/aquamatthias))

## [v0.13.0](https://github.com/mesosphere/marathon/tree/v0.13.0) (2015-12-01)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0-RC6...v0.13.0)

**Implemented enhancements:**

- Improve sidebar app status count and UX [\#2650](https://github.com/mesosphere/marathon/issues/2650)

**Fixed bugs:**

- Filter does not match apps correctly [\#2722](https://github.com/mesosphere/marathon/issues/2722)
- Dialog boxes don't break long text [\#2658](https://github.com/mesosphere/marathon/issues/2658)
- Port mappings do make sense when container is in net=host mode [\#2566](https://github.com/mesosphere/marathon/issues/2566)
- If driver finishes with error, Marathon does not abdicate [\#2558](https://github.com/mesosphere/marathon/issues/2558)

**Closed issues:**

- marathon fails to deploy docker container. [\#2746](https://github.com/mesosphere/marathon/issues/2746)
- Marathon keeps waiting if uri is not available [\#2736](https://github.com/mesosphere/marathon/issues/2736)
- Expose IP-per-container app definition in App Details page [\#2729](https://github.com/mesosphere/marathon/issues/2729)
- Integrate IP-Per-Container ipAddresses into task detail view [\#2727](https://github.com/mesosphere/marathon/issues/2727)
- Clean up model validation [\#2723](https://github.com/mesosphere/marathon/issues/2723)
- Show correct button label when creating inside group  [\#2719](https://github.com/mesosphere/marathon/issues/2719)
- Extract LESS into modules [\#2711](https://github.com/mesosphere/marathon/issues/2711)
- Remove documentation regarding `--executor\_health\_checks` [\#2700](https://github.com/mesosphere/marathon/issues/2700)
- Prototype: Show Logs \(Error Logs and and Output Logs\) in Task Detail View  [\#2645](https://github.com/mesosphere/marathon/issues/2645)
- The New Application / Health checks close button \(x\) does not work [\#2529](https://github.com/mesosphere/marathon/issues/2529)
- Tasks/Instances column rewording [\#2047](https://github.com/mesosphere/marathon/issues/2047)
- Refactor components: introduce EventBinder mixin [\#1737](https://github.com/mesosphere/marathon/issues/1737)

**Merged pull requests:**

- Update support.md [\#2742](https://github.com/mesosphere/marathon/pull/2742) ([mrajashree](https://github.com/mrajashree))
- Remove ref to outdated command line flag from docs [\#2703](https://github.com/mesosphere/marathon/pull/2703) ([philipnrmn](https://github.com/philipnrmn))
- Add haproxy installation support for openSuSE [\#2673](https://github.com/mesosphere/marathon/pull/2673) ([hayderimran7](https://github.com/hayderimran7))

## [v0.13.0-RC6](https://github.com/mesosphere/marathon/tree/v0.13.0-RC6) (2015-11-25)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0-RC5...v0.13.0-RC6)

**Fixed bugs:**

- Running instances are confusing [\#2684](https://github.com/mesosphere/marathon/issues/2684)

**Closed issues:**

- Link groupId in search results to individual groups [\#2705](https://github.com/mesosphere/marathon/issues/2705)
- Change format of groupId under app name [\#2704](https://github.com/mesosphere/marathon/issues/2704)
- Release another 0.13 RC with ui/service fixes [\#2696](https://github.com/mesosphere/marathon/issues/2696)
- New UI, feedback and suggestions [\#2612](https://github.com/mesosphere/marathon/issues/2612)

**Merged pull requests:**

- Raise UI version to 0.13.6 [\#2718](https://github.com/mesosphere/marathon/pull/2718) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fix flaky unit test [\#2632](https://github.com/mesosphere/marathon/pull/2632) ([gkleiman](https://github.com/gkleiman))
- Use mesos 0.25.0 for docker images. [\#2516](https://github.com/mesosphere/marathon/pull/2516) ([aquamatthias](https://github.com/aquamatthias))

## [v0.13.0-RC5](https://github.com/mesosphere/marathon/tree/v0.13.0-RC5) (2015-11-24)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0-RC4...v0.13.0-RC5)

**Implemented enhancements:**

- Show proper info on app creation auth error [\#2702](https://github.com/mesosphere/marathon/issues/2702)
- Show error dialog on kill task error [\#2687](https://github.com/mesosphere/marathon/issues/2687)

**Fixed bugs:**

- App list / health bar update/render issue [\#2699](https://github.com/mesosphere/marathon/issues/2699)
- Cherry-pick fix for \#2681 to 0.13 [\#2695](https://github.com/mesosphere/marathon/issues/2695)
- Filters don't updated correctly on reload [\#2691](https://github.com/mesosphere/marathon/issues/2691)
- 0.11.1 -\> 0.13.0-RC4 upgrade losing and then killing old tasks [\#2681](https://github.com/mesosphere/marathon/issues/2681)
- Create button doesn´t work with IE [\#2676](https://github.com/mesosphere/marathon/issues/2676)
- Fixes \#2681 - Circumvent cache if not yet preloaded [\#2686](https://github.com/mesosphere/marathon/pull/2686) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Mesos details link broken due to extra / [\#2682](https://github.com/mesosphere/marathon/issues/2682)
- Global Search: switch from live filter to submit to search [\#2680](https://github.com/mesosphere/marathon/issues/2680)
- Create mixin for filters query params functionality [\#2678](https://github.com/mesosphere/marathon/issues/2678)
- Edit in the UI an app using a docker image with an entrypoint result in entrypoint override and empty command [\#2677](https://github.com/mesosphere/marathon/issues/2677)
- Remove unused viewType property in AppListComponent [\#2671](https://github.com/mesosphere/marathon/issues/2671)
- Adapt Filter Behavior to new Global Search [\#2664](https://github.com/mesosphere/marathon/issues/2664)
- Adapt Filter Count  [\#2663](https://github.com/mesosphere/marathon/issues/2663)
- Change Header When Applying Filter in App Collection View  [\#2662](https://github.com/mesosphere/marathon/issues/2662)
- Global Search Result Set in App Collection View [\#2661](https://github.com/mesosphere/marathon/issues/2661)
- Adapt Search box in App Collection View [\#2660](https://github.com/mesosphere/marathon/issues/2660)
- Show the full ID path under the base ID [\#2659](https://github.com/mesosphere/marathon/issues/2659)
- Consolidate Actions Menu in App Details View [\#2646](https://github.com/mesosphere/marathon/issues/2646)
- Global Filters & Search in App Collection View [\#2644](https://github.com/mesosphere/marathon/issues/2644)

**Merged pull requests:**

- Set UI version to 0.13.5 [\#2708](https://github.com/mesosphere/marathon/pull/2708) ([aldipower](https://github.com/aldipower))
- Execute migrations sequentially. [\#2701](https://github.com/mesosphere/marathon/pull/2701) ([aquamatthias](https://github.com/aquamatthias))
- Docs: How to use static partitioning with Marathon [\#2669](https://github.com/mesosphere/marathon/pull/2669) ([kolloch](https://github.com/kolloch))
- Docs: Add "requiring ports" to common problems [\#2666](https://github.com/mesosphere/marathon/pull/2666) ([kolloch](https://github.com/kolloch))

## [v0.13.0-RC4](https://github.com/mesosphere/marathon/tree/v0.13.0-RC4) (2015-11-18)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0-RC3...v0.13.0-RC4)

**Implemented enhancements:**

- Prevent "show more labels" button breaking the line  [\#2631](https://github.com/mesosphere/marathon/issues/2631)
- Can use etcd instead of zookeeper for marathon to store apps info [\#2577](https://github.com/mesosphere/marathon/issues/2577)
- Implement marathon components for mesos persistent data stores [\#1769](https://github.com/mesosphere/marathon/issues/1769)

**Fixed bugs:**

- UI does not update/show the status correctly [\#2634](https://github.com/mesosphere/marathon/issues/2634)
- Tasks health column shows different health status [\#2627](https://github.com/mesosphere/marathon/issues/2627)
- Status icons are rendered blotted [\#2626](https://github.com/mesosphere/marathon/issues/2626)
- Keep input focus position when updating the Filter bar [\#2615](https://github.com/mesosphere/marathon/issues/2615)
- Cache for EventSubscribers not populated on startup [\#2599](https://github.com/mesosphere/marathon/issues/2599)
- Allow relative application dependencies [\#2543](https://github.com/mesosphere/marathon/issues/2543)
- Filter/search input border looks a bit strange [\#2528](https://github.com/mesosphere/marathon/issues/2528)
- Search for name only find entries in the current group [\#2524](https://github.com/mesosphere/marathon/issues/2524)
- Status for group is not shown [\#2523](https://github.com/mesosphere/marathon/issues/2523)
- When app is locked by deployment, deleting tasks via the UI does nothing [\#1780](https://github.com/mesosphere/marathon/issues/1780)
- Corrects \#2613 - Fix lost update loop [\#2635](https://github.com/mesosphere/marathon/pull/2635) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- how to monitor app's\(including shell and docker\) cpu,mem,network,disk info ? [\#2667](https://github.com/mesosphere/marathon/issues/2667)
- FeatureRequest: Show Resources [\#2643](https://github.com/mesosphere/marathon/issues/2643)
- Config change does not update all fields \(JSON Upload\) [\#2642](https://github.com/mesosphere/marathon/issues/2642)
- could one marathon instance management multiple mesos frameworks ? [\#2639](https://github.com/mesosphere/marathon/issues/2639)
- how to make app to monopolize one slave node ? [\#2638](https://github.com/mesosphere/marathon/issues/2638)
- Change Label of Search Textbox [\#2623](https://github.com/mesosphere/marathon/issues/2623)
- v0.13.0-RC3 docker hub build has failed [\#2622](https://github.com/mesosphere/marathon/issues/2622)
- No logging available [\#2621](https://github.com/mesosphere/marathon/issues/2621)
- Consolidate task update logic in TaskTracker [\#2618](https://github.com/mesosphere/marathon/issues/2618)
- Update Deployment Design Docs [\#2616](https://github.com/mesosphere/marathon/issues/2616)
- Can't pull docker image [\#2602](https://github.com/mesosphere/marathon/issues/2602)
- how to make host port  remain unchanged when app restart or move to other node ? [\#2578](https://github.com/mesosphere/marathon/issues/2578)
- Marathon keeps trying to start docker containers, even though instances are set at 1 [\#2555](https://github.com/mesosphere/marathon/issues/2555)
- PUT /v2/apps/{appId} to non-leader Marathon does not work [\#2546](https://github.com/mesosphere/marathon/issues/2546)
- Unable to find valid certification path to requested target - HTTPS errors on non-leader instances in cluster. [\#2540](https://github.com/mesosphere/marathon/issues/2540)
- Deploy app failed [\#2539](https://github.com/mesosphere/marathon/issues/2539)
- Event Subscriptions  [\#2447](https://github.com/mesosphere/marathon/issues/2447)
- Application and Task Limit Guidance [\#2183](https://github.com/mesosphere/marathon/issues/2183)
- Create scale tests for Marathon [\#1789](https://github.com/mesosphere/marathon/issues/1789)
- Github release archives don't contain the UI files [\#1720](https://github.com/mesosphere/marathon/issues/1720)

**Merged pull requests:**

- Set UI version to 0.13.4 [\#2670](https://github.com/mesosphere/marathon/pull/2670) ([aldipower](https://github.com/aldipower))
- Fixes \#2543 - relative path in application dependencies within a group. [\#2665](https://github.com/mesosphere/marathon/pull/2665) ([lexwbr](https://github.com/lexwbr))
- Fix bashism [\#2654](https://github.com/mesosphere/marathon/pull/2654) ([heichblatt](https://github.com/heichblatt))
- Update README URLs based on HTTP redirects [\#2649](https://github.com/mesosphere/marathon/pull/2649) ([ReadmeCritic](https://github.com/ReadmeCritic))
- Stop-gap warning about deployment design document [\#2648](https://github.com/mesosphere/marathon/pull/2648) ([kolloch](https://github.com/kolloch))
- Document \#2540 - users need to add local CA cert to keystore [\#2647](https://github.com/mesosphere/marathon/pull/2647) ([kolloch](https://github.com/kolloch))
- PortWithRoleRandomPortsFromRangesTest: Increase benchmark/expected du… [\#2641](https://github.com/mesosphere/marathon/pull/2641) ([kolloch](https://github.com/kolloch))
- Add Oracle Linux to OS check [\#2636](https://github.com/mesosphere/marathon/pull/2636) ([heichblatt](https://github.com/heichblatt))
- Full stops at the end of the description [\#2630](https://github.com/mesosphere/marathon/pull/2630) ([aquamatthias](https://github.com/aquamatthias))
- Fix Markdown code formatting [\#2629](https://github.com/mesosphere/marathon/pull/2629) ([earldouglas](https://github.com/earldouglas))
- Fixes \#2618 - Consolidate statusUpdate logic in TaskTracker life cycle methods [\#2625](https://github.com/mesosphere/marathon/pull/2625) ([kolloch](https://github.com/kolloch))
- Docs cleanup [\#2619](https://github.com/mesosphere/marathon/pull/2619) ([ssk2](https://github.com/ssk2))
- Fixes \#2440 - Finish testing and refactoring task update steps [\#2613](https://github.com/mesosphere/marathon/pull/2613) ([kolloch](https://github.com/kolloch))
- Remove unused test log4.properties. [\#2608](https://github.com/mesosphere/marathon/pull/2608) ([gkleiman](https://github.com/gkleiman))
- Update CI to remove pep8 gating on servicerouter [\#2591](https://github.com/mesosphere/marathon/pull/2591) ([hayderimran7](https://github.com/hayderimran7))

## [v0.13.0-RC3](https://github.com/mesosphere/marathon/tree/v0.13.0-RC3) (2015-11-10)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0-RC2...v0.13.0-RC3)

**Fixed bugs:**

- ActorLogging warning does not expand Throwable  [\#2603](https://github.com/mesosphere/marathon/issues/2603)
- Very long labels expand horizontal scrollbar in app list [\#2593](https://github.com/mesosphere/marathon/issues/2593)
- UI: App state incorrectly shown [\#2568](https://github.com/mesosphere/marathon/issues/2568)

**Closed issues:**

- docker portMappings protocol type ? [\#2592](https://github.com/mesosphere/marathon/issues/2592)
- how to share common env in a group of apps [\#2542](https://github.com/mesosphere/marathon/issues/2542)
- marathon service start error \[ marathon.service: main process exited, code=exited status=1/FAILURE\]  [\#2537](https://github.com/mesosphere/marathon/issues/2537)
- typo in release docs [\#2531](https://github.com/mesosphere/marathon/issues/2531)
- Service ports are assigned when servicePort is omitted [\#2521](https://github.com/mesosphere/marathon/issues/2521)

**Merged pull requests:**

- Fix typos in flags [\#2610](https://github.com/mesosphere/marathon/pull/2610) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fix minor typo [\#2607](https://github.com/mesosphere/marathon/pull/2607) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Explicitly name all portMapping values [\#2606](https://github.com/mesosphere/marathon/pull/2606) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Fixes \#2603 by defining log templates and binding variables. [\#2605](https://github.com/mesosphere/marathon/pull/2605) ([meichstedt](https://github.com/meichstedt))
- Fixes \#2603 by defining log templates and binding variables. [\#2604](https://github.com/mesosphere/marathon/pull/2604) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2599 by adding the event subscriber store to the leader ship callbacks [\#2600](https://github.com/mesosphere/marathon/pull/2600) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#2440 - Test for NotifyLaunchQueueStepImpl [\#2598](https://github.com/mesosphere/marathon/pull/2598) ([kolloch](https://github.com/kolloch))

## [v0.13.0-RC2](https://github.com/mesosphere/marathon/tree/v0.13.0-RC2) (2015-11-09)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.13.0-RC1...v0.13.0-RC2)

**Implemented enhancements:**

- Show all groups in the web ui. [\#959](https://github.com/mesosphere/marathon/issues/959)

**Fixed bugs:**

- Sorting by Status shifts heading text [\#2586](https://github.com/mesosphere/marathon/issues/2586)
- Sorting by CPU causes row column to expand [\#2585](https://github.com/mesosphere/marathon/issues/2585)
- Label Filter: Filter Label Box is not cleared   [\#2574](https://github.com/mesosphere/marathon/issues/2574)
- Task list contains staged task but it is not included in the staged counts [\#2322](https://github.com/mesosphere/marathon/issues/2322)
- Health state gets lost sporadically [\#2314](https://github.com/mesosphere/marathon/issues/2314)
- \[0.13\] correct staged counts, fix health check reconciliation [\#2596](https://github.com/mesosphere/marathon/pull/2596) ([kolloch](https://github.com/kolloch))
- Fixes \#2322 - count tasks without explicit state as staging [\#2581](https://github.com/mesosphere/marathon/pull/2581) ([kolloch](https://github.com/kolloch))
- Fixes \#2314 - Do not remove health checks that are still needed [\#2571](https://github.com/mesosphere/marathon/pull/2571) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Unable to use constraints with UNIQUE operator  [\#2588](https://github.com/mesosphere/marathon/issues/2588)
- Port mapping [\#2587](https://github.com/mesosphere/marathon/issues/2587)
- Shaky Unit Test: PortWithRoleRandomPortsFromRangesTest is lazy with multiple ranges [\#2579](https://github.com/mesosphere/marathon/issues/2579)
- could i use marathon api get the cluster information, such as mem,cpu,network usage on every node/cluster? [\#2576](https://github.com/mesosphere/marathon/issues/2576)
- Marathon can't see all roles available [\#2573](https://github.com/mesosphere/marathon/issues/2573)
- Change app icon title from "Basic" to "Application" [\#2565](https://github.com/mesosphere/marathon/issues/2565)
- Reject application json with undefined/superfluous json [\#2564](https://github.com/mesosphere/marathon/issues/2564)
- Marathon lost connection to zookeeper, now entire cluster refuses to start [\#2557](https://github.com/mesosphere/marathon/issues/2557)
- The "Application Groups" did not work in Marathon 0.11.1 [\#2552](https://github.com/mesosphere/marathon/issues/2552)
- Document datadog and graphite reporters [\#2478](https://github.com/mesosphere/marathon/issues/2478)
- Create unit tests for PR \#2381 [\#2440](https://github.com/mesosphere/marathon/issues/2440)
- Provide links to the release notes in the "Upgrading" section [\#1920](https://github.com/mesosphere/marathon/issues/1920)

**Merged pull requests:**

- Use EntityCacheStore for EventSubscribers [\#2597](https://github.com/mesosphere/marathon/pull/2597) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#2440 - unit tests for PostToEventStreamStepImpl [\#2595](https://github.com/mesosphere/marathon/pull/2595) ([kolloch](https://github.com/kolloch))
- Improves \#2440 - Unit test for ContinueOnErrorStep [\#2584](https://github.com/mesosphere/marathon/pull/2584) ([kolloch](https://github.com/kolloch))
- Fixes \#2579 - be smarter in timing tests [\#2582](https://github.com/mesosphere/marathon/pull/2582) ([kolloch](https://github.com/kolloch))
- Fix the commands in the mesos-simulation/README.md [\#2580](https://github.com/mesosphere/marathon/pull/2580) ([kolloch](https://github.com/kolloch))
- Remove servicerouter and point docs to marathon-lb [\#2572](https://github.com/mesosphere/marathon/pull/2572) ([discordianfish](https://github.com/discordianfish))
- Use 503\(Service Unavailable\) instead of Gateway Timeout if we run int… [\#2570](https://github.com/mesosphere/marathon/pull/2570) ([aquamatthias](https://github.com/aquamatthias))
- Update upgrade instructions. [\#2569](https://github.com/mesosphere/marathon/pull/2569) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2478 by describing the reporter command line flags  [\#2562](https://github.com/mesosphere/marathon/pull/2562) ([aquamatthias](https://github.com/aquamatthias))
- Fixes 2532 added docs [\#2559](https://github.com/mesosphere/marathon/pull/2559) ([janisz](https://github.com/janisz))

## [v0.13.0-RC1](https://github.com/mesosphere/marathon/tree/v0.13.0-RC1) (2015-11-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.1...v0.13.0-RC1)

**Implemented enhancements:**

- Create keyboard shortcut for focusing on the search field [\#2434](https://github.com/mesosphere/marathon/issues/2434)
- Implement optional "warm-up" health-check [\#2431](https://github.com/mesosphere/marathon/issues/2431)
- Docker indicator in app list [\#2054](https://github.com/mesosphere/marathon/issues/2054)
- Allow to specify custom Java binary location [\#2018](https://github.com/mesosphere/marathon/issues/2018)
- No error received when a DELETE is sent to a task in deployment [\#1835](https://github.com/mesosphere/marathon/issues/1835)
- Add a metric with the uptime [\#1730](https://github.com/mesosphere/marathon/issues/1730)
- Make use of variables in LESS [\#1057](https://github.com/mesosphere/marathon/issues/1057)
- Enable the ability to delete groups from the web UI. [\#958](https://github.com/mesosphere/marathon/issues/958)
- Fixes \#2256 - Improve insufficient resources message [\#2502](https://github.com/mesosphere/marathon/pull/2502) ([gkleiman](https://github.com/gkleiman))

**Fixed bugs:**

- Resources Filter does not work [\#2554](https://github.com/mesosphere/marathon/issues/2554)
- List/Tree Filter not implemented - should be removed [\#2553](https://github.com/mesosphere/marathon/issues/2553)
- EntityStoreCache is filled after the scheduler driver has been created [\#2550](https://github.com/mesosphere/marathon/issues/2550)
- LeadershipCallback.onElected: the default zk\_timeout is too low with real world data [\#2532](https://github.com/mesosphere/marathon/issues/2532)
- Wording Basic: there might be Basic apps, but not every command line app is a basic app [\#2525](https://github.com/mesosphere/marathon/issues/2525)
- UI Filters are not applied to group \(transitively\) [\#2522](https://github.com/mesosphere/marathon/issues/2522)
- Marathon doesn't run on the latest Vagrant DCOS [\#2482](https://github.com/mesosphere/marathon/issues/2482)
- Marathon forgets all tasks on restart [\#2477](https://github.com/mesosphere/marathon/issues/2477)
- Framework Id not visible in the UI [\#2459](https://github.com/mesosphere/marathon/issues/2459)
- Investigate MarathonSchedulerServiceTest failure [\#2307](https://github.com/mesosphere/marathon/issues/2307)
- Writes to EntityRepositories should be visible in following reads [\#2299](https://github.com/mesosphere/marathon/issues/2299)
- Scaling check ignores task versions [\#2280](https://github.com/mesosphere/marathon/issues/2280)
- Misleading log message if offer doesn't match because of filtered roles [\#2256](https://github.com/mesosphere/marathon/issues/2256)
- App not present right after its creation [\#2202](https://github.com/mesosphere/marathon/issues/2202)
- Backport: Make sure that reviveOffers is sent after last decline \#2181 [\#2190](https://github.com/mesosphere/marathon/issues/2190)
- REST api returns code 500 for invalid JSON and fails silently to proxy the error [\#2174](https://github.com/mesosphere/marathon/issues/2174)
- Error Handling/validation required for COMMAND health check [\#2117](https://github.com/mesosphere/marathon/issues/2117)
- Marathon crashes after unsuccessful deployment [\#2095](https://github.com/mesosphere/marathon/issues/2095)
- App scaled below minimumHealthCapacity [\#1904](https://github.com/mesosphere/marathon/issues/1904)
- Hangs while scaling apps using port 80 over public slaves  [\#1736](https://github.com/mesosphere/marathon/issues/1736)
- Incorrect healthcheck triggers 500 Server error [\#1588](https://github.com/mesosphere/marathon/issues/1588)
- Inconsistent /help \<-\> rest-api.md documentation [\#1563](https://github.com/mesosphere/marathon/issues/1563)
- Non-integer is accepted as instance count [\#1429](https://github.com/mesosphere/marathon/issues/1429)
- Fixes \#2441 - Make TaskReplaceActor wait after killing [\#2445](https://github.com/mesosphere/marathon/pull/2445) ([gkleiman](https://github.com/gkleiman))

**Closed issues:**

- How to pass env to docker container [\#2549](https://github.com/mesosphere/marathon/issues/2549)
- `backOffFactor` should not be reset until app become healthy [\#2544](https://github.com/mesosphere/marathon/issues/2544)
- Marathon failed to deploy in loop with docker image pull, no errors [\#2535](https://github.com/mesosphere/marathon/issues/2535)
- Mesos details [\#2534](https://github.com/mesosphere/marathon/issues/2534)
- Add a link to API-Doc in the UI [\#2500](https://github.com/mesosphere/marathon/issues/2500)
- Config change not updating docker volumes [\#2499](https://github.com/mesosphere/marathon/issues/2499)
- Marathon gem in the documentation [\#2494](https://github.com/mesosphere/marathon/issues/2494)
-  mem NOT SATISFIED [\#2492](https://github.com/mesosphere/marathon/issues/2492)
- Wrong font size in "Health Checks" section [\#2487](https://github.com/mesosphere/marathon/issues/2487)
- Update docs on COMMAND health checks for dockerized apps [\#2471](https://github.com/mesosphere/marathon/issues/2471)
- Trim Docker images again for production images [\#2460](https://github.com/mesosphere/marathon/issues/2460)
- Never recover from race condition when scaling up [\#2417](https://github.com/mesosphere/marathon/issues/2417)
- Looks like marathon\_store\_timeout is not used any longer [\#2372](https://github.com/mesosphere/marathon/issues/2372)
- Document Plugin Mechanism [\#2344](https://github.com/mesosphere/marathon/issues/2344)
- Document Security Features [\#2339](https://github.com/mesosphere/marathon/issues/2339)
- IntegrationTest failed: SingleAppScalingTest  create/stop app with 100 instances [\#2321](https://github.com/mesosphere/marathon/issues/2321)
- Using docker w/ application groups [\#2292](https://github.com/mesosphere/marathon/issues/2292)
- Shaky Test: MarathonSchedulerActorTest "Forced deployment" [\#2195](https://github.com/mesosphere/marathon/issues/2195)
- Marathon returns bad error when framework auth secret is too short [\#2169](https://github.com/mesosphere/marathon/issues/2169)
- Breaking line indentation: pick a style [\#2163](https://github.com/mesosphere/marathon/issues/2163)
- Clearing the last item in a duplicable list [\#2120](https://github.com/mesosphere/marathon/issues/2120)
- Add support for AuthN+Z. [\#1902](https://github.com/mesosphere/marathon/issues/1902)
- Missing /help pages [\#1356](https://github.com/mesosphere/marathon/issues/1356)
- REST API does not document responses [\#1054](https://github.com/mesosphere/marathon/issues/1054)
- No error feedback on undeployable tasks [\#951](https://github.com/mesosphere/marathon/issues/951)

**Merged pull requests:**

- Update Marathon UI version to 0.13.1 [\#2561](https://github.com/mesosphere/marathon/pull/2561) ([philipnrmn](https://github.com/philipnrmn))
- Update Marathon UI version to 0.13.0 [\#2560](https://github.com/mesosphere/marathon/pull/2560) ([philipnrmn](https://github.com/philipnrmn))
- Fixes 2550 by changing the order if the leader got elected. [\#2551](https://github.com/mesosphere/marathon/pull/2551) ([aquamatthias](https://github.com/aquamatthias))
- Add Argus to companies list [\#2536](https://github.com/mesosphere/marathon/pull/2536) ([alon-argus](https://github.com/alon-argus))
- Fixes 2532 by defining a specific timeout, which is by default bigger than the zk timeout [\#2533](https://github.com/mesosphere/marathon/pull/2533) ([aquamatthias](https://github.com/aquamatthias))
- Define Base RAML path relatively. [\#2530](https://github.com/mesosphere/marathon/pull/2530) ([aquamatthias](https://github.com/aquamatthias))
- The RAML Console loads the files from /public/api/api.raml [\#2526](https://github.com/mesosphere/marathon/pull/2526) ([aquamatthias](https://github.com/aquamatthias))
- Added changelog for 0.13 [\#2519](https://github.com/mesosphere/marathon/pull/2519) ([aquamatthias](https://github.com/aquamatthias))
- Changelog for 0.13.0 - UI [\#2518](https://github.com/mesosphere/marathon/pull/2518) ([mwasn](https://github.com/mwasn))
- Fixes EntityStoreCacheTest: Fetching a versioned entry will delegate … [\#2517](https://github.com/mesosphere/marathon/pull/2517) ([meichstedt](https://github.com/meichstedt))
- Changelog for 0.13.0 [\#2512](https://github.com/mesosphere/marathon/pull/2512) ([mwasn](https://github.com/mwasn))
- Fix SingleAppScalingTest by omitting the reconciliation case. [\#2510](https://github.com/mesosphere/marathon/pull/2510) ([aquamatthias](https://github.com/aquamatthias))
- Use sessionTimeout for session timeout. [\#2504](https://github.com/mesosphere/marathon/pull/2504) ([aquamatthias](https://github.com/aquamatthias))
- corrects documentation for current step of deployment events [\#2503](https://github.com/mesosphere/marathon/pull/2503) ([pbnsilva](https://github.com/pbnsilva))
- Fixes 2494 - Remove mentions of Marathon gem from docs [\#2496](https://github.com/mesosphere/marathon/pull/2496) ([gkleiman](https://github.com/gkleiman))
- Omit classpath from ProcessKeeper output [\#2495](https://github.com/mesosphere/marathon/pull/2495) ([gkleiman](https://github.com/gkleiman))
- Fixes \#1429 - upgrade play-json version [\#2490](https://github.com/mesosphere/marathon/pull/2490) ([gkleiman](https://github.com/gkleiman))
- Make travis do assembly instead of test. [\#2488](https://github.com/mesosphere/marathon/pull/2488) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2372 Mark `marathonStoreTimeout` as deprecated [\#2486](https://github.com/mesosphere/marathon/pull/2486) ([janisz](https://github.com/janisz))
- Change return type of StartingBehaviour\#receive [\#2485](https://github.com/mesosphere/marathon/pull/2485) ([gkleiman](https://github.com/gkleiman))
- Cleanup MarathonModule [\#2484](https://github.com/mesosphere/marathon/pull/2484) ([gkleiman](https://github.com/gkleiman))
- Fixes \#1835 by creating a deployment for kill with scale, which will … [\#2483](https://github.com/mesosphere/marathon/pull/2483) ([aquamatthias](https://github.com/aquamatthias))
- Exclude JCL from the dependencies. [\#2481](https://github.com/mesosphere/marathon/pull/2481) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2477 by using the current development version and the right task repo [\#2480](https://github.com/mesosphere/marathon/pull/2480) ([aquamatthias](https://github.com/aquamatthias))
- Remove unnecessary braces. [\#2479](https://github.com/mesosphere/marathon/pull/2479) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2147 - Remove unnecessary assertions [\#2475](https://github.com/mesosphere/marathon/pull/2475) ([janisz](https://github.com/janisz))
- Fixes \#1988 - Move from log4j to logback [\#2474](https://github.com/mesosphere/marathon/pull/2474) ([gkleiman](https://github.com/gkleiman))
- \[0.11\] Add datadog and graphite reporter [\#2470](https://github.com/mesosphere/marathon/pull/2470) ([aquamatthias](https://github.com/aquamatthias))
- Add v0.11.1 to the changelog [\#2469](https://github.com/mesosphere/marathon/pull/2469) ([gkleiman](https://github.com/gkleiman))
- Port max apps patches from 0.11 to master [\#2468](https://github.com/mesosphere/marathon/pull/2468) ([kolloch](https://github.com/kolloch))
- Cherry-picked task update changes from 0.11 to master [\#2467](https://github.com/mesosphere/marathon/pull/2467) ([kolloch](https://github.com/kolloch))
- Increase timeout for larger deployment [\#2466](https://github.com/mesosphere/marathon/pull/2466) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1730 - Add uptime metric [\#2465](https://github.com/mesosphere/marathon/pull/2465) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2460 - Provide different dev/prod Dockerfiles [\#2464](https://github.com/mesosphere/marathon/pull/2464) ([kolloch](https://github.com/kolloch))
- Update Marathon for Mesos 0.25.0. [\#2462](https://github.com/mesosphere/marathon/pull/2462) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update Marathon version in GH Pages [\#2458](https://github.com/mesosphere/marathon/pull/2458) ([gkleiman](https://github.com/gkleiman))
- Add graphite and datadog metrics reporter [\#2457](https://github.com/mesosphere/marathon/pull/2457) ([aquamatthias](https://github.com/aquamatthias))
- Improve dockerfile caching [\#2444](https://github.com/mesosphere/marathon/pull/2444) ([kolloch](https://github.com/kolloch))
- Fixes \#2405 0.13 migration failure [\#2438](https://github.com/mesosphere/marathon/pull/2438) ([meichstedt](https://github.com/meichstedt))
- Fix the seed. [\#2423](https://github.com/mesosphere/marathon/pull/2423) ([aquamatthias](https://github.com/aquamatthias))
- Add storage cache layer. [\#2411](https://github.com/mesosphere/marathon/pull/2411) ([aquamatthias](https://github.com/aquamatthias))
- Genesis of RAML based Rest API documentation. [\#2351](https://github.com/mesosphere/marathon/pull/2351) ([aquamatthias](https://github.com/aquamatthias))
- allow disabling syslog via /etc/marathon/conf/?no-logger' [\#2241](https://github.com/mesosphere/marathon/pull/2241) ([rboyer](https://github.com/rboyer))

## [v0.11.1](https://github.com/mesosphere/marathon/tree/v0.11.1) (2015-10-15)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.1-RC1...v0.11.1)

**Fixed bugs:**

- AppRestart deployments don't wait for old tasks to be killed [\#2441](https://github.com/mesosphere/marathon/issues/2441)

**Closed issues:**

- Application won't start on host \(Insufficient resources\) after task fails on host [\#2346](https://github.com/mesosphere/marathon/issues/2346)

**Merged pull requests:**

- Disable ZK compression by default [\#2455](https://github.com/mesosphere/marathon/pull/2455) ([gkleiman](https://github.com/gkleiman))
- Document ZK Compression flags [\#2454](https://github.com/mesosphere/marathon/pull/2454) ([gkleiman](https://github.com/gkleiman))
- Make --max\_apps optional for 0.11 \(backward compatible\) [\#2453](https://github.com/mesosphere/marathon/pull/2453) ([aquamatthias](https://github.com/aquamatthias))
- Document ZK Compression flags [\#2452](https://github.com/mesosphere/marathon/pull/2452) ([gkleiman](https://github.com/gkleiman))
- Add v0.11.1 changelog [\#2451](https://github.com/mesosphere/marathon/pull/2451) ([gkleiman](https://github.com/gkleiman))
- Add documentation and set the default value explicitly. [\#2428](https://github.com/mesosphere/marathon/pull/2428) ([aquamatthias](https://github.com/aquamatthias))

## [v0.11.1-RC1](https://github.com/mesosphere/marathon/tree/v0.11.1-RC1) (2015-10-14)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC6...v0.11.1-RC1)

**Implemented enhancements:**

- Generic handler for 4XX and 5XX error codes [\#2420](https://github.com/mesosphere/marathon/issues/2420)
- Make keyboard shortcuts discoverable [\#2031](https://github.com/mesosphere/marathon/issues/2031)

**Fixed bugs:**

- Error: Invalid calling object \(Win 8 IE10, Win 7 IE11\) [\#2421](https://github.com/mesosphere/marathon/issues/2421)
- Marathon stops apps instead of restart [\#2381](https://github.com/mesosphere/marathon/issues/2381)
- Fixes \#2381 - propagate task updates in defined order [\#2427](https://github.com/mesosphere/marathon/pull/2427) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Handle apps error response attribute on HTTP 422 [\#2422](https://github.com/mesosphere/marathon/issues/2422)

**Merged pull requests:**

- Remove unnecessary logging. [\#2442](https://github.com/mesosphere/marathon/pull/2442) ([aquamatthias](https://github.com/aquamatthias))
- Dockerfile\*: Separate resolving dependencies [\#2437](https://github.com/mesosphere/marathon/pull/2437) ([kolloch](https://github.com/kolloch))
- \[0.11\] Remove manual created equals method and rely on the scalac generated one [\#2436](https://github.com/mesosphere/marathon/pull/2436) ([aquamatthias](https://github.com/aquamatthias))
- \[0.11\] Restrict the number of maximal apps via configuration. [\#2435](https://github.com/mesosphere/marathon/pull/2435) ([aquamatthias](https://github.com/aquamatthias))
- Use chaos version 0.8.1. [\#2433](https://github.com/mesosphere/marathon/pull/2433) ([aquamatthias](https://github.com/aquamatthias))
- Add configurable zk node compression. [\#2418](https://github.com/mesosphere/marathon/pull/2418) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2369 - Increase default --task\_launch\_confirm\_timeout [\#2415](https://github.com/mesosphere/marathon/pull/2415) ([gkleiman](https://github.com/gkleiman))
- Add plugin management documentation. [\#2355](https://github.com/mesosphere/marathon/pull/2355) ([aquamatthias](https://github.com/aquamatthias))

## [v0.10.2-RC6](https://github.com/mesosphere/marathon/tree/v0.10.2-RC6) (2015-10-13)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC5...v0.10.2-RC6)

**Fixed bugs:**

- \[0.11\] Runtime privilege checkbox does not work [\#2402](https://github.com/mesosphere/marathon/issues/2402)
- \[0.11\] Blank docker image is created in app modal [\#2398](https://github.com/mesosphere/marathon/issues/2398)
- How to create app via rest-api with v0.11.0? [\#2397](https://github.com/mesosphere/marathon/issues/2397)
- Large file URIs cause "Failed to fetch all URIs for container" error when pulling from HDFS. [\#2369](https://github.com/mesosphere/marathon/issues/2369)
- PUT /v2/groups triggers restart while PUT /v2/apps does not [\#2360](https://github.com/mesosphere/marathon/issues/2360)
- \[0.11\] Never recover from race condition when scaling up [\#2353](https://github.com/mesosphere/marathon/issues/2353)
- \[0.11\] Fixes \#2353 - Race condition in scaling app [\#2407](https://github.com/mesosphere/marathon/pull/2407) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Failed to connect error potentially due to double '/' when redirected to Mesos task page. [\#2410](https://github.com/mesosphere/marathon/issues/2410)
- marathon app update documentation misleading \(requires file\) [\#2409](https://github.com/mesosphere/marathon/issues/2409)
- Parameters in the Docker container settings are not taken into account [\#2338](https://github.com/mesosphere/marathon/issues/2338)

**Merged pull requests:**

- Add configurable zk node compression. [\#2413](https://github.com/mesosphere/marathon/pull/2413) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2360 the same app definition does not trigger a restart [\#2406](https://github.com/mesosphere/marathon/pull/2406) ([aquamatthias](https://github.com/aquamatthias))
- Raise UI version number to 0.11.2 [\#2403](https://github.com/mesosphere/marathon/pull/2403) ([philipnrmn](https://github.com/philipnrmn))
- Rename Group\#updateApp to Group\#updateApps [\#2401](https://github.com/mesosphere/marathon/pull/2401) ([gkleiman](https://github.com/gkleiman))
- Remove dead code [\#2400](https://github.com/mesosphere/marathon/pull/2400) ([gkleiman](https://github.com/gkleiman))
- Efficiently create groups/apps in constant time \(was exponential\). [\#2399](https://github.com/mesosphere/marathon/pull/2399) ([aquamatthias](https://github.com/aquamatthias))
- Warn about 0.11 in changelog. [\#2394](https://github.com/mesosphere/marathon/pull/2394) ([kolloch](https://github.com/kolloch))
- Variable in /etc/default/marathon should be exported to take effect [\#2328](https://github.com/mesosphere/marathon/pull/2328) ([surdy](https://github.com/surdy))

## [v0.10.2-RC5](https://github.com/mesosphere/marathon/tree/v0.10.2-RC5) (2015-10-09)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC4...v0.10.2-RC5)

## [v0.10.2-RC4](https://github.com/mesosphere/marathon/tree/v0.10.2-RC4) (2015-10-09)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC3...v0.10.2-RC4)

**Implemented enhancements:**

- Cache GET request to /v2/apps, /v2/tasks, /v2/deployments [\#2391](https://github.com/mesosphere/marathon/pull/2391) ([meichstedt](https://github.com/meichstedt))

**Closed issues:**

- Marathon 0.11 ubuntu package looks to be broken [\#2384](https://github.com/mesosphere/marathon/issues/2384)
- mesosphere.mesos.ResourceMatcher bug on 0.11.0? [\#2375](https://github.com/mesosphere/marathon/issues/2375)

**Merged pull requests:**

- Only throttle non-GET requests [\#2389](https://github.com/mesosphere/marathon/pull/2389) ([meichstedt](https://github.com/meichstedt))
- Make the maximum number of apps configurable via --max\_apps [\#2388](https://github.com/mesosphere/marathon/pull/2388) ([meichstedt](https://github.com/meichstedt))
- Efficiently create groups/apps in  time \(was exponential\). [\#2387](https://github.com/mesosphere/marathon/pull/2387) ([aquamatthias](https://github.com/aquamatthias))
- Scale fixes tmp [\#2386](https://github.com/mesosphere/marathon/pull/2386) ([aquamatthias](https://github.com/aquamatthias))

## [v0.10.2-RC3](https://github.com/mesosphere/marathon/tree/v0.10.2-RC3) (2015-10-08)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.12.0-RC1...v0.10.2-RC3)

**Implemented enhancements:**

- Implementations of PersistentStore should log requests [\#2359](https://github.com/mesosphere/marathon/issues/2359)
- TaskTracker should use EntityStore [\#2282](https://github.com/mesosphere/marathon/issues/2282)

**Fixed bugs:**

- Problems displaying long app labels in Filter View [\#2374](https://github.com/mesosphere/marathon/issues/2374)
- IGNORE THIS - Zapier Transfer Test [\#2371](https://github.com/mesosphere/marathon/issues/2371)
- Latest Marathon package doesn't install on Ubuntu 14.04 [\#2357](https://github.com/mesosphere/marathon/issues/2357)
- Fixes small formatting issue in GET /logging [\#2362](https://github.com/mesosphere/marathon/pull/2362) ([mwasn](https://github.com/mwasn))

**Closed issues:**

- /v2/events does not delimit messages correctly [\#2380](https://github.com/mesosphere/marathon/issues/2380)
- Web interface does not handle container parameters correctly [\#2370](https://github.com/mesosphere/marathon/issues/2370)
- URIs files not found in the folder [\#2312](https://github.com/mesosphere/marathon/issues/2312)
- Refactor UI messages into constants as introduced in \#299 [\#2288](https://github.com/mesosphere/marathon/issues/2288)

**Merged pull requests:**

- Restrict the number of apps to 500. [\#2383](https://github.com/mesosphere/marathon/pull/2383) ([aquamatthias](https://github.com/aquamatthias))
- The ec for async IO should not use the bounded ForkJoin Pool. [\#2376](https://github.com/mesosphere/marathon/pull/2376) ([aquamatthias](https://github.com/aquamatthias))
- Upgrade Chaos to v0.7.2 [\#2368](https://github.com/mesosphere/marathon/pull/2368) ([gkleiman](https://github.com/gkleiman))
- AppDeployIntegrationTest: Wait for rollback deployment \(master\) [\#2367](https://github.com/mesosphere/marathon/pull/2367) ([kolloch](https://github.com/kolloch))
- AppDeployIntegrationTest: Wait for rollback deployment \(releasing-0.10\) [\#2366](https://github.com/mesosphere/marathon/pull/2366) ([kolloch](https://github.com/kolloch))
- Add metrics to all GroupRepository operations [\#2365](https://github.com/mesosphere/marathon/pull/2365) ([gkleiman](https://github.com/gkleiman))
- Corrected typo on health checks documentation page [\#2361](https://github.com/mesosphere/marathon/pull/2361) ([zemanel](https://github.com/zemanel))
- Changelog for 0.12 [\#2358](https://github.com/mesosphere/marathon/pull/2358) ([aquamatthias](https://github.com/aquamatthias))
- Remove FLAG deprecation notice [\#2356](https://github.com/mesosphere/marathon/pull/2356) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2352 - Update healtcheck documentation [\#2354](https://github.com/mesosphere/marathon/pull/2354) ([gkleiman](https://github.com/gkleiman))
- Make TaskTracker use EntityStore [\#2305](https://github.com/mesosphere/marathon/pull/2305) ([meichstedt](https://github.com/meichstedt))

## [v0.12.0-RC1](https://github.com/mesosphere/marathon/tree/v0.12.0-RC1) (2015-10-05)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.0...v0.12.0-RC1)

**Implemented enhancements:**

- UI Enhancement: Add column for number of times an app failed in its current form [\#1842](https://github.com/mesosphere/marathon/issues/1842)

**Fixed bugs:**

- Racy deployment creation [\#1407](https://github.com/mesosphere/marathon/issues/1407)

**Closed issues:**

- What is "Command health checks are currently not compatible with dockerized tasks." [\#2352](https://github.com/mesosphere/marathon/issues/2352)
- Marathon trigger happy with killing overdue tasks [\#2349](https://github.com/mesosphere/marathon/issues/2349)
- Add error if user adds an app with unknown properties [\#2341](https://github.com/mesosphere/marathon/issues/2341)
- Image v0.11.0 with errors [\#2337](https://github.com/mesosphere/marathon/issues/2337)
- "No pseudo-deterministic assignment of host ports anymore" - Should be labeled as breaking change? [\#2336](https://github.com/mesosphere/marathon/issues/2336)
- Refactor duplicable rows panels for DRYness [\#2315](https://github.com/mesosphere/marathon/issues/2315)
- healthcheck ports messing with docker and "host" networking mode [\#2313](https://github.com/mesosphere/marathon/issues/2313)
- Add Marathon 0.11 rc 1 into Multiverse [\#2251](https://github.com/mesosphere/marathon/issues/2251)
- Create Example AuthN/Z plugin [\#2243](https://github.com/mesosphere/marathon/issues/2243)
- Make row mappings in app modal more generic [\#2038](https://github.com/mesosphere/marathon/issues/2038)
- Consolidate logging [\#1988](https://github.com/mesosphere/marathon/issues/1988)

**Merged pull requests:**

- Remove filtering tasks with app id from list of tasks... [\#2350](https://github.com/mesosphere/marathon/pull/2350) ([kolloch](https://github.com/kolloch))
- Update CHANGELOG with UI section [\#2345](https://github.com/mesosphere/marathon/pull/2345) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Raise UI version to 0.13.0-SNAPSHOT [\#2343](https://github.com/mesosphere/marathon/pull/2343) ([aldipower](https://github.com/aldipower))
- Update ui to 0.12.0 release [\#2342](https://github.com/mesosphere/marathon/pull/2342) ([orlandohohmeier](https://github.com/orlandohohmeier))
- Define also slf4j as provided plugin dependency. [\#2340](https://github.com/mesosphere/marathon/pull/2340) ([aquamatthias](https://github.com/aquamatthias))
- Docs update for Marathon 0.11.0 [\#2334](https://github.com/mesosphere/marathon/pull/2334) ([aquamatthias](https://github.com/aquamatthias))

## [v0.11.0](https://github.com/mesosphere/marathon/tree/v0.11.0) (2015-10-01)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.0-RC5...v0.11.0)

**Implemented enhancements:**

- Create a health checks panel in the application creation/edit modal dialog [\#2131](https://github.com/mesosphere/marathon/issues/2131)

**Fixed bugs:**

- /v2/group/\<group\_id\>/versions will serialize the Iterable which is not usable [\#2329](https://github.com/mesosphere/marathon/issues/2329)
- HDFS doesn't complete Deployment on Testing Branch [\#2290](https://github.com/mesosphere/marathon/issues/2290)

**Closed issues:**

- Get app's hostname from Rest API [\#2331](https://github.com/mesosphere/marathon/issues/2331)
- Different apps on different hosts [\#2330](https://github.com/mesosphere/marathon/issues/2330)
- Implement consistent behaviour on 409 \(Conflict\) to force deployments [\#2298](https://github.com/mesosphere/marathon/issues/2298)
- Marathon 0.12 should use mesos-utils 0.24 [\#2230](https://github.com/mesosphere/marathon/issues/2230)
- Reflect application list filters in the URL [\#2135](https://github.com/mesosphere/marathon/issues/2135)
- document HOWTO execute a blue/green deployment [\#2075](https://github.com/mesosphere/marathon/issues/2075)
- Replace util.serializedArrayToDictionary with object-path.set/insert\(\) [\#2027](https://github.com/mesosphere/marathon/issues/2027)

**Merged pull requests:**

- Fixes \#2329 /v2/group/\<group\_id\>/versions will serialize the Iterable which is not usable [\#2333](https://github.com/mesosphere/marathon/pull/2333) ([aquamatthias](https://github.com/aquamatthias))
- Updating link to Github issues [\#2332](https://github.com/mesosphere/marathon/pull/2332) ([matsluni](https://github.com/matsluni))
- Don't use FATAL markers for logging [\#2324](https://github.com/mesosphere/marathon/pull/2324) ([gkleiman](https://github.com/gkleiman))
- Bump chaos version to 0.8.0 [\#2323](https://github.com/mesosphere/marathon/pull/2323) ([aquamatthias](https://github.com/aquamatthias))
- Raise UI snapshot version to 0.12.0 [\#2320](https://github.com/mesosphere/marathon/pull/2320) ([aldipower](https://github.com/aldipower))
- ResourceMatcher: reduce loglevel for unmet constraints [\#2316](https://github.com/mesosphere/marathon/pull/2316) ([felixb](https://github.com/felixb))
- Introduce Interfaces for AuthN and AuthZ. [\#2233](https://github.com/mesosphere/marathon/pull/2233) ([aquamatthias](https://github.com/aquamatthias))
- Fix \#2230 use mesos version 0.24.1 [\#2231](https://github.com/mesosphere/marathon/pull/2231) ([aquamatthias](https://github.com/aquamatthias))

## [v0.11.0-RC5](https://github.com/mesosphere/marathon/tree/v0.11.0-RC5) (2015-09-28)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.0-RC4...v0.11.0-RC5)

**Fixed bugs:**

- Overlapping text in Deployment view [\#2270](https://github.com/mesosphere/marathon/issues/2270)
- Do not show \(x\) in keyword search input until user begins typing [\#2216](https://github.com/mesosphere/marathon/issues/2216)

**Closed issues:**

- Redirect of / should be relative \(ui/ not /ui/\) [\#2317](https://github.com/mesosphere/marathon/issues/2317)
- Accepted resource roles schould be setable in the application creation form [\#2309](https://github.com/mesosphere/marathon/issues/2309)
- Marathon restarts tasks certain tasks during failover [\#2308](https://github.com/mesosphere/marathon/issues/2308)
- how to launch a zookeeper cluster in marathon? [\#2250](https://github.com/mesosphere/marathon/issues/2250)
- Create Design Document for persistent offers and dynamic reservations [\#2242](https://github.com/mesosphere/marathon/issues/2242)
- Add installation guide for native packages \(especially java8 related\) [\#2173](https://github.com/mesosphere/marathon/issues/2173)
- Tests for ModalDialogs [\#2138](https://github.com/mesosphere/marathon/issues/2138)
- UI: Add optional field for "user" in app definition [\#2127](https://github.com/mesosphere/marathon/issues/2127)
- $PORT out of sync or not updated correctly [\#1707](https://github.com/mesosphere/marathon/issues/1707)
- Add app labels to UI. [\#1055](https://github.com/mesosphere/marathon/issues/1055)

**Merged pull requests:**

- Raise UI version to 0.11.1 [\#2319](https://github.com/mesosphere/marathon/pull/2319) ([aldipower](https://github.com/aldipower))
- Fixes: \#2317 Redirect of / should be relative \(ui/ not /ui/\) [\#2318](https://github.com/mesosphere/marathon/pull/2318) ([aquamatthias](https://github.com/aquamatthias))
- Adding the use of JAVA\_HOME within marathon-framework. [\#2310](https://github.com/mesosphere/marathon/pull/2310) ([sledigabel](https://github.com/sledigabel))
- improve handling of exceptions for /v2/apps [\#2302](https://github.com/mesosphere/marathon/pull/2302) ([tamarrow](https://github.com/tamarrow))

## [v0.11.0-RC4](https://github.com/mesosphere/marathon/tree/v0.11.0-RC4) (2015-09-24)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.0-RC3...v0.11.0-RC4)

**Implemented enhancements:**

- Better error handling on application configuration change/creation  [\#2262](https://github.com/mesosphere/marathon/issues/2262)

**Fixed bugs:**

- Make boolean command line flags use Scallop's 'toggle' [\#2294](https://github.com/mesosphere/marathon/issues/2294)
- Marathon accepted app update for new docker, but didn't deploy task [\#2293](https://github.com/mesosphere/marathon/issues/2293)
- Disabling --ha and --checkpoint on command line [\#2272](https://github.com/mesosphere/marathon/issues/2272)
- Redirect to /ui/ doesn't work if Marathon is proxied [\#2267](https://github.com/mesosphere/marathon/issues/2267)
- Link "Mesos details" is broken [\#2266](https://github.com/mesosphere/marathon/issues/2266)
- Cannot submit job with id containing internal slashes [\#2264](https://github.com/mesosphere/marathon/issues/2264)
- Health Check Timeout Never Resolves to Healthy or Unhealthy Service [\#2078](https://github.com/mesosphere/marathon/issues/2078)

**Closed issues:**

- Cannot seem to change defaults through upstart or env variables [\#2291](https://github.com/mesosphere/marathon/issues/2291)
- /v2/events doesn't play well with JS EventSource [\#2289](https://github.com/mesosphere/marathon/issues/2289)
- cmdline switch --mesos\_user has no effect [\#2285](https://github.com/mesosphere/marathon/issues/2285)
- Expose the application dependencies field in the configuration tab [\#2284](https://github.com/mesosphere/marathon/issues/2284)
- Expose the application labels field in the configuration tab [\#2283](https://github.com/mesosphere/marathon/issues/2283)
- \#209 0 values in ports field are stripped [\#2278](https://github.com/mesosphere/marathon/issues/2278)
- \#209 Unfold optional panels which contain errors when editing [\#2276](https://github.com/mesosphere/marathon/issues/2276)
- \#209 Unify client-side validation error UI [\#2275](https://github.com/mesosphere/marathon/issues/2275)
- \#209 Remove duplicable row headers [\#2274](https://github.com/mesosphere/marathon/issues/2274)
- UI doesn't expose roles [\#2263](https://github.com/mesosphere/marathon/issues/2263)
- Task Health no longer displayed on app page [\#2261](https://github.com/mesosphere/marathon/issues/2261)
- Could not determine the current leader [\#2260](https://github.com/mesosphere/marathon/issues/2260)
- Dynamic Volume Mounts? [\#2259](https://github.com/mesosphere/marathon/issues/2259)
- Exception after reregistration "A metric named ... already exists" [\#2254](https://github.com/mesosphere/marathon/issues/2254)
- Wrong task number in Debug Tab  [\#2252](https://github.com/mesosphere/marathon/issues/2252)
- Docker: port mappings do not make sense when host network is used  [\#2248](https://github.com/mesosphere/marathon/issues/2248)
- Task Life Time number is very precise \(rounding needed\) [\#2240](https://github.com/mesosphere/marathon/issues/2240)
- POST /v2/apps 409 response is undocumented [\#2235](https://github.com/mesosphere/marathon/issues/2235)
- Display life time duration as other durations in UI [\#2223](https://github.com/mesosphere/marathon/issues/2223)
- Handle Auth Errors in UI [\#2194](https://github.com/mesosphere/marathon/issues/2194)
- COMMAND Health Check does not resume after failure? [\#2179](https://github.com/mesosphere/marathon/issues/2179)
- Create public interface for AuthZ/AuthN [\#2150](https://github.com/mesosphere/marathon/issues/2150)
- Refactor \#2147 workarounds [\#2148](https://github.com/mesosphere/marathon/issues/2148)
- Refactor the application create/edit modal data handling [\#2105](https://github.com/mesosphere/marathon/issues/2105)
- Tests for app modal [\#2098](https://github.com/mesosphere/marathon/issues/2098)
- Create universe package for 0.10.1 [\#2019](https://github.com/mesosphere/marathon/issues/2019)
- Docker container settings dialog needs better error handling [\#1985](https://github.com/mesosphere/marathon/issues/1985)

**Merged pull requests:**

- Send redirects as relative URL \(without Host\) [\#2306](https://github.com/mesosphere/marathon/pull/2306) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#1988 - Consolidate logging [\#2300](https://github.com/mesosphere/marathon/pull/2300) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2294 - Make boolean command line flags use Scallop's 'toggle'  [\#2296](https://github.com/mesosphere/marathon/pull/2296) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2264 - Fix validation of app id in AppDefinition.json [\#2286](https://github.com/mesosphere/marathon/pull/2286) ([kolloch](https://github.com/kolloch))
- Fixes \#2235 POST /v2/apps 409 response [\#2279](https://github.com/mesosphere/marathon/pull/2279) ([mwasn](https://github.com/mwasn))
- Fixes \#2254 prevent metrics registration upon regaining leadership \(please cherry-pick into 0.11\) [\#2269](https://github.com/mesosphere/marathon/pull/2269) ([meichstedt](https://github.com/meichstedt))
- Acknowledged YourKit OSS license in README. [\#2265](https://github.com/mesosphere/marathon/pull/2265) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Tried to clarify the concept of service ports [\#2239](https://github.com/mesosphere/marathon/pull/2239) ([kolloch](https://github.com/kolloch))
- Optimization: Use Iterable instead of Set for tasks in resource matching [\#2219](https://github.com/mesosphere/marathon/pull/2219) ([kolloch](https://github.com/kolloch))

## [v0.11.0-RC3](https://github.com/mesosphere/marathon/tree/v0.11.0-RC3) (2015-09-16)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC2...v0.11.0-RC3)

## [v0.10.2-RC2](https://github.com/mesosphere/marathon/tree/v0.10.2-RC2) (2015-09-16)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.2-RC1...v0.10.2-RC2)

## [v0.10.2-RC1](https://github.com/mesosphere/marathon/tree/v0.10.2-RC1) (2015-09-16)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.0-RC2...v0.10.2-RC1)

**Closed issues:**

- Force suspend/scale in UI [\#2246](https://github.com/mesosphere/marathon/issues/2246)
- Ability to scale an application forcefully if there is a deployment running [\#2244](https://github.com/mesosphere/marathon/issues/2244)
- Health checks stop when app is scaled [\#2234](https://github.com/mesosphere/marathon/issues/2234)
- POST to /v2/apps on non-leader doesn't work [\#2227](https://github.com/mesosphere/marathon/issues/2227)
- Why does marathon need to resolve the hostname of the node it runs on when --hostname is set? [\#2153](https://github.com/mesosphere/marathon/issues/2153)
- Marathon should optionally log all configuration values. [\#1908](https://github.com/mesosphere/marathon/issues/1908)
- Integration Tests currently shaky [\#1655](https://github.com/mesosphere/marathon/issues/1655)
- Random IP publishing - Marathon Scheduler [\#1198](https://github.com/mesosphere/marathon/issues/1198)

**Merged pull requests:**

- Move to Chaos 0.7.0 [\#2258](https://github.com/mesosphere/marathon/pull/2258) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#2220 - Added --task\_launch\_confirm\_timeout [\#2257](https://github.com/mesosphere/marathon/pull/2257) ([meichstedt](https://github.com/meichstedt))
- Clarify that portMappings are for BRIDGE networking [\#2238](https://github.com/mesosphere/marathon/pull/2238) ([kolloch](https://github.com/kolloch))
- Improve simulation and task confirmation timeout [\#2221](https://github.com/mesosphere/marathon/pull/2221) ([kolloch](https://github.com/kolloch))
- Fix \#1901 - Implement an external plugin loader [\#2188](https://github.com/mesosphere/marathon/pull/2188) ([gkleiman](https://github.com/gkleiman))

## [v0.11.0-RC2](https://github.com/mesosphere/marathon/tree/v0.11.0-RC2) (2015-09-10)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.11.0-RC1...v0.11.0-RC2)

**Fixed bugs:**

- new /ui path broken in HA mode: non-leaders must not follow 302s from leader [\#2225](https://github.com/mesosphere/marathon/issues/2225)

**Closed issues:**

- Marathon 0.11 should use mesos-utils 0.23 [\#2228](https://github.com/mesosphere/marathon/issues/2228)
- Marathon can't do anything after master failover [\#2207](https://github.com/mesosphere/marathon/issues/2207)

**Merged pull requests:**

- Fix \#2228 use mesos version 0.23.0 [\#2229](https://github.com/mesosphere/marathon/pull/2229) ([aquamatthias](https://github.com/aquamatthias))
- Fix \#2225 ProxyFilter should not follow redirects [\#2226](https://github.com/mesosphere/marathon/pull/2226) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1900 - Add a marathon-interface project [\#2151](https://github.com/mesosphere/marathon/pull/2151) ([gkleiman](https://github.com/gkleiman))

## [v0.11.0-RC1](https://github.com/mesosphere/marathon/tree/v0.11.0-RC1) (2015-09-09)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.1...v0.11.0-RC1)

**Implemented enhancements:**

- Display health checks in the application configuration tab [\#2133](https://github.com/mesosphere/marathon/issues/2133)
- App detail view refresh button is inconsistent [\#2116](https://github.com/mesosphere/marathon/issues/2116)
- UI should specify Accept header in requests to API [\#2108](https://github.com/mesosphere/marathon/issues/2108)
- Marathon should set a non-default filter when declining offers \(on master\) [\#1931](https://github.com/mesosphere/marathon/issues/1931)
- Configurable refuseTimeout for offers [\#1558](https://github.com/mesosphere/marathon/issues/1558)
- Fixes \#2009 - Export task life time in API [\#2149](https://github.com/mesosphere/marathon/pull/2149) ([kolloch](https://github.com/kolloch))

**Fixed bugs:**

- Integration Tests: Left over processes [\#2201](https://github.com/mesosphere/marathon/issues/2201)
- HealthCheckActor uses filterKeys to calculate new tasksHealth [\#2185](https://github.com/mesosphere/marathon/issues/2185)
- Make sure that reviveOffers is sent after last decline [\#2181](https://github.com/mesosphere/marathon/issues/2181)
- AppDeployIntegrationTest fails because tasks with stagedAt=0 are considered staging [\#2178](https://github.com/mesosphere/marathon/issues/2178)
- Application has no deployments object [\#2171](https://github.com/mesosphere/marathon/issues/2171)
- On master: Clarify when to reset the backoff delay and change code accordingly [\#2166](https://github.com/mesosphere/marathon/issues/2166)
- Row is off-centre if upper row is empty in lists [\#2157](https://github.com/mesosphere/marathon/issues/2157)
- Some empty fields in app modal submit bad values [\#2146](https://github.com/mesosphere/marathon/issues/2146)
- Confirm dialog should have focus on OK button [\#2144](https://github.com/mesosphere/marathon/issues/2144)
- Esc should dismiss all dialogs [\#2143](https://github.com/mesosphere/marathon/issues/2143)
- Dialog window isn't centered in IE11 [\#2137](https://github.com/mesosphere/marathon/issues/2137)
- Last task failures are not persisted [\#2130](https://github.com/mesosphere/marathon/issues/2130)
- Health isn't shown on task in task list [\#2123](https://github.com/mesosphere/marathon/issues/2123)
- Can't edit app version after applying version [\#2114](https://github.com/mesosphere/marathon/issues/2114)
- Can not remove environment variables completely in the app edit dialog [\#2094](https://github.com/mesosphere/marathon/issues/2094)
- App constraints handling in create/edit dialog broken [\#2079](https://github.com/mesosphere/marathon/issues/2079)
- Can't edit app config after inserting a space between ports [\#2072](https://github.com/mesosphere/marathon/issues/2072)
- In Marathon 0.8.2 POST /v2/apps returns 201 when the app doesn't necessarily exist [\#2070](https://github.com/mesosphere/marathon/issues/2070)
- Prevent repeated app config edit before the configuration has updated [\#2042](https://github.com/mesosphere/marathon/issues/2042)
- User Interface becomes unresponsive when running many tasks [\#1867](https://github.com/mesosphere/marathon/issues/1867)
- Marathon leaders that lose leadership kill tasks upon regaining leadership [\#1553](https://github.com/mesosphere/marathon/issues/1553)
- Fixes \#2181 - repeat reviveOffers [\#2189](https://github.com/mesosphere/marathon/pull/2189) ([kolloch](https://github.com/kolloch))
- Fixes \#2185 - materialize filterKeys result in HealthCheckActor [\#2186](https://github.com/mesosphere/marathon/pull/2186) ([kolloch](https://github.com/kolloch))
- Fixes \#2130 - Store task failures in Zookeeper [\#2136](https://github.com/mesosphere/marathon/pull/2136) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Separate timeout for launch confirmations [\#2220](https://github.com/mesosphere/marathon/issues/2220)
- portMapping not working correctly for static ports \(v 0.10.0\) [\#2215](https://github.com/mesosphere/marathon/issues/2215)
- Document how to install Java 8 in all our supported distros [\#2214](https://github.com/mesosphere/marathon/issues/2214)
- Flaky Test: GroupDeployIntegrationTest "groups with dependencies get deployed in correct order" [\#2206](https://github.com/mesosphere/marathon/issues/2206)
- Disable force push [\#2198](https://github.com/mesosphere/marathon/issues/2198)
- Extend Changelog for 0.11.0 \(UI\) [\#2196](https://github.com/mesosphere/marathon/issues/2196)
- Marathon not downloading files defined using uris parameter [\#2192](https://github.com/mesosphere/marathon/issues/2192)
- Make HTTP Retries in AppMockFacade less verbose and more reliable [\#2176](https://github.com/mesosphere/marathon/issues/2176)
- Extend and run scale test [\#2161](https://github.com/mesosphere/marathon/issues/2161)
- Document \#1931 - decline with configurable timeout [\#2158](https://github.com/mesosphere/marathon/issues/2158)
- Saner Embedded AppInfo [\#2132](https://github.com/mesosphere/marathon/issues/2132)
- cgroup question regarding number of cpu's and hard/soft limit [\#2125](https://github.com/mesosphere/marathon/issues/2125)
- Uniqueness blocks deployment even with minimumHealthCapacity=0 [\#2124](https://github.com/mesosphere/marathon/issues/2124)
- Enforce max-len in .eslintrc [\#2102](https://github.com/mesosphere/marathon/issues/2102)
- Can keyboard shortcuts interfere  [\#2033](https://github.com/mesosphere/marathon/issues/2033)
- Export task life time \(API\) [\#2009](https://github.com/mesosphere/marathon/issues/2009)
- Document \#1931 - reviveOffers configuration [\#1944](https://github.com/mesosphere/marathon/issues/1944)
- Create a plugin loader, that is able to load externally packaged plugins [\#1901](https://github.com/mesosphere/marathon/issues/1901)
- Add an interface module that can be used from external projects [\#1900](https://github.com/mesosphere/marathon/issues/1900)
- Minor refactoring: UNSPECIFIED\_NODE  [\#1725](https://github.com/mesosphere/marathon/issues/1725)
- Switching to a supported Java version [\#1544](https://github.com/mesosphere/marathon/issues/1544)

**Merged pull requests:**

- Add Known Issues section to the changelog [\#2222](https://github.com/mesosphere/marathon/pull/2222) ([gkleiman](https://github.com/gkleiman))
- 2196 UI changelog improvements [\#2218](https://github.com/mesosphere/marathon/pull/2218) ([philipnrmn](https://github.com/philipnrmn))
- Save tasks just before launching [\#2213](https://github.com/mesosphere/marathon/pull/2213) ([kolloch](https://github.com/kolloch))
- Mock LaunchQueue and TaskTracker [\#2212](https://github.com/mesosphere/marathon/pull/2212) ([aquamatthias](https://github.com/aquamatthias))
- Enhance IntegrationTests [\#2210](https://github.com/mesosphere/marathon/pull/2210) ([aquamatthias](https://github.com/aquamatthias))
- Use 3 seconds as default timeout for waiting for Futures [\#2209](https://github.com/mesosphere/marathon/pull/2209) ([kolloch](https://github.com/kolloch))
- Bigger timeout for MigrationTo0\_11Test [\#2205](https://github.com/mesosphere/marathon/pull/2205) ([kolloch](https://github.com/kolloch))
- Update README.md: Add AllUnite to companies list [\#2197](https://github.com/mesosphere/marathon/pull/2197) ([x-cray](https://github.com/x-cray))
- Remove git submodule wreckage [\#2191](https://github.com/mesosphere/marathon/pull/2191) ([okuryu](https://github.com/okuryu))
- Better test for never-ending deployment for unhealthy tasks [\#2187](https://github.com/mesosphere/marathon/pull/2187) ([kolloch](https://github.com/kolloch))
- Fixes \#2178 MarathonTask.stagedAt pre-filled with current time [\#2182](https://github.com/mesosphere/marathon/pull/2182) ([meichstedt](https://github.com/meichstedt))
- Fixes \#2176 - Make AppMockFacade retries less verbose and [\#2177](https://github.com/mesosphere/marathon/pull/2177) ([kolloch](https://github.com/kolloch))
- Fixes \#2166 - reset backoff delay for config changes and manual restarts [\#2175](https://github.com/mesosphere/marathon/pull/2175) ([kolloch](https://github.com/kolloch))
- Fix \#2171 deployments should be part of the index automatically \(back… [\#2172](https://github.com/mesosphere/marathon/pull/2172) ([aquamatthias](https://github.com/aquamatthias))
- Add troubleshooting step for secret too short [\#2168](https://github.com/mesosphere/marathon/pull/2168) ([jgarcia-mesosphere](https://github.com/jgarcia-mesosphere))
- Update README.md - adding marahton\_deploy commmand line tool [\#2167](https://github.com/mesosphere/marathon/pull/2167) ([sielaq](https://github.com/sielaq))
- Prepare changelog for 0.11 [\#2165](https://github.com/mesosphere/marathon/pull/2165) ([kolloch](https://github.com/kolloch))
- Setting the default for `--decline-offer-duration` to 120s [\#2162](https://github.com/mesosphere/marathon/pull/2162) ([kolloch](https://github.com/kolloch))
- Add github issues to the help section [\#2156](https://github.com/mesosphere/marathon/pull/2156) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Set UI version to 0.11.0 [\#2155](https://github.com/mesosphere/marathon/pull/2155) ([aldipower](https://github.com/aldipower))
- Add Note about Command Health Checks not working  with dockerized tasks. [\#2142](https://github.com/mesosphere/marathon/pull/2142) ([joerg84](https://github.com/joerg84))
- Saner extended AppInfo [\#2139](https://github.com/mesosphere/marathon/pull/2139) ([kolloch](https://github.com/kolloch))
- update download links to 0.10.1 [\#2134](https://github.com/mesosphere/marathon/pull/2134) ([meichstedt](https://github.com/meichstedt))
- Fix \#1544: Add java 8 changes to the changelog. [\#2128](https://github.com/mesosphere/marathon/pull/2128) ([aquamatthias](https://github.com/aquamatthias))
- Fix \#1931 decline with configurable duration. [\#2126](https://github.com/mesosphere/marathon/pull/2126) ([aquamatthias](https://github.com/aquamatthias))
- Use jetty9 SSE Servlet [\#2122](https://github.com/mesosphere/marathon/pull/2122) ([aquamatthias](https://github.com/aquamatthias))
- Fix \#1553 by clearing state of TaskTracker during abdication [\#2121](https://github.com/mesosphere/marathon/pull/2121) ([aquamatthias](https://github.com/aquamatthias))
- Make AppDeployIntegrationTest less shaky [\#2119](https://github.com/mesosphere/marathon/pull/2119) ([aquamatthias](https://github.com/aquamatthias))
- servicerouter: improve performance [\#2115](https://github.com/mesosphere/marathon/pull/2115) ([flosell](https://github.com/flosell))
- Fixes \#2011 - Provide app versioning information [\#2110](https://github.com/mesosphere/marathon/pull/2110) ([kolloch](https://github.com/kolloch))
- servicerouter.py: Only generate backends with valid hostname [\#2083](https://github.com/mesosphere/marathon/pull/2083) ([first-it-consulting](https://github.com/first-it-consulting))
- servicerouter: select http backend by http header X-Marathon-App-Id [\#2008](https://github.com/mesosphere/marathon/pull/2008) ([felixb](https://github.com/felixb))

## [v0.10.1](https://github.com/mesosphere/marathon/tree/v0.10.1) (2015-08-28)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.1-RC2...v0.10.1)

**Implemented enhancements:**

- Replace native alert, prompt and confirm with custom modals [\#2071](https://github.com/mesosphere/marathon/issues/2071)
- Move edit configuration button to top of config pane [\#2039](https://github.com/mesosphere/marathon/issues/2039)
- Replace JSON libraries with play-json [\#722](https://github.com/mesosphere/marathon/issues/722)

**Fixed bugs:**

- Error message breaks modal layout in Firefox [\#2100](https://github.com/mesosphere/marathon/issues/2100)
- Docker container settings doesn't look well in IE11 [\#2066](https://github.com/mesosphere/marathon/issues/2066)
- Filter input shows double X in IE11 [\#2065](https://github.com/mesosphere/marathon/issues/2065)
- Urgent: Firefox bug \#547718 and Marathon 204 responses [\#2062](https://github.com/mesosphere/marathon/issues/2062)
- Edit App causes reset of ports assigned on save [\#2058](https://github.com/mesosphere/marathon/issues/2058)
- Marathon UI keeps complaining about invalid constraint even after the constraint has been removed [\#2057](https://github.com/mesosphere/marathon/issues/2057)
- Proxying with "Expect: 100-continue" does not work correctly [\#1763](https://github.com/mesosphere/marathon/issues/1763)
- Adding constraints blocks deployment [\#1133](https://github.com/mesosphere/marathon/issues/1133)
- New App in the GUI: Optional Settings are not Optional [\#950](https://github.com/mesosphere/marathon/issues/950)
- Fixes \#2086 - Do not throw exceptions when [\#2089](https://github.com/mesosphere/marathon/pull/2089) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Do not try to deterministically assign host ports anymore [\#2107](https://github.com/mesosphere/marathon/issues/2107)
- Multiple ports are incorrectly matched [\#2091](https://github.com/mesosphere/marathon/issues/2091)
- In LeaderProxyFilter Zookeeper errors should be treated as inconsistent leadership [\#2086](https://github.com/mesosphere/marathon/issues/2086)
- Marathon REST API documentation should be able to be viewed by version. [\#2069](https://github.com/mesosphere/marathon/issues/2069)
- Inconsistent capitali{s,z}ation on new app modal [\#2068](https://github.com/mesosphere/marathon/issues/2068)
- docker should be Docker on new app modal [\#2067](https://github.com/mesosphere/marathon/issues/2067)
- Parts of the API Resources returned incorrect group JSON [\#2060](https://github.com/mesosphere/marathon/issues/2060)
- Marathon archived resources [\#2051](https://github.com/mesosphere/marathon/issues/2051)
- Empty post body on event subscription callback [\#2044](https://github.com/mesosphere/marathon/issues/2044)
- Add Endpoint IntegrationTests for AppTasksResource [\#2041](https://github.com/mesosphere/marathon/issues/2041)
- Create universe package for Marathon 0.9.2 [\#2015](https://github.com/mesosphere/marathon/issues/2015)
- Show summary about the most recent configuration change \(UI\) [\#2012](https://github.com/mesosphere/marathon/issues/2012)
- Export summary about the most recent configuration change \(API\) [\#2011](https://github.com/mesosphere/marathon/issues/2011)
- Show task life time \(UI\) [\#2010](https://github.com/mesosphere/marathon/issues/2010)
- Rewrite the GroupRepository/AppRepository logic and make it consistent [\#1898](https://github.com/mesosphere/marathon/issues/1898)
- Create UI that visualizes the Launch of thousands of Containers [\#1793](https://github.com/mesosphere/marathon/issues/1793)
- Total resource usage in UI [\#1251](https://github.com/mesosphere/marathon/issues/1251)

**Merged pull requests:**

- Improves \#1908 - log arguments on startup [\#2113](https://github.com/mesosphere/marathon/pull/2113) ([kolloch](https://github.com/kolloch))
- Fix typos in comments [\#2112](https://github.com/mesosphere/marathon/pull/2112) ([gkleiman](https://github.com/gkleiman))
- Fixes \#2107 - Don't try to use "ports" as host ports anymore [\#2111](https://github.com/mesosphere/marathon/pull/2111) ([kolloch](https://github.com/kolloch))
- Fixes \#2041 - Change Accept header in integration tests, check more result codes [\#2109](https://github.com/mesosphere/marathon/pull/2109) ([gkleiman](https://github.com/gkleiman))
- Improves \#2091 - Remove incorrect statement from the docs [\#2096](https://github.com/mesosphere/marathon/pull/2096) ([gkleiman](https://github.com/gkleiman))
- servicerouter: add performance measurement to reset\_from\_tasks [\#2093](https://github.com/mesosphere/marathon/pull/2093) ([flosell](https://github.com/flosell))
- servicerouter: make log format configurable [\#2092](https://github.com/mesosphere/marathon/pull/2092) ([flosell](https://github.com/flosell))
- Fixes \#1898 - Sync AppRepository writes with GroupRepository writes [\#2087](https://github.com/mesosphere/marathon/pull/2087) ([kolloch](https://github.com/kolloch))
- Fix typo in docs [\#2082](https://github.com/mesosphere/marathon/pull/2082) ([bobrik](https://github.com/bobrik))
- Fix TaskBuilderTest: Allow multiple port ranges in various tests [\#2080](https://github.com/mesosphere/marathon/pull/2080) ([kolloch](https://github.com/kolloch))
- Val name type error [\#2077](https://github.com/mesosphere/marathon/pull/2077) ([hangyan](https://github.com/hangyan))
- Fixes \#722 - Use play JSON for JSON serialization [\#2073](https://github.com/mesosphere/marathon/pull/2073) ([kolloch](https://github.com/kolloch))
- Fixes \#2060 - Use V2Group to render group for GroupsResource [\#2061](https://github.com/mesosphere/marathon/pull/2061) ([kolloch](https://github.com/kolloch))
- Update visualiser to 1.6.6 [\#2055](https://github.com/mesosphere/marathon/pull/2055) ([pierlo-upitup](https://github.com/pierlo-upitup))
- servicerouter.py - enhances the error output for bad requests [\#2048](https://github.com/mesosphere/marathon/pull/2048) ([MrMarvin](https://github.com/MrMarvin))
- Update to visualiser 1.6.3 [\#2046](https://github.com/mesosphere/marathon/pull/2046) ([philipnrmn](https://github.com/philipnrmn))
- Check servicerouter is PEP-8 compliant [\#2045](https://github.com/mesosphere/marathon/pull/2045) ([cmaloney](https://github.com/cmaloney))
- Add Indix to companies using Marathon [\#2043](https://github.com/mesosphere/marathon/pull/2043) ([manojlds](https://github.com/manojlds))
- Add Refinery29 to list of Marathon utilizing companies [\#2037](https://github.com/mesosphere/marathon/pull/2037) ([brockoffdev](https://github.com/brockoffdev))
- Fix \#1671 by setting the hostname directly, so mesos will not run into an exception [\#2025](https://github.com/mesosphere/marathon/pull/2025) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1943 - Call reviveOffers when already declined offers [\#2020](https://github.com/mesosphere/marathon/pull/2020) ([kolloch](https://github.com/kolloch))
- servicerouter: integrate health checks from marathon app definition [\#2005](https://github.com/mesosphere/marathon/pull/2005) ([felixb](https://github.com/felixb))
- servicerouter: remove callbacks when servicerouter terminates [\#2004](https://github.com/mesosphere/marathon/pull/2004) ([flosell](https://github.com/flosell))
- servicerouter: add option to disable logging to syslog [\#2001](https://github.com/mesosphere/marathon/pull/2001) ([felixb](https://github.com/felixb))

## [v0.10.1-RC2](https://github.com/mesosphere/marathon/tree/v0.10.1-RC2) (2015-08-19)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.1-RC1...v0.10.1-RC2)

**Implemented enhancements:**

- First step of migration should make sure the zookeeper path exists [\#1819](https://github.com/mesosphere/marathon/issues/1819)
- Make app configuration fields editable [\#808](https://github.com/mesosphere/marathon/issues/808)
- Expose all /v2 App attributes in UI [\#124](https://github.com/mesosphere/marathon/issues/124)

**Fixed bugs:**

- Shortcut for app creation no longer works [\#2030](https://github.com/mesosphere/marathon/issues/2030)
- Killing task not possible [\#2029](https://github.com/mesosphere/marathon/issues/2029)
- Avoid concurrent http requests on same endpoint [\#2014](https://github.com/mesosphere/marathon/issues/2014)
- Duplicable fields in app creation modal can send null values [\#1996](https://github.com/mesosphere/marathon/issues/1996)
- Error in `java': munmap\_chunk\(\): invalid pointer: 0x00007f014415b1d0 [\#1671](https://github.com/mesosphere/marathon/issues/1671)

**Closed issues:**

- Remove common keyboard operations from the shortcuts [\#2032](https://github.com/mesosphere/marathon/issues/2032)
- Show Marathon UI version in about modal [\#1993](https://github.com/mesosphere/marathon/issues/1993)
- Package the visualizer ui with the demo branch [\#1942](https://github.com/mesosphere/marathon/issues/1942)
- Rename and Rebase demo branch on top of 0.9.2-RC1 and make it available as docker image [\#1938](https://github.com/mesosphere/marathon/issues/1938)
- Load webui from webjar [\#1861](https://github.com/mesosphere/marathon/issues/1861)
- TabPanes should be pages [\#1214](https://github.com/mesosphere/marathon/issues/1214)

**Merged pull requests:**

- Fix \#2029 - add Produces JSON annotation to AppTasksResource [\#2040](https://github.com/mesosphere/marathon/pull/2040) ([meichstedt](https://github.com/meichstedt))
- Update to visualiser 1.6.2 [\#2036](https://github.com/mesosphere/marathon/pull/2036) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Update visualiser to 1.6.1 stable [\#2035](https://github.com/mesosphere/marathon/pull/2035) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Update visualiser to 1.6 stable [\#2034](https://github.com/mesosphere/marathon/pull/2034) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Use consolidated info of the LaunchQueue to determine [\#2028](https://github.com/mesosphere/marathon/pull/2028) ([kolloch](https://github.com/kolloch))
- Fix \#1819 First step of migration should make sure the zookeeper path exists [\#2026](https://github.com/mesosphere/marathon/pull/2026) ([aquamatthias](https://github.com/aquamatthias))
- Added S3 URLs [\#2024](https://github.com/mesosphere/marathon/pull/2024) ([kolloch](https://github.com/kolloch))
- Update advertised Marathon version to 0.10.0 [\#2023](https://github.com/mesosphere/marathon/pull/2023) ([kolloch](https://github.com/kolloch))
- Make MarathonTasks.makeTask deterministic [\#2022](https://github.com/mesosphere/marathon/pull/2022) ([kolloch](https://github.com/kolloch))
- Update to latest chaos version with jetty9. [\#2016](https://github.com/mesosphere/marathon/pull/2016) ([aquamatthias](https://github.com/aquamatthias))
- Tidy up Docker document and add DCOS note. [\#2013](https://github.com/mesosphere/marathon/pull/2013) ([ssk2](https://github.com/ssk2))
- make logger work in python 2.6 [\#2003](https://github.com/mesosphere/marathon/pull/2003) ([flosell](https://github.com/flosell))
- Update deployments.md to include common cause for Docker deploy failures [\#1999](https://github.com/mesosphere/marathon/pull/1999) ([jgarcia-mesosphere](https://github.com/jgarcia-mesosphere))
- Fixes \#1861 Serve UI from webjar [\#1973](https://github.com/mesosphere/marathon/pull/1973) ([aquamatthias](https://github.com/aquamatthias))

## [v0.10.1-RC1](https://github.com/mesosphere/marathon/tree/v0.10.1-RC1) (2015-08-14)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.3-RC1...v0.10.1-RC1)

## [v0.9.3-RC1](https://github.com/mesosphere/marathon/tree/v0.9.3-RC1) (2015-08-14)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.2...v0.9.3-RC1)

**Fixed bugs:**

- Reset Delay button not shown when app is Running [\#1844](https://github.com/mesosphere/marathon/issues/1844)

**Merged pull requests:**

- Fix \#1984 In multi Marathon setup, the zookeeper path is created concurrently [\#2007](https://github.com/mesosphere/marathon/pull/2007) ([aquamatthias](https://github.com/aquamatthias))

## [v0.9.2](https://github.com/mesosphere/marathon/tree/v0.9.2) (2015-08-14)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.0...v0.9.2)

**Fixed bugs:**

- Marathon doesn't remove tasks which do not exist in Mesos [\#1997](https://github.com/mesosphere/marathon/issues/1997)
- Creation of state path in Zookeeper fails when performed concurrently [\#1984](https://github.com/mesosphere/marathon/issues/1984)

**Closed issues:**

- Marathon should have a finite bound on how long to wait for offers before invoking reviveOffers [\#1935](https://github.com/mesosphere/marathon/issues/1935)

**Merged pull requests:**

- Fixes 1997 - Optimization naming problem [\#2006](https://github.com/mesosphere/marathon/pull/2006) ([aquamatthias](https://github.com/aquamatthias))
- Added SmartProcure to README.md [\#1998](https://github.com/mesosphere/marathon/pull/1998) ([lusid](https://github.com/lusid))
- REST API documentation: Remove duplicate info about updateStrategy [\#1992](https://github.com/mesosphere/marathon/pull/1992) ([kolloch](https://github.com/kolloch))

## [v0.10.0](https://github.com/mesosphere/marathon/tree/v0.10.0) (2015-08-13)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.0-RC5...v0.10.0)

**Implemented enhancements:**

- Expose task failures in the UI [\#1179](https://github.com/mesosphere/marathon/issues/1179)
- Add sorting to the health column in the app list [\#1058](https://github.com/mesosphere/marathon/issues/1058)

**Fixed bugs:**

- HealthBar isn't working correctly on non existing health data [\#1989](https://github.com/mesosphere/marathon/issues/1989)
- Task detail error message doesn't show up on non existent task [\#1960](https://github.com/mesosphere/marathon/issues/1960)
- Can not get marathon logo [\#1954](https://github.com/mesosphere/marathon/issues/1954)
- Kill & Scale, followed by scale-up does not work. [\#1868](https://github.com/mesosphere/marathon/issues/1868)

**Closed issues:**

- POST /v2/apps unstable [\#1979](https://github.com/mesosphere/marathon/issues/1979)
- Should marathon do scaling automatically when an app deployed with constraints "HOST UNIQUE"? [\#1974](https://github.com/mesosphere/marathon/issues/1974)
- Scale out gets stuck [\#1971](https://github.com/mesosphere/marathon/issues/1971)
- Make the revive offer patch available on master branch [\#1943](https://github.com/mesosphere/marathon/issues/1943)
- Release 0.9.2-RC1 and 0.10.0-RC-5 with disk and revive offer patch [\#1941](https://github.com/mesosphere/marathon/issues/1941)
- Can we convert version string to local time? [\#1937](https://github.com/mesosphere/marathon/issues/1937)
- Marathon becomes unresponsive under load [\#1910](https://github.com/mesosphere/marathon/issues/1910)
- Remove prefixes from less [\#1830](https://github.com/mesosphere/marathon/issues/1830)
- Docker params not working [\#1791](https://github.com/mesosphere/marathon/issues/1791)
- Package the UI as webjar  [\#1673](https://github.com/mesosphere/marathon/issues/1673)

**Merged pull requests:**

- Reset rate limiting delays without fetching the app from persistent storage [\#1983](https://github.com/mesosphere/marathon/pull/1983) ([aquamatthias](https://github.com/aquamatthias))
- Setting UI to 0.11.0-SNAPSHOT [\#1982](https://github.com/mesosphere/marathon/pull/1982) ([aldipower](https://github.com/aldipower))
- Added GSShop under Companies using Marathon [\#1981](https://github.com/mesosphere/marathon/pull/1981) ([vivekjuneja](https://github.com/vivekjuneja))
- Docs for \#1889 - Added Common Problems section [\#1980](https://github.com/mesosphere/marathon/pull/1980) ([sepiroth887](https://github.com/sepiroth887))
- Pointing 0.9.1 ui submodule to image path fix [\#1978](https://github.com/mesosphere/marathon/pull/1978) ([aldipower](https://github.com/aldipower))
- CSVExporter can export a directory of metric json data to CSV file. [\#1972](https://github.com/mesosphere/marathon/pull/1972) ([aquamatthias](https://github.com/aquamatthias))
- add additional s3 uris [\#1963](https://github.com/mesosphere/marathon/pull/1963) ([bblanton](https://github.com/bblanton))
- Fixes \#1958 - Fix JSON schema for command health check [\#1961](https://github.com/mesosphere/marathon/pull/1961) ([kolloch](https://github.com/kolloch))

## [v0.10.0-RC5](https://github.com/mesosphere/marathon/tree/v0.10.0-RC5) (2015-08-07)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.2-RC2...v0.10.0-RC5)

**Closed issues:**

- Make the revive offer patch available on 0.10 branch [\#1940](https://github.com/mesosphere/marathon/issues/1940)

## [v0.9.2-RC2](https://github.com/mesosphere/marathon/tree/v0.9.2-RC2) (2015-08-07)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.2-RC1...v0.9.2-RC2)

**Implemented enhancements:**

- Rename --reject\_offer\_duration to --decline\_offer\_duration. [\#1966](https://github.com/mesosphere/marathon/pull/1966) ([gkleiman](https://github.com/gkleiman))

**Fixed bugs:**

- "command" for healthCheck incorrect in AppDefinition.json \(schema\) [\#1958](https://github.com/mesosphere/marathon/issues/1958)
- Timezone offset in UI [\#1038](https://github.com/mesosphere/marathon/issues/1038)
- Flush after write in transfer [\#1930](https://github.com/mesosphere/marathon/pull/1930) ([drewrobb](https://github.com/drewrobb))

**Closed issues:**

- Adapt UI code following renaming mesos\_master\_url to mesos\_leader\_ui\_url [\#1962](https://github.com/mesosphere/marathon/issues/1962)
- Rename --mesos\_master\_url to --mesos\_leader\_ui\_url or similar [\#1957](https://github.com/mesosphere/marathon/issues/1957)
- "Run on all slaves" constraint [\#1956](https://github.com/mesosphere/marathon/issues/1956)
- Make the disk patch available on 0.9 and 0.10 branch  [\#1939](https://github.com/mesosphere/marathon/issues/1939)
- Resources from URIs with Docker containers [\#1869](https://github.com/mesosphere/marathon/issues/1869)

**Merged pull requests:**

- Add notes for 0.10-RC5 [\#1967](https://github.com/mesosphere/marathon/pull/1967) ([aquamatthias](https://github.com/aquamatthias))
- Add link to sidebar and change repository for correct registry. [\#1964](https://github.com/mesosphere/marathon/pull/1964) ([ssk2](https://github.com/ssk2))
- Fixes \#1957 - Rename --mesos\_master\_url to --mesos\_leader\_ui\_url [\#1959](https://github.com/mesosphere/marathon/pull/1959) ([janisz](https://github.com/janisz))
- Fixes \#968 - Put SlaveID in TaskFailure [\#1948](https://github.com/mesosphere/marathon/pull/1948) ([janisz](https://github.com/janisz))

## [v0.9.2-RC1](https://github.com/mesosphere/marathon/tree/v0.9.2-RC1) (2015-08-06)
[Full Changelog](https://github.com/mesosphere/marathon/compare/build-pr-1933...v0.9.2-RC1)

**Implemented enhancements:**

- Fixes for \#1924 \(offers without disk\) + \#1927 \(better logging\) for v0.10.0-RC4 [\#1946](https://github.com/mesosphere/marathon/pull/1946) ([gkleiman](https://github.com/gkleiman))
- Fixes for \#1924 \(offers without disk\) + \#1927 \(better logging\) for v0.9.1 [\#1945](https://github.com/mesosphere/marathon/pull/1945) ([gkleiman](https://github.com/gkleiman))

**Fixed bugs:**

- Fixes \#1931 - Flag for reviveOffers and offer reject duration [\#1949](https://github.com/mesosphere/marathon/pull/1949) ([kolloch](https://github.com/kolloch))
- Fixes for \\#1924 \\(offers without disk\\) + \\#1927 \\(better logging\\) for v0.10.0-RC4 [\#1946](https://github.com/mesosphere/marathon/pull/1946) ([gkleiman](https://github.com/gkleiman))
- Fixes for \\#1924 \\(offers without disk\\) + \\#1927 \\(better logging\\) for v0.9.1 [\#1945](https://github.com/mesosphere/marathon/pull/1945) ([gkleiman](https://github.com/gkleiman))
- Improve 0.9.1 [\#1932](https://github.com/mesosphere/marathon/pull/1932) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- SSE leader proxy buffer/latency problem [\#1926](https://github.com/mesosphere/marathon/issues/1926)

**Merged pull requests:**

- Fixes \#1745 - Use SlaveID for reconciliation [\#1934](https://github.com/mesosphere/marathon/pull/1934) ([janisz](https://github.com/janisz))
- Introduces RWLock utility class. [\#1921](https://github.com/mesosphere/marathon/pull/1921) ([ConnorDoyle](https://github.com/ConnorDoyle))

## [build-pr-1933](https://github.com/mesosphere/marathon/tree/build-pr-1933) (2015-08-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.1.1...build-pr-1933)

**Implemented enhancements:**

- NPM warns about lack of license field [\#1928](https://github.com/mesosphere/marathon/issues/1928)
- Marathon should log why an offer didn't match [\#1927](https://github.com/mesosphere/marathon/issues/1927)

**Fixed bugs:**

- App stuck in deployment because of missing \(unneeded\) disk resource in the offer [\#1924](https://github.com/mesosphere/marathon/issues/1924)
- Creating a containerised instance with a bridged network is not possible [\#1922](https://github.com/mesosphere/marathon/issues/1922)

**Closed issues:**

- Save Task SlaveID and use it for reconciliation [\#1745](https://github.com/mesosphere/marathon/issues/1745)
- Expose a way to identify "fragile" marathon apps in the web UI \(failure history\) [\#968](https://github.com/mesosphere/marathon/issues/968)

**Merged pull requests:**

- \#878 - Add slaveId in MarathonTask and API to retrieve Mesos Master URL [\#1882](https://github.com/mesosphere/marathon/pull/1882) ([janisz](https://github.com/janisz))

## [v0.8.1.1](https://github.com/mesosphere/marathon/tree/v0.8.1.1) (2015-08-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.1...v0.8.1.1)

**Fixed bugs:**

- Marathon UI Ignores API Errors [\#116](https://github.com/mesosphere/marathon/issues/116)

**Closed issues:**

- Declining Offers Infinute Loop [\#1917](https://github.com/mesosphere/marathon/issues/1917)
- Creating an App Using a Non-Leader Instance [\#1916](https://github.com/mesosphere/marathon/issues/1916)
- Marathon coredump on leader election \(Running inside docker on coreOS\) [\#1889](https://github.com/mesosphere/marathon/issues/1889)
- Get rid of all `classSet` usages [\#1845](https://github.com/mesosphere/marathon/issues/1845)
- Integrate with mesos 0.23.0 [\#1788](https://github.com/mesosphere/marathon/issues/1788)
- Migrate Marathon to java 8 [\#1786](https://github.com/mesosphere/marathon/issues/1786)
- Run Integration Tests with Java 8 as well [\#1773](https://github.com/mesosphere/marathon/issues/1773)
- Understand Marathon Doc for docker port binding in Bridge mode [\#1009](https://github.com/mesosphere/marathon/issues/1009)
- Jump to Mesos sandbox from UI [\#878](https://github.com/mesosphere/marathon/issues/878)

**Merged pull requests:**

- Handle missing disk resource in offers. [\#1925](https://github.com/mesosphere/marathon/pull/1925) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update rest-api.md [\#1911](https://github.com/mesosphere/marathon/pull/1911) ([cameronpickham](https://github.com/cameronpickham))

## [v0.9.1](https://github.com/mesosphere/marathon/tree/v0.9.1) (2015-07-31)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.0-RC4...v0.9.1)

**Implemented enhancements:**

- \[Feature Request\] HTTPS healthchecks [\#1894](https://github.com/mesosphere/marathon/issues/1894)
- servicerouter: name-based application routing [\#1880](https://github.com/mesosphere/marathon/issues/1880)
- Kill & Scale should be available for more than one task [\#1872](https://github.com/mesosphere/marathon/issues/1872)

**Fixed bugs:**

- Kill & Scale should be available for more than one task [\#1872](https://github.com/mesosphere/marathon/issues/1872)

**Closed issues:**

- Refactor react-router routes to camelCase [\#1874](https://github.com/mesosphere/marathon/issues/1874)
- /v2/groups PUT doesn't honor previous instances value [\#659](https://github.com/mesosphere/marathon/issues/659)

**Merged pull requests:**

- fix tomcat url in example [\#1907](https://github.com/mesosphere/marathon/pull/1907) ([anshulverma](https://github.com/anshulverma))
- Update constraints.md [\#1905](https://github.com/mesosphere/marathon/pull/1905) ([rncry](https://github.com/rncry))
- Improve our documentation about contributing documentation [\#1896](https://github.com/mesosphere/marathon/pull/1896) ([kolloch](https://github.com/kolloch))
- Documentation for Docker Registry 2.0, discussed in \#926 [\#1893](https://github.com/mesosphere/marathon/pull/1893) ([IanSaunders](https://github.com/IanSaunders))
- Fixes \#1741 - Replace TaskQueue/OfferMatcher with actor-based implementation [\#1840](https://github.com/mesosphere/marathon/pull/1840) ([kolloch](https://github.com/kolloch))
- Build for jdk 8 target. [\#1834](https://github.com/mesosphere/marathon/pull/1834) ([aquamatthias](https://github.com/aquamatthias))

## [v0.10.0-RC4](https://github.com/mesosphere/marathon/tree/v0.10.0-RC4) (2015-07-29)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.0-RC3...v0.10.0-RC4)

**Implemented enhancements:**

- Add a link to the app detail page from the deployments tab [\#1864](https://github.com/mesosphere/marathon/issues/1864)
- Show application groups in the ui [\#1262](https://github.com/mesosphere/marathon/issues/1262)

**Fixed bugs:**

- App can't be deleted because it "does not exist", although /apps still returns it [\#1853](https://github.com/mesosphere/marathon/issues/1853)
- Don't show "no apps/deployments" message during page load [\#1846](https://github.com/mesosphere/marathon/issues/1846)
- Additional properties are not allowed \('key', 'value' were unexpected\) [\#1836](https://github.com/mesosphere/marathon/issues/1836)
- Marathon should fail during start, if the HTTP port is already bound [\#1818](https://github.com/mesosphere/marathon/issues/1818)
- Keep the rest-api return format consistent when request headers without "Accept: application/json" [\#1647](https://github.com/mesosphere/marathon/issues/1647)
- docker: hostPath in volumes seems to be ignored [\#1600](https://github.com/mesosphere/marathon/issues/1600)
- Better error reporting in the UI [\#1193](https://github.com/mesosphere/marathon/issues/1193)
- UI showing empty list after scaling when on page \> 1 [\#548](https://github.com/mesosphere/marathon/issues/548)
- Fix \#1853: App can't be deleted because it "does not exist", although /apps still returns it [\#1888](https://github.com/mesosphere/marathon/pull/1888) ([aquamatthias](https://github.com/aquamatthias))

**Closed issues:**

- Marathon deploy the wrong docker version to slave [\#1884](https://github.com/mesosphere/marathon/issues/1884)
- Include Marathon 0.9.0 in Ubuntu Vivid repository [\#1883](https://github.com/mesosphere/marathon/issues/1883)
- Hash Sum mismatch when adding apt repo [\#1879](https://github.com/mesosphere/marathon/issues/1879)
- Running a container on all hosts [\#1876](https://github.com/mesosphere/marathon/issues/1876)
- Allow access to Mesos sandbox logs from Marathon UI [\#1871](https://github.com/mesosphere/marathon/issues/1871)
- Provide events long-polling endpoint [\#1870](https://github.com/mesosphere/marathon/issues/1870)
- Links in REST API docs don't work [\#1859](https://github.com/mesosphere/marathon/issues/1859)
- Update Docs: list all possible API error responses [\#1849](https://github.com/mesosphere/marathon/issues/1849)
- Improve structure of 'Upgrading' section [\#1832](https://github.com/mesosphere/marathon/issues/1832)
- Document the preferred way to upgrade a running Marathon installation to a new version [\#1817](https://github.com/mesosphere/marathon/issues/1817)
- Add tooltips to CHANGELOG [\#1816](https://github.com/mesosphere/marathon/issues/1816)
- Add container image name to environment [\#1766](https://github.com/mesosphere/marathon/issues/1766)
- Document current development process [\#1712](https://github.com/mesosphere/marathon/issues/1712)
- Make tasks exponentially back off, even if they end up as "TASK\_FINISHED", but just finish really rapidly [\#1470](https://github.com/mesosphere/marathon/issues/1470)
- Killing multiple tasks in the UI doesn't work [\#1207](https://github.com/mesosphere/marathon/issues/1207)

**Merged pull requests:**

- Fix developing VM docs [\#1897](https://github.com/mesosphere/marathon/pull/1897) ([janisz](https://github.com/janisz))
- Added Football Radar to companies list [\#1892](https://github.com/mesosphere/marathon/pull/1892) ([LeePorte](https://github.com/LeePorte))
- added sloppy.io to companies using marathon [\#1891](https://github.com/mesosphere/marathon/pull/1891) ([MikeMichel](https://github.com/MikeMichel))
- Fixes \#1647 - prefer responding with JSON [\#1887](https://github.com/mesosphere/marathon/pull/1887) ([kolloch](https://github.com/kolloch))
- Fixes \#1766 - Add container image name to environment [\#1886](https://github.com/mesosphere/marathon/pull/1886) ([kolloch](https://github.com/kolloch))
- Fixes \#1818 - Make Marathon fail on startup errors [\#1877](https://github.com/mesosphere/marathon/pull/1877) ([gkleiman](https://github.com/gkleiman))
- Improves \#1563 - Consolidate documentation for AppsResource\_create [\#1865](https://github.com/mesosphere/marathon/pull/1865) ([kolloch](https://github.com/kolloch))
- Fix internal links in REST api docs [\#1860](https://github.com/mesosphere/marathon/pull/1860) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Improves \#1563 - Move help resources into doc directory [\#1857](https://github.com/mesosphere/marathon/pull/1857) ([kolloch](https://github.com/kolloch))
- Make integration tests a bit less flaky [\#1851](https://github.com/mesosphere/marathon/pull/1851) ([kolloch](https://github.com/kolloch))
- Use sudo: false in travis.yml [\#1850](https://github.com/mesosphere/marathon/pull/1850) ([kolloch](https://github.com/kolloch))
- Fixes \#1832 - Separate upgrade guide [\#1843](https://github.com/mesosphere/marathon/pull/1843) ([kolloch](https://github.com/kolloch))
- Remove extra slash in @Path for artifacts [\#1841](https://github.com/mesosphere/marathon/pull/1841) ([bobrik](https://github.com/bobrik))
- run-tests.sh: Fixes showing value of $NO\_DOCKER\_CACHE [\#1839](https://github.com/mesosphere/marathon/pull/1839) ([kolloch](https://github.com/kolloch))
- Set 0.9.0 version in docs. [\#1838](https://github.com/mesosphere/marathon/pull/1838) ([aquamatthias](https://github.com/aquamatthias))
- dockerignore: Ignore more [\#1837](https://github.com/mesosphere/marathon/pull/1837) ([kolloch](https://github.com/kolloch))
- change permissions and add logging [\#1824](https://github.com/mesosphere/marathon/pull/1824) ([lloesche](https://github.com/lloesche))
- Improves \#1655 - Fix flaky integration tests [\#1810](https://github.com/mesosphere/marathon/pull/1810) ([gkleiman](https://github.com/gkleiman))

## [v0.10.0-RC3](https://github.com/mesosphere/marathon/tree/v0.10.0-RC3) (2015-07-20)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.0-RC2...v0.10.0-RC3)

**Fixed bugs:**

- Marathon forgets value for `acceptedResourceRoles` when app is updated \(including scaling\) [\#1829](https://github.com/mesosphere/marathon/issues/1829)
- Apps with multiple service ports fail to update [\#1827](https://github.com/mesosphere/marathon/issues/1827)
- Fixes \#1829 - Only override acceptedResourceRoles when set in update [\#1833](https://github.com/mesosphere/marathon/pull/1833) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Final polishing on \#90 [\#1798](https://github.com/mesosphere/marathon/issues/1798)

**Merged pull requests:**

- Fixes \#1827: Apps with multiple service ports fail to update [\#1831](https://github.com/mesosphere/marathon/pull/1831) ([aquamatthias](https://github.com/aquamatthias))
- servicerouter: make haproxy port overrideable [\#1826](https://github.com/mesosphere/marathon/pull/1826) ([lloesche](https://github.com/lloesche))

## [v0.10.0-RC2](https://github.com/mesosphere/marathon/tree/v0.10.0-RC2) (2015-07-16)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.10.0-RC1...v0.10.0-RC2)

**Fixed bugs:**

- The SetRequestDefaultsFilter does not handle missing headers correctly [\#1820](https://github.com/mesosphere/marathon/issues/1820)

**Merged pull requests:**

- Fixes \#1820: the default for missing headers is an empty enumeration instead of null [\#1821](https://github.com/mesosphere/marathon/pull/1821) ([aquamatthias](https://github.com/aquamatthias))
- force mode to http if hostname is set for app [\#1809](https://github.com/mesosphere/marathon/pull/1809) ([lloesche](https://github.com/lloesche))

## [v0.10.0-RC1](https://github.com/mesosphere/marathon/tree/v0.10.0-RC1) (2015-07-15)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.0...v0.10.0-RC1)

**Implemented enhancements:**

- Please add a search bar to the applications overview to filter the list of applications [\#1204](https://github.com/mesosphere/marathon/issues/1204)
- Fixes \#1254 - Add flag to define Marathon PORT prefix. [\#1807](https://github.com/mesosphere/marathon/pull/1807) ([gkleiman](https://github.com/gkleiman))

**Fixed bugs:**

- marathon-haproxy-bridge breaks when an app without ports is scaled to 0 instances [\#1799](https://github.com/mesosphere/marathon/issues/1799)
- Concurrent changes to the same AppDefinition will lead to inconsistent state [\#1709](https://github.com/mesosphere/marathon/issues/1709)
- Kill tasks with scaling does not update group [\#1397](https://github.com/mesosphere/marathon/issues/1397)
- Invalidate framework ID if registration triggers an error [\#1316](https://github.com/mesosphere/marathon/issues/1316)
- click outside the 'New App' panel -\> lose your data [\#948](https://github.com/mesosphere/marathon/issues/948)

**Closed issues:**

- Secure event\_subscriber callbacks [\#1772](https://github.com/mesosphere/marathon/issues/1772)
- UI: Allow administratively zeroing / resetting the taskLaunchDelay [\#1754](https://github.com/mesosphere/marathon/issues/1754)
- Enable untracked config file [\#1727](https://github.com/mesosphere/marathon/issues/1727)
- Add at least one integration test for each documented API endpoint. [\#1644](https://github.com/mesosphere/marathon/issues/1644)
- Default Marathon UI colour scheme is not usable for colour-blind individuals [\#1499](https://github.com/mesosphere/marathon/issues/1499)
- Add flag to define Marathon PORT prefix [\#1254](https://github.com/mesosphere/marathon/issues/1254)
- Passing routes by the properties to Marathon [\#1213](https://github.com/mesosphere/marathon/issues/1213)
- Add tooltip on hover to progress bars [\#1137](https://github.com/mesosphere/marathon/issues/1137)
- sbt assembly should also compile front end assets  [\#999](https://github.com/mesosphere/marathon/issues/999)

**Merged pull requests:**

- added Orbitz to companies using Marathon [\#1808](https://github.com/mesosphere/marathon/pull/1808) ([rickfast](https://github.com/rickfast))
- Changelog for 0.10 [\#1805](https://github.com/mesosphere/marathon/pull/1805) ([aquamatthias](https://github.com/aquamatthias))
- Increase timeout for futures in PersistentStoreTests [\#1804](https://github.com/mesosphere/marathon/pull/1804) ([aquamatthias](https://github.com/aquamatthias))
- add corvisa to the list of companies that use marathon in production [\#1803](https://github.com/mesosphere/marathon/pull/1803) ([ranxxerox](https://github.com/ranxxerox))
- Add the content length to WSGI input reading [\#1802](https://github.com/mesosphere/marathon/pull/1802) ([woegjiub](https://github.com/woegjiub))
- fix servicerouter.py logging [\#1797](https://github.com/mesosphere/marathon/pull/1797) ([lloesche](https://github.com/lloesche))
- Enable metrics per default and add the possibility to disable the metrics [\#1795](https://github.com/mesosphere/marathon/pull/1795) ([aquamatthias](https://github.com/aquamatthias))
- Disable the default for the concurrent requests limit [\#1794](https://github.com/mesosphere/marathon/pull/1794) ([aquamatthias](https://github.com/aquamatthias))
- Port guessing for servicerouter.py [\#1792](https://github.com/mesosphere/marathon/pull/1792) ([woegjiub](https://github.com/woegjiub))
- Improves \#1644 - Add integration tests for /v2/info. [\#1790](https://github.com/mesosphere/marathon/pull/1790) ([gkleiman](https://github.com/gkleiman))
- Pointing submodule to v0.10.0 of the UI [\#1783](https://github.com/mesosphere/marathon/pull/1783) ([aldipower](https://github.com/aldipower))
- Define the release process according to the RC/GA process. [\#1782](https://github.com/mesosphere/marathon/pull/1782) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#1644 - Adds integration test for /v2/queue. [\#1777](https://github.com/mesosphere/marathon/pull/1777) ([gkleiman](https://github.com/gkleiman))
- Improves \#1644 - Add deployment rollback integration test. [\#1776](https://github.com/mesosphere/marathon/pull/1776) ([gkleiman](https://github.com/gkleiman))
- Change description of "Companies using Marathon" [\#1774](https://github.com/mesosphere/marathon/pull/1774) ([janisz](https://github.com/janisz))
- Make integration tests a bit more robust. [\#1758](https://github.com/mesosphere/marathon/pull/1758) ([gkleiman](https://github.com/gkleiman))
- Use a synchronized GroupManager.upgrade for all changes [\#1743](https://github.com/mesosphere/marathon/pull/1743) ([aquamatthias](https://github.com/aquamatthias))
- Remove the frameworkId, if the scheduler reports an error. [\#1690](https://github.com/mesosphere/marathon/pull/1690) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1397 update AppDefinition in group when killing tasks w/ scale [\#1650](https://github.com/mesosphere/marathon/pull/1650) ([meichstedt](https://github.com/meichstedt))

## [v0.9.0](https://github.com/mesosphere/marathon/tree/v0.9.0) (2015-07-09)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.0-RC3...v0.9.0)

**Implemented enhancements:**

- Add metrics around all Mesos interface callbacks. [\#1723](https://github.com/mesosphere/marathon/issues/1723)
- Allow administratively zeroing / resetting the taskLaunchDelay  [\#1681](https://github.com/mesosphere/marathon/issues/1681)
- Marathon About page presents a confusing 'Name' which is not the framework name [\#1469](https://github.com/mesosphere/marathon/issues/1469)
- Add code coverage utility [\#817](https://github.com/mesosphere/marathon/issues/817)
- Lack of information when a deployment stalls [\#652](https://github.com/mesosphere/marathon/issues/652)
- Constraints not satisfied when scaling down [\#555](https://github.com/mesosphere/marathon/issues/555)

**Fixed bugs:**

- Too many simultaneous requests will kill Marathon [\#1710](https://github.com/mesosphere/marathon/issues/1710)
- The GUI doesn't allow creating apps with 0 instances, but it is possible through the v2 API [\#1660](https://github.com/mesosphere/marathon/issues/1660)
- Refresh button in app configuration page doesn't work [\#1236](https://github.com/mesosphere/marathon/issues/1236)

**Closed issues:**

- Make use of the tabs array in the deployments test [\#1771](https://github.com/mesosphere/marathon/issues/1771)
- Get a generic object merge function [\#1770](https://github.com/mesosphere/marathon/issues/1770)
- Merge CHANGELOG files upon release? [\#1746](https://github.com/mesosphere/marathon/issues/1746)
- Health Check issue.  [\#1744](https://github.com/mesosphere/marathon/issues/1744)
- Problem passing arguments to docker container [\#1740](https://github.com/mesosphere/marathon/issues/1740)
- Marathon cannot deploy docker container when portMapping is specified. [\#1739](https://github.com/mesosphere/marathon/issues/1739)
- Deployments badge should be set in NavTabsComponent [\#1738](https://github.com/mesosphere/marathon/issues/1738)
- Refactor FormGroupComponent: don't modify props directly [\#1735](https://github.com/mesosphere/marathon/issues/1735)
- Refactor getTaskHealthMessage of DOOM [\#1734](https://github.com/mesosphere/marathon/issues/1734)
- cannot create a working cluster [\#1731](https://github.com/mesosphere/marathon/issues/1731)
- Expose constraint/resource problems in a form other than logs [\#1728](https://github.com/mesosphere/marathon/issues/1728)
- Refactor: ditch Backbone completely, implement React router [\#1726](https://github.com/mesosphere/marathon/issues/1726)
- Does callback support username and password [\#1724](https://github.com/mesosphere/marathon/issues/1724)
- Define workflow for maintaining \(or not\) /dist folder [\#1721](https://github.com/mesosphere/marathon/issues/1721)
- When proxied, the UI does not go to the correct endpoint [\#1715](https://github.com/mesosphere/marathon/issues/1715)
- Introduce library agnostic ajax API [\#1705](https://github.com/mesosphere/marathon/issues/1705)
- About modal should use Flux Info store/actions [\#1704](https://github.com/mesosphere/marathon/issues/1704)
- App compontens should recieve data from flux store [\#1692](https://github.com/mesosphere/marathon/issues/1692)
- Create Git Tags for releases [\#1674](https://github.com/mesosphere/marathon/issues/1674)
- Marathon not respecting GROUP\_BY contraints [\#1633](https://github.com/mesosphere/marathon/issues/1633)
- Ged rid of jQuery [\#1223](https://github.com/mesosphere/marathon/issues/1223)
- deployment\_success/failed should contain deployment info [\#650](https://github.com/mesosphere/marathon/issues/650)

**Merged pull requests:**

- Improve documentation for offer matching tuning CLI flags [\#1767](https://github.com/mesosphere/marathon/pull/1767) ([kolloch](https://github.com/kolloch))
- add `version` info to `Event Stream` overview item [\#1765](https://github.com/mesosphere/marathon/pull/1765) ([Kosta-Github](https://github.com/Kosta-Github))
- Update docs: provide guidance for named args [\#1757](https://github.com/mesosphere/marathon/pull/1757) ([pierlo-upitup](https://github.com/pierlo-upitup))
- Speedup PortsMatcher [\#1755](https://github.com/mesosphere/marathon/pull/1755) ([kolloch](https://github.com/kolloch))
- Fix \#1681: Allow administratively getting and resetting the taskLaunchDelay [\#1753](https://github.com/mesosphere/marathon/pull/1753) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#1644 - Adds integration tests for /v2/leader endpoints. [\#1752](https://github.com/mesosphere/marathon/pull/1752) ([gkleiman](https://github.com/gkleiman))
- Fix flaky integration tests. [\#1751](https://github.com/mesosphere/marathon/pull/1751) ([gkleiman](https://github.com/gkleiman))
- Constraints: add selectTasksToKill based on constraints. [\#1749](https://github.com/mesosphere/marathon/pull/1749) ([aquamatthias](https://github.com/aquamatthias))
- Update constraints.md [\#1748](https://github.com/mesosphere/marathon/pull/1748) ([aameek](https://github.com/aameek))
- Improves \#1644 - Add an integration test for DELETE /v2/deployments/\[id\] [\#1747](https://github.com/mesosphere/marathon/pull/1747) ([gkleiman](https://github.com/gkleiman))
- Improves \#1644 - Add some integration tests for /v2/eventSubscriptions endpoints. [\#1742](https://github.com/mesosphere/marathon/pull/1742) ([gkleiman](https://github.com/gkleiman))
- Add Coverage Status to the Headline. [\#1733](https://github.com/mesosphere/marathon/pull/1733) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#1644 - Add some integration tests for /v2/artifacts endpoints. [\#1732](https://github.com/mesosphere/marathon/pull/1732) ([gkleiman](https://github.com/gkleiman))
- Limit the number of concurrent http requests. [\#1714](https://github.com/mesosphere/marathon/pull/1714) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#650. Add deployment plan to DeploymentSuccess/DeploymentFailed. [\#1699](https://github.com/mesosphere/marathon/pull/1699) ([aquamatthias](https://github.com/aquamatthias))
- Decouple API representations from internal models [\#1536](https://github.com/mesosphere/marathon/pull/1536) ([ConnorDoyle](https://github.com/ConnorDoyle))
- PEP-8 fixes for ServiceRouter [\#1534](https://github.com/mesosphere/marathon/pull/1534) ([cmaloney](https://github.com/cmaloney))
- Add coverage reporting [\#1108](https://github.com/mesosphere/marathon/pull/1108) ([c089](https://github.com/c089))

## [v0.9.0-RC3](https://github.com/mesosphere/marathon/tree/v0.9.0-RC3) (2015-06-27)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.0-RC2...v0.9.0-RC3)

**Implemented enhancements:**

- Add headers to Marathon responses indicating current leader and proxying [\#1716](https://github.com/mesosphere/marathon/issues/1716)
- Marathon 0.8.1 - API - /v2/tasks [\#1654](https://github.com/mesosphere/marathon/issues/1654)

**Fixed bugs:**

- Inconsistent content-type and response from REST API [\#1669](https://github.com/mesosphere/marathon/issues/1669)
- Proxying doesn't work for HTTPS [\#1556](https://github.com/mesosphere/marathon/issues/1556)
- MARATHON\_ env variables cause Marathon to fail to launch [\#1143](https://github.com/mesosphere/marathon/issues/1143)
- Fixes \#1556 - advertise HTTPS port for leader if HTTP is disabled [\#1713](https://github.com/mesosphere/marathon/pull/1713) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Mesos not working with private Docker registry [\#1708](https://github.com/mesosphere/marathon/issues/1708)
- Marathon crash when syncing tasks [\#1702](https://github.com/mesosphere/marathon/issues/1702)
- Eslint: enforce eqeqeq rule [\#1701](https://github.com/mesosphere/marathon/issues/1701)
- Tag v0.9.0-RC2 contains v0.9.0-RC1 in version.sbt file. [\#1700](https://github.com/mesosphere/marathon/issues/1700)
- Marathon fails to kill task, looping infinitely [\#1695](https://github.com/mesosphere/marathon/issues/1695)
- Move from Broccoli to Gulp [\#1693](https://github.com/mesosphere/marathon/issues/1693)
- Create an oboe.js-wrapper [\#1691](https://github.com/mesosphere/marathon/issues/1691)
- Implement Flux-compliant structure for "apps/\[appid\]/versions" endpoint [\#1679](https://github.com/mesosphere/marathon/issues/1679)
- Implement Flux-compliant structure for Info endpoint [\#1678](https://github.com/mesosphere/marathon/issues/1678)
- Implement Flux-compliant structure for "apps/tasks" endpoint [\#1675](https://github.com/mesosphere/marathon/issues/1675)
- More responsive/faster Marathon scale up and scale down [\#1641](https://github.com/mesosphere/marathon/issues/1641)

**Merged pull requests:**

- Fixes \#1716 - Add Proxy headers [\#1718](https://github.com/mesosphere/marathon/pull/1718) ([kolloch](https://github.com/kolloch))
- Fix \#1143 Filter MARATHON\_APP\* env variables. [\#1717](https://github.com/mesosphere/marathon/pull/1717) ([aquamatthias](https://github.com/aquamatthias))
- Fix typo in deployment deletion example [\#1703](https://github.com/mesosphere/marathon/pull/1703) ([arthurbarr](https://github.com/arthurbarr))
- Remove the frontend travis build setup [\#1698](https://github.com/mesosphere/marathon/pull/1698) ([aquamatthias](https://github.com/aquamatthias))
- Remove the publishing process to s3. [\#1697](https://github.com/mesosphere/marathon/pull/1697) ([aquamatthias](https://github.com/aquamatthias))
- Improves \#1644 - Add some integration tests for /v2/apps endpoints. [\#1696](https://github.com/mesosphere/marathon/pull/1696) ([gkleiman](https://github.com/gkleiman))
- Define TeamCity env parameters [\#1665](https://github.com/mesosphere/marathon/pull/1665) ([aquamatthias](https://github.com/aquamatthias))

## [v0.9.0-RC2](https://github.com/mesosphere/marathon/tree/v0.9.0-RC2) (2015-06-22)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.9.0-RC1...v0.9.0-RC2)

**Fixed bugs:**

- Leader Election Process fails, if the fetching of the frameworkId hits a timeout [\#1684](https://github.com/mesosphere/marathon/issues/1684)

**Closed issues:**

- Replace TaskQueue/OfferMatcher with an actor based implementation [\#1741](https://github.com/mesosphere/marathon/issues/1741)
- Support relative paths for host docker volumes [\#1694](https://github.com/mesosphere/marathon/issues/1694)
- 403 on Marathon built with marathon-pkg [\#1687](https://github.com/mesosphere/marathon/issues/1687)
- The size of state in Zookeeper is too large and continuously growing up [\#1683](https://github.com/mesosphere/marathon/issues/1683)
- Implement Flux-compliant structure for Apps endpoint [\#1677](https://github.com/mesosphere/marathon/issues/1677)
- Unable to access index [\#1670](https://github.com/mesosphere/marathon/issues/1670)
- Database, memory & swap space [\#1662](https://github.com/mesosphere/marathon/issues/1662)
- Q: Constraints not working [\#1661](https://github.com/mesosphere/marathon/issues/1661)
- Including docker container information and a blank CMD field in an app JSON breaks PUT updates but not POST app creations [\#1630](https://github.com/mesosphere/marathon/issues/1630)
- Empty response for GET /v2/apps? [\#1585](https://github.com/mesosphere/marathon/issues/1585)
- Report number of apps/groups in metrics [\#1573](https://github.com/mesosphere/marathon/issues/1573)
- --zk\_max\_versions doesn't apply to group versions? [\#1533](https://github.com/mesosphere/marathon/issues/1533)
- marathon 0.8.1 event\_subscriber not working [\#1302](https://github.com/mesosphere/marathon/issues/1302)
- Can Marathon expose internal ip of the container? [\#1075](https://github.com/mesosphere/marathon/issues/1075)
- Host networked apps showing port being mapped when app is part of a group [\#1074](https://github.com/mesosphere/marathon/issues/1074)
- Marathon sometimes fixates on launching a specific app to the exclusion of others, ignoring dependencies [\#1024](https://github.com/mesosphere/marathon/issues/1024)

**Merged pull requests:**

- Do not mention MacOS builds [\#1689](https://github.com/mesosphere/marathon/pull/1689) ([artemharutyunyan](https://github.com/artemharutyunyan))
- Fix \#1684 by handling exceptions while becoming a leader [\#1686](https://github.com/mesosphere/marathon/pull/1686) ([aquamatthias](https://github.com/aquamatthias))
- change help text based on Joel's suggestions [\#1676](https://github.com/mesosphere/marathon/pull/1676) ([lloesche](https://github.com/lloesche))
- Fix \#1647 by enriching all requests without appropriate request headers [\#1672](https://github.com/mesosphere/marathon/pull/1672) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1573 - Report number of apps/groups in metrics [\#1667](https://github.com/mesosphere/marathon/pull/1667) ([gkleiman](https://github.com/gkleiman))
- MarathonSchedulerActor: Remove some indirect dependencies [\#1666](https://github.com/mesosphere/marathon/pull/1666) ([kolloch](https://github.com/kolloch))
- Tests: ProcessKeeper reports total number of processes on process [\#1664](https://github.com/mesosphere/marathon/pull/1664) ([kolloch](https://github.com/kolloch))
- Cleanup fixed bugs [\#1663](https://github.com/mesosphere/marathon/pull/1663) ([kolloch](https://github.com/kolloch))
- Fix all scalastyle reported issues [\#1658](https://github.com/mesosphere/marathon/pull/1658) ([aquamatthias](https://github.com/aquamatthias))

## [v0.9.0-RC1](https://github.com/mesosphere/marathon/tree/v0.9.0-RC1) (2015-06-15)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.2...v0.9.0-RC1)

**Fixed bugs:**

- deployment got stuck when marathon updating app [\#1620](https://github.com/mesosphere/marathon/issues/1620)
- args\[\] does not work [\#1564](https://github.com/mesosphere/marathon/issues/1564)
- A marathon instance should never proxy to itself [\#1540](https://github.com/mesosphere/marathon/issues/1540)
- Reject null bodies in REST API [\#1259](https://github.com/mesosphere/marathon/issues/1259)
- Fixes \#1556 - Allow proxying to leader with HTTPS [\#1628](https://github.com/mesosphere/marathon/pull/1628) ([kolloch](https://github.com/kolloch))
- Fixes \#1541, \#1540 - LeaderProxyFilter, do not proxy to self, timeouts [\#1598](https://github.com/mesosphere/marathon/pull/1598) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Create changelog / breaking changes [\#1656](https://github.com/mesosphere/marathon/issues/1656)
- Need upgrade instructions for 0.7.x to 0.8.x? [\#1637](https://github.com/mesosphere/marathon/issues/1637)
- set resources=ports:\[5000-60000\] but use marathon can't deploy  [\#1634](https://github.com/mesosphere/marathon/issues/1634)
- Poor JSON response  [\#1632](https://github.com/mesosphere/marathon/issues/1632)
- when marathon start and  raise java.lang.NullPointerException [\#1626](https://github.com/mesosphere/marathon/issues/1626)
- SSE Stream handle should close the connection, when the leadership is lost [\#1625](https://github.com/mesosphere/marathon/issues/1625)
- Add UI .git directory etc to .dockerignore [\#1624](https://github.com/mesosphere/marathon/issues/1624)
- portMappings is setted  but not working [\#1622](https://github.com/mesosphere/marathon/issues/1622)
- Master/slave database failover question [\#1621](https://github.com/mesosphere/marathon/issues/1621)
- Run docker with portMapping in HOST network mode [\#1618](https://github.com/mesosphere/marathon/issues/1618)
- When will 0.8.2 be available in the mesosphere apt repository? [\#1617](https://github.com/mesosphere/marathon/issues/1617)
- Add documentation about the servicerouter [\#1615](https://github.com/mesosphere/marathon/issues/1615)
- Release 0.8.2 [\#1603](https://github.com/mesosphere/marathon/issues/1603)
- Remove `$$EnhancerByGuice$$...` from class names in metrics [\#1572](https://github.com/mesosphere/marathon/issues/1572)
- docker run and mkdir  [\#1571](https://github.com/mesosphere/marathon/issues/1571)
- JVM-only library for storing state \(in Zookeeper\) [\#1539](https://github.com/mesosphere/marathon/issues/1539)
- rewrite proxy filter [\#828](https://github.com/mesosphere/marathon/issues/828)

**Merged pull requests:**

- Update changelog [\#1659](https://github.com/mesosphere/marathon/pull/1659) ([gkleiman](https://github.com/gkleiman))
- Fixes \#1637 - fix recommended Mesos versions and [\#1651](https://github.com/mesosphere/marathon/pull/1651) ([kolloch](https://github.com/kolloch))
- Add servicerouter information to docs [\#1649](https://github.com/mesosphere/marathon/pull/1649) ([lloesche](https://github.com/lloesche))
- Documentation improvements. [\#1648](https://github.com/mesosphere/marathon/pull/1648) ([gkleiman](https://github.com/gkleiman))
- Fixes \#1625 - Close stream handle when the current instance loses [\#1646](https://github.com/mesosphere/marathon/pull/1646) ([kolloch](https://github.com/kolloch))
- TaskTrackerTest: wait for futures in test [\#1639](https://github.com/mesosphere/marathon/pull/1639) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1624 - add some UI directories \(.git etc\) to .dockerignore [\#1629](https://github.com/mesosphere/marathon/pull/1629) ([kolloch](https://github.com/kolloch))
- CommandInfo protobuf generation fixed for args. [\#1627](https://github.com/mesosphere/marathon/pull/1627) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1572 - Improve metrics name generation [\#1623](https://github.com/mesosphere/marathon/pull/1623) ([gkleiman](https://github.com/gkleiman))
- Update copyright to 2015 [\#1616](https://github.com/mesosphere/marathon/pull/1616) ([kolloch](https://github.com/kolloch))
- Change link to `compiling assets` in docs. [\#1614](https://github.com/mesosphere/marathon/pull/1614) ([quamilek](https://github.com/quamilek))
- Updated the changelog with upcoming 0.9.0 changes [\#1613](https://github.com/mesosphere/marathon/pull/1613) ([kolloch](https://github.com/kolloch))
- Updating changelog.md to the our published release notes for 0.8.2 [\#1612](https://github.com/mesosphere/marathon/pull/1612) ([kolloch](https://github.com/kolloch))
- publish 0.8.2 release in docs [\#1611](https://github.com/mesosphere/marathon/pull/1611) ([kolloch](https://github.com/kolloch))
- Added Marathon UI instructions to README [\#1602](https://github.com/mesosphere/marathon/pull/1602) ([aldipower](https://github.com/aldipower))
- GroupsResource use play json [\#1597](https://github.com/mesosphere/marathon/pull/1597) ([aquamatthias](https://github.com/aquamatthias))
- Move from State abstraction to direct zk access with scala based Futures [\#1582](https://github.com/mesosphere/marathon/pull/1582) ([aquamatthias](https://github.com/aquamatthias))
- allow load balancing mode to be set via env var [\#1444](https://github.com/mesosphere/marathon/pull/1444) ([lloesche](https://github.com/lloesche))

## [v0.8.2](https://github.com/mesosphere/marathon/tree/v0.8.2) (2015-06-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.2-RC4...v0.8.2)

**Implemented enhancements:**

- Integrate SSO and IDM for browser app and RESTful web services [\#883](https://github.com/mesosphere/marathon/issues/883)
- Docs site cleanup [\#854](https://github.com/mesosphere/marathon/issues/854)
- Download is insecure [\#477](https://github.com/mesosphere/marathon/issues/477)

**Fixed bugs:**

- Task uses invalid resources: disk\(\*\):0 [\#1583](https://github.com/mesosphere/marathon/issues/1583)
- Instructions in README for running in a VM lead to 404 [\#1565](https://github.com/mesosphere/marathon/issues/1565)
- Fixes \#1583 - Only pass non-zero disk quota to Mesos [\#1591](https://github.com/mesosphere/marathon/pull/1591) ([kolloch](https://github.com/kolloch))
- Fixes \#1520 - Satisfy port resources from any of the offered ranges [\#1552](https://github.com/mesosphere/marathon/pull/1552) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Release 0.8.2-RC4 [\#1574](https://github.com/mesosphere/marathon/issues/1574)
- http\_endpoints not being split on "," [\#1569](https://github.com/mesosphere/marathon/issues/1569)
- Proxying Marathon requests should use timeouts [\#1541](https://github.com/mesosphere/marathon/issues/1541)
- Enable jsx test suite execution when ```$ sbt test``` is invoked [\#1528](https://github.com/mesosphere/marathon/issues/1528)
- when stop marathon process mesos no delete marathon framework [\#1525](https://github.com/mesosphere/marathon/issues/1525)
- specifying a post action in input json file for docker container [\#1479](https://github.com/mesosphere/marathon/issues/1479)
- make resource paths relative [\#1369](https://github.com/mesosphere/marathon/issues/1369)
- Different output when using headers application/json [\#1357](https://github.com/mesosphere/marathon/issues/1357)
- Specify environment variables in the config to be used on each host through REST API [\#1328](https://github.com/mesosphere/marathon/issues/1328)
- Unable to upload artifacts [\#1305](https://github.com/mesosphere/marathon/issues/1305)
- Health check failed when using docker HOST network mode [\#1297](https://github.com/mesosphere/marathon/issues/1297)
- Gui off by 1 error in paging container instances [\#1265](https://github.com/mesosphere/marathon/issues/1265)
- Changing args to cmd triggers validation error [\#1222](https://github.com/mesosphere/marathon/issues/1222)
- RFE: Respect Content-Disposition header when downloading storeUrls artifacts [\#1037](https://github.com/mesosphere/marathon/issues/1037)
- Running tasks gets expunged after leader election [\#1032](https://github.com/mesosphere/marathon/issues/1032)
- Volume when cmd and not container [\#890](https://github.com/mesosphere/marathon/issues/890)
- Killing multiple Tasks does not recreate tasks [\#877](https://github.com/mesosphere/marathon/issues/877)
- Setting 'cmd' parameter via POST does not change in certain circumstances [\#874](https://github.com/mesosphere/marathon/issues/874)
- Unable to assign servicePort or hostPort [\#847](https://github.com/mesosphere/marathon/issues/847)
- Marathon loses connection to running task [\#821](https://github.com/mesosphere/marathon/issues/821)
- output from /v2/tasks is corrupted after scaling up [\#786](https://github.com/mesosphere/marathon/issues/786)
- Issue launching project with SBT [\#775](https://github.com/mesosphere/marathon/issues/775)
- How can marathon know the each mesos slave resources [\#770](https://github.com/mesosphere/marathon/issues/770)
- Failed to start: Container destroyed during launch [\#734](https://github.com/mesosphere/marathon/issues/734)
- Create new instance when application goes unhealthy [\#729](https://github.com/mesosphere/marathon/issues/729)

**Merged pull requests:**

- Separation of the assets directory \(the UI\) to own repository [\#1601](https://github.com/mesosphere/marathon/pull/1601) ([aldipower](https://github.com/aldipower))
- Update rest-api.md [\#1596](https://github.com/mesosphere/marathon/pull/1596) ([tfrench](https://github.com/tfrench))
- Remove unnecessary slash. [\#1593](https://github.com/mesosphere/marathon/pull/1593) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1569 - Update the changelog with a warning. [\#1592](https://github.com/mesosphere/marathon/pull/1592) ([gkleiman](https://github.com/gkleiman))
- Fixes \#1569 - Split http\_endpoints parameter [\#1590](https://github.com/mesosphere/marathon/pull/1590) ([gkleiman](https://github.com/gkleiman))
- Add Wikia Inc to list of known users of Marathon [\#1587](https://github.com/mesosphere/marathon/pull/1587) ([pchojnacki](https://github.com/pchojnacki))
- Set crossScalaVersion to scalaVersion [\#1581](https://github.com/mesosphere/marathon/pull/1581) ([kolloch](https://github.com/kolloch))
- Improve documentation of --local\_port\_max, --local\_port\_min. [\#1580](https://github.com/mesosphere/marathon/pull/1580) ([kolloch](https://github.com/kolloch))
- Fixes \#1545 - Make it easy to run integration tests [\#1575](https://github.com/mesosphere/marathon/pull/1575) ([kolloch](https://github.com/kolloch))

## [v0.8.2-RC4](https://github.com/mesosphere/marathon/tree/v0.8.2-RC4) (2015-05-28)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.2-RC3...v0.8.2-RC4)

**Implemented enhancements:**

- Use a sensible default for maximum number of versions, if zk\_max\_versions is not defined. [\#1521](https://github.com/mesosphere/marathon/issues/1521)
- Let users specify the Mesos role for each Marathon app [\#1460](https://github.com/mesosphere/marathon/issues/1460)
- Introduce abstraction for leader election [\#900](https://github.com/mesosphere/marathon/issues/900)

**Fixed bugs:**

- Disk resource quota not communicated to Mesos on task launch [\#1522](https://github.com/mesosphere/marathon/issues/1522)
- Marathon don't match correctly the resources for a defined role [\#1520](https://github.com/mesosphere/marathon/issues/1520)
- CPU usage increased dramatically 0.8.1-RC1 -\> master [\#1497](https://github.com/mesosphere/marathon/issues/1497)
- versions within groups isn't specified in the API [\#1459](https://github.com/mesosphere/marathon/issues/1459)
- Marathon delaying app start by 70min after cluster reboot [\#1456](https://github.com/mesosphere/marathon/issues/1456)
- Validation for app creation & update should not differ [\#1446](https://github.com/mesosphere/marathon/issues/1446)
- servicePorts are not copied into ports [\#1365](https://github.com/mesosphere/marathon/issues/1365)
- Bad JSON prints java types rather than human error message [\#1331](https://github.com/mesosphere/marathon/issues/1331)
- Marathon is Crashing Often [\#834](https://github.com/mesosphere/marathon/issues/834)
- Fixes \#1497 - Do not query app versions in MarathonHealthCheckManager [\#1568](https://github.com/mesosphere/marathon/pull/1568) ([kolloch](https://github.com/kolloch))
- Execute the steps of the 0.7.0 migration in sequence [\#1562](https://github.com/mesosphere/marathon/pull/1562) ([kolloch](https://github.com/kolloch))
- Fixes \#1365 - Always export service ports in app.ports field [\#1559](https://github.com/mesosphere/marathon/pull/1559) ([kolloch](https://github.com/kolloch))
- Fixes \#1446 - Disallow empty strings for app.cmd [\#1557](https://github.com/mesosphere/marathon/pull/1557) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Test Issue \(ignore\) [\#1567](https://github.com/mesosphere/marathon/issues/1567)
- Versioning for recent additions in docs [\#1560](https://github.com/mesosphere/marathon/issues/1560)
- No mesosphere/marathon:0.8.2-RC3 image on docker hub [\#1543](https://github.com/mesosphere/marathon/issues/1543)
- Marathon 0.8.2-RC3 never re-registers after cluster restart [\#1538](https://github.com/mesosphere/marathon/issues/1538)
- Flaky MarathonHealthCheckManagerTest [\#1408](https://github.com/mesosphere/marathon/issues/1408)
- Replace references to elastic mesos from the tutorial [\#1394](https://github.com/mesosphere/marathon/issues/1394)
- Command Health Check Failing [\#1380](https://github.com/mesosphere/marathon/issues/1380)
- SIGSEGV immediately after zookeeper session initiation \(with both OpenJDK and Oracle JDK\) [\#1352](https://github.com/mesosphere/marathon/issues/1352)
- Marathon Crashes continuously [\#1299](https://github.com/mesosphere/marathon/issues/1299)
- NPE during group update when file is empty [\#1247](https://github.com/mesosphere/marathon/issues/1247)
- Already 0 instances running, not scaling [\#1118](https://github.com/mesosphere/marathon/issues/1118)
- Marathon service can't find Mesos libs [\#967](https://github.com/mesosphere/marathon/issues/967)
- Refactor MarathonScheduler.newTask [\#937](https://github.com/mesosphere/marathon/issues/937)
- Add support for custom app data structures [\#773](https://github.com/mesosphere/marathon/issues/773)
- Cannot access bridged docker port [\#753](https://github.com/mesosphere/marathon/issues/753)
- haproxy-marathon-bridge : the 'contimeout' directive is now deprecated in favor of 'timeout connect' [\#742](https://github.com/mesosphere/marathon/issues/742)
- Marathon kill tasks due to NPE at mesosphere.util.BackToTheFuture [\#595](https://github.com/mesosphere/marathon/issues/595)
- Allow executor reuse [\#276](https://github.com/mesosphere/marathon/issues/276)

**Merged pull requests:**

- Update the docs for constraints to use the v2 api. [\#1576](https://github.com/mesosphere/marathon/pull/1576) ([spacejam](https://github.com/spacejam))
- Fixes \#1560 - Versioning recent changes in the API [\#1561](https://github.com/mesosphere/marathon/pull/1561) ([kolloch](https://github.com/kolloch))
- Fix service discovery link in docs. [\#1555](https://github.com/mesosphere/marathon/pull/1555) ([ssk2](https://github.com/ssk2))
- Fixes \#1522 - Include disk resource share in TaskInfo [\#1550](https://github.com/mesosphere/marathon/pull/1550) ([kolloch](https://github.com/kolloch))
- Fixes \#937 - TaskFactory.newTask should return an Option of a case class [\#1549](https://github.com/mesosphere/marathon/pull/1549) ([kolloch](https://github.com/kolloch))
- Fixes \#929 - Allow docker apps to use the same host/container port [\#1548](https://github.com/mesosphere/marathon/pull/1548) ([kolloch](https://github.com/kolloch))
- add json-schema validations to AddDefinitionTest [\#1547](https://github.com/mesosphere/marathon/pull/1547) ([tamarrow](https://github.com/tamarrow))
- Update service-discovery-load-balancing.md [\#1537](https://github.com/mesosphere/marathon/pull/1537) ([hansbogert](https://github.com/hansbogert))
- Update .gitignore and add tables support. [\#1532](https://github.com/mesosphere/marathon/pull/1532) ([ssk2](https://github.com/ssk2))
- Grammar. [\#1531](https://github.com/mesosphere/marathon/pull/1531) ([ssk2](https://github.com/ssk2))
- add privileged and parameters definition to AppDefinition json schema [\#1529](https://github.com/mesosphere/marathon/pull/1529) ([tamarrow](https://github.com/tamarrow))
- Fixes \#1460 - Allow configuring resource roles per app [\#1527](https://github.com/mesosphere/marathon/pull/1527) ([kolloch](https://github.com/kolloch))
- ModelValidation: make sure, the given group is not null. [\#1526](https://github.com/mesosphere/marathon/pull/1526) ([aquamatthias](https://github.com/aquamatthias))
- Add documentation for group versions. [\#1524](https://github.com/mesosphere/marathon/pull/1524) ([aquamatthias](https://github.com/aquamatthias))
- Set a default value for zk\_max\_versions, if this parameter is omitted. [\#1523](https://github.com/mesosphere/marathon/pull/1523) ([aquamatthias](https://github.com/aquamatthias))
- Enable better error messages for json rendering. [\#1503](https://github.com/mesosphere/marathon/pull/1503) ([aquamatthias](https://github.com/aquamatthias))
- Parse Metrics created from scaling test and compare to a base line. [\#1502](https://github.com/mesosphere/marathon/pull/1502) ([aquamatthias](https://github.com/aquamatthias))
- Log "No matching offer ..." at level DEBUG [\#1498](https://github.com/mesosphere/marathon/pull/1498) ([hellertime](https://github.com/hellertime))
- Add WebSocket and HTTP SSE support to stream Marathon events directly. [\#1436](https://github.com/mesosphere/marathon/pull/1436) ([aquamatthias](https://github.com/aquamatthias))

## [v0.8.2-RC3](https://github.com/mesosphere/marathon/tree/v0.8.2-RC3) (2015-05-13)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.2-RC2...v0.8.2-RC3)

**Fixed bugs:**

- Running marathon 0.8.2-RC2 in local development mode fails  [\#1507](https://github.com/mesosphere/marathon/issues/1507)
- Limit number of revisions to store [\#1464](https://github.com/mesosphere/marathon/issues/1464)
- Fixes \#1507 - Ignore all NonFatal exceptions in MarathonStore.names\(\) [\#1508](https://github.com/mesosphere/marathon/pull/1508) ([kolloch](https://github.com/kolloch))

**Closed issues:**

- Make it easy to run integration/scale tests via Docker [\#1545](https://github.com/mesosphere/marathon/issues/1545)
- can't find marathon log [\#1519](https://github.com/mesosphere/marathon/issues/1519)
- 0.8.2-RC2 doesn't start with a blank Zookeeper [\#1516](https://github.com/mesosphere/marathon/issues/1516)
- Decouple API \(un\)marshaling types from internal models [\#1505](https://github.com/mesosphere/marathon/issues/1505)
- Don't set ulimit in marathon-framework [\#1389](https://github.com/mesosphere/marathon/issues/1389)

**Merged pull requests:**

- Update instructions not to reference a blog post. [\#1515](https://github.com/mesosphere/marathon/pull/1515) ([ssk2](https://github.com/ssk2))
- Fix \#1469 - Adding framework name to the marathon config block on 'About' section. [\#1514](https://github.com/mesosphere/marathon/pull/1514) ([hekaldama](https://github.com/hekaldama))
- IntegrationTest: mesos-local bind to localhost [\#1510](https://github.com/mesosphere/marathon/pull/1510) ([aquamatthias](https://github.com/aquamatthias))
- IntegrationTest: make sure the zk repository is empty [\#1509](https://github.com/mesosphere/marathon/pull/1509) ([aquamatthias](https://github.com/aquamatthias))
- Fix Integration tests with mesos 0.22.1 [\#1501](https://github.com/mesosphere/marathon/pull/1501) ([aquamatthias](https://github.com/aquamatthias))
- MARATHON-100: Making url paths relative to enable proxied pathnames [\#1500](https://github.com/mesosphere/marathon/pull/1500) ([aldipower](https://github.com/aldipower))
- Consolidate docs text and move up. Update Mesosphere docs link. [\#1495](https://github.com/mesosphere/marathon/pull/1495) ([ssk2](https://github.com/ssk2))
- Tweak readme instructions for Docker. [\#1494](https://github.com/mesosphere/marathon/pull/1494) ([ssk2](https://github.com/ssk2))
- Update docs version. Fixes \#1491 [\#1493](https://github.com/mesosphere/marathon/pull/1493) ([ssk2](https://github.com/ssk2))
- Move "developing in a VM" instructions from wiki into docs [\#1492](https://github.com/mesosphere/marathon/pull/1492) ([ssk2](https://github.com/ssk2))
- extends apps basics doc with Docker [\#1490](https://github.com/mesosphere/marathon/pull/1490) ([mhausenblas](https://github.com/mhausenblas))
- Fixes \#1480 - use the correct conjunction operator in app-state diagram. [\#1485](https://github.com/mesosphere/marathon/pull/1485) ([kolloch](https://github.com/kolloch))
- raise open file limit only if running as root and if it's too low [\#1466](https://github.com/mesosphere/marathon/pull/1466) ([lloesche](https://github.com/lloesche))
- Improves \#1456 - Increase task launch delay only once [\#1461](https://github.com/mesosphere/marathon/pull/1461) ([kolloch](https://github.com/kolloch))
- Check-in mesos.proto file. [\#1455](https://github.com/mesosphere/marathon/pull/1455) ([kolloch](https://github.com/kolloch))

## [v0.8.2-RC2](https://github.com/mesosphere/marathon/tree/v0.8.2-RC2) (2015-05-11)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.2-RC1...v0.8.2-RC2)

**Fixed bugs:**

- App stays in locked state [\#1481](https://github.com/mesosphere/marathon/issues/1481)
- Destroy App in web ui does not work consistently  [\#961](https://github.com/mesosphere/marathon/issues/961)

**Closed issues:**

- Update docs with Marathon releases [\#1491](https://github.com/mesosphere/marathon/issues/1491)
- marathon abnormal exit [\#1488](https://github.com/mesosphere/marathon/issues/1488)
- Pulling from a private repo with SSL and basic auth not working [\#1482](https://github.com/mesosphere/marathon/issues/1482)
- Question: Health-Check Lifecycle Diagramm [\#1480](https://github.com/mesosphere/marathon/issues/1480)
- Introduce multiple scaling strategies [\#1477](https://github.com/mesosphere/marathon/issues/1477)
- Use healthy status in dependencies between applications [\#1474](https://github.com/mesosphere/marathon/issues/1474)
- 0.8.2-RC1 is failing constaintly [\#1472](https://github.com/mesosphere/marathon/issues/1472)
- Metrics should include zk read and write times [\#1465](https://github.com/mesosphere/marathon/issues/1465)
- Rolling Restart Alternative Stopping Mechanism [\#1463](https://github.com/mesosphere/marathon/issues/1463)
- sbt can't find com.twitter.common.zookeeper dependency when building marathon from source [\#1457](https://github.com/mesosphere/marathon/issues/1457)
- Build fails because of missing libraries [\#1453](https://github.com/mesosphere/marathon/issues/1453)
- Remove ulimit changes from shell script [\#1452](https://github.com/mesosphere/marathon/issues/1452)
- Provide applications.json file for apps to be auto-launched at startup [\#1449](https://github.com/mesosphere/marathon/issues/1449)
- marathon docker deploy only one instance can access [\#1441](https://github.com/mesosphere/marathon/issues/1441)
- storeUrls: unexpected behavior when updating existing app [\#1437](https://github.com/mesosphere/marathon/issues/1437)
- Marathon restart deployment stuck for service launched with constraints: \[\[hostname:UNIQUE\]\] [\#1425](https://github.com/mesosphere/marathon/issues/1425)
- Formalize adherence to semantic versioning [\#1332](https://github.com/mesosphere/marathon/issues/1332)
- URI runs over modal [\#1298](https://github.com/mesosphere/marathon/issues/1298)

**Merged pull requests:**

- Tweak text. [\#1496](https://github.com/mesosphere/marathon/pull/1496) ([ssk2](https://github.com/ssk2))
- Fix for flaky integration tests [\#1486](https://github.com/mesosphere/marathon/pull/1486) ([aquamatthias](https://github.com/aquamatthias))
- fixes \#1481 - Use timeout in call to Future.get in MarathonStore.names\(\) [\#1484](https://github.com/mesosphere/marathon/pull/1484) ([drexin](https://github.com/drexin))
- Update mesos-util dependency to 0.22.1-1 [\#1476](https://github.com/mesosphere/marathon/pull/1476) ([drexin](https://github.com/drexin))
- Remove extra slash in @Path for artifacts [\#1471](https://github.com/mesosphere/marathon/pull/1471) ([bobrik](https://github.com/bobrik))
- Add integration tests for apps and groups  [\#1467](https://github.com/mesosphere/marathon/pull/1467) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1332 - Formalize adherence to semantic versioning [\#1462](https://github.com/mesosphere/marathon/pull/1462) ([kolloch](https://github.com/kolloch))
- Include API doc generation into travis.yml [\#1454](https://github.com/mesosphere/marathon/pull/1454) ([kolloch](https://github.com/kolloch))
- Make app version component nicer [\#1443](https://github.com/mesosphere/marathon/pull/1443) ([bobrik](https://github.com/bobrik))
- Add Allegro Group to list of companies using marathon [\#1442](https://github.com/mesosphere/marathon/pull/1442) ([janisz](https://github.com/janisz))
- Add servicerouter Python Script to Marathon [\#1440](https://github.com/mesosphere/marathon/pull/1440) ([lloesche](https://github.com/lloesche))
- Fixes \#1438 - Make AppDeployIntegrationTest resilient to event reordering [\#1439](https://github.com/mesosphere/marathon/pull/1439) ([kolloch](https://github.com/kolloch))
- Consolidate seds functionality in awk itself [\#1411](https://github.com/mesosphere/marathon/pull/1411) ([pradeepchhetri](https://github.com/pradeepchhetri))

## [v0.8.2-RC1](https://github.com/mesosphere/marathon/tree/v0.8.2-RC1) (2015-04-29)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.1...v0.8.2-RC1)

**Implemented enhancements:**

- Matching an offer with an app is slow [\#1421](https://github.com/mesosphere/marathon/issues/1421)
- Listing all tasks of an app is very slow with large numbers of tasks [\#1278](https://github.com/mesosphere/marathon/issues/1278)
- Tag TaskInfo with app labels [\#1121](https://github.com/mesosphere/marathon/issues/1121)
- more helpful error when /groups are POSTed to /apps [\#1067](https://github.com/mesosphere/marathon/issues/1067)
- Query apps and tasks based on labels. [\#1053](https://github.com/mesosphere/marathon/issues/1053)
- Handle DockerInfo force\_pull\_image [\#837](https://github.com/mesosphere/marathon/issues/837)
- If a resource offer can accommodate multiple jobs in the queue, schedule multiple jobs at once [\#14](https://github.com/mesosphere/marathon/issues/14)
- Feature/cors headers [\#1296](https://github.com/mesosphere/marathon/pull/1296) ([mlunoe](https://github.com/mlunoe))
- Add option to force docker pull [\#899](https://github.com/mesosphere/marathon/pull/899) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Fixed bugs:**

- When deleting an app, don't remove app definition before all task are killed [\#1431](https://github.com/mesosphere/marathon/issues/1431)
- no-logger option throws error [\#1370](https://github.com/mesosphere/marathon/issues/1370)
- Deployment calculations are wrong [\#1344](https://github.com/mesosphere/marathon/issues/1344)
- Marathon sometimes registers with a new FrameworkID [\#1292](https://github.com/mesosphere/marathon/issues/1292)
- \n does not get trimmed from the secret when using Mesos auth [\#1289](https://github.com/mesosphere/marathon/issues/1289)
- Start health checks when app has been started [\#1276](https://github.com/mesosphere/marathon/issues/1276)
- Groups and Applications may not have the same identifier [\#851](https://github.com/mesosphere/marathon/issues/851)
- Deployment rollback often does apply to multiple running reployments [\#660](https://github.com/mesosphere/marathon/issues/660)
- Scaling from a non-leader node fails in HA mode [\#295](https://github.com/mesosphere/marathon/issues/295)
- Removed useless synchronization. [\#1378](https://github.com/mesosphere/marathon/pull/1378) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Closed issues:**

- AppDeployIntegrationTest is unstable because of event order [\#1438](https://github.com/mesosphere/marathon/issues/1438)
- Marathon cluster all apps restored to old point in time snapshot by delete deployment [\#1434](https://github.com/mesosphere/marathon/issues/1434)
- Remove flaky twitter maven repo [\#1433](https://github.com/mesosphere/marathon/issues/1433)
- Docker build issue [\#1417](https://github.com/mesosphere/marathon/issues/1417)
- Healthcheck for non web apps [\#1412](https://github.com/mesosphere/marathon/issues/1412)
- The DNS name is the internal dns of  EC2 [\#1404](https://github.com/mesosphere/marathon/issues/1404)
- Docker container name not being used [\#1403](https://github.com/mesosphere/marathon/issues/1403)
- Deployments "steps" json [\#1400](https://github.com/mesosphere/marathon/issues/1400)
- Marathon can not scale more instances then the number of slaves [\#1392](https://github.com/mesosphere/marathon/issues/1392)
- Simulate Mesos Environment with Many Tasks on Developer Machine [\#1391](https://github.com/mesosphere/marathon/issues/1391)
- Use separate Mesos work dir for integration tests  [\#1388](https://github.com/mesosphere/marathon/issues/1388)
- Detect MESOS\_NATIVE\_JAVA\_LIBRARY automatically in integration tests [\#1387](https://github.com/mesosphere/marathon/issues/1387)
- Allow running of integration tests with an already running Marathon instance [\#1386](https://github.com/mesosphere/marathon/issues/1386)
- PUT requests should replace and not update current definitions [\#1385](https://github.com/mesosphere/marathon/issues/1385)
- How do you provide the docker --dns=1.2.3.4 via the api? [\#1382](https://github.com/mesosphere/marathon/issues/1382)
- marathon is not listenning on TCP port [\#1375](https://github.com/mesosphere/marathon/issues/1375)
- Update the documentation site [\#1373](https://github.com/mesosphere/marathon/issues/1373)
- Add REST API documentation for labels [\#1372](https://github.com/mesosphere/marathon/issues/1372)
- Log exceptions of failed callback POSTS [\#1366](https://github.com/mesosphere/marathon/issues/1366)
- Why marathon throw an exception while occur a mistake of http event POST? [\#1362](https://github.com/mesosphere/marathon/issues/1362)
- Add option to disable HTTP access if HTTPS is enabled. [\#1360](https://github.com/mesosphere/marathon/issues/1360)
- Marathon can not post a event to the url which has already been registered \(about `/v2/eventSubscriptions`\) [\#1355](https://github.com/mesosphere/marathon/issues/1355)
- why the task keep running? [\#1354](https://github.com/mesosphere/marathon/issues/1354)
- can't scale application [\#1353](https://github.com/mesosphere/marathon/issues/1353)
- POST /v2/apps behaves like PUT to update existing app  [\#1351](https://github.com/mesosphere/marathon/issues/1351)
- Changing task status to running in TaskTracker is slow [\#1342](https://github.com/mesosphere/marathon/issues/1342)
- Support disk resource [\#1333](https://github.com/mesosphere/marathon/issues/1333)
- Leader value is not unset when zk is unreachable [\#1324](https://github.com/mesosphere/marathon/issues/1324)
- marathon 0.8.0 \[Status Update\] RUNNING event not working anymore. [\#1321](https://github.com/mesosphere/marathon/issues/1321)
- Destroy app often requires marathon service restart [\#1317](https://github.com/mesosphere/marathon/issues/1317)
- Gitalytics link on the README is broken. [\#1300](https://github.com/mesosphere/marathon/issues/1300)
- Docker container get killed every time when I try to curl a web server in it   [\#1295](https://github.com/mesosphere/marathon/issues/1295)
- After I update groups, app not destroy, but groups said it's done [\#1294](https://github.com/mesosphere/marathon/issues/1294)
- Publish 0.8.1 on docker hub [\#1293](https://github.com/mesosphere/marathon/issues/1293)
- App with "cpu: 0" is accepted as valid, but rejected by Mesos [\#1269](https://github.com/mesosphere/marathon/issues/1269)
- Clearly document that HAProxy does not support UDP load balancing [\#1268](https://github.com/mesosphere/marathon/issues/1268)
- Possible race condition on simultaneous application launch [\#1215](https://github.com/mesosphere/marathon/issues/1215)
- Decouple periodic task count frequency from task reconciliation [\#1177](https://github.com/mesosphere/marathon/issues/1177)
- Support auto scaling [\#1131](https://github.com/mesosphere/marathon/issues/1131)
- Clean up integration tests [\#1070](https://github.com/mesosphere/marathon/issues/1070)
- REST API: Add meta-data tag for applications/tasks [\#980](https://github.com/mesosphere/marathon/issues/980)
- Task has no ports listed but app has two ports configured [\#944](https://github.com/mesosphere/marathon/issues/944)
- Environments variables in BRIDGE mode \(PORT, PORTS\) [\#905](https://github.com/mesosphere/marathon/issues/905)
- API constantly changing [\#886](https://github.com/mesosphere/marathon/issues/886)
- SSL is not enforced if SSL settings are provided [\#474](https://github.com/mesosphere/marathon/issues/474)

**Merged pull requests:**

- fixes \#1433 - removed flaky twitter repo [\#1435](https://github.com/mesosphere/marathon/pull/1435) ([drexin](https://github.com/drexin))
- fixes \#1431 - On app deletion only remove app definition from repo when ... [\#1432](https://github.com/mesosphere/marathon/pull/1432) ([drexin](https://github.com/drexin))
- Marathon Maven plugin from HolidayCheck added as a client example [\#1430](https://github.com/mesosphere/marathon/pull/1430) ([krystiannowak](https://github.com/krystiannowak))
- .dockerignore Dramatically reduce the size of the docker context uploade... [\#1427](https://github.com/mesosphere/marathon/pull/1427) ([kolloch](https://github.com/kolloch))
- HolidayCheck added as one of Marathon users [\#1426](https://github.com/mesosphere/marathon/pull/1426) ([krystiannowak](https://github.com/krystiannowak))
- Fixes \#14 - Use one offer for multiple task launch... [\#1424](https://github.com/mesosphere/marathon/pull/1424) ([kolloch](https://github.com/kolloch))
- fixes \#1421 - refactor offer matching to increase performance and readab... [\#1422](https://github.com/mesosphere/marathon/pull/1422) ([drexin](https://github.com/drexin))
- Add debugging helper functions and make them available via command line. [\#1420](https://github.com/mesosphere/marathon/pull/1420) ([aquamatthias](https://github.com/aquamatthias))
- Fix documentation, DELETE app returns deployment info. [\#1419](https://github.com/mesosphere/marathon/pull/1419) ([kolloch](https://github.com/kolloch))
- Fixes \#1053 add support for querying multiple labels of applications [\#1416](https://github.com/mesosphere/marathon/pull/1416) ([aquamatthias](https://github.com/aquamatthias))
- Fixes \#1391 - Provide a simplistic simulation of mesos for scale testing [\#1413](https://github.com/mesosphere/marathon/pull/1413) ([kolloch](https://github.com/kolloch))
- Move new application introduction into its own guide. [\#1409](https://github.com/mesosphere/marathon/pull/1409) ([ssk2](https://github.com/ssk2))
- MarathonStore -- reading 0 bytes from store is not an error [\#1406](https://github.com/mesosphere/marathon/pull/1406) ([kolloch](https://github.com/kolloch))
- Make it easy to expand logging in tests by providing a base config. [\#1402](https://github.com/mesosphere/marathon/pull/1402) ([kolloch](https://github.com/kolloch))
- Fixes \#660 - Revert only changes of selected deployment on rollback [\#1399](https://github.com/mesosphere/marathon/pull/1399) ([kolloch](https://github.com/kolloch))
- Add a recipe for starting a private docker registry. [\#1396](https://github.com/mesosphere/marathon/pull/1396) ([aquamatthias](https://github.com/aquamatthias))
- Removed References to Elastic Mesos from Readme [\#1395](https://github.com/mesosphere/marathon/pull/1395) ([joerg84](https://github.com/joerg84))
- Fix \#851 - Allow apps to replace groups without apps [\#1393](https://github.com/mesosphere/marathon/pull/1393) ([kolloch](https://github.com/kolloch))
- Allow integration testing against external Marathon [\#1390](https://github.com/mesosphere/marathon/pull/1390) ([kolloch](https://github.com/kolloch))
- fixes \#1121 - Set labels configured in Marathon in Mesos TaskInfo [\#1384](https://github.com/mesosphere/marathon/pull/1384) ([drexin](https://github.com/drexin))
- Revert "Fix \#851 - Remove empty non-root groups automatically" [\#1383](https://github.com/mesosphere/marathon/pull/1383) ([drexin](https://github.com/drexin))
- adds docs around the uris concept [\#1381](https://github.com/mesosphere/marathon/pull/1381) ([mhausenblas](https://github.com/mhausenblas))
- Add link to marathonctl [\#1379](https://github.com/mesosphere/marathon/pull/1379) ([shoenig](https://github.com/shoenig))
- Updated Chaos to latest version 0.6.5. [\#1376](https://github.com/mesosphere/marathon/pull/1376) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix syntax error in docs \(missing endhighlight\). [\#1374](https://github.com/mesosphere/marathon/pull/1374) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix \#851 - Remove empty non-root groups automatically [\#1371](https://github.com/mesosphere/marathon/pull/1371) ([kolloch](https://github.com/kolloch))
- Fixes \#474 - Allow disabling HTTP altogether [\#1368](https://github.com/mesosphere/marathon/pull/1368) ([kolloch](https://github.com/kolloch))
- Fix \#1366 - directly log failure in posting event to callback URL [\#1367](https://github.com/mesosphere/marathon/pull/1367) ([kolloch](https://github.com/kolloch))
- ScaleApps separately to reconciliation of tasks. Fixes \#1177 [\#1361](https://github.com/mesosphere/marathon/pull/1361) ([ssk2](https://github.com/ssk2))
- Updated the Dockerfile for Mesos 0.22.0. [\#1358](https://github.com/mesosphere/marathon/pull/1358) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update deployments.md regarding force-updating. [\#1348](https://github.com/mesosphere/marathon/pull/1348) ([timoreimann](https://github.com/timoreimann))
- Fix \#1344 - Execute independent actions in parallel [\#1347](https://github.com/mesosphere/marathon/pull/1347) ([kolloch](https://github.com/kolloch))
- fixes \#1342 - Improve performance of TaskTracker.running by using map lo... [\#1343](https://github.com/mesosphere/marathon/pull/1343) ([drexin](https://github.com/drexin))
- Update mesos-utils to latest version \(0.22.0-1\). [\#1340](https://github.com/mesosphere/marathon/pull/1340) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Remove link to decommissioned service. [\#1339](https://github.com/mesosphere/marathon/pull/1339) ([ssk2](https://github.com/ssk2))
- Make TasksResource.indexJson code more explicit [\#1338](https://github.com/mesosphere/marathon/pull/1338) ([kolloch](https://github.com/kolloch))
- Add link to contribution instructions to README and tidy up text [\#1335](https://github.com/mesosphere/marathon/pull/1335) ([ssk2](https://github.com/ssk2))
- fixes \#1278 - Improves response time of /v2/tasks and /v2/apps/{appId}/t... [\#1330](https://github.com/mesosphere/marathon/pull/1330) ([drexin](https://github.com/drexin))
- User specified env variables overwrite automatic port variables \(\#905\) [\#1329](https://github.com/mesosphere/marathon/pull/1329) ([kolloch](https://github.com/kolloch))
- REST API: Extend documentation of the app.ports field [\#1327](https://github.com/mesosphere/marathon/pull/1327) ([kolloch](https://github.com/kolloch))
- fixes \#1292 - Don't create SchedulerDriver before instance has been elec... [\#1325](https://github.com/mesosphere/marathon/pull/1325) ([drexin](https://github.com/drexin))
- Upgrading Chaos to 0.6.3 \(env variables for http auth and ssl\) [\#1323](https://github.com/mesosphere/marathon/pull/1323) ([swartzrock](https://github.com/swartzrock))
- Change link to new Constraints Marathon Documentation page on error message in GUI [\#1322](https://github.com/mesosphere/marathon/pull/1322) ([quamilek](https://github.com/quamilek))
- --no-logger - do not propagate it to scala [\#1320](https://github.com/mesosphere/marathon/pull/1320) ([sielaq](https://github.com/sielaq))
- Documented task environment variables. [\#1319](https://github.com/mesosphere/marathon/pull/1319) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fixes \#1215, serialize calculation of DeploymentPlans [\#1318](https://github.com/mesosphere/marathon/pull/1318) ([kolloch](https://github.com/kolloch))
- Fixes \#1268. Clarify UDP service ports on docker [\#1315](https://github.com/mesosphere/marathon/pull/1315) ([ryanleary](https://github.com/ryanleary))
- Fix references to haproxy-marathon-bridge in documentation [\#1314](https://github.com/mesosphere/marathon/pull/1314) ([kolloch](https://github.com/kolloch))
- Some basic documentation for DeploymentPlan and DeploymentStep [\#1313](https://github.com/mesosphere/marathon/pull/1313) ([kolloch](https://github.com/kolloch))
- MarathonStore: Log deserialization errors [\#1311](https://github.com/mesosphere/marathon/pull/1311) ([kolloch](https://github.com/kolloch))
- waffle.io Badge [\#1304](https://github.com/mesosphere/marathon/pull/1304) ([waffle-iron](https://github.com/waffle-iron))
- fixes \#1269 - Reject app definition with 'cpus' less than or equal to 0 [\#1301](https://github.com/mesosphere/marathon/pull/1301) ([drexin](https://github.com/drexin))
- Add reference to the freenode marathon IRC channel [\#1291](https://github.com/mesosphere/marathon/pull/1291) ([dominichamon](https://github.com/dominichamon))
- fixes \#1287 - Added Accept header to MarathonFacade.tasks [\#1288](https://github.com/mesosphere/marathon/pull/1288) ([drexin](https://github.com/drexin))
- fixes \#1106 - Return empty HealthCheck result instead of None, when no r... [\#1107](https://github.com/mesosphere/marathon/pull/1107) ([drexin](https://github.com/drexin))
- removed broken tutorial link and added digitalocean as a place to try marathon [\#1088](https://github.com/mesosphere/marathon/pull/1088) ([kensipe](https://github.com/kensipe))
- Support reading config from /etc/default/marathon [\#1042](https://github.com/mesosphere/marathon/pull/1042) ([iven](https://github.com/iven))

## [v0.8.1](https://github.com/mesosphere/marathon/tree/v0.8.1) (2015-03-11)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.1-RC2...v0.8.1)

**Implemented enhancements:**

- Add support for https health check [\#772](https://github.com/mesosphere/marathon/issues/772)

**Fixed bugs:**

- 4 group integration tests fail because of missing Accept header [\#1287](https://github.com/mesosphere/marathon/issues/1287)

**Closed issues:**

- Listing apps and tasks gets unresponsive with large number of tasks [\#1274](https://github.com/mesosphere/marathon/issues/1274)
- Health status not reflected in REST API until some time after start [\#1270](https://github.com/mesosphere/marathon/issues/1270)
- Binding to 127.0.0.1 instead of 0.0.0.0 [\#1261](https://github.com/mesosphere/marathon/issues/1261)

**Merged pull requests:**

- Update rest-api.md [\#1285](https://github.com/mesosphere/marathon/pull/1285) ([felixb](https://github.com/felixb))
- Link new Ruby Marathon Client [\#1284](https://github.com/mesosphere/marathon/pull/1284) ([felixb](https://github.com/felixb))
- Add Otto to Marathon users in README [\#1283](https://github.com/mesosphere/marathon/pull/1283) ([felixb](https://github.com/felixb))
- Use /v2/ API with curl [\#1282](https://github.com/mesosphere/marathon/pull/1282) ([felixb](https://github.com/felixb))
- Minor typo fix [\#1280](https://github.com/mesosphere/marathon/pull/1280) ([wzyboy](https://github.com/wzyboy))
- fixes \#1274 - improved performance of AppResource.index and related inte... [\#1277](https://github.com/mesosphere/marathon/pull/1277) ([drexin](https://github.com/drexin))
- Added ING to Marathon users in README [\#1275](https://github.com/mesosphere/marathon/pull/1275) ([wouterkwakernaak](https://github.com/wouterkwakernaak))
- Update Chaos to version 0.6.2. [\#1273](https://github.com/mesosphere/marathon/pull/1273) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updates executor health checks description [\#1271](https://github.com/mesosphere/marathon/pull/1271) ([jrandall](https://github.com/jrandall))

## [v0.8.1-RC2](https://github.com/mesosphere/marathon/tree/v0.8.1-RC2) (2015-03-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.1-RC1...v0.8.1-RC2)

**Implemented enhancements:**

- Add --no-logger functionality so logging can be optional [\#1246](https://github.com/mesosphere/marathon/issues/1246)

**Fixed bugs:**

- Restart an app on non marathon leader not work  [\#1239](https://github.com/mesosphere/marathon/issues/1239)
- App with null ID causes issues [\#704](https://github.com/mesosphere/marathon/issues/704)

**Closed issues:**

- move endpoint to generate deployment previews to the groups resource [\#1256](https://github.com/mesosphere/marathon/issues/1256)
- change DELETE /v2/tasks to POST /v2/tasks/delete [\#1252](https://github.com/mesosphere/marathon/issues/1252)
- Unexpected 'feature' of the docker containerizer with parameters [\#1243](https://github.com/mesosphere/marathon/issues/1243)
- Removal of env variables does not trigger deployment [\#1238](https://github.com/mesosphere/marathon/issues/1238)
- Variable grace period – supporting HTTP health check result "100 - continue" [\#1126](https://github.com/mesosphere/marathon/issues/1126)
- Health checks for deployment [\#1099](https://github.com/mesosphere/marathon/issues/1099)

**Merged pull requests:**

- Changed minimumOverCapacity to maximumOverCapacity in the POST /v2/apps ... [\#1266](https://github.com/mesosphere/marathon/pull/1266) ([michiroth](https://github.com/michiroth))
- Adding Motus to list of companies using Marathon [\#1263](https://github.com/mesosphere/marathon/pull/1263) ([sdwr98](https://github.com/sdwr98))
- fixes \#1252 - Moved endpoint `DELETE /v2/tasks` to `POST /v2/tasks/delet... [\#1258](https://github.com/mesosphere/marathon/pull/1258) ([drexin](https://github.com/drexin))
- fixes \#1256 - Moved endpoint to generate deployment previews from /v2/de... [\#1257](https://github.com/mesosphere/marathon/pull/1257) ([drexin](https://github.com/drexin))
- adding HTTPS support [\#1255](https://github.com/mesosphere/marathon/pull/1255) ([nevins-b](https://github.com/nevins-b))
- fixes \#1239 - Set content type to application/json by default in LeaderP... [\#1253](https://github.com/mesosphere/marathon/pull/1253) ([drexin](https://github.com/drexin))
- Adds support for returning app schema [\#1250](https://github.com/mesosphere/marathon/pull/1250) ([jsancio](https://github.com/jsancio))
- Include task\_launch\_timeout in kill log message [\#1249](https://github.com/mesosphere/marathon/pull/1249) ([guenter](https://github.com/guenter))
- Add --no-logger functionality so logging can be optional [\#1245](https://github.com/mesosphere/marathon/pull/1245) ([sielaq](https://github.com/sielaq))
- Ignore health checks with HTTP response 100 to 199 [\#1188](https://github.com/mesosphere/marathon/pull/1188) ([sttts](https://github.com/sttts))
- Slim docker image [\#925](https://github.com/mesosphere/marathon/pull/925) ([bobrik](https://github.com/bobrik))

## [v0.8.1-RC1](https://github.com/mesosphere/marathon/tree/v0.8.1-RC1) (2015-02-25)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.0...v0.8.1-RC1)

**Implemented enhancements:**

- Add new endpoint to kill a given list of tasks [\#1206](https://github.com/mesosphere/marathon/issues/1206)
- Return deployment info instead of app definition when creating an app with PUT [\#1183](https://github.com/mesosphere/marathon/issues/1183)
- Disallow apps the be overwritten with a POST [\#1180](https://github.com/mesosphere/marathon/issues/1180)
- Get deployment plan before running deployment [\#1153](https://github.com/mesosphere/marathon/issues/1153)
- Send `webui\_url` in FrameworkInfo [\#801](https://github.com/mesosphere/marathon/issues/801)
- Add router, make resources linkable [\#325](https://github.com/mesosphere/marathon/issues/325)
- Return deployment with POST /v2/apps response. [\#1202](https://github.com/mesosphere/marathon/pull/1202) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Task health pie chart in application list view [\#914](https://github.com/mesosphere/marathon/pull/914) ([sttts](https://github.com/sttts))

**Fixed bugs:**

- A disturbance in the ?force for app restart [\#1228](https://github.com/mesosphere/marathon/issues/1228)
- /v2/queue endpoint is brokenly verbose [\#1210](https://github.com/mesosphere/marathon/issues/1210)
- Validation logic for xor\(cmd, args\) is broken when container is set [\#1195](https://github.com/mesosphere/marathon/issues/1195)
- Getting an invalid application version returns a missleading message. [\#1186](https://github.com/mesosphere/marathon/issues/1186)
- Potential deadlock in MarathonSchedulerActor [\#1178](https://github.com/mesosphere/marathon/issues/1178)
- Groups play-json Format is too strict [\#1167](https://github.com/mesosphere/marathon/issues/1167)
- Bring back `delay` field to /v2/queue [\#1157](https://github.com/mesosphere/marathon/issues/1157)
- Don't show tasks with count 0 in /v2/queue output [\#1155](https://github.com/mesosphere/marathon/issues/1155)
- Health checks are not working correctly [\#1151](https://github.com/mesosphere/marathon/issues/1151)
- Restarted deployments are not being deleted after successful completion [\#1150](https://github.com/mesosphere/marathon/issues/1150)
- 0.8.0: 'kill task' does not allow new task to take its place [\#1145](https://github.com/mesosphere/marathon/issues/1145)
- Marathon restarts app in POST /v2/apps [\#1044](https://github.com/mesosphere/marathon/issues/1044)
- Ensure service ports are unique [\#1002](https://github.com/mesosphere/marathon/issues/1002)
- IE9 uses cached Ajax responses, never updates /v2/apps [\#347](https://github.com/mesosphere/marathon/issues/347)

**Closed issues:**

- Add optional flag to set the framework ui url [\#1231](https://github.com/mesosphere/marathon/issues/1231)
- Constraint: Slave that can only run one kind of app [\#1209](https://github.com/mesosphere/marathon/issues/1209)
- args from app definition are ignored when scaling app from web ui [\#1194](https://github.com/mesosphere/marathon/issues/1194)
- MESOS-2161 bug killing Marathon every few hours [\#1187](https://github.com/mesosphere/marathon/issues/1187)
- Docs are not updated to 0.8.0 [\#1181](https://github.com/mesosphere/marathon/issues/1181)
- An app called `/` should not be allowed. [\#1176](https://github.com/mesosphere/marathon/issues/1176)
- POST /v2/apps is broken in master [\#1171](https://github.com/mesosphere/marathon/issues/1171)
- Application group on same host [\#1164](https://github.com/mesosphere/marathon/issues/1164)
- Marathon/Mesos does not pull docker images. [\#1161](https://github.com/mesosphere/marathon/issues/1161)
- Fix API docs for /v2/queue [\#1154](https://github.com/mesosphere/marathon/issues/1154)
- More graceful shutdown for old tasks [\#1147](https://github.com/mesosphere/marathon/issues/1147)
- Too many stale http event subscribers results in crash [\#1144](https://github.com/mesosphere/marathon/issues/1144)
- Wrong numbers in modal for apps [\#1138](https://github.com/mesosphere/marathon/issues/1138)
- Marathon is not deploying new docker image \(changed tag or name\) [\#1136](https://github.com/mesosphere/marathon/issues/1136)
- App labels example missing from REST API doc [\#1125](https://github.com/mesosphere/marathon/issues/1125)
- Question: Consul instead of Zookeeper? [\#1115](https://github.com/mesosphere/marathon/issues/1115)
- Review and update dependency versions [\#1069](https://github.com/mesosphere/marathon/issues/1069)
- Add restart app button to UI [\#1061](https://github.com/mesosphere/marathon/issues/1061)
- Port range support [\#835](https://github.com/mesosphere/marathon/issues/835)
- Get rid of the Modal/lightbox [\#810](https://github.com/mesosphere/marathon/issues/810)

**Merged pull requests:**

- Add --webui\_url parameter to be used by Mesos to link back to Marathon's UI [\#1237](https://github.com/mesosphere/marathon/pull/1237) ([sttts](https://github.com/sttts))
- fixes \#1228 - Use force parameter when restarting an app [\#1234](https://github.com/mesosphere/marathon/pull/1234) ([drexin](https://github.com/drexin))
- Update mesosphere-dnsconfig call in marathon-framework startup wrapper [\#1233](https://github.com/mesosphere/marathon/pull/1233) ([lloesche](https://github.com/lloesche))
- Update README.md [\#1232](https://github.com/mesosphere/marathon/pull/1232) ([ywahl](https://github.com/ywahl))
- Adding Human API to list of companies using Marathon [\#1230](https://github.com/mesosphere/marathon/pull/1230) ([freshmatrix](https://github.com/freshmatrix))
- fixes \#801 - Send webui\_url in FrameworkInfo [\#1227](https://github.com/mesosphere/marathon/pull/1227) ([drexin](https://github.com/drexin))
- fixes \#347 - Disable http caching by default [\#1226](https://github.com/mesosphere/marathon/pull/1226) ([drexin](https://github.com/drexin))
- Turn Timestamp into a normal case class and inherit equal and hashCode [\#1220](https://github.com/mesosphere/marathon/pull/1220) ([sttts](https://github.com/sttts))
- adding a link to go library for Marathon  [\#1219](https://github.com/mesosphere/marathon/pull/1219) ([gambol99](https://github.com/gambol99))
- Override Timestamp hashCode for consistent hashing [\#1218](https://github.com/mesosphere/marathon/pull/1218) ([sttts](https://github.com/sttts))
- add call to mesosphere-dnsconfig if installed [\#1212](https://github.com/mesosphere/marathon/pull/1212) ([lloesche](https://github.com/lloesche))
- fixes \#1210 - Return the correctly formatted JSON from /v2/queue [\#1211](https://github.com/mesosphere/marathon/pull/1211) ([drexin](https://github.com/drexin))
- fixes \#1206 - Adds new endpoint DELETE /v2/tasks to delete multiple task... [\#1208](https://github.com/mesosphere/marathon/pull/1208) ([drexin](https://github.com/drexin))
- Change link to Developing Marathon Documentation [\#1205](https://github.com/mesosphere/marathon/pull/1205) ([quamilek](https://github.com/quamilek))
- fixes \#1176 - Don't allow / as id for AppDefinition or AppUpdate, but al... [\#1203](https://github.com/mesosphere/marathon/pull/1203) ([drexin](https://github.com/drexin))
- fixes \#1195 - Fix validation logic for AppDefinition [\#1201](https://github.com/mesosphere/marathon/pull/1201) ([drexin](https://github.com/drexin))
- Add Strava to list of companies using marathon [\#1200](https://github.com/mesosphere/marathon/pull/1200) ([drewrobb](https://github.com/drewrobb))
- fixes \#1178 - Changed MarathonSchedulerActor to use a Set\[PathId\] for ap... [\#1199](https://github.com/mesosphere/marathon/pull/1199) ([drexin](https://github.com/drexin))
- Introducing the Backbone.Router and made resources linkable. [\#1197](https://github.com/mesosphere/marathon/pull/1197) ([aldipower](https://github.com/aldipower))
- Added link to Mesos-DNS documentation. [\#1192](https://github.com/mesosphere/marathon/pull/1192) ([kozyraki](https://github.com/kozyraki))
- fixes \#1186 - Improve message for an unknown version [\#1191](https://github.com/mesosphere/marathon/pull/1191) ([jsancio](https://github.com/jsancio))
- Converted the AppModal to a AppPage. [\#1190](https://github.com/mesosphere/marathon/pull/1190) ([aldipower](https://github.com/aldipower))
- fixes \#1183 - Return deployment info instead of app definition when crea... [\#1184](https://github.com/mesosphere/marathon/pull/1184) ([drexin](https://github.com/drexin))
- fixes \#1180 - Reject app with existing id on POST to /v2/apps [\#1182](https://github.com/mesosphere/marathon/pull/1182) ([drexin](https://github.com/drexin))
- Added restart app button. [\#1175](https://github.com/mesosphere/marathon/pull/1175) ([aldipower](https://github.com/aldipower))
- fixes \#1171 - removed constraint from ModelValidation.idErrors that reje... [\#1172](https://github.com/mesosphere/marathon/pull/1172) ([drexin](https://github.com/drexin))
- Actually embedding tasks again [\#1170](https://github.com/mesosphere/marathon/pull/1170) ([bobrik](https://github.com/bobrik))
- fixes \#1153 - Added endpoint to generate deployment steps from a given g... [\#1169](https://github.com/mesosphere/marathon/pull/1169) ([drexin](https://github.com/drexin))
- fixes \#1167 - Use default values in play-json Format for Group [\#1168](https://github.com/mesosphere/marathon/pull/1168) ([drexin](https://github.com/drexin))
- fixes \#1125 - Added labels to rest-api docs [\#1166](https://github.com/mesosphere/marathon/pull/1166) ([drexin](https://github.com/drexin))
- fixes \#1069 - Updated dependencies [\#1165](https://github.com/mesosphere/marathon/pull/1165) ([drexin](https://github.com/drexin))
- POST /v2/apps now results in 409 if there is a service ports conflict [\#1163](https://github.com/mesosphere/marathon/pull/1163) ([swartzrock](https://github.com/swartzrock))
- fixes \#1145 - Scale app after killing tasks without scaling [\#1160](https://github.com/mesosphere/marathon/pull/1160) ([drexin](https://github.com/drexin))
- fixes \#1157 - Include delay in /v2/queue result [\#1159](https://github.com/mesosphere/marathon/pull/1159) ([drexin](https://github.com/drexin))
- fixes \#1154 - Update docs for /v2/queue to match current output [\#1158](https://github.com/mesosphere/marathon/pull/1158) ([drexin](https://github.com/drexin))
- fixes \#1155 - In TaskQueue.list, only include tasks with count \> 0 [\#1156](https://github.com/mesosphere/marathon/pull/1156) ([drexin](https://github.com/drexin))
- Bugfix: Wrong amount of tasks on first page in paged tasks list. [\#1152](https://github.com/mesosphere/marathon/pull/1152) ([aldipower](https://github.com/aldipower))
- Ignore `MARATHON\_APP\_\*` when converting env vars to option values in start scripts. [\#1146](https://github.com/mesosphere/marathon/pull/1146) ([everpeace](https://github.com/everpeace))
- Migrate from Travis to TeamCity for publishing build artifacts [\#1142](https://github.com/mesosphere/marathon/pull/1142) ([lingmann](https://github.com/lingmann))
- Added Measurence to the list of companies that use Marathon [\#1139](https://github.com/mesosphere/marathon/pull/1139) ([cloudify](https://github.com/cloudify))
- Remove race condition where deployments start before an app is current [\#1134](https://github.com/mesosphere/marathon/pull/1134) ([sttts](https://github.com/sttts))
- fixes \#1128 - Docs now correctly mention, that HOME will only be set to ... [\#1132](https://github.com/mesosphere/marathon/pull/1132) ([drexin](https://github.com/drexin))
- don't accept empty string or / as app id [\#1113](https://github.com/mesosphere/marathon/pull/1113) ([c089](https://github.com/c089))
- Simplify and cleanup start actors [\#1060](https://github.com/mesosphere/marathon/pull/1060) ([sttts](https://github.com/sttts))

## [v0.8.0](https://github.com/mesosphere/marathon/tree/v0.8.0) (2015-02-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.0-RC2...v0.8.0)

**Implemented enhancements:**

- Last known state should be displayed when UI encounters error [\#466](https://github.com/mesosphere/marathon/issues/466)
- Simplify version numbers in the task list [\#396](https://github.com/mesosphere/marathon/issues/396)

**Fixed bugs:**

- Invalid npm build configuration introduced in 0.8.0-RC2 [\#1119](https://github.com/mesosphere/marathon/issues/1119)
- firstSuccess in health checks is incorrect [\#1082](https://github.com/mesosphere/marathon/issues/1082)
- Stop deployment moved rollback button to the next line [\#1018](https://github.com/mesosphere/marathon/issues/1018)

**Closed issues:**

- $HOME is not the same as $MESOS\_SANDBOX [\#1128](https://github.com/mesosphere/marathon/issues/1128)
- Web UI shows tasks scaled to 0 as "Running" [\#1122](https://github.com/mesosphere/marathon/issues/1122)
- npm install is broken in assets [\#1109](https://github.com/mesosphere/marathon/issues/1109)
- Clarify correct way to restart Marathon [\#1095](https://github.com/mesosphere/marathon/issues/1095)
- After scaling, old tasks are shown as "Out-of-date" [\#1025](https://github.com/mesosphere/marathon/issues/1025)
- Minor: Marathon does not update the frameworkId within MarathonSchedulerService after launch [\#793](https://github.com/mesosphere/marathon/issues/793)

**Merged pull requests:**

- Added 'suspended' status label if app has no tasks and instances. [\#1124](https://github.com/mesosphere/marathon/pull/1124) ([aldipower](https://github.com/aldipower))
- Configuration Versions "Apply these settings" button not working [\#1116](https://github.com/mesosphere/marathon/pull/1116) ([millerjam](https://github.com/millerjam))
- Fix docs link [\#1114](https://github.com/mesosphere/marathon/pull/1114) ([felixb](https://github.com/felixb))
- Fix:  npm install is broken in assets [\#1110](https://github.com/mesosphere/marathon/pull/1110) ([aldipower](https://github.com/aldipower))

## [v0.8.0-RC2](https://github.com/mesosphere/marathon/tree/v0.8.0-RC2) (2015-01-28)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.8.0-RC1...v0.8.0-RC2)

**Implemented enhancements:**

- Configurable maxLaunchDelay for apps [\#1087](https://github.com/mesosphere/marathon/issues/1087)

**Fixed bugs:**

- Health check result array \[null\] returned in embedded tasks sometimes [\#1106](https://github.com/mesosphere/marathon/issues/1106)

**Closed issues:**

- When the specified slave attribute missing, `UNLIKE` should match the offer [\#1102](https://github.com/mesosphere/marathon/issues/1102)
- Deployment stuck when replacing and scaling down [\#1100](https://github.com/mesosphere/marathon/issues/1100)
- Is there a changelog of exactly what has changed in the API for the 0.8RC1? [\#1097](https://github.com/mesosphere/marathon/issues/1097)
- marathon/examples/Docker.json formatting error [\#1091](https://github.com/mesosphere/marathon/issues/1091)
- Docs say checkpoint is default false [\#1089](https://github.com/mesosphere/marathon/issues/1089)
- make output for `backOff` human readable [\#1084](https://github.com/mesosphere/marathon/issues/1084)
- Task launch delay blows too fast [\#1083](https://github.com/mesosphere/marathon/issues/1083)
- Service Port doesn't default to ZERO [\#1073](https://github.com/mesosphere/marathon/issues/1073)
- Unknown health status, deployment stuck [\#1045](https://github.com/mesosphere/marathon/issues/1045)
- ZooKeeper timeout leaves Marathon cluster without a leader [\#1043](https://github.com/mesosphere/marathon/issues/1043)
- embed=apps.tasks on /v2/apps doesn't return tasks [\#1041](https://github.com/mesosphere/marathon/issues/1041)
- Execute One-Off Task [\#983](https://github.com/mesosphere/marathon/issues/983)
- Delete deployment button [\#876](https://github.com/mesosphere/marathon/issues/876)

**Merged pull requests:**

- Actually embedding tasks in /v2/apps?embed=apps.tasks [\#1105](https://github.com/mesosphere/marathon/pull/1105) ([bobrik](https://github.com/bobrik))
- Add attribute missing logic for Constraints [\#1103](https://github.com/mesosphere/marathon/pull/1103) ([iven](https://github.com/iven))
- Compute minHealth task number relative to new instances count [\#1101](https://github.com/mesosphere/marathon/pull/1101) ([sttts](https://github.com/sttts))
- Note about required protobuf version [\#1098](https://github.com/mesosphere/marathon/pull/1098) ([bobrik](https://github.com/bobrik))
- Configurable maxLaunchDelay for apps [\#1096](https://github.com/mesosphere/marathon/pull/1096) ([bobrik](https://github.com/bobrik))
- Fix docs for --checkpoint and --failover\_timeout. [\#1094](https://github.com/mesosphere/marathon/pull/1094) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Adding relative time in stead of version labels [\#1093](https://github.com/mesosphere/marathon/pull/1093) ([mlunoe](https://github.com/mlunoe))
- Updated Marathon JSON examples. [\#1092](https://github.com/mesosphere/marathon/pull/1092) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Catch exceptions during election correctly and offer leadership again [\#1086](https://github.com/mesosphere/marathon/pull/1086) ([sttts](https://github.com/sttts))
- fixes \#1084 - Make output for task backoff human readable [\#1085](https://github.com/mesosphere/marathon/pull/1085) ([drexin](https://github.com/drexin))
- In task launch delay log output time left, not absolute time [\#1081](https://github.com/mesosphere/marathon/pull/1081) ([sttts](https://github.com/sttts))
- Update --task\_launch\_timeout docs. [\#1080](https://github.com/mesosphere/marathon/pull/1080) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Change default for task\_launch\_timeout and document deprecation. [\#1079](https://github.com/mesosphere/marathon/pull/1079) ([guenter](https://github.com/guenter))
- Update native-docker.md [\#1076](https://github.com/mesosphere/marathon/pull/1076) ([gomes](https://github.com/gomes))

## [v0.8.0-RC1](https://github.com/mesosphere/marathon/tree/v0.8.0-RC1) (2015-01-21)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.6...v0.8.0-RC1)

**Implemented enhancements:**

- Starting Marathon on a specific Network Interface [\#882](https://github.com/mesosphere/marathon/issues/882)
- Introducing a 'stop deployment' button [\#960](https://github.com/mesosphere/marathon/pull/960) ([aldipower](https://github.com/aldipower))

**Fixed bugs:**

- Marathon uses new framework ID after failover [\#1063](https://github.com/mesosphere/marathon/issues/1063)
- Task expunge mechanism writes into ZooKeeper as non-leader [\#1039](https://github.com/mesosphere/marathon/issues/1039)
- PUT with force=yes to remove broken healthchecks did not restart task [\#1022](https://github.com/mesosphere/marathon/issues/1022)
- New frontend build systems leads to frequent failures in the build [\#1017](https://github.com/mesosphere/marathon/issues/1017)
- On group update, Marathon restarts even unchanged services [\#1007](https://github.com/mesosphere/marathon/issues/1007)
- Failed tasks are not rescheduled [\#1005](https://github.com/mesosphere/marathon/issues/1005)
- Marathon tries to match offers when not needed [\#1004](https://github.com/mesosphere/marathon/issues/1004)
- Scheduler actor is suspended again immediately after election [\#997](https://github.com/mesosphere/marathon/issues/997)
- Flaky test in MarathonSchedulerActorTest [\#946](https://github.com/mesosphere/marathon/issues/946)
- Marathon is unsure when task was started [\#918](https://github.com/mesosphere/marathon/issues/918)
- HTTP Health Checks not starting until next reconciliation period  [\#901](https://github.com/mesosphere/marathon/issues/901)
- Invalid task data [\#896](https://github.com/mesosphere/marathon/issues/896)
- Not specifying a mode for volume creates bad error message [\#895](https://github.com/mesosphere/marathon/issues/895)
- HealthCheck: COMMAND health check without port is not possible [\#891](https://github.com/mesosphere/marathon/issues/891)
- Posting a group with an absolute path does not work. [\#889](https://github.com/mesosphere/marathon/issues/889)
- Wrong default value for ports [\#888](https://github.com/mesosphere/marathon/issues/888)
- play.api.libs.json.JsResultException when submitting tasks using REST API [\#887](https://github.com/mesosphere/marathon/issues/887)
- Task reconciliation causes extra task instances [\#839](https://github.com/mesosphere/marathon/issues/839)
- Marathon picks service port causing app to never launch [\#833](https://github.com/mesosphere/marathon/issues/833)
- 0.7.5 - New Deployments Get Stuck [\#829](https://github.com/mesosphere/marathon/issues/829)
- Marathon still sending event callbacks to deleted subscribers [\#777](https://github.com/mesosphere/marathon/issues/777)
- Usage of minimumHealthCapacity hard to understand [\#689](https://github.com/mesosphere/marathon/issues/689)
- Stop health checks when no longer leader [\#356](https://github.com/mesosphere/marathon/issues/356)

**Closed issues:**

- Relax the default health check parameters. [\#1050](https://github.com/mesosphere/marathon/issues/1050)
- Lost staged tasks are never expunged [\#1047](https://github.com/mesosphere/marathon/issues/1047)
- Improve feedback when handling an "invalid" API payload \(e.g. underscores in app ID\)  [\#1023](https://github.com/mesosphere/marathon/issues/1023)
- Update Scala version to 2.11.5 [\#1010](https://github.com/mesosphere/marathon/issues/1010)
- Upgrading from 0.7.6 to 0.7.7 [\#995](https://github.com/mesosphere/marathon/issues/995)
- Marathon kills container when requests increase [\#994](https://github.com/mesosphere/marathon/issues/994)
- Health check reported failing in UI, shows passing on REST endpoint [\#992](https://github.com/mesosphere/marathon/issues/992)
- Affected apps of an deployment in the UI is empty [\#987](https://github.com/mesosphere/marathon/issues/987)
- Exponential backoff is stored locally, so backoff timers are rest after a failover [\#985](https://github.com/mesosphere/marathon/issues/985)
- Lost App Instances? [\#982](https://github.com/mesosphere/marathon/issues/982)
- API error during implicit rollback [\#977](https://github.com/mesosphere/marathon/issues/977)
- minimumHealthCapacity is broken [\#973](https://github.com/mesosphere/marathon/issues/973)
- Docker 'parameters' constrained to single value per key [\#970](https://github.com/mesosphere/marathon/issues/970)
- Health checks are broken after 0.7.5 -\> 0.7.6 upgrade [\#955](https://github.com/mesosphere/marathon/issues/955)
- MarathonSchedulerService.onDefeated not called on leader change [\#947](https://github.com/mesosphere/marathon/issues/947)
- Marathon should pull the latest image before running it [\#943](https://github.com/mesosphere/marathon/issues/943)
- Health red even when health checks are ok [\#942](https://github.com/mesosphere/marathon/issues/942)
- What advantage does mesos add on top of zookeeper [\#939](https://github.com/mesosphere/marathon/issues/939)
- How to use a Private registry [\#938](https://github.com/mesosphere/marathon/issues/938)
- Staged Docker containers sometimes show red health icon [\#934](https://github.com/mesosphere/marathon/issues/934)
- Healthchecks stay red in the UI [\#930](https://github.com/mesosphere/marathon/issues/930)
- Docker private registry with mesosphere marathon [\#926](https://github.com/mesosphere/marathon/issues/926)
- Scaling an app with 0 instances to 0 instances creates deployment which never ends [\#919](https://github.com/mesosphere/marathon/issues/919)
- Command health checks do not survive implicit reconciliation [\#917](https://github.com/mesosphere/marathon/issues/917)
- Health checks are not created for old appVersions on leader change [\#912](https://github.com/mesosphere/marathon/issues/912)
- Create job using port forwarding \(`ports` in JSON\), worked in 0.6.0 - not in 0.7.5 [\#907](https://github.com/mesosphere/marathon/issues/907)
- Health checks failures [\#903](https://github.com/mesosphere/marathon/issues/903)
- Optimize task queueing [\#902](https://github.com/mesosphere/marathon/issues/902)
- Run docker container on all mesos slaves [\#897](https://github.com/mesosphere/marathon/issues/897)
- Proper way to change mesos role? [\#892](https://github.com/mesosphere/marathon/issues/892)
- Non-leader marathon holds on to "phantom" tasks [\#885](https://github.com/mesosphere/marathon/issues/885)
- Can't get event\_subscriber to work. [\#884](https://github.com/mesosphere/marathon/issues/884)
- PUT /v2/apps/{appId} does not pull updated docker images [\#880](https://github.com/mesosphere/marathon/issues/880)
- Unable to update healthchecks [\#875](https://github.com/mesosphere/marathon/issues/875)
- env payload no longer takes integers [\#872](https://github.com/mesosphere/marathon/issues/872)
- Health Check in UI always reporting error [\#871](https://github.com/mesosphere/marathon/issues/871)
- E: Package 'mesos' has no installation candidate for Ubuntu 14.10 [\#869](https://github.com/mesosphere/marathon/issues/869)
- Prefer scaling across all nodes [\#866](https://github.com/mesosphere/marathon/issues/866)
- Remove --task\_launch\_timeout [\#733](https://github.com/mesosphere/marathon/issues/733)
- Mesos Marathon Docker parameters [\#649](https://github.com/mesosphere/marathon/issues/649)
- Add a script to build release Tarball [\#611](https://github.com/mesosphere/marathon/issues/611)

**Merged pull requests:**

- Abdicate leadership on exception during onElected [\#1065](https://github.com/mesosphere/marathon/pull/1065) ([sttts](https://github.com/sttts))
- fixes \#1063 and \#793 - Always fetch current framework ID in MarathonSche... [\#1064](https://github.com/mesosphere/marathon/pull/1064) ([drexin](https://github.com/drexin))
- Relax the default health check parameters. Fixes \#1050 [\#1059](https://github.com/mesosphere/marathon/pull/1059) ([guenter](https://github.com/guenter))
- Adds app labels \(key-value metadata\). [\#1051](https://github.com/mesosphere/marathon/pull/1051) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Allow groups with absolute paths to be POSTed. [\#1049](https://github.com/mesosphere/marathon/pull/1049) ([ConnorDoyle](https://github.com/ConnorDoyle))
- WIP: Reconcile lost staged tasks [\#1048](https://github.com/mesosphere/marathon/pull/1048) ([sttts](https://github.com/sttts))
- fixes \#1039 - Don't run periodic tasks on non-leaders [\#1040](https://github.com/mesosphere/marathon/pull/1040) ([drexin](https://github.com/drexin))
- Style corrections [\#1034](https://github.com/mesosphere/marathon/pull/1034) ([mlunoe](https://github.com/mlunoe))
- extends \#1028 - Add a test that checks, that no health checks will be st... [\#1033](https://github.com/mesosphere/marathon/pull/1033) ([drexin](https://github.com/drexin))
- Restrict TaskTracker.running only to staged tasks [\#1031](https://github.com/mesosphere/marathon/pull/1031) ([sttts](https://github.com/sttts))
- Remove obsolete function newAppPort [\#1030](https://github.com/mesosphere/marathon/pull/1030) ([sttts](https://github.com/sttts))
- Add useful life-cycle log output in TaskReplaceActor [\#1029](https://github.com/mesosphere/marathon/pull/1029) ([sttts](https://github.com/sttts))
- Don't start health checks for staged tasks [\#1028](https://github.com/mesosphere/marathon/pull/1028) ([sttts](https://github.com/sttts))
- Adding frontend tests [\#1026](https://github.com/mesosphere/marathon/pull/1026) ([mlunoe](https://github.com/mlunoe))
- changing nodce requirements [\#1021](https://github.com/mesosphere/marathon/pull/1021) ([mlunoe](https://github.com/mlunoe))
- Bump minor version =\> 0.8.0-SNAPSHOT. [\#1020](https://github.com/mesosphere/marathon/pull/1020) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Deployment button alignment corrected. [\#1019](https://github.com/mesosphere/marathon/pull/1019) ([aldipower](https://github.com/aldipower))
- fixes \#1005 - Use Deadline in RateLimiter instead of Duration to make th... [\#1016](https://github.com/mesosphere/marathon/pull/1016) ([drexin](https://github.com/drexin))
- fixes \#1007 - Don't restart apps that didn't change when updating a grou... [\#1014](https://github.com/mesosphere/marathon/pull/1014) ([drexin](https://github.com/drexin))
- fixes \#1004 - Ignore tasks with a count of 0 in the TaskQueue [\#1013](https://github.com/mesosphere/marathon/pull/1013) ([drexin](https://github.com/drexin))
- Make upgradeStrategy.maximumOverCapacity optional in proto [\#1012](https://github.com/mesosphere/marathon/pull/1012) ([sttts](https://github.com/sttts))
- fixes \#1010 - Upgrade to Scala 2.11.5 [\#1011](https://github.com/mesosphere/marathon/pull/1011) ([drexin](https://github.com/drexin))
- Restart app cleanup [\#1008](https://github.com/mesosphere/marathon/pull/1008) ([sttts](https://github.com/sttts))
- Modify representation of docker params [\#1003](https://github.com/mesosphere/marathon/pull/1003) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Readme update, added clojure client [\#1000](https://github.com/mesosphere/marathon/pull/1000) ([lorthos](https://github.com/lorthos))
- fixes \#997 - match on the extractor instead of the companion when trying... [\#998](https://github.com/mesosphere/marathon/pull/998) ([drexin](https://github.com/drexin))
- fixes \#995 - app id was not correctly extracted from task id in Marathon... [\#996](https://github.com/mesosphere/marathon/pull/996) ([drexin](https://github.com/drexin))
- Correcting reference to deployment affected apps [\#993](https://github.com/mesosphere/marathon/pull/993) ([mlunoe](https://github.com/mlunoe))
- add /usr/lib and /usr/lib64 to java.library.path [\#989](https://github.com/mesosphere/marathon/pull/989) ([lloesche](https://github.com/lloesche))
- fixes \#946 - Removed race conditions in both, the test and the MarathonS... [\#988](https://github.com/mesosphere/marathon/pull/988) ([drexin](https://github.com/drexin))
- New build system [\#986](https://github.com/mesosphere/marathon/pull/986) ([mlunoe](https://github.com/mlunoe))
- Removed remaining references to taskRateLimit in docs and ajax [\#984](https://github.com/mesosphere/marathon/pull/984) ([solarkennedy](https://github.com/solarkennedy))
- Adding automatic formatting. [\#979](https://github.com/mesosphere/marathon/pull/979) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updated AppUpdate to allow version to be posted. [\#978](https://github.com/mesosphere/marathon/pull/978) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Implement upgradeStrategy.maximumOverCapacity in the TaskReplaceActor [\#975](https://github.com/mesosphere/marathon/pull/975) ([sttts](https://github.com/sttts))
- Fix minimumHealthCapacity in TaskReplaceActor and add test case [\#972](https://github.com/mesosphere/marathon/pull/972) ([sttts](https://github.com/sttts))
- Add /v2/leader API endpoint which abdicates leadership on DELETE [\#971](https://github.com/mesosphere/marathon/pull/971) ([sttts](https://github.com/sttts))
- Fix bad link to contributing docs [\#964](https://github.com/mesosphere/marathon/pull/964) ([samccone](https://github.com/samccone))
- Reduced the initial task reconciliation delay to 15s. [\#963](https://github.com/mesosphere/marathon/pull/963) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update README.md [\#962](https://github.com/mesosphere/marathon/pull/962) ([roybos](https://github.com/roybos))
- Show last state even if connection error [\#957](https://github.com/mesosphere/marathon/pull/957) ([aldipower](https://github.com/aldipower))
- Avoid health checks and deployment recovery if a marathon instance is not leader [\#953](https://github.com/mesosphere/marathon/pull/953) ([sttts](https://github.com/sttts))
- 396 simplify version numbers [\#952](https://github.com/mesosphere/marathon/pull/952) ([aldipower](https://github.com/aldipower))
- Don't create unknown tasks with incomplete data in TaskTracker.running [\#945](https://github.com/mesosphere/marathon/pull/945) ([sttts](https://github.com/sttts))
- fixes \#902 - optimized task queueing behavior [\#936](https://github.com/mesosphere/marathon/pull/936) ([drexin](https://github.com/drexin))
- AWS Linux aware haproxy-marathon-bridge [\#933](https://github.com/mesosphere/marathon/pull/933) ([kmcgrath](https://github.com/kmcgrath))
- TaskStartActor tests, fixes and simplifications [\#932](https://github.com/mesosphere/marathon/pull/932) ([sttts](https://github.com/sttts))
- Always stop hc worker actor after sending results. [\#928](https://github.com/mesosphere/marathon/pull/928) ([ConnorDoyle](https://github.com/ConnorDoyle))
- 888 wrong ports default [\#924](https://github.com/mesosphere/marathon/pull/924) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Start health checks of all running app versions after leader change [\#922](https://github.com/mesosphere/marathon/pull/922) ([sttts](https://github.com/sttts))
- Finish RestartApp deployment step successfully if instances==0 [\#921](https://github.com/mesosphere/marathon/pull/921) ([sttts](https://github.com/sttts))
- Create health checks during ScaleApp deployment steps [\#920](https://github.com/mesosphere/marathon/pull/920) ([sttts](https://github.com/sttts))
- Add elected info attribute [\#915](https://github.com/mesosphere/marathon/pull/915) ([gphat](https://github.com/gphat))
- Fix deployment stuck when scaling apps [\#913](https://github.com/mesosphere/marathon/pull/913) ([iven](https://github.com/iven))
- Allow COMMAND health checks without ports [\#909](https://github.com/mesosphere/marathon/pull/909) ([sttts](https://github.com/sttts))
- Catch JSON parse exception on app create [\#908](https://github.com/mesosphere/marathon/pull/908) ([sttts](https://github.com/sttts))
- Added liveness to JSON health result. [\#906](https://github.com/mesosphere/marathon/pull/906) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Lower case component names \(wrap\) are no longer supported in JSX [\#904](https://github.com/mesosphere/marathon/pull/904) ([crackcomm](https://github.com/crackcomm))
- Fixed problems in haproxy-marathon-bridge script. [\#893](https://github.com/mesosphere/marathon/pull/893) ([mikljohansson](https://github.com/mikljohansson))
- Pass a timeout when 'get'ing futures from state.fetch. [\#881](https://github.com/mesosphere/marathon/pull/881) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add BrandingBrand to companies using Marathon [\#873](https://github.com/mesosphere/marathon/pull/873) ([phildougherty](https://github.com/phildougherty))
- Fix two REST API table of contents links [\#870](https://github.com/mesosphere/marathon/pull/870) ([tdooner](https://github.com/tdooner))

## [v0.7.6](https://github.com/mesosphere/marathon/tree/v0.7.6) (2014-12-06)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.5...v0.7.6)

**Implemented enhancements:**

- Add more contextual info to task environment [\#858](https://github.com/mesosphere/marathon/issues/858)
- HealthCheckManager logs too verbosely [\#840](https://github.com/mesosphere/marathon/issues/840)
- Add way to trigger an app restart via the REST API [\#838](https://github.com/mesosphere/marathon/issues/838)
- Turn on checkpointing by default [\#803](https://github.com/mesosphere/marathon/issues/803)
- AppUpdate with version and any other key should error [\#790](https://github.com/mesosphere/marathon/issues/790)
- Add support for arbitrary docker options [\#789](https://github.com/mesosphere/marathon/issues/789)
- Emit events for registration, reregistration, disconnected [\#788](https://github.com/mesosphere/marathon/issues/788)
- Update Port environment variables to allow lookup by declared port. [\#588](https://github.com/mesosphere/marathon/issues/588)
- Update Dockerfile to use Marathon package from repo [\#551](https://github.com/mesosphere/marathon/issues/551)
- Error messages should support multiple attributes [\#536](https://github.com/mesosphere/marathon/issues/536)
- running projects with procfiles [\#398](https://github.com/mesosphere/marathon/issues/398)
- Adds more context to task env variables. [\#863](https://github.com/mesosphere/marathon/pull/863) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Fixed bugs:**

- Incorrect app ID validation error message [\#849](https://github.com/mesosphere/marathon/issues/849)
- Cannot create an app with more than 250 instances [\#841](https://github.com/mesosphere/marathon/issues/841)
- Cancelled deployments are being restarted on failover [\#815](https://github.com/mesosphere/marathon/issues/815)
- Trouble posting a group with multiple apps [\#807](https://github.com/mesosphere/marathon/issues/807)
- MarathonSchedulerActorTest is flaky [\#780](https://github.com/mesosphere/marathon/issues/780)
- Deployments are too greedy [\#754](https://github.com/mesosphere/marathon/issues/754)
- Marathon deployment stuck with no tasks in the queue [\#731](https://github.com/mesosphere/marathon/issues/731)
- Orphaned Docker containers [\#673](https://github.com/mesosphere/marathon/issues/673)
- Malformed class name exceptions [\#646](https://github.com/mesosphere/marathon/issues/646)
- Destroyed apps are not immediately removed from UI [\#524](https://github.com/mesosphere/marathon/issues/524)
- Marathon doesn't prune killed tasks registered to an old FrameworkID [\#271](https://github.com/mesosphere/marathon/issues/271)
- made tasks endpoint return dates as valid date strings again [\#844](https://github.com/mesosphere/marathon/pull/844) ([drexin](https://github.com/drexin))
- Fix usage of constant. [\#842](https://github.com/mesosphere/marathon/pull/842) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Check args when deciding whether to use default zk [\#812](https://github.com/mesosphere/marathon/pull/812) ([branden](https://github.com/branden))

**Closed issues:**

- Marathon not tracking a task in Mesos [\#855](https://github.com/mesosphere/marathon/issues/855)
- Docker Container Fails with Network: Host [\#836](https://github.com/mesosphere/marathon/issues/836)
- Flaky test DeploymentActorTest.RestartApp [\#809](https://github.com/mesosphere/marathon/issues/809)
- About and docs buttons missing from header in Safari [\#805](https://github.com/mesosphere/marathon/issues/805)
- Handle new TaskState value: TASK\_ERROR [\#791](https://github.com/mesosphere/marathon/issues/791)
- If defeated as leader, Marathon eats all resource offers and prevents further work in Mesos -- along with leaking tasks [\#787](https://github.com/mesosphere/marathon/issues/787)
- Add "resources" tab to docs site. [\#785](https://github.com/mesosphere/marathon/issues/785)
- Unable to update args of an app [\#765](https://github.com/mesosphere/marathon/issues/765)
- update to scala 2.11.4 [\#764](https://github.com/mesosphere/marathon/issues/764)
- Health check runs once a minute despite app definition [\#763](https://github.com/mesosphere/marathon/issues/763)
- /v2/groups/{groupid}/version/{version} returns `null` without taking any action [\#762](https://github.com/mesosphere/marathon/issues/762)
- Add support for docker --privileged [\#748](https://github.com/mesosphere/marathon/issues/748)
- Add support for docker LXC options [\#747](https://github.com/mesosphere/marathon/issues/747)
- Add support for docker --hostname [\#746](https://github.com/mesosphere/marathon/issues/746)
- Port is lost after marathon restart [\#741](https://github.com/mesosphere/marathon/issues/741)
- Scaling Operations Sometimes Fail Silently [\#737](https://github.com/mesosphere/marathon/issues/737)
- Need to use --volumes-from flag to use share data between containers [\#719](https://github.com/mesosphere/marathon/issues/719)
- Docker containers still running even after rolling back deployment [\#716](https://github.com/mesosphere/marathon/issues/716)
- The option --resources="ports\(\*\):\[8000-9000, 31000-32000\]" [\#694](https://github.com/mesosphere/marathon/issues/694)
- Expand some variables before passing to container [\#641](https://github.com/mesosphere/marathon/issues/641)
- Allow Directory Browsing on downloads.mesosphere.io [\#582](https://github.com/mesosphere/marathon/issues/582)
- Proper Syslog Integration [\#442](https://github.com/mesosphere/marathon/issues/442)
- User error leads to orphaned tasks [\#441](https://github.com/mesosphere/marathon/issues/441)
- Limited Scalability [\#440](https://github.com/mesosphere/marathon/issues/440)
- Weird behaviour after reboot [\#204](https://github.com/mesosphere/marathon/issues/204)
- Show standard out and standard error logs in the UI [\#152](https://github.com/mesosphere/marathon/issues/152)

**Merged pull requests:**

- Updated docker doc for networking options. [\#868](https://github.com/mesosphere/marathon/pull/868) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Modify default reconciliation interval. [\#867](https://github.com/mesosphere/marathon/pull/867) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Send an additional empty list on task reconciliation to retrieve all the... [\#865](https://github.com/mesosphere/marathon/pull/865) ([drexin](https://github.com/drexin))
- Fix exception logging [\#864](https://github.com/mesosphere/marathon/pull/864) ([iven](https://github.com/iven))
- Fixed invalid PathID error message in ModelValidation. [\#862](https://github.com/mesosphere/marathon/pull/862) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Adds another test for deployment plan logic. [\#861](https://github.com/mesosphere/marathon/pull/861) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#841 - improved performance of offer to task matching, by making it lazy [\#860](https://github.com/mesosphere/marathon/pull/860) ([drexin](https://github.com/drexin))
- Add JAVA\_OPTS to run script. [\#857](https://github.com/mesosphere/marathon/pull/857) ([BenWhitehead](https://github.com/BenWhitehead))
- Complete rewrite of deployment plan calculation. [\#856](https://github.com/mesosphere/marathon/pull/856) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Make framework name configurable. Use app ID as task name. [\#850](https://github.com/mesosphere/marathon/pull/850) ([guenter](https://github.com/guenter))
- fixes \#838 - Add way to trigger an app restart via the REST API [\#845](https://github.com/mesosphere/marathon/pull/845) ([drexin](https://github.com/drexin))
- Log ignored task status in HC mgr at DEBUG. [\#843](https://github.com/mesosphere/marathon/pull/843) ([ConnorDoyle](https://github.com/ConnorDoyle))
- first steps towards play-json [\#831](https://github.com/mesosphere/marathon/pull/831) ([drexin](https://github.com/drexin))
- Revert "first steps towards play-json" [\#830](https://github.com/mesosphere/marathon/pull/830) ([drexin](https://github.com/drexin))
- Add resources tab and page w/ links to vids, tutorials. [\#827](https://github.com/mesosphere/marathon/pull/827) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#754 - added TaskReplaceActor to prevent upgrades with... [\#826](https://github.com/mesosphere/marathon/pull/826) ([drexin](https://github.com/drexin))
- Add Artirix to the list of companies using Marathon [\#822](https://github.com/mesosphere/marathon/pull/822) ([iangelov](https://github.com/iangelov))
- Made marathon store future timeout configurable. Default 2 seconds is no... [\#818](https://github.com/mesosphere/marathon/pull/818) ([maselvaraj](https://github.com/maselvaraj))
- haproxy-marathon-bridge EL7/systemd support [\#813](https://github.com/mesosphere/marathon/pull/813) ([lloesche](https://github.com/lloesche))
- fixes \#809 - Flaky test DeploymentActorTest.RestartApp [\#811](https://github.com/mesosphere/marathon/pull/811) ([drexin](https://github.com/drexin))
- fixes \#780 - MarathonSchedulerActorTest is flaky [\#806](https://github.com/mesosphere/marathon/pull/806) ([drexin](https://github.com/drexin))
- Turn on checkpointing by default. [\#804](https://github.com/mesosphere/marathon/pull/804) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix field name for rendered DeploymentActions [\#802](https://github.com/mesosphere/marathon/pull/802) ([mbabineau](https://github.com/mbabineau))
- fixes \#791 - Handle new TaskState value: TASK\_ERROR [\#799](https://github.com/mesosphere/marathon/pull/799) ([drexin](https://github.com/drexin))
- 789 arbitrary docker options [\#798](https://github.com/mesosphere/marathon/pull/798) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#762 - remove non-existent groups rollback endpoint from docs [\#797](https://github.com/mesosphere/marathon/pull/797) ([drexin](https://github.com/drexin))
- fixes \#765 - Allow to update args of an app [\#796](https://github.com/mesosphere/marathon/pull/796) ([drexin](https://github.com/drexin))
- fixes \#790 - version field in AppUpdate has to be exclusive [\#795](https://github.com/mesosphere/marathon/pull/795) ([drexin](https://github.com/drexin))
- Upgrade to mesos-utils-0.21.0-1 [\#794](https://github.com/mesosphere/marathon/pull/794) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#788 - Emit events for registration, reregistration, disconnected [\#792](https://github.com/mesosphere/marathon/pull/792) ([drexin](https://github.com/drexin))
- Add bol.com to list of companies using Marathon [\#784](https://github.com/mesosphere/marathon/pull/784) ([rhopman](https://github.com/rhopman))
- Update docs for release 0.7.5 [\#783](https://github.com/mesosphere/marathon/pull/783) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Expose ports in env as PORT\_XX. [\#774](https://github.com/mesosphere/marathon/pull/774) ([gkleiman](https://github.com/gkleiman))
- first steps towards play-json [\#771](https://github.com/mesosphere/marathon/pull/771) ([drexin](https://github.com/drexin))
- Add `hostname` support for `GROUP\_BY` constraint [\#720](https://github.com/mesosphere/marathon/pull/720) ([iven](https://github.com/iven))

## [v0.7.5](https://github.com/mesosphere/marathon/tree/v0.7.5) (2014-11-13)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.4...v0.7.5)

**Fixed bugs:**

- Container dropped in app JSON [\#779](https://github.com/mesosphere/marathon/issues/779)

**Closed issues:**

- Submitting CPU as a non-fractional number \(i.e. 1\) fails deployment silently [\#759](https://github.com/mesosphere/marathon/issues/759)
- Update service & load balancing doc to include Docker ports [\#584](https://github.com/mesosphere/marathon/issues/584)

**Merged pull requests:**

- Scaladoc fixes [\#782](https://github.com/mesosphere/marathon/pull/782) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Handle containers without port mappings. [\#781](https://github.com/mesosphere/marathon/pull/781) ([ConnorDoyle](https://github.com/ConnorDoyle))
- added compiler flags for [\#778](https://github.com/mesosphere/marathon/pull/778) ([drexin](https://github.com/drexin))
- updated scala version to 2.11.4 [\#776](https://github.com/mesosphere/marathon/pull/776) ([drexin](https://github.com/drexin))

## [v0.7.4](https://github.com/mesosphere/marathon/tree/v0.7.4) (2014-11-07)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.3...v0.7.4)

**Implemented enhancements:**

- Destroy deployment unconditionally [\#755](https://github.com/mesosphere/marathon/issues/755)
- Validate docker port protocol values [\#745](https://github.com/mesosphere/marathon/issues/745)
- Log louder when killing a task due to the task launch timeout. [\#732](https://github.com/mesosphere/marathon/issues/732)
- Health check subsystem needs a refactor [\#724](https://github.com/mesosphere/marathon/issues/724)
- Add metrics for performance of state storage implementation [\#703](https://github.com/mesosphere/marathon/issues/703)
- Improve DEBUG logging for MarathonScheduler & TaskBuilder [\#668](https://github.com/mesosphere/marathon/issues/668)
- When Mesos Command Executor check enabled, TCP and HTTP do not work anymore [\#664](https://github.com/mesosphere/marathon/issues/664)
- Support framework authentication [\#638](https://github.com/mesosphere/marathon/issues/638)
- Capture & expose task failure messages [\#482](https://github.com/mesosphere/marathon/issues/482)
- Added DELETE /v2/deployments/{id}?force=true [\#767](https://github.com/mesosphere/marathon/pull/767) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Adds hists for MarathonStore read-data-size, write-data-size. [\#707](https://github.com/mesosphere/marathon/pull/707) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Scheduler launches only current apps. [\#702](https://github.com/mesosphere/marathon/pull/702) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Latest Task Failure in App Response JSON [\#686](https://github.com/mesosphere/marathon/pull/686) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Allow user and password in Zookeeper URL [\#581](https://github.com/mesosphere/marathon/pull/581) ([iven](https://github.com/iven))

**Fixed bugs:**

- HAProxy marathon bridge not working [\#714](https://github.com/mesosphere/marathon/issues/714)
- Flaky test DeploymentActorTest.Restart [\#709](https://github.com/mesosphere/marathon/issues/709)
- Healthchecks don't work when being added to existing app [\#697](https://github.com/mesosphere/marathon/issues/697)
- My marathon crashes when I create this application [\#690](https://github.com/mesosphere/marathon/issues/690)
- Deployment steps out of sync [\#653](https://github.com/mesosphere/marathon/issues/653)
- Health Check failure on initial Docker deployment does not restart task [\#603](https://github.com/mesosphere/marathon/issues/603)
- Task health checking by app version. [\#752](https://github.com/mesosphere/marathon/pull/752) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Regognize all terminal states in StoppingBehavior [\#692](https://github.com/mesosphere/marathon/pull/692) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Closed issues:**

- Deployment never stop if `docker run` fails [\#769](https://github.com/mesosphere/marathon/issues/769)
- Lost Mesos Slave leads to Marathon Never Starting up New Tasks [\#761](https://github.com/mesosphere/marathon/issues/761)
- redis marathon docker image [\#760](https://github.com/mesosphere/marathon/issues/760)
- REST API call to stop applications is missing [\#758](https://github.com/mesosphere/marathon/issues/758)
- Marathon/Mesos stuck in staging / restart loop when deploying bridged container \(reproducable\) [\#744](https://github.com/mesosphere/marathon/issues/744)
- mesosphere/marathon:0.7.1 scales apps with full restart [\#743](https://github.com/mesosphere/marathon/issues/743)
- Clicking on an application name doesn't open the scale window [\#738](https://github.com/mesosphere/marathon/issues/738)
- Using Marathon json to create new implementations [\#718](https://github.com/mesosphere/marathon/issues/718)
- Boolean parameters at /etc/marathon/conf do not work [\#701](https://github.com/mesosphere/marathon/issues/701)
- Add task launch timeout to Docker docs [\#698](https://github.com/mesosphere/marathon/issues/698)
- Deployment with newly added health check never succeeds [\#688](https://github.com/mesosphere/marathon/issues/688)
- 0.7.3 build failing due to Scala version issue [\#684](https://github.com/mesosphere/marathon/issues/684)
- App JSON Inaccurate in REST doc [\#682](https://github.com/mesosphere/marathon/issues/682)
- Allow configuring with env variables like mesos [\#642](https://github.com/mesosphere/marathon/issues/642)
- Add contributor guidelines to wiki [\#622](https://github.com/mesosphere/marathon/issues/622)
- Make scalastyle warnings fail the build [\#606](https://github.com/mesosphere/marathon/issues/606)
- UI does not show correct state, if a new master is elected [\#554](https://github.com/mesosphere/marathon/issues/554)

**Merged pull requests:**

- Added Daemon -- companies using Marathon [\#768](https://github.com/mesosphere/marathon/pull/768) ([farukd](https://github.com/farukd))
- fixed bug in the MarathonScheduler that led to launched tasks not being ... [\#766](https://github.com/mesosphere/marathon/pull/766) ([drexin](https://github.com/drexin))
- Updated Scala version in .travis.yml [\#757](https://github.com/mesosphere/marathon/pull/757) ([ConnorDoyle](https://github.com/ConnorDoyle))
- validate protocol in port mapping [\#750](https://github.com/mesosphere/marathon/pull/750) ([drexin](https://github.com/drexin))
- Update download links to v0.7.3 [\#740](https://github.com/mesosphere/marathon/pull/740) ([stem](https://github.com/stem))
- Add support for CentOS/RHEL to haproxy-marathon-bridge [\#736](https://github.com/mesosphere/marathon/pull/736) ([potto007](https://github.com/potto007))
- Replace random service ports in docker mappings. [\#735](https://github.com/mesosphere/marathon/pull/735) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fixed error in post app json [\#728](https://github.com/mesosphere/marathon/pull/728) ([lukaswelte](https://github.com/lukaswelte))
- Refactored health check subsystem. [\#727](https://github.com/mesosphere/marathon/pull/727) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Minor refactoring for framework authentication [\#723](https://github.com/mesosphere/marathon/pull/723) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Added initial draft of contributor guidelines. [\#715](https://github.com/mesosphere/marathon/pull/715) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Formatting: allow a long line in StartingBehavior. [\#713](https://github.com/mesosphere/marathon/pull/713) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#709 - flaky test DeploymentActorTest.Restart [\#711](https://github.com/mesosphere/marathon/pull/711) ([drexin](https://github.com/drexin))
- Support Mesos Framework Authentication [\#710](https://github.com/mesosphere/marathon/pull/710) ([stem](https://github.com/stem))
- fixes \#668 - debug logging when tasks wasn't launched due to backoff [\#708](https://github.com/mesosphere/marathon/pull/708) ([drexin](https://github.com/drexin))
- Metrics for concrete subtypes of EntityRepository. [\#705](https://github.com/mesosphere/marathon/pull/705) ([ConnorDoyle](https://github.com/ConnorDoyle))
- mention --task\_launch\_timeout for Docker [\#700](https://github.com/mesosphere/marathon/pull/700) ([rasputnik](https://github.com/rasputnik))
- Enforce line length limit of 120 columns. [\#699](https://github.com/mesosphere/marathon/pull/699) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Mandatory type annotations for public methods. [\#696](https://github.com/mesosphere/marathon/pull/696) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Made test task depend on scalastyle in build [\#695](https://github.com/mesosphere/marathon/pull/695) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix docs for constraints [\#693](https://github.com/mesosphere/marathon/pull/693) ([iven](https://github.com/iven))
- Adding minimum progress step of 0 [\#691](https://github.com/mesosphere/marathon/pull/691) ([mlunoe](https://github.com/mlunoe))
- Update assembly artifact in .travis.yml [\#685](https://github.com/mesosphere/marathon/pull/685) ([ConnorDoyle](https://github.com/ConnorDoyle))
- remove duplicate params and add comma after args [\#683](https://github.com/mesosphere/marathon/pull/683) ([gregory90](https://github.com/gregory90))
- Read command line options from MARATHON\_\*. [\#475](https://github.com/mesosphere/marathon/pull/475) ([everpeace](https://github.com/everpeace))

## [v0.7.3](https://github.com/mesosphere/marathon/tree/v0.7.3) (2014-10-06)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.2...v0.7.3)

**Fixed bugs:**

- Migrate Task IDs from 0.4.0 to 0.7.1 [\#671](https://github.com/mesosphere/marathon/issues/671)

## [v0.7.2](https://github.com/mesosphere/marathon/tree/v0.7.2) (2014-10-06)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.1...v0.7.2)

**Fixed bugs:**

- Task reconciliation kills tasks in state TASK\_STARTING [\#676](https://github.com/mesosphere/marathon/issues/676)
- "Local" ports for Docker portMappings are always random [\#672](https://github.com/mesosphere/marathon/issues/672)
- Exponential backoff does not reset [\#669](https://github.com/mesosphere/marathon/issues/669)
- Scaling an app with health checks does not work properly [\#663](https://github.com/mesosphere/marathon/issues/663)
- Health check command is not interpolated and sent as raw string to mesos [\#662](https://github.com/mesosphere/marathon/issues/662)
- TCP health checks don't resolve [\#648](https://github.com/mesosphere/marathon/issues/648)
- HTTP 500 error when app.ports has fewer elements than Health Check needs [\#644](https://github.com/mesosphere/marathon/issues/644)
- mesosphere.marathon.upgrade.DeploymentActorTest.Restart app is a flakey test [\#577](https://github.com/mesosphere/marathon/issues/577)
- Update spray dependency for Scala 2.11 [\#658](https://github.com/mesosphere/marathon/pull/658) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Closed issues:**

- Health validation do not accept port index other that 0 or multiple validations for several ports [\#680](https://github.com/mesosphere/marathon/issues/680)
- Scaling docker containers [\#667](https://github.com/mesosphere/marathon/issues/667)
- Hash Sum mismatch when trying to install ubuntu package [\#661](https://github.com/mesosphere/marathon/issues/661)
- Docker container port mapping conflict? [\#647](https://github.com/mesosphere/marathon/issues/647)
- Docker Hub image [\#643](https://github.com/mesosphere/marathon/issues/643)
- Many messages sent to deadletters [\#639](https://github.com/mesosphere/marathon/issues/639)
- Execute docker image from private registry - no success [\#617](https://github.com/mesosphere/marathon/issues/617)
- Migrate to Scala 2.11 [\#612](https://github.com/mesosphere/marathon/issues/612)
- Cannot start docker job with UDP ports [\#478](https://github.com/mesosphere/marathon/issues/478)

**Merged pull requests:**

- Reduce pre-0.5 and post-0.5 taskIDs to one Regex [\#679](https://github.com/mesosphere/marathon/pull/679) ([ConnorDoyle](https://github.com/ConnorDoyle))
- TaskTracker.statusUpdate returns a Some if no err [\#678](https://github.com/mesosphere/marathon/pull/678) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add servicePort to port mapping object. [\#677](https://github.com/mesosphere/marathon/pull/677) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#669 - Reset rate limiters when app is stopped or changed [\#675](https://github.com/mesosphere/marathon/pull/675) ([drexin](https://github.com/drexin))
- fixes \#663 - Fix scaling of apps with health checks [\#666](https://github.com/mesosphere/marathon/pull/666) ([drexin](https://github.com/drexin))
- Fix $HOST env variable for command health checks [\#665](https://github.com/mesosphere/marathon/pull/665) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix broken AppDefinition health check validation [\#657](https://github.com/mesosphere/marathon/pull/657) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#648 - TCP health checks don't resolve [\#656](https://github.com/mesosphere/marathon/pull/656) ([drexin](https://github.com/drexin))
- fixes \#639 - don't send answers in MarathonSchedulerActor, when sender is noSender [\#655](https://github.com/mesosphere/marathon/pull/655) ([drexin](https://github.com/drexin))
- Fix docs for `LIKE` constraint and add `UNLIKE` constraint [\#645](https://github.com/mesosphere/marathon/pull/645) ([iven](https://github.com/iven))
- Update index of docs to include 0.7.1 [\#640](https://github.com/mesosphere/marathon/pull/640) ([ssk2](https://github.com/ssk2))
- spelling and grammar fixes to deployments.md [\#637](https://github.com/mesosphere/marathon/pull/637) ([bgentry](https://github.com/bgentry))
- Link to v0.7.1 release on docs home page [\#636](https://github.com/mesosphere/marathon/pull/636) ([ssorallen](https://github.com/ssorallen))
- Migrated to Scala 2.11 [\#613](https://github.com/mesosphere/marathon/pull/613) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix docs and add iQIYI to the company list [\#610](https://github.com/mesosphere/marathon/pull/610) ([iven](https://github.com/iven))

## [v0.7.1](https://github.com/mesosphere/marathon/tree/v0.7.1) (2014-09-26)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.0...v0.7.1)

**Implemented enhancements:**

- Support bridged networking mode for Docker containerizer [\#587](https://github.com/mesosphere/marathon/issues/587)
- Docker bridge [\#621](https://github.com/mesosphere/marathon/pull/621) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes \#479 - Recover running deployments on failover or restart [\#605](https://github.com/mesosphere/marathon/pull/605) ([drexin](https://github.com/drexin))

**Fixed bugs:**

- Chaos config missing from /v2/info [\#629](https://github.com/mesosphere/marathon/issues/629)
- Add event module config to /v2/info [\#625](https://github.com/mesosphere/marathon/issues/625)
- Remember killed tasks until receiving confirmation from Mesos [\#623](https://github.com/mesosphere/marathon/issues/623)
- Mesos and Marathon out of sync: orphaned tasks and "ghost" tasks [\#616](https://github.com/mesosphere/marathon/issues/616)

**Closed issues:**

- dockerfile/rabbitmq deploy fails - Command exited with status 1 [\#632](https://github.com/mesosphere/marathon/issues/632)
- Event module options missing from command-line docs [\#624](https://github.com/mesosphere/marathon/issues/624)
- Event bus is never activated [\#586](https://github.com/mesosphere/marathon/issues/586)

**Merged pull requests:**

- Bugfix in PortsMatcher involving iterator. [\#635](https://github.com/mesosphere/marathon/pull/635) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Dot com downloads [\#634](https://github.com/mesosphere/marathon/pull/634) ([ssorallen](https://github.com/ssorallen))
- Point to new root website, .com [\#633](https://github.com/mesosphere/marathon/pull/633) ([ssorallen](https://github.com/ssorallen))
- fixes \#629 - Added chaos config to /v2/info endpoint [\#631](https://github.com/mesosphere/marathon/pull/631) ([drexin](https://github.com/drexin))
- Docs for --event\_subscriber and --http\_endpoints [\#630](https://github.com/mesosphere/marathon/pull/630) ([ConnorDoyle](https://github.com/ConnorDoyle))
- fixes 580 - ignore TASK\_RUNNING in TaskStartActor for already known task... [\#628](https://github.com/mesosphere/marathon/pull/628) ([drexin](https://github.com/drexin))
- added event\_subscriber config to /info endpoint [\#627](https://github.com/mesosphere/marathon/pull/627) ([drexin](https://github.com/drexin))
- - don't remove tasks from task tracker before receiving TASK\_KILLED [\#626](https://github.com/mesosphere/marathon/pull/626) ([drexin](https://github.com/drexin))
- Haproxy marathon bridge multi backends [\#620](https://github.com/mesosphere/marathon/pull/620) ([lloesche](https://github.com/lloesche))
- fixes \#609 - Don't store status updates when state and health didn't cha... [\#618](https://github.com/mesosphere/marathon/pull/618) ([drexin](https://github.com/drexin))

## [v0.7.0](https://github.com/mesosphere/marathon/tree/v0.7.0) (2014-09-22)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.0-RC4...v0.7.0)

**Implemented enhancements:**

- Only write new state on status update if task state differs [\#609](https://github.com/mesosphere/marathon/issues/609)

**Merged pull requests:**

- fixes a flaky test in DeploymentActorTest.scala [\#614](https://github.com/mesosphere/marathon/pull/614) ([drexin](https://github.com/drexin))

## [v0.7.0-RC4](https://github.com/mesosphere/marathon/tree/v0.7.0-RC4) (2014-09-19)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.0-RC3...v0.7.0-RC4)

**Fixed bugs:**

- HTTP health check path should default to / [\#593](https://github.com/mesosphere/marathon/issues/593)
- Added default value for task version [\#615](https://github.com/mesosphere/marathon/pull/615) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Closed issues:**

- Marathon should include Vagrant file to run integration tests [\#585](https://github.com/mesosphere/marathon/issues/585)
- Persistent Deployments [\#479](https://github.com/mesosphere/marathon/issues/479)
- Add support for multiple user accounts [\#422](https://github.com/mesosphere/marathon/issues/422)
- Replace Guava event bus with Akka [\#289](https://github.com/mesosphere/marathon/issues/289)

**Merged pull requests:**

- Upgraded jackson-case-class-module [\#604](https://github.com/mesosphere/marathon/pull/604) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Adds scalastyle SBT plugin [\#568](https://github.com/mesosphere/marathon/pull/568) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update Dockerfile to build marathon from source [\#486](https://github.com/mesosphere/marathon/pull/486) ([crosbymichael](https://github.com/crosbymichael))

## [v0.7.0-RC3](https://github.com/mesosphere/marathon/tree/v0.7.0-RC3) (2014-09-15)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.0-RC2...v0.7.0-RC3)

**Fixed bugs:**

- Health checks not showing in UI [\#583](https://github.com/mesosphere/marathon/issues/583)

**Closed issues:**

- two step container setup \(pipework usage\) [\#528](https://github.com/mesosphere/marathon/issues/528)

**Merged pull requests:**

- Fixing a couple of json syntax errors. [\#600](https://github.com/mesosphere/marathon/pull/600) ([adamdecaf](https://github.com/adamdecaf))
- Slight tweak to GCP text to make consistent with docs [\#598](https://github.com/mesosphere/marathon/pull/598) ([ssk2](https://github.com/ssk2))
- Added health check results to embedded tasks [\#597](https://github.com/mesosphere/marathon/pull/597) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Adding a link to EMv2 [\#596](https://github.com/mesosphere/marathon/pull/596) ([florianleibert](https://github.com/florianleibert))

## [v0.7.0-RC2](https://github.com/mesosphere/marathon/tree/v0.7.0-RC2) (2014-09-12)
[Full Changelog](https://github.com/mesosphere/marathon/compare/v0.7.0-RC1...v0.7.0-RC2)

**Fixed bugs:**

- Marathon stops creating tasks for an app with outstanding resource offers [\#571](https://github.com/mesosphere/marathon/issues/571)

**Merged pull requests:**

- Fix indentation in markup so that chars are escaped correctly [\#592](https://github.com/mesosphere/marathon/pull/592) ([BenWhitehead](https://github.com/BenWhitehead))
- Revert "Deployments page" [\#591](https://github.com/mesosphere/marathon/pull/591) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update docs for docker to include increasing the executor timeout. [\#589](https://github.com/mesosphere/marathon/pull/589) ([BenWhitehead](https://github.com/BenWhitehead))
- Added brief doc on high availability [\#579](https://github.com/mesosphere/marathon/pull/579) ([ssk2](https://github.com/ssk2))
- More robust version detection in .travis.yml [\#578](https://github.com/mesosphere/marathon/pull/578) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add Disqus to companies using Marathon [\#576](https://github.com/mesosphere/marathon/pull/576) ([fuziontech](https://github.com/fuziontech))
- GroupManager: the plan should be stored after the deployment is accepted [\#575](https://github.com/mesosphere/marathon/pull/575) ([aquamatthias](https://github.com/aquamatthias))
- Deployments page [\#574](https://github.com/mesosphere/marathon/pull/574) ([mlunoe](https://github.com/mlunoe))

## [v0.7.0-RC1](https://github.com/mesosphere/marathon/tree/v0.7.0-RC1) (2014-09-10)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.6.1...v0.7.0-RC1)

**Implemented enhancements:**

- Allow Apps and Groups inside a Group [\#549](https://github.com/mesosphere/marathon/issues/549)
- Add elaborate deployment information in a `GET /v2/apps?embed=apps.deployments` endpoint [\#535](https://github.com/mesosphere/marathon/issues/535)
- Add `deployments` field to `/v2/apps` endpoint [\#516](https://github.com/mesosphere/marathon/issues/516)
- Task API should distinguish between tasks that are running and staging [\#476](https://github.com/mesosphere/marathon/issues/476)
- List any affecting deployments in app response [\#452](https://github.com/mesosphere/marathon/issues/452)
- App locked error message needs improvement [\#450](https://github.com/mesosphere/marathon/issues/450)
- Pass Non-Extractable URIs through Marathon [\#436](https://github.com/mesosphere/marathon/issues/436)
- Paginate task list in WebUI [\#419](https://github.com/mesosphere/marathon/issues/419)
- `cmd` should not default to blank string [\#377](https://github.com/mesosphere/marathon/issues/377)
- Improve task storage performance [\#358](https://github.com/mesosphere/marathon/issues/358)
- Expose AppDefinition versions in UI [\#279](https://github.com/mesosphere/marathon/issues/279)
- Add exponential back-off for task launching [\#258](https://github.com/mesosphere/marathon/issues/258)
- DELETE /v2/apps/{app\_id}/tasks?scale={true|false} behavior [\#157](https://github.com/mesosphere/marathon/issues/157)
- Add ability to group apps [\#136](https://github.com/mesosphere/marathon/issues/136)
- option to allow marathon to launch/stop tasks on slave in parallel to improve Docker integration [\#105](https://github.com/mesosphere/marathon/issues/105)
- Ignore health check failures if maxFailures == 0 [\#470](https://github.com/mesosphere/marathon/pull/470) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Fixed bugs:**

- Can't create apps from UI [\#560](https://github.com/mesosphere/marathon/issues/560)
- Can't scale an app from the UI if it's a docker container with no command [\#553](https://github.com/mesosphere/marathon/issues/553)
- Unexpected nested duplicate app in app [\#552](https://github.com/mesosphere/marathon/issues/552)
- HDFS zips no longer get extracted because not seen as extractable [\#526](https://github.com/mesosphere/marathon/issues/526)
- Posting to `/v2/groups` will destroy any apps that currently exist in that group [\#525](https://github.com/mesosphere/marathon/issues/525)
- Race condition in TaskTracker that leads to false scaling [\#520](https://github.com/mesosphere/marathon/issues/520)
- Repeated POSTS to `/v2/groups` [\#508](https://github.com/mesosphere/marathon/issues/508)
- Bad group state possible, related to namespaces  [\#506](https://github.com/mesosphere/marathon/issues/506)
- Typo in error message [\#501](https://github.com/mesosphere/marathon/issues/501)
- Can't create an app with a nested app id from the UI [\#500](https://github.com/mesosphere/marathon/issues/500)
- App creation form doesn't allow standalone executors [\#496](https://github.com/mesosphere/marathon/issues/496)
- Timeouts for /v2/deployments [\#464](https://github.com/mesosphere/marathon/issues/464)
- Remove tasks from task tracker before calling killTask [\#461](https://github.com/mesosphere/marathon/issues/461)
- Marathon returns old app config until deployments finish [\#458](https://github.com/mesosphere/marathon/issues/458)
- Marathon receives status update TASK\_FAILED but does not properly reconcile state [\#456](https://github.com/mesosphere/marathon/issues/456)
- Delete never returns 404 [\#451](https://github.com/mesosphere/marathon/issues/451)
- App not destroyable during deployment [\#449](https://github.com/mesosphere/marathon/issues/449)
- Stuck deployments after app deletion [\#447](https://github.com/mesosphere/marathon/issues/447)
- Creating an app in the UI always claims invalid ID [\#445](https://github.com/mesosphere/marathon/issues/445)
- TaskTracker is not threadsafe [\#438](https://github.com/mesosphere/marathon/issues/438)
- "env" and "disk" not updated when PUTing to an app [\#423](https://github.com/mesosphere/marathon/issues/423)
- When app is created operation returns '201 Created', but no object. [\#385](https://github.com/mesosphere/marathon/issues/385)
- Passing unsupported OPERATOR for "constraints" surfaces exception [\#317](https://github.com/mesosphere/marathon/issues/317)
- Timer already cancelled exception in zookeeper/marathon [\#309](https://github.com/mesosphere/marathon/issues/309)
- Creating a new task with `ports:null` raises NPE [\#292](https://github.com/mesosphere/marathon/issues/292)
- prevent mutable state from leaking out of TaskTracker [\#495](https://github.com/mesosphere/marathon/pull/495) ([drexin](https://github.com/drexin))
- /v2/tasks response should include health info [\#448](https://github.com/mesosphere/marathon/pull/448) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Closed issues:**

- Add health check event missing app ID [\#564](https://github.com/mesosphere/marathon/issues/564)
- WildFly JSON file stays at status 'Staged' [\#557](https://github.com/mesosphere/marathon/issues/557)
- Attempting to scale an app from the UI fails when in a group. [\#547](https://github.com/mesosphere/marathon/issues/547)
- Document replacement of `taskRateLimit` [\#530](https://github.com/mesosphere/marathon/issues/530)
- TASK\_RUNNING events  [\#529](https://github.com/mesosphere/marathon/issues/529)
- Rest API docs missing section for `/v2/groups` [\#502](https://github.com/mesosphere/marathon/issues/502)
- taskRateLimit not respected in api [\#493](https://github.com/mesosphere/marathon/issues/493)
- Marathon doesn't validate command / executor on task POST [\#483](https://github.com/mesosphere/marathon/issues/483)
- Typo in docs [\#460](https://github.com/mesosphere/marathon/issues/460)
- haproxy-marathon-bridge doesn't validate argument [\#444](https://github.com/mesosphere/marathon/issues/444)
- Incomplete task information returned by /v2/tasks [\#443](https://github.com/mesosphere/marathon/issues/443)
- Support for New Mesos ContainerInfo [\#437](https://github.com/mesosphere/marathon/issues/437)
- API Documentation Audit [\#432](https://github.com/mesosphere/marathon/issues/432)
- Health checks are executed while task is still staging [\#430](https://github.com/mesosphere/marathon/issues/430)
- Desired capacity can be decremented below zero [\#429](https://github.com/mesosphere/marathon/issues/429)
- v2/tasks and /v2/apps/{appId}/tasks parity with v1 API [\#427](https://github.com/mesosphere/marathon/issues/427)
- Docs for deployment features [\#417](https://github.com/mesosphere/marathon/issues/417)
- Marathon port allocation [\#416](https://github.com/mesosphere/marathon/issues/416)
- Marathon / HA / Zookeeper [\#412](https://github.com/mesosphere/marathon/issues/412)
- Port not being set by marathon in mesos offer [\#410](https://github.com/mesosphere/marathon/issues/410)
- Remove v1 API [\#404](https://github.com/mesosphere/marathon/issues/404)
- Move migration logic for tasks into Migration.scala class [\#401](https://github.com/mesosphere/marathon/issues/401)
- Fetch config via. REST API [\#400](https://github.com/mesosphere/marathon/issues/400)
- Having slashes in the app id's is breaking the script that generates an HAProxy.cfg. [\#387](https://github.com/mesosphere/marathon/issues/387)
- Can no longer scale apps in the UI. [\#383](https://github.com/mesosphere/marathon/issues/383)
- Unable to create app with same id as an app that has been deleted. [\#382](https://github.com/mesosphere/marathon/issues/382)
- Improve README [\#365](https://github.com/mesosphere/marathon/issues/365)
- Event JSON Needs Docs [\#162](https://github.com/mesosphere/marathon/issues/162)

**Merged pull requests:**

- Upgraded to mesos-utils 0.20.0 [\#573](https://github.com/mesosphere/marathon/pull/573) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Close modal after deleting app [\#572](https://github.com/mesosphere/marathon/pull/572) ([ssorallen](https://github.com/ssorallen))
- Fixed JSON for target groups in event-bus doc [\#570](https://github.com/mesosphere/marathon/pull/570) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Remove development doc in favor of wiki [\#569](https://github.com/mesosphere/marathon/pull/569) ([ssorallen](https://github.com/ssorallen))
- Delegate ID checking to backend, show errors in GUI [\#567](https://github.com/mesosphere/marathon/pull/567) ([ssorallen](https://github.com/ssorallen))
- Add WooRank to "Companies using Marathon" section [\#566](https://github.com/mesosphere/marathon/pull/566) ([bspaans](https://github.com/bspaans))
- Filled out missing message types in event-bus.md [\#565](https://github.com/mesosphere/marathon/pull/565) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Marathon Recipes in Docs [\#563](https://github.com/mesosphere/marathon/pull/563) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updated LB docs for haproxy\_marathon\_bridge script [\#562](https://github.com/mesosphere/marathon/pull/562) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add TaskRateLimit deprecation to migration doc [\#561](https://github.com/mesosphere/marathon/pull/561) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix \#549: Allow apps and groups  [\#559](https://github.com/mesosphere/marathon/pull/559) ([aquamatthias](https://github.com/aquamatthias))
- Fix for \#464 Timeouts for /v2/deployments [\#556](https://github.com/mesosphere/marathon/pull/556) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updated README to reduce duplication. \#432 [\#550](https://github.com/mesosphere/marathon/pull/550) ([ssk2](https://github.com/ssk2))
- Forget tasks after telling Mesos to kill them [\#546](https://github.com/mesosphere/marathon/pull/546) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add support page for Marathon site [\#545](https://github.com/mesosphere/marathon/pull/545) ([ssorallen](https://github.com/ssorallen))
- Improve Docker documentation [\#544](https://github.com/mesosphere/marathon/pull/544) ([ssorallen](https://github.com/ssorallen))
- Bug fix/update app bg [\#543](https://github.com/mesosphere/marathon/pull/543) ([mlunoe](https://github.com/mlunoe))
- Move query parameters to “Parameters” tables [\#542](https://github.com/mesosphere/marathon/pull/542) ([ssorallen](https://github.com/ssorallen))
- Do not allow POST requests for groups, that are already created. [\#541](https://github.com/mesosphere/marathon/pull/541) ([aquamatthias](https://github.com/aquamatthias))
- DON'T MERGE BEFORE PR 518: Deployments ui [\#540](https://github.com/mesosphere/marathon/pull/540) ([mlunoe](https://github.com/mlunoe))
- Centralize keyboard handling to Marathon.jsx [\#538](https://github.com/mesosphere/marathon/pull/538) ([ssorallen](https://github.com/ssorallen))
- Render modal in React based off state [\#537](https://github.com/mesosphere/marathon/pull/537) ([ssorallen](https://github.com/ssorallen))
- Deployments ui [\#534](https://github.com/mesosphere/marathon/pull/534) ([mlunoe](https://github.com/mlunoe))
- Validate executor pattern [\#533](https://github.com/mesosphere/marathon/pull/533) ([ssorallen](https://github.com/ssorallen))
- Documentation for application groups and deployments \#432 [\#532](https://github.com/mesosphere/marathon/pull/532) ([aquamatthias](https://github.com/aquamatthias))
- Added related deployments to GET /v2/apps [\#531](https://github.com/mesosphere/marathon/pull/531) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Extraction for zip-s [\#527](https://github.com/mesosphere/marathon/pull/527) ([sumkincpp](https://github.com/sumkincpp))
- Remove incorrect `cmd` validation from frontend [\#523](https://github.com/mesosphere/marathon/pull/523) ([ssorallen](https://github.com/ssorallen))
- fixes \#476 [\#522](https://github.com/mesosphere/marathon/pull/522) ([drexin](https://github.com/drexin))
- fixes \#520 - fixed two races in TaskTracker [\#521](https://github.com/mesosphere/marathon/pull/521) ([drexin](https://github.com/drexin))
- Updated REST doc for GET /v2/apps/{appId} [\#519](https://github.com/mesosphere/marathon/pull/519) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add v0.7.0 label to groups resource and fix link for PUT [\#515](https://github.com/mesosphere/marathon/pull/515) ([BenWhitehead](https://github.com/BenWhitehead))
- added 'currentStep' and 'totalSteps' to deployments api to be able to sh... [\#514](https://github.com/mesosphere/marathon/pull/514) ([drexin](https://github.com/drexin))
- Changed 'not settable' to 'read-only' [\#513](https://github.com/mesosphere/marathon/pull/513) ([ConnorDoyle](https://github.com/ConnorDoyle))
- removed /v2/apps/{id}?embed=app.tasks from api docs and added deployment... [\#512](https://github.com/mesosphere/marathon/pull/512) ([drexin](https://github.com/drexin))
- Fix 508 [\#511](https://github.com/mesosphere/marathon/pull/511) ([aquamatthias](https://github.com/aquamatthias))
- fixes \#506 - don't store invalid group [\#510](https://github.com/mesosphere/marathon/pull/510) ([drexin](https://github.com/drexin))
- Added REST docs for groups [\#509](https://github.com/mesosphere/marathon/pull/509) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Added app deployments to REST docs [\#507](https://github.com/mesosphere/marathon/pull/507) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Group and app names in groups validation error. [\#505](https://github.com/mesosphere/marathon/pull/505) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix missing comma [\#504](https://github.com/mesosphere/marathon/pull/504) ([BenWhitehead](https://github.com/BenWhitehead))
- Updated groups error message for readability [\#503](https://github.com/mesosphere/marathon/pull/503) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update docs with mesos compatibility. [\#499](https://github.com/mesosphere/marathon/pull/499) ([BenWhitehead](https://github.com/BenWhitehead))
- Create doc for upgrading from 0.6.x to 0.7.0 [\#498](https://github.com/mesosphere/marathon/pull/498) ([BenWhitehead](https://github.com/BenWhitehead))
- Minor enhancements to Docker doc. [\#497](https://github.com/mesosphere/marathon/pull/497) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fixed a couple typos in the Docker doc [\#494](https://github.com/mesosphere/marathon/pull/494) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Added a doc for how to run Docker w/ Mesos 0.20 [\#492](https://github.com/mesosphere/marathon/pull/492) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Print usage and exit if no args provided to bridge [\#491](https://github.com/mesosphere/marathon/pull/491) ([ssorallen](https://github.com/ssorallen))
- Add Sailthru to the "Companies Using Marathon" list! [\#490](https://github.com/mesosphere/marathon/pull/490) ([adgaudio](https://github.com/adgaudio))
- Add v0.7.0 label to new API endpoints [\#489](https://github.com/mesosphere/marathon/pull/489) ([ssorallen](https://github.com/ssorallen))
- added 'currentActions' to deployments api [\#488](https://github.com/mesosphere/marathon/pull/488) ([drexin](https://github.com/drexin))
- Rest doc updates [\#487](https://github.com/mesosphere/marathon/pull/487) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updated command for custom executors [\#485](https://github.com/mesosphere/marathon/pull/485) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add doc about enabling SSL and basic auth [\#484](https://github.com/mesosphere/marathon/pull/484) ([ssorallen](https://github.com/ssorallen))
- Update docs to show /v2/info endpoint [\#481](https://github.com/mesosphere/marathon/pull/481) ([BenWhitehead](https://github.com/BenWhitehead))
- Paged tasks [\#472](https://github.com/mesosphere/marathon/pull/472) ([mlunoe](https://github.com/mlunoe))
- Move docs to /docs and use Jekyll for GH Pages [\#471](https://github.com/mesosphere/marathon/pull/471) ([ssorallen](https://github.com/ssorallen))
- added ConcurrentSet and use it in TaskTracker [\#469](https://github.com/mesosphere/marathon/pull/469) ([drexin](https://github.com/drexin))
- Update download URL to the 0.6.1 release [\#468](https://github.com/mesosphere/marathon/pull/468) ([rthomas](https://github.com/rthomas))
- Complete docs for command line flags [\#467](https://github.com/mesosphere/marathon/pull/467) ([ssorallen](https://github.com/ssorallen))
- Adding description to develop Marathon with [\#465](https://github.com/mesosphere/marathon/pull/465) ([mlunoe](https://github.com/mlunoe))
- Issue 458 -- Store groups & apps before executing updates [\#459](https://github.com/mesosphere/marathon/pull/459) ([olix0r](https://github.com/olix0r))
- GET /v2/apps/some/app now lists active deployments [\#457](https://github.com/mesosphere/marathon/pull/457) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Enhancement 436 [\#455](https://github.com/mesosphere/marathon/pull/455) ([elingg](https://github.com/elingg))
- DELETE on a nonexistent app should return 404 [\#454](https://github.com/mesosphere/marathon/pull/454) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add deployment ids to app locked error message [\#453](https://github.com/mesosphere/marathon/pull/453) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Allow leading slash in app names in UI [\#446](https://github.com/mesosphere/marathon/pull/446) ([ssorallen](https://github.com/ssorallen))
- Consistency with upcoming docker support in Mesos [\#439](https://github.com/mesosphere/marathon/pull/439) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add node client [\#435](https://github.com/mesosphere/marathon/pull/435) ([silas](https://github.com/silas))
- Removed the v1 REST API [\#434](https://github.com/mesosphere/marathon/pull/434) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Re-throw enum exception as JsonParseException to yield a proper error [\#433](https://github.com/mesosphere/marathon/pull/433) ([guenter](https://github.com/guenter))
- Ignore failed health checks while task is staging. [\#431](https://github.com/mesosphere/marathon/pull/431) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Changed /v2/apps endpoint to add embed option for \#427 [\#428](https://github.com/mesosphere/marathon/pull/428) ([andreasst](https://github.com/andreasst))
- Wip artifact store [\#426](https://github.com/mesosphere/marathon/pull/426) ([drexin](https://github.com/drexin))
- Issue 423 app update completeness 0.7.0 preview [\#425](https://github.com/mesosphere/marathon/pull/425) ([ConnorDoyle](https://github.com/ConnorDoyle))
- App update completeness [\#424](https://github.com/mesosphere/marathon/pull/424) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix small subtle bug in GROUP\_BY constraint. [\#421](https://github.com/mesosphere/marathon/pull/421) ([brndnmtthws](https://github.com/brndnmtthws))
- Add go client [\#415](https://github.com/mesosphere/marathon/pull/415) ([jbdalido](https://github.com/jbdalido))
- Add The Factory to list of Marathon users [\#414](https://github.com/mesosphere/marathon/pull/414) ([mbabineau](https://github.com/mbabineau))
- Fix examples id [\#409](https://github.com/mesosphere/marathon/pull/409) ([chengweiv5](https://github.com/chengweiv5))
- 0.7.0 preview [\#408](https://github.com/mesosphere/marathon/pull/408) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Prefer to use app ports if available in an offer [\#384](https://github.com/mesosphere/marathon/pull/384) ([guenter](https://github.com/guenter))

## [marathon-0.6.1](https://github.com/mesosphere/marathon/tree/marathon-0.6.1) (2014-07-18)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.6.0...marathon-0.6.1)

**Implemented enhancements:**

- Allow Marathon users to specify what user to run tasks as [\#395](https://github.com/mesosphere/marathon/issues/395)
- Should be an easy way to query the current Marathon version [\#394](https://github.com/mesosphere/marathon/issues/394)
- Executor-performed health checks [\#359](https://github.com/mesosphere/marathon/issues/359)

**Fixed bugs:**

- Docker image field is lost if `options` field is not set [\#397](https://github.com/mesosphere/marathon/issues/397)
- Mis-aligned fields in UI [\#366](https://github.com/mesosphere/marathon/issues/366)
- Creating app with duplicate ID in UI doesn't give feedback [\#324](https://github.com/mesosphere/marathon/issues/324)
- Give up at some point if an app fails to start repeatedly [\#20](https://github.com/mesosphere/marathon/issues/20)

**Closed issues:**

- Let App model own the AppVersion collection [\#405](https://github.com/mesosphere/marathon/issues/405)
- question: Is kubernetes-mesos supposed to eventually replace marathon? [\#389](https://github.com/mesosphere/marathon/issues/389)

**Merged pull requests:**

- Reintroduce functional syntax in MarathonScheduler [\#407](https://github.com/mesosphere/marathon/pull/407) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix issue \#400 [\#406](https://github.com/mesosphere/marathon/pull/406) ([yemyat89](https://github.com/yemyat89))
- deployment features [\#403](https://github.com/mesosphere/marathon/pull/403) ([drexin](https://github.com/drexin))
- making the startup port for tomcat dynamic [\#399](https://github.com/mesosphere/marathon/pull/399) ([kensipe](https://github.com/kensipe))
- Naming: launchDelay =\> backoff [\#391](https://github.com/mesosphere/marathon/pull/391) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updated README to reference correct environmental variable. [\#390](https://github.com/mesosphere/marathon/pull/390) ([ssk2](https://github.com/ssk2))
- Exponential Task Launch Back-off \(per-app\) [\#386](https://github.com/mesosphere/marathon/pull/386) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Update README.md [\#381](https://github.com/mesosphere/marathon/pull/381) ([D-Roch](https://github.com/D-Roch))
- Fix bugs in startup script [\#379](https://github.com/mesosphere/marathon/pull/379) ([activars](https://github.com/activars))
- Enable CI notifications for Mesosphere’s Slack [\#376](https://github.com/mesosphere/marathon/pull/376) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Render “Staged” in task list with yellow health badge [\#374](https://github.com/mesosphere/marathon/pull/374) ([ssorallen](https://github.com/ssorallen))
- Print non-breaking space to prevent `\<dd\>` collapse [\#372](https://github.com/mesosphere/marathon/pull/372) ([ssorallen](https://github.com/ssorallen))
- id's can't have underscores [\#371](https://github.com/mesosphere/marathon/pull/371) ([jplock](https://github.com/jplock))
- id's can't have underscores [\#370](https://github.com/mesosphere/marathon/pull/370) ([jplock](https://github.com/jplock))
- exec java for interop with supervisors [\#369](https://github.com/mesosphere/marathon/pull/369) ([cbuben](https://github.com/cbuben))
- Cleanup to clear five compiler warnings. [\#363](https://github.com/mesosphere/marathon/pull/363) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Bug/duplicate [\#361](https://github.com/mesosphere/marathon/pull/361) ([mlunoe](https://github.com/mlunoe))
- App versions [\#350](https://github.com/mesosphere/marathon/pull/350) ([mlunoe](https://github.com/mlunoe))

## [marathon-0.6.0](https://github.com/mesosphere/marathon/tree/marathon-0.6.0) (2014-06-26)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.5.1_mesos-0.16.0...marathon-0.6.0)

**Implemented enhancements:**

- Exit with a meaningful error if mesos library can not be loaded [\#313](https://github.com/mesosphere/marathon/issues/313)
- Replace timestamp in Task ID with a time-based UUID [\#312](https://github.com/mesosphere/marathon/issues/312)
- Expose task health checks in UI [\#299](https://github.com/mesosphere/marathon/issues/299)
- Handle disk resources [\#12](https://github.com/mesosphere/marathon/issues/12)
- Allow `container` without `executor` in UI [\#360](https://github.com/mesosphere/marathon/pull/360) ([ssorallen](https://github.com/ssorallen))
- Changes to front and back end to handle disk resources \(as per \#12\). [\#348](https://github.com/mesosphere/marathon/pull/348) ([ssk2](https://github.com/ssk2))

**Fixed bugs:**

- Marathon doesn't work with Mesos 0.19.0 [\#354](https://github.com/mesosphere/marathon/issues/354)
- Task counts not aligned [\#342](https://github.com/mesosphere/marathon/issues/342)

**Closed issues:**

- MESOS\_NATIVE\_LIBRARY -\> MESOS\_NATIVE\_JAVA\_LIBRARY [\#352](https://github.com/mesosphere/marathon/issues/352)
- Empty JSON response for POST /v2/apps considered invalid [\#349](https://github.com/mesosphere/marathon/issues/349)
- Download URL in readme returning 403: Forbidden [\#337](https://github.com/mesosphere/marathon/issues/337)
- Health Checks in REST Documentation [\#305](https://github.com/mesosphere/marathon/issues/305)

**Merged pull requests:**

- Stop task health checks when no longer leader [\#357](https://github.com/mesosphere/marathon/pull/357) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Updated MESOS\_NATIVE\_LIBRARY to MESOS\_NATIVE\_JAVA\_LIBRARY for \#352 [\#355](https://github.com/mesosphere/marathon/pull/355) ([ssk2](https://github.com/ssk2))
- Remove `Content-Length` header for valid JSON response [\#351](https://github.com/mesosphere/marathon/pull/351) ([ssorallen](https://github.com/ssorallen))
- Move control of AppModal to root for routing [\#346](https://github.com/mesosphere/marathon/pull/346) ([ssorallen](https://github.com/ssorallen))
- Align instance counts [\#343](https://github.com/mesosphere/marathon/pull/343) ([ssorallen](https://github.com/ssorallen))
- Document the health checks API options [\#341](https://github.com/mesosphere/marathon/pull/341) ([ssorallen](https://github.com/ssorallen))
- Style Nuke [\#340](https://github.com/mesosphere/marathon/pull/340) ([ssorallen](https://github.com/ssorallen))
- bug fix: sort health checks [\#339](https://github.com/mesosphere/marathon/pull/339) ([mlunoe](https://github.com/mlunoe))
- Fix for commit \#c4a054c [\#338](https://github.com/mesosphere/marathon/pull/338) ([mlunoe](https://github.com/mlunoe))
- Feature/re skin [\#336](https://github.com/mesosphere/marathon/pull/336) ([mlunoe](https://github.com/mlunoe))
- added migration from 0.\* to 0.6 [\#334](https://github.com/mesosphere/marathon/pull/334) ([drexin](https://github.com/drexin))
- Replace timestamp in Task ID with a time-based UUID. Fixes \#312 [\#332](https://github.com/mesosphere/marathon/pull/332) ([guenter](https://github.com/guenter))
- Allow arbitrary JVM options to be passed to marathon [\#331](https://github.com/mesosphere/marathon/pull/331) ([hgschmie](https://github.com/hgschmie))
- Feature: Health checks [\#327](https://github.com/mesosphere/marathon/pull/327) ([mlunoe](https://github.com/mlunoe))

## [marathon-0.5.1_mesos-0.16.0](https://github.com/mesosphere/marathon/tree/marathon-0.5.1_mesos-0.16.0) (2014-06-05)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.5.1...marathon-0.5.1_mesos-0.16.0)

## [marathon-0.5.1](https://github.com/mesosphere/marathon/tree/marathon-0.5.1) (2014-06-05)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.5.0_mesos-0.16.0...marathon-0.5.1)

**Implemented enhancements:**

- UI Validation for LDH app names [\#315](https://github.com/mesosphere/marathon/issues/315)
- UI doesn't notify on connection problems [\#303](https://github.com/mesosphere/marathon/issues/303)
- Force app list refresh on modal close [\#287](https://github.com/mesosphere/marathon/issues/287)
- Compatibility with Mesos 0.16.x and below [\#240](https://github.com/mesosphere/marathon/issues/240)
- Make table columns sortable asc or desc [\#89](https://github.com/mesosphere/marathon/issues/89)
- Enforce LDH conventions for app names. [\#310](https://github.com/mesosphere/marathon/pull/310) ([solidsnack](https://github.com/solidsnack))

**Fixed bugs:**

- Allow container options with the default executor [\#307](https://github.com/mesosphere/marathon/issues/307)
- Loading state incorrectly says, "No running apps" [\#278](https://github.com/mesosphere/marathon/issues/278)
- New app doesn't immediately display in app list [\#277](https://github.com/mesosphere/marathon/issues/277)

**Closed issues:**

- Document new LDH \(Domain\) App name constraints [\#314](https://github.com/mesosphere/marathon/issues/314)

**Merged pull requests:**

- Replace global ExecutionContext by a cached thread pool context [\#328](https://github.com/mesosphere/marathon/pull/328) ([aquamatthias](https://github.com/aquamatthias))
- Mousetrap key bindings [\#326](https://github.com/mesosphere/marathon/pull/326) ([ssorallen](https://github.com/ssorallen))
- Locale timestamps [\#323](https://github.com/mesosphere/marathon/pull/323) ([ssorallen](https://github.com/ssorallen))
- Allow assets to be built from any directory. [\#321](https://github.com/mesosphere/marathon/pull/321) ([solidsnack](https://github.com/solidsnack))
- Compile only JSX assets [\#320](https://github.com/mesosphere/marathon/pull/320) ([ssorallen](https://github.com/ssorallen))
- Enforce valid hostnames \(minus uppercase\) for app IDs [\#319](https://github.com/mesosphere/marathon/pull/319) ([ssorallen](https://github.com/ssorallen))
- Document app ID requirements in REST.md [\#318](https://github.com/mesosphere/marathon/pull/318) ([ssorallen](https://github.com/ssorallen))
- Linkify hostname/port combos in task list [\#316](https://github.com/mesosphere/marathon/pull/316) ([ssorallen](https://github.com/ssorallen))
- UI refactorings [\#311](https://github.com/mesosphere/marathon/pull/311) ([ssorallen](https://github.com/ssorallen))
- Fixes \#307 Container opts with default executor. [\#308](https://github.com/mesosphere/marathon/pull/308) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Feature: Sortable columns [\#304](https://github.com/mesosphere/marathon/pull/304) ([mlunoe](https://github.com/mlunoe))
- Let ancestors access modal to prevent exception [\#301](https://github.com/mesosphere/marathon/pull/301) ([ssorallen](https://github.com/ssorallen))
- Please review [\#300](https://github.com/mesosphere/marathon/pull/300) ([mlunoe](https://github.com/mlunoe))
- Show “Loading apps…” until first app poll [\#298](https://github.com/mesosphere/marathon/pull/298) ([ssorallen](https://github.com/ssorallen))
- use sbt instead of maven [\#269](https://github.com/mesosphere/marathon/pull/269) ([drexin](https://github.com/drexin))

## [marathon-0.5.0_mesos-0.16.0](https://github.com/mesosphere/marathon/tree/marathon-0.5.0_mesos-0.16.0) (2014-05-21)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.5.0...marathon-0.5.0_mesos-0.16.0)

## [marathon-0.5.0](https://github.com/mesosphere/marathon/tree/marathon-0.5.0) (2014-05-21)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.4.1...marathon-0.5.0)

**Implemented enhancements:**

- Visible task list should auto-update [\#275](https://github.com/mesosphere/marathon/issues/275)
- Kill tasks that fail too many health checks [\#252](https://github.com/mesosphere/marathon/issues/252)
- Allow relative paths to executor [\#208](https://github.com/mesosphere/marathon/issues/208)
- Consider PATCH support for updating App instances [\#203](https://github.com/mesosphere/marathon/issues/203)
- No upgrade path from older revision [\#182](https://github.com/mesosphere/marathon/issues/182)
- Add health check for apps [\#174](https://github.com/mesosphere/marathon/issues/174)
- Document packaged versions [\#171](https://github.com/mesosphere/marathon/issues/171)
- Implement placement constraint for placing tasks on a particular machine [\#98](https://github.com/mesosphere/marathon/issues/98)
- Simplify health checks: get rid of response code list [\#260](https://github.com/mesosphere/marathon/pull/260) ([guenter](https://github.com/guenter))
- \#14 Optimize task scheduling [\#231](https://github.com/mesosphere/marathon/pull/231) ([drexin](https://github.com/drexin))
- HTTP and TCP Per-Task Health Checks [\#206](https://github.com/mesosphere/marathon/pull/206) ([ConnorDoyle](https://github.com/ConnorDoyle))

**Fixed bugs:**

- /v2/apps/{appId}/tasks throws exceptions [\#234](https://github.com/mesosphere/marathon/issues/234)
- Updating an app's constraints results in `500` [\#230](https://github.com/mesosphere/marathon/issues/230)
- Slave HTTP proxy discards response bodies upon 400 [\#226](https://github.com/mesosphere/marathon/issues/226)
- Tasks endpoints in text/plain should return hosts when no ports are allocated [\#222](https://github.com/mesosphere/marathon/issues/222)
- Updating an app causes container to be lost [\#221](https://github.com/mesosphere/marathon/issues/221)
- MarathonSchedulerService cannot be shutdown when Zookeeper dies. [\#212](https://github.com/mesosphere/marathon/issues/212)
- Requesting /v2/apps/NON\_EXISTENT\_ID/tasks, Accept: text/plain yields 500 [\#211](https://github.com/mesosphere/marathon/issues/211)
- Unsupported accept encoding causes 500 responses [\#210](https://github.com/mesosphere/marathon/issues/210)
- /v1/apps/scale broken in master [\#205](https://github.com/mesosphere/marathon/issues/205)
- Apps can't be scaled from the UI [\#198](https://github.com/mesosphere/marathon/issues/198)
- Validation does not respect multiple ports [\#195](https://github.com/mesosphere/marathon/issues/195)
- No upgrade path from older revision [\#182](https://github.com/mesosphere/marathon/issues/182)
- Zookeeper connection errors prevent reaching a good state [\#180](https://github.com/mesosphere/marathon/issues/180)
- rest api v2 app update ignores uri [\#170](https://github.com/mesosphere/marathon/issues/170)
- Never connects if started when ZooKeeper is dead [\#146](https://github.com/mesosphere/marathon/issues/146)
- Zombie mesos state for non-existing docker image [\#117](https://github.com/mesosphere/marathon/issues/117)
- Process doesn't exit if port is already in use [\#114](https://github.com/mesosphere/marathon/issues/114)
- "/v1/apps/scale" always returns 204 even in failure or bad request [\#109](https://github.com/mesosphere/marathon/issues/109)
- StorageException when killing two tasks in succession [\#108](https://github.com/mesosphere/marathon/issues/108)
- "v1/tasks/kill" returns 200 even in failure [\#107](https://github.com/mesosphere/marathon/issues/107)
- Marathon process stays alive, doesn't respond to signals, after suicide [\#90](https://github.com/mesosphere/marathon/issues/90)

**Closed issues:**

- Scaling from a non-leader node fails in HA mode [\#296](https://github.com/mesosphere/marathon/issues/296)
- bin/marathon-framework sets deprecated --zk\_hosts option [\#273](https://github.com/mesosphere/marathon/issues/273)
- Show number of running vs. provisioned instances in the UI [\#263](https://github.com/mesosphere/marathon/issues/263)
- Suspending when instances are still spawned misbehaves [\#254](https://github.com/mesosphere/marathon/issues/254)
- Status code for REST API "Create App" inconsistent with docs [\#232](https://github.com/mesosphere/marathon/issues/232)
- Getting framework messages from the scheduler [\#228](https://github.com/mesosphere/marathon/issues/228)
- Executor URI field should allow relative paths [\#209](https://github.com/mesosphere/marathon/issues/209)
- Tasks don't have version information [\#200](https://github.com/mesosphere/marathon/issues/200)
- Can't create new apps  [\#199](https://github.com/mesosphere/marathon/issues/199)
- Apps can't be deleted [\#194](https://github.com/mesosphere/marathon/issues/194)
- add env input to task creation UI [\#190](https://github.com/mesosphere/marathon/issues/190)
- Please document the GROUP\_BY constraint [\#189](https://github.com/mesosphere/marathon/issues/189)
- zookeeper config format different than mesos. necessary? [\#185](https://github.com/mesosphere/marathon/issues/185)
- Requested app ports should be validated for uniqueness [\#183](https://github.com/mesosphere/marathon/issues/183)
- NullPointerException when starting apps [\#181](https://github.com/mesosphere/marathon/issues/181)
- 404 error status code should not let Jetty return HTML error page [\#176](https://github.com/mesosphere/marathon/issues/176)
- Remove Content-Type from 204 responses [\#165](https://github.com/mesosphere/marathon/issues/165)
- Available resources and some mesos links in Marathon Web UI [\#151](https://github.com/mesosphere/marathon/issues/151)
- Marathon/Docker scaling up/down issue  [\#102](https://github.com/mesosphere/marathon/issues/102)

**Merged pull requests:**

- Use grace period instead of initial delay [\#293](https://github.com/mesosphere/marathon/pull/293) ([guenter](https://github.com/guenter))
- Add support for max consecutive health check failures [\#291](https://github.com/mesosphere/marathon/pull/291) ([guenter](https://github.com/guenter))
- Followup to \#272 [\#288](https://github.com/mesosphere/marathon/pull/288) ([guenter](https://github.com/guenter))
- Show running tasks in app list [\#284](https://github.com/mesosphere/marathon/pull/284) ([burke](https://github.com/burke))
- Auto-update TaskListComponent [\#283](https://github.com/mesosphere/marathon/pull/283) ([burke](https://github.com/burke))
- UI full width + hover [\#281](https://github.com/mesosphere/marathon/pull/281) ([ssorallen](https://github.com/ssorallen))
- use --zk instead of --zk\_hosts [\#274](https://github.com/mesosphere/marathon/pull/274) ([asher](https://github.com/asher))
- Added abdication of leadership on disconnect from the Mesos master \(plus other leadership defeats/elections rework\) [\#272](https://github.com/mesosphere/marathon/pull/272) ([marc-barry](https://github.com/marc-barry))
- \#NO\_ISSUE some refactorings [\#270](https://github.com/mesosphere/marathon/pull/270) ([drexin](https://github.com/drexin))
- Switch to scalatest [\#268](https://github.com/mesosphere/marathon/pull/268) ([guenter](https://github.com/guenter))
- Purge the queue when scaling down apps. Fixes \#254 [\#267](https://github.com/mesosphere/marathon/pull/267) ([guenter](https://github.com/guenter))
- Fixes \#146 - Zookeeper connection errors on start [\#265](https://github.com/mesosphere/marathon/pull/265) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add an endpoint to allow inspection of the task queue [\#264](https://github.com/mesosphere/marathon/pull/264) ([guenter](https://github.com/guenter))
- Added a timestamp property to the MarathonEvent object [\#262](https://github.com/mesosphere/marathon/pull/262) ([marc-barry](https://github.com/marc-barry))
- Asynchronously call sys.exit\(\) to avoid deadlock due to the JVM shutdown hooks [\#261](https://github.com/mesosphere/marathon/pull/261) ([marc-barry](https://github.com/marc-barry))
- \#108 Fix concurrent updates [\#259](https://github.com/mesosphere/marathon/pull/259) ([drexin](https://github.com/drexin))
- Add marathon-client.py to the list of clients [\#256](https://github.com/mesosphere/marathon/pull/256) ([MiLk](https://github.com/MiLk))
- \#NO\_ISSUE Constraints refactoring [\#253](https://github.com/mesosphere/marathon/pull/253) ([drexin](https://github.com/drexin))
- Use PATCH when updating \# of instances [\#251](https://github.com/mesosphere/marathon/pull/251) ([ssorallen](https://github.com/ssorallen))
- Upgrade to React 0.10.0 [\#250](https://github.com/mesosphere/marathon/pull/250) ([ssorallen](https://github.com/ssorallen))
- Ports in new app form [\#249](https://github.com/mesosphere/marathon/pull/249) ([ssorallen](https://github.com/ssorallen))
- Proposal: Change the MesosStatusUpdateEvent taskStatus parameter to a String [\#248](https://github.com/mesosphere/marathon/pull/248) ([marc-barry](https://github.com/marc-barry))
- \#212 Added workaround for shutdown problem [\#247](https://github.com/mesosphere/marathon/pull/247) ([drexin](https://github.com/drexin))
- Renamed some of the MarathonEvent case class parameters \(\*ID -\> \*Id\) [\#246](https://github.com/mesosphere/marathon/pull/246) ([marc-barry](https://github.com/marc-barry))
- Added the slave ID to MesosStatusUpdateEvent. [\#245](https://github.com/mesosphere/marathon/pull/245) ([marc-barry](https://github.com/marc-barry))
- Add marathon-python to list of clients [\#243](https://github.com/mesosphere/marathon/pull/243) ([mbabineau](https://github.com/mbabineau))
- \#206 Publish health check events to event bus [\#242](https://github.com/mesosphere/marathon/pull/242) ([drexin](https://github.com/drexin))
- Using foreach instead of map when dealing with an Option\[EventBus\]. Made... [\#241](https://github.com/mesosphere/marathon/pull/241) ([marc-barry](https://github.com/marc-barry))
- proto: make mandatory field ServiceDefinition.version optional with defa... [\#238](https://github.com/mesosphere/marathon/pull/238) ([aquamatthias](https://github.com/aquamatthias))
- Added more tests [\#237](https://github.com/mesosphere/marathon/pull/237) ([drexin](https://github.com/drexin))
- \#234 Fix unsafe generation of task listing [\#236](https://github.com/mesosphere/marathon/pull/236) ([drexin](https://github.com/drexin))
- use the most current mesos version in the dockerfile [\#235](https://github.com/mesosphere/marathon/pull/235) ([jhspaybar](https://github.com/jhspaybar))
- Added a framework message event and support for publishing these events ... [\#229](https://github.com/mesosphere/marathon/pull/229) ([marc-barry](https://github.com/marc-barry))
- \#226 Fix proxy discards reponse bodies upon 400 [\#227](https://github.com/mesosphere/marathon/pull/227) ([drexin](https://github.com/drexin))
- Fix for \#185 zookeeper config format different than mesos. necessary? [\#225](https://github.com/mesosphere/marathon/pull/225) ([aquamatthias](https://github.com/aquamatthias))
- \#222 Show apps with empty ports in endpoint api [\#224](https://github.com/mesosphere/marathon/pull/224) ([drexin](https://github.com/drexin))
- \#203 Add PATCH support for updating app instances [\#223](https://github.com/mesosphere/marathon/pull/223) ([drexin](https://github.com/drexin))
- Fix \#114 Process doesn't exit if port is already in use [\#220](https://github.com/mesosphere/marathon/pull/220) ([aquamatthias](https://github.com/aquamatthias))
- Fix for Issue \#165 and \#208 [\#219](https://github.com/mesosphere/marathon/pull/219) ([aquamatthias](https://github.com/aquamatthias))
- Add healthCheckResults to the apps task resource [\#217](https://github.com/mesosphere/marathon/pull/217) ([mattstep](https://github.com/mattstep))
- Add "id" search for feature parity with V1 API [\#216](https://github.com/mesosphere/marathon/pull/216) ([ssorallen](https://github.com/ssorallen))
- Case class module for Jackson [\#215](https://github.com/mesosphere/marathon/pull/215) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Fix \#200 Add version to tasks [\#207](https://github.com/mesosphere/marathon/pull/207) ([BenWhitehead](https://github.com/BenWhitehead))
- Send only editable attributes when updating an App [\#202](https://github.com/mesosphere/marathon/pull/202) ([ssorallen](https://github.com/ssorallen))
- Better handling of invalid requests [\#201](https://github.com/mesosphere/marathon/pull/201) ([guenter](https://github.com/guenter))
- Replace contributors with authors section in README [\#197](https://github.com/mesosphere/marathon/pull/197) ([ssorallen](https://github.com/ssorallen))
- AppDefinition validator now respects random ports [\#196](https://github.com/mesosphere/marathon/pull/196) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Minor cleanup. [\#192](https://github.com/mesosphere/marathon/pull/192) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add mesos\_user option, document CLI options and fix ZK master docs. [\#191](https://github.com/mesosphere/marathon/pull/191) ([gphat](https://github.com/gphat))
- State now stores individual app definition versions instead of appRepositories per app [\#187](https://github.com/mesosphere/marathon/pull/187) ([rbpark](https://github.com/rbpark))
- Validate ports for uniqueness [\#184](https://github.com/mesosphere/marathon/pull/184) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Upgrade to React 0.9.0 [\#179](https://github.com/mesosphere/marathon/pull/179) ([ssorallen](https://github.com/ssorallen))
- Set proper mime type and message on 404 responses. Fixes \#176 [\#178](https://github.com/mesosphere/marathon/pull/178) ([guenter](https://github.com/guenter))
- Automatically upload marathon assets to s3 with shasum [\#177](https://github.com/mesosphere/marathon/pull/177) ([lingmann](https://github.com/lingmann))
- Fix for \#107. Return 404 if tasks to kill cannot be found. [\#173](https://github.com/mesosphere/marathon/pull/173) ([johanatan](https://github.com/johanatan))
- Fix for \#109. Prevents negative integers being specified for number of i... [\#172](https://github.com/mesosphere/marathon/pull/172) ([johanatan](https://github.com/johanatan))

## [marathon-0.4.1](https://github.com/mesosphere/marathon/tree/marathon-0.4.1) (2014-03-07)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.4.0...marathon-0.4.1)

**Implemented enhancements:**

- Supporting Event Subscription Api Endpoints [\#147](https://github.com/mesosphere/marathon/issues/147)
- Give feedback when apps fail to scale to requested ordinality [\#126](https://github.com/mesosphere/marathon/issues/126)
- Feature: Add queued and running tasks to UI [\#118](https://github.com/mesosphere/marathon/issues/118)
- Document API endpoints [\#110](https://github.com/mesosphere/marathon/issues/110)
- Show app status in web UI [\#104](https://github.com/mesosphere/marathon/issues/104)
- Add endpoint to update an app [\#81](https://github.com/mesosphere/marathon/issues/81)
- Overhaul API [\#66](https://github.com/mesosphere/marathon/issues/66)
- Add /help endpoint [\#4](https://github.com/mesosphere/marathon/issues/4)

**Fixed bugs:**

- Assets are cached in the browser across version changes [\#134](https://github.com/mesosphere/marathon/issues/134)
- OpenJDK6 + Ubuntu compile issues? [\#127](https://github.com/mesosphere/marathon/issues/127)
- Inconsistent task statuses when failover timeout reached [\#18](https://github.com/mesosphere/marathon/issues/18)

**Closed issues:**

- POST /v2/apps should return 201 Created [\#167](https://github.com/mesosphere/marathon/issues/167)
- Versioned AppDefinitions [\#164](https://github.com/mesosphere/marathon/issues/164)
- GET /v2/apps/{id}/tasks and GET /v2/tasks returns a text response [\#156](https://github.com/mesosphere/marathon/issues/156)
- SimpleDateFormat chokes on task timestamp pattern in Java 6 [\#153](https://github.com/mesosphere/marathon/issues/153)
- unable to use http callbacks [\#148](https://github.com/mesosphere/marathon/issues/148)
- Port assigned even if app didn't request it [\#138](https://github.com/mesosphere/marathon/issues/138)

**Merged pull requests:**

- Fix for \#167. Return '201 - Created' from POST /v2/apps rather than '204... [\#169](https://github.com/mesosphere/marathon/pull/169) ([johanatan](https://github.com/johanatan))
- Versioned apps [\#166](https://github.com/mesosphere/marathon/pull/166) ([ConnorDoyle](https://github.com/ConnorDoyle))
- README update: terminology and doc links [\#163](https://github.com/mesosphere/marathon/pull/163) ([guenter](https://github.com/guenter))
- Update ZK urls in README for HA mode [\#160](https://github.com/mesosphere/marathon/pull/160) ([gphat](https://github.com/gphat))
- Added event subscriptions endpoint [\#159](https://github.com/mesosphere/marathon/pull/159) ([everpeace](https://github.com/everpeace))
- Immutable AppDefinition [\#158](https://github.com/mesosphere/marathon/pull/158) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Constraint fixes [\#155](https://github.com/mesosphere/marathon/pull/155) ([guenter](https://github.com/guenter))
- use joda-time for \< java 7 compatability [\#154](https://github.com/mesosphere/marathon/pull/154) ([rloomba](https://github.com/rloomba))
- Task list status [\#150](https://github.com/mesosphere/marathon/pull/150) ([ssorallen](https://github.com/ssorallen))
- Fixed the ISO date format settings, regenerated REST docs. [\#149](https://github.com/mesosphere/marathon/pull/149) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Deprecation fixes and task killing / app scaling cleanup [\#145](https://github.com/mesosphere/marathon/pull/145) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Wip running instances [\#144](https://github.com/mesosphere/marathon/pull/144) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Large App modal with all configuration options [\#143](https://github.com/mesosphere/marathon/pull/143) ([ssorallen](https://github.com/ssorallen))
- New app form validation [\#142](https://github.com/mesosphere/marathon/pull/142) ([ssorallen](https://github.com/ssorallen))
- README and REST documentation formatting improvement [\#141](https://github.com/mesosphere/marathon/pull/141) ([lingmann](https://github.com/lingmann))
- Support flags as well as options with values. [\#140](https://github.com/mesosphere/marathon/pull/140) ([solidsnack](https://github.com/solidsnack))
- Allow requests with no ports. Addresses \#138. [\#139](https://github.com/mesosphere/marathon/pull/139) ([solidsnack](https://github.com/solidsnack))
- UI App model validation blocks scale and suspend operations [\#137](https://github.com/mesosphere/marathon/pull/137) ([mohitsoni](https://github.com/mohitsoni))
- Burst Browser Cache for Static Assets [\#135](https://github.com/mesosphere/marathon/pull/135) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add a table of contents to v2 API docs [\#133](https://github.com/mesosphere/marathon/pull/133) ([ssorallen](https://github.com/ssorallen))
- wip-task-reconciliation [\#132](https://github.com/mesosphere/marathon/pull/132) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Replace HTTPie with curl in README, link to API doc [\#130](https://github.com/mesosphere/marathon/pull/130) ([ssorallen](https://github.com/ssorallen))

## [marathon-0.4.0](https://github.com/mesosphere/marathon/tree/marathon-0.4.0) (2014-01-24)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.3.0...marathon-0.4.0)

**Implemented enhancements:**

- Call out required fields in new App form better [\#112](https://github.com/mesosphere/marathon/issues/112)
- Add placement constraints to new app form in UI [\#111](https://github.com/mesosphere/marathon/issues/111)

**Closed issues:**

- Jsx cant build with buildscript [\#121](https://github.com/mesosphere/marathon/issues/121)

**Merged pull requests:**

- REST API V2 [\#129](https://github.com/mesosphere/marathon/pull/129) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Handle escaping/eval in a different way. [\#125](https://github.com/mesosphere/marathon/pull/125) ([solidsnack](https://github.com/solidsnack))
- Compile JS files before running Scala build [\#123](https://github.com/mesosphere/marathon/pull/123) ([ssorallen](https://github.com/ssorallen))
- Capture build dependencies in package.json [\#122](https://github.com/mesosphere/marathon/pull/122) ([ssorallen](https://github.com/ssorallen))
- REST docs [\#120](https://github.com/mesosphere/marathon/pull/120) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Catch `api-v2` up to `master` [\#119](https://github.com/mesosphere/marathon/pull/119) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Catch `api-v2` up to `master` [\#115](https://github.com/mesosphere/marathon/pull/115) ([ConnorDoyle](https://github.com/ConnorDoyle))
- Add "Kill" and "Kill & Scale" buttons for tasks [\#113](https://github.com/mesosphere/marathon/pull/113) ([ssorallen](https://github.com/ssorallen))
- Implement constraint like feature [\#100](https://github.com/mesosphere/marathon/pull/100) ([nguyenvanthan](https://github.com/nguyenvanthan))
- Update App Parameters [\#99](https://github.com/mesosphere/marathon/pull/99) ([ConnorDoyle](https://github.com/ConnorDoyle))

## [marathon-0.3.0](https://github.com/mesosphere/marathon/tree/marathon-0.3.0) (2014-01-08)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.2.1...marathon-0.3.0)

**Implemented enhancements:**

- Show "No tasks" in modal if no tasks running for app [\#95](https://github.com/mesosphere/marathon/issues/95)
- Return client error if a non-existent app id was passed [\#5](https://github.com/mesosphere/marathon/issues/5)

**Fixed bugs:**

- Test fails on Ubuntu 13.04 [\#83](https://github.com/mesosphere/marathon/issues/83)

**Closed issues:**

- Cant get marathon example running on Mesos 0.14.2  [\#94](https://github.com/mesosphere/marathon/issues/94)
- MESOS\_HOME and MESOS\_NATIVE\_LIBRARY settings not mentioned in docs [\#85](https://github.com/mesosphere/marathon/issues/85)
- Dead image in README [\#78](https://github.com/mesosphere/marathon/issues/78)

**Merged pull requests:**

- Simplify some lambdas. [\#106](https://github.com/mesosphere/marathon/pull/106) ([solidsnack](https://github.com/solidsnack))
- Allow clients to pass multiple 0s for fresh ports. [\#103](https://github.com/mesosphere/marathon/pull/103) ([solidsnack](https://github.com/solidsnack))
- Empty task list message [\#96](https://github.com/mesosphere/marathon/pull/96) ([ssorallen](https://github.com/ssorallen))
- Update README.md [\#92](https://github.com/mesosphere/marathon/pull/92) ([rkatti](https://github.com/rkatti))
- Rewrite UI using ReactJS + RequireJS [\#91](https://github.com/mesosphere/marathon/pull/91) ([ssorallen](https://github.com/ssorallen))
- Fix shutdown behavior. [\#88](https://github.com/mesosphere/marathon/pull/88) ([guenter](https://github.com/guenter))
- Adding a table of tasks in the detail view [\#87](https://github.com/mesosphere/marathon/pull/87) ([pyronicide](https://github.com/pyronicide))
- Converting the box UI into a table [\#86](https://github.com/mesosphere/marathon/pull/86) ([pyronicide](https://github.com/pyronicide))
- Scale app in /tasks/kill only if `scale` is true [\#84](https://github.com/mesosphere/marathon/pull/84) ([ssorallen](https://github.com/ssorallen))
- Convey port selection, environment variables, etc. to PathExecutor insta... [\#82](https://github.com/mesosphere/marathon/pull/82) ([davidhoyt](https://github.com/davidhoyt))
- Add a label to the memory field to clarify that it is MB and not GB [\#80](https://github.com/mesosphere/marathon/pull/80) ([benmccann](https://github.com/benmccann))
- Upgrade most dependencies [\#79](https://github.com/mesosphere/marathon/pull/79) ([benmccann](https://github.com/benmccann))

## [marathon-0.2.1](https://github.com/mesosphere/marathon/tree/marathon-0.2.1) (2013-11-23)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.2.0...marathon-0.2.1)

**Closed issues:**

- Docker Trusted Build [\#76](https://github.com/mesosphere/marathon/issues/76)

**Merged pull requests:**

- add Dockerfile for Docker Trusted Build [\#77](https://github.com/mesosphere/marathon/pull/77) ([BrianHicks](https://github.com/BrianHicks))
- Add custom serializer for better handling of constraints [\#74](https://github.com/mesosphere/marathon/pull/74) ([guenter](https://github.com/guenter))
- \[proxying\] Fix DELETE methods [\#73](https://github.com/mesosphere/marathon/pull/73) ([mrdmnd](https://github.com/mrdmnd))
- Improve httpie examples [\#72](https://github.com/mesosphere/marathon/pull/72) ([lingmann](https://github.com/lingmann))
- Added new task search, scale endpoints. [\#71](https://github.com/mesosphere/marathon/pull/71) ([brndnmtthws](https://github.com/brndnmtthws))

## [marathon-0.2.0](https://github.com/mesosphere/marathon/tree/marathon-0.2.0) (2013-11-11)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.1.1...marathon-0.2.0)

**Implemented enhancements:**

- Add endpoint to push changes to apps [\#11](https://github.com/mesosphere/marathon/issues/11)

**Fixed bugs:**

- Marathon continues to try to download resources it can't access [\#19](https://github.com/mesosphere/marathon/issues/19)

**Closed issues:**

- Marathon non-master UI not redirecting to master UI when using --ha flag [\#69](https://github.com/mesosphere/marathon/issues/69)
- Disallow spaces in task names for Marathon [\#46](https://github.com/mesosphere/marathon/issues/46)

**Merged pull requests:**

- Blocking API [\#68](https://github.com/mesosphere/marathon/pull/68) ([guenter](https://github.com/guenter))
- Gracefully handle deserialization exception. [\#65](https://github.com/mesosphere/marathon/pull/65) ([brndnmtthws](https://github.com/brndnmtthws))
- Cluster contraint fix [\#64](https://github.com/mesosphere/marathon/pull/64) ([brndnmtthws](https://github.com/brndnmtthws))
- Accounting fixes [\#63](https://github.com/mesosphere/marathon/pull/63) ([guenter](https://github.com/guenter))
- Rate limiting [\#62](https://github.com/mesosphere/marathon/pull/62) ([guenter](https://github.com/guenter))
- Adding hostname constraints [\#60](https://github.com/mesosphere/marathon/pull/60) ([florianleibert](https://github.com/florianleibert))
- Accounting [\#48](https://github.com/mesosphere/marathon/pull/48) ([brndnmtthws](https://github.com/brndnmtthws))
- Fixed web UI redirection by proxy. [\#42](https://github.com/mesosphere/marathon/pull/42) ([brndnmtthws](https://github.com/brndnmtthws))

## [marathon-0.1.1](https://github.com/mesosphere/marathon/tree/marathon-0.1.1) (2013-10-25)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.1.0...marathon-0.1.1)

**Closed issues:**

- Mesosphere fault tolerant tutorial link is broken [\#54](https://github.com/mesosphere/marathon/issues/54)

**Merged pull requests:**

- Add /v1/tasks to list tasks, and kill them per app and host [\#59](https://github.com/mesosphere/marathon/pull/59) ([guenter](https://github.com/guenter))
- Added 'id' and 'cmd' query praams for app list. [\#58](https://github.com/mesosphere/marathon/pull/58) ([brndnmtthws](https://github.com/brndnmtthws))
- Reduce padding and font-size to use more of the screen [\#57](https://github.com/mesosphere/marathon/pull/57) ([ssorallen](https://github.com/ssorallen))
- Let Mesos generate the framework ID and keep track of it in state. [\#55](https://github.com/mesosphere/marathon/pull/55) ([guenter](https://github.com/guenter))
- Follow symlinks, use nohup, and background marathon [\#53](https://github.com/mesosphere/marathon/pull/53) ([davidhoyt](https://github.com/davidhoyt))
- Accessibility UI Updates [\#52](https://github.com/mesosphere/marathon/pull/52) ([ssorallen](https://github.com/ssorallen))

## [marathon-0.1.0](https://github.com/mesosphere/marathon/tree/marathon-0.1.0) (2013-10-04)
[Full Changelog](https://github.com/mesosphere/marathon/compare/marathon-0.0.2...marathon-0.1.0)

**Implemented enhancements:**

- Add ability to chose the port when launching an app, and choosing n ports vs 1 [\#24](https://github.com/mesosphere/marathon/issues/24)
- Add support to chose app port instead of random assignment [\#22](https://github.com/mesosphere/marathon/issues/22)
- Add REST endpoint to list all host:port for an app [\#10](https://github.com/mesosphere/marathon/issues/10)

**Fixed bugs:**

- Hold on to ports for a while before re-assigning, to avoid collissions [\#21](https://github.com/mesosphere/marathon/issues/21)

**Closed issues:**

- Marathon/Mesos won't launch more than one app despite CPU being available \(i.e 0.1 \< 0.9 \) [\#38](https://github.com/mesosphere/marathon/issues/38)
- MarathonTask's port would be inconsistent to AppDefinition's port with high probability. [\#33](https://github.com/mesosphere/marathon/issues/33)
- JSON output for /v1/endpoints [\#28](https://github.com/mesosphere/marathon/issues/28)
- Marathon dead / zombie tasks [\#26](https://github.com/mesosphere/marathon/issues/26)

**Merged pull requests:**

- Use step timing for cursor blink to save CPU rendering [\#50](https://github.com/mesosphere/marathon/pull/50) ([ssorallen](https://github.com/ssorallen))
- Fix typo [\#49](https://github.com/mesosphere/marathon/pull/49) ([brndnmtthws](https://github.com/brndnmtthws))
- Change STOP to DESTROY and add SUSPEND [\#47](https://github.com/mesosphere/marathon/pull/47) ([ssorallen](https://github.com/ssorallen))
- Fixed $PORTS enviroment variable. [\#45](https://github.com/mesosphere/marathon/pull/45) ([brndnmtthws](https://github.com/brndnmtthws))
- Clean up CSS, make the UI appear in Firefox [\#44](https://github.com/mesosphere/marathon/pull/44) ([ssorallen](https://github.com/ssorallen))
- Initial support for Mesos reservations. [\#43](https://github.com/mesosphere/marathon/pull/43) ([brndnmtthws](https://github.com/brndnmtthws))
- Enable checkpointing [\#40](https://github.com/mesosphere/marathon/pull/40) ([curzonj](https://github.com/curzonj))
- Fix event reporting [\#39](https://github.com/mesosphere/marathon/pull/39) ([guenter](https://github.com/guenter))
- Move to a more functional style for constraints. [\#37](https://github.com/mesosphere/marathon/pull/37) ([solidsnack](https://github.com/solidsnack))
- Multiple ports [\#36](https://github.com/mesosphere/marathon/pull/36) ([guenter](https://github.com/guenter))
- Reserve ports in blocks in order to avoid collisions [\#31](https://github.com/mesosphere/marathon/pull/31) ([russellcardullo](https://github.com/russellcardullo))
- add JSON support for /v1/endpoints \(fixes mesosphere/marathon\#28\) [\#30](https://github.com/mesosphere/marathon/pull/30) ([tpetr](https://github.com/tpetr))
- Reduce over linking of terms in README [\#29](https://github.com/mesosphere/marathon/pull/29) ([ssorallen](https://github.com/ssorallen))
- Fix simple typo in README.md from framwork to framework. [\#27](https://github.com/mesosphere/marathon/pull/27) ([hsaputra](https://github.com/hsaputra))

## [marathon-0.0.2](https://github.com/mesosphere/marathon/tree/marathon-0.0.2) (2013-07-24)
**Implemented enhancements:**

- Support dynamic port allocations [\#13](https://github.com/mesosphere/marathon/issues/13)
- Record app instance host:port tuples in zookeeper so load balancers can read it [\#9](https://github.com/mesosphere/marathon/issues/9)
- Pick a port for each app and set it via the PORT env var [\#8](https://github.com/mesosphere/marathon/issues/8)
- Handle slave failure [\#3](https://github.com/mesosphere/marathon/issues/3)
- CLI first pass [\#2](https://github.com/mesosphere/marathon/issues/2)

**Fixed bugs:**

- Error when running `./bin/start.bash -m localhost:5000` [\#17](https://github.com/mesosphere/marathon/issues/17)
- Fix task updates on re-register [\#16](https://github.com/mesosphere/marathon/issues/16)
- Task queue in scheduler balloons if an app tries to run more instances than resources are available [\#7](https://github.com/mesosphere/marathon/issues/7)
- scale endpoint never scales up if \# of instances was 0 [\#6](https://github.com/mesosphere/marathon/issues/6)

**Closed issues:**

- Demo setup of HAProxy to services [\#15](https://github.com/mesosphere/marathon/issues/15)
- Move all state to Mesos state abstraction [\#1](https://github.com/mesosphere/marathon/issues/1)



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*